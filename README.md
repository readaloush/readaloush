## Hi — I'm Read

AI and embedded software engineer in Konya, Turkey. I train computer-vision and deep-learning models, check them honestly, get them running in the browser or on edge hardware, and build the firmware, PCB, wireless and cloud around them.

Day job: firmware and hardware for a commercial fire-safety product at İmax Elektronik.

Site → [readaloush.com](https://readaloush.com)

### Projects with live demos

Every demo runs the model inside the page; nothing you draw, upload or type leaves your device.

| Project | What it is | Result | Links |
| --- | --- | --- | --- |
| **Basira** بصيرة | Brain MRI tumor classification (4 classes) evaluated without the train/test leakage that inflates public benchmarks, plus a U-Net that outlines the tumor | 96% accuracy on a leak-free test; outline Dice 0.86 against radiologists' masks | [demo](https://readaloush.github.io/basira/) · [repo](https://github.com/readaloush/basira) |
| **Sanad** سند | Question answering over Saudi law in Arabic, citing the article it rests on: retriever fine-tuning and ALLaM-7B with QLoRA (in progress) | On questions people asked: dense retrieval 63% Recall@1 vs 40% for BM25 | [demo](https://readaloush.github.io/sanad/) · [repo](https://github.com/readaloush/sanad) |
| **Bahth** بحث | Photo search by text in Arabic, Turkish and English: multilingual CLIP fine-tuning, FastAPI service | Recall@1 for Arabic 24.8 → 46.5, Turkish 25.8 → 49.5 | [demo](https://readaloush.github.io/bahth/) · [repo](https://github.com/readaloush/bahth) |
| **Lawha** لوحة | Arabic licence plate recognition: YOLO11 detector + CRNN/CTC reader written in PyTorch | 92.3% of plates read fully correct end to end | [demo](https://readaloush.github.io/lawha/) · [repo](https://github.com/readaloush/lawha) |
| **Harf** حرف | Handwritten letter recognition for Arabic, Turkish and English with two small CNNs | 97.8% Arabic, 95.2% Latin on real handwriting | [demo](https://readaloush.github.io/harf/) · [repo](https://github.com/readaloush/harf) |

### Hardware and other work

| Project | What it is | Code |
| --- | --- | --- |
| **Smoke detector platform** | STM32 + FreeRTOS firmware, point-to-point LoRa, fuzzy-logic false-alarm filtering, AWS IoT Core backend, Flutter app, CV model for board serial-number recognition | closed source |
| **Automated waste sorting** | CNN on Raspberry Pi sorting five material streams in real time, ROS2 bridge to conveyor control | not public |
| **Foldable-wing UAV** | Multi-sensor air-quality payload, ML on telemetry to predict pollution patterns. Funded under TÜBİTAK 2209-A | not public |

### Currently into

- Medical imaging: leak-free evaluation, classification and segmentation on small clinical datasets
- Arabic NLP: retrieval and grounded question answering
- Edge AI: shrinking vision models until they run in a browser tab or on microcontroller-class hardware

### Stack

**AI / computer vision** — PyTorch · TensorFlow · Keras · OpenCV · CNNs · U-Net · YOLO · CLIP · transfer learning · segmentation · ONNX / onnxruntime-web · edge deployment

**NLP / LLM** — Hugging Face Transformers · sentence embeddings · retrieval (BM25, dense) · QLoRA fine-tuning · FastAPI · Docker

**Embedded** — C · C++ · STM32 · FreeRTOS · ESP32 · Raspberry Pi · UART / I2C / SPI · LoRa · Proteus

**Also** — Python · JavaScript · Dart · Flutter · ROS2 · AWS IoT Core · Siemens TIA Portal · Git · Kaggle

### Reach me

[readaloush.com](https://readaloush.com) · [LinkedIn](https://linkedin.com/in/readaloush) · dev@readaloush.com
