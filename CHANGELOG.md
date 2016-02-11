# Changelog

## 1.0.1 (2016-02-11)

Improvements:

  - updated image-size plugin for better SVG dimension lookup
  - added jshint and jscs for linting

## 1.0.0 (2016-02-10)

Fork from [gulp-compass-imagehelper](https://github.com/phlppschrr/gulp-compass-imagehelper)

Bugfixes:

  - replacing @ for imageInfo.fullname with - due to issues

Improvements:

  - using line instead of block comments to prevent output on Sass compile
  - using hypens instead of underscores
  - using single quotes for strings
  - moved image path prefix into a variable
  - fixed indentation for output
  - removed unused lines
  - always using brackets for conditions in JS
  - removed console.log from svg size detection
  - added pretty notice message if dimension of svg can not be determined
  - set encoding in global variable and use for file content string encoding
  - some code formatting
  - improved mustache template helper functions
  - wrapped every function in mustache template inside a function-exists check

Features:

  - added options to disable placeholder and inline-images
  - updated mustache template to reflect new options