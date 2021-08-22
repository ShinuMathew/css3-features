# CSS Box model
## Box model

* Each element on webpage is a box
* Each box has 4 areas
    * Content : Where the actual content are there. Width and height are applied to content area. It can be changed using box-sizing
    * Padding : Space within the element. Space between the content and the element. Kind of space between house and fence
    * Border : Fence of the house
    * Margin : Space between elements. 
        * `Margins is not added to the size of the element`
        * `Margins collapse on each other.. If I add margin-bottom :20px between boxes and add margin-top :25px, the actual margin between the 2 elements is 25px only`

## Box sizing

* By default it is `content-box`
* Content-box increases the width when padding is added
* `border-box` makes use of the maximum width available so the padding is included with the 33.3%
