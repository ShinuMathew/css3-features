# CSS GRIDS

## GRID COLUMNS:
* To create columns using % `grid-template-columns: 30% 20% 50%;`
* To create columns using fractions(fr) `grid-template-columns: 1fr 2fr 3fr`
* To create columns using repeat `grid-template-columns: repeat(3, 1fr)`

## GRID ROWS:
* The row height by default is determined by the content in it
* To set height explicitly `grid-auto-rows: 200px;` This however will cut the content in the div. To solve this we use `minmax()`. `grid-auto-rows: minmax(200px, auto)` means by default the row height is 200px but will scale to and when there is an element inside it

## GRID TEMPLATE AREAS:
```CSS
{
    grid-template-areas: 
    "header header header header"
    "aside aside main main"
    "nav nav main main"
    "section section section section"
    "footer footer footer footer"
}
```
