# preSvg
presentationable vector graphics created with inkscape

## [try live version](https://cdn.rawgit.com/gitbreaker222/preSvg/caa4bbad/presvg.html)

## how to create svg-slides

In inkscape:

- create a layer for each slide
- set background-color via document preferences
  - ![location of the background-color preference](http://goinkscape.com/wp-content/uploads/2015/04/transparent-3.png)
- set slide labels by layer name
  - prefix the layer name with `.` to exclude it from the slides (e.g. _".layout"_)
  - prefix the layer name with `+` to show this layer with every slides (e.g. _"+background"_)
  - prefix the layer name with `#` to mark it as a chapter title and show it in the menu (e.g. _"#how to create svg-slides"_)
- save file as inkscape-svg (default format)

## how to show svg-slides

- open **preSvg.html** in your browser
- load your inkscape svg file
- --> the first slide/layer shows up
- click **back/next** or use keys to loop through slides
  - back = arrow up, arrow left, backspace
  - next = arrow down, arrow right, space, enter
