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

* *index.md*. This is the *home page* of the website.
* *meeting.md*. This is the *Community Clinic* web-page.
* *contact.md*. This is the *Contact* information web-page.
* *about.md*. This is the *About* information web-page.

## Example of editing a change to the website.

Currently the *meeting.md* file contains the text: 

Please come to my *Community Clinics* ... on the first Friday of the each month.

If this is to be changed to the second Thursday of each month then the *meeting.md* file is edited and the text becomes:

Please come to my *Community Clinics* ... on the second Thursday of the each month.

After editing the change to the text you must then click on the button *Commit changes...*. The change to the file occurs, and then the *main.yml* script in the folder .github/workflow/ starts to execute. This runs the Nikola website building program which resides in an account on Github. The Nikola program converts all the source code files in the *Src* branch to be html files in the *main* branch. This takes 3 to 5 minutes. The website has now been re-built with the changes implemented. Upon refreshing the web-browser the web-site will show the *Community Clinics* web-page has the text:  

Please come to my *Community Clinics* ... on the second Thursday of the each month.

An advantage of having the website automatically rebuild itself after the changes made using a web-browser, is that the change can be made from anywhere in the world. i.e. You are *not* obliged to go home and use your PC at home to make the changes and then upload the changes to the web-site.

## Additional Files

The *conf.py* file. This is a Python programming language file that configures the web-site. For example configuration the buttons on the navigation panel is performed by editing this file. 

The *custom.css* file. This is a Cascading Style Sheets language. It is used to add features to all the website. For example, setting the colour of the navigation buttons to be red.







