# 🗣️ Accent-Agnostic Speech Transcription Model for Enhanced Accessibility

This project addresses the challenge of accent variability in speech recognition, particularly within e-learning environments, by developing a robust, accent-agnostic speech transcription system using deep learning techniques. Leveraging **MFCCs** for feature extraction and comparing **RNN**, **LSTM**, and **GRU** architectures, the **GRU-based model** demonstrated superior performance, making a meaningful step toward **inclusive and accessible education**.

---

## 🧠 Project Overview

- **🎯 Objective**: Build a speech recognition model that performs accurately across diverse English accents to improve transcription reliability in digital learning environments.
- **📦 Dataset**: [Mozilla Common Voice](https://commonvoice.mozilla.org/en/datasets) – multilingual dataset rich in diverse accents.

---

## 🛠️ Technologies Used

| Category            | Tools / Methods                           |
|---------------------|--------------------------------------------|
| Feature Extraction  | MFCCs (LibROSA)                            |
| Deep Learning       | RNN, LSTM, GRU (Keras/TensorFlow)          |
| Data Handling       | NumPy, Pandas                              |
| Visualization       | Matplotlib, Seaborn                        |
| Audio Conversion    | FFmpeg                                     |

---

## 🔄 Methodology

### 🔁 Data Preprocessing
- MP3 → WAV conversion using **FFmpeg**
- Resampling to 16kHz
- Feature extraction using **MFCCs**
- Data normalization for convergence

### 🧠 Model Development
- Built and compared **RNN**, **LSTM**, and **GRU** models
- Applied **Dropout** and `TimeDistributed` dense layers
- Used **Categorical Crossentropy** loss and **Adam** optimizer

### 📊 Evaluation Metrics
- Accuracy
- Training/Validation Loss
- Generalization across accents

---

## 📈 Performance Summary

| Model | Training Accuracy | Validation Accuracy | Training Loss | Validation Loss |
|-------|-------------------|---------------------|----------------|-----------------|
| RNN   | 75.2%             | 72.8%               | 0.88           | 0.93            |
| LSTM  | 81.4%             | 79.5%               | 0.65           | 0.70            |
| GRU   | **83.9%**         | **82.3%**           | **0.59**       | **0.62**        |

✅ **GRU** outperformed all other models in accuracy and generalization, proving most suitable for accent-agnostic transcription.

---

## 💡 Key Findings

- GRU provided the best trade-off between **accuracy** and **computational efficiency**
- LSTM showed strong results but was more resource-heavy
- RNN struggled with long-term dependencies and overfitting

---

## 🧩 Applications

- 🎓 **E-learning**: Enhanced subtitle generation and real-time voice recognition
- 🧏 **Accessibility**: Assistive tools for hearing-impaired users or non-native speakers
- 💼 **Voice-activated services**: For call centers, smart assistants, and multilingual platforms

---

## 👥 Team

**Team Name**: Titans Alliance  
- Ruchitha Paccha  
- Bojanapally Santhoshini  
- RamyaSri Muthineni

---

## 📚 References

- Mozilla Common Voice Dataset  
- Goodfellow, Bengio & Courville – *Deep Learning*  
- Graves et al. – *Connectionist Temporal Classification*  
- Rabiner – *Hidden Markov Models in Speech Recognition*  
- FFmpeg Documentation

---

## 📬 Contact

For questions or collaborations, feel free to reach out:

📧 **Email**: ruchitha1904@gmail.com  
🔗 **LinkedIn**: [Ruchitha Paccha](https://www.linkedin.com/in/ruchitha-chowdary-paccha) 

