# ForsaDeals
Forsadeals: Price Comparison Platform
Overview
Forsadeals is a data-driven platform built to compare prices across flights, hotels, and market products. The platform allows users to compare prices in real time, making it easier for customers to make informed purchasing decisions. The platform also includes advanced machine learning models for segmentation and classification, ETL processing using Talend, and data visualization with Power BI.
Key Features
•	Flight, Hotel, and Product Price Comparison: Compare prices in real-time across three key sectors: Flights, Hotels, and Products.
•	Customer Feedback and Satisfaction: Visualize customer feedback with key performance indicators (KPIs) like Customer Satisfaction and Net Promoter Score (NPS).
•	Revenue Insights: Track total revenue, cost, and profit across the three sectors.
•	Machine Learning Models: Implement segmentation and classification models to identify customer behavior and personalize recommendations.
Technologies Used
•	Web Scraping: BeautifulSoup, Selenium (Python)
•	ETL: Talend
•	Data Visualization: Power BI
•	Machine Learning: Python (scikit-learn, TensorFlow)
•	Backend: Flask
•	Frontend: Angular
•	Database: SQL Server (SSMS)
Project Setup
Prerequisites
Ensure that the following software is installed:
•	Power BI Desktop (Latest Version)
•	Talend (for ETL processing)
•	Python (for Machine Learning models)
•	Node.js and Angular CLI (for front-end development)
•	SQL Server (for the database)
Install Dependencies
1.	Clone the Repository:
bash
Copy
git clone https://github.com/yourusername/forsadeals.git
cd forsadeals
2.	For Machine Learning (Python):
o	Install the necessary Python libraries:
bash
Copy
pip install -r requirements.txt
3.	For Angular Frontend:
o	Install Node.js and Angular CLI.
o	Install dependencies:
bash
Copy
npm install
4.	For Talend ETL:
o	Install Talend Studio and configure your ETL jobs.
________________________________________
Data Collection
Web Scraping Process
Data is collected through web scraping from various online platforms:
1.	Flight Data: Scraped from popular airline websites using BeautifulSoup and Selenium.
2.	Hotel Data: Scraped from hotel booking platforms.
3.	Product Data: Scraped from e-commerce websites.
________________________________________
ETL Process
The ETL (Extract, Transform, Load) process is handled using Talend, transforming raw data into structured formats before loading it into the database.
1.	Extract: Scraped data and API data are extracted.
2.	Transform: Data is cleaned and transformed.
3.	Load: Transformed data is loaded into SQL Server.
________________________________________
Data Visualization
Power BI is used for building interactive dashboards that give insights into various KPIs and business metrics, including:
1.	Price Comparison: Display comparison charts for flights, hotels, and products.
2.	Satisfaction: Show customer satisfaction trends and feedback.
3.	Revenue: Track revenue across the three sectors.
Key Visuals:
•	KPI Cards: Display metrics like average price, satisfaction, and customer retention.
•	Bar/Column Charts: Show comparison data across different sectors.
•	Line Charts: Display trends over time (e.g., customer satisfaction, bookings).
•	Maps: Visualize geographic data, such as popular destinations or booking regions.
________________________________________
Machine Learning Models
Customer Segmentation and Classification
The project includes machine learning models to segment customers and classify them based on behavior.
1.	Segmentation: KMeans Clustering is used to group customers based on their booking patterns and preferences.
2.	Classification: Logistic regression models predict whether a customer will book again based on historical data.
3.	Targeting: Models are used to identify customer behavior and personalize recommendations.
________________________________________
Integration with Flask
Flask serves as the backend for the application, allowing us to integrate machine learning models, data sources, and visualizations.
API Endpoints:
•	/api/flight-prices: Get flight price data.
•	/api/hotel-prices: Get hotel price data.
•	/api/product-prices: Get product price data.
•	/api/prediction: Use machine learning models for predictions based on user input.
________________________________________
Deployment Instructions
1. Deploying the Backend (Flask API):
•	Navigate to the backend directory and run:
bash
Copy
python app.py
2. Deploying the Frontend (Angular):
•	Navigate to the frontend directory and run:
bash
Copy
ng serve
3. Power BI Dashboard:
•	Open the Power BI Desktop file (.pbix), connect it to SQL Server for data loading, and publish the report to Power BI Service for sharing.
________________________________________
Roles and Permissions
Forsadeals features 7 distinct roles, each with specific access permissions:
1. Client
•	View flight, hotel, and product comparisons.
•	Access their own booking history and feedback.
2. Customer Executive (Flights)
•	Access to flight price comparison, revenue metrics, and customer feedback related to flights.
3. Customer Executive (Hotels)
•	Access to hotel price comparison, revenue metrics, and customer feedback related to hotels.
4. Customer Executive (Products)
•	Access to product price comparison, revenue metrics, and customer feedback related to products.
5. Finance Manager (Flights)
•	Access to financial KPIs for flights, including revenue, cost, and profit.
6. Finance Manager (Hotels)
•	Access to financial KPIs for hotels, including revenue, cost, and profit.
7. Finance Manager (Products)
•	Access to financial KPIs for products, including revenue, cost, and profit.
Each role has specific page permissions and visual restrictions to ensure relevant data is accessible.
________________________________________
Contributing
To contribute to this project, follow these steps:
1.	Fork the repository.
2.	Clone the repository to your local machine.
3.	Create a branch for your feature:
bash
Copy
git checkout -b feature-branch
4.	Make your changes, commit them, and push them to your branch.
5.	Submit a pull request for review.
________________________________________
License
This project is licensed under the MIT License - see the LICENSE file for details.
________________________________________
Contact
For more information or inquiries, please contact:
•	Name: (Your Name)
•	Email: (Your Email)
•	GitHub: @yourusername

