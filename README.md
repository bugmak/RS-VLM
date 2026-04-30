# Awesome Remote Sensing Vision-Language Models (RS-VLM)

A curated survey of Vision-Language Models (VLMs) in Remote Sensing (RS), covering tasks such as visual grounding, open-vocabulary detection, VQA, captioning, and model acceleration.

---

## 🔥 Overview

Remote sensing vision-language models aim to bridge visual understanding and language reasoning in aerial and satellite imagery.  
Unlike natural images, RS data presents unique challenges such as:

- Large-scale scenes
- Dense objects
- Domain gap with natural images
- Multi-resolution and multi-sensor inputs

---

## 🧠 Taxonomy

We categorize RS-VLM methods into:

- **Visual Grounding**
- **Open-Vocabulary Detection (OVD)**
- **VQA / Captioning**
- **General RS-VLM**
- **Acceleration & Compression**

---

## 📊 Paper List

### 1. General RS-VLM

| Year | Paper | Venue | Task | Code |
|------|------|------|------|------|
| 2024 | LHRS-Bot | arXiv | General RS-VLM |[[Link](https://github.com/NJU-LHRS/LHRS-Bot)]  |
| 2024 | VHM | arXiv | RS multimodal understanding | [[Link](https://github.com/opendatalab/VHM)] |
| 2024 | GeoChat | CVPRW | RS dialogue | [[Link](https://github.com/mbzuai-oryx/GeoChat)] |
| 2024 | EarthDial | arXiv | RS grounding/dialogue | [[Link](https://github.com/hiyamdebary/EarthDial)] |

---

### 2. Visual Grounding

| Year | Paper | Venue | Task | Code |
|------|------|------|------|------|
| 2024 | Open-Text Aerial Detection | arXiv | Grounding + Detection | --- |
| 2025 | GeoGrounding | TBD | RS Grounding | [[Link](https://github.com/VisionXLab/GeoGround)] |

---

### 3. Open-Vocabulary Detection (OVD)

| Year | Paper | Venue | Task | Code |
|------|------|------|------|------|
| 2024 | OVA-DETR | arXiv | OVD | [[Link](https://github.com/wanggynpuer/OVA-DETR)] |
| 2024 | UAV-OVD | arXiv | UAV OVD | --- |

---

### 4. VQA / Captioning

| Year | Paper | Venue | Task | Code |
|------|------|------|------|------|
| 2023 | RSVQA | CVPR | RS-VQA | [[Link](https://github.com/syvlo/RSVQA)] |
| 2024 | RS Captioning models | - | Caption | [[Link](https://github.com/201528014227051/RSICD_optimal)] |

---

### 5. Acceleration & Compression ⭐（你的重点）

| Year | Paper | Venue | Task | Idea |
|------|------|------|------|------|
| 2024 | PIO-FVLM | arXiv | VLM Acceleration | Token pruning |
| 2024 | VLM Quantization | - | Compression | Quantization |

---

## 📦 Datasets

| Dataset | Task | Description |
|--------|------|------------|
| NWPU VHR-10 | Detection / Grounding | High-resolution aerial dataset |
| AID | Classification | Scene classification |
| RSVQA | VQA | QA dataset |
| DIOR | Detection | Large-scale detection |

---

## ⚙️ Evaluation Benchmarks

- Detection: mAP / AP50  
- Grounding: IoU / Accuracy  
- VQA: Accuracy  
- Efficiency: FPS / Latency / Memory  

---

## 🚀 Research Challenges

- Domain gap between RS and natural images  
- Lack of large-scale RS-VLM pretraining data  
- Poor generalization to unseen categories  
- High computational cost  

---

## 🔮 Future Directions

- Lightweight RS-VLM  
- Open-world RS understanding  
- Multi-modal multi-sensor fusion  
- Efficient deployment (Edge / UAV)  

---

## 📚 References

```bibtex
@article{lhrs_bot,
  title={LHRS-Bot},
  year={2024}
}
