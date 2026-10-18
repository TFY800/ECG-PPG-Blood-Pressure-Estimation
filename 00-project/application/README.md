---
name: TAOFUYUAN
neptun: GF9EDC
---
# Project Application

**Topic:** Blood Pressure Estimation Using ECG and PPG Signals

**Supervisor:** Dr. Ádám Schiffer

**Name:** TAOFUYUAN

**NEPTUN code:** GF9EDC

## 1. Why I Am Interested

I am interested in this project because I want to learn how signals from the human body can be used to build a computer model. I would like to understand how ECG and PPG signals might help estimate blood pressure.

## 2. My Understanding of the Project

I have started learning about ECG, PPG, and Pulse Arrival Time (PAT).

As I understand it, when the heart beats, it pumps blood into the arteries and creates a pulse wave. We can find an R peak in the ECG signal and the beginning of the corresponding pulse wave in the PPG signal. The time difference between these two points is called PAT.

Higher blood pressure can be associated with faster pulse wave travel, so PAT may become shorter. However, other factors also affect PAT, so it cannot directly tell us the exact blood pressure.

## 3. My Initial Plan

If existing datasets are allowed, I would like to start with ECG and PPG recordings that also include reference blood pressure measurements.

First, I want to learn how to read and plot the signals in Python. Then, I would like to detect ECG R peaks and PPG pulse onsets, calculate PAT, and study its relationship with blood pressure.

Once I understand these steps, I would like to try a simple blood pressure estimation model and compare its estimates with the reference measurements. The details will depend on the available data and my supervisor's guidance.

## 4. Questions

- Can I use existing ECG and PPG datasets, or do I need to collect signals using sensors?
- What is the expected scope of the undergraduate thesis?

I am still at the initial learning stage and have a lot to learn about signal processing. This repository currently contains application text and research notes. No experiments or models have been implemented yet.
