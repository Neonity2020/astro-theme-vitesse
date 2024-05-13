---
title: Blog Title
description: A tag field is provided, which can be used to display custom information.
date: 2024-03-01
tag: Tag Text
---

The main content of your article

## h2

The main content of your article

### h3

The main content of your article

#### h4

The main content of your article

##### h5

The main content of your article

###### h6

The main content of your article

Table Style:

| Field | Req | Description |
| :---- | :-- | :-----------|
| NAME | Yes | Displayed in header and footer. Used in SEO and RSS. |
| EMAIL | Yes | Displayed in contact section. |
| NUM_POSTS | Yes | Limit num of posts on home page. |
| NUM_WORKS | Yes | Limit num of works on home page. |
| NUM_PROJECTS | Yes | Limit num of projects on home page. |

Code Snippet:

```ts
export const data = {
  name: 'Name',
  value: 'Value'
}

export function getName() {
  return data.name
}
```