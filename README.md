
<h1 align="center"> Yoga Pose Classification — EE604 (Image Processing)</h1>

<p align="center">
  <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white"></a>
  <a href="#"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-2.x-EE4C2C?logo=pytorch&logoColor=white"></a>
</p>

<p align="center">
  <b>107-class yoga pose recognition with transfer learning + pose-centric pretraining.</b><br/>
  <i>Best config (Xception + pose pretrain): Train 95.06% · Test 56.77%.</i>
</p>
<p align="center">
  <b>TEAM MEMBERS </b><br/>
  <i>Anukalp Rai,</i>
  <i>Norah Srivastava,</i>
  <i>Sanya,</i>
  <i>Akshat Chouksey,</i>
  <i>Mangal Meena</i>
</p>

---

## 
- **Task:** Classify **107** yoga poses from single images  
- **Approach:** Start from ImageNet backbones (**VGG16**, **Xception**), then **pose-centric pretraining** on a large human-pose corpus → fine-tune on yoga  
- **Data hygiene & augs:** Remove corrupt images; strong geometric/photometric augmentations for robustness  
- **Outcome:** Strong reps with a generalization gap → pointers for domain adaptation, curriculum, and keypoint cues

## Dataset
- Kaggle link: **https://www.kaggle.com/code/akshat2009/yoga-classification**

