# space-situational-awareness-ML

**Differentiable Propagators and ML-Based Conjunction Assessment Screening**

This project develops machine learning solutions for **Space Situational Awareness (SSA)**, specifically targeting **ML-based conjunction assessment**. It aligns with the broader objective of creating AI tools for autonomous space safety.

Our most relevant work involves building a **conjunction assessment screening model** using **Differentiable Propagators** and **Machine Learning**. The goal is to more efficiently triage potential conjunction alerts—a task that will become increasingly challenging with the growing density of LEO objects.

### Key Components

- **Differentiable Propagation with GPU Acceleration**  
  I use a differentiable version of the SGP4 propagator (`dsgp4`) ( Their page at [https://github.com/esa/dSGP4](https://github.com/esa/dSGP4) ) implemented in PyTorch, enabling simultaneous orbital trajectory propagation and native integration with ML-based corrections.

- **Machine Learning-Based Conjunction Screening**  
  The problem is framed as a classification task, helping reduce the list of candidate conjunctions to those most deserving of computationally expensive follow-up. This is roughly modelled after the approach in [*Artificial Intelligence for All vs. All Conjunction Screening.* ](https://oa.upm.es/67167/1/EStevenson_ECSD8_2021_AI_for_all_vs_all_conjunction_screening.pdf) .

### Highlights

This project demonstrates practical experience in:

- Orbital mechanics and satellite propagation  
- ML modeling for rare event classification  


---

## References

Stevenson, Emma, et al. *Artificial Intelligence for All vs. All Conjunction Screening.* Proceedings of the AAS/AIAA Astrodynamics Specialist Conference, 2021.

Acciarini, Giacomo, Atılım Güneş Baydin, and Dario Izzo. "Closing the gap between SGP4 and high-precision propagation via differentiable programming." Acta astronautica 226 (2025): 694-701. [https://doi.org/10.1016/j.actaastro.2024.10.063](https://doi.org/10.1016/j.actaastro.2024.10.063)
