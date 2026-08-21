Edge AI and IoT Enabled Livestock Intrusion Detection and Automated Farm Protection

This repository contains the reproducibility materials, experimental artifacts, implementation files, and supporting evidence associated with the study:

**Edge AI and IoT Enabled Livestock Intrusion Detection and Automated Farm Protection Using YOLOv8s and MQTT-Enabled Event Notification**

The project presents an integrated cyber-physical system for real-time cattle intrusion detection and automated farm protection. The system combines YOLOv8s-based visual detection, Python-based event orchestration, MQTT communication, ESP32-based actuation, and automated notification services.

## Repository Contents

### `manuscript_materials`

Supporting materials associated with the manuscript, including selected figures, demonstrations, and experimental evidence that are not included directly in the main manuscript.

### `experiments`

Materials used for model training, evaluation, and experimental analysis.

This includes the YOLOv8s training and evaluation notebook and generated experimental results used to obtain the measurements reported in the manuscript.

### `circuitry`

Hardware and simulation materials associated with the ESP32-based intrusion response system.

The Wokwi project files are provided for reproduction and inspection of the MQTT-enabled embedded control workflow.


## Dataset

The cattle detection dataset used in this study was obtained from Roboflow Universe.

The dataset used in the experiments contains 3,176 images and 9,441 cattle instances, with one object class (`cow`).

The original dataset is not relicensed or claimed as authors' property by this repository. Researchers should obtain the dataset from its original source and comply with its applicable licensing terms.

## Reproducibility

The repository provides the principal materials required to inspect and reproduce the computational and system-level experiments reported in the study, including:

- YOLOv8s training and evaluation notebook
- Model evaluation results
- Experimental latency measurements
- MQTT communication evaluation
- ESP32/Wokwi implementation files
- Custom detection, communication, and notification code
- Supporting experimental and demonstration materials

The training notebook contains the experimental procedures and calculations used to obtain the reported model-performance and latency measurements.

## External Resources

Some components of the system rely on externally hosted or third-party resources, including the Roboflow dataset and cloud-based services used during development and evaluation.


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

The MIT License applies to the original source code, configuration files, notebooks, simulation files, and other materials created by the authors and included in this repository.

Third-party materials, including the Roboflow dataset and other externally hosted resources, remain subject to their respective licenses and terms of use and are not relicensed by this repository.

## Citation

If you use this repository or build upon the implementation, please cite the associated research paper:

> Oladepo, C.O., Abeeb, A.B., and Habeebullahi, O.A. (2026). *Edge AI and IoT Enabled Livestock Intrusion Detection and Automated Farm Protection Using YOLOv8s and MQTT-Enabled Event Notification.* [Journal Name / Under Review]

## Acknowledgement

This repository accompanies the research manuscript submitted to **Discover Computer Vision**.
