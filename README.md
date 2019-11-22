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
