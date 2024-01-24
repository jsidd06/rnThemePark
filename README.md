# RnThemePark

## Platform Support

| iOS     | Android |
| ------- | ------- |
| support | support |

# Metrics and Layout Styles

This module provides a set of constants for metric sizes, font sizes, and layout styles to be used consistently across your React Native application.

## Metric Sizes (MetricsSizes)

### Screen Metrics

- `SCREEN_WIDTH`: Width of the screen.
- `SCREEN_HEIGHT`: Height of the screen.
- `BASE_HEIGHT`: Base height calculated as a fraction of the screen width.
- `BASE_RADIUS`: Base radius calculated as a fraction of the screen width.

### Sizes Metrics

- `TINY`: Tiny size calculated based on the screen width.
- `SMALL`: Small size calculated based on the screen width.
- `REGULAR`: Regular size calculated based on the screen width.
- `MEDIUM`: Medium size calculated based on the screen width.
- `LARGE`: Large size calculated based on the screen width.
- `XLARGE`: Extra-large size calculated based on the screen width.
- `XXLARGE`: Double extra-large size calculated based on the screen width.
- `BASE40`: Base size calculated as 40 times a fraction of the screen width.
- `BASE50`: Base size calculated as 50 times a fraction of the screen width.
- `BASE80`: Base size calculated as 80 times a fraction of the screen width.
- `BASE100`: Base size calculated as 100 times a fraction of the screen width.
- `BASE200`: Base size calculated as 200 times a fraction of the screen width.
- `BASE150`: Base size calculated as 150 times a fraction of the screen width.
- `BASE220`: Base size calculated as 220 times a fraction of the screen width.
- `BASE250`: Base size calculated as 250 times a fraction of the screen width.
- `BASE120`: Base size calculated as 120 times a fraction of the screen width.
- `BASE110`: Base size calculated as 110 times a fraction of the screen width.

### Negative Metrics

- `NEG_TINY`: Negative tiny size calculated based on the screen width.
- `NEG_SMALL`: Negative small size calculated based on the screen width.
- `NEG_REGULAR`: Negative regular size calculated based on the screen width.

### Rating Width

- `RATING_SMALL`: Rating width as a fraction of the screen width.
- `RATING_MEDIUM`: Rating width as a fraction of the screen width.
- `RATING_LARGE`: Rating width as a fraction of the screen width.
- `RATING_XLARGE`: Rating width as a fraction of the screen width.
- `RATING_XXLARGE`: Rating width as the full screen width.

## Font Sizes (FontSize)

- `xs`: Extra small font size.
- `sm`: Small font size.
- `bs`: Base font size.
- `rg`: Regular font size.
- `md`: Medium font size.
- `lg`: Large font size.
- `xl`: Extra-large font size.
- `xxl`: Double extra-large font size.

## Layout Styles (layout)

This object provides various pre-defined layout styles to be used in your application.

### Alignments

- `alignCenter`: Align items and justify content to center.
- `rowJCenter`: Row layout with justified content and center-aligned items.
- `row`: Row layout.
- `justifySBContent`: Row layout with justified content.
- `fill`: Flex property set to 1, useful for filling available space.
- `positionA`: Absolute positioning.
- `positionR`: Relative positioning.
- `rowACenter`: Row layout with center-aligned items.
- `rowCCenter`: Row layout with justified content and center-aligned items.
- `columnSFlexStart`: Column layout with space between items and flex-start alignment.
- `column`: Column layout.
- `flexAStart`: Flex container with flex-start alignment.
- `flexAEnd`: Flex container with flex-end alignment.
- `rowFlexEnd`: Row layout with flex-end justification and items aligned to the end.
- `rowFlexStart`: Row layout with flex-start justification and items aligned to the start.
- `flexStart`: Flex container with flex-start alignment.
- `flexEnd`: Flex container with flex-end alignment.
- `textCenter`: Text alignment set to center.
- `rowSpaceEvenly`: Row layout with space-evenly justification and center-aligned items.
- `columnCenter`: Column layout with justified content and center-aligned items.

Feel free to use these constants throughout your application for consistent styling and layout.