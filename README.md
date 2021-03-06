# react-c3js

[![NPM version][npm-image]][npm-url]

React component for [C3.js](http://c3js.org/)

Note: `c3.css` is not included.

## Installation

```
$ npm install --save react-c3js
```

## Usage

```JavaScript
const data = {
  columns: [
    ['data1', 30, 200, 100, 400, 150, 250],
    ['data2', 50, 20, 10, 40, 15, 25]
  ]
};

ReactDOM.render((
  <C3Chart data={data} />
), document.getElementById('react-c3js'));
```

You can also see the example using [Docker](https://www.docker.com/):

```bash
docker build -t react-c3js .
docker run -p 8000:8000 react-c3js
```

## Contributing

See the [Dockerfile](https://github.com/bcbcarl/react-c3js/blob/master/Dockerfile).

## Properties

Check out [C3.js Reference](http://c3js.org/reference.html) for more details.

* data
* title
* size
* padding
* color
* interaction
* transition
* oninit
* onrendered
* onmouseover
* onmouseout
* onresize
* onresized
* axis
* grid
* regions
* legend
* tooltip
* subchart
* zoom
* point
* line
* area
* bar
* pie
* donut
* gauge
* className
* style

## License

MIT

[npm-image]: https://img.shields.io/npm/v/react-c3js.svg?style=flat-square
[npm-url]: https://npmjs.org/package/react-c3js