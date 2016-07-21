# bootstrap-tutorial

## Grid system
* 12 column grid
* accessed through CSS classes
* concepts
** containers
** rows
** columns

## Containers
Special class that allows you to control layout, which automatically adds padding. So, if you want the full widht, do not put it in a container.

## Fixed and Fluid Containers

Fluid will always adjust to the size of the device.
* has 15 pixel padding

Fixed-Width will show a specific size depending on the size of the viewport.
* also has 15 pixel padding
* adjusts to media query breakpoints

## Rows
* Horizontal groups of containers
* Placed within a container
* should always include columns when using rows
* rows get rid of padding using negative margins within a container, basically setting up the container for columns which will add gutters

## Columns
* 30px gutters, 15 on each side
* Use col-SIZE-SPAN
** SIZE is two letters, meaning when the column will convert to a single column stack
** number of columns to span
* >12 columns will wrap

Column metrics:
xs: < 768px
xm: >= 768px
md: >= 992px
lg: >= 1200px