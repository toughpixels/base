# Base Theme

Very basic starter theme for client sites.

# Project Start

1. Make a GitHub repo with the name of the client's site, we're using the example `website`.
    * `hugo new site website`  
    * `cd website`
    * `git init`  
    * `git submodule add https://github.com/toughpixels/base.git themes/base`
    * Update the `config.toml` file and add this line: `theme = "base"`  
1. Update projects that have base installed
   * `git submodule update --init --recursive`
   * `git submodule update --remote --merge`
1. To run a preview site for the theme, run
* `cd themes/base/exampleSite/`
* `hugo serve --themesDir ../..`


Thanks to [Victoria Drake](https://github.com/victoriadrake/hugo-theme-introduction) for the amazing model.

# Project Finish

1. [Generate favicons](https://favicon.io/favicon-generator/) and drop all files into the root of the themes/base/static/ folder
2. Test site speed/SEO/accessiblity in Lighthouse
