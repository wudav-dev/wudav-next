---
title: Python, ML, AI and the rest.
date: '2021-05-02'
tags: ['python']
draft: false
summary: 'Mattis ante odio posuere velit. Suspendisse elementum ipsum augue, quis eleifend libero aliquet in. Fusce ut diam vitae est lacinia tristique. Donec finibus pellentesque ex, et ullamcorper sapien venenatis nec.'
authors: ['zuhaib']
---

# Nested Routes

The blog template supports posts in nested sub-folders. This helps in organisation and can be used to group posts of similar content e.g. a multi-part series. This post is itself an example of a nested route! It's located in the `/data/blog/nested-route` folder.

## How

Simplify create multiple folders inside the main `/data/blog` folder and add your `.md`/`.mdx` files to them. You can even create something like `/data/blog/nested-route/deeply-nested-route/my-post.md`

We use Next.js catch all routes to handle the routing and path creations.

## Use Cases

Here are some reasons to use nested routes

-  More logical content organisation (blogs will still be displayed based on the created date)
-  Multi-part posts
-  Different sub-routes for each author
-  Internationalization (though it would be recommended to use [Next.js built-in i8n routing](https://nextjs.org/docs/advanced-features/i18n-routing))

## Note

-  The previous/next post links at bottom of the template are currently sorted by date. One could explore modifying the template to refer the reader to the previous/next post in the series, rather than by date.