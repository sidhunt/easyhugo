---
title: "Hugo Setup"
date: 2020-08-17T13:45:18-07:00
draft: false
---

```bash
# use deploy to add commit hugo to gh-pages and push
./deploy.sh

# starting a new repo
rm -rf easyhugo/
hugo new site easyhugo
cd easyhugo/
git init .
git remote add origin https://github.com/frankieliu/easyhugo.git
git push -u origin master
git status
git branch

# from scratch again
rm -rf easyhugo/
git clone https://github.com/frankieliu/easyhugo.git
cd easyhugo/
echo "# easyhugo" >> README.md
git add README.md 
git commit -m"readme"
git push
hugo new site --force .
git add archetypes/
git add config.toml 
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
echo 'theme = "ananke"' >> config.toml
hugo new posts/my-first-post.md
vim content/posts/my-first-post.md 
hugo server

# creating a gh-pages branch
echo "public" >> .gitignore
git checkout --orphan gh-pages
git checkout master
git status
git add .gitignore 
git add content/
git add static/
git add config.toml 
git status
git commit -m"starting"
git push
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push -u origin gh-pages
ls
cd teh
cd ..
git checkout master
cd easyhugo/
git checkout master
rm -rf public
git worktree add -B gh-pages public upstream/gh-pages
git worktree add -B gh-pages public origin/gh-pages
hugo
cd public && git add --all && git commit -m "Publishing to gh-pages" && cd ..
git push -u origin gh-pages
vim deploy.sh
git status
vim deploy.sh 
chmod +x deploy.sh 
./deploy.sh 
ls
hugo server
cd ..
cd hugo/
ls
less config.toml 
cd ..
ls
cd esa
cd easyhugo/
ls
vim config.toml 
./deploy.sh 
hugo server
ls
cd content/posts/
ls
mv ../../static/images/chinese-club-moss.jpg my-first-post/
mkdir my-first-post
mv ../../static/images/chinese-club-moss.jpg my-first-post/
ls
vim my-first-post
vim my-first-post.md 
hugo server
cd ..
hugo server
cd content/posts/
ls
vim my-first-post
vim my-first-post.md 
cd ..
hugo server
bg
ls
cd content/posts/my-first-post/
ls
cd ..
./deploy.sh 
ls
vim config.toml 
./deploy.sh 
hugo server
ls
vim config.toml 
./deploy.sh 
cd static/
ls
vim CNAME
cd ..
ls
cd ..
ls
cd hugo/
ls
less CNAME 
cd ..
cd easyhugo/
ls
./deploy.sh 
git checkout gh-pages 
ls
cd public/
ls
less CNAME 
cd ..
cd static/
ls
rm CNAME 
cd 
jobs
kill %
ls
cd github/
cd easyhugo/
cd static/
ls
cd ..
./deploy.sh 
cd public/
ls
cd ..
ls
cd public/
ls
less index.
less index.html 
cd ..
ls
less config.toml 
hugo server
cd public/
ls
cd posts/
ls
less index.html 
less my-first-post/
ls
cd ..
ls
cd posts/
ls
cd page/
ls
cd 1
ls
cd ..
ls
cd ..
ls
cd ..
ls
vin config.toml 
vim config.toml 
./deploy.sh 
jobs
hugo server 
ls
less config.toml 
cd ..
cd hugo/
ls
less config.toml 
ls
cd layouts/
ls
cd _default/ _
ls
less baseof.html 
diff baseof.html ../../themes/ananke/layouts/_default/baseof.html 
cd ..
ls
cd _g
cd _default/
ls
diff single.html ../../themes/ananke/layouts/_default/
cd ..
ls
cd partials/
ls
cd ..
ls
cd post/
ls
difless single.html 
diff single.html ../../themes/ananke/layouts/post/
diff single.html ../../themes/ananke/layouts/post
diff single.html ../../themes/ananke/layouts/post/
cd ..
ls
cd ..
ls
cd public/
ls
cd ..
ls
cd ..
ls
cd esa
cd easyhugo/
ls
cd content/
ls
cd posts/
ls
mv my-first-post my-first-post1
vim my-first-post.md 
cd ..
ls
cd ..
ls
cd static/
ls
cd images/
ls
cd ..
ls
cd images/
ls
cd ..
ls
cd ..
cd content/
ls
cd posts/
ls

mv my-first-post1/chinese-club-moss.jpg ../../static/images/
hugo server
cd ..
hugo server 
ls
cd content/posts/my-first-post1/
ls
cd ..
ls
vim my-first-post.md 
cd ..
hugo server
cd content/
ls
cd posts/
ls
rm -rf my-first-post
rm -rf my-first-post1
ls
cd ..
ls
cd ..
./deploy.sh 
ls
less config.toml 
vim config.toml 
./deploy.sh 
ls
less config.toml 
vim config.toml 
./deploy.sh 
tree
sudo aptitude install tree
ls
cd content/posts/
ls
cd ..
ls
cdacd ..
cd ..
ls
cd static/images/
ls
cd ..
ls
less config.toml 
vim config.toml 
less config.toml 
vim config.toml 
./deploy.sh 
cd ..
cd hugo/
ls
less config.toml 
cd ..
cd hugo/
ls
less config.toml 
cd ..
cd esa
cd easyhugo/
ls
less config.toml 
vim config.toml 
./deploy.sh 
ls
 2246  git commit -m"adding deploy.sh"
git push
git branch
./deploy.sh 
ls
vim deploy.sh 
./deploy.sh 
git add .
git commit -m"changing upstream to origin"
git push
./deploy.sh 
cd layouts/
ls
cd ..
cd content/
lsc
ls
cd post/
ls
vim my-first-post.md 
cd ..
git status
git add .
git commit -m"remove from draft"
git push
./deploy.sh 
cd themes/
ls
cd ananke/
ls
cd
cd github/
cd easyhugo/
cd themes/
cd ananke/
ls
cd ..
ls
git branch
cd .git
ls
vim config 
cd ..
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
rm -rf themes/ananke/
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
cd .git/
vim config 
git submodule remove  https://github.com/budparr/gohugo-theme-ananke themes/ananke
cd ..
less .gitmodules 
rm .gitmodules 
git submodule remove  https://github.com/budparr/gohugo-theme-ananke themes/ananke
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
ls
cd themes/
ls
cd an
cd ..
ls
rm themes/
rm -rf themes/
ls
cd .git/
l
less config 
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
cd ..
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
ls
cd .git/
ls
cd ..
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
touch .gitmodules
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
git submodule update --remote
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
git status
git rm .gitmodules 
git rm -f .gitmodules 
git status
git add themes 
git status
git commit -m"removing modules"
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
git push
git submodule add  https://github.com/budparr/gohugo-theme-ananke themes/ananke
ls
ls -a
cd .git/
ls
cd ..
ls
mv deploy.sh  ..
mv content/ ..
mv static/ ..
ls
mv config.toml  ..
ls
mv README.md  ..
ls
cd ..
rm -rf easyhugo/
hugo new site easyhugo
mv content/post/my-first-post.md easyhugo/
ls
mv config.toml hugo/
mv README.md hugo/
ls
mv deploy.sh hugo/
mv static/ hugo/
mv static/ easyhugo/
mv hugo/deploy.sh easyhugo/
ls
rmdir content/post/
rmdir content
ls
cd easyhugo/
ls
mkdir content/posts
mv my-first-post.md content/posts/
cd ..
ls
cd hugo/
ls
cd content
ls
cd ..
ls
cd ..
cd easyhugo/
ls
less config.toml 
cd ..
cd hugo/
ls
less config.toml 
mv config.toml  ../easyhugo/
git checkout config.toml
ls
git status
less README.md 
mv README.md  ../easyhugo/
ls
git status
git add content/.sample.md.swp 
git status
git commit -m"delete slp"

git push
cd ..
top
htop
cd easyhugo/
hub create
git init .
hub create
git remote add -f origin https://github.com/frankieliu/easyhugo
git status
git add README.md 
git add archetypes/
git add config.toml 
git add content/
git add deploy.sh 
git add static/
git status
git submodule add git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
ls
hugo server 
ls
echo "public" >> .gitignore
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push upstream gh-pages
git push origin gh-pages
git checkout master
git branch
git checkout master
git checkout -b master
git status
git add .gitignore
git add themes/
git status
git commit -m "first"
git status
ls
cd themes/
ls
git branch
git checkout gh-pages 
git status
cd ..
ls
cd ..
ls
rm -rf easyhugo/
ls
hugo new site easyhugo
dc easyhugo/
cd easyhugo/
git init .
git remote add origin https://github.com/frankieliu/easyhugo.git
git push -u origin master
git status
git branch
cd ..
rm -rf easyhugo/
git clone https://github.com/frankieliu/easyhugo
cd easyhugo/
ls
git branch
git init
echo "# easyhugo" >> README.md
git commit -m"first commit"
git push 
git branch
git remote add origin https://github.com/frankieliu/easyhugo
cd ..
rm -rf easyhugo/
git clone https://github.com/frankieliu/easyhugo.git
cd easyhugo/
ls
echo "# easyhugo" >> README>md
git status
rm README 
rm md 
echo "# easyhugo" >> README.md
git add README.md 
git commit -m"readme"
git push
git branch
hugo init .
hugo new site .
hugo new site --force .
git status
git add archetypes/
git add config.toml 
ls
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
echo 'theme = "ananke"' >> config.toml
hugo new posts/my-first-post.md
vim content/posts/my-first-post.md 
cd static/
ls
mkdir images
cd images/
mv ~/Downloads/chinese-club-moss-huperzine-a1-350x233.jpg chinese-club-moss-huperzine-a1.jpg
mv ~/Downloads/chinese-club-moss.jpg .
ls
rm chinese-club-moss-huperzine-a1.jpg 
cd ..
hugo server
less config.toml 
vim config.toml 
echo "public" >> .gitignore
git checkout --orphan gh-pages
git checkout master
git status
git add .gitignore 
git add content/
git add static/
git add config.toml 
git status
git commit -m"starting"
git push
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Initializing gh-pages branch"
git push -u origin gh-pages
ls
cd teh
cd ..
git checkout master
cd easyhugo/
git checkout master
rm -rf public
git worktree add -B gh-pages public upstream/gh-pages
git worktree add -B gh-pages public origin/gh-pages
hugo
cd public && git add --all && git commit -m "Publishing to gh-pages" && cd ..
git push -u origin gh-pages
vim deploy.sh
git status
vim deploy.sh 
chmod +x deploy.sh 
./deploy.sh 
ls
hugo server
cd ..
cd hugo/
ls
less config.toml 
cd ..
ls
cd esa
cd easyhugo/
ls
vim config.toml 
./deploy.sh 
hugo server
ls
cd content/posts/
ls
mv ../../static/images/chinese-club-moss.jpg my-first-post/
mkdir my-first-post
mv ../../static/images/chinese-club-moss.jpg my-first-post/
ls
vim my-first-post
vim my-first-post.md 
hugo server
cd ..
hugo server
cd content/posts/
ls
vim my-first-post
vim my-first-post.md 
cd ..
hugo server
bg
ls
cd content/posts/my-first-post/
ls
cd ..
./deploy.sh 
ls
vim config.toml 
./deploy.sh 
hugo server
ls
vim config.toml 
./deploy.sh 
cd static/
ls
vim CNAME
cd ..
ls
cd ..
ls
cd hugo/
ls
less CNAME 
cd ..
cd easyhugo/
ls
./deploy.sh 
git checkout gh-pages 
ls
cd public/
ls
less CNAME 
cd ..
cd static/
ls
rm CNAME 
cd 
jobs
kill %
ls
cd github/
cd easyhugo/
cd static/
ls
cd ..
./deploy.sh 
cd public/
ls
cd ..
ls
cd public/
ls
less index.
less index.html 
cd ..
ls
less config.toml 
hugo server
cd public/
ls
cd posts/
ls
less index.html 
less my-first-post/
ls
cd ..
ls
cd posts/
ls
cd page/
ls
cd 1
ls
cd ..
ls
cd ..
ls
cd ..
ls
vin config.toml 
vim config.toml 
./deploy.sh 
jobs
hugo server 
ls
less config.toml 
cd ..
cd hugo/
ls
less config.toml 
ls
cd layouts/
ls
cd _default/
ls
less baseof.html 
diff baseof.html ../../themes/ananke/layouts/_default/baseof.html 
cd ..
ls
cd _g
cd _default/
ls
diff single.html ../../themes/ananke/layouts/_default/
cd ..
ls
cd partials/
ls
cd ..
ls
cd post/
ls
difless single.html 
diff single.html ../../themes/ananke/layouts/post/
diff single.html ../../themes/ananke/layouts/post
diff single.html ../../themes/ananke/layouts/post/
cd ..
ls
cd ..
ls
cd public/
ls
cd ..
ls
cd ..
ls
cd esa
cd easyhugo/
ls
cd content/
ls
cd posts/
ls
mv my-first-post my-first-post1
vim my-first-post.md 
cd ..
ls
cd ..
ls
cd static/
ls
cd images/
ls
cd ..
ls
cd images/
ls
cd ..
ls
cd ..
cd content/
ls
cd posts/
ls

mv my-first-post1/chinese-club-moss.jpg ../../static/images/
hugo server
cd ..
hugo server 
ls
cd content/posts/my-first-post1/
ls
cd ..
ls
vim my-first-post.md 
cd ..
hugo server
cd content/
ls
cd posts/
ls
rm -rf my-first-post
rm -rf my-first-post1
ls
cd ..
ls
cd ..
./deploy.sh 
ls
less config.toml 
vim config.toml 
./deploy.sh 
ls
less config.toml 
vim config.toml 
./deploy.sh 
tree
sudo aptitude install tree
ls
cd content/posts/
ls
cd ..
ls
cdacd ..
cd ..
ls
cd static/images/
ls
cd ..
ls
less config.toml 
vim config.toml 
less config.toml 
vim config.toml 
./deploy.sh 
cd ..
cd hugo/
ls
less config.toml 
cd ..
cd hugo/
ls
less config.toml 
cd ..
cd esa
cd easyhugo/
ls
less config.toml 
vim config.toml 
./deploy.sh 
ls
```

