# prompts

- using canvas with webgl
- the canvas should fill the entire viewport.
- all 2d visual illusions(animation effect)
- each illusion is a single html file in the folder /html/
- each .html file named with a semantic name 
- without any 3rd party libraries
- without any external js or css or image files.
- .html file should be less than 200 lines.
- the shader code in each file shoule be less than 100 lines. so mobile platform could render it smoothly.
- every animation should be periodic with a period less than 15s. so no precision problem during long period.
- the first frame and the last frame of the period should be identical so that the animation is smooth forever. so this relies on the periodic function(e.g. the simplest sin/cos)
- the theme and vibe of each animation should be diverse