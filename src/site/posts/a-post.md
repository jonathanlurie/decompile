---
title: A post page
date: 2018-03-21
excerpt: This is the excerpt of 'a post'
cover: /images/cover1.jpg
---

There's not much here in the sample post page. Better get to work.

![](/images/cover1.jpg)

The common front-matter data for all of the files in the posts section are abstracted into a `posts.json` file so that we don't need to repeat that on every file. Handy.

It looks like this:

```js
{
  "layout" : "layouts/post.md",
  "tags" : "post",
  "templateEngineOverride": "njk,md"
}
```


