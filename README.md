# AI-DeepLearning-Projects
# AI & Deep Learning Projects  
Progetti realizzati per il corso di *Sistemas Inteligentes – Inteligencia Artificial*  
Universidad Nacional de Córdoba (UNC), 2025

Questo repository raccoglie una serie di notebook dedicati allo studio e alla sperimentazione di modelli di Machine Learning e Deep Learning.  
Gli esercizi sono stati sviluppati nell’ambito del corso dell’UNC e includono classificazione supervisionata, reti neurali per immagini e autoencoder.

L’obiettivo del lavoro è applicare diversi modelli neurali a dataset reali, comprenderne il comportamento, confrontarne il rendimento e costruire pipeline complete:  
preprocessing → training → valutazione → analisi dei risultati.

---

## 📂 Contenuto della repository

### **1️⃣ Heart Disease Classification – MLP (TensorFlow)**
Notebook: `HeartDisease_AI_Classification.ipynb`

Modello MLP per predire la presenza di malattia cardiaca utilizzando il dataset *Heart Disease UCI*.  
Include:
- preprocessamento e encoding delle variabili
- scaling numerico
- costruzione e addestramento di una rete MLP
- metriche di valutazione (accuracy, confusion matrix, ROC/AUC)

---

### **2️⃣ Image Classification – MLP, CNN e Autoencoder**
Notebook: `ImageClassification_MLP_CNN_Autoencoder.ipynb`

Studio comparativo di tre architetture su immagini del dataset *Sign Language MNIST*:
- **MLP** su pixel flattenati  
- **CNN** per estrarre feature spaziali  
- **Autoencoder** convoluzionale per compressione e ricostruzione delle immagini  

Include:
- preprocessing immagini  
- confronto delle performance tra MLP e CNN  
- visualizzazione di ricostruzioni da autoencoder  

---

## 🛠️ Tecnologie utilizzate

- **Python**
- **TensorFlow / Keras**
- **scikit-learn**
- **pandas / numpy**

---

## 🎯 Obiettivi formativi

Questi progetti sono stati sviluppati con l’obiettivo di:
- acquisire familiarità con i principali modelli di Deep Learning  
- imparare a costruire pipeline complete di ML e DL  
- confrontare architetture differenti su task reali  

---

## 👤 Autore
**Antonino Blancato**  
Studente di Ingeniería Informática – Universidad Nacional de Córdoba (Argentina) 
(Programma di scambio internazionale del Politecnico di Torino)

---

## 📌 Nota
Questo repository è finalizzato allo studio personale e alla documentazione dei progetti svolti durante il corso.  
I notebook sono stati realizzati in Google Colab e sono liberamente consultabili per scopi didattici.
