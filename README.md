# tipli Landing Page 

This repository contains a solution for an assignment from tipli.

## Notes

I have opted to use `scss`, which provides more developer ergonomics compared to raw `css` and solves some cross-compatibility off the shelf.

```sh
sass -w sass/main.scss styles.css
```

The solution supports all usual device sizes, including tablets in both portrait and landscape mode.

The "reordering" of the elements which occurs on mobile devices is achieved by utilizing media queries and order attribute of flex display.