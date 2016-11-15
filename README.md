Flexbox Grid
===========
Forked from original project: [kristoferjoseph/flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid) -
[flexboxgrid.com](http://flexboxgrid.com)

Grid based on the `flex` display property.

Usage
---------
The only difference between the original one and this fork is the implementation of `hidden-XX` class.

Example:
```html
<div class="row">
    <div class="col-xs-12 col-md-4 col-lg-6">
        <p>This one is always visible</p>
    </div>
    <div class="col-xs-12 col-md-4 hidden-lg">
        <p>This one is hidden on large devices</p>
    </div>
    <div class="col-xs-12 col-md-4 col-lg-6">
        <p>This one is always visible</p>
    </div>
</div>
```

All hidden classes:
- `hidden-xs` : Hidden on extra-small devices
- `hidden-sm` : Hidden on small devices
- `hidden-md` : Hidden on medium devices
- `hidden-lg` : Hidden on large devices

Install
---------
### npm
`npm i flexboxgrid --save`

### bower
`bower install flexboxgrid`
### cdn

<code>CDNJS</code>
```
<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/flexboxgrid/6.3.1/flexboxgrid.min.css" type="text/css" >
```

### css
* [Development](https://raw.githubusercontent.com/kristoferjoseph/flexboxgrid/master/dist/flexboxgrid.css)
* [Production](https://raw.githubusercontent.com/kristoferjoseph/flexboxgrid/master/dist/flexboxgrid.min.css)

Add the `flexboxgrid.css` __development__ or `flexboxgrid.min.css` __production__ to your html page.

```
<link rel="stylesheet" href="css/flexboxgrid.min.css" type="text/css">
```
Inspiration
-----------
- [topcoat-grid](https://github.com/topcoat/grid)
- [flexbox-grid by @zeMicro](https://github.com/zeMirco/flexbox-grid)
- [ptb2.me/flexgrid](http://ptb2.me/flexgrid/)
- [codepen.io/marcolago/pen/lqGFb](http://codepen.io/marcolago/pen/lqGFb)
- [philipwalton.github.io/solved-by-flexbox/demos/grids](http://philipwalton.github.io/solved-by-flexbox/demos/grids/)
- [davidwalsh.name/stylus-grid](http://davidwalsh.name/stylus-grid)
