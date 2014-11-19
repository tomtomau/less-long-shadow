# LESS Long Shadow

This is a fork of zensimila's awesome tr3ndy long shadow mixin.
It removed the @spread and added in a @min, @max which I found more useful.

* This Source; [https://github.com/tomtomau/less-long-shadow](https://github.com/tomtomau/less-long-shadow)
* This Author Twitter [@tomnewbyau](https://twitter.com/tomnewbyau)
* Original Source: [https://github.com/zensimilia/less-long-shadow](https://github.com/zensimilia/less-long-shadow)
* Original Author Twitter: [@zensimilia](https://twitter.com/zensimilia)

## Usage

```css
.box {
	overflow: hidden;

	.longShadow(@color, @size, @spread);
	.longShadowBox(@color, @size, @max, @min);
}
```

## Params

* __@color__ of shadow _e.g._ `#00FFFF`, `@buttonShadowColor` or `darken(#00FFFF)`.
* __@size__ in pixels that shadow would be.
* __@max__ the start opacity as integer percentage (e.g. 42%)
* __@min__ the end opacity as an integer percentage (e.g. 42%)

## Copyright and license

[MIT License](LICENSE.md)