# AI-Virtual-Painter
Built a Virtual Painter🎨 using Python + OpenCV! 
  This is a Virtual Painting App powered by computer vision and hand tracking, no mouse, no touchscreen, just your fingers and a webcam!
 -- Technologies & Libraries Used:
OpenCV: For real-time video processing and drawing.
NumPy: To manage the canvas as a matrix and perform image blending.
Custom Hand Tracking Module (MediaPipe-based): For accurate hand landmark detection.
cv2.flip & thresholding: To align camera mirror image and merge drawing with live feed.
Python: The language that makes all this magic happen.
 -- How it Works:
📸 Webcam feed is captured and mirrored.
✋ Hand landmarks are detected using a custom hand tracking module.
🖐️ Two fingers up = Selection Mode (Choose brush color or eraser).
☝️ One finger up = Drawing Mode (Start painting with your finger!).
🧽 Use black color as an eraser for cleanup.
🎨 Paint is drawn onto a transparent canvas and blended with the camera feed in real time
