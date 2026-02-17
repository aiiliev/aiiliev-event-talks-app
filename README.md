# Technical Talks Event Schedule Application

This is a simple web application designed to display a schedule of technical talks. It provides a clear overview of various sessions, including details about each talk, speaker information, categories, and a description. Users can also filter talks by category using a search bar.

## Features

*   **Event Schedule Display:** Clearly presents a timeline of technical talks, breaks, and transition times.
*   **Detailed Talk Information:** Each talk entry includes the start and end times, title, speakers, categories, and a brief description.
*   **Categorization:** Talks are categorized (e.g., AI, Machine Learning, Web Development, Cloud) for easy navigation and filtering.
*   **Category Search:** A search bar allows users to filter the displayed talks based on their categories.
*   **Intuitive Styling:** Different event types (talks, breaks, transitions) are visually distinguished for better readability.

## Technologies Used

*   **HTML:** For the basic structure of the web page.
*   **CSS:** For styling and layout, ensuring a user-friendly and aesthetically pleasing interface.
*   **JavaScript:** For dynamic content loading, search functionality, and interaction.

## Setup and Installation

To get this application up and running, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/aiiliev/aiiliev-event-talks-app.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd aiiliev-event-talks-app
    ```
3.  **Open `index.html`:**
    Simply open the `index.html` file in your preferred web browser. No web server is required for basic functionality.

## Usage

Once the `index.html` file is open in your browser:

*   **Browse the Schedule:** Scroll through the page to see the full schedule of technical talks, breaks, and transition times.
*   **Filter by Category:** Use the search input field at the top of the page to type in a category (e.g., "AI", "Node.js", "Cloud"). The schedule will dynamically update to show only the talks that match your search criteria.

## Project Structure

*   `index.html`: The main HTML file that structures the web page, includes the CSS styling, and the JavaScript logic for displaying and filtering the schedule.
*   `talk-data.json`: (Note: In this implementation, the `talkData` is directly embedded in `index.html` for simplicity.) This would typically be a JSON file containing the event schedule data, including talk details, times, speakers, and categories.
*   `.gitignore`: Specifies intentionally untracked files that Git should ignore.
*   `tools.txt`: (Assuming this is an internal file for the Gemini CLI and not part of the application itself.)

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository and submit pull requests.

## License

(Consider adding a license if you plan to make this project open source.)
