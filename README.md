# 🏡📊 Autodom Data Analysis Project

## 🔍 Overview
The **🏡📊 Autodom Data Analysis Project** is an 🌐 end-to-end 🛠️ data processing pipeline designed to analyze 🏠 real estate data from autodom.pl. The project involves 🕵️‍♂️ data scraping, 🔄 transformation, and 📈 analysis to extract valuable 🔎 insights into the 🏘️ property market in 🇵🇱 Poland.

## ⭐ Features
- **🕵️‍♂️ Data Scraping**: Collected 🏠 real estate data from autodom.pl using 🛠️ Bright Data.
- **💾 Data Storage**: Stored 📂 raw and 📊 structured data in ☁️ Snowflake.
- **🔄 Data Transformation**: Converted 📍 latitude and longitude to 📌 addresses using the 📡 Geocode API and translated 📜 property titles from 🇵🇱 Polish to 🇬🇧 English using the 🌎 Google Translator API.
- **📈 Data Analysis**: Executed 🔢 SQL queries to generate 📊 market insights and visualized data using 📊 Snowflake dashboards.

## 🛠️ Technologies Used
- **🛠️ Bright Data**: Web scraping 🌐 platform.
- **☁️ Snowflake**: Cloud-based 💾 data warehouse for 📊 storage and 🔎 querying.
- **🐍 Python**: Used for 🔄 data processing and 🌎 API integration.
- **🔢 SQL**: For data 🔄 transformation and 📈 analysis.
- **📡 Geocode API**: To resolve 📍 geographic coordinates into 📌 addresses.
- **🌎 Google Translator API**: For translating 📜 property titles.

## ⚙️ Installation & Setup
### 🔧 Prerequisites
Ensure you have 🐍 Python and the required 📦 dependencies installed:
```bash
pip install pandas requests snowflake-connector-python
```

### ❄️ Setting Up Snowflake
1. Create a ☁️ Snowflake account and set up a 🗄️ database.
2. Import the 📂 raw JSON data into ☁️ Snowflake.
3. Use 🔢 SQL queries to 🔄 flatten and 🛠️ process the data.

### 🚀 Running the Script
1. Run the 🐍 Python script to 📡 fetch and 🔄 transform data:
   ```bash
   python data_processing.py
   ```
2. Execute 🔢 SQL queries in ☁️ Snowflake to generate 📊 insights.
3. 📊 Visualize results using ☁️ Snowflake’s 📈 dashboard features.



---
### 👤 Author
Parth Shah  
🐙 GitHub: https://github.com/Parth639  
💼 LinkedIn: https://www.linkedin.com/in/parth-shah-68695b281/

