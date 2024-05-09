# Cloudflare Image Resizing worker for WordPress
 Rewrites images on the fly so you can use the [Cloudflare Image Resizing](https://blog.cloudflare.com/announcing-cloudflare-image-resizing-simplifying-optimal-image-delivery/) service.

Forked from https://github.com/Mecanik/cloudflare-image-resizing-worker.

 Source article: [Cloudflare Image Resizing for WordPress](https://mecanik.dev/en/posts/cloudflare-image-resizing-for-wordpress/).

## Current features
* Rewrites all src and srcset tags
* Rewrites all div tags with style, data-ultimate-bg, data-image-id attributes
* Rewrites all link tags for icons
* Rewrites all href tags for light boxes
* Rewrites all background image URLs for all inline CSS
* Rewrites all background image URLs for all external CSS
