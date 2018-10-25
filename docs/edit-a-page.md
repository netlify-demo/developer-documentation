---
id: edit-a-page
title: Edit a Page
sidebar_label: Edit a Page
---

To publish a change to this Docusaurus site, all you have to do is:

1. Edit a page in your favorite text editor
2. Create a Git commit on the production branch (`master`)
3. Push the production branch to the origin repo

Netlify will automatically detect the new commit, build the entire website, and
deploy it to a global CDN.


[Diagram showing project in Git repo, editing a page, pushing to origin,
Netlify building the site, and seeing the live changes.]



## 1. Edit a page

Make sure you’ve [set up this project](/docs/getting-started). Then, open up
`/docs/edit-a-page.md`, which is the source for this page, in a text editor.


**Delete or edit this line so you can see that something changed.**


Docusaurus will rebuild the site locally, and you should be able to see the updated
page at <a href='http://localhost:3000/docs/edit-a-page'
target='_blank'>localhost:3000/docs/edit-a-page</a>



## 2. Create a Git commit

Commit the change as you would in any static site generator:

    git commit -a -m "Edited some documentation"



## 3. Push the commit

To publish changes, simply push the branch back to the origin repo that we
created for you on GitHub.

    git push origin

In a few seconds, you should be able to see the updated page on the [live
site]().



## What’s Netlify Doing?

[Not done. Want to highlight the following.]

- Atomic deploy
- Direct to CDN
- No infrastructure
- Customizable build command (any dev docs engine)


[This is where we get to talk about build scripts and how Netlify can work with
any build tool. And about general benefits of continuous deployment and atomic
deploys and CDNs. All the "basic" features of Netlify.]


