# BizCard-Extracting-Business-Card-Data-with-OCR

## What is EasyOCR?
As the name implies, EasyOCR is a Python library that enables Optical Character Recognition for computer vision engineers.It is a Python package that makes it simple to extract text from photos and scanned documents using optical character recognition (OCR). I am using easyOCR to extract text from business cards for my project.

## Project Description:
You are responsible for creating a Streamlit application that enables users to upload images of business cards and utilise easyOCR to extract pertinent data from them. The company name, cardholder's name, title, mobile number, email address, website URL, region, city, state, and pin code should all be included in the retrieved data. The graphical user interface (GUI) of the application should then show the retrieved data. Users should also be able to save the extracted data and the uploaded business card image into a database using the programme. Multiple entries, each with its own business card image and extracted data, should be able to be stored in the database.Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL are all required to accomplish this. The programme should feature an easy-to-use user interface that leads users through the uploading and information-extracting processes for business cards. Users should be able to simply add the extracted data to the database with a click and it should be presented to them in a clear and organised manner.Additionally, provide a streamlined user interface that enables the user to read, update, and delete data. For this project, you'll need expertise in database management, GUI development, image processing, and OCR. In order to make sure that the application architecture is scalable, manageable, and extensible, you will also need to properly plan and design it. The organisation of the code and the quality of the documentation are both crucial for this project.

## Approach:
* Install the needed software packages: Python, Streamlit, easyOCR, and a database management system like SQLite or MySQL must all be installed.

* User interface design: Utilise Streamlit to provide a user interface that makes it easy for users to upload business card images and retrieve their information. To make the UI more interactive, utilise widgets 
  like file uploaders, buttons, and text fields.

* Use easyOCR to extract the necessary information from the uploaded business card image after performing image processing and OCR. Before sending the image to the OCR engine, you can improve the image quality by using image processing techniques like resizing, cropping, and thresholding.

* Display the extracted data: After the data has been gathered, present it in the Streamlit GUI in an orderly and tidy fashion. To present the information, you can utilise widgets like tables, text boxes, and labels.
  
* Integrate databases in practise: Store the extracted data and the uploaded business card image using a database management system like SQLite or MySQL. You can create tables, insert data, and retrieve data from the database using SQL queries. Through the streamlined user interface, update the data and allow the user to delete the data.

* Test the programme: Make sure the programme operates as intended by thoroughly testing it. The command streamlit run app.py, where app.py is the name of your Streamlit application file, can be used to launch the application on your local computer.

* The programme should be continually improved by including new features, streamlining the code, and removing problems. To increase the application's security, you can also implement user authentication and permission.

## Results:
The project would produce a Streamlit application that enables users to upload an image of a business card and utilise easyOCR to extract pertinent information from it. The company name, cardholder's name, title, mobile number, email address, website URL, region, city, state, and pin code would all be included in the information that was taken. The graphical user interface (GUI) of the application would then show the retrieved data. Along with the uploaded image of the business card, users would also be able to save the extracted data into a database using the programme. Multiple entries, each with its own business card image and extracted data, might be stored in the database. The finished programme would include an easy-to-use user interface that directs users through the uploading and information-extracting processes for business cards. Users could simply add the extracted data to the database with a click after it was presented to them in a neat and organised manner. The project would involve expertise in database management, GUI development, image processing, and OCR. In order to make sure that the application architecture is scalable, manageable, and extensible, rigorous design and planning would also be necessary. For the project, clear documentation and well-organized code are also essential. Overall, the project's output would be a beneficial tool for organisations and people that need to effectively manage the information on business cards.


  


