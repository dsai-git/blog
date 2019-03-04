DSAI Blog based on Sculpin Blog Skeleton and Argon Design System https://demos.creative-tim.com/argon-design-system/docs/getting-started/overview.html
=====================

Powered by [Sculpin](http://sculpin.io).

# Installation 

1. Install composer https://getcomposer.org/
2. Run "composer install" in blog folder
3. Put contents of assets folder found here: https://github.com/dsai-git/website/tree/master/assets into output_dev/assets folder to see proper styling while you code.

# Development

1. Run dev server: vendor/bin/sculpin generate --watch --server
2. Code away, sculpin docs are located here: https://sculpin.io/getstarted/
3. Actual blogposts are located in /_posts

# Production Deployment

1. Run vendor/bin/sculpin generate --env=prod
2. Copy contents of output_prod to /blog in root of dsai website.

