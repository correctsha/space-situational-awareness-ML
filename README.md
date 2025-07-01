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

Check out the code on GitHub:  
👉 [https://github.com/correctsha/space-situational-awareness-ML](https://github.com/correctsha/space-situational-awareness-ML)

---

## References

Stevenson, Emma, et al. *Artificial Intelligence for All vs. All Conjunction Screening.* Proceedings of the AAS/AIAA Astrodynamics Specialist Conference, 2021.
