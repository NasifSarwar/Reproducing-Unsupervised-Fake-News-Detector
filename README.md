# Unsupervised Fake News Detection — Reproducibility Study

This repository reproduces and extends the experiments from the paper  
**[“Unsupervised Fake News Detection on Social Media Using Hybrid Gaussian Mixture Model (GMM–GCO)”](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0330421)** (PLOS ONE, 2025).

Original implementation reference:  
**GitHub:** [https://github.com/perveen-2025/GMM-GCO-FakeNews](https://github.com/Sajida-Perveen/Project-code) *(from paper)*

---

## Repository Structure

| File | Description |
|------|--------------|
| **Unsupervised_Learning_Fake_News_Detector_Reproducibility.ipynb** | Jupyter notebook reproducing the baseline unsupervised models (K-Means, K-Medoids, GMM). Includes full preprocessing, clustering, and evaluation steps. |
| **GMM_+_GCO.ipynb** | Implementation of the hybrid **GMM–GCO** model. Integrates Group Counseling Optimization (GCO) for global parameter tuning of the Gaussian Mixture Model. |
| **news_data.tsv** | Original raw dataset containing labeled/unlabeled social media news samples used in the study. |
| **preprocessed_news_data (1).csv** | Cleaned and preprocessed version of `news_data.tsv` — includes feature vectors (TF-IDF or embeddings) used directly for clustering in both baseline and hybrid models. |

---

## Objective

To **reproduce** and **validate** the reported performance of the GMM–GCO hybrid model for unsupervised fake news detection, ensuring transparency and reproducibility of results.

---

## ⚙️ Usage

1. Clone the repository.  
2. Open notebooks in Jupyter or Google Colab.  
3. Run `Unsupervised_Learning_Fake_News_Detector_Reproducibility.ipynb` to reproduce baseline results.  
4. Run `GMM_+_GCO.ipynb` to execute the hybrid model and compare metrics (Silhouette, ARI, Purity).  

---

## 📄 Reference

Perveen, S. et al. (2025). *Unsupervised Fake News Detection on Social Media Using Hybrid Gaussian Mixture Model (GMM–GCO)*.  
**PLOS ONE**, 20(3): e0330421.  
[https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0330421](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0330421)
