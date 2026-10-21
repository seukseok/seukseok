## Hi, I'm Seungseok Lee (이승석)

Electronic Engineering student at Myongji University, focused on **embedded systems and firmware**.  
I work across hardware and firmware: co-designing 2-layer PCBs (KiCad/EasyEDA), soldering and wiring, MCU firmware (STM32/ESP32), and running a local LLM on a Jetson.

**Looking for:** a full-time embedded / firmware internship, **Dec 2026 – May 2027**.  
**Currently:** ride-testing higher regen current for downhill braking on my DIY dual-motor electric skateboard.

### Featured projects

| Project | What I did |
| --- | --- |
| **[HESTIA](https://github.com/MJU-HESTIA)** · [demo](https://www.youtube.com/watch?v=fuKamIi-SM0) | *Team lead.* Conversational AI home assistant for older adults living alone. Runs a quantized Llama 3 8B (Q4_K_M, via Ollama) locally on a Jetson Orin Nano 8GB for on-device Edge AI, moved from a GPT-4o cloud prototype. An ESP32 sends temperature, gas and light readings. I built IR control of home appliances such as the air conditioner (LG protocol) and fan (NEC) on the ESP32, and found a UART baud-rate mismatch. 4 awards. |
| **[Smart Desk Clock](https://github.com/smart-clock)** | ESP32 firmware: weather/stock API handling, a settings web server, and 115200-bps UART packets to the STM32. Revised the 2-layer main-board PCB over three orders. Course grade A+; Bronze Award, 2023 SEP Convergence Festival (team). |
| **[oh-in-pe-](https://github.com/seukseok/oh-in-pe-)** | STM32F767 audio workbench: WAV playback from SD through a VS1053b codec, codec-based volume/bass/treble control, a touch piano, and a 2048-point FFT spectrum of ADC input sampled at 25.6 kHz (timer interrupt), drawn on a TFT. Course team project; I did the firmware and integration. |
| **[micro-wake-word-gpu-starter](https://github.com/seukseok/micro-wake-word-gpu-starter)** | Dockerized NVIDIA GPU trainer with a web UI for custom ESPHome micro wake word models, plus a candidate "Hey Komi" model (quantized TFLite) awaiting on-device tests on an ESP32-S3. |
| **[jihwa (지화)](https://github.com/seukseok/jihwa)** | *Team project.* Offline AI art frame: a Raspberry Pi generates images with Stable Diffusion XL Turbo (OnnxStream) and shows them on a 7.3" color e-ink display on a schedule. I wrote the image-generation and e-ink display scripts and the install script, and integrated the vendor e-paper driver. |
| **[Companion Robot](https://github.com/MJU-Capstone-PetRobot)** | Battery monitoring with an ACS37800 I2C power monitor + ESP32 (laid out in KiCad, finalized in EasyEDA), touch and gas sensors, plus team work on speech recognition and LLM API integration; used ROS2 nodes and topics. Bronze Award, 2023 Probono ICT Mentoring Competition (team). |
| **DIY electric skateboard** *(personal, no repo)* | Dual-motor build I soldered and wired myself around a dual VESC controller (Flipsky Dual 75100). Caught and fixed a B-/B+ error in the wiring diagram, traced a no-spin fault to a wrong ESC-type setting on the remote, and restored current/voltage limits that the FOC detection wizard had reset to defaults. 3.88 km test ride so far. |
| **SCPC AI Challenge 2026** *(private repo)* | Built a Python harness (with the AI coding agent Codex) that scores each change and reverts regressions. Score went from 0.4436 to 0.8911, placing 34th on the round-1 Public leaderboard. |

Also: 2024 president of the [RATS](https://join.mju-rats.com) robotics club.

### Tech stack

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![VESC](https://img.shields.io/badge/VESC-333333?style=flat-square) ![Jetson](https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![ROS2](https://img.shields.io/badge/ROS2_(basic)-22314E?style=flat-square&logo=ros&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white) ![EasyEDA](https://img.shields.io/badge/EasyEDA-1765F6?style=flat-square&logo=easyeda&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Hands-on:** soldering · crimping · 3D printing  
**English:** reads technical documents well; actively improving spoken English

### Awards

- **HESTIA** (Team Lead)
  - Grand Prize, Campus Capstone Design Project Competition (Myongji Univ.), Dec 2024
  - Special Award, 11th National ICT Convergence Competition, Dec 2024
  - Encouragement Award, ChatGPT-based AI Practical Application Competition, Nov 2024
  - Grand Prize, Creative Software Program Competition, Oct 2024
- **Companion Robot**: Bronze Award, 2023 Probono ICT Mentoring Competition, Dec 2023 (team)
- **Smart Desk Clock**: Bronze Award, 2023 SEP Convergence Festival, Dec 2023 (team)

### Contact

[![Email](https://img.shields.io/badge/seungseok0109@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:seungseok0109@gmail.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-seukseok-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seukseok)
