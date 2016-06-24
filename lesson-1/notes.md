Three ways of combing css and/or javascript in html files

1st - in line styling
```html
<body style="background-color: linen;">
  <h1 style="color:blue;margin-left:30px;">This is a heading.</h1>
</body>
```

2nd - style in head or javascript in body

```html
<head>
<style>
body {
    background-color: linen;
}

h1 {
    color: maroon;
    margin-left: 40px;
}
</style>
</head>

<body>
  <h1>This is a heading.</h1>
</body>
```

For Javascript

```html
```

3rd - css/js in separate file and called in head

This is best practice, separating concerns to make it easier to read, manage and extend

#index.html
```html

<head>
  <link rel="stylesheet" type="text/css" href="mystyle.css">
</head>
<body>
  <h1>This is a heading.</h1>
</body>
```

#mystyle.css
```css
body {
    background-color: linen;
}

h1 {
    color: maroon;
    margin-left: 40px;
}
```

For Javascript

```html
```

```javascript
```
