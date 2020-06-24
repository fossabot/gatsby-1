<!-- ix-docs-ignore -->

![imgix logo](https://assets.imgix.net/sdk-imgix-logo.svg)

This is a library to make the interaction between Gatsby and [imgix](https://www.imgix.com/) far simpler.

---

<!-- /ix-docs-ignore -->

# Roadmap

**📣 Have your say on our roadmap below!**

Hey there! Thanks for checking out this repository. We are currently deciding on the roadmap for this library, and we'd love your help in showing us what to prioritize, and what you'd like us to build. If you're interested, read on!

Below is a list of issues that contain all the high-level use-cases that we thought apply to Gatbsy developers using imgix. Please check out any issues that are interesting, and **help us decide what to build first by voting on those issues that best fit your use case.**

- [I have an image stored in an imgix source (e.g. Amazon S3/GCP) that I want to display using gatsby-image](https://github.com/imgix/gatsby/issues/1)
- [I want to display imgix images with gatsby-image's lazy-load and blur-up features](https://github.com/imgix/gatsby/issues/2)
- [I have an image provided from a Gatsby source that I’d like to transform through imgix](https://github.com/imgix/gatsby/issues/3)
- [I have an image provided from a Gatsby source that I’d like to transform through imgix **and display using gatsby-image**](https://github.com/imgix/gatsby/issues/4)
- [I have an image stored in image manager that I want to render](https://github.com/imgix/gatsby/issues/6)
- [I have an image stored locally that I want to upload to image-manager and render](https://github.com/imgix/gatsby/issues/7)

Other features:
- [I want to have my imgix parameters in my Gatsby/GraphQL query be strongly-typed](https://github.com/imgix/gatsby/issues/5)

# Why use imgix with Gatsby?

Integrating imgix with Gatsby provides a few key advantages over the core image experience in Gatsby:

1. Access to imgix's best-in-class CDN. imgix has invested significant time and effort into a world-leading CDN, which ensures images are delivered your website's customers as quick as possible
2. Access to imgix's suite of transformations and optimizations. imgix has a larger variety of image transformations than are possible with the built in Gatsby system. Furthermore, we are continuously improving our image optimization to push the boundaries of image performance.
3. Better responsiveness than Gatsby. Since we offload the image rendering to our cloud, rather than the developer's device, we are able to create far more derivative images at different resolutions, resulting in better responsive image performance, meaning faster load times and less bandwidth usage for your users.
4. Faster time-to-awesome. imgix offers a set of default optimizations which allow you to achieve outstanding image quality which still keeping image size small, and allows you to focus on other aspects of your website.


