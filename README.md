# Electric-Fish-Neural-Spike-Analysis
This project analyzes the firing behavior of neurons in electric fish based on stimulus data, originally provided as part of MIT's 9.29J: Introduction to Computational Neuroscience.

# Electric Fish Neural Spike Analysis

This repository contains a Python-based solution to a classic computational neuroscience problem set originally developed at MIT (Course 9.29J - *Introduction to Computational Neuroscience*). The study revolves around the electrosensory system of the weakly electric fish *Eigenmannia*, focusing on spike train analysis, convolution-based firing rate estimation, and modeling neural response to stimulus input.

##  Original Source

>  This project is based on Problem Set 1 from MIT’s “9.29J: Introduction to Computational Neuroscience”, Spring 2004, taught by Prof. Sebastian Seung.  
>  
>  Research Paper Reference:  
> R. Wessel, C. Koch, and F. Gabbiani, “Coding of time-varying electric field amplitude modulations in a wave-type electric fish”, *Journal of Neurophysiology*, 75:2280–2293 (1996).  
>
>  Assignment PDF: `first problem.pdf`  
>  Dataset: [`fish.mat`](http://web.mit.edu/9.29j/www/assignments/fish.mat)

---

##  Project Aim

-  Visualize electrosensory stimulus and spike train
-  Estimate firing rates using boxcar filter convolution
-  Fit linear models to stimulus-response data
-  Perform correlation and autocorrelation analysis
-  Explore limits of linear encoding in spiking neurons

---

## 🗃️ Folder Structure

```plaintext
fish-analysis/
├── fish_data_analysis.ipynb   #  Your Python solution notebook
├── first problem.pdf          #  Original assignment from MIT
├── README.md                  #  This file
└── .gitignore                 #  Ignore unnecessary files
```

---

## Getting Started

Prerequisites
Make sure you have Python 3.x and the following libraries installed:

pip install numpy matplotlib scipy
Running the Notebook
Download the dataset fish.mat and place it in the same directory.
Open fish_data_analysis.ipynb in Jupyter Notebook or Jupyter Lab.
Run the cells sequentially to view plots and results.

---

Example Analyses

- Plotting stimulus and spike train
- Convolution-based firing rate estimation
- Linear regression: stimulus → firing rate
- Auto- and cross-correlation of stimulus and spikes
- Explanation of variance properties in binary vectors

---

License & Fair Use Disclaimer

This work is for educational and demonstrational purposes only. All credit for the original problem design goes to MIT and the authors of the referenced research.
Do not use this repository for cheating or academic dishonesty in your own coursework.

---

Author

Developed and converted to Python by [Handan VURAL]
Course Adaptation and Guidance by MIT Brain and Cognitive Sciences






