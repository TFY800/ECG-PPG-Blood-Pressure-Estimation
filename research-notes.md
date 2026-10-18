# Research Notes

These notes record my current understanding and questions. I will update them as I learn more.

## What I Understand

- ECG records the electrical activity of the heart. The R peak can be used as a timing reference.
- PPG records changes in light related to changes in blood volume at the measurement site. The beginning of a pulse is often called its onset or foot.
- When the heart pumps blood into the arteries, it creates a pulse wave.
- PAT is the time from an ECG R peak to the onset of the corresponding PPG pulse:

  `PAT = PPG pulse onset time - ECG R-peak time`

- The ECG and PPG recordings need to share a time reference so that this difference is meaningful.
- Higher blood pressure can be associated with faster pulse wave travel and shorter PAT, but this relationship is not fixed.
- PAT alone does not directly determine blood pressure.

## Questions I Still Have

- Which existing dataset would be suitable, and does it include synchronized ECG, PPG, and reference blood pressure measurements?
- How do I read the signal files and convert sample positions into time?
- How can I reliably detect R peaks and the start of PPG pulses, especially when the signals contain noise?
- How should I match each ECG R peak with its corresponding PPG pulse?
- How should PAT values be matched with the reference blood pressure measurements?
- What other factors affect PAT, and how much does its relationship with blood pressure vary between people?
- What is the pre-ejection period, how does it affect PAT, and how is PAT different from pulse transit time?
- What would be a suitable first model, and how should I evaluate it?

## First Practical Step

After discussing the dataset with Dr. Schiffer, I would like to load and plot a short recording in Python and inspect the ECG and PPG waveforms before trying automatic detection.

## Reading Reference

[Pulse arrival time as a surrogate of blood pressure (2021)](https://pubmed.ncbi.nlm.nih.gov/34815419/) explains the distinction between PAT and pulse transit time, and discusses limitations of using PAT to estimate blood pressure. This is a reference for further reading.
