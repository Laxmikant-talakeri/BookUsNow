


# BookUsNow

BookUsNow is a web application designed to help users discover and book upcoming events. It provides recommendations for shows and events based on user preferences.

## Features

- **Recommendations**: Users can view recommended shows based on their interests.
- **Upcoming Events**: Browse through a list of upcoming events and view details.
- **Infinite Scrolling**: Scroll through the list of upcoming events endlessly.

## Technologies Used

- **React**: Frontend framework for building user interfaces.
- **Swiper**: A modern carousel slider library for React.
- **Infinite Scroll Component**: A React component for infinite scrolling.
- **Azure Functions**: Backend service for fetching event data.

## Installation

1. Clone the repository:

```
git clone https://github.com/Laxmikant-talakeri/BookUsNow.git
```

2. Navigate to the project directory:

```
cd BookUsNow
```

3. Install dependencies:

```
npm install
```

4. Start the development server:

```
npm run dev
```

5. Open the application in your browser:

```
http://localhost:3000
```
## API Key Setup

Ensure you have the necessary API key configured for fetching event data. Refer to the environment variable `VITE_API_KEY` for the upcoming events component.

## Project Structure

- **src/components**: Contains React components for different parts of the application.
- **src/Loader/index.jsx**: Contains loader component for displaying loading state.
- **src/Card*/index.jsx*: Contains card component for displaying event information.
- **src/index.css**: Stylesheet for global styles.
- **src/Recommendation/index.jsx**: Stylesheet specific to the recommendation component.
- **src/Upcoming/index.jsx**: Stylesheet specific to the upcoming component.



## Usage

- Explore recommended shows on the home page.
- Click on "See all" to view all upcoming events.
- Scroll through the list of upcoming events.
- Click on an event card to view more details.

## Contributing

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
```

