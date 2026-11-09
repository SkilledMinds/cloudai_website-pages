# CloudAI Website

This repository contains the static website migrated from
[`SkilledMinds/cloudai_website`](https://github.com/SkilledMinds/cloudai_website).
The files formerly under `src/main/webapp` are served from the repository root.

## Deployment

GitHub Pages deploys the site automatically whenever a commit is pushed to
`main`. The deployment workflow is also available to run manually from the
Actions tab. After the first successful deployment, the site is available at:

<https://skilledminds.github.io/cloudai_website-pages/>

## Limitations

GitHub Pages hosts static files only. The Java Servlet application and its
server configuration were not migrated. Contact forms that post to PHP handlers
need a separate form service or backend to submit messages.
