# 🤖 The Humanoid Robot Blueprint:
## Systems Integration Roadmap

**Project Humanoid Robot** is the central execution hub for the MatsRobot initiative. This architecture maps the transition from pages of technical theory into a functional, integrated humanoid system by bridging the "Missing Links" between isolated robotics modules.

---

<table width="100%">
  <!-- ROW 1: MISSION STATUS (Now at the top for mobile/desktop clarity) -->
  <tr>
    <td align="center" bgcolor="#f8f9fa">
      <div style="padding: 15px;">
        <h3>Mission Status</h3>
        <img width="450" alt="Gemini_Generated_Image_v86lvsv86lvsv86l" src="https://github.com/user-attachments/assets/b97be2ff-ea97-429b-aa82-4668e3df16dc" />
        <br><br>
        <img src="https://img.shields.io/badge/PHASE_1-COMPLETE-238636?style=for-the-badge" alt="Phase 1 Complete" /> 
        <img src="https://img.shields.io/badge/PHASE_2-CURRENT-d4a017?style=for-the-badge" alt="Phase 2 Current" /> 
        <img src="https://img.shields.io/badge/PHASE_3-FUTURE-cf222e?style=for-the-badge" alt="Phase 3 Future" />
        <p><small>Ref: Master Tech Specification Document</small></p>
      </div>
    </td>
  </tr>
  <!-- ROW 2: STRATEGIC EXECUTION -->
  <tr>
    <td align="left" valign="top">
      <h2>🚀 Strategic Execution</h2>
      <p>
        This hub connects high-level AI theory with ground-level hardware implementation. Every breakthrough—from <b>CAN Bus logic</b> to <b>micro-expressions</b>—is a component of a larger architectural puzzle.
      </p>
      <blockquote style="font-size: 0.85rem; line-height: 1.4; margin: 10px 0;">
        <b>Current Activity:</b> Integrating <b>Magnetic Encoders</b> to implement <b>proprioceptive feedback</b>. This allows the Brain to validate physical displacement against commanded movement for precise motor control.
        <p style="margin-top: 8px;">
          Integrating MT6701 and AS5600 encoders marks the shift to a <b>closed-loop system</b>. By coupling sensing magnets to motor shafts, the Brain receives real-time data to ensure physical movement matches digital intent.
        </p>
      </blockquote>
    </td>
  </tr>
</table>

---
---

## ⚡ Weekly Log

This section serves as the dynamic bridge between high-level strategy and technical execution.

*   **Active Task:** `Magnetic Encoders MT6701 and AS5600`
*   **Technical Challenge:** Engineering a reliable physical coupling between the DC motors and sensing magnets using a custom 3D-printed **Position Encoder Module**.
*   **Progress:** Successfully integrated dual encoders with distinct I2C addresses to provide real-time angular feedback to the CAN Bus node.

**Current Resources:**
* 🔗 <a href="https://github.com/MatsRobot/Digital-Nervous-System/tree/main/Experiments/Stage4-%20Adding%20Practical%20Nodes%20to%20CAN%20Bus/CAN_Bus_Arduino_Nano" target="_blank">Repository Page: CAN_Bus_Arduino_Nano</a>
* 📂 <a href="https://github.com/MatsRobot/Digital-Nervous-System/blob/main/Experiments/Stage4-%20Adding%20Practical%20Nodes%20to%20CAN%20Bus/CAN_Bus_Arduino_Nano/CAN_Bus_Nano_Encoders_Display_bb.jpg" target="_blank">Technical Schematic: CAN_Bus_Nano_Encoders_Display</a>
---

<img width="1380" height="752" alt="Robot_Workshop" src="https://github.com/user-attachments/assets/d61aee20-84b7-4f63-8b86-fdf65eaaaa7e" />

---

## 📋 Master Task Ledger

Detailed trajectory of the project based on the master technical documentation.

### 🧠 Theoretical & AI Foundations
| Status | Task | Page |
| :--- | :--- | :--- |
| 🟢 **COMPLETE** | Neural Network Basics | p.5 |
| 🟢 **COMPLETE** | Linear Algebra & Tensors | p.5 |
| 🟢 **COMPLETE** | Calculus & Integration | p.6 |
| 🟡 **CURRENT** | Algorithmic Modelling | p.6 |
| 🔴 **FUTURE** | Full AI Maths | p.6 |

### 💻 Dev Environment & AI Debugging
| Status | Task | Page |
| :--- | :--- | :--- |
| 🟢 **COMPLETE** | Hardware Awareness Logic | p.7 |
| 🟢 **COMPLETE** | Python Env & VS Code | p.9 |
| 🟢 **COMPLETE** | Python OOP (POOP) | p.11 |
| 🟡 **CURRENT** | OpenCV & NumPy Integration | p.11 |

### 📡 Processor & Sensor Communication
| Status | Task | Page |
| :--- | :--- | :--- |
| 🟢 **COMPLETE** | UART/I2C/SPI Protocols | p.31 |
| 🟢 **COMPLETE** | Open-Drain Architecture | p.33 |
| 🟡 **CURRENT** | Lidar Build Parameters | p.38 |
| 🟡 **CURRENT** | I2C Processor Handshaking | p.40 |

### 🏗️ Hardware Design & Physical Integration
| Status | Task | Page |
| :--- | :--- | :--- |
| 🟢 **COMPLETE** | Pico Base Unit UART | p.49 |
| 🟢 **COMPLETE** | Robot Eyes & Mouth Lights | p.77 |
| 🟡 **CURRENT** | MoveHead ESP32_CAM | p.87 |
| 🟡 **CURRENT** | Servo Position Feedback | p.96 |
| 🔴 **FUTURE** | Moving Waist Assembly | p.108 |
| 🔴 **FUTURE** | Stereo Vision & Encoders | p.124 |

---

<small>© 2026 MatsRobot | Licensed under the [MIT License](https://github.com/MatsRobot/matsrobot.github.io/blob/main/LICENSE)</small>
