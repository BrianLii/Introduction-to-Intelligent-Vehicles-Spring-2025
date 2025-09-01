# Comparative Survey of Leading Models in CARLA Simulator

The project surveys recent state-of-the-art autonomous driving models evaluated in the [CARLA](https://carla.org/) simulator, including:

- **ReasonNet** - temporal and global reasoning for rare events  
- **InterFuser** - interpretable multi-sensor fusion using CNNs and transformers  
- **TransFuser++** - simplified architecture addressing training biases  
- **TCP Framework** - hybrid of trajectory-based and control-based control  

The survey evaluates their performance on CARLA metrics (Driving Score, Route Completion, Infraction Penalty) and discusses limitations and potential improvements.

## 📄 Report

Full report: [Report.pdf](doc/Report.pdf)
## 📊 Key Findings

* **ReasonNet** achieves the highest Driving Score in CARLA but is computationally heavy.
* **InterFuser** excels at safety and interpretability through advanced sensor fusion.
* **TransFuser++** reduces training biases and complexity, but struggles with route completion.
* **TCP Framework** combines trajectory and control signals, offering balanced but less generalizable performance.

## 📚 Reference

* Shao et al., *ReasonNet: End-to-End Driving with Temporal and Global Reasoning*, CVPR 2023
* Shao et al., *Safety-Enhanced Autonomous Driving Using Interpretable Sensor Fusion Transformer*, CoRL 2023
* Jaeger et al., *Hidden Biases of End-to-End Driving Models*, ICCV 2023
* Wu et al., *Trajectory-Guided Control Prediction for End-to-End Autonomous Driving*, NeurIPS 2022
* [CARLA Leaderboard Evaluation Metrics](https://leaderboard.carla.org/#evaluation-and-metrics)

## 👥 Authors

National Taiwan University
* **Chang-Yen Li** (B09902054)
* **Yun-Fang Li** (B08502041)

## 📌 License

This project is released for academic and research purposes.
Please cite appropriately if you reference this work.