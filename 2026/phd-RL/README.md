# Introduction to Reinforcement Learning

*PhD Course in Industrial Engineering*

**Simone Silvetti** (simone.silvetti@gmail.com)

---

This repository contains all the material for a PhD course on **Reinforcement Learning (RL)**.

RL addresses problems where a **decision-maker interacts repeatedly with a dynamic, uncertain system** and must learn — through experience — a strategy that maximizes performance over time: no labelled dataset, no explicit model of the system, only the outcome of decisions as a learning signal. The course follows a deliberate progression of problems, each adding exactly one new dimension of difficulty, from the simplest bandit with no state up to modern Deep RL with continuous actions and parametric policies (ε-greedy/UCB bandits, Value Iteration, Q-learning/SARSA, DQN, and Policy Gradient/actor-critic).

## Material

The material is organized in two parts:

- **Slides** — [`2024_Phd_4hurs_RL_full.pdf`](2024_Phd_4hurs_RL_full.pdf): the lecture slides for the course.
- **Notebook** — [`RL_course.ipynb`](RL_course.ipynb): a self-contained Colab notebook with the theory, the problems, and runnable code. Open it directly in the browser with the badge below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonesilvetti/teaching/blob/main/2026/phd-RL/RL_course.ipynb)

> **Per gli studenti — salvate la vostra copia.** Cliccando sul badge il notebook si apre in una sessione Colab temporanea: potete eseguire ed editare le celle, ma le modifiche **non vengono salvate** e si perdono chiudendo la scheda. Prima di iniziare a lavorarci fate **File → Salva una copia in Drive** (*File → Save a copy in Drive*): otterrete un duplicato personale sul vostro Google Drive su cui fare liberamente le vostre prove, senza toccare l'originale.

## References

- **[SB]** Sutton, R. S., and Barto, A. G. (2018). *Reinforcement Learning: An Introduction*, 2nd edition. MIT Press. [Free online](http://incompleteideas.net/book/the-book-2nd.html). The primary reference for this course (Chapters 1–8).
- **[Sz]** Szepesvári, Cs. (2010). *Algorithms for Reinforcement Learning*. Morgan & Claypool. [Free online](https://sites.ualberta.ca/~szepesva/rl_book.html). A compact, mathematically rigorous companion.
- **[SP]** OpenAI (2018). *Spinning Up in Deep RL*. [Online](https://spinningup.openai.com). The reference for practical Deep RL implementation.
