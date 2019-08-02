---
published: false
title: 'Comparing website with designs using Figma + GluePrint'
cover_image: 'https://thepracticaldev.s3.amazonaws.com/i/ru4adz37fdmfaa0oig8u.png'
description: 'Compare your design with the running app/website design using Figma+GluePrint (an alternative to "Pop Out" in Zeplin)'
tags: Design, Figma, Zeplin
---

At Australia Post we use [Figma](https://www.figma.com/features/) to create and share UI designs. In the past we used Sketch+Zeplin which has a really nice feature called ["Pop Out"](https://support.zeplin.io/en/articles/1437093-comparing-app-website-with-designs-using-pop-out). It allows you to overlay the designs on the actually running app/website to really easily see if your code matches the designs. Figma does not have this same feature (as far as I know).

There is a workaround, however, to getting similar functionality in Figma using [GluePrint](http://glueprintapp.com/).

1. Export the design as a PNG (select frame then export as 1x PNG).

2. Open the image in GluePrint. You can change the opacity from GluePrint by scrolling.

3. Open your running app/website and GluePrint will be overlayed on top of it. You can then compare it with the designs to make it pixel perfect!

## Example

![](https://media.giphy.com/media/fqgrhd4447r8jbZ4H3/giphy.gif)

It's not as convenient as Zeplin's Pop Out feature but does the job.

If you have any better ideas please let me know in the comments.

## Found a typo?

If you've found a typo, a sentence that could be improved, or anything else that can be updated on this blog post, you can submit pull request to update the content directly at [the repository](https://github.com/BBlackwo/my-dev.to/blob/master/blog-posts/figma-pop-out/figma-pop-out.md).
