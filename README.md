<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ai-cain&style=flat-square&color=444444" alt="Profile Views"/>
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Gerald+Cainicela;Embedded+Systems+Engineer;Computer+Vision;AI+%26+Edge+Computing" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://ai-cain.github.io/portfolio/#home">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=safari&logoColor=white" />
  </a>&nbsp;
  <a href="https://www.linkedin.com/in/gerald-cainicela/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>&nbsp;
  <a href="https://github.com/ai-cain">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
<table>
<tr>
<td width="30%" valign="top">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ai-cain&theme=tokyonight&utcOffset=-5" />
</td>
<td width="60%" valign="top">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ai-cain&theme=tokyonight" />
</td>
</tr>
</table>
</p>

---

### About Me

<table>
<tr>
<td width="50%" valign="top">

```python
from typing import Dict, List

class Engineer:
    def __init__(self):
        self.name = "Gerald Cainicela"
        self.role = "Embedded & CV Engineer"
        self.location = "Lima, Peru 🇵🇪"
        self.focus = [
            "Real-Time Computer Vision",
            "Edge AI & Inference Optimization",
            "Industrial Embedded Systems",
            "Protocol Engineering (CAN/J1939)"
        ]

    def get_stack(self) -> Dict[str, List[str]]:
        return {
            "vision":   ["CUDA", "TensorRT", "YOLO", "DeepStream"],
            "embedded": ["ESP32", "FreeRTOS", "STM32", "ARM Cortex"],
            "edge":     ["Jetson Orin", "Docker", "ONNX", "OpenVINO"],
            "plc":      ["CODESYS", "IEC 61131-3", "Modbus", "OPC UA"],
        }

    async def deploy(self, target: str) -> str:
        return f"✓ Optimized & deployed to {target}"
```

</td>
<td width="50%" valign="top">

```cpp
#include <memory>
#include <vector>
#include <string>
#include <map>

class Engineer {
    const std::string name_{"Gerald Cainicela"};
    const std::vector<std::string> focus_{
        "Real-Time CV", "Edge AI",
        "Industrial IoT", "Protocol Eng."
    };

public:
    auto getStack() const noexcept {
        return std::map<std::string,
            std::vector<std::string>>{
            {"vision",   {"C++20", "CUDA", "TensorRT"}},
            {"embedded", {"ESP-IDF", "FreeRTOS", "ARM"}},
            {"edge",     {"Jetson", "Docker", "ONNX"}},
            {"comms",    {"CAN", "J1939", "Modbus"}}
        };
    }

    template<typename T>
    [[nodiscard]] auto optimize(T&& pipeline) {
        return std::make_shared<std::decay_t<T>>(
            std::forward<T>(pipeline));
    }
};
```

</td>
</tr>
</table>

Specialized in **real-time computer vision** and **industrial embedded systems**. I build high-performance pipelines for edge inference, industrial bus communication, and robust production deployments. My work sits at the intersection of hardware and AI — optimizing every frame and every byte.

---

### Featured Projects

