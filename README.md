# TikZ-Extensions

## License

This material is subject to the LaTeX Project Public License and the GNU Free Documentation License.

## About the Author

Name: Qrrbrbirlbel

## Introduction

This is not a LaTeX package but a collection of libraries for PGF and TikZ;

* `ext.arrows` provides additional arrow tips.
  * Many of the standard `arrows.meta` library's tips get “Centered” and “Untipped” variants.
  * Additional arrow tips: `ext_Hug Cap`, `ext_Loop`, `ext_Double Cap`, `ext_Double Stealth`, `ext_Double Triangle`.
* `ext.arrows-plus` allows to place arrow tips along a path.
  * via pics *along* a path operation (`ext/arrow`, `ext/softpath arrows` and `ext/softpath arrow`)
  * via keys ( `ext/arc arrows` and `ext/softpath arrows`) along a previous arc or any path segment.
  * All except the `ext/arrow` key support the bending of arrow tips.
  * The `\arrow` command of the `decorations.markings` library has alternatives `\arrow*` and `\arrow**` for shifting and shifting/bending.
* `ext.beamer` provides better Beamer support for TikZ.
* `ext.calendar-plus` extends the `calendar` library with more tests, week numbers and a few goodies.
  * The already defined keys `day xshift`, `day yshift`, `month xshift` and `month yshift` are now proper value-keys and can be accessed without having to use an `@`-riddled macro name.
  * The `if` key is nestable.
  * Via the `pgfcalendar-ext` package more conditionals are available, also week numbering according to ISO 8601 is supported.
* `ext.layers` allows to put nodes etc on a separate layer without having to use `pgfonlayer`.
* `ext.misc` which includes
  * the PGFKeys library `ext.pgfkeys-plus` and
  * the PGFFor extension `pgffor-ext`.
* `ext.node-families` uses the AUX file to sync the sizes of nodes.
  * `ext.node-families.shapes.geometric`
* `ext.nodes` extends the functionalities around nodes.
* `ext.paths.arcto` implements a `arc to` path operation to construct an arc *to* a point.
* `ext.paths.ortho` provides orthogonal path operations `-|-`, `|-|`, `r-rl`, `r-lr`, `r-du` and `r-ud`.
* `ext.paths.timer` adds timers to the path operations `rectangle`, `parabola`, `sin` and `cos`.
* `ext.patterns.images` allows images to be used as a path‘s pattern.
* `ext.positioning-plus` adds more ways to position nodes in reference to each other.
* `ext.scalepicture` scales a TikZ picture to the desired dimensions.
* Shapes:
  * `ext.shapes.circlearrow`
  * `ext.shapes.circlecrosssplit`
  * `ext.shapes.heatmark`
  * `ext.shapes.rectangleroundedcorners`
  * `ext.shapes.superellipse`
  * `ext.shapes.uncenteredrectangle`
* `ext.topaths.arcthrough` installs a `to path` that expects a third point that defines an arc.
* `ext.topaths.autobend` implements various `to path`s that bend in a specific direction instead of left or right.
* `ext.transformations.mirror` adds transformations that reflect on arbitrary lines.

These were developed in response to questions on tex.stackexchange.com or texwelt.de.
