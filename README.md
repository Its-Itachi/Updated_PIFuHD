# 🖥 PIFuHD – Patched Colab Version

> ⚠️ Note: This repository is a patched version of **PIFuHD by Facebook Research**.  
> The modifications (Colab compatibility fixes, updated dependencies, and PyTorch 2.6+ support) are © 2025 **Jayesh Dethe**.  
> Redistribution is allowed under the same **MIT License** with proper attribution.

---

## 🧩 About This Project

This repository contains a **fixed and fully runnable version** of the original **PIFuHD notebook**.  
Several issues were resolved to make it compatible with **PyTorch 2.6+** and modern Python environments.

---

## 🔧 Main Fixes

- Updated `recon.py` for safe checkpoint loading with PyTorch 2.6+  
- Fixed import and dependency issues  
- Corrected path handling and output directories  
- Resolved version conflicts  
- Ensured full pipeline execution: 2D Image → 3D Mesh → OBJ Output  

> ✅ Fully compatible with modern Python + PyTorch 2.6+

---

## 🚀 How to Use

1. **Clone this repository**  
2. **Open the notebook** in a Python environment that supports Jupyter notebooks  
3. **Run all cells sequentially:**  
   - Install dependencies  
   - Download pretrained checkpoints  
   - Run `recon.py` to create **3D meshes**  
4. **If output is not generated on the first run:**  
   - This is a common Python import/caching issue  
   - Simply **run the entire notebook a second time**  
   - This ensures all local modules are compiled and cached (`__pycache__/`)  

---

## 🛠 Tech Stack

| Layer         | Tools Used          |
|---------------|---------------------|
| Deep Learning | PyTorch             |
| Data Handling | NumPy, OpenCV, PIL  |
| Visualization | Matplotlib, OpenCV  |
| Notebook      | Jupyter / Colab     |

---

## 👥 Credits

- **Original Creator:** [PIFuHD – Facebook Research](https://github.com/facebookresearch/pifuhd)  
- **Patched & Updated By:** Jayesh Dethe  

---

## ⭐ Support

If you find this project useful, please:  

- ⭐ Star the repository on GitHub  
- 📢 Share with peers  
- 🔔 Follow for more ML + 3D reconstruction projects  

---

## 📝 Notes

- This version addresses runtime errors, checkpoint loading issues, and Python environment compatibility problems  
- Users can run the notebook directly without manual fixes  
- **Tip:** If the final cell does not produce output, re-run the notebook to fix Python import caching issues  
- For feedback or suggestions, please open an **Issue**

---

## ⚖️ License

This project is released under the **MIT License (© 2025 Jayesh Dethe)**. You are free to use and modify it with proper credit.

---

Happy 3D modeling! 🚀
