---
id: my-doc-id
title: My document title
description: My document description
slug: /my-custom-url
---

## Markdown heading
Markdown text with [links](./hello.md)

## Links
<!-- url path -->
Let's see how to [Create a page](/docs/tutorial-basics/create-a-page).
<!-- relative file path -->
Let's see how to [Create a page](./tutorial-basics/create-a-page.md).

## Images
<!-- absolute path -->
![Docusaurus logo](/img/docusaurus.png)
<!-- relative -->
![Docusaurus logo](../static/img/docusaurus.png)

## Code Blocks
```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
  return <h1>Hello, Docusaurus!</h1>;
}
```

## Admonitions
:::tip[My tip]

Use this awesome feature option

:::

:::danger[Take care]

This action is dangerous

:::

## MDX and React Components
```jsx
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !
```

export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '20px',
      color: '#fff',
      padding: '10px',
      cursor: 'pointer',
    }}
    onClick={() => {
      alert(`You clicked the color ${color} with label ${children}`)
    }}>
    {children}
  </span>
);

This is <Highlight color="#25c2a0">Docusaurus green</Highlight> !

This is <Highlight color="#1877F2">Facebook blue</Highlight> !