# Ryan Carson | AI Research Portfolio

I’m an independent AI researcher focused on model behavior, memory, and representation geometry. I use mathematics and signal processing to ask what a model retains, how its internal state changes, and where its behavior breaks down. I’m also interested in how prompts and training incentives shape a model’s stated preferences. I served as a sergeant in the U.S. Marine Corps, where I learned to pay attention to details and check assumptions against what I could observe.

## Research prototypes

### Dendritron Recurrent Engram

A 2,048-dimensional recurrent reasoning prototype that looks up frozen bigram and trigram representations, falls back to dictionary senses, and combines six procedural skill operators with two DeepLoop blocks reused across visits. The September 2026 full-bank check completed six loops on one held-out prompt from each skill family. At the last visit, all six prompts routed every tested position to `forward_chain`. Full-bank runs require separately stored model-derived assets, and natural-language readout remains open.

[Repository](https://github.com/Carson1391/Dendritron-recurrent-engram) · [Validation and current limitations](https://github.com/Carson1391/Dendritron-recurrent-engram/blob/main/CURRENT_HANDOFF.md)

### Spectral Adversarial Patches

Fourier analysis of YOLOv3 feature maps, followed by controlled patch-shape and texture sweeps across four YOLO versions. In the documented comparisons, some frequencies that suppressed detections on YOLOv3 produced false positives on newer versions. Re-running the analyses requires local model weights and test images.

[Repository](https://github.com/Carson1391/spectral-adversarial-patches) · [Experiment report](https://github.com/Carson1391/spectral-adversarial-patches/blob/main/MASTER_FINDINGS.md)

### GENEO YOLOv3 Embedding Inversion

A GENEO-based decoder that reconstructs approximate images from YOLOv3 detection-head features. The four COCO test images averaged 0.481 SSIM and 15.0 dB PSNR. The repository includes the code and saved comparisons. Re-running reconstruction requires the separately stored decoder checkpoint.

[Repository and example reconstructions](https://github.com/Carson1391/Geneo-yolo-inversion) · [Per-image metrics](https://github.com/Carson1391/Geneo-yolo-inversion/blob/main/metrics.csv)

## Applied tools

### VoxFlow

On-device dictation with a Windows hotkey app and an Android keyboard. Both use sherpa-onnx for streaming speech recognition and share an editable vocabulary for technical terms. Windows also supports optional local transcript cleanup through Ollama.

[Source and setup](https://github.com/Carson1391/VoxFlow)

### ExposureWatch

A Kotlin Android app that establishes a local baseline for nearby Wi-Fi and Bluetooth Low Energy signals. It uses signal fingerprints and observation history to flag patterns such as a device recurring across locations. The app shows the observations behind each heuristic flag.

[Repository](https://github.com/Carson1391/ExposureWatch) · [Scoring logic](https://github.com/Carson1391/ExposureWatch/blob/main/app/src/main/java/com/exposurewatch/app/engine/ScoringEngine.kt)

## Exploratory plots

[Selected plots](./Visuals1.png) · [Extended plot collection](./Visuals2.png)
