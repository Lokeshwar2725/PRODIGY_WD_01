The News Niche

The News Niche is a global news website designed to fetch and display news articles on various topics using the News API. The site provides categorized sections such as "Breaking News," "Technology," "Politics," and more, allowing users to easily explore the latest headlines and search for specific news topics.

Table of Contents:
#Features
#Technologies Used
#Usage
#Customization
#API Information
#Credits

Features:
Categorized News Sections: Offers sections like Breaking News, India, Global, Technology, Politics, Business, Sports, and Weather.
Search Functionality: Users can search for any topic (e.g., "Science") to fetch relevant articles.
Dynamic News Cards: News articles are displayed as cards with images, titles, descriptions, and source information.
Responsive Design: The website is fully responsive and adjusts to different screen sizes.
Grid Layout: Uses a grid system to display news articles.

Technologies Used:
HTML5: Structure of the website.
CSS3: For styling and layout.
JavaScript (ES6+): Handles fetching news data from the API and rendering it on the page.
News API: External API used to fetch the news articles.

Usage:
Navigation: Navigate through various news categories by clicking on the navigation items (e.g., "Breaking News," "India," "Technology").
Click on the news cards to open the full news article in a new tab.
Search: Use the search bar to find news articles on specific topics.

Key Components:
index.html: The structure and layout of the website, including navigation and news card templates​(index).
styles.css: Defines the appearance of the website, including grid layout, typography, and responsive design​(styles).
script.js: Contains JavaScript code to fetch data from the News API, populate the page dynamically, and handle user interactions like search and navigation​(script).

Customization:
API Key: Replace the API_KEY in script.js with your own key from NewsAPI to extend the free request limits.
Modify Categories: To add or remove news categories, edit the <li> elements inside the <ul> in index.html.
Styling: Customize colors, fonts, or layout by modifying styles.css.
API Information
API Used: NewsAPI
Endpoint: https://newsapi.org/v2/everything

Key Features:
Fetch articles based on queries.
Returns news data in JSON format, including title, description, image, and publication date.

Credits:
News API: Provides the news data.
Developer: Lokeshwar S
