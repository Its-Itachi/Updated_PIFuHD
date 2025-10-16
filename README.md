# 🖥 PIFuHD – Patched Colab Version

### ⚡ Quick Start
Open in Colab and **run all cells sequentially** to go from **2D image → 3D mesh → OBJ output**:  
[Run in Colab](https://colab.research.google.com/drive/1aTgf-WrwwGyXeC9Yk8oddEHshv5x5Zt9?usp=sharing)

---

👉 **Original PIFuHD GitHub**: [https://github.com/facebookresearch/pifuhd](https://github.com/facebookresearch/pifuhd)

This repository contains a **fixed and fully runnable version** of the original PIFuHD Google Colab notebook. Several issues were resolved to make it compatible with **PyTorch 2.6+** and the latest Colab environment.

---

## 🔧 Main Fixes

- Updated `recon.py` for safe checkpoint loading with PyTorch 2.6+  
- Fixed import and dependency issues in Colab  
- Corrected path handling and output directories  
- Resolved version conflicts  
- Ensured full pipeline execution: 2D Image → 3D mesh → OBJ output  

> ✅ Compatible with latest Colab + PyTorch 2.6+  

---

## 🚀 How to Use

1. **Open the notebook:** [Run in Colab](https://colab.research.google.com/drive/1aTgf-WrwwGyXeC9Yk8oddEHshv5x5Zt9?usp=sharing)  
2. **Run all cells sequentially:**  
    - Install dependencies  
    - Download pretrained checkpoints  
    - Run `recon.py` to create **3D meshes**  
3. **If output is not generated on the first run:**  
    - This is a common Python import/caching issue in Colab  
    - Simply **run the entire notebook a second time**  
    - This ensures all local modules are compiled and cached (`__pycache__/`), so imports work properly  

---

## 🛠 Tech Stack

| Layer         | Tools Used                |
|---------------|---------------------------|
| Deep Learning | PyTorch                   |
| Data Handling | NumPy, OpenCV, PIL       |
| Visualization | Matplotlib, OpenCV       |
| Notebook      | Google Colab             |

---

## 👥 Credits

- **Original Creator**: [PIFuHD – Facebook Research](https://github.com/facebookresearch/pifuhd)  
- **Patched & Updated By**: Jayesh Dethe  

---

## ⭐ Support

If you find this project useful, please:  

- ⭐ Star the repository on GitHub  
- 📢 Share with peers  
- 🔔 Follow for more ML + 3D reconstruction projects  

---

## 📝 Notes

- This version addresses runtime errors, checkpoint loading issues, and Colab compatibility problems  
- Users can run the notebook directly without manual fixes  
- **Tip for Colab:** If your final cell does not produce output, run the entire notebook a second time to resolve Python import caching issues  
- For feedback or suggestions, please open an **Issue**  

---

Happy 3D modeling! 🚀
