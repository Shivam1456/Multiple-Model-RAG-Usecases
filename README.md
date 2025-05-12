# Multiple-Model-RAG-Usecases

✅ Steps to Run a Cloned Flask App in VS Code
1. Clone the Repository
In the terminal:

git clone https://github.com/satyamjaysawal/Multiple-Model-RAG-Usecases.git
cd Multiple-Model-RAG-Usecases
Replace the URL with your actual GitHub repo link.

2. Open the Project in VS Code
code .

3. Create and Activate a Virtual Environment
# Create
python -m venv venv

# Activate
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

4. Install Dependencies
pip install -r requirements.txt

5. Create a .env File (Optional but Recommended)
In the project root, create a file named .env with:

GOOGLE_API_KEY=
FLASK_SECRET_KEY=
MONGO_URI=
QDRANT_URL=
QDRANT_API_KEY=
Replace app.py with the actual entry point of your app (e.g., run.py, or a package name).

To use .env files automatically, install python-dotenv (if not already in requirements):

pip install python-dotenv
Flask will automatically read the .env file if python-dotenv is installed and you're using the Flask CLI.


6. Run the Flask App
flask run

7. Open in Browser
Go to: 📍 http://127.0.0.1:5000/


![Screenshot (12)](https://github.com/user-attachments/assets/a4d41e28-f2c4-44f4-b1e0-07ba0db83049)

![Screenshot (13)](https://github.com/user-attachments/assets/bdc5ef22-b3e7-47f1-a108-7cc3ed1b0ecd)
![Screenshot (17)](https://github.com/user-attachments/assets/a178f4d2-00bc-4708-9835-5cef952efb95)


![Screenshot (18)](https://github.com/user-attachments/assets/df93e492-492e-4461-a447-a78bf9c505a5)


![Screenshot (19)](https://github.com/user-attachments/assets/4b87371f-4a08-42b2-8cda-ff0c3a3fde60)
