# Indoor Scan-to-BIM Review

This repository collects and organizes resources related to indoor Scan-to-BIM (Building Information Modeling), including academic papers, datasets, benchmark tools, and relevant project links. It aims to support researchers and practitioners in understanding, comparing, and developing Scan-to-BIM methods for complex indoor environments.

Contents include:
1. Curated list of key papers on indoor Scan-to-BIM techniques
2. Publicly available datasets and their usage notes
3. Benchmark results and evaluation tools
4. Related open-source projects and useful links

Feel free to contribute by submitting issues or pull requests to keep this resource up-to-date.

## Related Bechmark Datasets

- SLABIM [[Paper]](http://doi.org/10.48550/arXiv.2502.16856) [[Data Download]](https://github.com/HKUST-Aerial-Robotics/SLABIM.git)
- ISPRS Indoor Modelling Dataset [[Paper]](http://doi.org/10.5194/isprs-archives-XLIII-B5-2020-207-2020) [[Data Download]](https://dpv.uvigo.es/index.php/s/edzBCDDGkHjSWGC)
- MiMAP [[Paper]](http://doi.org/10.5194/isprs-annals-V-5-2020-117-2020) [[Data Download]](https://dpv.uvigo.es/index.php/s/edzBCDDGkHjSWGC)
- S3DIS [[Paper]](http://doi.org/10.1109/CVPR.2016.170) [[Data Download]](https://redivis.com/datasets/9q3m-9w5pa1a2h/files)
- CRASLAB [[Paper]](http://doi.org/10.3390/data8060101) [[Data Download]](https://doi.org/10.5281/zenodo.7948116)
- ScanNet [[Paper]](http://doi.org/10.1109/CVPR.2017.261) [[Data Download]](https://github.com/ScanNet/ScanNet)
- FloorNet [[Paper]](http://doi.org/10.1007/978-3-030-01231-1_13) [[Data Download]](https://art-programmer.github.io/floornet.html)

## Related Review Articles

- [Autonomous Mobile Scanning Systems for the Digitization of Buildings: A Review (Adan2019, Remote Sensing)](http://doi.org/10.3390/rs11030306) This paper critically reviews autonomous scanning systems for 3D building modeling, analyzing key challenges such as data redundancy, occlusion, and autonomy, while comparing representative systems and highlighting future research directions.
- [A Review of Techniques for 3D Reconstruction of Indoor Environments (Kang2020, ISPRS International Journal of Geo-Information)](http://doi.org/10.3390/ijgi9050330) This paper reviews state-of-the-art techniques for 3D indoor environment reconstruction, covering datasets, geometric/semantic/topological methods, key challenges, and future directions including deep learning-based multi-task approaches and indoor–outdoor integration.
- [Linking Points With Labels in 3D: A Review of Point Cloud Semantic Segmentation (Xie2020, IEEE Geoscience and Remote Sensing Magazine)](http://doi.org/10.1109/MGRS.2019.2937630) Ripe with possibilities offered by deep-learning techniques and useful in applications related to remote sensing, computer vision, and robotics, 3D point cloud semantic segmentation (PCSS) and point cloud segmentation (PCS) are attracting increasing interest. This article summarizes available data sets and relevant studies on recent developments in PCSS and PCS.
- [Procedural Point Cloud Modelling in Scan-to-BIM and Scan-vs-BIM Applications: A Review (Abreu2023, ISPRS International Journal of Geo-Information)](http://doi.org/10.3390/ijgi12070260) This paper reviews recent point cloud processing techniques in AEC applications, highlighting shared workflows, key challenges like occlusion and data planning gaps, and emphasizing the need for better benchmarking and deep learning integration in Scan-to-BIM and Scan-vs-BIM.
- [Indoor Positioning Systems of Mobile Robots: A Review (Huang2023, Robotics)](http://doi.org/10.3390/robotics12020047) This paper reviews 147 studies from 2019 to 2021 on indoor localization for mobile robots, compares 12 mainstream positioning methods, and analyzes common patterns and trends in recent research.
- [Technologies for digital twin applications in construction (Tuhaise2023, Automation in Construction)](http://doi.org/10.1016/j.autcon.2023.104931) This paper presents a systematic review to identify key technologies enabling digital twins in construction, highlighting research gaps and future directions in data transmission, interoperability, integration, and visualization.
- [Digital technologies in architecture, engineering, and construction (Brozovsky2024, Automation in Construction)](http://doi.org/10.1016/j.autcon.2023.105212) This paper presents a quantitative scoping review of 3950 studies to map digital technology adoption in the AEC sector, revealing BIM's dominance, emerging trends like IoT and 3D printing, geographic research hotspots, and the need for better education and industry collaboration.
- [Comprehensive systematic review of information fusion methods in smart cities and urban environments (Fadhel2024, Information Fusion)](http://doi.org/10.1016/j.inffus.2024.102317) This paper conducts a comprehensive literature review on information fusion in smart cities, highlighting the role of machine learning and deep learning, key challenges, and ethical considerations, while identifying research directions to support intelligent urban development.
- [3D LiDAR SLAM: A survey (Zhang2024, Photogrammetric Record)](http://doi.org/10.1111/phor.12497) This paper presents a comprehensive review of 3D LiDAR SLAM, addressing its key challenges, algorithmic advances, datasets, and evaluation metrics, while highlighting emerging trends such as multi-sensor fusion, event-based, and quantum SLAM to guide future research.
- [A Review of Sensing Technologies for Indoor Autonomous Mobile Robots (Liu2024, Sensors)](http://doi.org/10.3390/s24041222) This paper reviews sensing technologies for indoor autonomous mobile robots, comparing single-sensor and multi-sensor approaches, introducing key algorithms, and discussing future trends and challenges in real-world applications.
- [Mobile robot localization: Current challenges and future prospective (Ullah2024, Computer Science Review)](http://doi.org/10.1016/j.cosrev.2024.100651) This paper comprehensively reviews mobile robot localization (MRL) technologies within the context of the Intelligent Internet of Things (IIoT), covering intelligent architectures, localization methods, security concerns, and challenges in achieving robust indoor and outdoor navigation.
- [Deep Learning on 3D Semantic Segmentation: A Detailed Review (Betsas2025, Remote Sensing)](http://doi.org/10.3390/rs17020298) This paper proposes a standardized taxonomy for 3D semantic segmentation (3DSS) deep learning methods, reviews over 400 approaches and datasets.

## Articles Related to Scan-to-BIM "Devices"

Early research in indoor Scan-to-BIM focus on wearable platforms:

1.Helmet

<img src="helmet.png" alt="Devices-Helmet" width="100"/>

- [WHU-Helmet: A Helmet-Based Multisensor SLAM Dataset for the Evaluation of Real-Time 3-D Mapping in Large-Scale GNSS-Denied Environments (Li2023, IEEE Transactions on Geoscience and Remote Sensing)](http://doi.org/10.1109/TGRS.2023.3275307)
- [EVALUATION OF A COMPACT HELMET-BASED LASER SCANNING SYSTEM FOR ABOVEGROUND AND UNDERGROUND 3D MAPPING (Li2022, 2022 24th ISPRS Congress)](http://doi.org/10.5194/isprs-archives-XLIII-B2-2022-215-2022)
- [Map building using helmet-mounted LiDAR for micro-mobility (Yoshida2023, Artificial Life and Robotics)](http://doi.org/10.1007/s10015-022-00848-6)

2.Backpack

<img src="backpack.png" alt="Devices-Backpack" width="100"/>

- [Backpack LiDAR-Based SLAM With Multiple Ground Constraints for Multistory Indoor Mapping (Zhou2023, IEEE Transactions on Geoscience and Remote Sensing)](http://doi.org/10.1109/TGRS.2023.3332916)
- [KINECT BACKPACK FOR RAPID MOBILE INDOOR MAPPING (Bleier2022, 2022 24th ISPRS Congress)](http://doi.org/10.5194/isprs-annals-V-1-2022-121-2022)
- [Semantic line framework-based indoor building modeling using backpacked laser scanning point cloud (Wang2018, ISPRS Journal of Photogrammetry and Remote Sensing)](http://doi.org/10.1016/j.isprsjprs.2018.03.025)

More recent studies have incorporated handheld platforms with different lightweight scan sensors:

3.Handheld

<img src="handheld.png" alt="Devices-Handheld" width="100"/>

- [Santiago urban dataset SUD: Combination of Handheld and Mobile Laser Scanning point clouds (Gonzalez-Collazo2024, Expert Systems with Applications)](http://doi.org/10.1016/j.eswa.2023.121842)
- [Use of Kinect Azure for BIM reconstruction: Establishment of an acquisition protocol, segmentation and 3D modeling (ElHaouss2022, 7th International Workshop on LowCost 3D - Sensors, Algorithms, Applications)](http://doi.org/10.5194/isprs-archives-XLVIII-2-W1-2022-87-2022)
- [Indoor 3D reconstruction from point clouds for optimal routing in complex buildings to support disaster management (Nikoohemat2020, Automation in Construction)](http://doi.org/10.1016/j.autcon.2020.103109)

As robotic platforms have emerged, wheeled scanning systems start to be used for autonomous data collection in larger or more challenging environments:

4.Wheeled Robots

<img src="wheeled.png" alt="Devices-Wheeled Robots" width="100"/>

- [A Novel Approach for As-Built BIM Updating Using Inertial Measurement Unit and Mobile Laser Scanner (Yang2024, Remote Sensing)](http://doi.org/10.3390/rs16152743)
- [Indoor mapping using low-cost MLS point clouds and architectural skeleton constraints (Luo2023, Automation in Construction)](http://doi.org/10.1016/j.autcon.2023.104837)
- [BIM generation from 3D point clouds by combining 3D deep learning and improved morphological approach (Tang2022, Automation in Construction)](http://doi.org/10.1016/j.autcon.2022.104422)

Moreover, quadruped robots integrated scan sensor have expanded the capabilities of Scan-to-BIM, especially for scenes with uneven terrains that demand high mobility and adaptability:

5.Quadruped Robots

<img src="dog.png" alt="Devices-Quadruped Robots" width="100"/>

- [Automated reality capture for indoor inspection using BIM and a multi-sensor quadruped robot (Chen2024, Automation in Construction)](http://doi.org/10.1016/j.autcon.2024.105930)
- [Semantic enrichment of BIM with IndoorGML for quadruped robot navigation and automated 3D scanning (Zhai2024, Automation in Construction)](http://doi.org/10.1016/j.autcon.2024.105605)
- [A Hybrid-Dimensional Laser SLAM Framework for Indoor Quadruped Inspection Robots (Cheng2024, IEEE Sensors Journal)](http://doi.org/10.1109/JSEN.2024.3382336)

## Cross-Disciplinary Collaboration in Scan-to-BIM Research

The Scan-to-BIM process has transcended its origins in civil engineering and architecture, now capturing significant attention from a diverse range of fields including geomatics, computer science, and artificial intelligence. This convergence has given rise to a host of interdisciplinary research streams, such as GeoBIM, which integrates geospatial data with BIM contexts, and AI-aided BIM, which leverages machine learning for automated object recognition and semantic enrichment. Despite this fertile ground for innovation, the intersection of these disciplines presents considerable challenges.

- [Urban GeoBIM Construction by Integrating Semantic LiDAR Point Clouds With as-Designed BIM Models (Shao2024, IEEE Transactions on Geoscience and Remote Sensing)](http://doi.org/10.1109/TGRS.2024.3358370)
