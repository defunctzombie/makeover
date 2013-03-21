# makeover

[stylus](https://github.com/LearnBoost/stylus) plugin for vendor prefix mixins

## install

```
npm install makeover
```

## use

In your js
```js
stylus.use(makeover());
```

In your css
```css
@import 'makeover/vendor'
```
Now you can just use ```border-radius``` like styles and they will be expanded automatically.

## why?

Because I don't want all of nib. I just want vendor prefixes.

## credit

The stylus code is copied from the [nib](https://github.com/visionmedia/nib) project and licensed under MIT.
