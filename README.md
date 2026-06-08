Fake Job Posting Detection System

A Machine Learning-powered web application that detects fraudulent job advertisements by analyzing job descriptions, images, URLs, and CSV files. The system uses Natural Language Processing (NLP), OCR, and classification algorithms to help job seekers identify fake recruitment postings and avoid online job scams.

Features
📝 Job Description Analysis
Analyze job descriptions in real-time
Detect suspicious keywords and fraudulent patterns
Classify job postings as Real or Fake
🖼️ Image-Based Job Detection
Upload job poster screenshots
Extract text using OCR
Analyze extracted content for fraud indicators
🌐 URL Analysis
Verify job posting URLs
Detect suspicious or potentially fraudulent websites
Analyze website content for authenticity
📊 CSV Bulk Analysis
Upload CSV files containing multiple job postings
Perform batch fraud detection
Generate results for all uploaded entries

Technical Stack:
Backend
Python
Flask
Scikit-learn
Pandas
NumPy
Machine Learning
Logistic Regression
Random Forest
Naïve Bayes
TF-IDF Vectorization
OCR

Frontend:
HTML
CSS
JavaScript


Installation:
Install Python
Download and install Python from the official website.

Install Flask
Open Command Prompt or VS Code Terminal and run:
pip install flask

Open Project Folder
cd fake_job_detector

Verify Project Files
dir

This command displays all project files and folders.

Usage
Run the Application
python app.py

Access the Application
After starting the server, open your browser and visit:
http://127.0.0.1:5000

Application Features
Job Description Analysis:
Enter job details and description.
The system analyzes the content using NLP techniques.
Predicts whether the job posting is Real or Fake.
Image Scan:
Upload a job advertisement image.
OCR extracts text from the image.
The extracted content is analyzed by the machine learning model.
URL Analysis:
Submit a job posting URL.
The system evaluates the website and predicts authenticity.
CSV File Analysis:
Upload a CSV file containing multiple job postings.
The system performs bulk analysis and generates prediction results.

Output:
Real Job Posting
Fake Job Posting
Prediction Results
User Dashboard
Scan History

Future Enhancements
Deep Learning-based Fraud Detection
Advanced URL Threat Analysis
Improved OCR Accuracy
Real-Time Job Portal Integration
Mobile Application Support
Impact
Protects job seekers from recruitment scams
Reduces the risk of financial and identity fraud
Automates job posting verification
Improves trust in online recruitment platforms
License

This project is developed for educational and research purposes.
