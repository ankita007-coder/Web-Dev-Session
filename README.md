# Flexbox and CSS Grid Example

This repository provides examples and explanations of using Flexbox and CSS Grid layout models in web development.

## Flexbox

### Container Properties:

- **display:** `display: flex;` establishes a flex container. Direct children of this container become flex items.

- **flex-direction:** 
  - `flex-direction: row;`: Items are placed in the same direction as the text.
  - `flex-direction: row-reverse;`: Items are placed in the opposite direction of the text.
  - `flex-direction: column;`: Items are placed top to bottom.
  - `flex-direction: column-reverse;`: Items are placed bottom to top.

- **flex-wrap:**
  - `flex-wrap: nowrap;`: All flex items will be on one line.
  - `flex-wrap: wrap;`: Flex items will wrap onto multiple lines if needed.

- **flex-flow:**
  - `flex-flow: <flex-direction> <flex-wrap>;`: A shorthand for `flex-direction` and `flex-wrap`.

- **justify-content:**
  - `justify-content: flex-start;`: Items are packed toward the start of the flex container.
  - `justify-content: flex-end;`: Items are packed toward the end of the flex container.
  - `justify-content: center;`: Items are centered in the flex container.
  - `justify-content: space-between;`: Items are evenly distributed in the flex container with equal space around them.
  - `justify-content: space-around;`: Items are evenly distributed in the flex container with equal space around them, including the outer edges.
  - `justify-content: space-evenly;`: Items are evenly distributed in the flex container with equal space around them, including the outer edges.

- **align-items:**
  - `align-items: stretch;`: Items are stretched to fit the container.
  - `align-items: flex-start;`: Items are placed at the start of the cross axis.
  - `align-items: flex-end;`: Items are placed at the end of the cross axis.
  - `align-items: center;`: Items are centered in the cross axis.
  - `align-items: baseline;`: Items are aligned based on their baseline.

- **align-content:**
  - `align-content: stretch;`: Lines stretch to take up the remaining space.
  - `align-content: flex-start;`: Lines are packed toward the start of the container.
  - `align-content: flex-end;`: Lines are packed toward the end of the container.
  - `align-content: center;`: Lines are centered in the container.
  - `align-content: space-between;`: Lines are evenly distributed in the container with equal space around them.
  - `align-content: space-around;`: Lines are evenly distributed in the container with equal space around them, including the outer edges.
  - `align-content: space-evenly;`: Lines are evenly distributed in the container with equal space around them, including the outer edges.

### Item Properties:

- **order:** `order: <integer>;` determines the order of the flex item. Default is 0.

- **flex:**
  - `flex: <flex-grow> <flex-shrink> <flex-basis>;` is a shorthand for `flex-grow`, `flex-shrink`, and `flex-basis`.
  - `flex-grow: <number>;` specifies the factor by which the flex item will grow relative to the other items.
  - `flex-shrink: <number>;` specifies the factor by which the flex item will shrink relative to the other items.
  - `flex-basis: <length> | <percentage> | auto;` specifies the initial size of the flex item.

- **align-self:**
  - `align-self: auto;`: Inherited from the parent `align-items`.
  - `align-self: flex-start;`: The item is placed at the start of the cross axis.
  - `align-self: flex-end;`: The item is placed at the end of the cross axis.
  - `align-self: center;`: The item is centered in the cross axis.
  - `align-self: stretch;`: The item is stretched to fit the container.
  - `align-self: baseline;`: The item is aligned based on its baseline.

## CSS Grid

### Container Properties:

- **display:** `display: grid;` establishes a grid container.

- **grid-template-columns / grid-template-rows:** Define the size and number of columns or rows in the grid.

- **grid-template-areas:** Allows you to define named grid areas.

- **grid-template:** A shorthand property that combines `grid-template-columns`, `grid-template-rows`, and `grid-template-areas`.

- **grid-column-gap / grid-row-gap / grid-gap:** Specify the size of the gaps between columns and rows.

- **justify-items / align-items:** Align grid items along the row (for `justify-items`) or column (for `align-items`) axis.

- **justify-content / align-content:** Align the grid along the row (for `justify-content`) or column (for `align-content`) axis.

- **grid-auto-columns / grid-auto-rows:** Define the size of implicitly created columns or rows when using the `grid-auto-flow` property.

- **grid-auto-flow:** Determine how the auto-placement algorithm works, whether by rows, columns, or both.

- **grid:** A shorthand property that combines various grid properties into one declaration.

### Item Properties:

- **grid-column-start / grid-column-end / grid-row-start / grid-row-end:** Specify the start and end lines for grid items in both the column and row directions.

- **grid-column / grid-row:** Shorthand properties that combine the start and end values for both columns and rows.

- **grid-area:** A shorthand property that combines `grid-row-start`, `grid-column-start`, `grid-row-end`, and `grid-column-end`.

- **justify-self / align-self:** Align individual grid items along the row (for `justify-self`) or column (for `align-self`) axis.

### Grid Line Properties:

- **grid-column-gap / grid-row-gap / grid-gap:** Specify the size of the gaps between columns and rows.

- **grid-column / grid-row:** Specify the range of columns or rows a grid item should span.

- **grid-template-areas:** Define named grid areas.

### Responsive Grids:

- **@media queries:** Use media queries to create responsive grid layouts, adjusting the number and size of columns based on the screen size.

These layout models provide powerful tools for creating responsive and flexible designs in web development. Use them based on your layout requirements and preferences.
