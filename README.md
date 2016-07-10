# jQuery LoadingBox
### A lightweight jQuery loading box plugin.

![Screenshot](screenshot.png)

## Usage

1. Include jQuery:

	```html
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.0.0/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="jquery.LoadingBox.js"></script>
	```

3. Show LoadingBox:

	```javascript
	var lb = $.LoadingBox();
	```

4. Hide LoadingBox:

    ```javascript
    lb.close();
    ```

## Options [with default settings]

```javascript
$.LoadingBox({
    mainElementID: "loading-box",
    fadeInSpeed: "normal",
    fadeOutSpeed: "normal",
    opacity: 0.8,
    backgroundColor: "#000",
    loadingImageWitdth: "60px",
    loadingImageHeigth: "60px",
    loadingImageSrc: "loading.gif"
});
```
