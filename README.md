[![Build Status](https://travis-ci.org/digabi/rich-text-editor.svg?branch=master)](https://travis-ci.org/digabi/rich-text-editor)

Rich text editor with math support for Finnish Matriculation Examination Board.
Live demo can be found at [https://math-demo.abitti.fi/](https://math-demo.abitti.fi/)

Since v4.0.0, only ES2017 code with ES modules is provided (in the `dist`
directory). If you want to use this library, a bundler such as Webpack or
Rollup is probably needed.

## Dependencies

- MathQuill (https://github.com/digabi/mathquill)
- MathJax-Node
- Bacon
- Jquery
- sanitize-html

## Getting started

1. Install [Node.js](https://nodejs.org/en/) 
2. Run `npm install`.
3. Run `npm run dev`.
4. Go to [http://localhost:5000](http://localhost:5000)

## Example of direct usage

Demo: http://digabi.github.io/rich-text-editor/

Source: https://github.com/digabi/rich-text-editor/blob/master/index.html

## Deploy to https://math-demo.abitti.fi/

Update `rich-text-editor` dependency in [https://github.com/digabi/math-demo/](https://github.com/digabi/math-demo/), build and deploy it according to its documentation.

# License

https://opensource.org/licenses/MIT
