# Intelligent-Driver-Drowsiness-Detection-and-Accident-Alert-System
An AI-powered Drowsiness Detection System that monitors driver alertness in real time using computer vision. It detects eye closure and yawning patterns through webcam input and triggers an alert to prevent accidents.


git clone https://github.com/<your-username>/drowsiness-detection-system.git
cd drowsiness-detection-system
🧱 Step 2: Create a Virtual Environment (Recommended)
To avoid dependency conflicts, create a virtual environment:

bash
Copy code
python -m venv venv
Activate it using:

Windows:

bash
Copy code
venv\Scripts\activate
Mac/Linux:

bash
Copy code
source venv/bin/activate
📦 Step 3: Install the Required Dependencies
Now install all dependencies from the requirements file:

bash
Copy code
pip install -r requirements.txt
If you don’t have a requirements.txt file, create one and paste this content:

text
Copy code
opencv-python
dlib
imutils
numpy
scipy
If dlib installation fails:

Install CMake and Visual Studio Build Tools (for Windows)

Then run:

bash
Copy code
pip install cmake
pip install dlib
🧠 Step 4: Download the Facial Landmark Predictor
The model file shape_predictor_68_face_landmarks.dat is required by dlib to detect facial landmarks.

Download it from:
👉 https://github.com/davisking/dlib-models

After downloading, place the file inside your project folder:

perl
Copy code
drowsiness-detection-system/
│
├── drowsiness_detection.py
├── shape_predictor_68_face_landmarks.dat
└── requirements.txt
🖥️ Step 5: Run the Project
Once everything is set up, start the system with:

bash
Copy code
python drowsiness_detection.py
Your webcam will open, and the live feed will start displaying:

“Eyes Open” / “Eyes Closed”

“Yawning” messages

“DROWSINESS ALERT!” when fatigue is detected

❌ Step 6: Stop the System
Press the q key on your keyboard to safely close the webcam window and exit the program.

🧩 Example Output
Here’s an example of what you’ll see in the terminal and video window:

mathematica
Copy code
Eyes Closed
DROWSINESS ALERT!
Yawning
Yawn Count: 3
Real-time contours will be drawn around your eyes (yellow) and mouth (green) while monitoring.

📂 Project Structure
perl
Copy code
drowsiness-detection-system/
│
├── drowsiness_detection.py          # Main Python script
├── shape_predictor_68_face_landmarks.dat  # Pre-trained dlib model
├── requirements.txt                 # Dependencies file
└── README.md                        # Project documentation
🧾 Requirements
List of all Python packages required:

text
Copy code
opencv-python
dlib
imutils
numpy
scipy
You can install them at once using:

bash
Copy code
pip install -r requirements.txt
🚀 Future Enhancements
Add audio alarms when drowsiness is detected

Connect with IoT systems for vehicle integration

Display real-time dashboard for performance monitoring

Log drowsiness statistics over time

Add mobile notification alerts

👨‍💻 Author
Your Name
Developer & Maintainer
📧 Email: your-email@example.com
🔗 GitHub: @your-username

📜 License
This project is licensed under the MIT License.
You’re free to use, modify, and distribute this project with proper attribution.

🧠 Stay Safe and Stay Awake!
yaml
Copy code

---

Would you like me to automatically generate a matching **`requirements.txt`** file (with compatible versions for Python 3.10–3.12) so that users can install it error-free when they clone your repo?




give me readme compiling everything in one single readme fill and please make it clean and understandaballe
