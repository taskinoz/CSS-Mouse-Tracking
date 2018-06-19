# CSS Mouse Tracking

![Demonstration of CSS Tracking](https://github.com/taskinoz/CSS-Mouse-Tracking/blob/master/demo/demo.gif)

## How it works:

The CSS Tracking works by requesting CSS content when the user hovers over a cell of the invisible table
that overlays the page.

example:

```
  td:hover{
    content: url(tracking.php?xposition=2&yposition=4)
  }
```

When a user hovers over this cell the CSS will load the content from the php file which will effectively send a GET request telling you that the user is at `xposition=2` and `yposition=4`

## ToDo:

- Add PHP file to accept the CSS GET requests

- Generate Graph based on hover locations
