## tooltip-css

tooltip css style. Just my learning purposes.

### Normal tooltip section

**Position Top**
``` html
<div class="tooltip top"> my text </div>
```

**Position Bottom**
``` html
<div class="tooltip bottom"> my text </div>
```

**Position Left**
``` html
<div class="tooltip left"> my text </div>
```

**Position Right**
``` html
<div class="tooltip right"> my text </div>
```

### Normal tooltip section with animation

**Position Top**
``` html
<div class="tooltip animation top"> my text </div>
```

**Position Bottom**
``` html
<div class="tooltip animation bottom"> my text </div>
```

**Position Left**
``` html
<div class="tooltip animation left"> my text </div>
```

**Position Right**
``` html
<div class="tooltip animation right"> my text </div>
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
