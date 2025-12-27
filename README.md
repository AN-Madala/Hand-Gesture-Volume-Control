This project is an AI-driven Gesture Volume Controller that allows users to manage their system audio levels, mute sound, and exit the application using only hand gestures. It leverages Computer Vision and Machine Learning to provide a touchless interface.

The system utilizes MediaPipe to track 21 distinct hand landmarks in real-time. By calculating the distance between specific finger joints and the palm, the script interprets user intent:
Volume Adjustment: Measures the distance between the Thumb (Tip 4) and Index Finger (Tip 8).
Mute: Triggered when all fingers are curled into a fist.
Safety Exit: Triggered when all fingers are fully extended, providing a hands-free way to close the app.
