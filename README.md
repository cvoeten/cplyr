# cplyr

R package `dplyr` has some issues:
 * it does not correctly load magrittr; and
 * it will cause problems if plyr is loaded after it.

This package works around these problems by loading plyr, magrittr, and dplyr, in the correct order.

There is no actual code contained within this package.
