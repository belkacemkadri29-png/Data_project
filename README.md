# Power-System-Datasets-Under-Advanced-Cyber-Attacks-scenarios. 

This repository contains power system datasets under advanced attack scenarios, with the aim of supporting the research community in developing and evaluating new data-driven models to enhance the security of power system infrastructures.

The dataset is designed for both supervised and unsupervised learning approaches. It includes unpoisoned scenarios, where the data represent normal system behavior without any sample perturbation or label manipulation. Specifically, the dataset provides unpoisoned labeled data for training supervised models and unpoisoned unlabeled data for training unsupervised models.

In addition to the unpoisoned data, a poisoned version of the dataset is provided. In this setting, the data contain samples generated using Projected Gradient Descent (PGD) attacks, where the nominal system behavior is deliberately perturbed in both supervised and unsupervised scenarios. The objective of this poisoned dataset is to enhance the robustness of machine learning and deep learning models to advanced adversarial threats. In particular, we consider one of the most advanced attack strategies, namely Projected Gradient Descent (PGD), as introduced by Madry et al.

Finally, the dataset includes balanced labeled test sets that are used to evaluate the performance of the trained models under different attack scenarios. The datasets cover four power system infrastructures of increasing scale: a small 4-bus system, medium-scale 14-bus and 39-bus systems, and a large-scale 57-bus system.

Given the difficulty of obtaining stealthy False Data Injection Attack (FDIA) scenarios targeting power system infrastructures for the evaluation of machine learning and deep learning models, this repository includes stealthy attack vector data. For further information and technical details regarding the methodology used to generate these data and the simulated attack scenarios, readers are invited to refer to our paper entitled :"Physics-Aware Hybrid Estimator for Dynamic Power System Dataset Generation and Cyber Attack Simulation
"  DOI:https://10.1109/ACCESS.2025.3599318

To support our work, please cite the paper. For any questions, do not hesitate to contact the authors at: belkacemkadri29@gmail.com.
