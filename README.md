# Face-Detection


This is a Python script that uses OpenCV and face_recognition libraries to detect and recognize faces from a live video stream captured by the default camera.

The script loads a sample image of a known face, encodes it using the face_recognition library, and then compares it with the face encodings of the faces detected in the live video stream. If a match is found, it draws a green rectangle around the face and displays a greeting message with the name of the known person. If there is no match, it draws a red rectangle around the face and displays an "Unknown Face" message.

The script also uses the playsound library to play an audio file when a match is found or an unknown face is detected.

The script runs in an infinite loop until the user presses the 'q' key to exit. It captures each frame from the video stream, converts it to RGB format, and detects the face locations and encodings using the face_recognition library. Then, it compares the encodings with the known encoding and displays the appropriate message and rectangle around the face.

Overall, this script can be used for face recognition applications such as security systems, attendance systems, or personalized greeting systems.



