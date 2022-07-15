# Easy SASS compile setup

This repo for crate easy sass compile setup. for your project. you can use online Editor. but this is real simple.

## Deployment

add node sass

```bash
  npm i node-sass
```

for run type

```bash
  npm run sass
```

## Usage/Examples

generate rem size:

```css
h1 {
    padding: rem(100) rem(40);
}
```

media queries:

```css
h1 {
    padding: rem(50) rem(50);
    @include mq_max($sm) {
        padding: rem(20) rem(20);
    }
}
```

typography:

```css
h1 {
    @include title_1;
}
```
