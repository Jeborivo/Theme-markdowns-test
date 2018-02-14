
> ## Feiring theme

## Basic theme configruation
**Colors:**

| color       | hex           | opacity  |usage ||
| ------------- |:-------------:| -----:|-----:|-----:|
| white | fff |  ||
| near-white | f2f2f2 |  ||
| gray-lightest | e5e5e5 |  ||
| gray-lighter | ccc |  ||
| gray-light | 999 |  ||
| gray | 666 |  ||
| gray-dark | 4c4c4c |  ||
| gray-darker | 333 |  ||
| black | 000 |  ||
| wisp-pink | fdf0f1 |  ||
| flamingo | ee4037 | 0.5 |frontpage cards, kontakt section, tile background|
| black-squeeze | e4eff5 |  |pukk business area (cards section background), pukk products (products and prices)|
| congress-blue | 014a81 | 0.5 |pukk business area (hero, products, card-large, cards,  card links)|
| aths-special | e6edce |  |Mobile knusig business area (cards section background, order)|
| saratoga | 44530e | 0.5 |Mobile knusig business area (hero, buttons, kontakt, card-large, cards, card links)|
| whisper | eeeef6 |  |Massemotak business area (cards section background)|
| martinique | 3f3550 | 0.5 | Massemotak business area (hero, products, card-large, cards, card links, kontakt)|
| ebb | e9e4e0 |  |Asfalt business area ( cards section background) Asfalt product (product)|
| taupe | 43362d | 0.5 |Asfalt business area (hero, products, card-large, cards, card links, kontakt)|
| fantasy | faf2f0 |  | Tentex business area (cards section background) |
| irish coffee | 663024 | 0.5 | Tentex business area (hero, products, card-large, cards, card links, kontakt)|
| tundora | 493e3f |  |frontpage cards-large |
| linen | fceeed |  |cards section background|
| mine shaft | 212121 |  |site footer background|


## Typography :

| font family   | font weight   | font size  |usage ||
| ------------- |:-------------:| -----:|-----:|-----:|
| Gotham | bold |70px, 52px, 45px, 30px |h1, h2, h3, h4 |
| Gotham | light |52px, 25px, 17px |h2 (section), cards-lg subtitle, cards-lg text |
| Gotham book| regular |17px |cards text |
| Gotham | medium |17px |cards links |


## grid :
 - Container size :  max-width 1200px;
 - Column size : 100, 50/50, 33.33/33.33/33.33
 - Squares : 25vw

## Breakpoints:
- xs - 400px
- small - 420px
- medium - 656px
- large - 768px
- xl - 1024px
 

## image sizes :
- icons - 60x60
- cards-img - 380x260
- cards-large - 710x680
- hero - 1920x1080

## icons :
- svg icons are made by `gulp icons` gulp task, which creates SVG css in `_icon_sprite.scss`   from SVG files in `images/icons/src/.`
-  http://www.grumpicon.com/- svg files for slideshow arrows are in the theme.

## npm and build tools :

 
| commands |  |
|--|--|
| npm start | compiles everything (runs all required gulp tasks) and watches for changes |
| gulp icons | creates svg css in `_icon_sprite.sccs` from svg files in `images/icons/src` |