Quick Start | Hugo
https://gohugo.io/getting-started/quick-start/

Host on GitHub | Hugo
https://gohugo.io/hosting-and-deployment/hosting-on-github/

URL Management | Hugo
https://gohugo.io/content-management/urls/

# Image path

Image path - support - HUGO
https://discourse.gohugo.io/t/image-path/1721

Where is the path of images? - support - HUGO
https://discourse.gohugo.io/t/where-is-the-path-of-images/12945

# Github repo baseurl

Githublink helper by SvenDowideit · Pull Request #1398 · gohugoio/hugo
https://github.com/gohugoio/hugo/pull/1398

# Github pages setup

Managing a custom domain for your GitHub Pages site - GitHub Docs
https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site

Managing a custom domain for your GitHub Pages site - GitHub Docs
https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain

# Raw html pages

Add raw html page as post - support - HUGO
https://discourse.gohugo.io/t/add-raw-html-page-as-post/15434/2

masasam/emacs-easy-hugo: Emacs major mode for managing hugo
https://github.com/masasam/emacs-easy-hugo

It is best to do the one above by Masashi Miyauram, html's
don't need anything special

# Creating images

It is nice to be able to just link to a directory called
`posts/post-name-files/` where the `post-name` is the
name of the post, and then when you need to put an 
image use the following:

