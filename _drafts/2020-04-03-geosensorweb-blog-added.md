---
layout: post
title:  "GeoSensorWeb Lab Blog"
date:   2020-04-03 10:09:57 -0600
published: true
category: geosensorweblab
---

The GeoSensorWeb Lab will from time to time post blog entries.

## Publish

In order for a blog post to be displayed on the site:

* The files should be in the `_posts` folder
* The file names must have the format: `YYYY-MM-DD-dagger-case-title.md`
* YYYY-MM-DD in the file name and date field must be earlier than today's date
   * you can post-date posts this way
* The `published` field in the front matter must be `published: true`
   * you can delay or prevent publishing by making it false until ready
* The extension of the file should correspond to the format
  * markdown: `md` or `markdown`

## Drafts

Editing posts in the `_drafts` folder allows testing of the post before publication.

### Preview

* Change `published: false` front matter entry to `published: true`
* Change the date in the name and the date field to yesterday's date
* Start Jekyll locally with: `bundle exec jekyll serve --drafts`
* View the site at `http://localhost:4000`

