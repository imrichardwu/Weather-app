Weather App with React

This repository hosts a dynamic weather application built using React, providing real-time weather information based on user-specified locations. The application is feature-rich and user-friendly, utilizing various components and external APIs for geocoding and weather data retrieval. Here's an overview of its key functionalities:
<img width="1464" alt="Screenshot 2023-09-01 at 9 56 10 AM" src="https://github.com/imrichardwu/Weather-app/assets/123898971/bf5e6b5e-2fa7-42d8-ba16-cfb53c1cddd8">

Features:

Dynamic Weather Display: The app fetches weather data for the user's chosen location, including daily weather codes, maximum and minimum temperatures, and more.

Location Search: Users can input their desired location for weather information, with results displayed instantly.

User-Friendly UI: The application boasts an intuitive and visually appealing user interface, with emoji icons to represent different weather conditions.

Persistent Storage: The user's last searched location is saved in local storage for convenience.

Interactive Date Counter: An additional feature is an interactive date counter component, allowing users to explore weather forecasts for future dates.

Components:

App Component: The central component orchestrating the application's functionality, including location search and weather data fetching.

Input Component: A reusable component for handling location input.

Weather Component: Responsible for displaying weather data in a user-friendly format.

Day Component: A component rendering individual weather forecasts for specific days, complete with weather icons and temperature ranges.

Counter Component: An optional component showcasing an interactive date counter, ideal for planning weather forecasts for upcoming dates.

APIs Used:

Geocoding API: Utilized for converting location names into latitude and longitude coordinates.

Weather API: Provides detailed weather information based on geographic coordinates.

Usage:

Feel free to fork and clone this repository to build your own weather application with React. Explore the code, customize it, and enhance its features to suit your needs. Don't forget to check out the interactive date counter component, which can be adapted for various applications beyond weather forecasting.
