# Weather Widget

## Overview

This Weather Widget is a customizable, embeddable component that displays local weather information including temperature, conditions, and timezone. It's designed to be easily integrated into any website, providing real-time weather data with a sleek, modern interface.

## Features

- Displays current temperature, weather conditions, and timezone
- Customizable appearance (background, text color, link color)
- Responsive design that adapts to different screen sizes
- Real-time updates with JavaScript enabled
- Fallback functionality when JavaScript is disabled

## Usage

To add this weather widget to your website, simply copy and paste the following code into your HTML:
html
<iframe src="https://sunao.github.io/weather-widget/" width="300" height="400" frameborder="0"></iframe>

You can adjust the `width` and `height` attributes to fit your design needs.

## Customization

### Background

By default, the widget has a transparent background. To add a custom background, wrap the iframe in a div and style it as needed.

### Text Color

To change the text color, add the following parameter to the iframe URL:
&textColor=%23ffffff

Replace `%23ffffff` with your desired hex color code (remember to use `%23` instead of `#`).

### Link Color

To change the link color, add the following parameter to the iframe URL:
&linkColor=%23ffffff

Replace `%23ffffff` with your desired hex color code.

### Custom CSS

For advanced customization, you can add your own CSS styles. Append the following to the iframe URL:
&styleUrl=YOUR_CSS_URL

Replace `YOUR_CSS_URL` with the path to your custom stylesheet.

## JavaScript Functionality

While the widget works without JavaScript, enabling it allows for:

- Real-time updates
- Enhanced interactivity
- Accurate timezone information based on the selected location

## Support

If you encounter any issues or have questions about the Weather Widget, please open an issue in this repository.

## License

[Include your license information here]

---

Enjoy using the Weather Widget! We hope it adds value to your website and provides useful information to your visitors.
