# Mapty - Map Your Workouts

Mapty is a web application that allows users to map their workouts, including running and cycling activities, by using geolocation and the Leaflet library for interactive maps.

## Features
- Track running and cycling workouts.
- Log workout details such as distance, duration, cadence (for running), and elevation gain (for cycling).
- Display workout locations on an interactive map.
- Store workouts in local storage to persist data across sessions.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/mapty.git
    cd mapty
    ```

2. Open the `index.html` file in your browser to run the application.

## Usage

1. Allow the browser to access your geolocation.
2. Click on the map to add a workout.
3. Fill in the workout details in the form and submit.
4. The workout will be displayed on the map and listed in the sidebar.
5. Click on a workout in the sidebar to move to its location on the map.

## Project Structure
```
mapty/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # Main JavaScript file
├── logo.png            # Application logo
├── icon.png            # Favicon
└── other files         # Additional files and images
```

## Local Storage
- Workouts are saved in the browser's local storage.
- On application load, stored workouts are retrieved and displayed on the map and in the sidebar.

## Dependencies
- [Leaflet](https://leafletjs.com/) for interactive maps.
- Google Fonts for typography.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Inspired by the [JavaScript course](https://www.udemy.com/course/the-complete-javascript-course/) by Jonas Schmedtmann.

## Live Demo
Check out the live demo of the project [here](https://darwashiom.github.io/mapty/).
