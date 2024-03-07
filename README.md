
```markdown
# Glowing Gradient Border Effect

This project demonstrates how to create an animated glowing gradient border effect using CSS.

## How It Works

The CSS code in `style.css` creates a box with a gradient border that rotates continuously. The gradient colors change from green to yellow to blue to pink and back to green. Additionally, the box has a pseudo-element (`::after`) that adds a blurred version of the gradient, creating a glowing effect.

- The `box` class represents the main container with a specified width and height.
- The `::before` pseudo-element creates the gradient border that rotates using the `rotating` animation.
- The `::after` pseudo-element adds a blurred version of the gradient with reduced opacity to enhance the glowing effect.
- The `rotating` animation animates the rotation of the gradient colors, controlled by the `--a` custom property.

When the box is hovered over, the gradient colors change to red, green, blue, yellow, and pink, creating a glowing effect. This is achieved using the `:hover` pseudo-class to update the gradient colors in the `::before` and `::after` pseudo-elements.

## Usage

To use this effect in your project, include the provided CSS code in your stylesheet. You can adjust the `width`, `height`, `border-radius`, and gradient colors to customize the appearance of the glowing border.

```html
<link rel="stylesheet" href="style.css">
```

Then, add a `<div>` element with the `box` class to your HTML file:

```html
<div class="box"></div>
```
