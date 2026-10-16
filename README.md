<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=150&section=header&text=Noman%20Khan&fontSize=48&fontColor=ffffff&fontAlignY=42&desc=AI%20%C2%B7%20Machine%20Learning%20%C2%B7%20Computer%20Vision%20%C2%B7%20Software&descSize=17&descAlignY=70" alt="Noman Khan" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=900&color=3A7CA5&center=true&vCenter=true&width=640&lines=M2+student+in+Biometrics+%26+Intelligent+Systems;Building+practical+AI+and+software+projects" alt="Typing animation" />

<br/>

📍 France &nbsp;·&nbsp; 🎓 M2 at UPEC, Paris-Est Créteil &nbsp;·&nbsp; 🗣️ English · French

[![Portfolio](https://img.shields.io/badge/Portfolio-2c5364?style=for-the-badge&labelColor=0f2027)](https://noman-khan.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-2c5364?style=for-the-badge&labelColor=0f2027)](https://www.linkedin.com/in/noman-khan-b90914289/)
[![Email](https://img.shields.io/badge/Email-2c5364?style=for-the-badge&labelColor=0f2027)](mailto:noman.khan.job@gmail.com)

</div>

<br/>

## About me

Hi, I'm Noman. I'm a Master's student in **Biometrics and Intelligent Systems** at Université Paris-Est Créteil in France, now in M2 after finishing my first year with honours. Computer vision, machine learning and applied AI are what I enjoy most.

I came to this through Information Technology: I spent two years building software for clients, then co-authored a CNN paper on solar-panel defect detection before moving to Paris for my Master's. I like seeing a project through from start to finish: training a model, checking properly whether it actually works, and then putting it behind an API or a web interface so people can try it.

![M1](https://img.shields.io/badge/M1%20result-15%2F20%20with%20honours-2c5364?style=flat-square&labelColor=0f2027)
![Experience](https://img.shields.io/badge/Software%20development-2%20years-2c5364?style=flat-square&labelColor=0f2027)
![Research](https://img.shields.io/badge/Published%20research-CNN%20paper-2c5364?style=flat-square&labelColor=0f2027)

## Tech stack

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-2c5364?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-2c5364?style=flat-square&logo=javascript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-2c5364?style=flat-square)

**Computer vision & biometrics**<br/>
![OpenCV](https://img.shields.io/badge/OpenCV-2c5364?style=flat-square&logo=opencv&logoColor=white)
![Face Detection](https://img.shields.io/badge/Face%20Detection-2c5364?style=flat-square)
![Face Recognition](https://img.shields.io/badge/Face%20Recognition-2c5364?style=flat-square)
![MTCNN](https://img.shields.io/badge/MTCNN-2c5364?style=flat-square)
![Image Processing](https://img.shields.io/badge/Image%20Processing-2c5364?style=flat-square)
![Biometric Evaluation](https://img.shields.io/badge/Biometric%20Evaluation-2c5364?style=flat-square)

**Machine learning & deep learning**<br/>
![PyTorch](https://img.shields.io/badge/PyTorch-2c5364?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2c5364?style=flat-square&logo=tensorflow&logoColor=white)
![CNNs](https://img.shields.io/badge/CNNs-2c5364?style=flat-square)
![FaceNet](https://img.shields.io/badge/FaceNet-2c5364?style=flat-square)
![Triplet Loss](https://img.shields.io/badge/Triplet%20Loss-2c5364?style=flat-square)
![ArcFace](https://img.shields.io/badge/ArcFace-2c5364?style=flat-square)
![CosFace](https://img.shields.io/badge/CosFace-2c5364?style=flat-square)
![LLM Integration](https://img.shields.io/badge/LLM%20Integration-2c5364?style=flat-square)

**Backend & web**<br/>
![Flask](https://img.shields.io/badge/Flask-2c5364?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-2c5364?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-2c5364?style=flat-square)
![React](https://img.shields.io/badge/React-2c5364?style=flat-square&logo=react&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-2c5364?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-2c5364?style=flat-square)

**Data & tools**<br/>
![NumPy](https://img.shields.io/badge/NumPy-2c5364?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2c5364?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-2c5364?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-2c5364?style=flat-square&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-2c5364?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-2c5364?style=flat-square&logo=github&logoColor=white)

## Featured projects

### 🔐 [Facial Biometrics System with LLM-Assisted Evaluation](https://github.com/Mr-Noman-Khan/Facial-Biometrics-llm)

A Flask research prototype for face verification (1:1) and identification (1:N), built for local experimentation and demonstration.

```mermaid
flowchart LR
  A["Face image"] --> B["MTCNN<br/>detect and align"]
  B --> C["FaceNet<br/>embedding"]
  C --> D["Cosine matching<br/>1:1 or 1:N"]
  D --> E["FAR, FRR, EER<br/>ROC, CMC"]
  E --> F["LLM<br/>explanation"]
  classDef n fill:#2c5364,stroke:#0f2027,color:#ffffff;
  class A,B,C,D,E,F n;
```

- Face quality checks for lighting, blur, resolution, face size and tilt
- Verification metrics: FAR, FRR, EER, ROC and DET curves. Identification metrics: Rank-1, Rank-k and CMC
- Robustness experiments under changes in illumination, blur, resolution and compression
- Web dashboard for enrollment, verification, identification, evaluation and audit logs
- Optional LLM explanations of metrics and decisions, with OpenAI or a local Qwen model
- Experiment tracking with MLflow

<!-- Add a screenshot of the dashboard here, using synthetic or non-sensitive images only -->

`Python` · `Flask` · `FaceNet` · `MTCNN` · `OpenCV` · `MLflow`

### 📄 [SolarAI: Solar-Panel Optimization & Defect Resolution using CNN](https://www.researchgate.net/publication/385549917_SolarAI_Solar-Panel_Optimization_Defect_Resolution_using_CNN)

A published research paper, co-authored during my final bachelor year, on using a convolutional neural network to detect defects in solar panels so they can be found and fixed early.

`CNN` · `Deep Learning` · `Image Classification` · `Python`

### More on my profile

[Personal Portfolio](https://github.com/Mr-Noman-Khan/noman-khan-portfolio) ([live](https://noman-khan.vercel.app/)) · [Nagging Chatbot](https://github.com/Mr-Noman-Khan/Nagging-Chatbot) · [React Labs](https://github.com/Mr-Noman-Khan/React_labs) · [React Budget App](https://github.com/Mr-Noman-Khan/React_budget_app)

## Currently exploring

Deep learning for computer vision, with a focus on face recognition losses and proper model evaluation, and on turning models into practical applications.

## Get in touch

📧 [noman.khan.job@gmail.com](mailto:noman.khan.job@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/noman-khan-b90914289/) &nbsp;·&nbsp; 🌐 [Portfolio](https://noman-khan.vercel.app/)
