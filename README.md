This Python script uses OpenCV and MediaPipe to detect and count push-ups in real-time using your webcam.

How It Works:
MediaPipe Pose detects key body landmarks, such as the shoulder, elbow, and wrist.
The script calculates the angle between these points to determine the position of your arms during a push-up.
A push-up is counted when your arms extend (angle > 160°) after bending them (angle < 90°).
A cooldown period is added to prevent counting multiple push-ups at the bottom position.
