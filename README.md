<div align="center">

# Üzeyir (Khuzair) Askyer

**Robotics Software & Distributed Systems Engineer**  
*Deterministic Autonomous Systems · Edge AI & Perception · Production Full-Stack Architecture*

[![Portfolio](https://img.shields.io/badge/Portfolio-huzarh.github.io-C8953C?style=flat-square&logo=googlechrome&logoColor=white)](https://huzarh.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-uzeyiraskyer-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/uzeyiraskyer)
[![Email](https://img.shields.io/badge/Direct_Contact-huzarh44%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:huzarh44@gmail.com)
[![Location](https://img.shields.io/badge/Location-%C4%B0stanbul%2C_TR-18181B?style=flat-square&logo=openstreetmap&logoColor=white)](https://huzarh.github.io)
[![Followers](https://img.shields.io/github/followers/huzarh?style=flat-square&label=Followers&color=18181B)](https://github.com/huzarh?tab=followers)

</div>

---

### 🛰️ Engineering Profile

I design and build software systems where **determinism, low latency, and reliability** are non-negotiable — spanning from hard real-time control loops on PREEMPT_RT Linux and Jetson SoCs to production-grade distributed backend services.

My engineering work converges on two connected domains:
- **Autonomous Robotics & Edge Systems**: Perception-to-action autonomy stacks, real-time UAV mission planning, visual target tracking, sensor calibration (LiDAR/Camera), and simulation-first validation (ROS 2, Gazebo Harmonic, PX4/MAVLink).
- **Resilient Full-Stack Architecture**: Clean, modular application ecosystems, role-based backend microservices, real-time WebSocket telemetry, and containerized cloud/edge infrastructure (NestJS, TypeScript, Next.js, PostgreSQL/Prisma, Redis, Docker).

---

### 🛠️ Core Disciplines & Technology Stack

| Domain | Core Toolchain & Technologies |
| :--- | :--- |
| **Robotics & Autonomy** | ![ROS 2](https://img.shields.io/badge/ROS_2-Humble_%2F_Jazzy-22314E?style=flat-square&logo=ros&logoColor=white) ![PX4](https://img.shields.io/badge/PX4-Autopilot-1F2937?style=flat-square&logo=drone&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-Harmonic-FF6B6B?style=flat-square&logo=gazebo&logoColor=white) ![Nav2](https://img.shields.io/badge/Nav2-Navigation-3B82F6?style=flat-square) ![MAVLink](https://img.shields.io/badge/MAVLink-Telemetry-8B5CF6?style=flat-square) ![DDS](https://img.shields.io/badge/DDS-Cyclone_%2F_FastDDS-008080?style=flat-square) |
| **Languages & Tooling** | ![C++](https://img.shields.io/badge/C%2B%2B-17_%2F_20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square&logo=cmake&logoColor=white) |
| **Perception & Edge AI** | ![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA-Jetson_Orin_%2F_Xavier-76B900?style=flat-square&logo=nvidia&logoColor=white) ![TensorRT](https://img.shields.io/badge/TensorRT-Inference-76B900?style=flat-square&logo=nvidia&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-Perception-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-v8_Detection-00FFFF?style=flat-square&logoColor=black) ![PCL](https://img.shields.io/badge/PCL-Point_Clouds-22314E?style=flat-square) |
| **Backend & Distributed** | ![NestJS](https://img.shields.io/badge/NestJS-Backend-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-LTS-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-Cache_%2F_Queue-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Systems & Infra** | ![Linux](https://img.shields.io/badge/Linux-PREEMPT__RT-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy-009639?style=flat-square&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/Git-CI_%2F_CD-F05032?style=flat-square&logo=git&logoColor=white) |
| **Frontend & UI** | ![Next.js](https://img.shields.io/badge/Next.js-App_Router-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-18%2B-61DAFB?style=flat-square&logo=react&logoColor=black) ![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |

---

### 🚀 Highlighted Systems & Engineering Work

#### 1. UAV Autonomy & Flight Mission Architecture (Savaşan İHA / Varyans)
*Mission-critical autonomy stack for fixed-wing / multirotor UAVs navigating competitive combat & observation scenarios.*
- **Autonomy & Control Loops**: Built end-to-end mission managers and state machines handling target acquisition, track lock-on, and autonomous flight maneuvers interfaced with Pixhawk/PX4 over MAVLink.
- **Computer Vision & Tracking**: Real-time onboard detection and tracking pipelines using YOLO and OpenCV, optimized for edge execution with tight latency bounds.
- **Simulation-First Validation**: Comprehensive SIL/HIL testing across Gazebo Harmonic and ROS 2 middleware before flight execution.
- **Ground Station Tooling**: Developed [`VaryansGC`](https://github.com/huzarh/VaryansGC), a cross-platform ground control station customized for mission oversight, telemetry inspection, and manual override.
- **Repositories**: [`varyans`](https://github.com/huzarh/varyans) · [`varyans_workflow`](https://github.com/huzarh/varyans_workflow) · [`VaryansGC`](https://github.com/huzarh/VaryansGC) · [`Teknofest-SIHA-Goruntu-Isleme-Gorev-Yazilimi`](https://github.com/huzarh/Teknofest-SIHA-Goruntu-Isleme-Gorev-Yazilimi)

#### 2. FarmerAI Platform (🏆 1st Place — TEKNOFEST)
*End-to-end digital agriculture ecosystem uniting farmers, buyers, and administrators in a single operational platform.*
- **Backend Architecture**: Modular REST API with NestJS featuring JWT authentication, Role-Based Access Control (RBAC), request validation, Swagger documentation, and automated testing (Jest/Supertest).
- **Data & Caching**: PostgreSQL persistence layer managed through Prisma ORM with automated migrations, backed by Redis for caching and session management.
- **Mobile Experience**: Cross-platform mobile client built with React Native and Expo, incorporating Redux Toolkit state management and offline-first data synchronization.
- **Automation Support**: Automated image text processing and document OCR workflows.
- **Repositories**: [`FarmerAIMobileApp`](https://github.com/huzarh/FarmerAIMobileApp) · [`RestApiFarmerai`](https://github.com/huzarh/RestApiFarmerai) · [`FarmerAIOCR`](https://github.com/huzarh/FarmerAIOCR)

#### 3. Robotics Tooling & Spatial Perception
*Experimental perception and autonomous navigation packages for mobile robotics.*
- **Extrinsic Sensor Calibration**: [`tetra_calibration`](https://github.com/huzarh/tetra_calibration) — LiDAR-to-camera spatial calibration pipeline for aligned point cloud and optical stream projection.
- **Autonomous Navigation & Simulation**: [`Tetra_Otonom`](https://github.com/huzarh/Tetra_Otonom) — ROS Noetic / Gazebo simulation exercises implementing obstacle avoidance algorithms and LiDAR-based spatial reasoning.

#### 4. High-Performance Financial Dashboard (`trading-viewer`)
*Interactive multi-panel market analysis interface.*
- **Architecture**: Next.js App Router, TypeScript, and Tailwind CSS.
- **Performance**: High-frequency chart controls, validated input parameters, and modular UI components engineered for minimal re-renders.
- **Repository**: [`trading-viewer`](https://github.com/huzarh/trading-viewer)

---

### 🧠 Engineering Principles ("How I Build")

```
   [ Deterministic ]       [ Simulation-First ]       [ Hardware-Conscious ]
          │                         │                          │
          ▼                         ▼                          ▼
 Loops hold period         Validating QoS & jitter      Bounded memory & zero-copy
 under worst-case load     before burning flight hours   buffers on Jetson / ARM
```

- **Deterministic over Clever**: Predictable loop frequencies, bounded memory allocations in real-time execution paths, and explicit fail-safe state machines over unpredictable abstraction layers.
- **Simulation-First, Hardware-Proven**: Validating sensor degradation, DDS latency, and mission branches in simulation (Gazebo Harmonic / SITL) to ensure zero surprises during deployment.
- **Hardware-Conscious Development**: Respecting thermal, memory bandwidth, and power constraints when deploying GPU-accelerated neural networks (TensorRT FP16) to NVIDIA Jetson edge compute.
- **Modular & Observable Architecture**: Decoupled subsystems with explicit API contracts, health watchdogs, and structured telemetry logging.

---

### 📊 System Vitals

| Dimension | Specification |
| :--- | :--- |
| **Field** | Autonomous Robotics · Real-Time Systems · Distributed Backends |
| **Target Platforms** | NVIDIA Jetson (Orin NX / Xavier), x86_64 RT-Linux (PREEMPT_RT), ARM Cortex |
| **Middleware** | ROS 2 (Humble / Jazzy), CycloneDDS, PX4 uORB / MAVLink |
| **Foundation** | Mechatronics Engineering (Sakarya UAS) |
| **Languages (Spoken)** | Kazakh, Turkish, Mongolian, English |

---

<div align="center">

**Building software that holds its promises to real-world hardware.**  
Feel free to connect or explore my work:

[![Portfolio](https://img.shields.io/badge/Portfolio-huzarh.github.io-C8953C?style=for-the-badge&logo=googlechrome&logoColor=white)](https://huzarh.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-uzeyiraskyer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/uzeyiraskyer)
[![Email](https://img.shields.io/badge/Email-huzarh44%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:huzarh44@gmail.com)

</div>