`post-name-files\somefile.png`

You can refer to this file in the post as

`../post-name-files/somefile.png`

This is simple enought and it collocates the files
next to the post which is kind of nice.

# Adding html to post
Add raw html page as post - support - HUGO
https://discourse.gohugo.io/t/add-raw-html-page-as-post/15434/2

# goldmark-mathjax

Add goldmark-mathjax by xjzsq · Pull Request #7435 · gohugoio/hugo
https://github.com/gohugoio/hugo/pull/7435/files

# server setup

hugo server | Hugo
https://gohugo.io/commands/hugo_server/

# Defining your own navigation menu

Taken from "How to create navigation menus in Hugo" 

Create the following partials: `layouts/partials/nav.html`

```html
<ul>
	{{ range .Site.Menus.mainmenu }}
	<li>><a href="{{ .URL }}">{{ .Name }}</a></li>
	{{ end }}
</ul>
```

Note that in this case the menu is called `mainmenu`.

If you want to display this partial in the header: `layouts/partials/header.html`

```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>{{.Title}} : {{.Site.BaseURL}}</title>
	<link rel="canonical" href="{{ .Permalink }}">
	<link href="https://fonts.googleapis.com/css?family=Muli:400,800" rel="stylesheet">
	<link rel="stylesheet" href="/css/style.css">
</head>
<body>
	<header>
		<div class="wrapper">
			<a href="{{.Site.BaseURL}}" class="sitelogo">My Test Website</a>
			<nav class="header-menu">{{ partial "nav" . }}</nav>
		</div>
	</header>
	<main>
		<div class="wrapper">
```

