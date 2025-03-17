---
id: my-doc-id
title: My document title
description: My document description
slug: /my-custom-url
---

## Markdown heading

Markdown text with [links](./hello.md)

### Links
<!-- url path -->
Let's see how to [Create a page](/docs/tutorial-basics/create-a-page).
<!-- relative file path -->
Let's see how to [Create a page](./tutorial-basics/create-a-page.md).

### Images
<!-- absolute path -->
![Docusaurus logo](/img/docusaurus.png)
<!-- relative -->
![Docusaurus logo](../static/img/docusaurus.png)

### Code Blocks
```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
  return <h1>Hello, Docusaurus!</h1>;
}
```