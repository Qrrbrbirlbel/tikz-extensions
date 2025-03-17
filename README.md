# TikZ-Extensions

## License

This material is subject to the LaTeX Project Public License and the GNU Free Documentation License.

## About the Author

Name: Qrrbrbirlbel

## Introduction

This is not a LaTeX package but a collection of libraries for PGF and TikZ;

 * `ext.arrows` provides additional arrow tips.
   * Many of the standard `arrows.meta` library's get “Centered” and “Untipped” alternative.
   * Furthermore, the arrow tips `ext_Hug Cap` for connecting circles neatly and `ext_Loop` are provided.
 * `ext.arrows-plus` allows to place arrow tips along a path.
   
   These can either be placed via pics *along* a path operation (`ext/arrow`, `ext/softpath arrows` and `ext/softpath arrow`)
   or via keys ( `ext/arc arrows` and `ext/softpath arrows`) along a previous arc or any path segment.
   All except the `ext/arrow` key support the bending of arrow tips.

   The `\arrow` command of the `decorations.markings` library has alternatives `\arrow*` and `\arrow**` for shifting and shifting/bending.
   
 * `ext.calendar-plus` extends the `calendar` library with more tests, week numbers and a few goodies.
   * The already defined keys `day xshift`, `day yshift`, `month xshift` and `month yshift` are now proper value-keys and can be accessed wtithout having to use an `@`-riddled macro name.
   * The `if` key is nestable.
   * Via the `pgfcalendar-ext` package more conditionals are available, also week numbering according to ISO 8601 is supported.
 * `ext.layers` allows to put nodes etc on a separate layer without having to use `pgfonlayer`.
 * `ext.nodes` extends the functionalities around nodes.
 * `ext.node-families` uses the AUX file to sync the sizes of nodes.
    * `ext.node-families.shapes.geometric`
 * `ext.paths.arcto` uses `\pgfpatharcto` to construct an arc *to* a point.
 * `ext.paths.ortho` provides orthogonal path operations `-|-`, `|-|`, `r-rl`, `r-lr`, `r-du` and `r-ud`.
 * `ext.paths.timer` adds timers to `rectangle`, `parabola`, `sin` and `cos`.
 * `ext.patterns.images` allows images to be used as a path‘s pattern.
 * `ext.positioning-plus` adds more ways to position nodes in reference to each other.
 * `ext.scalepicture` scales a TikZ picture to the desired dimensions.
 * `ext.topaths.arcthrough` installs a `to path` that expects a third point that defines an arc.
 * `ext.transformations.mirror` adds transformations that reflect on arbitrary lines.
 * `ext.misc` which includes
   * the PGFKeys library `ext.pgfkeys-plus` and
   * the PGFFor extension `pgffor-ext`.
 * Shapes:
   * `ext.shapes.circlearrow`
   * `ext.shapes.circlecrosssplit`
   * `ext.shapes.heatmark`
   * `ext.shapes.rectangleroundedcorners`
   * `ext.shapes.superellipse`
   * `ext.shapes.uncenteredrectangle`

 These were developed in response to questions on tex.stackexchange.com or texwelt.de.
