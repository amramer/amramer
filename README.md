<div align="center">

# Amr Amer

**Machine Learning Engineer | Computer Vision | Deep Learning**

M.Sc. Visual Computing, Saarland University · Research engineering experience at DFKI

<a href="https://amramer.github.io/"><img src="https://img.shields.io/badge/Portfolio-0b6e69?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iMTAiLz48cGF0aCBkPSJNMiAxMmgyME0xMiAyYTE1LjMgMTUuMyAwIDAgMSA0IDEwIDE1LjMgMTUuMyAwIDAgMS00IDEwIDE1LjMgMTUuMyAwIDAgMS00LTEwIDE1LjMgMTUuMyAwIDAgMSA0LTEweiIvPjwvc3ZnPg%3D%3D" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/amr-amer-2023-cs/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwLjQ1IDIwLjQ1aC0zLjU2di01LjU3YzAtMS4zMy0uMDItMy4wNC0xLjg1LTMuMDQtMS44NSAwLTIuMTQgMS40NS0yLjE0IDIuOTR2NS42N0g5LjM1VjloMy40MXYxLjU2aC4wNWMuNDgtLjkgMS42NC0xLjg1IDMuMzctMS44NSAzLjYgMCA0LjI3IDIuMzcgNC4yNyA1LjQ2djYuMjh6TTUuMzQgNy40M2EyLjA2IDIuMDYgMCAxIDEgMC00LjEzIDIuMDYgMi4wNiAwIDAgMSAwIDQuMTN6TTcuMTIgMjAuNDVIMy41NlY5aDMuNTZ2MTEuNDV6TTIyLjIyIDBIMS43N0MuNzkgMCAwIC43NyAwIDEuNzN2MjAuNTRDMCAyMy4yMy43OSAyNCAxLjc3IDI0aDIwLjQ1Yy45OCAwIDEuNzgtLjc3IDEuNzgtMS43M1YxLjczQzI0IC43NyAyMy4yIDAgMjIuMjIgMHoiLz48L3N2Zz4%3D" alt="LinkedIn"></a>
<a href="mailto:amribrahim.amer@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://amramer.github.io/assets/Resume_Amr_Amer.pdf"><img src="https://img.shields.io/badge/CV-333333?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCI%2BPHBhdGggZD0iTTE0IDJINmEyIDIgMCAwIDAtMiAydjE2YTIgMiAwIDAgMCAyIDJoMTJhMiAyIDAgMCAwIDItMlY4eiIvPjxwYXRoIGQ9Ik0xNCAydjZoNk0xNiAxM0g4TTE2IDE3SDhNMTAgOUg4Ii8%2BPC9zdmc%2B" alt="CV"></a>

</div>

## About me

I build intelligent visual systems that see, understand and generate, from multimodal 3D avatar generation and real-time sports analytics to medical imaging and autonomous driving perception.

My work lives at the intersection of computer vision, deep learning and generative modeling, with a focus on pushing research-grade systems toward scalable, real-world solutions. On the data and MLOps side, I build reproducible pipelines with DVC, Airflow, Spark and MLflow, add automated data-quality gates, and ship models with Docker, Kubernetes and CI/CD on GitHub Actions.

Currently seeking roles in Machine Learning Engineering and Computer Vision.

## Featured projects

### [Master's thesis: Personality-Aware Non-verbal Behavior Generation](https://github.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation)

A **multimodal generative model** for synthesizing realistic listener avatars in dyadic conversations, conditioned on personality traits. The model predicts facial expressions, head motion and upper-body gestures of a listener from the speaker's audio and motion signals.

<p align="center">
  <img src="assets/thesis-avatars.gif" width="100%" alt="Generated listener avatars with extrovert, neutral and introvert personalities">
</p>

**Results:** face FID 6.15 and P-FID 10.31, upper-body FID 43.16 and P-FID 87.73, better than a personality-agnostic baseline. In a user study, participants identified the extroverted avatar in 86% of cases.

**Tech stack:** `PyTorch` · `Transformers` · `VQ-VAE` · `SMPL-X (PIXIE)` · `Librosa` · `OpenCV` · `CUDA` · `TensorBoard` · `SLURM` · `Enroot` · `Multi-GPU training (A100)`

