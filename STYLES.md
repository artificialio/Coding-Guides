#CSS/SASS Style Guide

##Framework use
Always use some kind of framework that gives you a basis to work with. Preferably compatible with [libsass](https://github.com/sass/libsass). One that we have made very good experiences with is [Foundation](https://github.com/zurb/foundation), which also follows the semantic class naming scheme.

##Structure
The basic structure for small and big projects is almost the same, the two main differences being for small projects we will only have one file for variables and we will probably end up with less files in total.

**For small projects only**

`_variables.scss` - Put all your scss variables, such as colours, etc (see Section Variables) in here

**For large projects only**

`_colors.scss`

`_z-index.scss` - Define all z-index that are used within the projects here and only here. Preferably use numbers starting with 1 and incrementing by 1. For example `$z-index-1: 1;`, `$z-index-2: 2;'`, `$z-index-3: 3;`, etc. This removes any confusion about z-indices as well as using any ridicolous numbers such as `999999`.

`_font-size.scss`

`_line-height.scss`

**General**

`_base.scss` - Only has global/base styling that applyies to html elements such as h1, ul, etc. That are usually font-styling, colour, size, etc.

`components` - The biggest chunk of your SASS code should lie in these `component` files. To understand the principle on how to name these see Naming -> Files

**Optional**

`_utilities.scss` - Contains additional utility classes, such as `padded`, `underlined`, etc. These are classes that are meant to be applied to a range of components, that adds side-wide consistent style changes.


`_mixins.scss` - The place to put any mixins that are used, if any are used.


##Naming
 * **Files**

 * **Classes**

 ##Variables
