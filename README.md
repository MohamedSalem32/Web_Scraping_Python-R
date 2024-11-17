# Web Scraping for Mauritanian License Plates on Facebook Marketplace

This project automates the collection of images of Mauritanian license plates from Facebook Marketplace using web scraping techniques. The main goal is to gather a dataset of unique images to be used for a vehicle-related competition or analysis.

## Project Overview

This project is divided into two parts:

1. **Data Collection**: This part involves web scraping using Python to automate the process of collecting URLs of vehicle listings on Facebook Marketplace, which include images of Mauritanian license plates. The URLs are then used to download images.
2. **Sophisticated Analysis**: In the second phase, the collected images can be analyzed for various machine learning or computer vision tasks, such as detecting the license plate numbers or classifying vehicle types.

### Technologies Used

- **Python**
- **Selenium**: For automating web browser interactions.
- **BeautifulSoup**: For parsing HTML content.
- **Requests**: For downloading images from URLs.
- **Chrome WebDriver**: To control the web browser.
- **os**: To manage directories and file paths.

## Setup Instructions

Follow these steps to set up and run the web scraping code:

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Google Chrome
- ChromeDriver matching your Chrome version
- Install the necessary Python packages using pip:

```bash
pip install selenium beautifulsoup4 requests
Steps to Run the Code
Clone the repository:

```
git clone https://github.com/MohamedSalem32/Web_Scraping_Python-R.git
Change directory to the project folder:

```bash
cd Web_Scraping_Python-R
```
Open the web_scraping.py file and enter your Facebook login credentials:

```python
username = 'your_email'
password = 'your_facebook_password'
```
Run the script to start scraping vehicle listings from Facebook Marketplace:

```bash
python web_scraping.py
```
The images will be downloaded and saved in the ws_data_fb directory.

Code Structure
web_scraping.py: Main script for web scraping Facebook Marketplace for vehicle listings.
output/: Folder where downloaded images will be stored.
README.md: This documentation file.
Contributing
Feel free to fork the repository and contribute by creating pull requests. If you encounter any issues or bugs, please open an issue in the repository.

License
This project is open-source and available under the MIT License.

Acknowledgments
Selenium: For automating web browsing.
BeautifulSoup: For parsing HTML data.
Facebook Marketplace: For providing the dataset of vehicle listings.

To use it:
1. Go to your repository on GitHub.
2. Click on the **"Add file"** button and choose **"Create new file"**.
3. Name the file `README.md`.
4. Paste the content above into the file editor.
5. Click **"Commit new file"** to save it.

Let me know if you need further adjustments!
