# BizCardX-Extracting-Business-Card-Data-with-OCR
## Introduction

BizCardX is a Streamlit application that effortlessly streamlines business card data extraction through advanced OCR technology. Users can easily upload card images to retrieve essential details, including company names, cardholder names, contact information, and more. With a strong focus on data security and user authentication, BizCardX ensures secure data storage and offers streamlined management via the user-friendly Streamlit UI. Experience an efficient, secure, and user-friendly solution for managing business card information effortlessly with BizCardX.

* To run this project, you need to install the following packages:
  
       pip install easyocr 
          
       pip install numpy
          
       pip install pandas
          
       pip install sqlite3
          
       pip install streamlit
    
       pip install streamlit_option_menu

* Features

      BizCardX offers a range of powerful features to streamline the extraction and management of business card information with a strong emphasis on data protection.

* E T L Process
  
      a) Extract data
        
           * Extract relevant information from business cards by using the easyOCR library
             
      b) Process and Transform the data
        
           * After the extraction process, process the extracted data based on,Name, Company name,  Designation, Mobile Number, Email, Address, and Pincode is converted into a data frame.
             
      c) Load data
        
           * After the transformation process, the data is stored in the SQLITE3.

## User Guide

Step 1. Data collection zone

    Click the 'Browse Files' button and select an image
  
Step 2. Data upload

    Click the 'Upload' button to upload the data to the sql database
   
Step 3. Modification zone

    In this 'Modification zone' you can able to modify the information also you can delete the previous data
    
## Project Overview
BizCardX aims to simplify the process of extracting and managing information from business cards. The tool offers the following features:

    * Extraction of key information from business cards: company name, cardholder name, designation, contact details, etc.
    
    * Storage of extracted data in a MySQL database for easy access and retrieval.
    
    * GUI built with Streamlit for a user-friendly interface.
    
    * User options to upload, extract, and modify business card data.
    
* Contact

📧 Email: suvetha0520@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/suvetha-soubrayen-82a072190/
  
