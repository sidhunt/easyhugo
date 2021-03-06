+++
categories = [""]
tags = [""]
title = "Vim"
date = "2020-08-18T16:59:35-07:00"
draft = false
+++

# Koans

Vim Kōans | Arabesque
https://sanctum.geek.nz/arabesque/vim-koans/

# Editing
## add files from file

```vim
:r tail -5 file.txt
:r head -5 file.txt
```

vim -- How to read range of lines from a file into current buffer - Stack Overflow
https://stackoverflow.com/questions/240244/vim-how-to-read-range-of-lines-from-a-file-into-current-buffer

## ascii

How To Create ASCII Drawings in Vim Editor (Draw Boxes, Lines, Ellipses, Arrows Inside Text File)
https://www.thegeekstuff.com/2009/12/how-to-create-ascii-drawings-in-vim-editor-draw-boxes-lines-ellipses-arrows-inside-text-file/

How to add ASCII Art around code comment blocks in vim - DEV
https://dev.to/biancapower/how-to-add-ascii-art-around-code-comment-blocks-in-vim-1o1m

boxes - Examples
https://boxes.thomasjensen.com/examples.html

vim-boxdraw in action - asciinema
https://asciinema.org/a/qeig6TH6N4uteq7J6n4epUGaq

(533) Creating technical presentations with VIM - YouTube
https://www.youtube.com/watch?v=GDa7hrbcCB8

Text Mode ASCII-art Box and Comment Drawing in Linux - nixCraft
https://www.cyberciti.biz/tips/unix-linux-draw-any-kind-of-boxes-around-text-editor.html

5 Best ASCII Diagram Tools to Use it With both Online and Desktop ? Itechsoul
https://www.itechsoul.com/5-best-ascii-diagram-tools-to-use-it-with-both-online-and-desktop

JavE - Download
http://www.jave.de/download/download.html

Linux Tips: Fun With the Figlet And Toilet Commands - Linux.com
https://www.linux.com/training-tutorials/linux-tips-fun-figlet-and-toilet-commands/


## clipboard

```vim
"*p
```

Pasting a huge amount of text into vim is slow? - Stack Overflow
https://stackoverflow.com/questions/18258561/pasting-a-huge-amount-of-text-into-vim-is-slow

Difference between vim-gtk and vim-gnome - Ask Ubuntu
https://askubuntu.com/questions/33260/difference-between-vim-gtk-and-vim-gnome

virtual machine - How can I get vim yank to clipboard ("*y) working? - Stack Overflow
https://stackoverflow.com/questions/40709985/how-can-i-get-vim-yank-to-clipboard-y-working

How to copy to clipboard in Vim? - Stack Overflow
https://stackoverflow.com/questions/3961859/how-to-copy-to-clipboard-in-vim

Vim - ArchWiki
https://wiki.archlinux.org/index.php/Vim#Clipboard

## closing buffer

How do I close a single buffer (out of many) in Vim? - Stack Overflow
https://stackoverflow.com/questions/1269648/how-do-i-close-a-single-buffer-out-of-many-in-vim

## closing panes

```vim
Ctrl-W O
```

vim close all panes besides current one - Google Search
https://www.google.com/search?q=vim+close+all+panes+besides+current+one&oq=vim+close+all+panes+besides+current+one&aqs=chrome..69i57.11285j0j7&sourceid=chrome&ie=UTF-8

## cmdline

If you need to do a lot of editing in the command line, it is best to use 

```vim
q:
```

bash - In VIM, how do you delete to end of line while in command mode :? - Super User
https://superuser.com/questions/846854/in-vim-how-do-you-delete-to-end-of-line-while-in-command-mode

Vim documentation: cmdline
http://vimdoc.sourceforge.net/htmldoc/cmdline.html

## comment

How to comment out a block of Python code in Vim - Stack Overflow
https://stackoverflow.com/questions/2561418/how-to-comment-out-a-block-of-python-code-in-vim#:~:text=Step%201%3A%20Go%20to%20the,line%20you%20want%20to%20comment.&text=Step%203%3A%20Shift%20%2D%20I%20%23,be%20modified%20after%20Step%204.)&text=%23%20to%20comment%20your%20lines%20from%20the%20first%20column.

What's a quick way to comment/uncomment lines in Vim? - Stack Overflow
https://stackoverflow.com/questions/1676632/whats-a-quick-way-to-comment-uncomment-lines-in-vim/23063140#23063140
## folding

Creating your own syntax files | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Creating_your_own_syntax_files

Syntax folding of Vim scripts | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Syntax_folding_of_Vim_scripts

Vim Markdown Folding? - Stack Overflow
https://stackoverflow.com/questions/3828606/vim-markdown-folding

Folding | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Folding

Vim tips: Folding fun - Linux.com
https://www.linux.com/training-tutorials/vim-tips-folding-fun/

Is it possible to fold all sections at start time? · Issue #68 · hashivim/vim-terraform
https://github.com/hashivim/vim-terraform/issues/68
Folding | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Folding
## follow links

Ctrl-] : follow link
Ctrl-T : previous topic
Ctrl-O : older location
Ctrl-I : newer location

