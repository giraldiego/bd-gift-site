# bd-gift-site

## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!

## Summary

### Make img completely round

```css
border-radius: 50%;
```

### Use group CSS selector
```css
h1, h2, h4 {
	text-shadow: 0px 0px 1px black;
}```

### Turn the header into a flexbox

> heading elements are block by default.

```css
    display: flex;
    flex-direction: column;  /* This means column direction, default is row */
    justify-content: center; /* start, center, end, space-around, 
    space-evenly, space-between */
    align-items: center; /* default is stretch, start, center, end */
```

### Replace img with a div
```css
.gift-img {
  background-image: url("images/gift-cover.jpg"); 
  background-size: cover;
  margin: 0px auto;
}
```
> text-align only centers in-line elements.

### Make elements change on hover
```css
.gift-img:hover {
  background-image: url("images/happy.gif");
}```

### Reuse classes, be specific with IDs

```css
.gift-img {
  /* ... */
}

#gift-img-happy:hover {
  background-image: url("images/happy.gif"); 
}

#gift-img-hot:hover {
  background-image: url("images/hot.gif"); 
}
```

### Add the footer

https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_links

### Gradients

```css
background: linear-gradient(#a2d2ff, #efb0c9);
```

