# 3 ways to implement CSS into HTML

- External css
- Internal css
- Inline style

## Inline style

Inside the element, introduce `style` attribute to use css

```html
<h1 style="margin: 10px">Heading 1</h1>
```

## Internal css

```html
<head>
  <style>
    /* tag selector */
    h1 {
      background: red;
    }

    /* class selector */
    .heading {
      background: blue;
    }

    /* id selector */
    #head_id {
      background: green;
    }
  </style>
</head>

<body>
  <h1 class="heading" id="head_id">Heading 1</h1>
</body>
```

## External css

index.html

```html
<head>
  <link rel="stylesheet" href="main.css" />
</head>

<body>
  <h1 class="heading" id="head_id">Heading 1</h1>
</body>
```

main.css

```css
/* tag selector */
h1 {
  background: red;
}

/* class selector */
.heading {
  background: blue;
}

/* id selector */
#head_id {
  background: green;
}
```

# Define color in CSS

- rgb
- hsl
- hex
- color name

# Pseudo Class Selector

```css
h1:focus
h1:hover
h1:focus-within
h1:before
h1:after
```
