demo_conjugate
==============

Interactively plots the convex conjugate of arbitrary functions

Syntax:

 `demo_conjugate(funcp, xx, gg)`
 *  funcp: function handle to the function you want to plot
 *     xx: x values for the function
 *     gg: x-range of the convex conjugate function (optional)

Examples:
*  `demo_conjugate(@(x)abs(x),-5:0.1:5)` gives
 ![f(x)=|x|](https://raw.github.com/ryotat/demo_conjugate/master/abs.png)
*  `demo_conjugate(@(x)x.*log(x)+(1-x).*log(1-x),0.001:0.001:0.999)` gives
 ![f(x)=xlog(x)+(1-x)log(1-x)](https://raw.github.com/ryotat/demo_conjugate/master/entropy.png)

Copyright: Ryota Tomioka, 2012
