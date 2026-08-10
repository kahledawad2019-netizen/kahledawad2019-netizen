# Khaled Metwalie

**Data Science · Applied AI · Computer Vision · Healthcare Analytics**

Licensed pharmacist turned data scientist. I spent two years behind a pharmacy counter watching
real decisions reach real patients — a misread interaction, a wrong dose, a stockout on a
life-saving drug. That is where the standard I hold my models to comes from.

[Portfolio](https://khaledmetwalie.lovable.app/) ·
[LinkedIn](https://linkedin.com/in/khaled-m-947583172) ·
[Email](mailto:khaledawad@hotmail.com)

---

## About

I build end-to-end systems: raw data to trained model to something a person can actually use.
Trained through the **Digital Egypt Pioneers Initiative (DEPI)** under the Ministry of
Communications, with a B.Pharm from Mansoura University behind it.

Two things I care about more than headline metrics:

- **Whether a result is real.** Several projects below contain an experiment that failed and is
  reported anyway — a five-seed study that killed a model I had already built, an augmentation
  change that made things worse, a re-tiling strategy that regressed. Those are the evidence
  that the numbers I *do* report were earned.
- **Domain understanding.** I know what pharmaceutical and clinical data *means*, not just what
  it says.

---

## Featured Projects

### Computer Vision — industrial and scientific inspection

**[Steel Surface Defect Detection](https://github.com/kahledawad2019-netizen/steel-defect-detection)**
Six-class defect detection on hot-rolled steel (NEU-DET, YOLOv8). Reimplemented three published
"improved YOLO" variants, then ran a **five-seed statistical gate** — none beat plain YOLOv8n on
a 180-image test set, so the baseline shipped. 0.7475 ± 0.0161 mAP@0.5 · 174.6 FPS. Includes a
measured PyTorch/ONNX/TensorRT benchmark and a FastAPI + React inspection app.

**[Fabric Defect Detection](https://github.com/kahledawad2019-netizen/fabric-defect-detection)**
Twenty-class woven-fabric defect detection (Tianchi), built on a **hash-frozen dataset** and an
evaluation gate that refuses to tabulate runs whose config or data drifted. Ghost backbone cut
parameters 43% at equal accuracy; SimAM and WIoU proved to be within noise and are reported that
way. Largest lever was input representation (+46%), not architecture.

**[Seismic Fault Detection](https://github.com/kahledawad2019-netizen/seismic-fault-detection)**
3D U-Net for fault segmentation, trained **entirely on synthetic volumes** and applied zero-shot
to two real surveys (Netherlands F3, Penobscot) — the transfer approach used in production
geoscience, because real surveys have no dense labels. Test F1 0.877 ± 0.034; over 93% of
real-data detections form coherent fault surfaces.

**[Motherboard Defect Detection](https://github.com/kahledawad2019-netizen/motherboard-defect-detection)**
Eleven-class electronics assembly QA — missing, loose and incorrect fasteners, detached fan
ports, scratches. Test mAP@0.5 0.937 at 47 FPS. Resolution mattered more than model capacity;
added augmentation regressed and is reported as a negative result.

### Healthcare AI and Analytics

**[Hospital Length of Stay Prediction](https://github.com/kahledawad2019-netizen/Hospital-LOS-DataMining)**
318,438 patient records across a **22-table 3NF database**, predicting length of stay over 11
classes. Full data engineering and analytics pipeline with Power BI dashboards.

**[Hotel Booking Cancellation Prediction](https://github.com/kahledawad2019-netizen/Hotel-Reservation-DataMining)**
Stacking ensemble reaching **92.93% accuracy** over 119,208 records and 60+ engineered features.
Pipeline: SQL Server → Python EDA → 8-model comparison → Power BI.

**[Pharma Demand Forecasting](https://github.com/kahledawad2019-netizen/pharma-demand-forecasting)**
Time-series forecasting across 8 drug categories with XGBoost and Random Forest, served through a
**FastAPI** inference endpoint.

**[Pharma Sales Analysis](https://github.com/kahledawad2019-netizen/Pharma-Sales-Analysis)**
600,000+ transactions over 6 years, with an ATC-to-plain-English layer so non-pharmacists could
act on the findings.

### RAG / LLM and Deep Learning

**[Pharmacist RAG Assistant](https://github.com/kahledawad2019-netizen/pharmacist-rag-assistant)**
Retrieval-augmented drug Q&A grounded in source documents, aimed at the questions pharmacists
actually field. See also [pharma-rag](https://github.com/kahledawad2019-netizen/pharma-rag), a
from-scratch RAG pipeline.

**[HYDRA-Net — Counter-UAV Detection](https://github.com/kahledawad2019-netizen/hydra-net)**
Cascaded multimodal architecture over 128K RF signal segments: **90.07% accuracy**, F1 0.9003,
ROC-AUC 0.9812, and a **91.9× median latency reduction** via confidence-gated early exit.

**[DeepSign AI — Signature Verification](https://github.com/kahledawad2019-netizen/signature-verification)**
Offline handwritten signature verification with a Siamese ResNet18 trained under contrastive loss
on the CEDAR dataset.

---

## Technical Skills

**Languages** — Python · SQL · TypeScript

**Machine Learning** — scikit-learn · XGBoost · Random Forest · stacking ensembles ·
time-series forecasting · class-imbalance handling

**Deep Learning** — PyTorch · Ultralytics YOLO · 3D U-Net · Siamese networks · custom modules
(attention, IoU losses) · transfer learning · Eigen-CAM explainability

**Computer Vision** — Object detection · semantic segmentation · sliced/tiled inference ·
dataset auditing and de-duplication

**LLM / RAG** — Retrieval-augmented generation · grounded question answering · document
retrieval pipelines

**Experimental Method** — Controlled ablations · multi-seed studies with significance testing ·
dataset freezing by hash · fairness-gated evaluation · negative-result reporting

**Data & BI** — Pandas · NumPy · SQL Server · database design (3NF) · Power BI · Excel

**Deployment** — FastAPI · Streamlit · Docker · Hugging Face Spaces · ONNX / TensorRT export ·
latency benchmarking

---

## Education

| Programme | Institution | Detail |
|---|---|---|
| Data Analytics & Applied AI | DEPI / Ministry of Communications & MTC | Digital Egypt Pioneers Initiative |
| B.Pharm | Mansoura University | GPA 3.15 · May 2023 |
| Biostatistics & Clinical Research | Mansoura University | Coursework |

---

## Current Direction

Applied machine learning where labels are scarce or expensive and the honest question is not
"what is the best score" but "is this measurement trustworthy enough to act on" — industrial and
scientific inspection, healthcare analytics, and retrieval-grounded assistants.

Open to Data Science, Applied AI, Computer Vision and Healthcare Analytics roles.