[Thesis website](https://amramer.github.io/Personality-Aware-Non-verbal-Behavior-Generation/) | [Repository](https://github.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation) | [Full thesis (PDF)](https://github.com/amramer/Personality-Aware-Non-verbal-Behavior-Generation/blob/main/docs/Thesis_final_doc.pdf)

---

### [Badminton-VisionAI](https://github.com/amramer/Badminton-visionAI)

An **end-to-end computer vision pipeline** for badminton match analysis that converts raw match footage into structured performance analytics for players and coaches. The system tracks players and the shuttlecock, detects shot events, projects motion onto a mini-court representation and generates a downloadable coach-style performance report.

<p align="center">
  <img src="assets/badminton-tracking.gif" width="100%" alt="Badminton tracking: players, shuttle, shot detection and mini-court mapping">
</p>

**Tech stack:** `Python` · `PyTorch` · `OpenCV` · `YOLO` · `ByteTrack` · `TrackNet` · `SAM` · `Streamlit` · `Plotly` · `Docker` · `CUDA` · `Homography` · `Body pose estimation` · `3D motion trajectories` · `CI/CD pipeline`

[CV pipeline video](https://www.youtube.com/watch?v=dAe9e_1AGuA) | [Dashboard video](https://www.youtube.com/watch?v=Bc2JLifgjzI) | [Repository](https://github.com/amramer/Badminton-visionAI) | [Live demo](https://badminton-visionai-web.onrender.com/) <sub>(free server, can take about a minute to wake up)</sub>

---

### [AV Sensor DataOps](https://github.com/amramer/av-sensor-dataops)

An **automated pipeline** that turns raw autonomous-vehicle sensor logs (nuScenes camera and LiDAR) into **versioned, quality-checked, ML-ready datasets**, then trains a camera detector, **fuses it with LiDAR for 3D object detection**, evaluates it nuScenes-style and serves it as a **monitored API**.

```mermaid
flowchart LR
  A[Raw sensor logs] --> B[Bronze] --> C[Silver] --> D{Quality gate} --> E[Gold] --> F[Train] --> G[Evaluate] --> H{Promotion gate} --> I[ONNX + FastAPI]
```

- **Versioning and lineage:** every stage is a DVC stage; datasets and models are reproducible from a Git tag, and MLflow runs carry the commit and dataset hash
- **Data quality:** Pandera schemas plus sensor and label checks (sync offsets, dropped frames, corrupt files, degraded LiDAR, suspect calibration) that fail the pipeline on errors
- **Orchestration and CI/CD:** Airflow triggers training when a new dataset version lands; GitHub Actions runs tests, the full pipeline on synthetic data and a reproducibility check on every push
- **Serving and monitoring:** ONNX Runtime and FastAPI with Prometheus metrics and Grafana dashboards

**Tech stack:** `DVC` · `Airflow` · `PySpark` · `Pandera` · `MLflow` · `YOLOv8` · `ONNX Runtime` · `FastAPI` · `Prometheus` · `Grafana` · `Docker` · `Kubernetes` · `GitHub Actions`

## More projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/amramer/Semantic-Segmentation-Model-for-Autonomous-Vehicles-An-End-to-End-ML-Workflow"><img src="assets/driving-segmentation.webp" width="100%" alt="Semantic segmentation of a street scene"></a>
<br><b><a href="https://github.com/amramer/Semantic-Segmentation-Model-for-Autonomous-Vehicles-An-End-to-End-ML-Workflow">Semantic Segmentation for Autonomous Vehicles</a></b>
<br>Multi-class segmentation of urban street scenes on BDD100K, with systematic hyperparameter sweeps. mIoU ≈ 0.45 (road ≈ 0.88, vehicle ≈ 0.78).
<br><sub>PyTorch · fastai · Weights &amp; Biases</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/amramer/brain-tumor-segmentation-3D-DeepLearning"><img src="assets/brain-tumor-segmentation.webp" width="100%" alt="Brain tumor segmentation on MRI"></a>
<br><b><a href="https://github.com/amramer/brain-tumor-segmentation-3D-DeepLearning">3D Brain Tumor Segmentation (MRI)</a></b>
<br>Multi-label segmentation of glioma sub-regions from 3D multimodal MRI with a 3D SegResNet. Mean Dice 0.78 (WT 0.90, TC 0.82, ET 0.59).
<br><sub>PyTorch · MONAI · sliding-window inference · Weights &amp; Biases</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/amramer/realtime-vision-captioning"><img src="assets/realtime-captioning.webp" width="100%" alt="Realtime vision captioning app"></a>
<br><b><a href="https://github.com/amramer/realtime-vision-captioning">Realtime Vision Captioning</a></b>
<br>Jupyter notebooks that progress from offline image understanding to a real-time webcam app for live image captioning (BLIP) and classification (ResNet-50).
<br><sub>PyTorch · Hugging Face Transformers · Gradio</sub>
</td>
<td width="50%" valign="top">
<img src="assets/conversational-agent.webp" width="100%" alt="AI conversational agent web interface">
<br><b>AI Conversational Agent</b> <sub>(in progress)</sub>
<br>Real-time voice and text interaction, LLM-powered reasoning and a digital-human interface in a custom web app.
<br><sub>Python · OpenAI GPT · speech-to-text · text-to-speech · JavaScript</sub>
</td>
</tr>
</table>

## Technical skills

| Area | Skills and tools |
|---|---|
| **Computer vision** | Object detection · segmentation · tracking · 3D object detection · camera + LiDAR fusion · video motion analysis · digital human models |
| **Generative AI** | VQ-VAE · diffusion models · VLMs · multimodal generation |
| **Models and frameworks** | PyTorch · TensorFlow · OpenCV · YOLO · SAM · Vision Transformers (ViT) · TrackNet · Supervision |
| **Data pipelines and MLOps** | DVC · Airflow · PySpark · Pandera data-quality checks · MLflow · Weights & Biases · TensorBoard |
| **Deployment** | Docker · Kubernetes · FastAPI · ONNX Runtime · AWS (EC2 GPU) · Streamlit · batch and real-time inference |
| **CI/CD and monitoring** | GitHub Actions · automated testing · Prometheus · Grafana |
| **Compute** | SLURM (HPC) · multi-GPU and multi-node training (CUDA) |
| **Software engineering** | Python · C++ · object-oriented design · Git · unit testing |

For the full overview of my work, visit **[amramer.github.io](https://amramer.github.io/)**.

<div align="center"><sub><em>Building systems that see and understand the world, one model at a time.</em></sub></div>
