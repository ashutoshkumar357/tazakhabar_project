Project: Taza Khabar - News Website
Description:
Taza Khabar is a dynamic news website that fetches and displays the latest news articles based on user input or predefined categories such as IPL, Finance, and Politics. It uses the NewsAPI to fetch the news articles and display them in a card layout format.

Features:
Dynamic News Fetching: Fetches news articles dynamically based on predefined categories or user input search queries.
Responsive Design: The website layout is responsive, making it accessible across various devices.
News Categories: Users can click on predefined categories like IPL, Finance, or Politics to view related news articles.
Search Functionality: Users can search for news articles by entering a keyword in the search bar.
News Cards: Displays news articles in a card layout with images, titles, descriptions, and sources.
Click to Read More: Each news card is clickable and redirects users to the full article on the respective news website.

Technologies Used:
HTML5
CSS3
JavaScript (ES6+)
NewsAPI (for fetching news data)

File Structure:
index.html: Main HTML file containing the structure of the webpage.
style.css: CSS file containing styles for the website.
script.js: JavaScript file containing logic for fetching and displaying news articles.
assets/: Folder containing static assets like images (e.g., the company logo).

Setup Instructions:
Clone the Repository: git clone https://github.com/yourusername/taza-khabar.git

API Key Setup:
Obtain an API key from NewsAPI.
Replace the placeholder API key in script.js with your actual API key: const API_KEY = "YOUR_API_KEY_HERE";

Open the Project:
Open the index.html file in your preferred web browser.

How It Works:
Initial Load: On page load, the website fetches and displays news articles related to "India".
Category Navigation: Clicking on any of the categories (IPL, Finance, Politics) will fetch and display relevant news articles.
Search Functionality: Users can enter a keyword in the search bar and click the "Search" button to fetch articles related to the keyword.
News Cards: Each article is displayed as a card containing an image, title, source, and description. Clicking on the card redirects the user to the full article.

Customization:
Add More Categories: You can add more categories by extending the <li> elements in the navigation bar and handling them in the onNavItemClick() function in script.js.
Styling: Modify style.css to customize the look and feel of the website.

Notes:
Rate Limiting: The free version of NewsAPI has limitations on the number of requests per day. Consider upgrading if your project requires higher usage.
Timezone Adjustment: The news publication date is displayed in the Asia/Jakarta timezone. You can change the timezone in script.js to match your preference.

Future Enhancements:
Pagination for handling large sets of news articles.
Adding a loading spinner while news data is being fetched.
Improving error handling for API responses.
