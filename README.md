SheGuard AI
Hybrid Forensic Deepfake Detection Engine

 Project Overview
SheGuard AI is an AI-powered web application designed to detect whether a facial image is real or AI-generated (Deepfake). With the rise of AI-generated media, deepfakes are becoming increasingly convincing, posing threats such as identity fraud, misinformation, and digital impersonation attacks.
SheGuard AI provides a reliable, user-friendly solution to this problem by combining:
•	Deep learning-based image classification: Detects subtle facial anomalies invisible to the human eye.
•	Digital forensic signal analysis: Examines inconsistencies in image compression, noise, and metadata.
By merging these approaches, SheGuard AI ensures higher accuracy and robust detection compared to conventional single-method systems.

Tech Stack
Frontend
•	HTML5
•	CSS3
•	JavaScript
Backend
•	Python 3.14.3
•	Flask
AI / ML
•	NumPy
•	OpenCV
•	Pillow
Tools
•	Git
•	VS Code

 Key Features
•	AI-powered Deepfake Detection
•	Real-time Image Upload & Preview
•	 Prediction with Probability Score
•	 Clean, Responsive UI
•	 Secure File Handling
•	 Loader Animation During Processing
•	Flask-based Backend API
Why SheGuard AI?
•	Reduces the spread of fake media online
•	Protects personal identity and digital reputation
•	Easy-to-use web interface for quick verification

Installation
Clone the Repository
git clone https://github.com/Nikshiptha102024/aidetector123/tree/main 
 Create & Activate Virtual Environment
Install Dependencies
pip install -r requirements.txt

Running the Application
python app.py
Open your browser and visit:
http://127.0.0.1:5000

Screenshots
 Homepage UI
  <img width="940" height="464" alt="image" src="https://github.com/user-attachments/assets/e8d26c57-ae2c-453c-80cc-d76e3a20a9ff" />



Image Upload & Preview
 <img width="940" height="469" alt="image" src="https://github.com/user-attachments/assets/618b3e4a-9636-4b5e-8a46-8f85b51a97d9" />

 
Prediction Result
 

<img width="940" height="468" alt="image" src="https://github.com/user-attachments/assets/b6e96def-e9cc-4038-9306-7741e31382c4" />



 Architecture
 <img width="916" height="407" alt="image" src="https://github.com/user-attachments/assets/d55dedf1-99c4-43b8-8f48-be6cbbcc54b7" />



 API Endpoints
 Homepage
•	Endpoint: /
•	Method: GET
•	Description: Returns the homepage.
 Image Upload & Prediction
•	Endpoint: /
•	Method: POST
•	Request Type: multipart/form-data
•	Parameter: image → Uploaded image file
Response:
•	Prediction Label → Real / Fake
•	Probability Score → real - around 10 - 25% , fake images - 80 - 95 %

Team Members
Devara Nikshiptha – ai ,backend 
Bevara Hima Varshitha – front end 

 License
 
This project is licensed under the MIT License. You are free to use, modify, and distribute this project with proper attribution.


 Future Enhancements
Hybrid Feature + CNN Approaches
Pretrained Deep Learning Models
Frequency Domain Analysis
