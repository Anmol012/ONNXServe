# ⚡ ONNXServe

**Tagline:** Deploy, Load, Predict — Anywhere.  

ONNXServe is a lightweight model serving framework for ONNX models, providing flexible upload, dynamic loading, and easy prediction APIs.

---

## 🔹 Features

- **Model Upload & Registry**
  - Upload ONNX models via API or UI.
  - Metadata stored in MySQL.
  - Model binaries stored in MinIO.

- **Model Loading**
  - Load models dynamically into ONNX Runtime.
  - Support for multiple models in memory.
  - Unload models to free up resources.

- **Prediction API**
  - REST endpoints for inference.
  - Send input → receive predictions.

---

## 🚀 Quick Start

```bash
# Clone repo
git clone https://github.com/Anmol012/onnxserve.git
cd onnxserve

