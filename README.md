## tooltip-css

tooltip css style. Just my learning purposes.

View Demo - https://tooltip-css.netlify.app

Inject tooltip css file in your code,
```html
<link rel="stylesheet" type="text/css" href="/tooltip.css" />
```

### Normal tooltip section

**Position Top**
``` html
<div class="tooltip top">text</div>
```

**Position Bottom**
``` html
<div class="tooltip bottom">text</div>
```

**Position Left**
``` html
<div class="tooltip left">text</div>
```

**Position Right**
``` html
<div class="tooltip right">text</div>
```

### Normal tooltip section with animation

**Position Top**
``` html
<div class="tooltip animation top">text</div>
```

**Position Bottom**
``` html
<div class="tooltip animation bottom">text</div>
```

**Position Left**
``` html
<div class="tooltip animation left">text</div>
```

**Position Right**
``` html
<div class="tooltip animation right">text</div>
```

### Customize tooltip section.

Main purpose of this tooltip created to avoid ::after and ::before selector

**Position Top**

``` html
<div class="tooltip-main">
  <div class="custom-tooltip top"> {{ tooltip-text }} </div>
  <div>your text</div>
</div>
```

**Position Bottom**

``` html
<div class="tooltip-main">
  <div class="custom-tooltip bottom"> {{ tooltip-text }} </div>
  <div>your text</div>
</div>
```

**Position Right**

``` html
<div class="tooltip-main">
  <div class="custom-tooltip right"> {{ tooltip-text }} </div>
  <div>your text</div>
</div>
```

**Position Left**

``` html
<div class="tooltip-main">
  <div class="custom-tooltip left"> {{ tooltip-text }} </div>
  <div>your text</div>
</div>
```
