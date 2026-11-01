# Jihun Rho

### CUDA & GPU Performance Engineer · Computer Vision

**Building high-throughput vision systems, from CUDA kernels to real-time applications.**

Seoul, South Korea · Open to remote opportunities

[![Portfolio](https://img.shields.io/badge/Portfolio-76B900?style=for-the-badge&logo=googlechrome&logoColor=white)](https://931njhthe-star.github.io/)
[![Email](https://img.shields.io/badge/Email-555555?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hunjirho@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-1f6feb?style=for-the-badge&logo=readthedocs&logoColor=white)](https://931njhthe-star.github.io/#contact)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/931njhthe-star)

---

## About me

My work spans **GPU performance engineering, computer vision, and real-time systems**. I have **4 years 8 months of hands-on CUDA/C++ experience** optimizing industrial machine-vision workloads, alongside research experience in vision and software work integrating robotics and sensors.

I focus on profiling-driven optimization: identifying pipeline bottlenecks, choosing what belongs on the CPU or GPU, and tuning kernels, memory use, and execution overlap. In production, this work contributed to **11.2× throughput over a single-core CPU baseline**, **~40% over a multi-core CPU-only pipeline**, and throughput of **2.52 million images per hour**.

Currently completing a full-time AI Orchestration program while building end-to-end vision and inference systems.

## Featured Project

### High-Throughput CUDA Vision Pipeline

Production machine-vision work for pharmaceutical inspection. I optimized the CPU–GPU processing pipeline through selective CUDA acceleration, workload allocation, kernel and memory tuning, and NVIDIA Nsight profiling. Proprietary algorithms and implementation details are not disclosed.

- **11.2× higher throughput** than a single-core CPU baseline
- **~40% higher throughput** than a multi-core CPU-only pipeline
- **2.52 million images/hour**, processing 12 views per inspected object
- Selective GPU acceleration for compute-intensive operations

**Tech stack:** `C++` · `CUDA` · `Nsight Systems` · `Nsight Compute` · `Computer Vision`

[Portfolio project overview](https://931njhthe-star.github.io/#projects)

## More Projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://931njhthe-star.github.io/drivefusion/"><img src="https://931njhthe-star.github.io/assets/drivefusion.gif" width="100%" alt="DriveFusion camera-radar perception dashboard"></a>

### DriveFusion — Real-Time Camera–Radar Perception & Evaluation

A solo CARLA project combining YOLO11n detection, vehicle tracking, radar-assisted distance estimation, and a Qt monitoring dashboard. A C++/CUDA TensorRT module runs inference; session recording and ground-truth evaluation support repeatable comparisons across nine driving sessions.

**Evaluation:** 16,491 common samples, **5.41% lower overall distance MAE**; 437 radar-corrected samples, **39.42% lower MAE**.

**C++ · CUDA · TensorRT · YOLO11n · Qt · CARLA · Radar fusion**

[Project page](https://931njhthe-star.github.io/drivefusion/) · [Repository](https://github.com/931njhthe-star/DriveFusion)

</td>
<td width="50%" valign="top">

<a href="https://github.com/931njhthe-star/subsync-ai-tutor"><img src="https://931njhthe-star.github.io/assets/subsync.gif" width="100%" alt="SubSync browser extension and AI tutor"></a>

### SubSync — AI-Powered YouTube English Tutor

Led a five-person team building a Chrome extension MVP for learning English with synchronized subtitles, saved vocabulary, and an AI tutor. Integrated the extension with backend APIs, authentication, storage, and caching. The backend test suite passed all 79 tests.

**Chrome Extension (MV3) · FastAPI · AI agent · Supabase · Redis**

[Repository](https://github.com/931njhthe-star/subsync-ai-tutor)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<a href="https://931njhthe-star.github.io/robotics-vision/"><img src="https://931njhthe-star.github.io/assets/robotics-system-flow-original.png" width="100%" alt="Robotics integration overview with Solomon 3D vision, Doosan robot arms, MiR AMR, and LMS"></a>

### Robotics & 3D Bin-Picking System Integration

At INA Oriental Motor, integrated a MiR autonomous mobile robot, a Doosan six-axis robot, Solomon 3D vision, and pneumatic gripper control into a coordinated demonstration system. Developed software interfaces for existing device controllers and coordinated robot, vision, and gripper workflows.

**Python · REST · TCP/IP · Modbus · Digital I/O · 3D vision**

[Project page](https://931njhthe-star.github.io/robotics-vision/) · [Demonstration video](https://www.youtube.com/watch?v=wLmfVy-GDSs)

</td>
</tr>
</table>

## Technical skills

| Area | Skills and tools |
|---|---|
| **GPU performance** | C++, CUDA kernels, memory tuning, stream overlap, occupancy, CPU–GPU pipeline optimization |
| **Profiling** | NVIDIA Nsight Systems, NVIDIA Nsight Compute, performance analysis |
| **Computer vision** | OpenCV, image processing, detection, tracking, calibration, camera–radar fusion |
| **Inference** | TensorRT, YOLO, real-time evaluation |
| **Systems** | Multithreading, Qt, CMake, Windows, Linux |
| **Robotics & integration** | Robot control, REST, TCP/IP, Modbus, Digital I/O |
| **AI application engineering** | Python, FastAPI, LangGraph, Docker, CI/CD |

## Experience

- **Enclony** · Research Engineer, CUDA & GPU Performance · Mar 2021 – Oct 2025
- **Sejong University** · Computer Vision Researcher · Nov 2019 – Oct 2020
- **INA Oriental Motor** · Software Engineer, Robotics & Vision Integration · Jan 2018 – Oct 2019

## Education

**B.S. in Electronic Engineering** · Sejong University  
Engineering Accreditation · GPA: 3.38 / 4.5

---

<div align="center"><sub>GPU performance · Real-time vision · High-throughput systems</sub></div>