## insert in command line

vim CTRL_R CTRL_A - Google Search
https://www.google.com/search?q=vim+CTRL_R+CTRL_A&rlz=1C1CHBF_enUS811US811&oq=vim+CTRL_R+CTRL_A&aqs=chrome..69i57.6313j0j7&sourceid=chrome&ie=UTF-8

## macro

vim how to record a macro - Google Search
https://www.google.com/search?q=vim+how+to+record+a+macro&rlz=1C1CHBF_enUS811US811&oq=vim+how+to+record+a+macro&aqs=chrome..69i57.4996j0j7&sourceid=chrome&ie=UTF-8

## open link/file

netrw's "gx" functionality doesn't open URLs anymore in macOS · Issue #4738 · vim/vim
https://github.com/vim/vim/issues/4738

Vim - General - cygwin vim doesn't know app bindings to file exensions?
http://vim.1045645.n5.nabble.com/cygwin-vim-doesn-t-know-app-bindings-to-file-exensions-td5723131.html

Newest 'vim' Questions - Stack Overflow
https://stackoverflow.com/questions/tagged/vim

## panes

How do I change the current split's width and height? - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/514/how-do-i-change-the-current-splits-width-and-height

## registers

@" is the unnamed register where a yank goes to

Vim registers: The basics and beyond
https://www.brianstorti.com/vim-registers/

Vim registers: The basics and beyond
https://www.brianstorti.com/vim-registers/
## shell

It defaults to executing in directory where you started vim.

If you want it to follow the current buffer, then use

```vim
set autochdir
```
Executing a shell command in the parent directory - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/13612/executing-a-shell-command-in-the-parent-directory

curl - Replace vim selection with output of shell command - Stack Overflow
https://stackoverflow.com/questions/6932382/replace-vim-selection-with-output-of-shell-command

how does vi mode work for bash - Google Search
https://www.google.com/search?q=how+does+vi+mode+work+for+bash&rlz=1C1CHBF_enUS811US811&oq=how+does+vi+mode+work+for+bash&aqs=chrome..69i57.4967j0j7&sourceid=chrome&ie=UTF-8

Vi mode in Bash | Arabesque
https://sanctum.geek.nz/arabesque/vi-mode-in-bash/

## snippets

frankieliu/vim-snippets: AsciiDoc, DocBook, Mallard, and RELAX NG snippets for Vim
https://github.com/frankieliu/vim-snippets

SirVer/ultisnips: UltiSnips - The ultimate snippet solution for Vim. Send pull requests to SirVer/ultisnips!
https://github.com/SirVer/ultisnips

UltiSnips - default location for snippets seems to be current directory? : vim
https://www.reddit.com/r/vim/comments/4qnq70/ultisnips_default_location_for_snippets_seems_to/

-romainl- (u/-romainl-) - Reddit
https://www.reddit.com/user/-romainl-

how to update vim documentation vim directory - Google Search
https://www.google.com/search?rlz=1C1CHBF_enUS811US811&sxsrf=ALeKk03YcAh6rNZNjhu5L0IW1uzCFffYJQ%3A1599525066529&ei=ytBWX8zwH4f0-gSvqJbgAg&q=how+to+update+vim+documentation++vim+directory&oq=how+to+update+vim+documentation++vim+directory&gs_lcp=CgZwc3ktYWIQAzoECAAQRzoHCCMQsAIQJzoGCAAQBxAeOgYIABAIEB46CAgAEAgQBxAeOgQIIRAKUNw7WMyMAWD5jgFoEHABeACAAV6IAdUWkgECMziYAQCgAQGqAQdnd3Mtd2l6wAEB&sclient=psy-ab&ved=0ahUKEwjM_Zibp9jrAhUHup4KHS-UBSwQ4dUDCA0&uact=5

