# Frontend-2-Module-Test--August

Project Overview
You're assigned the task of creating a dynamic weather application that fetches current weather data for a user's location. The application will obtain the user's geolocation, display it on Google Maps, and then retrieve and display the relevant weather details from the OpenWeatherMap API.

Functional Requirements
Geolocation API: On the landing screen, the user should only see a "Fetch Data" button. Once clicked, the application should use the Geolocation API to fetch the latitude and longitude of the user's current device.
Displaying the Map: Using the acquired latitude and longitude, show the user's location on Google Maps.

Fetching Weather Data: Use the `One Call API` from OpenWeatherMap to fetch the current weather data for the given coordinates- (https://openweathermap.org/api/one-call-3)
UI/UX: The UI of the application should be designed according to the provided Figma link.

Features
Fetch Geolocation: Use the Geolocation API to fetch the user's current latitude and longitude.

Map Integration: Display the user's current location on Google Maps.
Fetch Weather Data: Send a GET request to the OpenWeatherMap API using the retrieved latitude and longitude to fetch the relevant weather details.
Display Weather Data: Create a section to dynamically display the weather data, ensuring all relevant details provided in the API response are handled and shown.