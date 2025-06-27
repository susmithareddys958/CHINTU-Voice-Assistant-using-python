Hello coders!
In this post, I build a super cool Python project called CHINTU– Your Personal Voice Assistant.

It can:

✅ Listen to your voice
✅ Understand what you said
✅ Open Chrome or VS Code
✅ Play songs on YouTube
✅ Tell jokes
✅ Give you the current time
✅ Tell who someone is using Wikipedia
✅ And most importantly… it talks about you!
🛠️ Tools Required
Python 3.8 or above
VS Code (or any editor)
A microphone
Internet connection for YouTube/Wikipedia
Step 1: Create Project Folder
Open VS Code → Create a new folder:
🧪 Step 2: Set Up a Virtual Environment

Run this to create a virtual environment:
python -m venv venv

Activate it:
Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
You’ll see (venv) in your terminal – that means you’re good to go!

Step 3: Install Required Libraries
Run this to install all dependencies:

pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
Libraries Explained:
speech_recognition-Converts voice to text
pyttsx3-Converts text to speech (works offline)
pywhatkit-Used to play YouTube videos via voice
wikipedia-Fetches summary of people or topics
pyjokes-Tells random programming jokes
os / sys-To open apps or exit the assistant
