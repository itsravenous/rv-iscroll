# rv-iscroll

A web component built with Polymer 1.0, providing scrolling and pinch-zoom/panning via [IScroll](http://iscrolljs.com). Heavily based on [x-iscoll](https://github.com/YannickDot/x-iscroll) (which is built with Polymer 0.3.3).

## Usage

```
<!-- Import it -->
<link rel="import" href="bower_components/rv-iscroll/rv-iscroll.html">

<!-- Use it! -->
<rv-iscroll></rv-iscroll>
```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`zoom`        | *boolean*   | `false`      | Enables pinch to zoom.
`scrollY`     | *boolean*   | `true`       | Enables scroll on Y axis.
`scrollX`     | *boolean*   | `false`      | Enables scroll on X axis.
`freeScroll`  | *boolean*   | `false`      | Enables free panning when scroll on both axis is enabled.

## Testing

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.

## License
&lt;rv-iscroll&gt; is released under the [MIT License](http://opensource.org/licenses/MIT).

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style.

## Thanks
1. To [Matteo Spinelli](http://cubiq.org/), author of IScroll and many other fantastic projects.
2. To [Yannick Levif](http://yannickdot.github.io), upon whose &lt;x-iscroll&gt; &lt;rv-iscroll&gt; is heavily based.