ultisnips/UltiSnips.txt at 4eac9798885f508d388d07847946a925dea583a5 � SirVer/ultisnips
https://github.com/SirVer/ultisnips/blob/4eac9798885f508d388d07847946a925dea583a5/doc/UltiSnips.txt#L368-L406

Vim 101: runtimepath | by Alex R. Young | usevim | Medium
https://medium.com/usevim/vim-101-runtimepath-83194d411b0a#:~:text=Vim%20looks%20for%20scripts%20and,by%20the%20'runtimepath'%20option.&text=This%20is%20used%20to%20locate,plugins%20that%20ship%20with%20Vim.

honza/vim-snippets: vim-snipmate default snippets (Previously snipmate-snippets)
https://github.com/honza/vim-snippets

Vim Ultisnips - How do I move to the next placeholder or tabstop? - Stack Overflow
https://stackoverflow.com/questions/19039443/vim-ultisnips-how-do-i-move-to-the-next-placeholder-or-tabstop

how to set filetyle vim - Google Search
https://www.google.com/search?q=how+to+set+filetyle+vim&rlz=1C1CHBF_enUS811US811&oq=how+to+set+filetyle+vim&aqs=chrome..69i57.4057j0j7&sourceid=chrome&ie=UTF-8

## stay in visual mode

Vim: how to stay in visual mode after executing a command - Stack Overflow
https://stackoverflow.com/questions/4711079/vim-how-to-stay-in-visual-mode-after-executing-a-command

keyboard shortcuts - Vim visual mode, stay selected - Super User
https://superuser.com/questions/115038/vim-visual-mode-stay-selected

### how to do it
gv 


Is there a way to reselect the last visual shape, rather than the last actual selection, starting at the current cursor position? - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/5750/is-there-a-way-to-reselect-the-last-visual-shape-rather-than-the-last-actual-se

vim what does 1v do? - Google Search
https://www.google.com/search?q=vim+what+does+1v+do%3F&rlz=1C1CHBF_enUS811US811&oq=vim+what+does+1v+do%3F&aqs=chrome..69i57.4371j0j7&sourceid=chrome&ie=UTF-8

## tabs and buffers

editor - Using Vim's tabs like buffers - Stack Overflow
https://stackoverflow.com/questions/102384/using-vims-tabs-like-buffers

## uppercase

Changing case in Vim - Stack Overflow
https://stackoverflow.com/questions/2946051/changing-case-in-vim#:~:text=2%20Answers&text=Visual%20select%20the%20text%2C%20then,gu%20for%20lowercase.

~    : Changes the case of current character
guu  : Change current line from upper to lower.
gUU  : Change current LINE from lower to upper.
guw  : Change to end of current WORD from upper to lower.
guaw : Change all of current WORD to lower.
gUw  : Change to end of current WORD from lower to upper.
gUaw : Change all of current WORD to upper.
g~ ~  : Invert case to entire line
g~w  : Invert case to current WORD
guG : Change to lowercase until the end of document.


## vim script
About | Arabesque
https://sanctum.geek.nz/arabesque/about/

(1) Tom Ryder | LinkedIn
https://www.linkedin.com/in/tom-ryder-tejrnz/

# Modes
## buffer

Vim: Changing Buffer Numbers - Stack Overflow
https://stackoverflow.com/questions/4545294/vim-changing-buffer-numbers

## syntax highlight

Turn on syntax highlighting for vim on Mac OS | Codexpedia
https://www.codexpedia.com/text-editor/turn-on-syntax-highlighting-for-vim-on-mac-os/#:~:text=By%20default%2C%20Mac%20OS%20doesn,it%20doesn't%20already%20exist.

Vim clear last search highlighting - Stack Overflow
https://stackoverflow.com/questions/657447/vim-clear-last-search-highlighting/25569434#25569434

## hugo

Too basic...

robertbasic/vim-hugo-helper: A small Vim plugin with a set of helpers for Hugo https://gohugo.io
https://github.com/robertbasic/vim-hugo-helper

## org mode for vim

jceb/vim-orgmode: Text outlining and task management for Vim based on Emacs' Org-Mode
https://github.com/jceb/vim-orgmode

