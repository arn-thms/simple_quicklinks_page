# Simple Quick Links Page

## Overview
Simple Quick Links Page is a simple web page that provides quick access to frequently used websites by organizing them into categories. It dynamically fetches website favicons and presents clickable shortcuts in an intuitive, grid-based layout. The page can be set as default page when oopening a browser to help you have quick link page available when you open browser

## Features
- Categorized website shortcuts (Social Media, Search & Knowledge, Entertainment, Shopping, Tech & Development). Can modify by edising json structure in web page
- Automatic fetching of website favicons.
- Clickable shortcuts open in a new tab.
- Responsive design with a dark theme for better readability.
- Uses jQuery for dynamic content generation.

## Customization
- To add or modify website shortcuts, edit the `groups` object inside the `<script>` section.
- Favicons are automatically fetched but can be manually replaced by modifying the `iconUrl`.

## Technologies Used
- **HTML**: Structure of the page.
- **CSS**: Styling and layout.
- **JavaScript (jQuery)**: Dynamic generation of shortcut tiles and click handling.
- **Google Favicon API**: Fetches favicons for visual recognition.

## Installation & Usage
1. Clone or download the repository.
2. Open the `index.html` file in a browser.
3. Click on any shortcut to open the corresponding website in a new tab.

## Dependencies
This project uses the following external libraries and APIs:
- [jQuery 3.6.0](https://code.jquery.com/jquery-3.6.0.min.js) (Licensed under the [MIT License](https://jquery.org/license/))
- [Google Favicon API](https://www.google.com/s2/favicons) for fetching favicons dynamically.



## License
This project is open-source and available for personal and non-commercial use under the **MIT License**.

---
© 2025 Your Name | Licensed under MIT
