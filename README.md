# 🔬 Check Gene Expression on UMAP in scRNA-seq Datasets

This script allows you to visualize gene expression (e.g., marker genes) on UMAP embeddings from single-cell RNA-seq datasets, specifically using:

- Sanofi CD45+ dataset  
- **Khavari et al.**, 2020  
- **Lyko et al.**, 2023  
- **Zou et al.**, 2024  

---

## 🚀 Quick Start

### 1. Activate Conda Environment
Ensure you're in the correct environment:
```bash
conda activate R_python2

### 2. Run the Script
python umap_plot_Sanofi_Khavari_Lyko_Zou_Mar25.py \
    --colors CD68,CD163 \
    --save_path ./macrophage_markers

⚙️ Arguments
	•--colors: Comma-separated list of genes to plot (e.g., marker genes)
	•--save_path: Directory where the output plots will be saved

🧪 Example Use Case

python umap_plot_Sanofi_Khavari_Lyko_Zou_Mar25.py \
    --colors CD68,CD163 \
    --save_path ./macrophage_markers


📝 Notes
	•	Designed for exploratory marker analysis in scRNA datasets.
	•	Tested with conda env R_python2.
