# ADAS & Autonomous Vehicle Validation Portfolio
**Senior AV Simulation & Integration Systems Engineer**  
📍 Irvine, USA | ✉️ urvi8@vt.edu | 🔗 [LinkedIn Profile](https://linkedin.com/in/urvi-desai) | 🖥️ [GitHub Platform](https://github.com/urvi8)

---

##  Executive Summary
Highly analytical **Automated Driving Systems Engineer** with 8 years of foundational experience bridging traditional OEM vehicle architecture with modern cloud-scale software pipelines. Proven track record across Tier-1 and Top OEM environments developing robust, Python-driven automation frameworks, engineering complex synthetic scenarios, and performing deep-dive forensic diagnostics on high-dimensional sensor fusion logs. Specialized in transforming manual, safety-critical testing loops into massive, hands-on regression architectures.

---

##  Core Technology & Tooling Directory

| Category | Competencies & Ecosystem |
| :--- | :--- |
| **Core Languages** | Python, C++, Linux/Bash, SQL |
| **Robotics & Infrastructure** | ROS/ROS2, Git, Docker, Devops (CI/CD Automated Pipelines) |
| **Simulation Suites** | Virtual Test Drive (VTD), RoadRunner, OpenDRIVE, CarSim, IPG CarMaker |
| **Validation Architecture** | Software-in-the-Loop (SIL), Hardware-in-the-Loop (HIL), Test Automation Engineering |
| **Automotive Diagnostics** | CAN/LIN, Automotive Ethernet, Vector CANoe, Vehicle Spy, ETAS INCA, dSPACE, ControlDesk |

---

##  Featured System Architecture Case Studies

###  Case Study 1: Synthetic Scenario Engineering & Automated Multi-Variant Regression Infrastructure
> **Core Focus:** Virtual Asset Generation, Closed-Loop Data Scalability, and Hardware/Software Interface Co-Design

####  System Objective
Establish a high-fidelity virtual test ecosystem from absolute zero to validate edge-case performance for **Traffic Sign Recognition (TSR)** models and L2/L2+ active safety controllers across multiple physical hardware variants.

```text
[HD Geodetic Map Data] ➔ [RoadRunner Map Compilation] ➔ [OpenDRIVE Asset Networks]
                                                               │
                                                               ▼
[Custom Python Orchestration Engine] ➔ ➔ ➔ ➔ ➔ ➔ [VTD Deterministic Simulation]
                                                               │
                                                               ▼
[Asynchronous Camera/CAN Stream Logs] ➔ ➔ [Multi-Variant VCU Bench Hardware]
```

####  Technical Execution
* **Virtual Environment Compilations:** Processed raw geospatial/HD map data through **RoadRunner** to compile highly precise, standards-compliant **OpenDRIVE** road asset networks.
* **Deterministic Simulation Design:** Engineered 100+ high-fidelity safety-critical operational domains within **Virtual Test Drive (VTD)**, meticulously modeling environmental occlusions, dynamic lux shifts, and international traffic asset variations.
* **Automation Engineering:** Formulated a custom **Python orchestration pipeline** that automated environmental data injection, dynamic target vehicle scripting, and synchronous log capture, effectively shifting a legacy manual hardware lab into a fully continuous execution framework.

####  Quantifiable Engineering Impact
* **Infrastructure Scale:** Modeled and cataloged a library of **100+ unique driving environments** targeting complex, non-deterministic perception edge-cases.
* **Testing Bandwidth:** Successfully transitioned the verification loop from 100% manual operations into an automated system processing **100+ parallel regression scenarios**.
* **Defect Isolation:** Discovered, reproduced, and systematically resolved **20+ safety-critical software regressions** prior to any prototype track vehicle integration.

---

###  Case Study 2: Asynchronous Perception Stack Integration & Forensic Log Diagnostics
> **Core Focus:** Sensor Fusion Layer Optimization, Data Pipeline Profiling, and Closed-Loop Defect Engineering

####  System Objective
Integrate, profile, and stabilize a multi-modal perception and tracking layer—including camera-based object detection, deep lane-tracking architectures, and radar-to-camera tracking algorithms—onto an embedded production computing platform.

```text
[Field-Captured Failures / Anomalies] ➔ [Asynchronous ROS Bags / Raw CAN Extraction]
                                                               │
                                                               ▼
                                              [Pipeline State & Clock Auditing]
                                                               │
                                                               ▼
                                              [C++ Algorithmic Patch & Unit Testing]
                                                               │
                                                               ▼
[SIL Simulation Execution Suite (VTD)] ➔ ➔ ➔ ➔ [On-Track System Validation Deployment]
```

####  Technical Execution
* **Codebase Stabilization:** Architected performance-critical patches and refactored high-throughput messaging interfaces in **C++**, ensuring strict adherence to low-latency processing budgets inside localized **CI/CD pipelines**.
* **Forensic Anomaly Diagnostics:** Conducted down-to-the-frame log analysis of system failures. Traced network traffic anomalies by isolating structural drops inside raw **ROS bags**, packetized **CAN buses**, and micro-architectural tracking threads.
* **Simulation-First Defect Verification:** Built high-fidelity replay fixtures utilizing **Software-in-the-Loop (SIL)** pipelines to re-inject real-world vehicle tracking errors back into virtual models, ensuring rigorous proof-of-fix verification prior to physical validation testing.

####  Quantifiable Engineering Impact
* **System Precision:** Successfully root-caused highly intermittent sensor fusion dropout patterns, transforming raw spatial anomalies into deterministic **C++ algorithmic fixes**.
* **Stack Reliability:** Developed and merged exhaustive multi-module unit test suites to guard core perception states, resulting in a dramatic reduction in downstream multi-sensor integration crashes.
* **Validation Rigor:** Monitored object boundary precision, deep latency profiles, and spatial synchronization alignment variations across millions of simulated operational steps.

---
<sub>*Note: Out of respect for non-disclosure agreements (NDAs) and proprietary security boundaries, all system metrics, structural architectures, and quantitative values are scaled, anonymized, and framed around core engineering methodologies.*</sub>