<details>
<summary><strong>🔬 Computer Vision & Inference</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [industrial-visual-inspection-engine](https://github.com/ai-cain/industrial-visual-inspection-engine) | Computer vision engine for industrial inspection and anomaly detection in production environments |
| [real-time-vision-decision-system](https://github.com/ai-cain/real-time-vision-decision-system) | Real-time decision system built on top of CV pipelines for industrial and edge AI applications |
| [event-driven-vision-processing-engine](https://github.com/ai-cain/event-driven-vision-processing-engine) | Event-driven CV engine for transforming video streams into structured decision events |
| [low-latency-video-stream-orchestrator](https://github.com/ai-cain/low-latency-video-stream-orchestrator) | Low-latency video orchestration for distributing, processing, and routing real-time streams |
| [qt-face-auth](https://github.com/ai-cain/qt-face-auth) | Face authentication system built with Qt/C++ |
| [image-to-fourier-epicycle-pipeline](https://github.com/ai-cain/image-to-fourier-epicycle-pipeline) | Image to Fourier epicycle rendering pipeline in C++ |

</details>

<details>
<summary><strong>⚙️ Edge AI & System Orchestration</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [edge-ai-system-orchestrator](https://github.com/ai-cain/edge-ai-system-orchestrator) | Orchestrator for coordinating distributed edge AI modules: vision, sensors, and comms |
| [multi-physics-simulation-and-control-system](https://github.com/ai-cain/multi-physics-simulation-and-control-system) | Simulation and control system integrating mechanical, electrical, and computational models |
| [formal-specification-to-system-implementation](https://github.com/ai-cain/formal-specification-to-system-implementation) | Transforming formal logic specifications into executable engineering systems |
| [symbolic-to-numeric-computation-pipeline](https://github.com/ai-cain/symbolic-to-numeric-computation-pipeline) | Symbolic-to-numeric computation pipeline |

</details>

<details>
<summary><strong>🧪 Labs & Experimentation</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [cpp-lab](https://github.com/ai-cain/cpp-lab) | C++ experiments and patterns |
| [python-lab](https://github.com/ai-cain/python-lab) | Python courses and experiments |
| [embedded-lab](https://github.com/ai-cain/embedded-lab) | Embedded systems experiments (ESP32, STM32) |
| [qt-qml-lab](https://github.com/ai-cain/qt-qml-lab) | Qt/QML UI experiments |
| [lean-math](https://github.com/ai-cain/lean-math) | Formal mathematics in Lean |

</details>

<details>
<summary><strong>🏭 Industrial Automation & PLC</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [iec-61131-3-insights](https://github.com/ai-cain/iec-61131-3-insights) | Guides, best practices, and resources for the IEC 61131-3 standard |

</details>

<details>
<summary><strong>🎓 Academic & MATLAB</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [matlab-legume-classifier](https://github.com/ai-cain/matlab-legume-classifier) | Legume classification system via image processing in MATLAB |
| [matlab-image-processing-app-fx](https://github.com/ai-cain/matlab-image-processing-app-fx) | Interactive image transformation tool built with MATLAB App Designer |
| [matlab-candy-cap-detection](https://github.com/ai-cain/matlab-candy-cap-detection) | Cap and candy detection, classification, and matching in MATLAB |
| [matlab-audio-equalizer](https://github.com/ai-cain/matlab-audio-equalizer) | Audio equalizer built with MATLAB App Designer |
| [special-functions-calculus](https://github.com/ai-cain/special-functions-calculus) | Notes on special functions with integrals, limits, and series |
| [segmented-linear-fit-encoder](https://github.com/ai-cain/segmented-linear-fit-encoder) | Segmented linear fit encoder |

</details>

<details>
<summary><strong>📄 Publishing & Templates</strong></summary>
<br>

| Repository | Description |
|:--|:--|
| [cv-latex-template](https://github.com/ai-cain/cv-latex-template) | LaTeX CV template — free to use and customize |
| [tex-content-publisher](https://github.com/ai-cain/tex-content-publisher) | TeX content publishing tools |
| [lnx-science-education](https://github.com/ai-cain/lnx-science-education) | LaTeX & Python content for educational pages |
| [portfolio](https://github.com/ai-cain/portfolio) | Personal portfolio website |

</details>

---

<details>
<summary><strong>🛠️ Tech Stack</strong></summary>
<br>

**Computer Vision & AI**  
`C++14/17/20` `CUDA` `cuDNN` `TensorRT` `ONNX Runtime` `OpenCV` `OpenCV C++` `YOLO` `YOLOv8` `DeepStream` `Qt6` `OpenGL` `libtorch` `Eigen` `Manim`

**Edge AI & Deployment**  
`Jetson Orin` `Jetson Nano` `JetPack` `L4T` `Docker` `NVIDIA Runtime` `TensorRT` `DeepStream` `ONNX` `OpenVINO`

**Embedded & IoT**  
`C` `C++` `ESP32` `ESP-IDF` `FreeRTOS` `MicroPython` `Arduino` `STM32` `ARM Cortex` `Raspberry Pi` `LoRa (SX127x/SX126x)` `MQTT` `Modbus RTU` `CAN` `J1939` `RS485` `RS232` `OTA` `Bootloader`

**Industrial Automation & PLC**  
`CODESYS` `IEC 61131-3` `Ladder Logic` `Structured Text` `Function Block Diagram` `Modbus TCP/RTU` `OPC UA` `SCADA`

**Protocols & Hardware Interfaces**  
`I2C` `SPI` `UART` `PWM` `ADC` `DMA` `BLE` `WiFi` `ESP-NOW` `NVS` `WebSocket` `HTTP` `TCP/UDP` `Ethernet` `USB` `Profibus` `Profinet`

**ML/DL Frameworks**  
`PyTorch` `libtorch` `TensorFlow` `TensorFlow Lite` `ONNX` `Keras` `OpenCV DNN` `scikit-learn` `NumPy` `Pandas` `Plotly` `Matplotlib`

**DevOps, Tools & Languages**  
`Docker` `docker-compose` `Kubernetes` `CI/CD` `GitHub Actions` `GitLab CI` `Linux` `Ubuntu` `Git` `CMake` `Makefile` `Bash` `GStreamer` `FFmpeg` `GDB` `Valgrind` `Perf` `NVIDIA Nsight` `MATLAB` `LaTeX`

**Databases**  
`PostgreSQL` `MySQL` `SQLite` `SQL Server`

**CAD & Design**  
`AutoCAD` `SolidWorks` `EasyEDA`

</details>

---

### 📊 GitHub Stats

<p align="center">
<table>
<tr>
<td width="48%" valign="top">
  <img width="100%" src="https://github-readme-streak-stats-eight.vercel.app/?user=ai-cain&theme=tokyonight&hide_border=true" />
  <br>
  <img width="100%" src="https://github-profile-trophy-eight.vercel.app/?username=ai-cain&theme=tokyonight&no-frame=true&row=1&column=3&margin-w=10&margin-h=10&title=Commits,MultiLanguage,Repositories" />
</td>
<td width="48%" valign="top">
  <img width="90%" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=ai-cain&layout=compact&theme=tokyonight&hide_border=true&langs_count=12" />
</td>
</tr>
</table>
</p>

---

### ✍️ Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</p>

---

<p align="center">
  <sub>Lima, Peru · 2026</sub>
</p>
