# Assignment 7.4 - Modern Landing Page Header

## Header

The header uses Flexbox with justify-content: space-between, so the logo is on the left, the navigation links are in the middle and the CTA button is on the right. align-items: center aligns them vertically. The header uses position: sticky, so it stays at the top when the page scrolls.

## Hero Section

The hero section is a flex container. The text (heading, paragraph and button) is on the left and the image is on the right. Both children use flex: 1, so they take equal width, and align-items: center aligns them vertically in the middle.

## Footer

The footer uses the same blue background as the header, with centered white text.

## Responsive Layout

I checked the layout at different widths. Below 768px, a media query changes the hero flex-direction to column, so the text goes above the image and is centered, and the heading becomes smaller.
