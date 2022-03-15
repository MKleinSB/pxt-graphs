# pxt-graphs

This library contains extensions and blocks to enable new kinds of graphing
on the micro:bit LED matrix display.

## Basic usage

```blocks
// Plot the ambient light as a horizontal bar graph on row 0
led.plotSingleBarHorisontal(input.lightLevel(), 255, 0)

// Plot the temperature as a vertical bar graph on column 4
led.plotSingleBarVertical(input.temperature() + 5, 55, 4)
```

## TODO

- [ ] Add "icon.png" image (300x200) in the root folder
- [ ] Turn on your automated build on https://travis-ci.org
- [ ] Use "pxt bump" to create a tagged release on GitHub
- [ ] Get your package reviewed and approved https://makecode.microbit.org/packages/approval

Read more at https://makecode.microbit.org/packages/build-your-own

## License

MIT

## Supported targets

* for PXT/microbit
* for PXT/calliopemini
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
