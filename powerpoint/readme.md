# Make presentation from source text

Give Claude the component library and the source text and instruct Claude to create a presentation (prompt below).

Prompt to Claude: 

```
Fetch the component template from:
https://cdn.jsdelivr.net/gh/Lummelunda/scaleout@main/powerpoint/slide-components.html
Build a deck and output a complete, self-contained HTML file. Content attached. 
```

## HTML presentation

Prompt this to make it into a HTML presentation:

```
update the html file to display one slide at a time
add controller for navigation
and add the "contenteditable" attribute to all text elements.
```

## Powerpoint format

Instruct Claude to generate a pptx file from newly generated presentation html file.

Then you can import the generated pptx file into Google slides (or Powerpoint, Keynotes, ...) and make adjustments.

