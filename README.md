# Wiki Clone

## Overview
Wiki Clone is a simple web application that allows users to search for articles on Wikipedia using the Wikipedia API. It provides a user-friendly interface with a search bar, result listings, and a light/dark theme toggle.

## Features
- Search Wikipedia articles using a search query.
- Display search results with titles, links, and snippets.
- Toggle between light and dark themes.
- Responsive design for better usability on different devices.

## Technologies Used
- HTML
- CSS
- JavaScript (ES6+)
- Wikipedia API

## Setup and Usage

### Prerequisites
Ensure you have a modern web browser installed.

### Steps to Run
1. Clone this repository or download the project files.
   ```bash
   git clone <repository-url>
   ```
2. Open the `index.html` file in a web browser.
3. Enter a search term in the input field and press the "Search" button.
4. Click on any search result to open the full article on Wikipedia.
5. Use the "Light/Dark" theme toggle button to switch themes.

## Project Structure
```
Wiki Clone/
│── index.html       # Main HTML file
│── style.css        # Stylesheet for the UI
│── app.js           # JavaScript logic
│── README.md        # Project documentation
```

## API Usage
This project uses the Wikipedia API to fetch search results. The API endpoint used:
```
https://en.wikipedia.org/w/api.php?action=query&list=search&prop=info&inprop=url&utf8=&format=json&origin=*&srlimit=10&srsearch=<search-term>
```

## Troubleshooting
- If search results do not appear, check your internet connection.
- If the theme toggler does not work, ensure JavaScript is enabled in your browser.
- If API requests fail, Wikipedia API might be temporarily down.

## Future Enhancements
- Implement pagination for search results.
- Add autocomplete suggestions for search queries.
- Improve UI styling with animations and transitions.

## License
This project is open-source and free to use under the MIT License.
