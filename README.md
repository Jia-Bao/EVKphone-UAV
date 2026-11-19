# Evkphone-UAV

## Asynchronous UAV Detection and Tracking with Event Cameras on mobile phone

<p align="center">
  <img src="fig1.png" width="1000" />
</p>

### Event cameras offer asynchronous sensing advantages that provide effective modality information for counter-UAV tasks. While counter-UAV algorithms based on event cameras are constantly emerging, they are limited by edge-device computing power. The special asynchronous processing requirements also mean that there are currently few counter-UAV detection devices designed directly for mobile phones. To solve the "last mile" problem of counter-UAV and improve the flexibility and portability of drone detection, we developed this drone detection software that can be directly linked to event cameras.

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

The asynchronous Ant-UAV methodology follows [ASUMOT](https://arxiv.org/abs/2607.11303) ([code](https://github.com/Jia-Bao/ASUMOT)).
