## Getting started

1. run `npm install bdd-flex`

2. to use bdd-flex import `"node_modules/bdd-flex/src/bdd.scss"`
   in angular.json file in section `architext -> build -> styles`

# Documentation

## FLEX

- .bdd-spacer - is used to create flexible empty space within a flex container. It's typically used to distribute remaining space among flex items.
- **`.bdd-flex`**:

  - Specifies that the element should be displayed as a flex container. This class sets the CSS property `display: flex;` on the element.

- **`.bdd-no-flex`**:

  - Specifies that the element should not be flexible. It sets the CSS property `flex: none;`, meaning the element will not grow or shrink in a flex container.

- **`.bdd-flex-row`**:

  - Sets the flex direction to row. It changes the layout of flex items to flow horizontally.

- **`.bdd-flex-row-r`**:

  - Sets the flex direction to row-reverse. This reverses the order of flex items within a row.

- **`.bdd-flex-col`**:

  - Sets the flex direction to column. It changes the layout of flex items to flow vertically.

- **`.bdd-flex-col-r`**:

  - Sets the flex direction to column-reverse. This reverses the order of flex items within a column.

- **`.bdd-flex-wrap`**:

  - Specifies that flex items should wrap if necessary. It sets the CSS property `flex-wrap: wrap;`.

- **`.bdd-flex-nowrap`**:

  - Specifies that flex items should not wrap. It sets the CSS property `flex-wrap: nowrap;`.

- **`.bdd-jc-start`**:

  - Sets the justification of flex items to flex-start.

- **`.bdd-jc-end`**:

  - Sets the justification of flex items to flex-end.

- **`.bdd-jc-center`**:

  - Sets the justification of flex items to center.

- **`.bdd-jc-space-between`**:

  - Sets the justification of flex items to space-between.

- **`.bdd-jc-space-around`**:

  - Sets the justification of flex items to space-around.

- **`.bdd-jc-space-evenly`**:

  - Sets the justification of flex items to space-evenly.

- **`.bdd-ai-stretch`**:

  - Aligns flex items to stretch to fill the container.

- **`.bdd-ai-start`**:

  - Aligns flex items to the start of the container.

- **`.bdd-ai-end`**:

  - Aligns flex items to the end of the container.

- **`.bdd-ai-center`**:

  - Aligns flex items to the center of the container.

- **`.bdd-ai-baseline`**:

  - Aligns flex items to the baseline of the container.

- **`.bdd-as-auto`**:

  - Sets the align-self property to auto.

- **`.bdd-as-stretch`**:

  - Sets the align-self property to stretch.

- **`.bdd-as-center`**:

  - Sets the align-self property to center.

- **`.bdd-as-start`**:

  - Sets the align-self property to flex-start.

- **`.bdd-as-end`**:

  - Sets the align-self property to flex-end.

- **`.bdd-as-baseline`**:

  - Sets the align-self property to baseline.

- .bdd-flex-0, .bdd-flex-1, .bdd-flex-2, .bdd-flex-3, .bdd-flex-4, .bdd-flex-5
- .bdd-flex-b-0, .bdd-flex-b-100, .bdd-flex-b-200, .bdd-flex-b-300, .bdd-flex-b-400, .bdd-flex-b-500

## FLEX with BREAK POINTS

- The class names are generated based on the breakpoints and sizes provided. They follow a pattern like .bdd-[breakpoint]:[property]-[size].

## Auto margins

- .bdd-ml-a
- .bdd-mr-a
- .bdd-mt-a
- .bdd-mb-a
- .bdd-mx-a
- .bdd-my-a

## Margins and paddings

- Generated based on the defined padding and margin sizes. Follows a pattern like .bdd-[property]-[size].

## Margin and padding with breakpoints

- Similar to the above, but with breakpoints applied. Follows a pattern like .bdd-[breakpoint]:[property]-[size].

## Show and hide classes

- .bdd-show
- .bdd-hide
- Classes for each breakpoint like .bdd-[breakpoint]:show and .bdd-[breakpoint]:hide.
