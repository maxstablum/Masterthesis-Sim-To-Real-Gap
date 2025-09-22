# Systematic Literature Review: Sim-to-Real Transfer Analysis

A comprehensive analysis of the systematic literature review on sim-to-real transfer methodologies in robotics and machine learning.

## 📚 Project Overview

This repository contains the complete data analysis of a systematic literature review (SLR) on the sim-to-real gap. The analysis examines publications on transfer methods between simulation and real-world applications in robotics and ML domains.

### 🎯 Analysis Objectives

1. **Temporal Analysis**: Distribution of publications across years
2. **Geographic Analysis**: Distribution of publications by continent
3. **Quality Assessment**: Analysis of SJR rankings
4. **Conceptual Mapping**: Most frequent concept pairs and triples
5. **Cross-tabular Analysis**: Relationships between approaches and use cases
6. **Network Visualization**: Sankey diagram of challenge-algorithm-approach relationships

## 📁 Project Structure

```
masterthesis-Sim-To-Real-Gap/
├── README.md                          # Project documentation
├── requirements.txt                   # Python dependencies
├── SLR_analysis_notebook.ipynb       # Main analysis notebook
├── SLR_Analysis.xlsx                 # Systematic literature review dataset
└── img/                              # Generated visualizations
    ├── distribution_of_publication_country.png
    ├── distribution_of_publication_sjr.png
    ├── distribution_of_publication_year.png
    └── sankey_sim2real.png
```

## 🔧 Installation and Setup

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook/Lab
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/maxstablum/masterthesis-Sim-To-Real-Gap.git
   cd masterthesis-Sim-To-Real-Gap
   ```

2. **Create Conda environment (recommended):**
   ```bash
   conda create -n masterthesis-sim-to-real python=3.9
   conda activate masterthesis-sim-to-real
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

## 📊 Usage

### Data Filtering

⚠️ **Important Note**: To replicate the thesis results, you must filter the Excel file `SLR_Analysis.xlsx` in the "included" column for "yes" before processing.

### Running the Notebook

1. Open `SLR_analysis_notebook.ipynb` in Jupyter
2. Execute all cells sequentially
3. Visualizations will be automatically saved in the `img/` folder

### Main Features

#### 1. Descriptive Analysis
- Frequency distributions for all coded dimensions
- Bibliometric analysis (temporal, geographic, quality-based)

#### 2. Relational Analysis
- Multi-dimensional concept combinations
- Challenge-approach correspondence analysis
- Cross-tabular analyses

#### 3. Network Visualization
- Interactive Sankey diagram
- Challenge → Algorithm → Approach relationships

## 📈 Generated Visualizations

The notebook creates the following visualizations:

- **Temporal Distribution**: Publications per year
- **Geographic Distribution**: Publications by continent
- **Journal Quality**: SJR ranking distribution
- **Sankey Diagram**: Conceptual pathways

## 🔬 Methodology

### Data Processing
- Multi-value fields are systematically processed through list expansion
- Frequency analysis to identify patterns
- Combinatorial analysis for concept relationships

### Statistical Methods
- Descriptive statistics
- Cross-tabular analysis
- Network analysis

## 📋 Dataset

The dataset `SLR_Analysis.xlsx` contains coded data from reviewed publications with the following main categories:

- **Challenges**: Challenges (concept and subconcept level)
- **Simulator**: Simulation environments (concept and subconcept level)
- **Learning Algorithm**: Learning algorithms and concepts
- **Approaches**: Methodological approaches (concept and subconcept level)
- **Use Case**: Application domains

## 🛠️ Technical Details

### Core Libraries
- **pandas**: Data manipulation and analysis
- **matplotlib**: Statistical visualization
- **plotly**: Interactive diagrams
- **numpy**: Numerical computing
- **country-converter**: Geographic data standardization

### Export Options
- HTML export for interactive documentation
- PNG export for static visualizations
- Jupyter Notebook cleaning and conversion


## 👤 Author

- **Maximilian Stablum** - [GitHub](https://github.com/maxstablum)

---