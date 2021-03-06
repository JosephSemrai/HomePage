# HomePage
 Browser Startpage created in React & Node. Also works well in mobile since it's a PWA.
   
 ## Some of the functionalities
  * Current time
  * Current weather based on location
  * Gmail latest emails
  * Github notifications
  * Todoist (task manager) integration
  * Favourite websites
  * Google search
  * Dribbble feed
  * News feed
  * HackerNews feed
  * Movies feed
  * TV Shows feed
    
  ## Prints
  * [Home](https://imgurl.me/image/dPApM)
  * [Settings](https://imgurl.me/image/dPoch)
  * [Movies](https://imgurl.me/image/dPmMv)
  * [HackerNews](https://imgurl.me/image/dPljH)
  * [News](https://imgurl.me/image/dPOGR)
  
  ## Usage
  * Create a .env file on the 'client' folder with the following keys for the features you want:
      * Google API Client ID & Google API Key for Gmail - REACT_APP_GOOGLE_CLIENT_ID & REACT_APP_GOOGLE_API_KEY 
      * OpenWeatherMap API key for Weather - REACT_APP_WEATHER_API_KEY 
      * NewsAPI key for News feed - REACT_APP_NEWS_API_KEY
      * TheMoviesDB API key for Movies & TV Shows feeds - REACT_APP_MOVIES_API_KEY
      * Tiingo API key for stocks data feed - REACT_APP_TIINGO_KEY
      * Password for 'login' - not optional - REACT_APP_LOGIN_KEY
  * Example: https://imgurl.me/image/dhJnu
  * To have news from your country, open file 'news.js' and change 'COUNTRYCODE' on line 6 to whatever country you want. See codes [here](https://newsapi.org/sources)
  * Open the settings and fill with name, Github API key, Todoist API key and the URL for a background image
  
  ## Commands
  * 'npm run dev' to start both frontend and server
  * 'npm run client' to start frontend only
  * 'npm run server' to start server only
  * 'heroku-postbuild' to deploy on Heroku
  


