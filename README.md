# 🫁 Lung Segmentation from Chest CT Scans using Deep Learning

This project performs automatic **lung region segmentation** from chest CT scans using 2D slices and a lightweight **U-Net** architecture. 
---

### Notebook contains a complete end-to-end pipeline:

- Preprocessing of 3D CT volumes into 2D slices
- Train U-NET using PyTorch Lightning
- Evaluate with Dice, IoU, Precision, Recall, F1
- Export predictions in `.png` and `.nii.gz`
---

**Dataset can be downloaded from:**  
[Public CT Dataset – MICLab-Unicamp](https://github.com/MICLab-Unicamp/Public-data/releases/download/v1.0/raw.zip)  

## 📁 Project Structure

| File/Folder              | Description                          |
|--------------------------|--------------------------------------|
| `lung_segmentation.ipynb`| full pipeline notebook               |
| `exported_masks/`        | sample lung masks                    |
| `lightning_logs/`        | FP/FN overlays                       |
| `plots/`                 | dice_iou/sample & score_distributions|
| `metrics/`               | lung_segmentation_metrics_results    |




## 📁 Project Structure

| File/Folder           | Description                                 |
|------------------------|---------------------------------------------|
| `data/`                | Raw, preprocessed, and predicted slices     |
| `notebooks/`           | Step-by-step Jupyter notebooks              |
| `scripts/`             | Modular training, evaluation scripts        |
| `outputs/`             | Plots, reports, overlays                    |
| `requirements.txt`     | Python dependencies                         |

---

## 🛠 Setup & requirements

```bash
git clone https://github.com/your-username/lung-segmentation-DL.git
cd lung-segmentation-DL
pip install -r requirements.txt
