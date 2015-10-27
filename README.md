# mjcopy

This was one of the first things I made with Gainesville Dev Academy. The idea was to make a mock resume page. But mostly it was early steps into learning about html and css.

### Sample Code

```
$("#fun").hover(function(){
    $("#fun").toggleClass("make-salmon");
});

$("h1").hover(function(){
    $(this).animate({
        fontSize: "100px"
    }, 1500);
    $(this).css("color", "yellow");
});
```

This is where the terrible, terrible magic happens. Because what website wouldn't be complete without headings that jump out at you and the color salmon.
