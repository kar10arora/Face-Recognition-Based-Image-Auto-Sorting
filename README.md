# Face-Recognition-Based-Image-Auto-Sorting
Automatically detect and recognize multiple faces in images using deep learning, and sort them into respective person folders based on identity. A great real-world use case similar to how Google Photos or iOS Photos app groups people.
🔍 Project Objective
This project aims to:

Train a face recognition model on labeled face data.

Automatically detect multiple faces in any image.

Predict each detected face’s identity.

Save the image to every corresponding person’s folder (if an image contains A, B, C → saved in folders A, B, and C).

🧠 Tech Stack
 Python 3.10+

📦 Libraries:

face_recognition (built on dlib)

OpenCV

scikit-learn

pickle

os, shutil

📌 Features
✅ Multi-face detection and recognition per image

✅ Supports any number of known identities

✅ Automatically creates person folders if not present

✅ Easy to scale — just add more training images!
