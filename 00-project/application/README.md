---
name: TAOFUYUAN
---
# Project Application

**Topic:** Blood Pressure Estimation Using ECG and PPG Signals

**Prospective Supervisor:** Dr. Ádám Schiffer

## 1. Why I Am Interested

I understand the basic idea of PAT, but I started wondering whether the same PAT value means the same blood pressure for different people.

I think factors such as age, sex, and height may affect the results. I would like to learn how to handle these differences when working with ECG and PPG data, and how to build a model that can estimate blood pressure more reliably.

I also wonder how heart rate and a person's physical condition might affect the relationship between PAT and blood pressure. I would like to understand why differences between people may occur, but I do not yet know which factors matter most or whether the data will include this information.

## 2. My Understanding of the Project

I have started learning about ECG, PPG, and Pulse Arrival Time (PAT).

As I understand it, when the heart beats, it pumps blood into the arteries and creates a pulse wave. ECG records the heart's electrical activity, and we can find its R peaks. PPG detects changes in local blood volume with each pulse, and we can find the beginning of the pulse. The time difference between an ECG R peak and the beginning of the corresponding PPG pulse is called PAT.

Higher blood pressure can be associated with faster pulse wave travel, so PAT may become shorter. However, other factors also affect PAT, so it cannot directly tell us the exact blood pressure.

## 3. My Initial Plan

If existing datasets are allowed, I would like to start with ECG and PPG recordings that also include reference blood pressure measurements.

1. Learn how to read and plot ECG and PPG signals in Python.
2. Learn how to detect ECG R peaks and the beginnings of PPG pulses.
3. Calculate PAT and look at its relationship with blood pressure.
4. Look at whether there are clear differences in this relationship between people.
5. Learn how to work with larger datasets, including noisy signals, missing data, signal timing, and data quality.
6. With suitable data and guidance from Dr. Schiffer, try a simple blood pressure estimation model.
7. Compare the estimates with the reference blood pressure measurements and look at errors for different groups of people, if the data allow it.

I see data processing as an important part of the project. I would like to learn how to check that ECG, PPG, and reference blood pressure measurements match in time, and how to split data for training and testing.

Factors such as age, sex, and height could be studied later, depending on the available data and what the experiments show. I do not yet know whether including them would improve the estimates.

This is only my initial idea. I would like to discuss the scope and the next steps with Dr. Schiffer before deciding on a final plan.

## 4. Questions

I would like to understand the project requirements better:

- Can I use existing ECG and PPG datasets, or do I need physical sensors?
- Does the available data include information such as age, sex, and height?
- What is the expected scope of this bachelor's thesis?
- What exactly is meant by vascular peak calculation in the original topic description?

I am still at the initial learning stage and have a lot to learn about signal processing. No experiments or models have been implemented yet.
