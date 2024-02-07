 # Bizcard_easyocr: which extracts data from business cards using Optical Character Recognition (OCR) and allows users to interact with the extracted data.

# Overview:

• Purpose: Bizcard_easyocr is a Streamlit web application designed for extracting data from business cards using OCR.

•	Functionality: Users upload an image of a business card, and the application extracts relevant information using the easyOCR library.
 The extracted information is then displayed in a user-friendly format and can be stored in a MySQL database for future reference.The application allows users to view, modify, or delete the extracted data. It also has a user interface for uploading business card images and a table interface for displaying the extracted data.

 # Prerequisites:
•	Python Environment: Requires Python 3.x with certain libraries installed (Streamlit, Pandas, easyOCR, PIL, cv2, matplotlib, re, mysql-connector-python).

•	MySQL Server: Requires a MySQL server set up and running.

# Features:
1.	Home: Provides an overview of the app, including technologies used and a brief description.
	
2.	Upload & Extract: Allows users to upload business card images, processes them, and extracts data such as company name, card holder name, designation, mobile number, email, website, area, city, state, pin code, and the image of the card.
  
3.	Modify: Enables users to select entries from the database, update or delete them, and commit changes to the database.

# How to Run:
1.	Clone or Download: Clone the repository or download the Python script.
	
2.	Run Script: Execute the script using the command line: streamlit run app.py.
	
3.	Access Application: The application will open in a new tab of your web browser, where users can interact with it.
	
4.	Database Setup: Ensure the MySQL server is running, and the database details in the script match your MySQL setup.
	
Note: It's important to ensure the MySQL server is running and that the database details in the script are correctly configured to match your MySQL setup for the application to work properly.








