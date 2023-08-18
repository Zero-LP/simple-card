# Simple Card Example

This is a simple HTML and CSS example that demonstrates the creation of a card-like layout. The example includes an image, title, tag, and call-to-action button. The purpose of this mini-project was to practise taking a design from Figma and bringing it into reality.

## Technologies Used

- HTML5
- CSS3
- Figma

## Features & Learnings

- A card-like layout with responsive design.
  - Used `em` for `margin` & `padding` and `rem` for typography
- Utilization of Google Fonts for typography.
  - Grabbed 2 styles of the font `regular` & `bold`
- Styling and layout adjustments using CSS.
  - Used minimal `grid` just for centering the article both horizontally and vertically.
- Use of Figma for translating given design into code.

## Tips

#### 62.5%

- Came across the convention of setting the `html` root `font-size` to 62.5% so that whenever you wish to use `rem` or `em` it would be equivalent to 10 pixels. Unless you have nested elements that declare various `font-size` in which case you would need to take that into account only when dealing with `em`.

#### em is less predictable than rem

- This is due to the possibility of `em` stacking.
- If you were to have a parent element with a font-size of 2rem = 20 pixels if the root is set to 62.5%
  - Then the nested element `padding` or `margin` would need to take the new `font-size` into consideration when using `em`.
  - For example you wanted a padding of 10 pixels -> `10 / 20 = 0.5em` instead of `10 / 10 = 1em`

#### Figma

- The usage of `shift r` to show the rows and columns within the element/layout
- When paddings/margins are not quite accurate, press `r` and draw a rectangle from point a to b, to get a better reading of `padding` or `margin` required.
- For icons or any other svgs you can simply toggle code mode and grab the `html` for said `svg`. However do not rely on the `CSS` too much.

## Setup and Usage

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser to see the rendered example.

## Screenshots

You can see the card layout in action:

![Card Layout](/assets/simple-card.png)
