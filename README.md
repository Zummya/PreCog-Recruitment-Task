# MetaFam Knowledge Graph Analysis
quick update: we made it in :)
## Project Overview
This repository contains a comprehensive analysis of the MetaFam Knowledge Graph dataset - a synthetic family relationship dataset. The project demonstrates various graph analysis techniques including Graph Theory, Community Detection, Logic Rule Mining, and Link Prediction using Knowledge Graph Embeddings and Graph Neural Networks.

## Key Highlights
- **Complete Attempt**: All 4 main tasks attempted (+ 4 bonus tasks attempted)
- **Comprehensive Reports**: Detailed PDF reports for each task with insights and visualizations
- **Real-world Applications**: Family relationship inference, community detection, and logical rule discovery

## Project Structure
```
PreCog_Task/
├── README.md                           # This file
├── requirements.txt                     # Python dependencies
│
├── The Problem/                        # Dataset
│   ├── train.txt                       # Training triples
│   └── test.txt                        # Test triples
│
├── Task 1/                             # Dataset Exploration & Graph Analysis
│   ├── task1_ExploreDataset.ipynb     # EDA and graph metrics
│   └── Plots/                          # Generated visualizations
│
├── Task 2/                             # Community Detection
│   └── task2_CommunityDetection_GeneMetrics.ipynb
│                                       # Louvain, Label Propagation, genealogical analysis
│
├── Task 3/                             # Rule Mining
│   └── task3_RuleMining.ipynb         # Inverse, compositional, and symmetric rules
│
├── Task 4/                             # Link Prediction Models
│   ├── rgcn-withoutdgl-final.ipynb    # Relational GCN implementation
│   ├── task4-transe-rotate-final.ipynb # TransE & RotatE models
│   ├── task4-compgcnwithtransedecoder.ipynb  # CompGCN + TransE
│   └── task4-compgcnwithrotatedecoder.ipynb  # CompGCN + RotatE
│
├── Models/                             # Saved trained models
│   ├── rgcn_model.pt
│   ├── transe_model.pt
│   ├── rotate_model.pt
│   ├── compgcn_model.pt
│   └── compgcn_rotate_model.pt
│
├── BonusTasks(DeadlineExtended)/      # Additional analyses
│   ├── bonustask-mothers-deserve-better.ipynb    # Gender bias analysis
│   ├── bonustask-rules-go-brrrr.ipynb           # Rule-based link prediction
│   ├── bonustask-who-needs-13k-edges.ipynb      # KG compression
│   └── bonustask-your-family-is-not-safe.ipynb  # Privacy in Family KGs
│
└── Task_Reports/                       # Detailed PDF reports
    ├── PrecogTask1Report.pdf
    ├── PrecogTask2Report.pdf
    ├── PrecogTask3Report.pdf
    └── PrecogTask4Report.pdf
```

## 🔧 Setup Instructions

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- (Optional) CUDA-capable GPU for faster training of neural models

### Installation

1. **Clone the repository** (or navigate to the project directory)
```bash
cd "C:\IIITH\PreCog_Task"
```

2. **Create a virtual environment** (recommended)
```bash
python -m venv venv
```

3. **Activate the virtual environment**
```bash
# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

4. **Install dependencies**
```bash
pip install -r requirements.txt
```

### Running the Notebooks

1. **Start Jupyter Notebook**
```bash
jupyter notebook
```

2. **Navigate to any task folder** and open the desired `.ipynb` file

3. **Run the cells sequentially** - each notebook is self-contained with data loading

**Note**: The notebooks include conditional loading for both Kaggle and local environments, so they should work out-of-the-box.


---

**The reports are well-organized and provide the necessary context to understand the analysis, compensating for any disorder in the notebooks.**

Created as part of the PreCog Lab assignment at IIIT Hyderabad.

## Acknowledgments
- PreCog Lab, IIIT Hyderabad for the task design
- Research papers on TransE, RotatE, R-GCN, and CompGCN
- PyTorch and NetworkX communities

---

**Note**: While the Jupyter Notebooks may appear somewhat unorganized due to time constraints, the analysis is thorough and the comprehensive reports provide clear, structured findings. The focus has been on depth of analysis and meaningful insights rather than code aesthetics.

This has been my attempt at the 26'graphs-precog-task.

