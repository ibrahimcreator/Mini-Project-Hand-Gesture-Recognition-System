# ✋ Real-Time AI-Enabled Hand Gesture Recognition for Deaf and Dumb Aid Communication

Welcome to the repository for a real-time, AI-powered hand gesture recognition system designed to bridge the communication gap for the **deaf and mute community**. This application leverages **Computer Vision** and **Machine Learning** to recognize hand gestures and interpret them in real time.

---

## 💡 Project Overview

This project was developed as a major academic initiative (Sep 2023 – Dec 2023), focusing on inclusive technology and real-world impact. Built using **Python**, **MediaPipe**, and **OpenCV**, the system accurately detects and classifies hand gestures, displaying corresponding text-based communication in a user-friendly GUI.

---

## 🚀 Features

* 🧠 **AI-Powered Prediction**: Integrated a custom-trained **RandomForestClassifier** model to recognize hand gestures using extracted landmarks.
* ✋ **Precise Hand Detection**: Leveraged **MediaPipe Hands API** for accurate real-time landmark tracking and gesture extraction.
* 🖥️ **Real-Time Recognition**: Seamless recognition pipeline using **OpenCV**, optimized for performance on standard hardware.
* 🪟 **Accessible GUI**: Built with **Tkinter**, offering an intuitive, easy-to-use interface suitable for diverse users.
* 🗂️ **Modular Codebase**: Includes clearly separated modules for data collection, training, processing, and inference.

---

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Libraries**: OpenCV, MediaPipe, Tkinter, NumPy, Scikit-learn
* **Model**: RandomForestClassifier (sklearn)
* **Development Tools**: VS Code, GitHub, Jupyter Notebook

---

## 📁 Project Structure

```
├── Application.py             # Main application interface
├── Data_Collection.py        # Module for collecting landmark data
├── Data_Preprocessing.py     # Preprocessing raw data for ML
├── Data_Training.py          # Training the classifier model
├── Sample_Model.ipynb        # Jupyter notebook version of training
├── data.pickle               # Trained model data
├── Requirements.txt          # Required dependencies
├── data/                     # Landmark data folder
```

---

## 🤖 How It Works

1. Capture hand landmarks in real-time using MediaPipe.
2. Extract features and classify them using a trained Random Forest model.
3. Display the predicted gesture as readable text in a GUI.

---

## 🎓 What I Gained

* Practical understanding of real-time computer vision systems.
* Experience in building end-to-end machine learning applications.
* Improved skills in Python, GUI design, and model training.
* Developed empathy-driven tech for assistive communication.

---

## 📫 About Me

Hi 👋, I'm **SYED IBRAHIM A** – a recent **B.Tech CSE graduate** with a specialization in **AI (IBM Certified)**. I'm passionate about using technology for good, especially in fields like accessibility, healthcare, and education.

* 💼 Open to: Python Developer, AI/ML Developer, Software Engineer, QA Engineer
* 🌐 Portfolio: https://www.linkedin.com/in/ibrahimcreator/
* 📍 Location: India (Open to Remote / Hybrid / On-site opportunities)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

If this project inspires you or aligns with your goals, feel free to star ⭐ it and connect with me!
