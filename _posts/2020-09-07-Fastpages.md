---
title: 'Fastpages'
description:  A post about the blog 
author: John Telford
layout: post
toc: true
comments: true
categories: [Blog, VScode, git, GitHub, Fastpages, GitHub Pages]
---
 
{::comment}
{{site.baseurl}}
{:/comment}

> Warning: Work in Progress!

> This is an opinionated technology blog about technologies of interest to me

Since the early days of the Internet, I have built  blogs from scratch or used   blog technology du jour. This blog is built using [fastpages](https://fastpages.fast.ai), a tool in [fast.ai](https://www.fast.ai/)'s tool kit

How fitting.  The first blog post is about the blog

## Synopsis

-  *fastpages* is not plug and play

- It requires:

    - Experience using *git*

    - Experience using *GitHub*

- The documentation is a guide, not step by step

My experience installing and using *fastpages* was worth while. I have learned things too

## Git, GitHub, GitHub Pages

*Git*, *GitHub*, and *GitHub Pages* are integral to *fastpages*. It relies on *GitHub* for hosting the blog repository, *GitHub Pages* to compile and deploy the blog, and  *GitHub Actions*  for  blog creation  automation

[Git](https://git-scm.com) is a key structural component. It is a distributed version control system designed to track project file changes. It helps answering the questions: Who Changed What, Where, When, and Why? *Git* is responsible for everything *GitHub*-related that happens  on the editing computer.

[GitHub](https://github.com) is an online platform for hosting  versions of most any type of file.  *GitHub* is a platform for storing files in a remote repository. It comes with tools for project collaboration 

[Git Hub Pages](https://pages.github.com) creates and deploys public web pages 

### Some Helpful Resources

[Set up Git](https://docs.github.com/en/github/getting-started-with-github/set-up-git)

[Getting started with GitHub](https://docs.github.com/en/github/getting-started-with-github)

[Git and GitHub in a Nutshell: ](https://dev.to/educative/git-and-github-in-a-nutshell-definitive-tutorial-for-beginners-2i05) Definitive tutorial for beginners

[Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)

# From Edits to Web Blog

The diagram illustrates  creating blog posts from editing to deploying blogs


<img  src="{{site.baseurl}}/images/Fastpages.png" />

<p style="text-align: center;">
    <em>A Process for Creating Fastpages Posts</em>
</p>

## Fastpages Posts

[Fastpages](https://fastpages.fast.ai) supports creating blog post using [Jupyter Notebooks](https://fastpages.fast.ai),  [Markdown](https://guides.github.com/features/mastering-markdown/), and Microsoft Word

*Fastpages* uses [GitHub Pages](https://pages.github.com) to create and deploy blogs. It uses [GitHub Markdown](https://guides.*GitHub*.com/features/mastering-markdown/) for  blog post text. It has some features that other markdown dialects may not have, like commenting out lines of markdown, and supporting embedding HTML

## VScode

[VScode](https://code.visualstudio.com) is  my go-to editor for blog command and control,  text editing, and interfacing with `git` and *GitHub*.   The [Github Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview) extension pack is  convenient  for  previewing  *GitHub* markdown blog posts while typing
 
The *VScode* [Docker Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker) enables  previewing the  entire *fastpages* blog from any `git` branch. This is a much faster and safer way to view the  blog while writing new blog posts without disturbing the the blog public view.  One can be working on several new blog posts on different `git` branches. When a new blog post is ready for public viewing, merge it with the `git` master branch  and  pushing it to the *GitHub* Repository 

## Local Repository

The local repository contains a copy the *GitHub* repository. Contents are edited using *VScode*. The *GitHub* repository is not directly updated. It is updated after edited files are saved, staged, a message is added, and pushed  to the *GitHub* repository

One can use the built-in *VScode* terminal to manually update the *GitHub* repository with the updated files in the local repository. The `git add` command stages the edited  files.  The `git commit -m "message"` command adds the "why" message. The `git push` command pushes the edited files to the *GitHub* repository. I prefer using the *VScode* built-in *git* interface.  It is quicker to push file changes. Microsoft owns both *GitHub* and *VScode*

The local repository is updated with the `git pull` command. It ensures the local repository is  up to date with the *GitHub* repository

## GitHub Chain

*Fastpages* relies on a cast of creative APIs and apps to compile and deploy blogs

*GitHub Repository* -> *Fastpages* -> *GitHub Pages* -> Deploy Blog

*GitHub* notifies *fastpages* after a push from the local repository. *fastpages* prepares the blog for *GitHub Pages* to compile and deploy

{::comment}

## GitHub Pages

- compose blogs on your computer and save it to your local GitHub repository blog repository

- save a copy to the local GitHub repository to the GitHub repository

- GitHub saves all versions of the changes to the repository

- information about who changed what, when, where, and why, is stored in repository 

- *fastpages*  automatically compiles  blog  posting from the repository

- the top of the blog post page has links to the blog About page, a search link for the entire blog,  a link to all blog tags, and a link to the blog home page

 - links to all blog postings are added to the blog home page, with post title, description, and date added to the blog

- clicking a blog posting link opens the posting

- a table of contents is 
shown for each section of the blog post 

{:/comment}

