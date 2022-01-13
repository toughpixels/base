# Base Theme

Basic starter theme for Hugo client sites.

# Project Start

Make a GitHub repo with the name of the client's site, we're using the example `website`.
    * `hugo new site website`  
    * `cd website`
    * `git init`  
    * `git submodule add git@github.com:toughpixels/base.git themes/base`
    * Copy the example site to your project directory: `cp -r themes/base/exampleSite/* .`

## Editing Base

To run a preview site for the theme, run
* `cd exampleSite/`
* `hugo serve --themesDir ../..`

## Cloning an Existing Project

To clone the submodule code for an exisitng project, run:
`git clone --recurse-submodules git://github.com/toughpixels/SITE.git`

Or, if you've already cloned the repo, run commands to pull and start submodule.
`git submodule update --init`


## Updating a Submodule
Simply run `git submodule update` to get the latest version.

You can also: 
```
cd themes/base
git pull
```

Thanks to [Victoria Drake](https://github.com/victoriadrake/hugo-theme-introduction) for the amazing model.
