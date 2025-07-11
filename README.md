# Real-Time Event Finder

This is a single-page web application that allows users to search for real-time events using the Ticketmaster API. It provides a user-friendly interface to discover events, view them on a map, and save them for later.

## Features

*   **Live Event Search:** Instantly search for events by location, category, or keyword. The results update automatically as you type.
*   **Interactive Map View:** Events are displayed on an interactive map using Leaflet.js, with marker clustering for better performance with a large number of events. The map automatically zooms to fit the search results.
*   **Dark Theme:** A sleek, modern dark theme is enabled by default.
*   **List View:** A clean, card-based list view of events.
*   **Save Events:** Save events you're interested in to a separate list.
*   **Event Notes:** Add personal notes to your saved events.
*   **Event Reminders:** Set browser notifications to remind you about your saved events.
*   **Geolocation:** Use your current location to find events happening near you.
*   **Responsive Design:** The application is designed to work on both desktop and mobile devices.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/real-time-event-finder.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd real-time-event-finder
    ```
3.  **Open `index.html` in your web browser.**

That's it! No complex setup or build process is required.

## Technologies Used

*   **HTML5**
*   **Tailwind CSS** (via CDN)
*   **JavaScript (ES6+)**
*   **React** (via CDN)
*   **Leaflet.js** (for the interactive map)
*   **Leaflet.markercluster** (for map marker clustering)
*   **Ticketmaster API** (for event data)
