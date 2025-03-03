<div align="center">

# 🚀 Welcome to My GitHub! 🌌

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Hello,%20I'm%20ChaeRin%20Jeong!&fontSize=40)

### 🌠 **Astrophysics | Numerical Simulations | Computational Science**
🔭 Passionate about **Astronomy & Computational Simulations**  
💻 Working with **Gizmo, Enzo, Gadget, Python, C++, Linux**  
📚 Currently studying at **Kyung Hee University, Dept. of Space Science**  
📧 Contact me: **fls3721@khu.ac.kr**  
🌍 Love **Exploring the Universe & Scientific Computing**  

---

## 🛠 **Tech Stack**
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Enzo-2E86C1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Gizmo-3498DB?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Gadget-1ABC9C?style=for-the-badge"/>
</p>

---


---

## 🌟 **Coding Activity**
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=your-username&theme=react-dark&hide_border=true" width="95%">
</p>

---

## 🚀 **Most Used Languages**
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-username&layout=compact&theme=tokyonight" width="50%">
</p>

---

## 🎯 **What I'm Working On**
- ⭐ **High-resolution Galaxy Simulations with AGORA**
- 🔬 **Comparing Gizmo vs. Enzo for Numerical Convergence**
- 🚀 **Analyzing Star Formation and Feedback Models**
- 📖 **Expanding Computational Astrophysics Skills**

---

## ✨ **Let's Connect!**
<p align="center">
  <a href="mailto:fls3721@khu.ac.kr"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://orcid.org/your-orcid"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/></a>
</p>

---

## 🛰 **Fun Facts about Me**
- 🌌 **Passionate about Space, Simulations, and Machine Learning**
- 🔭 **Dreaming of contributing to major astronomical discoveries**
- 🎮 **Loves Sci-Fi, Strategy Games, and Coding Challenges**
- 📝 **Currently writing a research paper on numerical simulations**

---



##  연구의 필요성
AGORA 프로젝트는 서로 다른 수치적 구현 방식(Gizmo vs. Enzo)이 동일한 물리적 모델을 적용할 때 수렴(convergence)할 수 있는지를 검증하는 것이 목표였습니다.  
그러나, 기존 연구에서는 수렴을 "캘리브레이션을 통한 조정"으로 접근했을 뿐, 이 수렴이 "물리적으로 의미 있는가?"에 대한 검증은 부족했습니다.

## ✔ 연구 질문
- AGORA 프로젝트에서 코드 간 수렴이 이루어졌다고 하지만, 이 수렴이 물리적으로 의미 있는가?  
- 별 형성률과 피드백 강도가 동일하게 조정되었을 때, 코드 간 수치적 차이가 여전히 존재하는가?  
- 수치적 방법(SPH vs. AMR)이 별 형성과 피드백 강도에 미치는 영향이 물리적 차이보다 중요한가?

## ✔ 연구 가설
- 피드백 강도와 SFE를 동일하게 맞추더라도, **Gizmo와 Enzo의 수치적 차이** 때문에 은하 진화가 다르게 나타날 것이다.  
- 기존 AGORA의 캘리브레이션이 코드 간 물리적 차이를 충분히 보정하지 못했을 가능성이 있다.  
- **수치적 구현 방식이 물리적 모델 차이보다 더 큰 영향을 미칠 수도 있다.**

---

##  논문 스토리라인
### 1️ 서론 (Introduction)
- AGORA 프로젝트 개요 및 기존 연구에서 제기된 코드 간 차이
- 기존 연구의 한계: 피드백과 SFE 연구는 많지만, **"수치적 방법 vs. 물리적 모델 차이"**를 정량적으로 분석한 연구는 부족함
- 본 연구의 목표: Gizmo와 Enzo의 수치적 차이가 피드백 및 SFE 변화보다 중요한지 검증

### 2️ 방법론 (Methodology)
- **사용할 코드**: Gizmo (SPH) vs. Enzo (AMR)  
- **파라미터 조정**:
  - 피드백 강도: 0.1× ~ 10×
  - 별 형성 효율 (SFE): 0.01 ~ 1.0
- **분석할 주요 물리량**:  
  - 별 형성률(SFR), 은하 질량 성장, CGM 특성, 금속 확산, outflow 구조

