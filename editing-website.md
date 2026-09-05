# Editing a Website

## Introduction

The repository in the Github account that has a name ending in *.github.io* will default to being the website. The *main* branch of this repository contains *.html* files, which are sent to any web-browser that connects to the website. The web-browser interprets an html file and displays the contents of that web page.

If it is desired to change the content of a web-page, then it could be done by editing the html file. This is a relatively difficult editing task to perform.

The Github website repository also has a branch labelled *src*, short for *source code*. Everything that makes up a website is stored in the *src* branch. Every time the contents of the *src* changes, then the *Nikola* website generator program automatically runs. Nikola changes the source code in *src* branch to html files in the *main branch*. 

The source code can be written in the *markdown* markup language. This is a language that is easy to learn. Thus it is easy to edit a markdown file whenever changes need to be made to the website.

The folders and files in the *src* branch are:

```
    georgie-web.github.io/
    ├── conf.py
    │
    ├── files
    │   └── assets
    │       └── css
    │           └── custom.css
    │
    ├── images
    │   ├── favicon-fern.png
    │   ├── georgie-2026-07-31-2kx3k.jpg
    │   └── logo.webp
    │
    ├── pages
    │   ├── about.md
    │   ├── contact.md
    │   ├── index.md
    │   └── meeting.md
    │
    └── .github
        └── workflows
            └── main.yml
```

The *image* folder is where more photo images can be stored to be used by web-pages.
The *pages* folder is where the text of each web-page is stored in a *.md, *markdown* file.

There are currently four markdown web-pages:

* index.md. This is the *home page* of the website.
* meeting.md. This is the *Community Clinic* web-page.
* contact.md. This is the *Contact* information web-page.
* about.md. This is the *About* information web-page.

*  
