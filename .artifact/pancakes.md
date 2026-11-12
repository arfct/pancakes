---
title: Pancakes
date: 2021-07
category: product
tags:
  - web
url: https://gdoc.app
links:
  source: https://github.com/arfct/pancakes
media:
  - src: stack.jpg
    caption: "The sample table of contents as the sidebar, with the document 2021 Milestones open beside it"
    alt: "A Pancakes page with a grey sidebar listing documents and links, and a document titled 2021 Milestones under a banner image of a rabbit eating pancakes"
unconfirmed:
  - date
---

The grey sidebar in the image is a Google Doc. Pancakes, a Google Apps Script web app, takes one document as a table of contents, turns its headings and links into that sidebar and opens each linked document beside it, so that a set of documents reads as one site.

Google Docs are fetched through the Docs API and redrawn as HTML in the page. Sheets, Slides, Figma files, YouTube videos and Drive files open in an embedded frame. Settings are typed into a document as its last line. When that line is JSON, Pancakes reads a background color, a text color or CSS from it and leaves the line out of the page.

The README describes deploying Pancakes inside an organization to limit who can open it. A page at gdoc.app, served from GitHub Pages, loads the script in a frame and keeps the path of the open document in its own address.

Google Apps Script and the Google Docs API. 2021.
