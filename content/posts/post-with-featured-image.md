+++
title = "Post With Featured Image"
tags = [
    "go",
    "golang",
    "templates",
]
date = "2018-04-02"
+++

Just define the image URL in the content’s front matter, the featured image will be displayed as the background. 

For example:

```yaml
---
images:
  - https://picsum.photos/1024/768/?random
---
```

This is an array, you can set multiple urls, only the first url will be used. These images is also used in [Twitter Cards](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/guides/getting-started.html) and the [Open Graph](http://ogp.me/) metadata.