Now you can add in your front-matter of a content file:

```yaml
menu: mainmenu
```

Another way to add on the menu with a different name:
```yaml
menu:
	mainmenu:
		name: "AnotherName"
```

# Taxonomies

Hierarchical content - HUGO
https://discourse.gohugo.io/t/hierarchical-content/14692

Content Organization | Hugo
https://gohugo.io/content-management/organization/

Taxonomies | Hugo
https://gohugo.io/content-management/taxonomies#readout

Taxonomies | Hugo
https://gohugo.io/content-management/taxonomies/

Archetypes | Hugo
https://gohugo.io/content-management/archetypes/

Gohugo Theme Ananke | Hugo Themes
https://themes.gohugo.io/gohugo-theme-ananke/

What's the concept of the categories taxonomy? - support - HUGO
https://discourse.gohugo.io/t/whats-the-concept-of-the-categories-taxonomy/6486/3

Taxonomies | Hugo
https://gohugo.io/content-management/taxonomies/#hugo-taxonomy-defaults

Add Tags to Your Hugo Blog Using Taxonomies
https://www.jakewiesler.com/blog/hugo-taxonomies

Gohugo Theme Ananke | Hugo Themes
https://themes.gohugo.io/gohugo-theme-ananke/

Implemement Hugo List and Taxonomy Pages | PäksTech
https://www.pakstech.com/blog/hugo-list-page/

