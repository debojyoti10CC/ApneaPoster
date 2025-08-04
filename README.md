# Sleep Apnea Detection using 1D CNN-BiLSTM with Attention

> An AI-driven pipeline that detects sleep apnea from single-lead ECG signals using 1D CNN and BiLSTM layers enhanced with an attention mechanism.

## 🧠 Abstract

Sleep apnea is a disorder that leads to disrupted breathing during sleep. This project introduces a deep learning architecture combining 1D CNN + BiLSTM with an attention layer to detect apnea events from ECG signals.

---

## 👨‍💻 Team Members
- Sampurnaa Nag (12024052016005)
- Sylvia Barick (12024052016009)
- Debojyoti De Majumder (12024052020010)

---

## 📈 Architecture

- **CNN Layers**: Extract spatial features from raw ECG.
- **BiLSTM**: Capture temporal dependencies from past & future.
- **Attention Mechanism**: Focus on apnea-relevant time steps.
- **Fully Connected + Sigmoid**: Classify apnea or normal.

---

## 📊 Performance

- **Training Accuracy**: 95.79%
- **Validation Accuracy**: 93.62%
- **Test Accuracy**: 97.18%

---

## 📁 Dataset

- **Source**: [PhysioNet Apnea-ECG Database](https://physionet.org/content/apnea-ecg/1.0.0/)
- **Preprocessing**:
  - Chebyshev bandpass filter (0.5–48 Hz)
  - 1-minute segmenting
  - Autocorrelation-based noise removal

---

## 🚀 Future Scope

- Incorporate SpO₂ and respiratory signals
- Use Transformer/Ensemble architectures
- Improve explainability for clinical use

---

## 📄 References

See [`references.md`](./references.md)

---

## 🛠️ Setup

```bash
git clone https://github.com/<your-username>/Sleep-Apnea-Detection-CNN-BiLSTM.git
cd Sleep-Apnea-Detection-CNN-BiLSTM
pip install -r requirements.txt
