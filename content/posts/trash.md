+++
categories = [""]
tags = [""]
title = "Trash"
date = "2020-08-18T15:17:18-07:00"
draft = false
+++

shell - Make `rm` move to trash - Unix & Linux Stack Exchange
https://unix.stackexchange.com/questions/42757/make-rm-move-to-trash/42775

andreafrancia/trash-cli: Command line interface to the freedesktop.org trashcan.
https://github.com/andreafrancia/trash-cli/

* Files in different mounts

Issue 63 in trash-cli: trash-put: trash: cannot trash regular empty file `test': [Errno 13] Permission denied: '/.Trash-1000'
https://groups.google.com/g/trash-cli-devel/c/TtZr53YFxqc?pli=1

#+BEGIN_QUOTE
trash regular empty file `test': [Errno 13] Permission
denied: '/.Trash-1000'
http://code.google.com/p/trash-cli/issues/detail?id=63

Dear Narnie
I think I figured out the problem.

Currently trash-cli always trashes files moving they in a trash directory
of the same volume.

In your case the /tmp/test file belongs to the "/" volume. Unfortunately in
this volume there isn't any trash directory and none can be created (since 
$HOME is on a different volume).

The trash spec address this issue letting the administrator create a
directory with the sticky bit in the $topdir of volumes that should support
trashing.

The following command should solve your issue:

sudo mkdir --mode=1777 /.Trash

Please let me know if works

Andrea
#+END_QUOTE
