
<div align="center">

# ScreenCAD

**Diagnosing 3D Volumes from Camera Video: A Semantic-Robust Framework Without Direct DICOM Access**  
*MICCAI 2026*

</div>

<div align="center">

![visitors](https://visitor-badge.laobi.icu/badge?page_id=5Junl/ScreenCAD)
[![GitHub Repo stars](https://img.shields.io/github/stars/5Junl/ScreenCAD?style=social)](https://github.com/5Junl/ScreenCAD/stargazers)

</div>


**Authors:** Junlei Wu*, Haolin Huang*, Jiaming Li, Qian Wang†  

## Abstract
Medical imaging traditionally assumes that high-fidelity, lossless data are required for reliable computer-aided diagnosis (CAD), an assumption inherited by AI models trained on pristine DICOM volumes. While 2D radiographs have shown tolerance to smartphone recapture, it remains unknown whether 3D volumetric diagnosis can survive the severe degradation introduced when a camera records slice scrolling as a video stream. This question is increasingly relevant as DICOM-level access and PACS integration impose substantial infrastructural barriers, particularly in resource-limited settings. We introduce \textbf{ScreenCAD}, a framework designed to test whether a 3D medical volume, transformed into a camera-captured video, still preserves sufficient semantic information for AI diagnosis. ScreenCAD combines cascaded ROI extraction, a frozen medical foundation model with strong semantic invariance, and a Task-Token Mixture-of-Experts aggregator to operate directly on low-fidelity, variable-length video streams. On CT-RATE with real-world screen recordings, ScreenCAD achieves competitive diagnostic performance under video inputs, while conventional 3D baselines degrade sharply. These results provide initial evidence that volumetric diagnosis can remain feasible under substantial information loss, highlighting camera-based acquisition as a promising interface for future medical AI systems when direct PACS integration is infeasible. Code will be released upon acceptance.

---

**Code coming soon.**
