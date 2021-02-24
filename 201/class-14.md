# CSS transform 
 * transform property has two settings: 2d imensional and 3d dimensional
 * but you have to install  nightly version of Chrome to see the changes by transform property.
 * transform property included a multiple prefix to support all browsers.and it accept many values like 
 * **rotate** for rotating an element from 0 to 360.
 * **scale** for changing the size of the element :any value between .99 and .01 makes the element smaller, and greater than 1.01 it looks larger.
 * we can determine ther height and width of an element by scalex,scaley
 * **translte** property:it changes the direction of an elemnet without changing the flow of other elemnts 
 * **skew**  is used to distort elements on the horizontal axis, vertical axis, or both.
 we can combine all values of transform property  like this code 
 * ```<figure class="box-1">Box 1</figure>
    <figure class="box-2">Box 2</figure>
    .box-1 {
      transform: rotate(25deg) scale(.75);
     }
    .box-2 {
     transform: skew(10deg, 20deg) translateX(20px);
     }```
 * transform-origin property it accept 2 values for x-axis and y axis 
 * **perspective** for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.
 ## Transitions & Animations:
  The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
  There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.
  * more popular transitional properties include the following.
  ```background-color/ background-position/ border-color/border-width/border-spacing/bottom/ clip
  color/crop/font-size/font-weight/height/left/letter-spacing/line-height/margin/max-height/max-width min-height/min-width/opacity/outline-color/outline-offset/outline-width/paddingright/text-indent/text-shadow/topvertical-align/visibility/widthword-spacing/z-index```





