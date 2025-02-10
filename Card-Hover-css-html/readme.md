# Hover Effect on Card using Only CSS and HTML

This is a simple example of how to create a card with a hover effect using only HTML and CSS. When the user hovers over the card, the card will scale and add a shadow effect, giving it a 3D look.

## Files Included

- \`index.html\`: The HTML structure of the card and CSS for styling the card and hover effect.

## Demo

To see the effect in action, just open \`index.html\` in your browser.

## Explanation

1. **HTML Structure**: 
   - The card is composed of an image and some text inside a \`div\` with the class \`card\`. The image is placed inside \`card-image\`, and the text is placed inside \`card-content\`.

2. **CSS Styling**:
   - The card has a border radius, box shadow, and padding for a neat appearance.
   - The hover effect is achieved using \`:hover\` on the \`.card\` class. When hovered, the card will slightly scale up and move upwards, giving it a 3D effect.
   - The transition effect is applied to the \`transform\` and \`box-shadow\` properties, making the change smooth.

3. **Hover Effect**:
   - When you hover over the card, it increases in size (\`scale(1.05)\`) and moves up slightly (\`translateY(-10px)\`), while the shadow becomes stronger, making it look like the card is floating.

## Customization

- **Image**: Replace the \`src\` attribute of the image with your desired image URL.
- **Card Size**: Adjust the width of the \`.card\` class to change the card's size.
- **Colors**: Modify background colors, text colors, and shadow effects in the CSS for your own design.
- **Font**: Change the font-family or use web fonts to match your design style.

