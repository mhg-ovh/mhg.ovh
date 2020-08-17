# mhg.ovh
mhg.ovh static website sources.

## Build & deploy

MKdocs is used to transform Markdown source files to HTML pages.

GitHub Action is used for every push:
- Build: setup Python, install mkdocs + theme and build pages.
- Deploy: sync to S3 bucket and reset CDN cache (Cloudfront invalidation).
