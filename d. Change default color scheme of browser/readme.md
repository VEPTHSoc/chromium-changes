#Changing the theme

In this problem I figured out that I can change the theme color of the browser by going to theme_properties.cc and here I have made some changes too. As I was short on time I figured out that I would replace the default color scheme which is grey with red and used the color_palette.h color values to do so.
You can find the color scheme values in the color_palette.h and some of the custome color schemes as rgb values in theme_properties.cc

I have made changes at
```
src\chrome\browser\themes\theme_properties.cc
```
I have used the color_palette at
```
src\ui\gfx\color_palette.h
```
