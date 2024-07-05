# Web-Scraping-Projects

Web Scraping 1:
This script serves as an introductory project in web scraping, utilizing the pytube library to interact with YouTube. After installing pytube3, the script prompts the user to input a YouTube video link. It then creates an instance of the YouTube class with this link, enabling the extraction of various details about the video, such as its title, view count, duration, description, rating, and likes. Additionally, the script identifies and downloads the highest resolution version of the video, providing a completion message upon successful download. This project effectively demonstrates how to use Python for web scraping and data extraction from an online service.

Web Scraping 2:
This script demonstrates web scraping with the twint library to gather Twitter followings data. After installing twint, it defines a list of notable users and a function to scrape their followings. The script iterates over each user, storing followings in a dictionary and compiling a combined list. It then uses Counter to identify the top 10 most common followings among these users. Additionally, it creates a dictionary to track mutual follow relationships, constructing a DataFrame to visualize these relationships. This project highlights the use of Python for web scraping and data analysis, focusing on Twitter interactions.

Web Scraping 3:

This script demonstrates web scraping with BeautifulSoup to extract product information from Flipkart. After installing and importing the necessary libraries (bs4 and urllib3), it fetches the HTML content of a Flipkart search results page for Samsung mobiles. The HTML is parsed, and product containers are identified by their specific class. For each product, the script extracts the name, price, and ratings, and then writes this information to a CSV file named "products.csv". This project illustrates the use of Python for web scraping, data extraction, and saving the data in a structured format for further analysis or use.

Web Scraping 4:

This script utilizes the instaloader library for web scraping Instagram, showcasing its capabilities for extracting user profile information and downloading posts. After installing the instaloader library, it initializes an instance of Instaloader to interact with Instagram. The script loads and prints details from the profile of 'abhishek_rastogi10', such as username, user ID, post count, follower count, followee count, biography, and external URL. It includes commands for logging into Instagram, essential for accessing private profiles and detailed follower/followee information. The script demonstrates how to fetch lists of followers and followees for a given profile, printing these lists. Additionally, it iterates over posts from another profile, 'abhishekrastogi38069', downloading each post and saving it locally. This project serves as a practical example of using Python to scrape social media data, showcasing capabilities for both data extraction and content downloading from Instagram.




