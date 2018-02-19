 ## Doktorsjouren theme
## colors
|  color | hex  | opacity | usage |
|--|--|--|--|
| dark-grey| #1f2532 |||
| charcoal-grey | #424243 |||
| label-color | #4a4a4a |||
| slate-grey | #707072 |||
| cool-grey |  #a3a3a5|||
| navgrey |  #f5f6f8 |||
| silver | #d1d1d5  |||
| pale-grey| #dfe4f0 |||
| pale-grey-two | #f1f2f8 |||
| border-grey | #e5e9ec |||
| white | #f8f8f8 |||
| white-two| #fbfbfb |||
| dark-grey-blue | #2f3055 |||
| dark-sky-blue| #26a0d8 ||button (brand-primary)|
| lightblue | #5cbdea || header, button (brand-info)|
| navblue| #72d5e7  |||
| lightish-green | #5fd777 |||
| dark-mint | #53c76a ||button (brand-success)|
| pastel-red | #e26666 ||button (brand-danger)|
| coral| #fa5757  ||button (brand-warning)|
| purple | #a65fe5 |||
| yellow | #f5a623 |||

## typography

| font-family | weight | font-size | usage |
|--|--|--|--|
| sans-serif open-sans|  | 26px, 20px, 18px, 14px, 13px, 12px | h1, h2, h3, h4, h5, h6, base-font |

## Iconography
-   icon-font is generated by `npm run icons` that generates `_icon-font.scss` from SVG images in `doctors/images/`.  
-	icon-font-path :  `"scss/_icon-font/"` Load fonts from this directory.


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
-  User profile images  - min-size  120x68

## npm and build tools
|commands|  |
|--|--|
| gulp watch | compiles everything and watches for changes |
| npm run icons | generates `_icon-font.scss` from SVG images in `doctors/images/` |
