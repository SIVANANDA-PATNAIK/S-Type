Z-Type
## Project Overview

The Typing Speed Test Web App is a modern and responsive web application designed to help users measure and improve their typing speed. Built with Tailwind CSS, the app boasts a sleek, user-friendly interface with smooth animations, customizable color palettes, and clean typography. The primary and secondary colors are set to specific RGB values to ensure a consistent visual theme across the app. One of the standout features is the "blink" animation for the cursor, which provides a clear visual indicator of the typing position. The app also incorporates custom styles for various components and functionality to hide scrollbars for a cleaner look.

## File Structure

### 1. `index.html`
This is the main HTML file that structures the web app. It includes links to the Tailwind CSS stylesheet and the main JavaScript file. The HTML file defines the overall layout of the app, including the typing area, feedback messages, and control buttons.

### 2. `styles.css`
This file contains additional custom styles that complement the Tailwind CSS framework. Here, the specific RGB values for primary and secondary colors are defined, along with styles for the "blink" animation, tool buttons, and feedback messages for correct and incorrect text input. The hidden scrollbar feature is also implemented in this file.

### 3. `app.js`
The main JavaScript file handles the core functionality of the app. It includes the logic for measuring typing speed, detecting correct and incorrect text input, and providing real-time feedback to the user. The file also manages the "blink" animation for the cursor and any other dynamic behaviors required by the app.

### 4. `tailwind.config.js`
This configuration file is used to customize the Tailwind CSS framework. It includes settings for the custom color palette, enabling and disabling specific features, and defining responsive breakpoints. This file ensures that the Tailwind CSS framework is tailored to meet the specific design requirements of the Typing Speed Test Web App.

## Design Choices

### 1. Tailwind CSS
Choosing Tailwind CSS as the main styling framework was a deliberate decision to ensure a modern, responsive design with minimal effort. Tailwind's utility-first approach allowed for rapid prototyping and fine-tuning of the app's appearance.

### 2. Customizable Color Palette
Setting the primary and secondary colors to specific RGB values was essential for maintaining a consistent visual theme. This decision ensures that all components of the app have a uniform look and feel, enhancing the overall user experience.

### 3. Blink Animation
The "blink" animation for the cursor was implemented to provide a clear visual indicator of the typing position. This feature improves user experience by making it easier to track where text input will appear, especially during fast typing.

### 4. Hidden Scrollbars
To achieve a cleaner look, scrollbars were hidden where possible. This design choice minimizes visual clutter and allows users to focus solely on the typing area and feedback messages.

### 5. Feedback for Text Input
Providing immediate feedback for correct and incorrect text input was crucial for helping users improve their typing skills. The custom styles for feedback messages ensure that users can easily distinguish between correct and incorrect input, allowing for more effective practice sessions.

## Conclusion

The Typing Speed Test Web App is a thoughtfully designed tool that leverages the power of Tailwind CSS to deliver a seamless and visually appealing user experience. By focusing on key features such as customizable color palettes, smooth animations, and clear feedback mechanisms, the app provides a robust platform for users to measure and enhance their typing speed. The design choices made throughout the development process ensure a consistent and enjoyable experience for all users.

A web app to test your typing speed. Keep your typing speed in check and make sure it's blazingly fast.
Try it: 
Step 1: Install tailwind extension and live server in vs code
Step 2: Run index.html in docs folder using live server on the browser 