# Tabler icon font support for qx applications

## Using the iconfont in your Application

```console
$ qx package update
$ qx package list
$ qx package install oposs/qx-iconfont-tabler
```

To induce the compiler to copy the font file you can either add a 'dummy' call to:

`iconfont.tabler.Load;`

to your appliaction or you can explicitly include the class in the `compile.json` file.

Your app now knows about all the material icons. To access the icons
use names like:

`@TablerIcons/adjustments/40`

The demo app shows a list of all the icons available.

To find the names of the icons, either look at the demo app, or go to https://tabler-icons.io/

## Running the Demo App

This contrib also comes with a demo application.

Just run

```console
$ qx serve
```

