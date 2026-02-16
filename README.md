
---

## 🧾 Dataset

Dataset file:  
📌 `100_Unique_QA_Dataset.csv`

It contains 2 columns:

| question | answer |
|---------|--------|
| What is the capital of France? | Paris |
| Who wrote To Kill a Mockingbird? | Harper-Lee |

---

## 🏗️ Model Architecture

### SimpleRNN
- Embedding: `vocab_size → 50`
- RNN Hidden Units: `64`
- Linear Output: `64 → vocab_size`

---

## ⚙️ Training Details

- Loss Function: `CrossEntropyLoss`
- Optimizer: `Adam`
- Learning Rate: `0.001`
- Epochs: `25`

---

## 🖥️ Installation

```bash
pip install -r requirements.txt