vim-orgmode/orgguide.txt at master · jceb/vim-orgmode
https://github.com/jceb/vim-orgmode/blob/master/doc/orgguide.txt

## nerdtree
preservim/nerdtree: A tree explorer plugin for vim.
https://github.com/preservim/nerdtree
## markdown

plasticboy/vim-markdown: Markdown Vim Mode
https://github.com/plasticboy/vim-markdown#options

plasticboy/vim-markdown: Markdown Vim Mode
https://github.com/plasticboy/vim-markdown
## python

Running Python code in Vim - Stack Overflow
https://stackoverflow.com/questions/18948491/running-python-code-in-vim

## visual

Vim: faster way to select blocks of text in visual mode - Stack Overflow
https://stackoverflow.com/questions/7406949/vim-faster-way-to-select-blocks-of-text-in-visual-mode#:~:text=v%20puts%20you%20in%20select,beginning%20of%20the%20next%20paragraph.&text=This%20selects%20the%20current%20line%20and%20the%20next%2Fprevious%20n%20lines.

Vim expand selection by a paragraph - Stack Overflow
https://stackoverflow.com/questions/57498501/vim-expand-selection-by-a-paragraph

## opening browser

Open a URL from Vim - Today I Learned
https://til.hashrocket.com/posts/69e7479ab9-open-a-url-from-vim#:~:text=If%20you%20have%20Vim%20and,file%20handler%3B%20open%20for%20OSX.

How do I "open with Vim" using windows subsystem for linux? - Stack Overflow
https://stackoverflow.com/questions/49888546/how-do-i-open-with-vim-using-windows-subsystem-for-linux

vim - Setting netrw like NERDTree - Stack Overflow
https://stackoverflow.com/questions/5006950/setting-netrw-like-nerdtree

how to configure netrw wslview - Google Search
https://www.google.com/search?q=how+to+configure+netrw+wslview&rlz=1C1CHBF_enUS811US811&oq=how+to+configure+netrw+wslview&aqs=chrome..69i57.8010j0j4&sourceid=chrome&ie=UTF-8

setting netrw did not work

However Ctrl_R Ctrl_A does work

# plugins
## install

Installing Vim(8) plugins with the native pack system | by Paulo Diovani | Medium
https://medium.com/@paulodiovani/installing-vim-8-plugins-with-the-native-pack-system-39b71c351fea#:~:text=vim%2Fpack%20is%20considered%20a,user%20with%20the%20command%20%3Apackadd.

Release NVIM 0.5.0 � neovim/neovim
https://github.com/neovim/neovim/releases/tag/nightly

What's the difference between installing 32bit or 64bit apps on a 64bit Windows? - Stack Overflow
https://stackoverflow.com/questions/4077885/whats-the-difference-between-installing-32bit-or-64bit-apps-on-a-64bit-windows#:~:text=32bit%20operating%20systems%20can%20allocate,you%20have%20more%20than%204GB.

Is there vim plugin for notepad++? - Stack Overflow
https://stackoverflow.com/questions/12817027/is-there-vim-plugin-for-notepad

FAQ � neovim/neovim Wiki
https://github.com/neovim/neovim/wiki/FAQ#how-to-use-the-windows-clipboard-from-wsl

## alternatives

Vim: So long Pathogen, hello native package loading | George Ornbo
https://shapeshed.com/vim-packages/

plugin system - What is the Vim8 package feature and how should I use it? - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/9522/what-is-the-vim8-package-feature-and-how-should-i-use-it

## details
```bash

mkdir -p ~/.vim/pack/plugins/start
cd ~/.vim/pack/plugins/start

git submodule add <github> vim-<package name>
# optional:
# I like to prepend all package names with vim-

# if .zip or .vimball (:so %)
# need to move the files generated to
# a folder under ~/.vim/pack/plugins/start

cd vim-<package name>/docs # or doc
vim-helptags.sh .     # script is below
```

## generating tags

```vim
:helptags <directory>
```

Vim helptag generation - Stack Overflow
https://stackoverflow.com/questions/4180590/vim-helptag-generation

I wrote a little shell script to help with the tags

```bash
#!/bin/bash
vim -u NONE -c "helptags $$1" -c q
```

## markdown-preview

