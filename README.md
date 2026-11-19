# Evkphone-UAV

## Asynchronous UAV Detection and Tracking with Event Cameras on mobile phone

<p align="center">
  <img src="fig1.png" width="1000" />
</p>

### 📖 Overview

**Event cameras** offer asynchronous sensing advantages that provide effective modality information for counter-UAV tasks. However, deploying these algorithms presents two main challenges:

* **Edge-computing limitations:** Existing algorithms are constrained by the limited computing power of edge devices.
* **Processing complexity:** The unique asynchronous processing requirements result in a scarcity of counter-UAV detection devices designed specifically for mobile phones.

#### 💡 Our Solution
To solve the **"last mile"** problem of counter-UAV operations and enhance the flexibility and portability of drone detection, we have developed this software that can **directly link to event cameras** on mobile devices.

<p align="center">
  <img src="val.gif" width="500" />
</p>

### 🚀 ASUMOT Optimization

* **Model Quantization**: Quantized the multi-task validation network.
* **Batch Processing**: Implemented batch processing for validation.

**Results:**
* ✅ **Improved Inference Speed**: Achieves real-time asynchronous tracking on mobile phones.
* ⚖️ **Trade-off**: Quantization slightly reduces UAV recognition capability but significantly improves overall operational efficiency.

## Cite
The mobile phone software follows [EVKphone] ([code](https://github.com/Jia-Bao/EVKphone)).

The asynchronous Anti-UAV methodology follows [ASUMOT](https://arxiv.org/abs/2607.11303) ([code](https://github.com/Jia-Bao/ASUMOT)).
