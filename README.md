# USAGE

1. Copy Bar.js file to your project.

2. Import Bar in your html file:

```JavaScript
<script src="./Bar.js"></script>
```

3. Create new bar

```JavaScript
<script>
var bar = new Bar({
	message: 'Test msg.',
	position: 'top',
	clickOk: () => alert('OK!'),
	close: () => alert(':(')
});
</script>
```
---
+ Available positions: top, bottom

# Screenshots

## Top position with slide

![top-slide1.png](/screenshots/top-slide1.png?raw=true)

![top-slide2.png](/screenshots/top-slide2.png?raw=true)

## Bottom position

![bottom.png](/screenshots/bottom.png?raw=true)