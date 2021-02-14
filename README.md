# sticky_header

The Javascript code needed in theme.js
```
window.onscroll = function() {
    if (document.body.scrollTop > 700 || document.documentElement.scrollTop > 700) {
        $(".template-index .site-header").addClass("fixed-header")
    } else {
        $(".template-index .site-header").removeClass("fixed-header")
    }
}

```
