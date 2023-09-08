---
slug: welcome
title: Welcome
authors: [rehan]
date: 2023-9-07
tags: [facebook, hello, docusaurus]
---

Simply add Markdown files (or folders) to the `blog` directory.

Regular blog authors can be added to `authors.yml`.

Congratulations, you are trying to make your first blog !!

1. See the file name `2023-09-07-greetings.md`, the date will appear on your blog below the title, the other part is just some name to identify your file, so you can name it anything you like

2. Create a similar folder in blog directory when you checkout
   https://github.com/rehan-ssh/thetechtriangle.com

3. When you open the md file

   1. The slug field at the top refers to path that will be appended to the url
   2. The title refer to the heading and the sidebar name
   3. Add yourself to the authors.yml and use that name in author like rehan for example
   4. The tags field refers to on what tags would you like to search this document

4. You can add your images as well refer to
   Feel free to play around and edit this post as much you like.

A blog post folder can be convenient to co-locate blog post images:

## Example of things you can use in blog posts

See the welcome/index.md file and the web together to correlate

### Adding an image

![The Tech Triangle](./logo.svg)

### Adding a tip

:::tip

Use the power of React to create interactive blog posts.

```js
<button onClick={() => alert("button clicked!")}>Click me!</button>
```

<button onClick={() => alert('button clicked!')}>Click me!</button>

:::

Blog posts support [Docusaurus Markdown features](https://docusaurus.io/docs/markdown-features), such as [MDX](https://mdxjs.com/).

Use a `<!--` `truncate` `-->` comment to limit blog post size in the list view at the right

You can read about the plugin at [Docusaurus blogging features](https://docusaurus.io/docs/blog)
