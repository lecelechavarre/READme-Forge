ReadMe Forge
A simple tool to create professional README files for your projects.

What It Does
Create README files with a simple form

See live preview as you type

Upload screenshots easily

Get AI-generated descriptions (optional)

Export directly to GitHub

Download as Markdown file

Quick Start
1. Install Backend
```bash
cd backend
python -m venv venv
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
pip install -r requirements.txt
```
2. Install Frontend
```bash
cd frontend
npm install
```
3. Run the App
Terminal 1 - Backend:

```bash
cd backend
source venv/bin/activate
python app.py
Terminal 2 - Frontend:
```
```bash
cd frontend
npm run dev
```
4. Open Browser
```
Go to: http://localhost:5173
```

How to Use
-Fill out the form with your project details

-See live preview on the right side

-Upload screenshots by dragging and dropping

-Click "Export README" to download or push to GitHub

Setup API Keys (Optional)
Create backend/.env file:
```
env
OPENAI_API_KEY=your_openai_key_here
```
