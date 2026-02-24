# Akhilesh "Akhi" Warty

ML engineer based in Boston. I've worked on NIH-funded Alzheimer's research building survival models and ETL pipelines over UK Biobank and EHR data at scale, and independently on computer vision systems — object detection pipelines, edge deployment, and the low-level embedded work that goes with it. I tend to care about the parts that are easy to skip: correctness, reproducibility, and making analyses and models actually hold up under scrutiny.

Open to roles in AI/ML Engineering, Computer Vision, or Data/Software Engineering.

---

## Experience

**Data/ML Engineer — NIH-funded Alzheimer's Disease Research**

Built and validated longitudinal survival models (Cox PH, pooled logistic regression, mixed-effects) over UK Biobank and EHR datasets. Wrote statistical pipelines in R and Spark for data preparation, descriptive statistics, regression outputs, and publication-ready tables. Engineered Spark SQL ETL pipelines for extraction, validation, and preprocessing of large-scale clinical data supporting cohort analyses. Improved pipeline throughput by 13% through parallel Spark job scheduling optimization. Built an internal Python metadata management system for UK Biobank variables that standardized model specifications and enabled reproducible multiverse analyses across Alzheimer's and dementia cohorts. Contributed to manuscript development and presented findings to multidisciplinary stakeholders.

---

## Projects

**[MobileNetV2-SSD Detection Pipeline](https://github.com/AdmiralAki99/MobileNetV2-SSD)**
End-to-end SSD training framework built on MobileNetV2. Implements custom prior generation, anchor matching, hard-negative mining, and modular loss orchestration. Evaluation uses VOC-style mAP. Config-driven design with edge inference as a first-class concern.

**[Faster R-CNN from Scratch (TensorFlow)](https://github.com/AdmiralAki99/FasterRCNN)**
Full reimplementation of Faster R-CNN without pretrained scaffolding — custom RPN, dense RoI batching with GPU-friendly masking, and a complete two-stage training loop. Built with debuggability in mind: visualization utilities and failure-mode analysis throughout.

**[Data Pipeline Quality & Lineage API](https://github.com/AdmiralAki99/Data-Pipeline-Quality-Lineage-API)**
Spring Boot backend for tracking dataset and pipeline lineage, running automated quality checks, and maintaining audit logs. REST API with full OpenAPI documentation. CI/CD via GitHub Actions.

---

## Skills

**ML/CV:** TensorFlow/Keras, PyTorch, SSD, Faster R-CNN, loss design, evaluation metrics, model debugging  
**Backend/Data:** Python, Java (Spring Boot), SQL, REST APIs, data pipeline design  
**Infra:** Docker, GitHub Actions, AWS (EC2/S3), edge deployment, embedded Linux

---

[LinkedIn](https://www.linkedin.com/in/akhileshwarty) — wartyakhilesh@gmail.com
