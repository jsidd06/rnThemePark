# React Native Styling Utilities

### This module provides a collection of styling utilities for React Native applications, including metrics sizes, font sizes, and layout styles for consistent design across platforms.

## Platform Support

| iOS     | Android |
| ------- | ------- |
| support | support |

# Metrics Sizes (MetricsSizes)

### Screen Metrics

- `SCREEN_WIDTH`: Width of the screen.
- `SCREEN_HEIGHT`: Height of the screen.
- `SET_HEIGHT`: Set height calculated as a fraction of the screen width.
- `SET_RADIUS`: Set radius calculated as a fraction of the screen width.

### Sizes Metrics

- `TINY`: Tiny size calculated based on the screen width.
- `SMALL`: Small size calculated based on the screen width.
- `REGULAR`: Regular size calculated based on the screen width.
- `MEDIUM`: Medium size calculated based on the screen width.
- `LARGE`: Large size calculated based on the screen width.
- `XLARGE`: Extra-large size calculated based on the screen width.
- `XXLARGE`: Double extra-large size calculated based on the screen width.
- `SET40`: set size calculated as 40 times a fraction of the screen width.
- `SET50`: set size calculated as 50 times a fraction of the screen width.
  SET80`: set size calculated as 80 times a fraction of the screen width.
- `SET100`: set size calculated as 100 times a fraction of the screen width.
- `SET200`: set size calculated as 200 times a fraction of the screen width.
- `SET150`: set size calculated as 150 times a fraction of the screen width.
- `SET220`: set size calculated as 220 times a fraction of the screen width.
- `SET250`: set size calculated as 250 times a fraction of the screen width.
- `SET120`: set size calculated as 120 times a fraction of the screen width.
- `SET110`: set size calculated as 110 times a fraction of the screen width.

### Negative Metrics

- `NEG_TINY`: Negative tiny size calculated based on the screen width.
- `NEG_SMALL`: Negative small size calculated based on the screen width.
- `NEG_REGULAR`: Negative regular size calculated based on the screen width.

### Width Metrics

- `WIDTH_SMALL`:Width calculated as a quarter of the screen width.
- `WIDTH_MEDIUM`: Width calculated as a third of the screen width.
- `WIDTH_LARGE`:Width calculated as half of the screen width.
- `WIDTH_XLARGE`: Width calculated as one and a half times the screen width.
- `WIDTH_XXLARGE`: Full screen width.

### Height Metrics

- `HEIGHT_SMALL` : Height calculated as a quarter of the screen height.
- `HEIGHT_MEDIUM` : Height calculated as a third of the screen height.
- `HEIGHT_LARGE` : Height calculated as half of the screen height.
- `HEIGHT_XLARGE` : Height calculated as one and a half times the screen height.
- `HEIGHT_XXLARGE` : Full screen height.

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
- `fillB` : Flex property set to 1 with a white background color.
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

## Wrapper Component (Wrapper)

### The Wrapper component is provided for convenient wrapping of your content with consistent padding based on the platform.

#### Wrapper Props

- `children`: React components or elements to be wrapped.
- `style`: Additional style to be applied to the wrapper component.

## Example Usage

```
import { Wrapper } from '../Themes';

const YourComponent = () => {
  return (
    <Wrapper>
      {/* Your component content */}
    </Wrapper>
  );
};

```

Feel free to leverage these utilities to achieve a cohesive and responsive design in your React Native application.
