# pdf_to_html_using_openAI_API

**Setup Instructions**
Prerequisites
1)Python 3.x
2)Flask
3)OpenAI API key


**Installation**
1.Clone the Repository:
--> git clone <YOUR_REPOSITORY_URL>
cd <REPOSITORY_DIRECTORY>

2.Create and Activate a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3.Install Dependencies:
pip install -r requirements.txt

4.Set Up Environment Variables:
OPENAI_API_KEY=your_openai_api_key_here

**Running the Application**
1.Start the Flask Server:
python app.py

2.Access the Application:
Open a browser and navigate to http://localhost:5000.

**Usage**
1.Upload a LinkedIn PDF:
Click on the "Upload PDF" button.
Select the LinkedIn PDF file from your local machine.

2.Generate HTML Resume:
After uploading, the application will process the PDF using OpenAI’s API.
The extracted data will be converted into an HTML resume.

3.Download HTML Resume:
A link to download the HTML resume will be provided once the processing is complete.

**Troubleshooting**
1.Rate Limit Errors: Ensure that your OpenAI API key has sufficient quota. Check OpenAI’s API documentation for more information.
2.File Upload Issues: Ensure the PDF is correctly formatted and not corrupted.

**Deployment**
This application is deployed on GitHub Pages. You can access the live version at:
http://127.0.0.1:5000/

**Acknowledgments**
1.Flask Documentation
2.OpenAI API Documentation
3.GitHub Pages Documentation

**Contact**
For any questions or issues, please contact:
Email: Pujarinavyasree2003@gmail.com
