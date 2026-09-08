<h1 align="center">Hyunkyu Kang</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&amp;weight=600&amp;size=22&amp;duration=3200&amp;pause=900&amp;color=2F80ED&amp;center=true&amp;vCenter=true&amp;width=760&amp;lines=Human-Scene+Interaction+%7C+Motion+Generation;Affordance+Learning+%7C+Embodied+AI;From+Language+and+3D+Scenes+to+Motion" alt="Human–Scene Interaction · Motion Generation · Embodied AI" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Human--Scene%20Interaction-2F80ED?style=flat-square" alt="Human–Scene Interaction" />
  <img src="https://img.shields.io/badge/Focus-Motion%20Generation-27AE60?style=flat-square" alt="Motion Generation" />
  <img src="https://img.shields.io/badge/Focus-Affordance%20Learning-9B51E0?style=flat-square" alt="Affordance Learning" />
  <img src="https://img.shields.io/badge/Systems-Embodied%20AI-F2994A?style=flat-square" alt="Embodied AI" />
</p>

<p align="center">
  <a href="https://khk0606.github.io/"><img src="https://img.shields.io/badge/Portfolio-khk0606.github.io-111111?style=flat-square&amp;logo=githubpages" alt="Academic website" /></a>
  <a href="https://khk0606.github.io/files/CV_HyunkyuKang.pdf"><img src="https://img.shields.io/badge/CV-Download%20PDF-2F80ED?style=flat-square" alt="Download CV" /></a>
  <a href="mailto:khk0606@naver.com"><img src="https://img.shields.io/badge/Contact-Email-D14836?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
</p>

I study **human–scene interaction, affordance-aware motion generation, and embodied AI**.

I am an undergraduate in the School of Art and Technology at **Chung-Ang University**, with additional studies in Data Privacy. I participated in the AI·SW Convergence Undergraduate Researcher Program at **CREAL Lab**, advised by **Prof. Taeil Jin**, from July to August 2026.

My work explores how **language, spatial relationships, and interaction history** can guide motion: not just where an action is possible, but how it should unfold over time. My projects span motion-data pipelines, scene-conditioned generation, robot simulation, and language-model robustness.

## Research Interests

- Human–scene interaction and purpose-conditioned affordances
- Interaction history and temporal representations
- Scene-conditioned motion generation with diffusion models
- Teacher adaptation, LoRA, and mixture-of-experts routing
- Video-to-robot motion transfer and simulation-based control

## Research

| Work | Focus | Status |
| --- | --- | --- |
| [Affordance-aware motion generation](https://khk0606.github.io/research/#affordance-aware-motion-generation) | Purpose, scene geometry, and interaction history for human motion | Ongoing research |
| [Temporal interaction diagnostics](https://khk0606.github.io/research/#temporal-diagnostics-for-interaction-representations) | Order-information loss in pooled interaction representations | Experimental analysis |
| [YBot / HumanML263 data pipeline](https://khk0606.github.io/research/#motion-data-processing-and-validation) | Motion conversion, natural trajectories, and data consistency | Validated 162-sequence dataset |

These entries describe research projects and experiments, not peer-reviewed publications.

## Selected Projects

| Project | Description |
| --- | --- |
| [ADM-MoE-Teacher](https://github.com/khk0606/ADM-MoE-Teacher) | Scene-conditioned human motion research with teacher adaptation, MoE routing, contact supervision, and reproducible evaluation. |
| [Video-to-Robot Motion Transfer](https://github.com/khk0606/Zero-Shot-Video-to-Robot-Motion-Transfer) | Reference-video interpretation, motion specifications, and Dial-MPC control for a quadruped in MuJoCo/MJX simulation. |
| [Korean Text Robustness](https://github.com/khk0606/Korean-Hate-Speech-Robustness-under-Text-Obfuscation) | Korean hate-speech classification under text obfuscation, with normalization, calibration, and error-trade-off analysis. |
| [Chair Pose](https://github.com/khk0606/chair_pose) | A vision-language-model prototype for plausible 2D sitting keypoints from a chair-only image. |

## Tools & Technologies

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&amp;logo=numpy&amp;logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&amp;logo=scikitlearn&amp;logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&amp;logo=huggingface&amp;logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/JAX-5E97F6?style=flat-square" alt="JAX" />
  <img src="https://img.shields.io/badge/MuJoCo-00695C?style=flat-square" alt="MuJoCo" />
  <img src="https://img.shields.io/badge/Unity-222222?style=flat-square&amp;logo=unity&amp;logoColor=white" alt="Unity" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&amp;logo=git&amp;logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=black" alt="Linux" />
</p>

## Research Workflow

- Build data pipelines with explicit coordinate, representation, and split checks.
- Inspect motion visually alongside numerical metrics.
- Document experimental assumptions, failed validation gates, and limitations.
- Keep prototype behavior separate from validated end-to-end results.

<details>
<summary><b>한국어 소개</b></summary>

<br>

안녕하세요, **강현규**입니다. 중앙대학교 예술공학부에서 공부하며 데이터 프라이버시 분야를 함께 이수하고 있습니다. 2026년 7–8월에는 진태일 교수님의 **CREAL 연구실**에서 AI·SW융합 학부연구생 프로그램에 참여했습니다.

관심 분야는 **인간–장면 상호작용, 어포던스 기반 동작 생성, Embodied AI**입니다. 언어와 3D 공간 정보, 과거 상호작용 이력을 결합해 상황에 맞는 행동을 생성하는 방법을 탐구하고 있습니다.

**주요 작업**

- 목적·장면·이력 조건을 반영하는 어포던스 표현과 동작 생성 파이프라인
- YBot 동작의 HumanML263 변환 및 데이터·좌표·분할 일관성 검증
- 시간 정보를 보존하는 상호작용 표현 분석
- 영상 기반 로봇 동작 전이와 시뮬레이션 제어
- 텍스트 변형에 대한 한국어 혐오표현 분류 모델의 강건성 평가

연구 과정에서는 수치와 시각화를 함께 확인하고, 검증된 결과와 아직 진행 중인 실험을 구분해 기록합니다.

</details>

## Links

- Website: [khk0606.github.io](https://khk0606.github.io/)
- CV: [Download PDF](https://khk0606.github.io/files/CV_HyunkyuKang.pdf)
- Email: [khk0606@naver.com](mailto:khk0606@naver.com)
