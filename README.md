# CareerCraft - ATS-Optimized Resume Analyzer Documentation

## Project Overview

**Project Name:** CareerCraft - ATS-Optimized Resume Analyzer  
**Description:** CareerCraft is a powerful platform designed to help job seekers optimize their resumes for better alignment with job descriptions using advanced Applicant Tracking System (ATS) techniques. This system analyzes resumes against job descriptions, identifies missing keywords, and offers personalized recommendations to enhance resume compatibility, skill development, and career progression.

### Key Features:

1. **Resume Optimization:**
   - Analyzes resumes and job descriptions to determine the percentage match.
   - Identifies missing keywords and provides recommendations to improve alignment with job roles.
   - Helps job seekers optimize their resumes to increase the chances of securing interviews.

2. **Skill Enhancement:**
   - Compares resumes with job descriptions to identify skill gaps.
   - Offers personalized recommendations for skill improvement and development based on industry standards.
   
3. **Career Progression Guidance:**
   - Provides strategic insights into career trajectories by analyzing resumes and job descriptions.
   - Identifies relevant skills and experiences for career growth.
   - Offers personalized recommendations to help professionals achieve their career goals.

## Technology Stack

- **UI Framework:** Streamlit
- **PDF Handling:** PyPDF2
- **Natural Language Processing (NLP):** Google Generative AI (Gemini Model)
- **Email Functionality:** SMTP (via smtplib) for handling contact messages
- **Image Processing:** PIL (Python Imaging Library)
- **Environment Variables Management:** Python `dotenv`

## Installation and Setup

### Prerequisites:

- Python 3.x
- Pip (Python package manager)

### Steps to Run the Application:

1. **Clone the Repository:**

   Clone the project repository from GitHub to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. **Create and Activate a Virtual Environment:**

   Navigate to the project directory and create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

   Activate the environment:
   - For Windows:
     ```bash
     venv\Scripts\activate
     ```
   - For macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install Required Packages:**

   Install all required dependencies listed in the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Environment Variables:**

   Create a `.env` file in the project root directory and add the following variables:
   ```bash
   EMAIL_ADDRESS=your-email@example.com
   EMAIL_PASSWORD=your-email-password
   GOOGLE_API_KEY=your-google-api-key
   ```

5. **Run the Application:**

   Start the application using Streamlit:
   ```bash
   streamlit run app.py
   ```

6. **Access the Application:**

   Once the server is running, open a browser and navigate to `http://127.0.0.1:8501/` to access the web interface.

## Usage

1. **Upload Resume:**
   - Upload your resume in PDF format using the file uploader.

2. **Job Description Analysis:**
   - Paste the job description into the text area provided.

3. **Get Insights:**
   - The system will analyze the resume against the job description using the Gemini Model and provide the following:
     - **Match Percentage:** A score representing how well your resume aligns with the job description.
     - **Missing Keywords:** A list of important keywords that are missing from your resume.
     - **Profile Summary:** A tailored summary to improve your resume’s presentation.

4. **Contact Us:**
   - Users can send feedback or questions directly via the Contact Us section, which uses SMTP to send emails.

## Contributing

Contributions are welcome! If you'd like to contribute to CareerCraft, follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

**Contact Information:**  
For support or inquiries, contact us at `singhsidver@gmail.com`.
