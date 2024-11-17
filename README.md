Web Scraping for Mauritanian License Plates on Facebook Marketplace
This project automates the collection of images of Mauritanian license plates from Facebook Marketplace using web scraping techniques. The main goal is to gather a dataset of unique images to be used for a vehicle-related competition or analysis.

Project Overview
This project is divided into two parts:

Data Collection: This part involves web scraping using both Python and R to automate the process of collecting URLs of vehicle listings on Facebook Marketplace, which include images of Mauritanian license plates. The URLs are then used to download images.
Sophisticated Analysis: In the second phase, the collected images can be analyzed for various machine learning or computer vision tasks, such as detecting the license plate numbers or classifying vehicle types.
Technologies Used
Python
R
Selenium (Python): For automating web browser interactions.
BeautifulSoup (Python): For parsing HTML content.
Requests (Python): For downloading images from URLs.
rvest (R): For web scraping in R.
Chrome WebDriver: To control the web browser.
os: To manage directories and file paths.
Setup Instructions
Follow these steps to set up and run the web scraping code:

Prerequisites
Ensure you have the following installed:

Python 3.x
Google Chrome
ChromeDriver matching your Chrome version
R
Install the necessary Python packages using pip:
bash
Copier le code
pip install selenium beautifulsoup4 requests
For R dependencies, install rvest:

R
Copier le code
install.packages("rvest")
Steps to Run the Code
Clone the repository:

bash
Copier le code
git clone https://github.com/MohamedSalem32/Web_Scraping_Python-R.git
Change directory to the project folder:

bash
Copier le code
cd Web_Scraping_Python-R
For Python:

Open the web_scraping.py file and enter your Facebook login credentials:

python
Copier le code
username = 'your_email'
password = 'your_facebook_password'
Run the script to start scraping vehicle listings from Facebook Marketplace:

bash
Copier le code
python web_scraping.py
For R:

Open the web_scraping.R file and enter your Facebook login credentials.

Run the script to start scraping the data in R:

R
Copier le code
source('web_scraping.R')
The images will be downloaded and saved in the ws_data_fb directory.

Code Structure
web_scraping.py: Main Python script for web scraping Facebook Marketplace for vehicle listings.
web_scraping.R: Main R script for web scraping Facebook Marketplace for vehicle listings.
output/: Folder where downloaded images will be stored.
README.md: This documentation file.
Contributing
Feel free to fork the repository and contribute by creating pull requests. If you encounter any issues or bugs, please open an issue in the repository.

License
This project is open-source and available under the MIT License.

Acknowledgments
Selenium: For automating web browsing.
BeautifulSoup: For parsing HTML data (Python).
rvest: For web scraping (R).
Facebook Marketplace: For providing the dataset of vehicle listings.
