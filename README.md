
# Faceide: A Facial Recognition App Using Tkinter and Kivy

Faceide is a Python application that uses facial recognition to identify and verify people from images or videos. Faceide uses the [face_recognition](^1^) library, which is built on top of [dlib](^2^), a C++ toolkit for machine learning and computer vision. Faceide also uses [tkinter](^3^) and [kivy](^4^), two cross-platform GUI frameworks for Python, to create user-friendly interfaces for the app.

## Features

Faceide has the following features:

- **Face detection**: Faceide can detect faces in images or videos using the [HOG](^5^) (Histogram of Oriented Gradients) algorithm or the [CNN](^6^) (Convolutional Neural Network) model.
- **Face recognition**: Faceide can recognize faces in images or videos by comparing them with a database of known faces. Faceide uses the [face_recognition](^1^) library, which implements a state-of-the-art face recognition system based on [deep learning](^7^).
- **Face verification**: Faceide can verify if two faces belong to the same person by computing the [Euclidean distance](^8^) between their face embeddings. Faceide uses a threshold of 0.6 to determine if two faces are similar enough to be considered a match.
- **Tkinter interface**: Faceide has a simple and intuitive interface built with tkinter, which allows the user to select an image or video file, choose a face detection or recognition mode, and view the results in a new window.
- **Kivy interface**: Faceide also has an alternative interface built with kivy, which offers more features and customization options. The kivy interface allows the user to capture images or videos from the webcam, adjust the face detection or recognition parameters, and save the results to a file.

## Installation

To install Faceide, you need to have Python 3.6 or higher installed on your system. You also need to install the following dependencies:

- [face_recognition](^1^): A Python library for face recognition.
- [tkinter](^3^): A standard Python library for GUI development.
- [kivy](^4^): A Python framework for creating cross-platform applications.
- [opencv-python](^9^): A Python wrapper for OpenCV, a library for computer vision and image processing.
- [Pillow](^10^): A Python library for image manipulation.

You can install these dependencies using pip, a package manager for Python. To do so, run the following command in your terminal:

```bash
pip install face_recognition tkinter kivy opencv-python Pillow
```

Alternatively, you can use the `requirements.txt` file provided in this repository to install all the dependencies at once. To do so, run the following command in your terminal:

```bash
pip install -r requirements.txt
```

## Usage

To run Faceide, you need to clone this repository or download it as a zip file. Then, navigate to the project folder and run one of the following commands in your terminal:

```bash
python faceide_tk.py # to run the tkinter interface
python faceide_kv.py # to run the kivy interface
```

You will see a window with buttons and options to select an image or video file, choose a face detection or recognition mode, and view the results. You can also use the kivy interface to capture images or videos from your webcam, adjust the parameters, and save the results.

## Screenshots

Here are some screenshots of Faceide in action:

![Tkinter interface](tkinter_screenshot.png)
![Kivy interface](kivy_screenshot.png)

## License

Faceide is licensed under the [MIT License](LICENSE).

উত্স: Bing-এর সাথে বার্তালাপ, 8/25/2023
(1) Learn the Key Differences Between Kivy and Tkinter - EDUCBA. https://www.educba.com/kivy-vs-tkinter/.
(2) GitHub - kivy/kivy: Open source UI framework written in Python, running .... https://github.com/kivy/kivy.
(3) Kivy · PyPI. https://pypi.org/project/Kivy/.
(4) How to Write a Good README File for Your GitHub Project - freeCodeCamp.org. https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/.
(5) Quickstart for writing on GitHub - GitHub Docs. https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github.
(6) README.md: What Is It, How To Create It Yourself. https://markdown.land/readme-md.
(7) Learn the Key Differences Between Kivy and Tkinter - EDUCBA. https://www.educba.com/kivy-vs-tkinter/.
(8) How to add emojis to your GitHub README and other markdown files. https://towardsdev.com/how-to-add-emojis-to-your-github-readme-and-other-markdown-files-c8f13b3f9de4.
(9) markdown-templates/markdown-emojis: :fire: All the emojis :tada: - GitHub. https://github.com/markdown-templates/markdown-emojis.
(10) Learn the Key Differences Between Kivy and Tkinter - EDUCBA. https://www.educba.com/kivy-vs-tkinter/.
(11) Kivy · PyPI. https://pypi.org/project/Kivy/.
(12) How to Write a Good README File for Your GitHub Project - freeCodeCamp.org. https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/.
(13) Unicode / emojis in Github markdown - Stack Overflow. https://stackoverflow.com/questions/34538879/unicode-emojis-in-github-markdown.
(14) undefined. https://kivy.org/docs.
(15) undefined. https://groups.google.com/group/kivy-users.
(16) undefined. https://chat.kivy.org.
(17) undefined. https://groups.google.com/group/kivy-dev.
