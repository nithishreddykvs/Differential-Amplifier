# 📡 Differential Amplifier Design for Audio Codec Subsystem (Hearing Aid)

This repository contains the design and implementation details for a **Differential Amplifier** intended for use in the **audio codec subsystem of a hearing aid**. The amplifier was designed using **Cadence Virtuoso** in the **180nm CMOS technology node**.

---

## 📌 Project Overview

The primary objective of this project was to design, simulate, and layout a differential amplifier that offers:
- A gain of **approximately 26 dB**
- Low power consumption
- Suitability for audio processing applications in hearing aids

---

## 🛠️ Design Environment

- **EDA Tool:** Cadence Virtuoso Analog Design Environment (ADE L)
- **Technology:** GPDK 180nm CMOS
- **Platform:** Red Hat Linux

---

## 📑 Design Process Summary

### 1️⃣ Schematic Design  
- Designed a differential amplifier using NMOS and PMOS transistors.
- Included biasing circuits, current mirrors, and a tail current source.
- Validated functionality using Virtuoso's **Check and Save**.

### 2️⃣ Pre-Layout Simulations  
- Performed **Transient** and **AC analyses**.
- Verified amplifier gain of approximately **26 dB**.

### 3️⃣ Layout Design  
- Created a manual layout emphasizing symmetry in the differential pair.
- Routed connections with appropriate metal layers and vias.
- Addressed common DRC issues like spacing violations and metal widths.

### 4️⃣ Current Status  
- Layout is near-complete, with ongoing **DRC debugging**.
- **LVS checks** and **Post-Layout simulations** will follow.

---

## 📊 Simulation Results

- **AC Gain:** ≈ 26 dB  
- **Transient and Frequency Response:** See images in `Pre-Layout_Simulations/`

---

## 📌 Note

This repository currently includes:
- **Schematic screenshots**
- **Pre-layout simulation outputs**
- **Layout screenshots**

Further updates (Post-Layout simulations, LVS results) will be added in upcoming commits.

---

## 📬 Contact

**Designed by:** Nithish Reddy KVS  
📧 Email: nithishreddy.k.v.s@gmail.com  

---

## 📃 License

This project is for academic and personal learning purposes.
