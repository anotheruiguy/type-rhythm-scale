# Typography makes life better

### A commonly used series of typography mixins and functions

Look through the code, you will get the idea pretty quick. I will put more instructions in here soon, pinky swear.

In the mean time `bower install type-rhythm-scale` to get it in there. And then in your `gruntfile.js` add the following when using `grunt-sass`:

```js
options: {
  includePaths: [
    './bower_components/type-rhythm-scale'
  ]
}
```

Then import into your primary Sass manifest file:

```scss
@import "type-rhythm-scale";
```
