# João Maerbal

### Electrical Engineering @ UFTM · Embedded Systems · ROS 2 · Computer Vision

Electrical Engineering student at **UFTM** (Uberaba, Brazil) and head of the programming division at **GAIA Robotics**. My work is on the software side of robotic systems: microcontroller firmware, ROS 2 integration and vision models, built on a foundation of C and data structures.

[LinkedIn](https://www.linkedin.com/in/joaomaerbal/) · [Email](mailto:jmaerbal@gmail.com)

## Technical Focus

- **Embedded / ROS 2 integration:** ESP32 firmware (C++, PlatformIO) exposed as ROS 2 nodes through micro-ROS and the micro-ROS Agent over serial transport.
- **ROS 2 Jazzy:** nodes, topics, services, parameters and actions on Ubuntu 24.04; simulation with TurtleBot3 and `ros2_control` demos.
- **Computer vision:** object detection with YOLO and image processing with OpenCV, including dataset and training documentation.
- **Algorithms in C:** tree structures, sorting, pointers and manual memory management, measured with controlled experiments.
- **Studying next:** cloud platforms (Google Cloud, AWS) for data and model workflows.

## Projects

| Project | Description | Stack |
|---|---|---|
| [esp32-microros-sensor](https://github.com/joaomaerbalbarros/esp32-microros-sensor) | ESP32 node `sensor_esp32` samples an LDR module every 100 ms, drives a local LED and publishes `/sensor/valor` (`Int32`) and `/sensor/alerta` (`Bool`) to ROS 2 through the micro-ROS Agent. Used as the hands-on example for the sensor-integration class of the GAIA ROS 2 course. | C++, rclc, micro-ROS, ROS 2 Jazzy, PlatformIO, Docker |
| [osu-pp-simulator-bst-avl](https://github.com/joaomaerbalbarros/osu-pp-simulator-bst-avl) | BST vs AVL on real data: 200 osu! top plays keyed by beatmap ID, with insert, search, delete and traversals, plus a pp simulator that ranks a new play and applies the position weight (0.95<sup>n−1</sup>). With sorted insertion the BST degenerates to height 200 (100.5 comparisons per search on average), while the AVL stays at height 8 (6.76). Includes report and [video](https://www.youtube.com/watch?v=bza74MyH1AQ). | C, Python (osu! API data collection) |
| [sorting-algorithms-c](https://github.com/joaomaerbalbarros/sorting-algorithms-c) | Average-time benchmark of five sorting algorithms implemented from scratch (Quick, Merge, Insertion, Selection, Bubble) on random arrays of 10k–90k elements, 5 runs each, with output verification, CSV export and a generated SVG plot. At n = 90,000, QuickSort averaged 11.3 ms against 23.9 s for BubbleSort. Includes [video](https://www.youtube.com/watch?v=3vfH9RDy3Oo). | C |
| [osu-map-recommender](https://github.com/joaomaerbalbarros/osu-map-recommender) **(in progress)** | Recommends osu! beatmaps by play style. Parses `.osu` files (including real slider curves), extracts 31 rhythm, slider, spacing and jump features, builds a statistical profile per style from reference maps and counter-examples, and ranks candidates by weighted distance. CLI plus a local web UI, with rate-limited on-demand downloads and SQLite storage. Next: style sliders, learning from feedback and a tosu overlay. | Python (standard library), SQLite, JavaScript |
| [otim-nivis](https://github.com/joaomaerbalbarros/otim-nivis) **(planning)** | AI rival for [Mito Ignis](https://twitch.tv/mito_ignis), my original VTuber: it watches a Minecraft session and reacts with short sarcastic voice lines. Planned as a five-stage pipeline (log event reader → director with queue, priority and cooldown → LLM → TTS → OBS avatar driven by the audio RMS envelope), with tracked requirements, architecture decision records and a latency target under 1.5 s. Original character design included. | Python, LLM API, TTS, OBS |
| [imersao-dev-01](https://github.com/joaomaerbalbarros/imersao-dev-01) | Static search page over a JSON dataset, with filtering by name, description and year and relevance ordering. [Live demo](https://joaomaerbalbarros.github.io/imersao-dev-01/). | HTML, CSS, JavaScript |

## GAIA Robotics — Programming Division

Member of the programming division since **July 2025**. Head of the division since **April 2026**, and currently also working in the electronics division.

- **Vision:** contributed to a YOLO + OpenCV model for pressure gauge inspection, and documented the code, datasets and training procedures.
- **ROS 2 course:** co-teach the team's internal ROS 2 Jazzy course, from workspaces and `colcon` to parameters, actions and micro-ROS sensor integration.
- **Coordination:** organize the division's work and keep its code and procedures documented so other members can continue it.

GAIA projects are team efforts; these items describe my contributions, not sole authorship.

## Tools

C · C++ · Python · ROS 2 · micro-ROS · PlatformIO · ESP32 · OpenCV · YOLO · Docker · Git · Linux
