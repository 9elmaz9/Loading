# Blurry Loading

![Blurry Loading Gif]([path/to/your-gif.gif](https://cdn.dribbble.com/users/2973561/screenshots/5757826/media/c5083407af44c0753602fa3e7b025ba7.gif))

This project demonstrates a simple and visually appealing loading screen effect where an image background gradually comes into focus as the loading percentage increases. The text displaying the loading percentage fades out as the background image sharpens, creating a smooth transition effect.

## Features

- **Blurry Image Loading**: The background image starts off blurry and gradually comes into focus as the loading progresses.
- **Dynamic Text**: The loading percentage is displayed in real-time and fades out as the loading completes.
- **Responsive Design**: The project is designed to be fully responsive and will adjust to different screen sizes.

## Technologies Used

- **HTML5**: The structure of the page.
- **CSS3**: Styles the page, including the use of Google Fonts and a background image blur effect.
- **JavaScript**: Handles the dynamic loading text and the blurring effect using a custom scaling function.

## Code Explanation

- **CSS**:
  - The background image is set using `background: url()` and initially blurred using the `filter: blur(30px)` property.
  - The `body` is centered using Flexbox to ensure that the content remains in the center of the screen regardless of screen size.
  - The text is styled to be large, white, and centered on the screen.

- **JavaScript**:
  - A `setInterval` function is used to increment the loading percentage from 0 to 100.
  - As the loading percentage increases, the text opacity decreases and the background image becomes less blurred.
  - The `scale` function maps the loading percentage to the appropriate opacity and blur values.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/9elmaz9/Loading.git