About | Notre-Dame de Paris
https://themes.gohugo.io//theme/gohugo-theme-ananke/about/

Menus | Hugo
https://gohugo.io/content-management/menus/

# menus

This is how menus work.

There is default menu at front-page called menu.

Any content that you want to have on the menu add the following:

```yaml
---
title: <sometittle>
date: <somedate>
draft: false
menu:
	mainmenu:
	name:	"About"
---
```
# nav

(459) How to create navigation menus in Hugo - YouTube
https://www.youtube.com/watch?v=E6bhmixcR5k

# hugo configure markup

## turn off unsafe
Configure Markup | Hugo
https://gohugo.io/getting-started/configuration-markup/

# Menus

(460) How to create navigation menus in Hugo - YouTube
https://www.youtube.com/watch?v=E6bhmixcR5k

Menus | Hugo
https://gohugo.io/content-management/menus/#advanced

Menu Templates | Hugo
https://gohugo.io/templates/menu-templates/

# easyhugo

masasam/emacs-easy-hugo: Emacs major mode for managing hugo
https://github.com/masasam/emacs-easy-hugo

# port 1313
Port 1313 already in use (no its not) - support - HUGO
https://discourse.gohugo.io/t/port-1313-already-in-use-no-its-not/11785

# hugo and wsl
Hugo on BashOnWindows (Windows Subsystem for Linux) - support - HUGO
https://discourse.gohugo.io/t/hugo-on-bashonwindows-windows-subsystem-for-linux/3976

Hugo development environment in WSL 2 - Sysadmins of the North
https://www.saotn.org/hugo-development-environment-in-wsl-2/

# content management
Content Formats | Hugo
https://gohugo.io/content-management/formats/

# releases
Releases � gohugoio/hugo
https://github.com/gohugoio/hugo/releases

# hugo extended

Should I use Hugo extended for a new Hugo Project? - HUGO
https://discourse.gohugo.io/t/should-i-use-hugo-extended-for-a-new-hugo-project/13954/9

# baseurl -> use relativeUrl and you are set

absURL | Hugo
https://gohugo.io/functions/absurl/

baseURL messes up link to static files when using hugo as user page (#7) � Issues � GitLab Pages examples / hugo � GitLab
https://gitlab.com/pages/hugo/-/issues/7

# ananke


Gohugo Theme Ananke | Hugo Themes
https://themes.gohugo.io/gohugo-theme-ananke/

# even theme

olOwOlo/hugo-theme-even: ? A super concise theme for Hugo https://hugo-theme-even.netlify.app
https://github.com/olOwOlo/hugo-theme-even

favicon generator - Google Search
https://www.google.com/search?q=favicon+generator

404 page not found - olOwOlo
https://olowolo.com/example-site/post/shortcodes/

# themes

Develop a Theme for Hugo
https://www.zeolearn.com/magazine/develop-a-theme-for-hugo

# netlify
how to deploy github web pages on netlify - Google Search
https://www.google.com/search?q=how+to+deploy+github+web+pages+on+netlify&rlz=1C1CHBF_enUS811US811&oq=how+to+deploy+github+web+pages+on+netlify&aqs=chrome..69i57.11083j0j4&sourceid=chrome&ie=UTF-8

Migrating from GitHub Pages to Netlify: how and why?
http://www.rebeccabarter.com/blog/2017-06-29-website/

# blogdown
1.2 A quick example | blogdown: Creating Websites with R Markdown
https://bookdown.org/yihui/blogdown/a-quick-example.html

Editing blogdown/02-hugo.Rmd at master � rstudio/blogdown
https://github.com/rstudio/blogdown/edit/master/docs/02-hugo.Rmd

