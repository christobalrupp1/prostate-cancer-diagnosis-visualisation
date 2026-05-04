# Prostate Cancer Diagnostic Pathway - BPMN Process Model & Interactive Simulator

A BPMN-based process model of the prostate cancer diagnostic pathway in the German healthcare system, built as a foundation for patient flow simulation.

---

## Overview

This repository accompanies the seminar paper **"Establishing the Foundation for Clinical Process Simulation: An Analysis of Prostate Cancer Diagnostic Pathways Using BPMN"**, developed at the University of Mannheim. It maps the full diagnostic pathway for suspected prostate cancer, from initial PSA measurement to tumor board decision, as a formal BPMN process model grounded in the S3-Leitlinie Prostatakarzinom v8.1. The model includes 8 process steps, 6 decision gateways, pathway probabilities derived from three clinical trials, and resource estimates drawn from four regulatory sources.

---

## Getting Started

No installation required. Download `index.html` and open it in any modern browser.

---

## Features

- **Simulation mode** — animated patient journey through the diagnostic pathway
- **Heatmap mode** — patient flow across 100,000 simulated patients
- **Compare mode** — two scenarios side by side with divergence markers
- **Resource overlay** — time, personnel, and equipment per process step
- **Info modals** — medical background and guideline references per node

---

## Project Structure

```
├── S3-Process_FINAL.bpmn    # BPMN process model
├── index.html               # Self-contained interactive simulator
└── README.md
```

---

## Authors

Christobal Rupp — University of Mannheim  
Supervised by Michael Sternberg — Chair of General Management and Information Systems  

---

## References

Leitlinienprogramm Onkologie (Deutsche Krebsgesellschaft, Deutsche Krebshilfe, AWMF) (2025). S3-Leitlinie Prostatakarzinom, Langversion 8.1. AWMF-Registernummer 043-022OL.

Arsov et al. (2022). PROBASE Trial — A randomized trial of risk-adapted screening for prostate cancer in young men. *Int J Cancer*, 150(11), 1861–1869.

Josefsson et al. (2024). GÖTEBORG-2 — Performance of 4Kscore as a Reflex Test to PSA in the GÖTEBORG-2 Prostate Cancer Screening Trial. *European Urology*, 86(3), 223–229.

Boesen et al. (2019). Prebiopsy Biparametric MRI Combined with PSA Density in Detecting and Ruling out Gleason 7–10 Prostate Cancer in Biopsy-naïve Men. *European Urology Oncology*, 2(3), 311–319.

---

## Disclaimer

This repository and all associated files are developed strictly for academic research purposes as part of a seminar paper at the University of Mannheim. The process model, pathway probabilities, and resource estimates are derived from published clinical guidelines and peer-reviewed literature and are intended to serve as a structured foundation for subsequent simulation research — not as clinical guidance.

The content of this repository does not constitute medical advice and must not be used to inform clinical decision-making or patient care. All medical decisions should be made exclusively by qualified healthcare professionals in accordance with current clinical guidelines.
