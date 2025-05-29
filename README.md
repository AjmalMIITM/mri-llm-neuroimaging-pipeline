<div align="center" style="background-color:#212121; color:#e0e0e0; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; padding: 22px 20px; border-radius: 12px;">

<h1 style="font-weight: 700; font-size: 2.1em; color:#00bcd4; margin-bottom:14px;">
MRI + LLM Neuroimaging Pipeline
</h1>

<p style="font-size: 1.15em; color:#b0bec5; margin-bottom: 16px;">
A modular, AI-powered workflow for MRI preprocessing, quantitative feature extraction, and LLM-driven clinical reporting.<br>
Inspired by research at the Sudha Gopalakrishnan Brain Centre, IIT Madras.
</p>

<hr style="border: 1.5px solid #00bcd4; width: 60%; margin: 18px auto;"/>

</div>

## Overview

This repository presents an end-to-end pipeline for automated MRI analysis and clinical-style report generation using large language models (LLMs).  
The workflow is designed for research, reproducibility, and seamless integration with modern AI APIs.

---

## Features

- **MRI Preprocessing:** High-pass filtering and CLAHE contrast enhancement for improved tissue visualization.
- **Feature Extraction:** Automated calculation of intensity statistics (mean, std, min, max) for downstream analysis.
- **LLM Integration:** Modular interface for LLaMA 3 API (or any LLM) to generate structured, natural language reports from imaging features.
- **Kaggle/Colab Ready:** Downloadable outputs, clean code, and reproducible workflow.
- **Research Alignment:** Follows best practices from the Sudha Gopalakrishnan Brain Centre and contemporary neuroimaging AI.

---

## Quick Start

1. **Clone this repository**
- git clone https://github.com/AjmalMIITM/mri-llm-neuroimaging-pipeline.git
  
2. **Open the notebook**  
Use Jupyter, Colab, or Kaggle.

3. **Run all cells**  
- Upload your MRI image(s)
- Enter your LLaMA 3 API key (if available)
- Download outputs from the `output_images/` directory

4. **Try it on Kaggle**  
[View the full notebook on Kaggle](https://www.kaggle.com/code/ajmaliitm/implementing-a-multi-modal-neuroimaging-analysis)

---

## Example Output

- **AI-Generated Report:**  
<pre>
MRI Brain Scan Detailed Report:
- Mean Intensity: 24.19
- Standard Deviation: 34.30
- Maximum Intensity: 255.00
- Minimum Intensity: 4.00

Clinical Interpretation:
- Good contrast and intensity distribution.
- No abnormal hyperintensities or hypointensities detected.
- Recommend further segmentation and region-specific analysis.
</pre>

---

## References & Acknowledgements

- **Dataset:** LGG MRI Segmentation Dataset ([Kaggle](https://www.kaggle.com/datasets))
- **Libraries:** NumPy, OpenCV, PIL, Matplotlib, Transformers, Qdrant Client
- **LLM:** LLaMA 3 API (Meta AI, 2024)
- **Research Inspiration:** Sudha Gopalakrishnan Brain Centre, IIT Madras
- **Key Papers:**
 - SHFormer: Dynamic Spectral Filtering for MRI Reconstruction, Neural Networks, 2025.
 - DHARANI: 3D Digital Brain Atlas of the Indian Population, J. Comp. Neurol., 2025.

---

## License

This project is for academic and research demonstration purposes.

---

<div align="center" style="color:#b2ebf2;">
Developed as part of the Sudha Gopalakrishnan Brain Centre internship showcase.
</div>
