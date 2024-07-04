# SecureX
SecureX revolutionizes the process of finding missing persons by efficiently and accurately identifying individuals in surveillance footage, social media, and other digital sources. By comparing the victim’s image to a database of images, officials can quickly track a missing person's movements over time by identifying them in multiple images captured at different locations and creating a predictive route map. Additionally, the app can also track down possible suspects by identifying people who may have been in contact with the victim from the feed.

## Features
* Efficiently identifies missing persons in surveillance footage and social media.
* Compares the victim’s image to a database of images.
* Tracks the missing person's movements over time and generates a predictive route map.
* Identifies potential suspects who may have been in contact with the victim.
* Alerts authorities via email or popup message.

## Algorithm Steps
* Image Input: Provide the system with an image of the missing person.
* Data Processing: The algorithm processes the input through web/social media (APIs & web scraping) and live camera feeds.
* Face Detection: The system detects faces using YOLO (CNN).
* Face Comparison: Detected faces are compared using the face_recognition library.
* Data Extraction: If similarity is found, the system extracts the username, location, time/date, tagged people, etc., from social media and live camera feeds.
* Alerts: Alerts the concerned authorities via email (SMTP library) or a popup message.
* Predictive Route Map: Generates a predictive route map of the missing person's movements.

## How to run the code locally
- Running project locally
- establish a database by using 'police_data1.csv' file in MySQL.
- name the database ‘police_database' and create table with the required fields and name it 'missing_person'. 
- dowload all the essential libraries provided below :

- Pip install smtplib
- pip install customtkinter
- Pip install tkinter
- Pip install beautifulsoup4
- pip install dlib
- Pip install face_recognition
- Pip install csv
- Pip install requests
- Pip install mimestypes
- Pip install pillow
- Pip install pyautogui
- Pip install pycopy-webbrowser
- Pip install mysql-connector-python
- Pip install opencv-python

- save all the 'TEST IMAGES' and the ‘main.py' file in a single folder.
- dowload all files from the ‘REQUIREMENTS' folder into the same folder as that of ‘main.py' folder.

## Tech Stack used

- YOLO (You Only Look Once) : It is a state-of-the-art object detection algorithm that uses a Convolutional Neural Network (CNN) for real-time object detection.

 - Face_recognition :This library can detect faces in an image, and return the coordinates of the bounding boxes around each detected face.

- Tkinter : It is a standard Python library that provides a GUI (Graphical User Interface) toolkit for creating desktop applications with Python.

- PyAutoGUI : It provides cross-platform support for controlling the mouse, keyboard, and screen of a computer to automate tasks that involve GUI interactions.

- PIL (Python Imaging Library) : It provides tools for working with images in tkinter GUI applications.

- Mysql : Used for creating and managing the databases.
  
- Haar cascade classifier: an Object Detection Algorithm used to identify faces in an image or a real time video
  
- OPENCV: opencv is a Computer Vision library, overlaps with fields like Image Processing, Photogrammetry, and Pattern Recognition.
  
- BeautifulSoup : It is a popular Python library used for web scraping and parsing HTML and XML documents. 

## Screenshots

![WhatsApp Image 2023-03-17 at 11 58 31 AM (1)](https://user-images.githubusercontent.com/122262294/228805203-120af962-4cef-4bff-ac32-2696e888e7cc.jpeg)
![WhatsApp Image 2023-03-17 at 11 58 32 AM](https://user-images.githubusercontent.com/122262294/228805318-292813dc-165c-41f3-a39d-17d6116110fd.jpeg)
![WhatsApp Image 2023-03-17 at 11 58 32 AM (1)](https://user-images.githubusercontent.com/122262294/228805558-fe9ba56d-f193-4528-9528-ba9d46be5149.jpeg)

![WhatsApp Image 2023-03-17 at 11 58 32 AM (2)](https://user-images.githubusercontent.com/122262294/228805396-06e17e60-4e67-4949-ad1d-2e7aba748dde.jpeg)

![WhatsApp Image 2023-03-17 at 11 58 33 AM](https://user-images.githubusercontent.com/122262294/228805625-53dbb832-2722-482f-a2fb-a52a2ba073d6.jpeg)
![WhatsApp Image 2023-03-17 at 11 58 34 AM](https://user-images.githubusercontent.com/122262294/228805653-a5d852c3-4647-42d3-808e-23268d49179e.jpeg)
