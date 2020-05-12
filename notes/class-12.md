
# Canvas, Text, Shapes

## Charts.s
  - a library that has a bunch a prebuilt charts that are free to use
  - had MIT License
  - to download, clone repo to local machine and attach library with the script tag
  - customizable tables - fonts, colors, interactions, layout

## Basic Usage of Canvas 
<canvas> - does not have the src and alt attributes, it does however use the width and height attributes

  - provides an area that you are able to draw with js
  - 300px x 150px automatic layout size
  - id attribute is always good to use on a canvas
  - canvas is a good tool in order to set fallback content for older browsers

## Drawing Shapes with Canvas
- the grid / coordinate space

``` fillRect(x, y, width, height)
    strokeRect(x, y, width, height)
    clearRect(x, y, width, height)
    begingPath()
    closePath()
    stroke()
    fill()
    moveto()
    moveTo(x, y)
    arc(x, y, radius, startAngle, endAngle, anticlockwise)
    Path2d()
```

## Applying styles and colors

```
  fillStyle = color

  strokeStyle = color 
  
  global Alpha = transparencyValue
  
  lineCap = type

  lineJoin = type
  
  miterLimit = value
  
  getLineDash()

  setLineDash(segments)

  lineDashOffset = value
  
  shadowOffsetX = float
```
## Drawing Text
- 2 ways to render text to page 
  - fillText method
  - strokeText method

- measureText()
  - contains text width in pixels

```
font = value

textAlign = value

textBaseline = value

direction = value
```