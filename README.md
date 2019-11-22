Sass mixins for create beautiful gradients.

## Getting Started
1. `yarn add mustart-gradients`

## Using on Stylesheets
```sass
@import '/path/to/core'

// Default mixins of mustart-gradients 
+mustart-gradients

// Create Gradients
$color-1: red
$color-2: blue
$name: sample
+mustart-gradient($color-1, #color-2, $name)

// Using on Spesific class
.your-class
  @extend .mustart-gradient-sample

.your-gradient-text-class
  @extend .mustart-gradient-sample-text
```

## Using on HTML
Just add `mustart-gradient-{name}` class on your spesific elements.

## Available Class Name Format
1. .mustart-gradient-{name}
2. .mustart-gradient-{name}-flip
3. .mustart-gradient-{name}-dark
4. .mustart-gradient-{name}-dark-flip
5. .mustart-gradient-{name}-light
6. .mustart-gradient-{name}-light-flip
7. .mustart-gradient-{name}-text
8. .mustart-gradient-{name}-text-flip
9. .mustart-gradient-{name}-text-dark
10. .mustart-gradient-{name}-text-dark-flip
11. .mustart-gradient-{name}-text-light
12. .mustart-gradient-{name}-text-light-flip
