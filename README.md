# DDoS Attack Detection in Software Defined Networks using Deep Learning Models

### Software And Tools Requirement

1. [Python Environment](https://colab.research.google.com/)
2. [Github Account](https://github.com)
3. [Heroku/Render Account](https://heroku.com)
4. [VS Code IDE](https://code.visualstudio.com)
5. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment 

```
using virtualenv-

python -m pip install virtualenv  ## Ensure virtualenv is installed
virtualenv --python=python3.12 venv

Activate the virtual environment-

Windows (Command Prompt)
venv\Scripts\activate

selecting kernel-
url= http://localhost:8888/?token=your-token-here
password= ?token=your-token-here
```

## 📄 Project Overview  
This project aims to detect Distributed Denial-of-Service (DDoS) attacks in Software-Defined Networks (SDNs) using Machine Learning (ML) and Deep Learning (DL) technologies. DDoS attacks pose a significant threat to network security, and traditional detection methods often fall short in dynamic SDN environments. This project explores the potential of advanced ML/DL models for accurate and timely DDoS detection.

---

## 📊 Datasets
The project utilizes a dataset containing network traffic features extracted from variuos SDN environments. The datasetx includes labeled instances of normal traffics and DDoS attack traffics.

## 🌟 Click below to find the Datasets:
- [LR-HR DDos](https://www.kaggle.com/datasets/abdussalamahmed/lr-hr-ddos-2024-dataset-for-sdn-based-networks)
- [SNT (Simulated Network Traffic Using Mininet and Ryu)](https://data.mendeley.com/datasets/9hz6f62gtk/1)
- [Tree-SDN-DDoS Defense Dataset](https://data.mendeley.com/datasets/m4bp9wjnf9/1)
- [Torus-SDN-DDoS Defense Dataset](https://data.mendeley.com/datasets/h9sdd6wjb9/1)
---

## ⚙️ Methodology  

1. **🔧 Data Preprocessing:**  
   The dataset is cleaned, normalized, and prepared for model training.  

2. **🎯 Feature Engineering:**  
   Relevant features are selected or engineered to improve model performance.  

3. **🧠 Model Development:**  
   Several ML/DL models are implemented and trained, including:  
   - **📈 LSTM (Long Short-Term Memory)**  
   - **🔄 Bi-LSTM (Bidirectional LSTM)**  
   - **🌐 CNN (Convolutional Neural Network)**  
   - **🤖 RNN (Recurrent Neural Network)**  
   - **⚖️ MLP (Multi-Layer Peceptron)**  
   - **🔁 TabNet**  


4. **📊 Model Evaluation:**  
   Models are evaluated using metrics such as:  
   - Accuracy ✅  
   - Precision 🎯  
   - Recall 🔁  
   - F1-Score 🏆  
   - AUC (Area Under the ROC Curve) 📈  

5. **⚖️ Comparison:**  
   The performance of different models is compared to identify the most effective approach.  

---

## 🌟 Results  
The project demonstrates the effectiveness of DL models in detecting DDoS attacks in SDNs. The results show that the chosen models achieve high accuracy and provide a promising solution for enhancing network security.  

---

## 🚀 Usage  

1. **📂 Clone the repository:**  
   ```bash
   git clone https://github.com/Ip-12345/DDoS-Attacks-Detection-in-SDN-using-DeepLearning-Models
   ```  

2. **🗃️ Prepare the dataset:**  
   Ensure the dataset is in the correct format and location.  

---

## 🔮 Future Amendments  

* 🚀 Explore more advanced DL models.  
* 🔧 Optimize the model parameters for better performance.  
* 📡 Implement real-time DDoS detection in an SDN environment.  

---

## 🤝 Contributions 

Contributions are welcome! 🛠️ If you find any bugs 🐛 or have suggestions 💡 for improvement, please feel free to submit an issue or a pull request.  

---

## 📜 License  

This project is licensed under the **Apache License** 📝.  

Feel free to add your own ideas to this repo! 😊