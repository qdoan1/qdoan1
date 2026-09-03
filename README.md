# Quang Viet Doan

Statistics & Data Science + Mathematics (Computing) at UMass Amherst. I work on the part of ML that decides whether a number is real — leakage-safe splits, honest baselines, and the tests that keep them honest.

## Currently

- AI/ML Fellow at AI4ALL (May 2026 - present)
- Building CI/CD and pgvector retrieval for What-if, a multi-agent LLM simulation engine (Jun 2026 - present)

## Selected work

**[ASL Fingerspelling Recognition](https://github.com/kcosteen/DLQ---Deep-Learning-for-Quiet-Communication)** — a 29-class recognizer that turns live webcam fingerspelling into text and speech.
Python · PyTorch · EfficientNet-B0 · MediaPipe · OpenCV · pytest

> A random split reported 99.9% accuracy. I traced it to near-duplicate frames from the same
> continuous recordings, rebuilt 87,000 images into a deterministic frame-range split, and locked
> the corrected number — **97.8% accuracy, 0.978 macro-F1** on the leakage-safe split — behind
> 7 pytest leakage cases so it cannot silently regress.

**[Sleep Doctor](https://github.com/Poudel-Sanskriti/Sleep_Doctor)** — predicts sleep quality from lifestyle factors, deployed as a Streamlit app. Built with a 6-person team as my AI4ALL fellowship project.
Python · scikit-learn · pandas · Streamlit

> Lifted accuracy from a **44.5% majority-class baseline to 68%** on a 100,000-record synthetic
> health dataset. Permutation importance and 5-fold cross-validation identified stress
> (r = -0.64) as the dominant driver, overturning default importances that ranked step count first.

**What-if** — a multi-agent LLM simulation engine built by a small team. I own CI/CD and the pgvector retrieval layer. *(Private repo — happy to walk through the work.)*
Python · PostgreSQL/Neon · pgvector · Docker · Fly.io · GitHub Actions · Alembic

> Every merge is gated behind lint, type, test, and secret-scan checks, with preview deploys of
> web and engine on each PR. The retrieval layer is a source-tracked embedding corpus on
> serverless Postgres, with reversibility-tested Alembic migrations.

## Skills

**Programming & Databases** — Python, SQL, R, Java, C++, MATLAB, PostgreSQL (pgvector), Neon

**ML & Data** — scikit-learn, PyTorch, pandas, NumPy, OpenCV, MediaPipe, Matplotlib, Seaborn, Jupyter Notebook, Tableau, Excel

**Cloud & DevOps** — Docker, GitHub Actions (CI/CD), pytest, Alembic, Fly.io, Vercel, Git/GitHub

## Education

**University of Massachusetts Amherst** — B.S. Statistics & Data Science and B.S. Mathematics (Computing), expected May 2028. GPA 4.00/4.00, Dean's List.

## Contact

[qdoan530@gmail.com](mailto:qdoan530@gmail.com) · [LinkedIn](https://www.linkedin.com/in/quang-doan-957b68363/)