markdown-preview.nvim/test.md at master � iamcco/markdown-preview.nvim
https://github.com/iamcco/markdown-preview.nvim/blob/master/test/test.md

# keymappings
## summary

Use ~.vim/ftplugin/org.vim~ and add any mappings there

```vim
nnoremap <buffer> <localleader>np q:i! cd ../..; hugo new content/posts/.org<Esc>hhhi
```

Understand Vim Mappings and Create Your Own Shortcuts! | by Jonas B. Rossi |
vim drops | Medium
https://medium.com/vim-drops/understand-vim-mappings-and-create-your-own-shortcuts-f52ee4a6b8ed

Vim documentation: map
http://vimdoc.sourceforge.net/htmldoc/map.html#{lhs}

Mapping keys in Vim - Tutorial (Part 2) | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Mapping_keys_in_Vim_-_Tutorial_(Part_2)

## conditional mapping

key bindings - File Type dependent key mapping - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/10664/file-type-dependent-key-mapping

key bindings - File Type dependent key mapping - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/10664/file-type-dependent-key-mapping

How to set conditional mappings in VIM (ie: depending on the extension of a file)? - Stack Overflow
https://stackoverflow.com/questions/13673424/how-to-set-conditional-mappings-in-vim-ie-depending-on-the-extension-of-a-file

## leader

```vim
set Leader='\'
```

Can you have different localleaders for different Vim plugins? - Stack Overflow
https://stackoverflow.com/questions/12076227/can-you-have-different-localleaders-for-different-vim-plugins

Leaders / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/chapters/06.html

vim - What is the <leader> in a .vimrc file? - Stack Overflow
https://stackoverflow.com/questions/1764263/what-is-the-leader-in-a-vimrc-file

## recursive

Recursive mappings | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Recursive_mappings

# vimscript

## tutorial

Autoloading / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/chapters/53.html

Preface / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/preface.html

https://stevelosh.com
https://stevelosh.com/

## conditionals

Conditionals / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/chapters/21.html

vimscript - Why am I getting a "E488: Trailing characters" error on this custom command? - Vi and Vim Stack Exchange
https://vi.stackexchange.com/questions/4689/why-am-i-getting-a-e488-trailing-characters-error-on-this-custom-command

## echo messages

Echoing Messages / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/chapters/01.html

## open url
Open URL under cursor in Vim with browser - Stack Overflow
https://stackoverflow.com/questions/9458294/open-url-under-cursor-in-vim-with-browser

## silent disable enter
How do I disable the "Press ENTER or type command to continue" prompt in Vim? - Stack Overflow
https://stackoverflow.com/questions/890802/how-do-i-disable-the-press-enter-or-type-command-to-continue-prompt-in-vim

# filetype

Vim documentation: filetype
http://vimdoc.sourceforge.net/htmldoc/filetype.html

vim - How to get 'filetype' of a buffer specified by a number? - Stack Overflow
https://stackoverflow.com/questions/18714650/how-to-get-filetype-of-a-buffer-specified-by-a-number

# hidden write on change

set hidden : so that vim doesn't ask you to write out everytime you change
buffers

Vim buffer FAQ | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Vim_buffer_FAQ#hidden

# save files

How to save a file with a new name in VIM while switching to that new buffer (and closing the original) - Stack Overflow
https://stackoverflow.com/questions/31092505/how-to-save-a-file-with-a-new-name-in-vim-while-switching-to-that-new-buffer-an

vi - Renaming the current file in Vim - Stack Overflow
https://stackoverflow.com/questions/1205286/renaming-the-current-file-in-vim

How to save as a new file and keep working on the original one in Vim? - Stack Overflow
https://stackoverflow.com/questions/4980168/how-to-save-as-a-new-file-and-keep-working-on-the-original-one-in-vim


vim what does a ! mean in front of function - Google Search
https://www.google.com/search?q=vim+what+does+a+!+mean+in+front+of+function&rlz=1C1CHBF_enUS811US811&oq=vim+what+does+a+!+mean+in+front+of+function&aqs=chrome..69i57.9362j0j4&sourceid=chrome&ie=UTF-8

Potion Section Movement / Learn Vimscript the Hard Way
https://learnvimscriptthehardway.stevelosh.com/chapters/51.html

Set options or named registers with let | Vim Tips Wiki | Fandom
https://vim.fandom.com/wiki/Set_options_or_named_registers_with_let


