# Old TV Mixin effect for scss/sass

Flickering and old crt tv effect using css animations. 

## How to use

```
npm install old-tv-effect-scss -D

// OR

yarn add old-tv-effect-scss -D
```

Then in your sass/scss:

```scss
@import '~old-tv-effect-scss/mixin';

// Apply mixin to desired class. In this case, it is a class called body.
// The markup in this case could be <body class="body"></body>
@include apply-old-tv-effect('body');
```

## License

MIT
