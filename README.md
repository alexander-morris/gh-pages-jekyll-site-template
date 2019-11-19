# Github Pages Jekyll Site Template

This sample project contains all the building blocks of a basic site. Fill in your content and run `jekyll serve --incremental` to see it in the browser, or run `jekyll build` to create a post-compiled version in the `docs/` folder. 

## Github Pages Setup

To build this site to Github pages, push it to a new repo and open the 'Settings' tab in the Github web UI. Configure the Github pages settings to use the docs/ folder of the master branch as detailed here: https://pages.github.com/

## File / Directory Structure

`_data/` - this directory contains files for rendering throughout. An Example is provided which works with navigation.html (in `_includes/`) 

`_layouts/` - this is the heart of the project, and contains the different page layout used

`_includes/` - this folder contains chunk elements which can be pulled into page or post content. Navigation.html is provided as an example

`_config.yaml` - this is the core config file and handles things like the output directory, routing, and collection handling

`_sass/` - place precompiled styles here

`_posts/` - this directory will be parsed and rendered into new .html files

`assets/` - this folder is for additional assets such as post-compiled styles, scripts, or images, and will be added directly to the build folder as is

`docs/` - this project is designed for github pages, so we output all builds to the docs/ folder. Do not edit content in this folder as it will be overwritten when Jekyll runs

For more usage and general guidelines be sure to visit https://jekyllrb.com/