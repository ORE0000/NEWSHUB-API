# NEWSHUB-API 🌐📰

<img src="NEWSHUB-API .png" alt="Screenshot" width="100%" />


This project is a dynamic web application designed to provide real-time news updates through integration with the NewsAPI. Developed using HTML, CSS, and JavaScript, the application fetches news articles based on user queries and displays them in an interactive and responsive interface. The platform delivers timely information, showcasing articles, sources, and images, enabling users to stay informed with the latest news across various categories.

## Technologies Used 🛠️
- ![HTML Badge](https://img.shields.io/badge/Language-HTML-red)
- ![CSS Badge](https://img.shields.io/badge/Language-CSS-blue)
- ![JavaScript Badge](https://img.shields.io/badge/Language-JavaScript-yellow)

## Description 📖

The **NewsHub-API** project is designed to fetch and display real-time news using the **NewsAPI**. It features:
- 📰 **Real-time news updates** by category (e.g., India, Technology, Business, etc.)
- 📱 **Responsive design** for desktop and mobile views
- 🖥️ **Clean and interactive user interface** for easy navigation and article browsing

### Features ✨
- **Dynamic News Fetching**: The app fetches news articles based on a predefined query (e.g., "India") or custom search terms.
- **Detailed Article Information**: Each news card displays an image, headline, description, source, and publishing date.
- **Interactive Navigation**: Users can click on news items to open the article in a new tab.
- **Search Functionality**: Allows users to search for news based on custom queries.

## How to Run Locally 🏠

Due to the limitations of the free tier for the **NewsAPI** service, this project runs locally in a **localhost environment** with the API key for personal use only. It will not function as expected if deployed online without a valid NewsAPI key under the paid plan. 

### Steps to Run Locally ⚙️:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ORE0000/NEWSHUB-API.git
   ```

2. **Open the Project Folder**:
   Navigate to the project folder using your preferred terminal or code editor.

3. **Open the `index.html` File**:
   Open the `index.html` file directly in your browser to view the project.

4. **API Key Setup** 🔑 (Optional):
   If you'd like to use the project with your own API key, you can sign up for NewsAPI, obtain your API key, and replace the key in the `script.js` file:
   ```js
   const API_KEY = "your-api-key-here";
   ```

5. **Access the News Website** 🌍:
   Upon opening the project in your browser (using localhost), it will fetch the latest news based on your query and display it dynamically.

### Important Notes ⚠️:
- **API Limitations**: The free NewsAPI plan restricts the number of requests per day and limits the features available. For full functionality, a paid NewsAPI subscription is required.
- **Localhost Only**: The project is intended for **local development purposes** and **runs only in a localhost environment**. It requires a valid API key, which works only when the project is run locally (localhost).

## Screenshots 📸
<img src="NEWSHUB-API .png" alt="Screenshot" width="100%" />




## Acknowledgments 🙏

- **NewsAPI** for providing the news data.
- **FontAwesome** for icons used in the project.
- **MDN Web Docs** for helpful documentation on web development.
