# Virtual-Mouse-AI---Hand-Gesture-Control
Control your computer  without a physical mouse. This project uses  AI, Computer Vision, and Hand Gesture Recognition to create a **Virtual Mouse** powered by "Python, OpenCV, MediaPipe, and PyAutoGUI". 

Project Description:-
Virtual Mouse AI is an innovative computer vision project that enables users to control their computer cursor and perform mouse actions using hand gestures. Built with Python and leveraging AI-powered hand       tracking, this system converts your hand movements into precise computer commands in real-time.

Feature	Emoji	Description:-
    Cursor Control	🖱️	Move cursor by pointing with index finger
    Left Click	👆	Pinch thumb and index finger together
    Right Click	🤞	Show index and middle fingers
    Drag & Drop	🎯	Pinch and hold while moving hand
    Smooth Scrolling	📜	Two-finger vertical movement
    Real-time Tracking	🔄	Live hand landmark detection
    Visual Feedback	👁️	On-screen hand skeleton display

Tech Stack:-
    AI & Computer Vision: MediaPipe, OpenCV
    Programming: Python 3.8+
    GUI Automation: PyAutoGUI
    Math & Arrays: NumPy
    Camera Input: OpenCV Video Capture

Project Structure:-
    virtual-mouse-ai/
    │
    ├── main.py                 # Main application controller
    ├── hand_tracking.py        # Hand detection and landmark tracking
    ├── gesture_logic.py       # Gesture recognition and screen mapping
    ├── mouse_control.py       # Mouse action implementations
    ├── utils.py               # Smoothing and utility functions
    ├── requirements.txt       # Project dependencies
    └── README.md 


Hand Gesture Guide:-
    "Gesture"      	"HandPosition"            "Action"                 "Visual"
    Cursor Move  	Index finger              extended	Moves cursor	  👆
    Left Click  	Thumb & index pinch	      Single click	            🤏
    Right Click  	Index + middle fingers	  Right-click              	🤞
    Drag & Drop	  Pinch and move	          Drag items              	🎯
    Scroll	      Two fingers vertical  	  Page scroll              	📜
    Exit	        Press ESC key	            Close application        	⏹️


Installation & Setup:-
  Step 1: Clone the Repository
  git clone https://github.com/yourusername/virtual-mouse-ai.git
  cd virtual-mouse-ai
    
  Step 2: Create Virtual Environment (Recommended)
  python -m venv Myvenv
  # On Windows:-
  Myvenv\Scripts\activate
  # On Mac/Linux:-
  source venv/bin/activate
  
  Step 3: Install Dependencies
  pip install -r requirements.txt
  
  Step 4: Run the Application
  python main.py


How It Works:-
    - Capture Webcam Feed using OpenCV.
    - Detect Hand Landmarks (21 points) with MediaPipe.
    - Extract Key Points (index tip, thumb tip, etc.).
    - Map Coordinates from camera space → screen space.
    - Apply Smoothing to reduce jitter.
    - Recognize Gestures (pinch, two-finger, etc.).
    - Trigger Mouse Actions via PyAutoGU


<img width="641" height="511" alt="Virrtual_Mouse" src="https://github.com/user-attachments/assets/69c3e4e5-1ca4-4fcf-980e-c4ee80b01643" />

