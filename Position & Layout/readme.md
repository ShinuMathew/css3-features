# Positions and Layouts

* Static : 
    * `Default value`
    * No special positioning
    * Keeps in normal document flow
* Relative
    * Can move the element from its original position in a relative manner to itself
        ```css
        {
            position: relative;
            left: 20px;
            bottom: 20px
        }
        ```
* Fixed
    * Fixed relative to the viewport. Will be fixed even when we scroll down. Sticky header
         ```css
        {
            position: fixed;
            left: 0px;
            bottom: 0px
        }
        ```
* Absolute
    * Postions absolutely relative to the parents which have a position property applied to it
        ```css
        {
            position: absolute;
            left: 20px;
            bottom: 20px
        }
        ```
* Sticky
    * Mixture of static and fixed
    * Starts as static and becomes fixed when you roll to a certain position in the page

---
## How to wrap navigation links in one line
* Give a width of (100/no of elements)%
* `display: inline-block`

```css
    nav li {
        width:25%;
        display: inline-block;
        font-size: 24px;
    }

    nav ul {
        white-space: nowrap;
    }
```

## How to align a nav in centre?
* Give max-width
* Make `margin: 0 auto`
* It will set margin based on the max-width to itself
```css
    nav ul {
        white-space: nowrap;
        max-width: 1200px;
        margin: 0 auto;
    }
```