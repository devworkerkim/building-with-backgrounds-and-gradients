# Building With Backgrounds And Gradients

This is the repo for the Building With Backgrounds And Gradients project in the HTML and CSS course of The Odin Project.  The project is a recreation of an old Apple homepage that includes elements with background images and background gradients.  The purpose of the project was to get familiar with using backgrounds and gradients.

## What I Learned

### `flex-wrap`

I wanted to try something different when spacing out the elements in the footer.  My normal process would have been to create a `<div>` for each row and then flex each row accordingly.  This would have created two separate rows and then elements I could work with in between the rows.  For a different twist, I decided to try using the `flex-wrap` property of flexbox and try to wrap my elements around.  This added a little bit more CSS, but it reduced the amount of `<div>` elements in my HTML.  I set side margins in the parent element to force the child elements to wrap sinc their widths were big enough to cause wrapping.  I just needed wide enough margins to wrap a second row.  After adding some gap, my footer child elements look like they are in two columns.

### `box-sizing`

All this time I had been trying to do weird calculations to figure out the width I wanted for an element that included padding and a border.  This made for some weird numbers, especially if I was trying to make the design responsive.  With the `box-sizing` property, I can now control element sizing with much more accuracy and not have to worry about how the padding and border affects the sizing.  I wish the default value was `border-box` but I don't mind setting this for every element because it's such a relief to have that control.