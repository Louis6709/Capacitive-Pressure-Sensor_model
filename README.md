# Plantar Pressure Analysis and State Prediction System  
![Figure_1](https://github.com/user-attachments/assets/f6acbf18-3b32-465b-afba-6184792be3ee)

*(Replace with actual project screenshot or schematic)*

---

## 📖 Project Overview  
This repository provides a comprehensive solution for **plantar pressure data acquisition, processing, and state prediction**, designed for **10-sensor arrays**. Key features include:  
- **Real-time Data Acquisition**: Capture plantar pressure signals via sensor arrays.  
- **Data Preprocessing**: Filtering, normalization, and outlier removal.  
- **Stress Cloud Visualization**: Generate dynamic/static pressure distribution maps using interpolation algorithms (supports DXF export).  
- **State Prediction**: Implement gait classification or health state prediction using PyTorch models.  

**Tech Stack**: Python 3.9 + PyTorch + Scipy + Matplotlib  

---

## 🛠️ Environment Setup  
### Dependency Installation  
```bash
# Create a virtual environment (recommended)
conda create -n plantar python=3.9
conda activate plantar

# Install PyTorch (adjust based on CUDA version)
pip install torch==1.12.1+cu113 --extra-index-url https://download.pytorch.org/whl/cu113

# Install other dependencies
pip install numpy pandas scipy matplotlib scikit-learn pyserial ezdxf
