# HTML & CSS - CSS Grid With Image Span

![example_png](./example.png)

### About

More CSS magic! using the fixed background attachment you can span an image over multiple divs (with the same bg set via a class).

```
background-attachment: fixed;

```

We can then target various elements using the nth-of-type(xx) and change backgrounds.

```
.container > div:nth-of-type(1) {
  grid-column: 1 / 3;
}

```

also used grid-column to span divs over multiple columns.

finally, we added a hover effect to transform the scale of the div and opacity to give it a cool effect:

```
.container > div:hover {
  opacity: 0.7;
  transform: scale(0.98);
}
```

### Acknowledgement

Thanks to Traversy Media for another great tutorial.
