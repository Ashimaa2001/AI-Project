# Real-time Face Masking with emoji augmentation

This project implements real-time face masking with emoji augmentation using the webcam feed. The program detects faces in the webcam feed and overlays an emoji on each detected face. After 20 seconds or when the 'q' key is pressed, the current frame is saved, and the emoji changes. The project includes three different emojis in total. Once all three augmented images are captured, a collage is displayed, showcasing the captured images.

<ins>How the Code Works</ins> -

- The program uses the haarcascade classifier for face detection in the webcam feed.
- When executed, the webcam feed starts, and faces are detected in real-time.
- The program overlays one of the predefined emojis on each detected face.
- If the 'q' key is pressed or after 20 seconds, the current frame is saved as an augmented image.
- The emoji changes, and the process continues to capture a total of three augmented images.
