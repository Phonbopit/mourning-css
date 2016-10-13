# mourning-css
Make html to grayscale

## Usage

## Method 1 : JavaScript

Include javascript tags at the end of the document body

```
<!doctype html>
<html>
<head></head>
<body>
    ...
    ...
    <script src="https://rawgit.com/phonbopit/mourning-css/master/main.js"></script>
</body>
</html>
```

## Method 2 : CSS

```css
html {
    -webkit-filter: grayscale(1);
            filter: grayscale(1);
}
```
