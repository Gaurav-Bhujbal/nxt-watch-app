# Nxt Watch

Nxt Watch is a YouTube alternative that allows users to log in, browse various video categories such as **Trending** and **Gaming**, view saved videos, and search for specific content with a customizable theme.

## Features

- **User Authentication**: Secure login system with username/password input, JWT token authentication, and persistent login states.
- **Interactive UI**: Designed interactive pages including **Login, Home, Trending, Gaming, and Saved Videos** using React components and state management.
- **Video Search & Categories**: Users can search for videos and explore categorized content.
- **Dark/Light Theme Support**: Customizable theme for personalized viewing experience.
- **Protected Routes**: Implemented authentication-based protected routes using React Router.
- **Local Storage Integration**: Persistent user authentication and saved video preferences.

## Technologies Used

- **React JS**
- **JavaScript**
- **CSS**
- **Bootstrap**
- **React Router**
- **REST API Calls**
- **Local Storage**
- **JWT Token Authentication**
- **Authorization & Authentication**

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Gaurav-Bhujbal/nxt-watch-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd nxt-watch-app
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```
5. Open the application in your browser at `http://localhost:3000/`.

## Usage

### Login Credentials
- **Username**: rahul
- **Password**: rahul@2021

1. **Login**: Enter your credentials to log in and access the platform.
2. **Explore Videos**: Browse through different categories such as **Trending**, **Gaming**, and **Saved Videos**.
3. **Search Functionality**: Easily search for specific content using the search bar.
4. **Theme Customization**: Toggle between Light and Dark mode for a personalized experience.

## Future Enhancements

- **Video Upload Feature**: Allow users to upload their own videos.
- **Live Streaming**: Enable live video streaming functionality.
- **Comment & Like System**: Users can engage with videos through comments and likes.
- **Playlist Management**: Users can create and manage playlists.
- **Recommendations**: AI-powered video recommendations based on user preferences.
- **Offline Mode**: Allow users to download and watch videos offline.

## Design Files

<details>
<summary>Login Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Login](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-sm-outputs.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Login Failure - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-failure-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-light-theme-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login - Dark Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-dark-theme-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login Failure - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-failure-light-theme-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Login Failure - Dark Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-login-failure-dark-theme-lg-output-v1.png)

</details>

<details>
<summary>Home Route</summary>

- [Extra Small (Size < 576px) - Home](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-success-xs-outputs.png)
- [Small (Size >= 576px) - Home - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-success-light-theme-sm-output.png)
- [Small (Size >= 576px) - Home - Dark Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-success-dark-theme-sm-output.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Home - No Search Results](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-no-videos-sm-outputs.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Home Failure](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-failure-sm-outputs.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-success-light-theme-lg-output-v0.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Home - Dark Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-home-success-dark-theme-lg-output-v0.png)

</details>

<details>
<summary>Trending Route</summary>

- [Extra Small (Size < 576px) - Trending](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-trending-success-xs-outputs.png)
- [Small (Size >= 576px) - Trending - Light Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-trending-success-light-theme-sm-output.png)
- [Small (Size >= 576px) - Trending - Dark Theme](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-trending-success-dark-theme-sm-output.png)

</details>

<details>
<summary>Not Found Route</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-page-not-found-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Not Found](https://assets.ccbp.in/frontend/content/react-js/nxt-watch-page-not-found-light-theme-lg-output-v0.png)

</details>