### 3️ 결과 (Results)
- **Fig. 1-3**: Gizmo vs. Enzo의 기본적인 수치적 차이 분석 (Density map, Temperature map 등)
- **Fig. 4-5**: 은하 질량 및 CGM의 차이
- **Fig. 6-7**: 피드백 강도 및 SFE 변화에 따른 별 형성 억제 효과 비교
- **Fig. 8-10**: 관측 가능성 (JWST에서의 예측 밝기 차이 등)

### 4️ 논의 (Discussion)
- 피드백 강도 및 SFE 변화가 두 코드에서 다르게 나타나는 이유
- **수치적 구현 방식의 차이가 물리적 모델 차이보다 중요한지 평가**
- AGORA에서 추가적인 보정이 필요한지 논의

### 5️ 결론 (Conclusion)
- 연구의 주요 발견 요약
- 향후 연구 방향 및 AGORA 프로젝트에 대한 기여

---

##  연구에서 제시할 Figure 추천 (10개 이상)
| Figure | 설명 및 기대 결과 |
|--------|----------------|
| **Fig. 1** | Gizmo vs. Enzo의 기본적인 수치적 차이 시각화 (Density map, Temperature map 등) |
| **Fig. 2** | 별 형성 속도(SFR) 비교: SFE 변화에 따른 결과 |
| **Fig. 3** | Feedback 강도에 따른 별 형성 억제 효과 비교 |
| **Fig. 4** | CGM (Circumgalactic Medium) 가스 분포 비교 |
| **Fig. 5** | Halo mass – Stellar mass 관계 비교 (HMSM Relation) |
| **Fig. 6** | 별 형성 이력 (Star Formation History) 분석 |
| **Fig. 7** | 은하 내 금속 분포 비교 |
| **Fig. 8** | JWST에서 예측되는 밝기 (UV Luminosity) 비교 |
| **Fig. 9** | Velocity field 비교 (Outflow 구조 분석) |
| **Fig. 10** | 가스 소실량 (Gas Loss Fraction) 비교 |

---

##  기존 연구와 차별점
### ✔ 기존 연구
- 피드백 강도와 SFE의 변화가 은하 진화에 미치는 영향을 분석하는 연구는 이미 많이 진행됨.
- 그러나 대부분의 연구는 **특정 코드 하나에서만 수행**됨.
- AGORA에서 코드 간 수렴을 맞추었지만, **실제로 물리적으로 의미 있는지에 대한 검증이 부족**함.

### ✔ 본 연구의 차별점
 수치적 구현 방식(SPH vs. AMR)의 차이가 물리적 모델 차이보다 더 중요한지 실험적으로 검증  
 동일한 피드백 강도 및 SFE 조건에서도 코드 간 차이가 여전히 존재하는지 분석  
 AGORA에서 캘리브레이션된 결과가 실제 물리적으로 타당한지 평가  

---

##  결론 및 기대 기여
### **만약 코드 간 차이가 크다면?**
- "AGORA에서 수렴한 결과가 단순한 조정(calibration) 때문이지, **실제 물리적 타당성을 의미하는 것은 아니다.**"
- "Enzo와 GIZMO는 동일한 물리적 파라미터에서도 **수치적 차이로 인해 결과가 다르게 나올 수 있다.**"

### **만약 코드 간 차이가 작다면?**
- "적절한 피드백 모델링과 캘리브레이션이 이루어진다면, **코드 간 차이는 무시할 수 있는 수준이다.**"
- "즉, **피드백과 SFE의 영향이 수치적 방법보다 훨씬 중요하다.**"

결과가 어느 쪽으로 나오든, 본 연구는 의미가 있음.  
왜냐하면 **"코드의 수치적 차이 vs. 물리적 차이"**라는 질문에 대해 실험적으로 검증하는 연구가 거의 없었기 때문.

---

##  최종 요약
 **AGORA 프로젝트에서 코드 간 수렴이 이루어졌다고 하지만, 이 수렴이 물리적으로 의미 있는가?**  
 **수치적 방법(SPH vs AMR)이 별 형성과 피드백 강도에 미치는 영향이 물리적 차이보다 중요한가?**  
 **동일한 피드백 강도와 SFE 조건에서도 Gizmo와 Enzo의 차이가 존재한다면, 그 원인은 무엇인가?**  

 **이 연구를 통해 AGORA의 수렴이 진정한 물리적 수렴인지, 아니면 단순한 조정(calibration) 결과인지 검증하는 것이 핵심!** 🚀

## 🖖 **Live Long and Explore the Universe! 🚀**
</div>
