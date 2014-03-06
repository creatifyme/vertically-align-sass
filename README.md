vertically-align-sass
=====================

Vertical align anything with just 1 mixin


Sass Mixin
```
@mixin vertical-align {
  position: relative;
  top: 50%;
  @include transform(translateY(-50%));
}
```

Using Mixin
```
.something {
  @include vertical-align;
}
```

Browser Support:
Works even in IE9
http://caniuse.com/#feat=transforms2d


Code From Sebastian Ekström:
http://zerosixthree.se/vertical-align-anything-with-just-3-lines-of-css/
