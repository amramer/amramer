<!--
**amramer/amramer** is a ✨ _special_ ✨ repository because its `README.md` appears on your GitHub profile.
-->

<h1 align="center">Amr Amer</h1>

<p align="center">
<strong>Machine Learning Engineer • Computer Vision • Multimodal Generative Models</strong>
</p>

<p align="center">
Building intelligent systems for visual understanding, behavior generation, and real-time AI.
</p>

<p align="center">
  <a href="https://amramer.github.io/">
    <img src="Amr-Amer-Business-Card.jpeg" alt="Amr Amer Business Card" width="500" />
  </a>
</p>

<p align="center">
  <a href="https://amramer.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
  </a>  
  <a href="mailto:amribrahim.amer@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/amr-amer-2023-cs/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</p>

---

## 🚀 Featured Projects

### 🎓 [Master’s Thesis: Personality-Aware Non-verbal Behavior Generation](https://github.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation)

**Multimodal generative model** for generating realistic listener avatars in dyadic conversations, conditioned on personality traits.
  The model predicts facial expressions, head motion, and upper-body gestures of a listener from the speaker’s audio and motion signals.
  
  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation/main/assets/Images/avatars.gif" width="100%" alt="personality-aware avatars">
  </p>
  
- **Tech Stack:** PyTorch · Vision-Transformers · VQ-VAE · SMPL-X (PIXIE)-Librosa · OpenCV · CUDA · TensorBoard
    SLURM · Enroot · Multi-GPU Training (A100)

- **Demo:** [Thesis Website](https://thesis-website-3sxt.onrender.com/)
- **Paper:** [Full Thesis Document](https://github.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation/blob/main/docs/Thesis_final_doc.pdf)

---

### 🏸 [Badminton-VisionAI](https://github.com/amramer/Badminton-visionAI)

**End-to-end computer vision pipeline** for badminton match analysis that converts badminton match videos into structured performance analytics for players and coaches.
  The system tracks both players and the shuttlecock, detects shot events, projects motion onto a mini-court representation, and generates a downloadable coach-style performance report.

  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/Badminton-visionAI/main/demos/badminton-visionAI_01.gif" width="100%" alt="badminton analysis">
  </p>

- **Tech Stack:** Python · PyTorch ·  OpenCV · YOLO · ByteTrack · Streamlit · SAM · Plotly · Docker · CUDA
    TrackNet · CI/CD Pipeline · Homography · Body Poses estimation · 3D Motion Trajectories
  
- **Demo:** [Live Demo](https://badminton-visionai-web.onrender.com/) | [CV. Pipeline Video](https://www.youtube.com/watch?v=dAe9e_1AGuA) | [Dashboard Video](https://www.youtube.com/watch?v=Bc2JLifgjzI)

---

### 🚗 [Semantic Segmentation for Autonomous Vehicles](https://github.com/amramer/Semantic-Segmentation-Model-for-Autonomous-Vehicles-An-End-to-End-ML-Workflow)

This project focuses on **semantic segmentation** using the BDD100K dataset, a large-scale, diverse dataset for autonomous driving. 
The main objective is to accurately segment and identify various objects in street scenes, which is important for improving the **AI perception** vision of **autonomous vehicles**.
  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/Semantic-Segmentation-for-Autonomous-Vehicles/main/media/final_segmentation.gif" width="100%" alt="autonmous driving">
  </p>

- **Tech Stack:** PyTorch · Fastai · Semantic Segmentation · Hyperparamter Tunning · Weights & Biases

---

### 🩺 [3D Brain Tumor Segmentation (MRI)](https://github.com/amramer/brain-tumor-segmentation-3D-DeepLearning)
An end-to-end workflow for **multi-label brain tumor segmentation** from 3D multimodal MRI scans. The project targets segmentation of **glioma subregions** (tumor core, whole tumor, enhancing tumor) using a **3D SegResNet model**.
  
  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/brain-tumor-segmentation-3D-DeepLearning/main/assets/visualize-dec-dataset.gif" width="100%" alt="Medical Imaging">
  </p>

  **Tech Stack:**  PyTorch · MONAI · 3D SegResNet · Multi-modal MRI
    3D Medical Image Transforms · Sliding Window Inference · Experiment Tracking (W&B)

---

### 🎥 [Realtime Vision Captioning](https://github.com/amramer/realtime-vision-captioning)

This repository contains a curated set of Jupyter notebooks demonstrating core computer vision and vision–language capabilities using **VLM foundation models**. The notebooks progress from offline **image understanding** tasks to a **realtime webcam application** that performs **image captioning** and **image classification** on live video streams.
  
  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/realtime-vision-captioning/main/assets/realtime-app.gif" width="100%" alt="Vision-Langauge Models Application">
  </p>

- **Tech Stack:** PyTorch · Torchvision · Hugging Face Transformers · Gradio · PIL · VLM · Realtime inference
---

### 🎙️ [AI Conversational Agent](https://github.com/amramer/AI-Conversational-Agent) (Ongoing)
  
  This AI Agent is more than just a chatbot. It is real-time voice/text interaction, LLM-powered reasoning, and a digital human conversational model.
  <p align="center">
      <img src="https://raw.githubusercontent.com/amramer/amramer.github.io/main/assets/AI-conversationa-assistant.png" width="100%" alt="Conversation AI Bot">
  </p>
  
- **Tech Stack:** Python · OpenAI GPT · Speech-to-Text · Text-to-Speech · HTML · CSS · JavaScript · Bootstrap · jQuery
---

## 🌐 Portfolio
For more details about my work and projects, visit my [portfolio website](https://amramer.github.io/).

---

## 🧠 Technical Focus
 | Area                     | Skills & Tools                                                                 |
 |--------------------------|---------------------------------------------------------------------------------|
 | **Computer Vision**      | Object Detection, Segmentation, Tracking, Video Motion Analysis, Digital Human Models |
 | **Models & Frameworks**  | PyTorch, TensorFlow, OpenCV, YOLO, Vision Transformers (ViT), Supervision         |
 | **Training & Evaluation**| Transfer Learning, Hyperparameter Optimization, Weights & Biases, TensorBoard    |
 | **Deployment**           | Docker, AWS (EC2 GPU), Streamlit, Batch & Real-time Inference                    |
 | **Software Engineering** | Python, C++, Object-Oriented Design, Git, Debugging, Unit Testing                |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=amramer&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
</p>
