In CSS we use different type of Unit like px, em, rem etc. Now we learn about these unit.

`Pixel`: px is an absolute length. As a beginer, in maximum time we use the pixel. But it is not good practice. Because it break the responsive layout model.

`em`: By using `em` unit we use the relative size of the parent. If the parent we use 16px and in child we use 2em then the child will be 32px.

`rem`: By using `rem` unit we use the relative size of root. Usually it take size from viewport.

`Percentage(%)`: It is relative to the value of the parent element. 100% is the width of the parent element.

`vh`: The full meaning of `vh` is viewport height. If we want the element take the full height of the window then we will use `height: 100vh`.

`vw`: The full meaning of `vh` is viewport widht. If we want the element take the full width of the window then we will use `height: 100vw`.

`vmin` & `vmax`

![[vmin_vmax.png]]

We use `vmin` and `vmax` because of if we use `vw` and `vh` then if we change the orinetation of the device then the value of `vw` and `vh` will be change. But if we use the `vmin` and the `vmax` then the height and width will not change after changing the device orientation.

You can learn about uniy from the site [smazee.com](https://smazee.com/blog/css-units-px-em-rem-vh-vw-vmin-vmax)