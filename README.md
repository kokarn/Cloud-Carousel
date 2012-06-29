Cloud-Carousel
==============

Updated / Forked version of professor cloud's Cloud Carousel

Original version here http://www.professorcloud.com/mainsite/carousel.htm

Parameters
=============
<table width="100%" border="1" cellpadding="2">
  <tbody><tr>
    <th>Parameter</th>
    <th>Description (from V1.0.0)</th>
    <th>Default Value</th>
  </tr>
  <tr>
    <td>minScale</td>
    <td>The minimum scale appled to the furthest item. The item at the front has a scale of 1. To make items in the distance one quarter of the size, minScale would be 0.25.</td>
    <td class="noWrap">0.5</td>
  </tr>
  <tr>
    <td>reflHeight</td>
    <td>Height of the auto-reflection in pixels, assuming applied to the item at the front. The reflection will scale automatically. A value of 0 means that no auto-reflection will appear.</td>
    <td>0</td>
  </tr>
  <tr>
    <td>reflGap</td>
    <td>Amount of vertical space in pixels between image and reflection, assuming applied to the item at the front. Gap will scale automatically.</td>
    <td>0</td>
  </tr>
  <tr>
    <td>reflOpacity</td>
    <td>Specifies how transparent the reflection is. 0 is invisible, 1 is totally opaque.</td>
    <td>0.5</td>
  </tr>
   <tr>
    <td>xRadius</td>
    <td>Half-width of the circle that items travel around.</td>
    <td class="noWrap">Width of container / 2.3</td>
  </tr>
  <tr>
    <td>yRadius</td>
    <td>Half-height of the circle that items travel around. By playing around with this value, you can alter the amount of 'tilt'.</td>
    <td>Height of container / 6</td>
  </tr>
  <tr>
    <td>xPos</td>
    <td>Horizontal position of the circle centre relative to the container. You would normally set this to half the width of the container.</td>
    <td>0</td>
  </tr>
  <tr>
    <td>yPos</td>
    <td>Vertical position of the circle centre relative to the container. You would normally set this to around half the height of container.</td>
    <td>0</td>
  </tr>
   <tr>
    <td>buttonLeft</td>
    <td>A reference to the element that will serve as the 'rotate left' button. The button doesn't have to be within the container.</td>
    <td>null</td>
  </tr>
   <tr>
    <td>buttonRight</td>
    <td>A reference to the element that will serve as the 'rotate right' button. The button doesn't have to be within the container.</td>
    <td>null</td>
  </tr>
   <tr>
    <td>titleBox</td>
    <td>A reference to the element that will display an image's title attribute when hovered over. This element does not have to be within the container.</td>
    <td>null</td>
   </tr>
   <tr>
    <td>altBox</td>
    <td>A reference to the element that will display an image's <strong>alt</strong> attribute when hovered over. This element does not have to be within the container.</td>
    <td>null</td>
  </tr>
  
  <tr>
    <td>FPS</td>
    <td>This is the approximate frame rate of the carousel in frames per second. The higher the number, the faster and smoother the carousel movement will appear. However, frame rates that are too high can make the user's browser feel sluggish, especially if they have an under powered machine. The default setting of 30 is a good tradeoff between speed and performance.
      </td>
    <td>30</td>
  </tr>
  
</tbody></table>

CSS
=============
Cloud Carousel does not need any specific CSS styles to operate. However, you will want to style the carousel container, text boxes and buttons.

You may wish to set the initial display property to display:hidden for these items so they will automatically dissapear if JavaScript is disabled. This is a good thing as they have no use without JavaScript enabled. The plugin will automatically set the display property of these items to display:inline.

Setting the container to overflow:scroll is a good idea as this will create a neat scrolling box with the images inside if JavaScript is disabled.

It is advisable not to apply styles to the images used in the carousel.

Why?
=============
It didn't work as intended and the last update was in march 2011 so i figured it might be time for an update.

Hope you find any use for it!