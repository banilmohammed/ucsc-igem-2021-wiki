# CSS Tags

## Position
* when used, you can use left, right, top, bottom, properites to move position

* **static**
    * not affected by left, right, top, bottom
    * always positioned to the normal flow of the page
* **relative**
    * relative to normal position
    * moves away from normal position
* **fixed**
    * relative to viewport
    * doesnt move even when page is scrolled
* **absolute**
    * position relative to parent positioned element
    * if no parent positioned element, uses document body and moves with page scrolling
* **sticky**
    * based on users scroll position
* **z-index**
    * used to change order of stacked things
    * higher element means closer to front

## Pseudo-elements
* style parts of an element

* **::before**
    * insert *content* before the modified element
        * content is another property you define in the css declaration

## Backgrounds
* **background-color**
    * use to change bc color of containers
* **background-image**
    * set an image as the background of some container
    * use *url(path to image)* to set image
* **background-repeat**
    * use with background-image
        * default repeats image horizontally and vertically
    * to only repeat horizontal: repeat-x
    * only repeat vertica: repeat-y
    * no-repeat for no repeat
* **background-size**
    1. auto: original size of image
    2. cover: resize image to size of entire container
    3. contain: resize image to make sure image is fully visible

## Visual Effects
* **filter**
    * use this to apply visual effects like blur, brightness, etc.
    * to use more than one effect(function), just separate by space

## Flexbox
* one-dimensional layout model
    * deals with one dimension at a time, either a row or a column
* flexbox has 2 axes:
    * main
    * cross
        * perpendicular to main axis
* defined by flex-direction property
    1. row
        * inline(horizontal)
    2. row-reverse
        * inline(horizontal)
    3. column
        * block(vertical)
    4. column-reverse
        * block(vertical)
* to make a container a flex container
    * display: flex;
* **flex-direction** determines which way flex is oriented
* **flex-wrap**: wrap or no
* **flex-basis**: initial flex box property
* **flex-grow**: flex boxes can expand
* **flex-shrink**: items can become smaller than flex-basis
* **align-items**: align flex elements on cross axis:
    * stretch: items stretch to fit height
    * flex-start: align to start
    * flex-end: align to end
    * center: align to center
* **justify-content**: align items on the main axis:
    * flex-start
    * flex-end
    * center
    * space-around: equal amount of space on right and left(end spacing will be different)
    * space-between: equal amount of space between(no space on ends)
    * space-evenly: spaced evenly

## Font
* **font-family**: chooose what font you want
    * to include fallbacks, use a comma after and include name
* **font-style**: what style font:
    * normal
    * italic
    * oblique
* **font-weight**:
    * normal
    * bold
* **font-variant**: normal or small caps version
    * normal
    * small-caps
* **font-size**: font size
    * 1em is current font size, can also use to resize
