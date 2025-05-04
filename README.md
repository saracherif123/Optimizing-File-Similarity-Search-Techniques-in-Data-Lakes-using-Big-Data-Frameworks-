# Optimizing-File-Similarity-Search-Techniques-in-Data-Lakes-using-Big-Data-Frameworks


This project explores scalable techniques for detecting similar or duplicate datasets in large-scale data lakes using **Big Data frameworks** like Apache Spark. It reimplements the **DS-Prox early pruning algorithm** and evaluates two machine learning models—**Random Forest** and **Multilayer Perceptron (MLP)**—to optimize schema matching and deduplication.

---

## Related Publication

 **Conference Paper:**  
**Title:** *Optimizing File Similarity Search Techniques in Data Lakes using Parallel Processing and Big Data Frameworks*  
**Authors:** Sara Sherif Daoud Saad, Ayman Alserafi  
**Conference:** IEEE Smart Cities Symposium, October 2023  
🔗 [Read on IEEE Xplore](https://ieeexplore.ieee.org/document/10526156)  
🔗 [Read on ResearchGate](https://www.researchgate.net/publication/379734769)

---


## Techniques Used

- **Big Data Framework:** Apache Spark (PySpark)
- **Machine Learning Models:**
  - Random Forest
  - Multilayer Perceptron (Neural Network)
- **Similarity Properties:**
  - `Rel`: Relatedness between datasets (same topic)
  - `Dup`: Duplication of datasets (same schema/content)

---

## Experiment Goals

- Reimplement and scale the DS-Prox algorithm using Spark
- Use statistical meta-features to reduce computation cost
- Compare ML models in classifying dataset similarity
- Apply undersampling for class balance during training

---

## Citation

If you use this work, please cite:

```bibtex
@inproceedings{sherif2023similarity,
  title={Optimizing File Similarity Search Techniques in Data Lakes using Parallel Processing and Big Data Frameworks},
  author={Sara Sherif Daoud Saad and Ayman Alserafi},
  booktitle={IEEE Smart Cities Symposium},
  year={2023},
  doi={10.1109/SmartCities4.056956.2023.10526156}
}


