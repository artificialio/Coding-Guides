#CSS/SASS Style Guide

##Framework use
Always use some kind of

##Structure
The basic structure for small and big projects is almost the same, the two main differences being for small projects we will only have one file for variables and we will probably end up with less files in total.
`_variables.scss`
**For small projects only** Put all your globally used scss variables (see Section Variables) in here

`_colors.scss`

`_z-index.scss`

`_font-size.scss`

`_line-height.scss`

`_utilities.scss`

`_base.scss`
Only has global/base styling that applyies to html elements such as h1, ul, etc.
That are usually font-styling, colour, size, etc.

`_mixins.scss`
**Optional**

`components`
The biggest chunk of your SASS code should lie in these `component` files. To understand the principle on how to name these see Naming -> Files

##Naming
 * **Files**

 * **Classes**

 ##Variables