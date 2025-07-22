# Neural Network – Bidirectional LSTM Multi-Output System for CNC Maintenance

## Overview

This repository documents the design of an advanced AI-based predictive maintenance system for CNC nesting machines. Developed for SCM Group S.p.A., the system uses a **Bidirectional LSTM Recurrent Neural Network** with custom attention and adapter layers to monitor the wear of the sacrificial work surface (piano martire) based on customer usage habits.

The system issues early warnings to operators via Maestro Active (a production GUI), suggesting optimal times for maintenance operations such as planing or replacement.

> ⚠️ **Note**: The source code is not available due to ownership and confidentiality constraints. This repository serves as a detailed technical showcase of the solution's architecture, workflow, and purpose.

---

## Project Goals

- Predict wear level of the sacrificial surface in CNC machines.
- Issue proactive alerts for maintenance actions.
- Enhance predictive accuracy using customer behavior data.
- Ensure seamless integration with SCM’s Maestro Active GUI.

---

## Technologies Used

- **Programming Language:** Python
- **Frameworks & Libraries:** TensorFlow, Keras, NumPy, Pandas, PyTorch, Sckit-learn, Flask API, ReSTful
- **AI Components:** Bidirectional LSTM, Attention Mechanism, Adapter Layers, Transfer Learning, Fine-tuning
- **Deployment:** Flask REST API (6 endpoints: 1 GET, 5 POST)
- **Packaging:** Virtual environment Venv + integrated executable for Maestro Active plugin

---

## Architecture Summary

- **Input Layer:** Operational logs and usage history.
- **Model:** Bidirectional LSTM + Attention + Adapter Layers.
- **Outputs:** Regression (wear value) + Classification (maintenance status).
- **Server:** Flask-based RESTful API with pre-trained weights.
- **Interface:** Notification pop-ups in Maestro Active.

---

## Key Features

- ⚙️ Self-generated simulation dataset for model training.
- 🎯 Dual output: regression and classification.
- 🔁 Fine-tuning system for real-world deployment.
- 📡 REST API with secure data handling.
- 🔌 Seamless plug-in deployment in CNC production tools.

---

## Folder Structure

```
/docs/                      → project documentation
LICENSE.md                  → project license
README.md                   → project overview
```

---

## Contact

Project by **Filippo Matteini**  
📍 San Marino | ✉️ fili85g@gmail.com | 🌐 [LinkedIn](https://www.linkedin.com/in/filippo-matteini-29554a355) | 💻 [GitHub](https://github.com/Fil952701)

---

## Disclaimer

This repository is for presentation purposes only. All rights and proprietary code belong to **SCM Group S.p.A.** and are not publicly distributed.
