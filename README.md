# tailwind-card-2
hosted link:-https://thakaresakshi.github.io/tailwind-card-2/
![image](https://github.com/ThakareSakshi/tailwind-card-2/assets/86354291/33c4f1fe-bdc1-4557-a0fe-8a21ae4b8672)
various Tailwind CSS classes are used to style HTML elements. Here's an explanation of the Tailwind properties used in each tag:

1. **`<html>` and `<head>`**: These are standard HTML elements and do not have Tailwind CSS properties.

2. **`<body>`**:
   - `class="flex justify-center items-center h-screen"`: This class configures the body to be a flex container, horizontally and vertically centered (`justify-center` and `items-center`), and to take up the entire height of the screen (`h-screen`).

3. **`<div class="flex p-6 font-mono w-2/5 shadow-xl">`**:
   - `flex`: Configures the div as a flex container.
   - `p-6`: Adds padding to the div.
   - `font-mono`: Applies a monospaced font.
   - `w-2/5`: Sets the width to 40% of the parent container.
   - `shadow-xl`: Adds a shadow to the element.

4. **Image Container (`<div class="flex-none w-48 mb-10 relative z-10 before:absolute before:top-1 before:left-1 before:w-full before:h-full before:bg-teal-400">`)**:
   - `flex-none`: Specifies that this div should not grow within the flex container.
   - `w-48`: Sets the width to 12rem.
   - `mb-10`: Adds margin at the bottom.
   - `relative`: Establishes a relative positioning context for child elements.
   - `z-10`: Sets the z-index to control stacking order.
   - `before:absolute`: Pseudo-element that becomes absolutely positioned.
   - `before:top-1 before:left-1 before:w-full before:h-full before:bg-teal-400`: Pseudo-element styles for positioning and background color.

5. **Image (`<img>`)**:
   - `absolute inset-0 w-full h-full object-cover rounded-lg`: Positions the image absolutely within its container, ensuring it covers the entire area (`inset-0`) while maintaining its aspect ratio (`object-cover`). The `rounded-lg` class rounds the corners.

6. **Form (`<form class="flex-auto pl-6">`)**:
   - `flex-auto`: Makes the form grow and fill available space.
   - `pl-6`: Adds left padding.

7. **Product Title (`<h1>`)**:
   - `text-2xl`: Sets the text size to 1.25rem.
   - `font-semibold`: Sets the font weight to semibold.
   - `text-white`: Sets the text color to white.
   - `mb-2`: Adds margin at the bottom.

8. **Product Price and Availability (`<div class="relative text-lg text-white">`, `<div class="relative uppercase text-teal-400 ml-3">`)**:
   - `relative`: Establishes a relative positioning context.
   - `text-lg`: Sets the text size to 1rem.
   - `text-white`: Sets the text color to white.
   - `uppercase`: Converts text to uppercase.
   - `text-teal-400`: Sets the text color to a teal shade.
   - `ml-3`: Adds left margin.

9. **Size Options (`<label>` elements)**:
   - `space-x-3`: Adds horizontal spacing between label elements.
   - `text-sm font-medium`: Sets text size to 0.875rem and font weight to medium.

10. **Size Radio Buttons (`<input>` and `<div>` elements)**:
    - `sr-only`: Hides the radio button visually.
    - `peer`: Selects the adjacent sibling (the `<div>` in this case) for styling.
    - `peer-checked:bg-black peer-checked:text-white`: Applies styles to the adjacent `<div>` when the radio button is checked.

11. **Action Buttons (`<button>` elements)**:
    - Various classes are used to set button styles, including size (`h-12`, `w-12`), padding (`px-6`), font weight (`font-semibold`), text color (`text-black`, `text-slate-900`), and borders (`border`, `border-black`, `border-slate-200`).

12. **Like Button (`<button>` with a heart icon)**:
    - `flex-none`: Specifies that this button should not grow within its container.
    - `w-12 h-12`: Sets the width and height of the button.
    - `text-black`: Sets the text color to black.

13. **Shipping Info (`<p class="text-xs leading-6 text-slate-500">`)**:
    - `text-xs`: Sets the text size to 0.75rem.
    - `leading-6`: Sets the line height to 1.5.
    - `text-slate-500`: Sets the text color to a slate shade.

These Tailwind CSS classes provide styling and responsiveness to the HTML elements, making it easy to create a visually appealing and responsive web page.
