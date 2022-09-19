# Photo-Gallery

add header element with class name "header"
add h1 element inside header
after header element, add a div element with class name "gallery"
and add 9 img elements inside .gallery element with src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/x.jpg", where x is the number of img element
select all the elements with * selector and add a property of box-sizing with border-box value, in border-box box-sizing width and height apply to all parts of the element: content, padding and borders.
select all img elements of .gallery class and give width of 100%, max-width of 350px and height to 300px
Now remove the margin from body element, add font-family to sans-serif and background color to #f5f6f7
select .header class and align the text to its center.
make the text in uppercase by setting text-transform property to uppercase.
give padding of 32px on all sides.
give background-color. 
give text color.
give border-bottom value of 4px solid color

Select the .gallery element and give display of flex
set flex-direction to row, there are 4 possible values for flex-direction property, row, row-reverse, column, column-reverse

set flex-wrap property to wrap, as when there is no space, it will wrap to the next row or column, default is nowrap, it prevents from wrapping the content and shrink if needed.

Now give value of justify-content to center

To vertically center images, use align-items property with value of center, align-items positions the flex content along cross axis, here flex-direction is row, so cross axis is vertical axis, to vertically aligned to center, give align-items to center.

To make space inside the .gallery element, give padding of 20px at top and bottom and 10px sideways

give .gallery element a max-width of 1400px
and center the items with margin 0 auto

Observe some images are distorted because of different aspect ratios, we can use object-fit property in .gallery img element and set the value to cover, this will tell image to fill the image container while maintaining aspect ratio, resulting in croping of it.

To give equal gaps between images, we can use gap property in .gallery element.

we have sharp edges at each image, to make it smooth, give .gallery img element a border-radius of 10px.

Adjust the browser window so that it shows 2 column layout and observe the last image gets centered leaving spaces at left and right side, to make it correct, whenever there is 2 column layout, last image should be on left side and leaving empty space at its right side, we can do this with ::afer pseudo-element selector, it creates empty element. So give .gallery::after selector and give empty content and width of 350px.