# Date Management App

## Overview
This Ionic-based web application provides several date-related functionalities, including:

1. Displaying the current date.
2. Showing the number of days remaining until key academic year events.
3. Allowing users to select a date and calculating the days until that date.
4. Determining the zodiac sign based on the selected date and displaying the corresponding image.

## Features
- **Current Date Display:** The first card shows the current date.
- **Academic Year Schedule Countdown:** The second card lists important academic year events and the number of days remaining until each.
- **Custom Date Countdown:** The third card allows users to pick a date and calculates the days remaining until then.
- **Zodiac Sign Finder:** The fourth card determines the zodiac sign based on the selected date and displays an image from the `img` directory.

## Technologies Used
- **Ionic Framework** for UI components
- **JavaScript** for logic and interactivity
- **HTML & CSS** for structure and styling

## Installation and Usage
1. Clone the repository or download the `index.html` file.
2. Ensure the `img` directory contains zodiac sign images named in Czech.
3. Open `index.html` in a web browser to use the app.

## How It Works
1. **Current Date:** Automatically displayed on page load.
2. **Academic Year Countdown:** Events are predefined, and the app calculates the days remaining dynamically.
3. **Date Countdown:** User selects a date, and the app calculates the difference in days.
4. **Zodiac Sign Display:** The app determines the zodiac sign from the selected date and displays the corresponding image.

## Dependencies
The app relies on the Ionic framework, which is included via CDN:
- `@ionic/core`
- `ionic.bundle.css`

