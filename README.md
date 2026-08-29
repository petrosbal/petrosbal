# Hey, I'm Petros

MSc student in Artificial Intelligence and Data Analytics.

My work has focused on containers and Kubernetes, specifically container runtimes, benchmarking, resource accounting, and the general question of what a workload actually costs to execute. My BSc thesis was a benchmarking framework built around that exact question.

I write mostly Python, Go and Java at the moment, with C, Prolog and TypeScript behind them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0088B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/petros-baloglou/)
[![Email](https://img.shields.io/badge/Email-EE1123?style=for-the-badge&logo=gmail&logoColor=white)](mailto:petrosbaloglou@gmail.com)

---

### Projects

**[Krater](https://github.com/petrosbal/krater)** - `Python` `C` `Docker` `k3s` `WASM`
Automated Kubernetes benchmarking framework comparing WebAssembly and native Linux environments across C optimization levels, with direct resource monitoring via cgroup v2 and configuration via YAML.

> *This repo was for my BSc thesis, graded 10/10.*

**[NN](https://github.com/petrosbal/neural-networks-coursework) / [ML](https://github.com/petrosbal/machine-learning-coursework)** - `Python` `Keras` `scikit-learn` `SHAP`
- An RNN for time-series energy disaggregation (NILM)
- a DNN vs CNN comparison on image classification with transfer learning and significance testing
- an 8-model classification pipeline for bankruptcy prediction with Bayesian hyper-opt and class imbalance handling
- a 4-model regression study on diabetes progression with SHAP explainability

> *The four projects above were part of a team effort, for two relevant UoM courses.*

**[Caveo](https://github.com/petrosbal/caveo)** - `Go` `Chi` `Docker` `GitHub Actions`
Stateless Argon2id service that takes password hashing off application servers. Released as `ghcr.io/petrosbal/caveo`. Self-describing hashes, bounded concurrency with load shedding, distroless nonroot image, and a crypto core validated against the Argon2 reference implementation's own test vectors.

> *Started this project inspired by UoM's Cryptography course. The main idea was getting to know what a microservice needs to be production-grade.*

**[Raffy](https://github.com/petrosbal/raffy)** - `Java 21` `Spring Boot 4` `PostgreSQL` `React 19` `TypeScript`
Full-stack reading tracker that derives analytics based on the user's reading habits. Pace, momentum, streaks, genre fingerprint and predicted finish dates are all computed from raw session rows at request time. The schema is built around a user's own copy of a book rather than the book itself, which keeps user context implicit through the entire session layer. Books are added by searching the Google Books API, so that metadata comes pre-filled, rather than typed by hand.

> *The interesting problem here was finding out what belongs in the DB and what should be derived on request.*
