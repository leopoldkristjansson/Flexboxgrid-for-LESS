# Flexboxgrid for projects using Less
The code for the grid is copied from [this project (flexboxgrid2)](https://github.com/evgenyrodionov/flexboxgrid2) and modified to work in projects using [Less](http://lesscss.org/).

## How to use the code?
If you have a project with a Less setup just copy the code from the file `flexboxgrid.less` into your project and import it.

`@import "flexboxgrid.less";`



To learn about how to use the CSS classes [visit the flexboxgrid2 docs](https://evgenyrodionov.github.io/flexboxgrid2/).

## Config

The following vars at the top of `flexboxgrid.less` can be configured to your liking.

```
@gutter-width: 16px;

@outer-margin: 32px;

// Breakpoints

@xs-min: 0rem;

@sm-min: 576px;

@md-min: 768px;

@lg-min: 992px;

@xl-min: 1200px;
```