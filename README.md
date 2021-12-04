# css-framework

💅 A simple grid-based framework built with SCSS.
Inspired by [TailwindCSS](https://tailwindcss.com/)

## Features

<details>
  <summary>Size classes</summary>

- Sizes: `1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 14, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 60, 64, 72, 80, 96`
- Width: `w-size, e.g. w-1`
- Height: `h-size, e.g. h-1`
- Margins and paddings:

  - Horizontal: `mx-size, px-size, e.g. mx-1, px-1`
  - Vertical: `my-size, py-size, e.g. my-1, py-1`
  - Top: `mt-size, pt-size, e.g. mt-1, pt-1`
  - Right: `mr-size, pr-size, e.g. mr-1, pr-1`
  - Bottom: `mb-size, pb-size, e.g. mb-1, pb-1`
  - Left: `ml-size, pl-size, e.g. ml-1, pl-1`

</details>

<details>
  <summary>Grid system</summary>

_The grid system has 12 columns_

1. Initialize grid container: `d-grid` class
2. _(Optional)_ Set grid item size of element with `grid-size, e.g. grid-12 for full width`

### Example of usage:

```html
<div class="d-grid">
  <div class="grid-6"></div>
  <div class="grid-6"></div>
</div>
```

_Makes 2 column grid_

</details>

<details>
  <summary>Font system</summary>

- Font family
  - There are 3 families that you can use with some default fonts: `sans-serif: Inter, serif: Merriweather and monospace: Source Code Pro`
  - Sans-serif font is set globally by default
  - To set specific font family use: `font-family, e.g. font-serif` class
- Weights
  - Available weights are: `300, 400, 700, 900`
  - To set specific font weight use: `font-w-weight, e.g. font-w-300` class
- Sizes
  - Available size classes are: `xs, sm, base, lg, xl, 2xl, 3xl, 4xl, 5xl`
  - `base` is a default font size
  - To set specific font size use: `font-s-size, e.g. font-s-xs` class

</details>

## Usage

1. Download [main.css](https://github.com/michalwachowicz/css-framework/blob/main/dist/main.css) file from the `dist` directory
2. Include the file in your HTML
3. Add classes you need to your elements
4. Enjoy!

## Sample usage

```html
<p class="mx-4 font-s-sm font-w-300">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam fermentum.
</p>
```

_Paragraph with horizontal size-4 margin and small, light font_

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
