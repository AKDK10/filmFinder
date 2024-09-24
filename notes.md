Film Finder Project


Overview
Film Finder is a movie discovery app that helps users get recommendations for what to watch next. Using The Movie Database (TMDb) API, the app allows users to select from a variety of genres and receive random movie suggestions. Users can like or dislike a movie, and the app will offer another recommendation accordingly.

The project uses HTTP requests and asynchronous JavaScript to interact with the TMDb API, fetching movie data based on the user's selected genre. This project is ideal for practicing working with APIs and asynchronous operations in JavaScript.

Features
Genre Selection: Choose from multiple movie genres to get personalized recommendations.
Random Movie Suggestions: Get a random movie recommendation from the selected genre.
Like or Dislike: Users can provide feedback on the movie suggestion (like or dislike) and get a new recommendation.
Getting Started
Before you begin building the Film Finder app, you’ll need to get an API key from The Movie Database (TMDb). Follow these steps to get your API key:

Step 1: Create a TMDb Account
Go to The Movie Database website and sign up for a free account.
After creating your account, verify your email address.
Step 2: Request an API Key
Click on your user icon at the top-right corner of the screen and navigate to the Settings page.

On the Settings page, select the API section.

Click on the link to Request an API Key and register as a Developer.

During the registration process, you’ll need to provide some personal information, including your address and phone number. This is standard for many API services to track the usage of their data.

You will also need to provide a URL for the website where you plan to use the API. You can list https://codecademy.com for this purpose.

Once registered, you'll receive an API key that you'll use to access movie data from TMDb.

Step 3: Implement the API Key
After obtaining your API key, you can use it to authenticate requests to TMDb's API in your JavaScript code. You'll use this key to fetch data like genres, movies, and other relevant details for the Film Finder app.

Technologies Used
JavaScript: For handling HTTP requests and asynchronous operations.
HTML/CSS: Basic structure and styling for the user interface.
The Movie Database (TMDb) API: To get data about movies and genres.
Asynchronous JavaScript: Used for fetching data from the API using promises (async/await and fetch).
Next Steps
Once you have your API key and have set up the basic project structure, you can start implementing the core functionality:

Fetch Genres: Use the TMDb API to fetch a list of available movie genres.
Display Genres: Populate the genre dropdown menu in the app UI.
Get Movie Suggestions: Fetch random movies based on the selected genre.
Like/Dislike Functionality: Allow users to like or dislike a movie and fetch new suggestions based on their feedback.
Additional Resources
If you need more guidance on registering for an API key or using the TMDb API, refer to the official TMDb API documentation.