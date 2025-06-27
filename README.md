# **NVNT's Joy-Con 2 Mouse Info Database & Repository**

The purpose of this is for dumping and logging the hardware info (PID, VID etc) of the Nintendo Switch 2 Joy-Con 2, as well as documenting the mouse sensor inside of it. 

---

## 📚 Table of Contents
- **Introduction**
  - [Goals](#goals)
  - [Status](#status)

---

## How is this possible?

Utilizing a Nordic nRF52840-based Bluetooth sniffer to capture and analyze connection packets transmitted by the Nintendo Switch 2 Joy-Con 2 controllers to the host device. This process includes identifying hardware-level details such as Product ID (PID), Vendor ID (VID), and other relevant descriptors.

For documentation purposes, this repo will also catalog as much detailed sensor information as possible such as LOD, Polling Rate, etc.

A long-term goal is to develop a custom driver that enables the Joy-Con 2 to function as a native mouse input device on Windows, complete with proper initialization sequences and motion reporting.

---

## Goals

- 🔲 Log Joy-Con 2 Mouse Sensor Information (Model, LOD, DPI, etc)
- 🔲 Dump PID, VID & Other Manufacturing Info
- 🔲 Dump Handshake / Connection Information (from Nordic 52840 Sniffer)
- 🔲 Create Driver to use Joy-Con 2 as a mouse on Windows

---

## Status

Work in progress. Currently, evaluating the Sensor Lift Off Distance (LOD) has commenced. 

---
