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

![Screenshot (20)](https://github.com/user-attachments/assets/40b3f725-b170-4917-a9fb-3c23af240e01)

![Screenshot (21)](https://github.com/user-attachments/assets/427bd702-be10-4b96-b751-c5ae2d37953d)

![Screenshot (22)](https://github.com/user-attachments/assets/3f372fc1-07d2-4563-9c66-c4a2746be54d)
