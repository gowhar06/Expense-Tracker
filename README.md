# Smart Expense Tracker Web App

Smart Expense Tracker is a full-stack web application that helps users manage, analyze, and optimize their expenses with both manual input and smart file-based automation. It supports file uploads like PDF, Excel, Word, and image files, extracts data using OCR and parsing, and provides visual and AI-powered insights into the user's spending habits.

## Features

- User authentication (register/login/logout)
- Manual expense entry with category, date, amount, and note
- Upload files: PDF, Excel, Word, Image formats
- Automatic extraction of expenses using Python-based parsers
- Visualization of expenses using pie and line charts
- Monthly PDF report generation
- Budget limit alerts
- Detection of recurring and wasteful expenses
- AI chatbot for answering expense-related questions
- Expense prediction based on past behavior

## Tech Stack

- Frontend: React.js, Tailwind CSS, Chart.js
- Backend: Node.js, Express.js
- File Parsing & OCR: Python (Flask), pytesseract, pandas, PyMuPDF, python-docx
- Database: MongoDB or PostgreSQL
- Authentication: JWT, bcrypt
- File Storage: Firebase or Cloudinary

## Folder Structure


## Setup Instructions

1. Clone the repository  
   `git clone https://github.com/your-username/expense-tracker.git`

2. Install backend dependencies  

3. Install frontend dependencies  

4. Set up Python environment and install dependencies  

5. Create `.env` files for backend, frontend, and Python parser with required configuration

6. Start all servers  
- Python parser: `python app.py`  
- Backend API: `npm start`  
- Frontend: `npm start`

## Supported File Types

- PDF (`.pdf`)
- Word (`.docx`)
- Excel (`.xlsx`, `.xls`)
- Images (`.jpg`, `.jpeg`, `.png`)

## Libraries Used

- PyMuPDF, pdfplumber – PDF extraction
- pytesseract – OCR for images
- pandas, openpyxl – Excel parsing
- python-docx – Word file parsing
- Chart.js – For chart visualizations
- JWT – Authentication tokens
- bcrypt – Password hashing
- spaCy, Scikit-learn – NLP and categorization
- ReportLab – PDF report generation

## Example Use Flow

1. User signs up and logs in
2. Uploads a bill image or PDF
3. The system parses and extracts expenses
4. The extracted entry is added automatically
5. User views updated charts and insights
6. AI chatbot answers queries like "Where did I spend the most last month?"
7. Monthly report is generated and downloadable

## License

This project is licensed under the MIT License.
