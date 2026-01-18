                                                                           
  ▄▄▄▄▄                ▄▄▄                             ▄▄▄                 
 ██▀▀▀▀█▄             ▀██▀                            ██▀▀█▄       █▄      
 ▀██▄  ▄▀       ▄      ██      ▀▀ ▄        ▄▄         ██ ▄█▀      ▄██▄     
   ▀██▄▄  ██ ██ ████▄  ██      ██ ████▄ ▄████ ▄███▄   ██▀▀█▄ ▄█▀█▄ ██ ▄▀▀█▄
 ▄   ▀██▄ ██▄██ ██ ██  ██      ██ ██ ██ ██ ██ ██ ██ ▄ ██  ▄█ ██▄█▀ ██ ▄█▀██
 ▀██████▀▄▄▀██▀▄██ ▀█ ████████▄██▄██ ▀█▄▀████▄▀███▀ ▀██████▀▄▀█▄▄▄▄██▄▀█▄██
            ██                             ██                              
          ▀▀▀                            ▀▀▀                               

**SynLingo Beta** is a prototype web-based application designed to perform **real-time Indian Sign Language (ISL) hand gesture recognition** using a live webcam feed.  
The project aims to explore how artificial intelligence and computer vision can be used to improve accessibility and communication for the hearing- and speech-impaired community.

This project was developed as part of a **Class 11 Artificial Intelligence (AI) project**.

---

## 📌 Project Overview

SynLingo captures live video from a user’s webcam, extracts individual frames, and sends them to a **computer vision model** for inference. The model predicts the corresponding ISL alphabet and displays the result in real time on a web application.

---

## 🎯 Objectives

- To recognize ISL hand gestures in real time
- To demonstrate the integration of AI models with web technologies
- To build an accessible and easy-to-use prototype for sign language recognition
- To understand the practical application of computer vision in assistive technology

---

## 🛠️ Technologies Used

- **HTML, CSS, JavaScript** – Frontend and UI
- **Web Camera API (MediaDevices)** – Access live webcam feed
- **HTML Canvas** – Capture video frames
- **Roboflow Universe** – Dataset sourcing
- **Roboflow Hosted Inference API** – Pretrained model deployment

---

## ⚙️ How It Works

1. The browser accesses the user’s webcam using the MediaDevices API.
2. Live video frames are captured using an HTML canvas.
3. Each frame is converted into a base64-encoded image.
4. The image is sent to the Roboflow Hosted Inference API.
5. The AI model predicts the ISL hand sign.
6. The predicted class and confidence score are displayed on the webpage.

---

## 📂 Project Structure


SynLingo/
├── index.html   # One-page web application
└── README.md    # Project documentation

---

## 👥 Project Team

This project was developed by:

- **Vishwajith**
- **Drishti**
- **Saumya**
- **Manya**

**Class:** 11  
**Subject:** Artificial Intelligence  

Each team member contributed to research, development, testing, and documentation of the project.

---

## ⚠️ Limitations

- Requires an internet connection for API-based inference
- API key is exposed in the frontend (acceptable for demos, not production)
- Accuracy depends on lighting conditions and hand positioning
- Limited to the gestures included in the training dataset

---

## 📜 License

This project is licensed under the **MIT License**.

### MIT License

MIT License

Copyright (c) 2026 SynLingo Project Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## 📌 Acknowledgements

- Roboflow for dataset hosting and model deployment
- Open-source web technologies that made rapid prototyping possible
- Teachers and mentors for guidance and support

---

**SynLingo (Prototype)** – Bridging communication through AI 🤝
