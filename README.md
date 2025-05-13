## Electric Fish Neural Spike Analysis

This project analyzes the firing behavior of neurons in electric fish based on stimulus data, originally provided as part of MIT's 9.29J: *Introduction to Computational Neuroscience*.

---

## Project Description

This repository contains a Python-based solution to a classic computational neuroscience problem set originally developed at MIT. The study revolves around the electrosensory system of the weakly electric fish *Eigenmannia*, focusing on:

- Spike train analysis  
- Convolution-based firing rate estimation  
- Modeling neural response to stimulus input using linear regression  
- Correlation and autocorrelation exploration

---

## Original Source

> This project is based on **Problem Set 1** from MIT’s  
> “9.29J: *Introduction to Computational Neuroscience*”, Spring 2004,  
> taught by **Prof. Sebastian Seung**.

**Research Paper Reference:**  
R. Wessel, C. Koch, and F. Gabbiani,  
“*Coding of time-varying electric field amplitude modulations in a wave-type electric fish*”,  
*Journal of Neurophysiology*, 75:2280–2293 (1996).

📄 Assignment PDF: `first problem.pdf`  
📥 Dataset: [`fish.mat`](http://web.mit.edu/9.29j/www/assignments/fish.mat)

---

## Project Aims

- Visualize electrosensory stimulus and spike train  
- Estimate firing rates using boxcar filter convolution  
- Fit linear models to stimulus-response data  
- Perform auto- and cross-correlation analysis  
- Explore the limits of linear encoding in spiking neurons

---

## Folder Structure

```
fish-analysis/
├── fish_data_analysis.ipynb   #  Python solution notebook
├── MIT_first problem.pdf      #  Original MIT assignment
└── README.md                  #  This file
---

## Getting Started

### Prerequisites

Make sure you have Python 3.x and the following libraries:

```bash
pip install numpy matplotlib scipy
```

### Running the Notebook

1. Download the dataset [`fish.mat`](http://web.mit.edu/9.29j/www/assignments/fish.mat)  
2. Place it in the same folder as `fish_data_analysis.ipynb`  
3. Launch the notebook in Jupyter and run all cells

---

## Example Analyses

- Plotting stimulus and spike train  
-  Firing rate estimation using convolution  
-  Linear regression: stimulus → firing rate  
-  Autocorrelation and cross-correlation of signals  
-  Mathematical analysis of spike train statistics

---

## License & Fair Use Disclaimer

This work is for **educational and demonstrational purposes only**.  
All credit for the original problem design belongs to **MIT** and the authors of the referenced research.

>  Do not use this repository to commit academic dishonesty or plagiarism.

---

## Author

Developed and converted to Python by **Handan VURAL**  
Guided by the original curriculum from MIT Brain and Cognitive Sciences

