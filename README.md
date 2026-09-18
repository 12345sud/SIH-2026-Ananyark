# AI-Enabled Wearable System for Early Knee Osteoarthritis Screening

## Smart India Hackathon 2026

**Team Name:** Ananyark  
**Problem Statement ID:** 26004  
**Problem Statement:** AI-Assisted Early Detection System for Osteoarthritis (OA) Risk Markers in North Eastern Region (NER)  
**Theme:** Assistive Healthcare and Intelligent Screening  
**PS Category:** Hardware

---

## 📌 Overview

Osteoarthritis (OA) is a common musculoskeletal condition that can progressively affect mobility and quality of life. Early identification of risk markers can help individuals seek appropriate medical evaluation before the condition becomes more severe.

This project proposes an **AI-enabled wearable system for early knee osteoarthritis screening** using gait and biomechanical parameters collected through wearable sensors.

The system combines:

- Wearable motion sensing
- Foot pressure measurement
- Signal processing
- Gait feature extraction
- Machine learning
- Edge-based analysis

The objective is to provide a **portable, non-invasive and low-cost preliminary screening solution**, particularly useful for communities where access to specialized healthcare may be limited.

> **Note:** The proposed system is intended for screening and risk assessment and is not a replacement for clinical diagnosis.

---

## 🎯 Objectives

- Detect gait-related markers associated with potential OA risk.
- Collect relevant lower-limb movement and pressure information.
- Extract meaningful gait features from sensor data.
- Apply machine learning models for risk classification.
- Develop a portable and non-invasive wearable system.
- Enable preliminary screening in low-connectivity environments.
- Support faster referral of individuals who may require further clinical evaluation.

---

## 🦿 Proposed Wearable System

The proposed wearable integrates multiple sensors around the lower limb and foot.

### Hardware Components

- ESP32-S3
- MPU6050 IMU
- FSR402 Force Sensitive Resistors
- Li-ion Battery
- Battery Holder
- Charging Module
- Shoe Insole
- Jumper Wires

The system uses motion and pressure information to capture gait characteristics relevant to knee movement and loading patterns.

---

## 🔬 Technical Approach

The proposed machine learning pipeline consists of:

```text
Gait Data
    ↓
Feature Extraction
    ↓
Feature Selection
    ↓
Standardization
    ↓
Machine Learning Model
    ↓
OA Risk Screening