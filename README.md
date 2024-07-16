# HK-House-Price-Prediction Web App

## Architecture
![image](https://github.com/user-attachments/assets/c754845b-925e-4b28-9c8b-f964c61162f6)

## Dataset:
[https://www.kaggle.com/datasets/joebeachcapital/s-and-p500-index-stocks-daily-updated](https://www.kaggle.com/datasets/cyrusttf/hong-kong-housing-price-2020-2023)

### Key Features:
- **Price Prediction**: Predicts the price of HK houses based on critical features including flat area, rental or non-rental, public or private housing, and district. Introduced a new feature called "unlucky 
                        floors" which include floor numbers that are considered unlucky in Chinese culture, which users may want to avoid.
- **User Interface**: Users can input their desired features and the web app will return a predicted price.
- **Cloud Integration**: Hosting the web app on AWS EC2 instance to allow access of the web app from a AWS provided DNS.

## 🛠 Project Workflow

1. **Data Extraction**: 
   - The dataset was sourced from Kaggle, containing raw HK housing prices data from 2020-2023.
   
2. **Data Cleaning**: 
   - Python and Pandas were utilized to clean and preprocess the dataset (Data Cleaning and Machine learning models(final).ipynb)
   - Features: "Saleable area", "District", "Rental", "Public Housing", "Unlucky Floors"
   - Prediction: "Price"

3. **Machine Learning prediction**:
   - Performance of 3 Scikit-Learn models were compared:
     ![image](https://github.com/user-attachments/assets/5c6ff1f0-d8af-414d-ad7f-ed1adcced16c)
   - Decision Tree was chosen, testing: 
     ![image](https://github.com/user-attachments/assets/e1ffcec7-b65f-45ea-a0a7-3ad6eeb93bc0)

**WORKING ON...**     
4. **Creating Python Flask Server and Nginx Web App**: <br>
**Prototype**:<br>
![image](https://github.com/user-attachments/assets/7ff97c96-141a-4fe9-b304-562ece865187)

6. **Hosting Web App on AWS EC2 instance**:
