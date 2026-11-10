---
title: Pancakes
date: 2021-07
category: product
tags:
  - web
links:
  source: https://github.com/arfct/pancakes
media:
  - src: stack.jpg
    caption: "The sample table of contents in the sidebar, with the document 2021 Milestones open beside it"
    alt: "A Pancakes page with a grey sidebar listing documents and links, and a document titled 2021 Milestones under a banner image of a rabbit eating pancakes"
unconfirmed:
  - date
---

Pancakes is a Google Apps Script web app that presents a set of documents as one site. A Google Doc is the table of contents. Its headings and links become a sidebar, and each linked document opens beside the sidebar.

Google Docs are fetched through the Docs API and drawn as HTML in the page. Sheets, Slides, Figma files, YouTube videos and Drive files open in an embedded frame. A table of contents can set its own colors and CSS.

The README describes deploying Pancakes inside an organization to limit access. A page at gdoc.app, served from GitHub Pages, loads the script in a frame and keeps the document path in the URL.

Google Apps Script and the Google Docs API. 2021.
