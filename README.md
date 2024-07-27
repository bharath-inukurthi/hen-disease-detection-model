
# Flock Guard

Introducing Flock Guard, a cutting-edge poultry monitoring system that leverages deep learning and computer vision to revolutionize poultry health management. Utilizing YOLO v8, this advanced model predicts and monitors the health of poultry in real-time, providing immediate health alerts and integrating real-time climate monitoring to ensure optimal living conditions and enhance poultry welfare. This project aims to automate health monitoring, reduce manual oversight, and promote sustainable farming practices. A comprehensive research paper detailing the methodologies and findings is forthcoming.



![Logo](https://cdn.prod.website-files.com/6697f3e249f36fb47b4e2b86/66a242c3d44d46cb55895c4f_project%20logo.jpeg)


## Environment Variables

To run this project, you will need to add python/scripts to your environment variables in system PATH

Visit https://pytorch.org/get-started/locally and install the dependencies by selecting your local environment specifications and run in your terminal


## Run Locally

#### Clone the project

```bash
  git clone https://github.com/bharath-inukurthi/hen-disease-detection-model.git
```

#### Go to the project directory

```bash
  cd hen-disease-detection-model
```

#### Install dependencies


Visit https://pytorch.org/get-started/locally and install the dependencies by selecting your local environment specifications and run in your terminal

After installing from above link run the command given below
```bash
  pip install -r requirements.txt
```

#### initialize the model

```bash
  yolo task=detect mode=predict model=model.pt source=1.jpeg show=True
```
This may take few seconds of time based on your system speed

To access your device webcame as source of video set the source value as 0

## Demo

Insert gif or link to demo

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://everything-about-bharath.webflow.io/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bharath-kumar-inukurthi/)


