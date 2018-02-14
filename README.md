>## Basic theme configuration

## colors
|  color | hex  |
|--|--|
| gray-base | #000 |
| gray-dark | (#000, 13.5%) |
| gray-darker | (#000, 20%) |
| gray-light | (#000, 46.7%) |
| gray-lighter |  (#000, 93.5%)|
| gray |  (#000, 33.5%) |
| brand-primary | (#428bca, 6.5%)  |
| brand-success| #5cb85c  |
| brand-info | #5bc0de |
| brand-warning | #f0ad4e |
| brand-danger | #d9534f |

## typography

| font-family | weight | font-size | usage |
|--|--|--|--|
| sans-serif |  | 52px, 45px, 30px | h1, h2, h3 |
| serif | bold | 25px | buttons|
| monospace | regular | 16px | base-font|

## Iconography
-	@icon-font-path :  `"../fonts/"` Load fonts from this directory.
-	@icon-font-name : `"glyphicons-halflings-regular"` File name for all font files.
-	@icon-font-svg-id : `"glyphicons_halflingsregular"` Element ID within SVG icon file.

## Grid
- grid-columns - 12
- grid-gutter-width - 30px
- grid-float-breakpoint - screen-sm-min

## Container sizes
- container-sm - 720px + grid-gutter-width
- container-md - 940px + grid-gutter-width
- container-lg - 1140px + grid-gutter-width

## Media queries breakpoints

 - screen-xs - 480px
 - screen-sm - 768px
 - screen-md - 992px
 - screen-lg - 1200px
 
## Images
-  Portfolio - 580x520
-  Large images - 1920x1080
## npm and build tools
|commands|  |
|--|--|
| gulp watch | compiles everything and watches for changes |
| gulp icons | creates svg css in `_icon_sprite.sccs` from svg files in `images/icons/src` |

