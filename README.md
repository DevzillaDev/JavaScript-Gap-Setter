# JavaScript-Gap-Setter

## Description
This JavaScript snippet allows users to set the gap between elements by adding `data-gapX` or `data-gapY` attributes to HTML elements.

## How It Works
1. Fetches elements with `data-gap-x` or `data-gap-y` attributes.
2. Retrieves the values of these attributes.
3. Sets CSS `columnGap` or `rowGap` properties based on the attribute values.

## Usage
1. Add `data-gap-x` attribute to set column gap.
2. Add `data-gap-y` attribute to set row gap.
3. Values assigned to these attributes determine the gap size.

## Example
```html
<div data-gap-x="10px">Element with column gap</div>
<div data-gap-y="20px">Element with row gap</div>
