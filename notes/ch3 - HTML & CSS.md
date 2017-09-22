# Chapter 3 notes

In `dummy.html` I wouldn't use an inline style; I prefer CSS classes like so:

```html
<p>Want to try crossing out an <a href='nowhere.html' class='deadlink'>obsolete link</a>? This is your chance!</p>
```

Then in my CSS file:

```css
.deadlink {
	color: #900;
	text-decoration: line-through;
}
```