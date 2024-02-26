### border box

# box-sizing:content-box; by default
<p>In this mode, the width and height of the element are calculated only based on the content inside it, excluding padding and border. This means that if you set a width of 200 pixels to an element and then add 20 pixels of padding and 5 pixels of border, the total width of the element will be 200 pixels (content width) + 40 pixels (padding) + 10 pixels (border) = 250 pixels.</p>

# box-sizing:border-box;
<p> In this mode, the width and height of the element include the padding and border. So, if you set a width of 200 pixels to an element with box-sizing: border-box, and then add 20 pixels of padding and 5 pixels of border, the total width of the element will remain 200 pixels, and the padding and border will be added within that width. This makes it easier to design layouts because you can set the overall dimensions of an element and then add padding and border without changing its overall size.</p>

