# BHARAT-SRIJAN Login Page

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [File Structure](#file-structure)
5. [Setup and Usage](#setup-and-usage)
6. [Customization](#customization)
7. [Future Enhancements](#future-enhancements)
8. [Credits](#credits)
9. [License](#license)

---

## Introduction
The **BHARAT-SRIJAN Login Page** is a visually appealing and responsive web interface for the BHARAT-SRIJAN platform, designed to cater to two types of users: **Users** and **Craftsmen**. The page features a modern design with a focus on simplicity and usability, making it easy for users to log in to the platform.

---

## Features
1. **Blurred Background**:
   - A high-resolution background image with a subtle blur effect to maintain focus on the login box.

2. **Responsive Login Box**:
   - Centralized and styled with rounded corners and shadows.
   - Two login options:
     - **Login as User**
     - **Login as Craftsman**

3. **User-Friendly Input Fields**:
   - Fields for entering a username and password with clear placeholder text.

4. **Branding**:
   - Logo positioned at the top-left corner for a professional look.

5. **Interactive Buttons**:
   - Login buttons with hover effects to enhance user engagement.

---

## Technologies Used
- **HTML5**: For structuring the webpage.
- **CSS3**: For styling and layout, including flexbox and animations.

---

## File Structure
```
project-folder/
├── index.html          # Main HTML file for the login page
├── image/              # Directory for storing images
│   └── IMG_20240907_012911_272.png  # Logo image
└── README.md           # Documentation for the project
```

---

## Setup and Usage

1. **Clone or Download the Repository**:
   ```
   git clone <repository-url>
   ```

2. **Open in Browser**:
   - Navigate to the project folder and open `index.html` in any modern web browser.

3. **Ensure Proper File Placement**:
   - The logo file (`IMG_20240907_012911_272.png`) must be located in the `image` directory.

4. **Optional**:
   - If hosting on a web server, upload all project files to the server.

---

## Customization

### Change Background Image
- Replace the URL in the `background-image` property of the `.container::before` class in the `<style>` section with your desired image URL.
  ```css
  background-image: url('your-image-url');
  ```

### Update Logo
- Replace the `IMG_20240907_012911_272.png` file in the `image` directory with your custom logo.
- Adjust the size via the `.logo img` CSS rule:
  ```css
  .logo img {
      width: 190px; /* Modify as needed */
  }
  ```

### Styling Adjustments
- Modify button colors, font styles, or layout by editing the embedded CSS in `index.html`.

---

## Future Enhancements
1. **Form Validation**:
   - Add client-side and server-side validation for username and password fields.
2. **Error Handling**:
   - Display error messages for invalid login credentials.
3. **Backend Integration**:
   - Connect the login page to a backend system for authentication.
   - Use encryption to secure sensitive data such as passwords.
4. **Mobile Optimization**:
   - Improve responsiveness for smaller screen devices using media queries.

---

## Credits
- **Background Image**: Sourced from [Unsplash](https://unsplash.com).
- **Font**: Default system font (Arial).
- **Logo**: Custom logo (can be replaced with your own).

---

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code as per the license terms.

