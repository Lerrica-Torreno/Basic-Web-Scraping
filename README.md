# Basic-Web-Scraping 
This is a Laboratory Work #1 in System Fundamentals that scrapes the data in Starlink using a Python program supplemented by a JSON file from the Starlink website. 

# Steps on how to use it 
1. Place the `WebScraper.py` file and your extracted `starlink_data.json` file together into the exact same folder on your computer.
2. Open your system's Terminal (macOS/Linux) or Command Prompt/PowerShell (Windows).
3. Navigate to your project folder directory using the `cd` command:
   ```bash
   cd path/to/your/project/folder

# Requirements 
- json
- csv
- datetime
- json file (starlink_data)

# Setup 
Create a file named `WebScraper.py` in the same directory as your `starlink_data.json` file and paste the following implementation code

# Setup for JSON File 
1. Navigate to the  subscription section of your Starlink account portal.
2. Right-click anywhere on the page and select **Inspect**.
3. Click on the **Network** tab at the top of the Developer Tools panel and select the **Fetch/XHR** filter.
4. Refresh the page, locate the network request containing the `annotated` data structure, and copy the entire text from the **Response** tab.
5. Open your project folder in VS Code, create a new file named `starlink_data.json`, and paste the copied response data directly into it.
   
# Output 
The output would be a csv file (starlink_daily_usage.csv) that has 2 columns, namely the date and the data usage 
