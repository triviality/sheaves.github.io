---
layout: post
title: Title of Post
draft_tag: 
- Tag 1
- Tag 2
---

This is a sample post. It can be viewed [here](http://sheaves.github.io/Sample-Post/){:target="_blank"}. The URL of this post depends on the part of the filename that comes after the date. If you change the filename, the URL of this post will change as well.

It's probably best to copy this file into a new post, instead of editing this directly, so that this can serve as a future reference.

## Front matter

The things in the `---` are the front matter. To make this post your own, change the following things:

  - **Filename**: Filenames should be of the form `YYYY-MM-DD-Title-of-Post.md`. As mentioned above, changing the filename causes the URL of the post to change.
  - **Title**: Self-explanatory
  - **Tags**: You can create your own tags, or use [existing ones](http://sheaves.github.io/topics){:target="_blank"}.

### Drafts

This post is a **draft** post, because it has `draft_tag` in the front matter instead of just `tag`. Draft posts will not appear on the [front page](http://sheaves.github.io/){:target="_blank"}, nor on the Topics or Archive page. No one will know of their existence, except  However, they can be accessed via their URL so that you can preview what it looks like.

To convert a draft post to a normal post, simply remove the `draft_` from `draft_tag` in the front matter. Once that happens, the post will appear on the front page of this site, **as well as on subscribers' feeds**, so be careful! Any new tags you've created will also appear on the Topics page.

## Writing in Markdown

Most standard markdown syntax works. Here's a [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet){:target="_blank"}.

You can also type $\LaTex$ inline, like $x + 2$ or 

$$ \int_0^1 x dx $$

Note empty line before and after the `$$`.

For hyperlinks, I prefer to add `{:target="_blank"}` so that the link opens in a new page, but that's personal preference.

## Writing SageMath code



  

