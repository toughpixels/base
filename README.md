# Base Theme

Very basic starter theme for client sites.

# Project Start

1. Make a GitHub repo with the name of the client's site, we're using the example `website`.
    * `hugo new site website`  
    * `git init`  
    * `cd website`
    * `git submodule add https://github.com/toughpixels/base.git themes/base`
1. Update projects that have base installed
   * `git submodule update --init --recursive`
   * `git submodule update --remote --merge`


# Project Finish

1. [Generate favicons](https://favicon.io/favicon-generator/) and drop all files into the root of the themes/base/static/ folder
2. Test site speed/SEO/accessiblity in Lighthouse
