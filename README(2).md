# Artificial Intelligence: Zero to 100

A free-first, sequential learning roadmap for progressing from absolute beginner to practical AI developer, machine-learning engineer, generative-AI engineer, or research-oriented learner.

This repository is a **curriculum, not just a link collection**. It explains what to learn, why it matters, which prerequisites come first, where to study, what to implement, and how to decide whether to move on.

**Last reviewed:** 2026-10-25  
**Primary programming language:** Python  
**Default strategy:** Learn concepts, implement small examples, evaluate results, document what you learned, then build a project.

> Resource availability, prices, API behavior, model licenses, and free compute limits change. Check the linked source before committing time or money. This directory does not promise unlimited free GPU access or that every course offers a free certificate.

## Table of Contents

- [What This Roadmap Covers](#what-this-roadmap-covers)
- [Who This Roadmap Is For](#who-this-roadmap-is-for)
- [How to Use This Repository](#how-to-use-this-repository)
- [Learning Rules](#learning-rules)
- [Prerequisite Map](#prerequisite-map)
- [Zero-to-100 Roadmap](#zero-to-100-roadmap)
  - [Stage 0: AI Orientation](#stage-0--orientation-and-understanding-artificial-intelligence)
  - [Stage 1: Developer Foundations](#stage-1--computer-and-developer-foundations)
  - [Stage 2: Python](#stage-2--programming-foundations-with-python)
  - [Stage 3: Algorithms](#stage-3--data-structures-algorithms-and-computational-thinking)
  - [Stage 4: Mathematics](#stage-4--mathematics-for-ai)
  - [Stage 5: Data Analysis](#stage-5--python-for-data-analysis-and-scientific-computing)
  - [Stage 6: Data Engineering](#stage-6--databases-data-engineering-and-data-preparation)
  - [Stage 7: Classical AI](#stage-7--classical-artificial-intelligence)
  - [Stage 8: Machine Learning](#stage-8--machine-learning-foundations)
  - [Stage 9: Advanced ML](#stage-9--intermediate-and-advanced-machine-learning)
  - [Stage 10: Deep Learning](#stage-10--deep-learning-foundations)
  - [Stage 11: Computer Vision](#stage-11--computer-vision)
  - [Stage 12: NLP](#stage-12--natural-language-processing)
  - [Stage 13: Transformers and LLMs](#stage-13--transformers-and-large-language-models)
  - [Stage 14: Generative AI](#stage-14--generative-ai-beyond-text)
  - [Stage 15: Prompt Engineering](#stage-15--prompt-engineering-and-context-engineering)
  - [Stage 16: AI Application Development](#stage-16--llm-apis-and-ai-application-development)
  - [Stage 17: Retrieval](#stage-17--embeddings-vector-search-and-information-retrieval)
  - [Stage 18: RAG](#stage-18--retrieval-augmented-generation-rag)
  - [Stage 19: Fine-Tuning](#stage-19--fine-tuning-and-custom-model-adaptation)
  - [Stage 20: AI Agents](#stage-20--ai-agents-and-tool-using-systems)
  - [Stage 21: Reinforcement Learning](#stage-21--reinforcement-learning)
  - [Stage 22: Multimodal AI](#stage-22--multimodal-ai)
  - [Stage 23: Deployment and MLOps](#stage-23--ai-deployment-and-mlops)
  - [Stage 24: Evaluation, Safety, and Security](#stage-24--ai-evaluation-reliability-safety-and-security)
  - [Stage 25: Research](#stage-25--ai-research-and-advanced-theory)
  - [Stage 26: Specializations](#stage-26--advanced-specializations)
  - [Stage 27: Portfolio and Capstones](#stage-27--portfolio-and-capstone-projects)
- [Subject-Wise Resource Index](#subject-wise-resource-index)
- [Expanded Free Resource Library — 40 Resources per Subject](#expanded-free-resource-library--40-resources-per-subject)
- [Resource Collections by Format](#resource-collections-by-format)
- [Practice and Assessment Framework](#practice-and-assessment-framework)
- [Example Learning Schedules](#example-learning-schedules)
- [Free-First Learning Strategy](#free-first-learning-strategy)
- [Datasets and Computing](#datasets-and-computing)
- [Glossary](#glossary)
- [Contribution Guidelines](#contribution-guidelines)
- [Verification Methodology](#verification-methodology)
- [Disclaimer](#disclaimer)

## What This Roadmap Covers

The learning sequence moves through:

1. Computing foundations and computational thinking.
2. Python and software development practices.
3. Mathematics, probability, statistics, and optimization.
4. Data analysis, databases, and data preparation.
5. Classical AI and search.
6. Classical and advanced machine learning.
7. Neural networks and deep learning.
8. Computer vision and natural language processing.
9. Transformers, large language models, and generative AI.
10. Prompt and context engineering.
11. Embeddings, information retrieval, and RAG.
12. Fine-tuning, AI agents, and multimodal applications.
13. Reinforcement learning.
14. Evaluation, security, deployment, and MLOps.
15. Research methods, specializations, and capstone projects.

Not every learner needs every branch. A software engineer building a document assistant can prioritize LLM applications, retrieval, evaluation, and deployment. A researcher should invest more deeply in mathematics, experimental design, and reading papers.

## Who This Roadmap Is For

- **Absolute beginners:** Follow the stages in order, starting at Stage 0.
- **Students:** Use the stages to structure coursework, practice, and portfolio projects.
- **Programmers entering AI:** Review Stages 0–3, then focus on math, data, ML, and deep learning.
- **Data analysts:** Emphasize statistics, data preparation, ML evaluation, and applied projects.
- **Software engineers:** Emphasize model integration, retrieval, agents, evaluation, and deployment after ML fundamentals.
- **Aspiring ML engineers:** Complete the core stages through deployment and monitoring.
- **Generative AI developers:** Learn ML foundations, transformers, prompting, APIs, retrieval, evaluation, and safe tool use.
- **Research-oriented learners:** Add rigorous mathematics, research papers, reproducibility, and a specialization after the core foundations.

## How to Use This Repository

1. Start at the earliest stage whose prerequisites you do not already satisfy.
2. Choose **one primary course or book per subject**. Do not attempt every resource simultaneously.
3. Use official documentation as a reference and use exercises to prove that you understand the material.
4. Keep a single repository of notes, experiments, datasets references, and projects.
5. Do not advance just because you watched a video. Advance when you can explain the ideas and implement the stage's project.
6. Revisit earlier material whenever an advanced topic exposes a gap.
7. Record the date, environment, dependencies, dataset source, license, and evaluation method for each project.

## Learning Rules

- **Code more than you watch.** For an introductory technical topic, aim to spend at least as much time practicing as consuming material.
- **Build baselines first.** A simple, evaluated baseline is more informative than a complicated model with no comparison.
- **Separate data.** Never use the final test set to repeatedly tune a model.
- **Measure performance.** Choose metrics that reflect the actual task and error costs.
- **Keep experiments reproducible.** Record random seeds where applicable, package versions, data provenance, and configuration.
- **Treat AI output as a draft.** Verify generated code, citations, mathematical claims, and security advice.
- **Respect licenses and privacy.** A public dataset or open-weight model is not automatically unrestricted for every use.

## Prerequisite Map

```text
Computer / terminal / Git
          |
          v
Python fundamentals ------> Testing, APIs, software engineering
          |
          v
Data structures + computational thinking
          |
          +--------------------+
          v                    v
Linear algebra + calculus   Probability + statistics
          |                    |
          +----------+---------+
                     v
             Data analysis + SQL
                     |
                     v
             Classical AI + ML
                     |
                     v
                Deep learning
             /       |        \
            v        v         v
     Computer vision NLP    Reinforcement learning
                      |
                      v
             Transformers and LLMs
                      |
           +----------+-----------+
           v                      v
     Prompt/context         Embeddings and retrieval
      engineering                   |
           |                        v
           +--------------------> RAG
                                    |
                       +------------+-----------+
                       v            v           v
                  Fine-tuning    AI agents   Multimodal AI
                       \            |           /
                        +-----------+----------+
                                    v
                       Evaluation, safety, MLOps
                                    |
                                    v
                         Production systems / research
```

This is a simplified map, not the only valid route. Some topics can be studied in parallel. For example, basic Python and data analysis can progress together, while advanced deep learning research generally requires stronger mathematics and programming.

# Zero-to-100 Roadmap

Each stage includes a goal, prerequisites, learning topics, selected resources, practical work, a project, a mastery checkpoint, and common pitfalls. Links are selected from official documentation, universities, recognized educational projects, or established open-source projects. Resource details are described conservatively where pricing or course access can vary.

## STAGE 0 — Orientation and Understanding Artificial Intelligence

**Goal:** Understand the AI landscape before building systems.

**Prerequisites:** None.

**Learn:**
- Artificial intelligence, machine learning, deep learning, and generative AI.
- Symbolic/rule-based systems versus statistical learning.
- Narrow AI versus general intelligence as a research and conceptual distinction.
- Generative versus discriminative models.
- Data, algorithms, models, parameters, training, inference, and evaluation.
- Typical AI applications and limitations.
- Why models can hallucinate, fail under distribution shift, or reflect data bias.
- How to read a technical page and distinguish a demo from a validated result.

**Primary resources:**
- [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/): a structured entry point to ML concepts and problem framing.
- [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/): a project-based course covering classical AI and ML concepts; it expects prior Python experience, so save it for after Stage 2 if needed.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework): a reference for thinking about AI risks and responsible deployment.

**Practice:**
1. Classify ten products or features as rule-based, predictive ML, generative AI, or a combination.
2. For one use case, specify inputs, outputs, failure cases, and an evaluation metric.
3. Explain the difference between training a model and using it for inference.

**Project:** Write a two-page AI landscape guide with five use cases, their likely methods, and limitations.

**Mastery checkpoint:** Explain the major AI subfields without treating every AI system as an LLM.

**Common mistakes:** Starting with agent frameworks before understanding data, models, and evaluation; assuming a fluent answer is necessarily true.

## STAGE 1 — Computer and Developer Foundations

**Goal:** Set up, run, debug, and version-control projects independently.

**Prerequisites:** Basic computer use.

**Learn:**
- Files, folders, paths, file extensions, and permissions.
- Processes, environment variables, and command-line basics.
- Shell commands and package managers.
- Editors and IDEs.
- HTTP, requests, responses, and status codes.
- Git commits, branches, remotes, pull requests, and `.gitignore`.
- Python virtual environments and dependency files.
- Error messages, stack traces, debugging, and reproducible setup.

**Resources:**
- [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/): shell, tools, version control, and developer workflows.
- [Git documentation](https://git-scm.com/doc): official Git reference.
- [GitHub Skills](https://skills.github.com/): guided GitHub practice.
- [Python `venv` documentation](https://docs.python.org/3/library/venv.html): isolated Python environments.
- [MDN HTTP overview](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview): request/response fundamentals.

**Practice:**
- Create a repository, commit changes, create a branch, and merge a pull request.
- Run a Python file from a terminal.
- Create and activate a virtual environment.
- Reproduce a setup from a README on a clean directory.

**Project:** A small command-line application with a clear README, dependency instructions, and version history.

**Mastery checkpoint:** A second person can clone the repository and run it using your instructions.

**Common mistakes:** Committing API keys, omitting setup steps, and installing packages globally without tracking versions.

## STAGE 2 — Programming Foundations with Python

**Goal:** Write readable, modular, tested programs before building models.

**Prerequisites:** Stage 1 recommended.

**Learn in order:**
1. Installing Python; scripts versus notebooks.
2. Variables, types, operators, expressions, and input/output.
3. Strings and string methods.
4. Conditionals and loops.
5. Functions, parameters, return values, and scope.
6. Lists, tuples, sets, dictionaries, and comprehensions.
7. Modules, imports, packages, and dependency management.
8. File handling; CSV and JSON.
9. Exceptions and debugging.
10. Classes, objects, composition, and inheritance.
11. Iterators, generators, and type hints.
12. Testing and code organization.
13. HTTP requests and APIs.
14. Basic asynchronous programming when useful.

**Primary resource:**
- [The Python Tutorial](https://docs.python.org/3/tutorial/): official language tutorial; useful once the learner is comfortable installing and running programs.
- [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/): structured course with exercises.
- [Python Packaging User Guide](https://packaging.python.org/en/latest/): packaging and environment practices.
- [pytest documentation](https://docs.pytest.org/en/stable/): testing Python code.
- [Python Tutor](https://pythontutor.com/): visualize program execution and data structures.

**Practice:**
- Solve 30–50 small problems, gradually increasing difficulty.
- Parse a CSV, validate its rows, and write a summary.
- Call a public API and handle errors and timeouts.
- Add unit tests to a small module.
- Refactor a long script into functions and modules.

**Project:** A command-line data collector that calls an API, validates the response, saves JSON/CSV, and generates a report.

**Mastery checkpoint:** Build a modest program without copying a complete solution, explain its control flow, and test normal and failure cases.

**Optional language branch:** Java, JavaScript, or C++ can support broader software engineering goals, but Python remains the primary language for this curriculum.

## STAGE 3 — Data Structures, Algorithms, and Computational Thinking

**Goal:** Reason about representations, algorithms, and computational cost.

**Prerequisites:** Python fundamentals.

**Learn:**
- Problem decomposition, pseudocode, and flowcharts.
- Big O time and space complexity.
- Arrays, lists, linked lists, stacks, queues, and hash tables.
- Trees, heaps, graphs, and priority queues.
- Searching, sorting, recursion, and graph traversal.
- Greedy methods and introductory dynamic programming.
- Breadth-first search and depth-first search.
- Basic computational complexity and algorithmic trade-offs.

**Resources:**
- [OpenDSA](https://opendsa-server.cs.vt.edu/): interactive open educational materials on data structures and algorithms.
- [VisuAlgo](https://visualgo.net/en): visualizations of common data structures and algorithms.
- [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/): lectures, notes, and assignments; advanced compared with a beginner overview.
- [Python `collections` documentation](https://docs.python.org/3/library/collections.html): standard-library data structures.

**Practice:** Implement a stack, queue, hash-map use case, binary search, sorting algorithm, BFS, and DFS. Benchmark two implementations on increasing input sizes.

**Project:** Maze solver that compares BFS, DFS, and A* on the same maps.

**Mastery checkpoint:** Choose a data structure for a stated problem and explain the runtime trade-off.

**Common mistakes:** Memorizing complexity labels without understanding the operations being counted.

## STAGE 4 — Mathematics for AI

**Goal:** Understand the mathematical ideas behind models and optimization.

**Prerequisites:** Algebra, functions, and basic arithmetic. Study missing school-level algebra first if needed.

### 4.1 Algebra and functions
- Equations, inequalities, functions, composition, exponents, logarithms.
- Summation notation, sequences, coordinate systems, and mathematical reasoning.

Resources: [Khan Academy](https://www.khanacademy.org/math) and [Paul's Online Math Notes](https://tutorial.math.lamar.edu/).

### 4.2 Linear algebra
- Scalars, vectors, matrices, dot products, matrix multiplication.
- Linear combinations, span, basis, dimension, independence.
- Linear systems, norms, distances, orthogonality.
- Eigenvalues/eigenvectors, matrix decompositions, SVD.
- Geometric interpretation of transformations.

Resources:
- [3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra): visual intuition.
- [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/): lectures and problem sets.
- [NumPy linear algebra](https://numpy.org/doc/stable/reference/routines.linalg.html): computational practice.

### 4.3 Calculus
- Limits, continuity, derivatives, partial derivatives, chain rule.
- Gradients, multivariable functions, integrals, optimization.
- Jacobians and Hessians at an introductory level.
- Automatic differentiation versus symbolic and numerical differentiation.

Resources:
- [Khan Academy — Calculus](https://www.khanacademy.org/math/calculus-1).
- [3Blue1Brown — Essence of Calculus](https://www.3blue1brown.com/topics/calculus).
- [SciPy documentation](https://docs.scipy.org/doc/scipy/): numerical methods and scientific computing.

### 4.4 Probability
- Events, conditional probability, independence, Bayes' theorem.
- Random variables, distributions, expectation, variance, covariance.
- Joint and conditional distributions.
- Bernoulli, binomial, Gaussian, and other common distributions.
- Sampling, law of large numbers, and central limit theorem.

Resources:
- [Harvard Stat 110](https://stat110.hsites.harvard.edu/): probability course materials.
- [Seeing Theory](https://seeing-theory.brown.edu/): visual probability and statistics.

### 4.5 Statistics
- Descriptive statistics, sampling, estimation, confidence intervals.
- Hypothesis testing, p-values, effect sizes, and statistical power.
- Regression, correlation versus causation, experimental design.
- Sampling bias, measurement error, and uncertainty.

Resources:
- [OpenIntro Statistics](https://www.openintro.org/book/os/): openly available statistics textbook.
- [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html): statistical computing reference.

### 4.6 Optimization and numerical methods
- Objective and loss functions, gradients, gradient descent, learning rates.
- Convexity intuition, regularization, constraints, numerical stability.
- Floating-point arithmetic and approximation.

Resources:
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course): practical loss, gradient descent, and ML concepts.
- [Dive into Deep Learning](https://d2l.ai/): mathematical and computational explanations for deep learning.

**Practice:** Implement vector operations and gradient descent with NumPy; visualize a loss function; calculate simple probabilities; compare sample estimates across random seeds.

**Project:** Implement linear regression with gradient descent from scratch and compare it with a trusted library.

**Mastery checkpoint:** Explain a gradient, compute a small dot product, interpret a probability, and describe why a model minimizes a loss.

**Common mistakes:** Waiting to master every advanced proof before practicing ML, or skipping all mathematics and treating training as magic. Learn the math in layers, then deepen it when the model requires it.

## STAGE 5 — Python for Data Analysis and Scientific Computing

**Goal:** Turn raw datasets into documented analyses.

**Prerequisites:** Python basics and algebra; Stage 4 can progress in parallel.

**Learn:** NumPy arrays and broadcasting; Pandas/Polars tables; visualization; Jupyter; missing values; duplicates; outliers; joins and aggregation; exploratory data analysis; feature inspection; random seeds; data leakage; and reproducible reports.

**Resources:**
- [NumPy Learn](https://numpy.org/learn/): curated official learning material.
- [NumPy documentation](https://numpy.org/doc/stable/).
- [pandas getting started](https://pandas.pydata.org/docs/getting_started/index.html).
- [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html).
- [Jupyter documentation](https://docs.jupyter.org/en/latest/).
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/): freely available online edition; check the edition and license information on the site.

**Practice:** Clean a real CSV; create summary tables and charts; write reusable transformations; explain the limitations of the dataset.

**Project:** Reproducible exploratory data analysis notebook with a short written report and a clear data source.

**Mastery checkpoint:** Another person can rerun the notebook and understand the conclusions and assumptions.

## STAGE 6 — Databases, Data Engineering, and Data Preparation

**Goal:** Understand how reliable data is collected, validated, split, and supplied to models.

**Prerequisites:** Python and data analysis.

**Learn:**
- SQL `SELECT`, filtering, joins, grouping, subqueries, and window functions.
- Relational schemas, keys, normalization, and indexes.
- CSV, JSON, and Parquet.
- ETL/ELT, ingestion, validation, and data pipelines.
- Batch versus streaming concepts.
- Data labeling, annotation quality, provenance, and versioning.
- Train/validation/test splits, class imbalance, and leakage prevention.
- Feature scaling, encoding, privacy, and dataset documentation.

**Resources:**
- [SQLBolt](https://sqlbolt.com/): interactive SQL lessons.
- [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html): official database tutorial.
- [DuckDB documentation](https://duckdb.org/docs/): analytical SQL engine.
- [Polars user guide](https://docs.pola.rs/): DataFrame processing.
- [Great Expectations documentation](https://docs.greatexpectations.io/): data quality workflows.
- [DVC documentation](https://dvc.org/doc): data and model versioning workflows.

**Practice:** Ingest files, validate schema and ranges, deduplicate records, and produce deterministic train/test splits.

**Project:** A versioned data pipeline that converts raw data into a documented model-ready dataset.

**Mastery checkpoint:** Show the source, transformations, schema, split strategy, and checks that reduce leakage risk.

## STAGE 7 — Classical Artificial Intelligence

**Goal:** Learn search, planning, logic, and constraint solving.

**Prerequisites:** Python and basic data structures.

**Learn:**
- Intelligent agents and problem formulation.
- State spaces and search trees.
- BFS, DFS, uniform-cost search, heuristic search, A*.
- Adversarial search, minimax, and alpha-beta pruning.
- Constraint satisfaction and backtracking.
- Propositional and first-order logic.
- Knowledge representation and rule-based expert systems.
- Planning and probabilistic reasoning.

**Resources:**
- [Harvard CS50 AI](https://cs50.harvard.edu/ai/): projects on search, knowledge, uncertainty, optimization, learning, neural networks, and language.
- [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/): course materials and search/decision-making concepts.
- [AIMA resources](https://aima.cs.berkeley.edu/): companion resources for *Artificial Intelligence: A Modern Approach*; book access depends on edition and publisher.

**Practice:** Implement a maze solver, tic-tac-toe opponent, and a small constraint solver.

**Project:** A puzzle-solving agent with a baseline, node-expansion counts, and comparisons between search strategies.

**Mastery checkpoint:** Select a classical AI technique and justify it for the problem structure.

## STAGE 8 — Machine Learning Foundations

**Goal:** Learn the complete ML workflow before pursuing specialized models.

**Prerequisites:** Python, data analysis, basic linear algebra, probability, and statistics.

**Workflow:**
1. Define the task and metric.
2. Inspect data and establish a baseline.
3. Create train/validation/test splits.
4. Build preprocessing pipelines.
5. Train models and tune using training/validation data.
6. Evaluate once on held-out test data.
7. Diagnose errors and compare baselines.
8. Document limitations and save the reproducible model.

### Supervised learning
- Regression and classification.
- Linear and logistic regression.
- k-nearest neighbors.
- Decision trees and random forests.
- Gradient boosting.
- Support vector machines and Naive Bayes.
- Regularization, feature engineering, and selection.

### Unsupervised learning
- Clustering: k-means, hierarchical, and density-based methods.
- Dimensionality reduction and PCA.
- Anomaly detection and representation learning concepts.

### Evaluation
- Train/validation/test split and cross-validation.
- Underfitting, overfitting, bias-variance trade-off.
- Confusion matrix, precision, recall, F1, ROC and precision-recall curves.
- MAE, MSE, RMSE, and \(R^2\).
- Calibration, thresholds, class imbalance, error analysis.
- Hyperparameter tuning, leakage, and distribution shift.

**Resources:**
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course): practical modules and interactive exercises.
- [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html): pipelines, estimators, and model evaluation.
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html): reference for algorithms and workflows.
- [Introduction to Statistical Learning](https://www.statlearning.com/): textbook and companion materials; check current edition resources.
- [Kaggle Learn](https://www.kaggle.com/learn): short practical exercises; account and platform requirements may apply.

**Practice:** Train at least one regression and one classification model; compare against a naive baseline; use a pipeline; explain metric choice.

**Project:** End-to-end tabular prediction with preprocessing, baseline, evaluation, error analysis, and a model card.

**Mastery checkpoint:** Explain why your split, metric, and baseline are appropriate and why the test set was not used for repeated tuning.

## STAGE 9 — Intermediate and Advanced Machine Learning

**Goal:** Select methods based on problem structure rather than novelty.

**Prerequisites:** Stage 8 and stronger statistics.

**Topics:**
- Gradient boosting systems and ensemble learning.
- Bayesian methods and probabilistic ML.
- Gaussian processes, where relevant.
- Time-series analysis and forecasting.
- Recommender systems, ranking, and learning-to-rank.
- Anomaly detection and imbalanced learning.
- Semi-supervised, self-supervised, active, and online learning.
- Transfer learning and domain adaptation.
- Causal inference foundations.
- Model uncertainty, interpretability, robustness, and distribution shift.

**Resources:**
- [Google ML advanced courses](https://developers.google.com/machine-learning): topic-specific courses including clustering and recommendation systems.
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html): implementations and assumptions.
- [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/).
- [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/).
- [Evidently documentation](https://docs.evidentlyai.com/): data and model monitoring concepts.
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/): online textbook for forecasting.

**Project options:** Recommender, forecast, ranking system, or anomaly detector with temporal or group-aware evaluation where appropriate.

**Mastery checkpoint:** Compare two plausible methods, explain assumptions, and show where each fails.

## STAGE 10 — Deep Learning Foundations

**Goal:** Understand neural networks and train them reproducibly.

**Prerequisites:** Linear algebra, derivatives/chain rule, probability basics, and Python.

**Learn:**
- Perceptrons, neurons, layers, activations, and tensors.
- Forward propagation, loss, backpropagation, and computational graphs.
- Automatic differentiation.
- SGD, mini-batches, Adam, and learning-rate schedules.
- Initialization, normalization, dropout, and regularization.
- Vanishing/exploding gradients, training curves, and checkpointing.
- GPU fundamentals and reproducibility.

**Frameworks:** Start with PyTorch. Learn TensorFlow/Keras if required by a course or project. Treat JAX as an optional advanced path.

**Resources:**
- [PyTorch Tutorials](https://docs.pytorch.org/tutorials/): official beginner workflow and advanced recipes.
- [TensorFlow Tutorials](https://www.tensorflow.org/tutorials): official notebook-based lessons.
- [Dive into Deep Learning](https://d2l.ai/): interactive text with theory and code.
- [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/): free, practical course for learners with some coding experience.
- [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/): free online book.

**Practice:** Implement a tiny neural network with NumPy; then train a model using PyTorch; plot training and validation loss; diagnose overfitting.

**Project:** A reproducible classification network with tracked experiments and documented failure cases.

**Mastery checkpoint:** Explain forward pass, loss, gradients, backpropagation, and the purpose of validation data.

## STAGE 11 — Computer Vision

**Goal:** Build systems that process images and video.

**Prerequisites:** Deep learning foundations and basic linear algebra.

**Learn:**
- Image tensors, color channels, transformations, and augmentation.
- CNNs, convolution, pooling, and transfer learning.
- Classification, object detection, semantic/instance segmentation.
- Image embeddings and similarity.
- Vision transformers and OCR.
- Video understanding and evaluation.
- Dataset annotation, licensing, and privacy.

**Resources:**
- [Stanford CS231n](https://cs231n.stanford.edu/): deep learning for computer vision course material.
- [Torchvision tutorials](https://pytorch.org/vision/stable/index.html): image datasets, transformations, and model utilities.
- [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html): image and video processing.
- [Hugging Face computer vision course materials](https://huggingface.co/learn): model and task-oriented learning resources.
- [COCO dataset](https://cocodataset.org/): widely used detection/segmentation benchmark; review terms.
- [Roboflow Universe](https://universe.roboflow.com/): dataset and project discovery; review each dataset's license.

**Project progression:** Image classifier → transfer-learning classifier → detection or segmentation system → optional deployed inference API.

**Mastery checkpoint:** Report task-specific metrics and describe dataset coverage, error types, and limitations.

## STAGE 12 — Natural Language Processing

**Goal:** Understand text processing from classical methods to neural models.

**Prerequisites:** Python, probability/statistics, and basic ML.

**Learn:**
- Tokenization, normalization, stemming, and lemmatization.
- Bag of words, n-grams, TF-IDF, and text classification.
- Word embeddings and Word2Vec-style representations.
- RNNs, LSTMs, GRUs, attention, and transformer foundations.
- NER, semantic similarity, retrieval, summarization, translation, and question answering.
- Multilingual NLP and task-specific evaluation.

**Resources:**
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/): NLP with deep learning, including transformers and LLMs. Prerequisites include probability and ML foundations.
- [NLTK Book](https://www.nltk.org/book/): introductory NLP concepts and exercises.
- [spaCy course](https://course.spacy.io/): practical NLP pipeline lessons.
- [Hugging Face NLP course](https://huggingface.co/learn/nlp-course): transformers and practical NLP workflows.
- [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/): online draft textbook; verify edition status.

**Project progression:** Spam/sentiment classifier → semantic similarity → text search or question-answering prototype.

**Mastery checkpoint:** Compare a TF-IDF baseline with an embedding or transformer-based approach and explain the evaluation trade-offs.

## STAGE 13 — Transformers and Large Language Models

**Goal:** Understand modern language models beyond using an API.

**Prerequisites:** Deep learning, NLP, linear algebra, and probability.

**Learn:**
- Tokenization and embeddings.
- Positional information and self-attention.
- Multi-head attention and transformer blocks.
- Encoder-only, decoder-only, and encoder-decoder architectures.
- Pretraining objectives and next-token prediction.
- Context windows, decoding, temperature, top-k, and top-p.
- Instruction tuning, supervised fine-tuning, and preference optimization.
- Quantization, distillation, and efficient inference.
- Open-weight model licenses, model cards, and limitations.
- Hallucination, prompt injection, and LLM evaluation.

**Resources:**
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/): visual introduction.
- [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/): model loading, pipelines, tokenizers, training, and inference.
- [Hugging Face course](https://huggingface.co/learn): hands-on model and NLP education.
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/): theoretical and practical NLP background.
- [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/): talks and seminar resources on transformers.
- [Meta Llama documentation](https://www.llama.com/docs/): model-specific information; licensing varies by model.
- [Mistral documentation](https://docs.mistral.ai/): model and API reference.

**Practice:** Inspect tokenization; compare decoding parameters; run a small pretrained model; write a small set of evaluation questions and score outputs.

**Project:** An LLM application with documented model/version, test set, evaluation criteria, and limitations.

**Mastery checkpoint:** Explain the transformer block, next-token prediction, inference decoding, and the difference between pretraining and adaptation.

## STAGE 14 — Generative AI Beyond Text

**Goal:** Understand the major families of generative models and multimodal generation.

**Prerequisites:** Deep learning; Stage 13 is helpful for multimodal LLMs.

**Learn:**
- Generative versus discriminative modeling.
- Latent representations and variational autoencoders.
- Generative adversarial networks.
- Diffusion models and denoising.
- Text-to-image, image-to-image, video, audio, and speech generation.
- Conditioning, guidance, sampling, and adapters.
- Synthetic data, output evaluation, copyright, provenance, and misuse risks.

**Resources:**
- [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course): diffusion concepts and implementation.
- [Hugging Face Diffusers documentation](https://huggingface.co/docs/diffusers/index): model pipelines and training/inference.
- [TensorFlow tutorials](https://www.tensorflow.org/tutorials): includes generative-model examples.
- [Runway Academy](https://academy.runwayml.com/): generative-video guidance and examples.
- [Stability AI documentation](https://platform.stability.ai/docs): model/API documentation; usage and licensing terms vary.

**Practice:** Generate outputs with a documented set of inputs and settings; compare consistency, fidelity, controllability, and failure cases.

**Project:** A small image, audio, or video generation prototype with an evaluation rubric and rights/safety notes.

**Mastery checkpoint:** Explain at least two model families and why they have different strengths and costs.

## STAGE 15 — Prompt Engineering and Context Engineering

**Goal:** Design instructions and context that can be tested and maintained.

**Prerequisites:** Basic LLM usage and clear written communication.

**Learn:**
- Clear task instructions and context selection.
- Role, constraints, audience, and output schema.
- Few-shot examples and structured JSON outputs.
- Prompt templates and variables.
- Prompt chaining, context assembly, and tool instructions.
- Model-specific behavior and context-window limits.
- Prompt versioning, test cases, adversarial testing, and prompt injection.
- Untrusted input handling and data leakage risks.

**Resources:**
- [OpenAI prompting guide](https://developers.openai.com/api/docs/guides/prompt-engineering): official prompting guidance; model/API features change over time.
- [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview): model-specific techniques and examples.
- [Google Gemini prompting strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies): official developer guidance.
- [Learn Prompting](https://learnprompting.org/): educational material on prompting and prompt security.
- [Prompting Guide](https://www.promptingguide.ai/): techniques, examples, and research links.

**Practice:** Create three prompt variants, define success criteria before testing, use normal and adversarial cases, and compare outputs systematically.

**Project:** A version-controlled prompt library with test cases, expected behaviors, and a repeatable evaluation procedure.

**Mastery checkpoint:** Demonstrate measured improvement, not merely a prompt that looks detailed.

## STAGE 16 — LLM APIs and AI Application Development

**Goal:** Build reliable AI-powered software.

**Prerequisites:** Python, HTTP/APIs, and basic LLM knowledge.

**Learn:**
- API authentication, secrets, request/response schemas, and model selection.
- Streaming, timeouts, retries, rate limits, and error handling.
- Token usage, cost estimation, conversation state, and structured outputs.
- Tool/function calling, multimodal inputs, and provider abstraction.
- Input validation, safety checks, logging, testing, fallback behavior, and privacy.
- Local inference versus hosted APIs.

**Resources:**
- [OpenAI API documentation](https://developers.openai.com/api/docs/): official API guides and reference.
- [Anthropic API documentation](https://docs.anthropic.com/): official API guides.
- [Google Gemini API documentation](https://ai.google.dev/gemini-api/docs): official API reference.
- [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/): build Python APIs.
- [Pydantic documentation](https://docs.pydantic.dev/latest/): data validation and schemas.
- [Ollama documentation](https://docs.ollama.com/): local model workflows; hardware requirements depend on model size.
- [LiteLLM documentation](https://docs.litellm.ai/): provider abstraction and routing; review current supported providers and license.

**Practice:** Build a small app with request validation, a timeout, error handling, environment-based secrets, and tests. Track latency and token/cost estimates.

**Project:** An AI application with a clean interface, backend API, tests, documented configuration, and failure behavior.

**Mastery checkpoint:** Demonstrate how the app responds to invalid input, provider errors, rate limits, and empty output.

## STAGE 17 — Embeddings, Vector Search, and Information Retrieval

**Goal:** Retrieve relevant source material independently of answer generation.

**Prerequisites:** Python, basic NLP, and ML evaluation.

**Learn:**
- Information retrieval; dense and sparse retrieval.
- Embeddings and similarity metrics.
- Keyword search and BM25.
- Vector indexes, metadata filters, and hybrid retrieval.
- Chunking, document parsing, reranking, and query rewriting.
- Precision, recall, ranking metrics, latency, access control, and index updates.

**Resources:**
- [Sentence Transformers documentation](https://www.sbert.net/): sentence embeddings and semantic search.
- [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers): embedding models and model cards.
- [FAISS documentation](https://faiss.ai/): similarity search and vector indexing.
- [pgvector](https://github.com/pgvector/pgvector): vector similarity in PostgreSQL.
- [Qdrant documentation](https://qdrant.tech/documentation/): vector search and filtering.
- [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html): vector retrieval in Elasticsearch.
- [BEIR benchmark repository](https://github.com/beir-cellar/beir): heterogeneous information retrieval benchmark.

**Practice:** Build keyword search and dense retrieval over the same collection; compare top-k relevance using a small labeled query set.

**Project:** A semantic search engine with a visible source snippet, metadata, and retrieval evaluation.

**Mastery checkpoint:** Report retrieval quality separately from language-model answer quality.

## STAGE 18 — Retrieval-Augmented Generation (RAG)

**Goal:** Build document-grounded AI systems with measurable retrieval and answer quality.

**Prerequisites:** LLM APIs, embeddings, document processing, and basic evaluation.

**Learn:**
- Ingestion, parsing, chunking, metadata, embeddings, and indexing.
- Keyword, dense, and hybrid retrieval.
- Reranking, query rewriting, context assembly, and compression.
- Grounded generation, citations, and source attribution.
- Conversational RAG and access control.
- Evaluation sets, retrieval metrics, faithfulness, citation correctness, and hallucination analysis.
- Freshness, observability, tenant isolation, and production failure modes.
- Advanced: graph-based, hierarchical, agentic, and multimodal RAG.
- Decide among prompting, RAG, fine-tuning, and long-context approaches.

**Resources:**
- [LangChain learning guides](https://docs.langchain.com/oss/python/learn): tutorials including semantic search and RAG agents.
- [LlamaIndex documentation](https://docs.llamaindex.ai/): data connectors, indexes, retrieval, and query engines.
- [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/): a worked RAG example; verify current dependencies.
- [Ragas documentation](https://docs.ragas.io/): RAG evaluation methods.
- [OpenAI evaluation best practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices): principles for testing variable model outputs.
- [OWASP GenAI Security Project](https://genai.owasp.org/): risks such as prompt injection and insecure AI integrations.

**Project progression:**
1. Searchable document collection.
2. Basic RAG Q&A.
3. Hybrid retrieval with citations.
4. Evaluated RAG application with logging and access control.

**Mastery checkpoint:** Maintain a fixed evaluation set and demonstrate a measurable change in retrieval or answer quality.

**Common mistakes:** Treating every vector search as RAG; assuming citations are correct because they exist; placing sensitive documents in an index without access-control design.

## STAGE 19 — Fine-Tuning and Custom Model Adaptation

**Goal:** Decide when adapting a pretrained model is justified and evaluate whether it helps.

**Prerequisites:** Deep learning, LLM basics, dataset preparation, and evaluation.

**Learn:**
- Prompting versus RAG versus fine-tuning.
- Instruction datasets and data quality.
- Supervised fine-tuning and transfer learning.
- LoRA, QLoRA, and parameter-efficient fine-tuning.
- Quantization and compute requirements.
- Validation, overfitting, catastrophic forgetting, and regression tests.
- Dataset and model licensing, privacy, model cards, and deployment.

**Resources:**
- [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/index): parameter-efficient fine-tuning.
- [Hugging Face TRL documentation](https://huggingface.co/docs/trl/index): training methods for transformer models.
- [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training): official training workflows.
- [Axolotl documentation](https://docs.axolotl.ai/): configurable fine-tuning workflows; hardware and supported models vary.
- [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards): documentation of model intended use and limitations.

**Practice:** Establish a baseline before fine-tuning; create a small, legally usable dataset; compare held-out performance and regressions.

**Project:** Adapt a suitable open-weight model for one narrow task and compare it against prompting and/or RAG baselines.

**Mastery checkpoint:** Show measurable improvement and explain the compute, licensing, data, and maintenance trade-offs.

## STAGE 20 — AI Agents and Tool-Using Systems

**Goal:** Build bounded systems that can choose tools and execute multi-step workflows safely.

**Prerequisites:** LLM APIs, structured outputs, software testing, and security basics.

**Learn:**
- Agent architecture, tool interfaces, state, planning, and task decomposition.
- Memory concepts and context management.
- Structured tool calls, workflow orchestration, and human approval.
- Workflow versus autonomous agent.
- Multi-agent coordination and when not to use it.
- Tool failure handling, retries, idempotency, and timeouts.
- Least privilege, sandboxing, prompt injection, and traceability.
- Agent evaluation, cost/latency budgets, and monitoring.

**Resources:**
- [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview): stateful agent/workflow orchestration.
- [LangChain learning guides](https://docs.langchain.com/oss/python/learn): practical use cases and agent tutorials.
- [CrewAI documentation](https://docs.crewai.com/): role/task-oriented multi-agent workflows.
- [AutoGen documentation](https://microsoft.github.io/autogen/): multi-agent framework material; check the current project status and successor guidance before choosing it.
- [Model Context Protocol documentation](https://modelcontextprotocol.io/): a protocol for connecting AI applications to tools and data sources.
- [OWASP GenAI Security Project](https://genai.owasp.org/): agent and tool security considerations.

**Practice:** First implement one tool call without a framework. Add validation, permission checks, bounded retries, and an explicit approval step for consequential actions.

**Project progression:** Single tool assistant → multi-step research workflow → human-approved automation → evaluated bounded agent.

**Mastery checkpoint:** Demonstrate safe failure behavior and explain what the agent is permitted to do.

**Common mistakes:** Giving an agent unrestricted shell, file, email, payment, or production access; using multi-agent orchestration where a simple deterministic workflow is sufficient.

## STAGE 21 — Reinforcement Learning

**Goal:** Understand learning through interaction and reward.

**Prerequisites:** Probability, linear algebra, calculus basics, Python, and ML foundations.

**Learn:**
- Agent, environment, state, action, reward.
- Markov decision processes, policies, and value functions.
- Bellman equations and dynamic programming.
- Monte Carlo and temporal-difference methods.
- Q-learning and deep Q-networks.
- Policy gradients and actor-critic methods.
- Exploration/exploitation, reward design, reward hacking, offline RL, and evaluation.

**Resources:**
- [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/): lecture materials.
- [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/): educational deep RL resource; check its maintenance status and dependencies.
- [Gymnasium documentation](https://gymnasium.farama.org/): standard API for RL environments.
- [Stable-Baselines3 documentation](https://stable-baselines3.readthedocs.io/): implementations and examples.

**Practice:** Implement tabular Q-learning in a small environment; compare against a random or rule-based policy; run multiple seeds.

**Project:** Train an agent in a simulated environment and report reward curves, variability, and baseline performance.

**Mastery checkpoint:** Explain the reward signal and show that the learned policy outperforms a baseline under a repeatable evaluation.

## STAGE 22 — Multimodal AI

**Goal:** Build applications combining text, images, documents, audio, and video.

**Prerequisites:** LLM APIs and relevant vision/NLP fundamentals.

**Learn:** Multimodal embeddings; vision-language models; image Q&A; OCR and document understanding; speech recognition and synthesis; audio understanding; video summarization; cross-modal retrieval; multimodal RAG; alignment; modality-specific evaluation; privacy and safety.

**Resources:**
- [Hugging Face task guides](https://huggingface.co/tasks): model and task introductions across modalities.
- [Transformers documentation](https://huggingface.co/docs/transformers/): multimodal model support and inference examples.
- [OpenAI API documentation](https://developers.openai.com/api/docs/): current API capabilities and input/output formats.
- [Google Gemini API documentation](https://ai.google.dev/gemini-api/docs): multimodal API guides.
- [Whisper repository](https://github.com/openai/whisper): speech recognition implementation; check dependencies and license.

**Project:** A document/image/audio understanding application with separate tests for each modality and for the end-to-end workflow.

**Mastery checkpoint:** Report failure cases by modality, not only a single overall score.

## STAGE 23 — AI Deployment and MLOps

**Goal:** Move experiments into maintainable, observable services.

**Prerequisites:** Python, APIs, ML workflows, and basic software engineering.

**Learn:**
- Model serialization and inference services.
- REST APIs and FastAPI.
- Docker, environment configuration, CI/CD, and tests.
- Experiment tracking, model registries, and data/model versioning.
- Batch versus online inference.
- GPU serving, quantization, caching, concurrency, latency, and throughput.
- Logging, tracing, monitoring, drift detection, rollback, and retraining.
- Security, reliability, and cloud cost management.

**Resources:**
- [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/).
- [Docker getting started](https://docs.docker.com/get-started/).
- [MLflow documentation](https://mlflow.org/docs/latest/): experiment tracking and model lifecycle.
- [DVC documentation](https://dvc.org/doc): data and pipeline versioning.
- [GitHub Actions documentation](https://docs.github.com/en/actions): CI/CD automation.
- [Evidently documentation](https://docs.evidentlyai.com/): monitoring and evaluation.
- [KServe documentation](https://kserve.github.io/website/): model serving; infrastructure requirements vary.

**Project:** Deploy an ML or RAG service with tests, health checks, structured logs, configuration management, and a documented rollback procedure.

**Mastery checkpoint:** Show how to reproduce, monitor, debug, and safely update the service.

## STAGE 24 — AI Evaluation, Reliability, Safety, and Security

**Goal:** Make system quality measurable and manage known risks.

**Prerequisites:** At least one ML or LLM application.

**Learn:**
- Benchmark and test-set design.
- Human and automated evaluation.
- Limits of LLM-as-a-judge.
- Hallucination, groundedness, and citation correctness.
- Bias, fairness, robustness, calibration, and distribution shift.
- Privacy, data governance, copyright, and licensing.
- Prompt injection, data exfiltration, unsafe tool execution, and model abuse.
- Red teaming, access control, audit trails, incident response, and transparency.
- Relevant standards and regulations; distinguish law from guidance.

**Resources:**
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework): AI risk management reference.
- [OWASP GenAI Security Project](https://genai.owasp.org/): LLM application risks and mitigations.
- [OpenAI evaluation best practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices): evaluation design principles.
- [Google Responsible AI](https://ai.google/responsibility/): principles and resources.
- [NIST AI Resource Center](https://airc.nist.gov/): AI risk resources.
- [MITRE ATLAS](https://atlas.mitre.org/): knowledge base of adversary tactics and techniques against AI-enabled systems.

**Practice:** Build an evaluation dataset with normal, edge, and adversarial cases. Test permissions and prompt injection. Record severity, likelihood, mitigations, and residual risks.

**Project:** An evaluation and risk-assessment suite for one AI application.

**Mastery checkpoint:** Produce a report covering quality, reproducibility, failure modes, safety controls, and unresolved limitations.

## STAGE 25 — AI Research and Advanced Theory

**Goal:** Read, reproduce, evaluate, and communicate research.

**Prerequisites:** Strong ML/deep learning foundations; mathematics appropriate to the chosen topic.

**Learn:**
- Research questions, hypotheses, and literature reviews.
- Reading methods, experiments, results, and limitations.
- Baselines, ablation studies, statistical uncertainty, and reproducibility.
- Benchmark limitations, dataset ethics, research integrity, and negative results.
- Preprints, peer review, citation management, implementation, and technical reporting.

**Resources:**
- [arXiv](https://arxiv.org/): preprints; preprints are not automatically peer-reviewed.
- [OpenReview](https://openreview.net/): conference review and paper discussion for participating venues.
- [ACL Anthology](https://aclanthology.org/): NLP and computational linguistics papers.
- [NeurIPS proceedings](https://proceedings.neurips.cc/).
- [ICML proceedings](https://proceedings.mlr.press/).
- [ICLR OpenReview](https://openreview.net/).
- [CVF Open Access](https://openaccess.thecvf.com/): computer vision conference papers.
- [Papers with Code](https://paperswithcode.com/): papers, implementations, datasets, and benchmarks; check project activity and links.
- [Google Research publications](https://research.google/pubs/).

**Practice:** Read one paper weekly; summarize the question, method, baseline, data, metric, result, and limitation. Reproduce a small result before attempting a novel extension.

**Project:** Reproduce an established result or compare methods in a controlled experiment.

**Mastery checkpoint:** Publish a technical report with code, environment, data provenance, results, and limitations.

## STAGE 26 — Advanced Specializations

These are branches, not one mandatory sequence. Choose one based on interests, prerequisites, and project goals.

### A. Machine Learning Engineering
- Focus: pipelines, training infrastructure, feature management, serving, monitoring, reliability.
- Start from: Stages 8–10 and 23–24.
- Resources: [scikit-learn](https://scikit-learn.org/stable/), [MLflow](https://mlflow.org/docs/latest/), [DVC](https://dvc.org/doc/), [KServe](https://kserve.github.io/website/).
- Capstone: versioned training pipeline and monitored prediction service.

### B. Generative AI Engineering
- Focus: LLM architecture, RAG, adaptation, evaluation, multimodal systems, agents, cost/latency.
- Start from: Stages 13–20 and 22–24.
- Resources: [Hugging Face](https://huggingface.co/learn), [LangChain](https://docs.langchain.com/), [LlamaIndex](https://docs.llamaindex.ai/), [Ragas](https://docs.ragas.io/).
- Capstone: evaluated RAG or multimodal assistant with permission boundaries and monitoring.

### C. Computer Vision Research
- Focus: detection, segmentation, vision-language models, 3D vision, video understanding.
- Start from: Stages 10–11 and 25.
- Resources: [CS231n](https://cs231n.stanford.edu/), [Torchvision](https://pytorch.org/vision/stable/), [CVF Open Access](https://openaccess.thecvf.com/).
- Capstone: reproduce or compare vision models on a clearly licensed dataset.

### D. NLP and Language Model Research
- Focus: transformer architectures, multilingual modeling, evaluation, alignment, efficient adaptation, retrieval.
- Start from: Stages 12–19 and 25.
- Resources: [CS224N](https://web.stanford.edu/class/cs224n/), [Hugging Face course](https://huggingface.co/learn/nlp-course), [ACL Anthology](https://aclanthology.org/).
- Capstone: controlled experiment on an NLP task with baselines and error analysis.

### E. Reinforcement Learning Research
- Focus: policy optimization, model-based/offline RL, multi-agent RL, simulation, safety.
- Start from: Stages 4, 8, 10, 21, and 25.
- Resources: [David Silver's course](https://www.davidsilver.uk/teaching/), [Gymnasium](https://gymnasium.farama.org/), [Stable-Baselines3](https://stable-baselines3.readthedocs.io/).
- Capstone: compare an RL method with a simple baseline across multiple seeds.

### F. Data Science and Applied ML
- Focus: statistics, experimentation, forecasting, causal inference, business metrics, decision support.
- Start from: Stages 4–9.
- Resources: [OpenIntro](https://www.openintro.org/book/os/), [Forecasting: Principles and Practice](https://otexts.com/fpp3/), [Kaggle Learn](https://www.kaggle.com/learn).
- Capstone: a decision-focused analysis with assumptions, uncertainty, and actionable recommendations.

### G. AI Infrastructure and Systems
- Focus: GPU computing, distributed training, parallelism, memory optimization, quantization, serving.
- Start from: Stages 10, 13, and 23.
- Resources: [PyTorch tutorials](https://docs.pytorch.org/tutorials/), [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/), [Ray documentation](https://docs.ray.io/).
- Capstone: benchmark inference throughput and latency with a documented environment.

### H. AI Research Scientist
- Focus: mathematical depth, research design, reproduction, novel hypotheses, scientific writing.
- Start from: Stages 4, 8–10, 25, and a focused specialization.
- Resources: [arXiv](https://arxiv.org/), [OpenReview](https://openreview.net/), [Papers with Code](https://paperswithcode.com/).
- Capstone: a reproducible study with an explicit research question and limitations.

### I. AI Product Engineering
- Focus: user needs, product architecture, UX for AI, evaluation, privacy, analytics, reliability, cost.
- Start from: Stages 8, 13–18, and 23–24.
- Resources: [Google PAIR Guidebook](https://pair.withgoogle.com/guidebook/), [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework), [OpenAI evaluation guidance](https://developers.openai.com/api/docs/guides/evaluation-best-practices).
- Capstone: an AI product prototype with user-centered evaluation and explicit risk controls.

## STAGE 27 — Portfolio and Capstone Projects

Build projects that show independent understanding, not only copied tutorials or thin API wrappers.

### Beginner projects
- Python calculator with tests.
- CSV data analyzer.
- Maze/search algorithm visualizer.
- Data visualization report.
- Rule-based chatbot with a clear rule set.

### Intermediate projects
- Regression and classification pipeline.
- Customer segmentation analysis.
- Recommendation engine.
- NLP classifier with baseline comparison.
- Image classifier using transfer learning.
- Time-series forecast with temporal validation.
- Semantic search application.

### Advanced projects
- Production-style ML API with monitoring.
- RAG application with hybrid retrieval and citations.
- Narrowly fine-tuned model compared against baselines.
- Multimodal document assistant.
- Tool-using agent with approval controls and bounded permissions.
- AI evaluation dashboard.
- Research reproduction project.

### Capstone requirements

Every serious capstone should document:

- Problem statement and intended users.
- Data source, license, and provenance.
- Baseline and methodology.
- Reproducible implementation and environment.
- Evaluation metrics and results.
- Error analysis and known limitations.
- Security, privacy, and misuse considerations.
- Setup instructions and tests.
- Demo or deployment where practical.
- Model card or system card when appropriate.

**Portfolio quality test:** Can a reviewer run it, understand why you chose the method, see how it was evaluated, and identify what does not work?

# Subject-Wise Resource Index

Use this index to jump directly to the relevant stage and primary references.

| Subject | Start here | Primary resources |
|---|---|---|
| AI fundamentals | Stage 0 | [Google ML](https://developers.google.com/machine-learning/), [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) |
| Computer tools, terminal, Git | Stage 1 | [Missing Semester](https://missing.csail.mit.edu/), [Git](https://git-scm.com/doc), [GitHub Skills](https://skills.github.com/) |
| Python | Stage 2 | [Python tutorial](https://docs.python.org/3/tutorial/), [CS50P](https://cs50.harvard.edu/python/) |
| Data structures and algorithms | Stage 3 | [OpenDSA](https://opendsa-server.cs.vt.edu/), [MIT 6.006](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) |
| Mathematics | Stage 4 | [Khan Academy](https://www.khanacademy.org/math), [3Blue1Brown](https://www.3blue1brown.com/), [MIT Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) |
| Linear algebra | Stage 4 | [3Blue1Brown](https://www.3blue1brown.com/topics/linear-algebra), [MIT OCW](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) |
| Calculus | Stage 4 | [Khan Academy](https://www.khanacademy.org/math/calculus-1), [3Blue1Brown](https://www.3blue1brown.com/topics/calculus) |
| Probability and statistics | Stage 4 | [Harvard Stat 110](https://stat110.hsites.harvard.edu/), [OpenIntro](https://www.openintro.org/book/os/) |
| NumPy | Stage 5 | [NumPy Learn](https://numpy.org/learn/), [NumPy docs](https://numpy.org/doc/stable/) |
| Pandas and data analysis | Stage 5 | [pandas getting started](https://pandas.pydata.org/docs/getting_started/index.html), [Matplotlib](https://matplotlib.org/stable/tutorials/index.html) |
| SQL and data engineering | Stage 6 | [SQLBolt](https://sqlbolt.com/), [PostgreSQL](https://www.postgresql.org/docs/current/tutorial.html), [DuckDB](https://duckdb.org/docs/) |
| Classical AI | Stage 7 | [CS50 AI](https://cs50.harvard.edu/ai/), [Berkeley CS188](https://inst.eecs.berkeley.edu/~cs188/) |
| Machine learning | Stage 8 | [Google MLCC](https://developers.google.com/machine-learning/crash-course), [scikit-learn](https://scikit-learn.org/stable/getting_started.html) |
| Advanced ML | Stage 9 | [scikit-learn](https://scikit-learn.org/stable/user_guide.html), [XGBoost](https://xgboost.readthedocs.io/en/stable/) |
| Deep learning | Stage 10 | [PyTorch](https://docs.pytorch.org/tutorials/), [D2L](https://d2l.ai/), [fast.ai](https://course.fast.ai/) |
| TensorFlow/Keras | Stage 10 | [TensorFlow tutorials](https://www.tensorflow.org/tutorials) |
| Computer vision | Stage 11 | [CS231n](https://cs231n.stanford.edu/), [OpenCV](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) |
| NLP | Stage 12 | [CS224N](https://web.stanford.edu/class/cs224n/), [NLTK Book](https://www.nltk.org/book/), [spaCy course](https://course.spacy.io/) |
| Transformers and LLMs | Stage 13 | [Hugging Face Transformers](https://huggingface.co/docs/transformers/), [Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) |
| Generative AI | Stage 14 | [Diffusers](https://huggingface.co/docs/diffusers/index), [Diffusion course](https://huggingface.co/learn/diffusion-course) |
| Prompt engineering | Stage 15 | [OpenAI guide](https://developers.openai.com/api/docs/guides/prompt-engineering), [Learn Prompting](https://learnprompting.org/) |
| LLM APIs | Stage 16 | [OpenAI](https://developers.openai.com/api/docs/), [Anthropic](https://docs.anthropic.com/), [Gemini](https://ai.google.dev/gemini-api/docs) |
| Embeddings and vector databases | Stage 17 | [Sentence Transformers](https://www.sbert.net/), [FAISS](https://faiss.ai/), [pgvector](https://github.com/pgvector/pgvector) |
| Information retrieval | Stage 17 | [BEIR](https://github.com/beir-cellar/beir), [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) |
| RAG | Stage 18 | [LangChain](https://docs.langchain.com/), [LlamaIndex](https://docs.llamaindex.ai/), [Ragas](https://docs.ragas.io/) |
| Fine-tuning | Stage 19 | [PEFT](https://huggingface.co/docs/peft/index), [TRL](https://huggingface.co/docs/trl/index) |
| AI agents | Stage 20 | [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview), [CrewAI](https://docs.crewai.com/), [MCP](https://modelcontextprotocol.io/) |
| Reinforcement learning | Stage 21 | [David Silver course](https://www.davidsilver.uk/teaching/), [Gymnasium](https://gymnasium.farama.org/) |
| Multimodal AI | Stage 22 | [Hugging Face tasks](https://huggingface.co/tasks), [Transformers](https://huggingface.co/docs/transformers/) |
| Deployment and MLOps | Stage 23 | [FastAPI](https://fastapi.tiangolo.com/tutorial/), [Docker](https://docs.docker.com/get-started/), [MLflow](https://mlflow.org/docs/latest/) |
| AI safety and evaluation | Stage 24 | [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework), [OWASP GenAI](https://genai.owasp.org/) |
| Research methodology | Stage 25 | [arXiv](https://arxiv.org/), [OpenReview](https://openreview.net/), [ACL Anthology](https://aclanthology.org/) |
| AI infrastructure | Stage 26G | [PyTorch](https://docs.pytorch.org/tutorials/), [Ray](https://docs.ray.io/), [NVIDIA DLI](https://www.nvidia.com/en-us/training/) |

# Resource Collections by Format

## Free courses and structured learning

- [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Python fundamentals with exercises.
- [CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — classical AI and ML projects; Python prerequisite.
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — practical ML concepts and interactive exercises.
- [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/) — hands-on deep learning for learners with coding experience.
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — NLP with deep learning; public materials vary by offering.
- [Stanford CS231n](https://cs231n.stanford.edu/) — computer vision course materials.
- [Hugging Face course](https://huggingface.co/learn) — NLP, transformers, and other model-oriented courses.
- [Kaggle Learn](https://www.kaggle.com/learn) — short practical lessons; account/platform conditions may apply.

## Official documentation

- [Python](https://docs.python.org/3/)
- [NumPy](https://numpy.org/doc/stable/)
- [pandas](https://pandas.pydata.org/docs/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [PyTorch](https://docs.pytorch.org/)
- [TensorFlow](https://www.tensorflow.org/learn)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/)
- [Hugging Face Datasets](https://huggingface.co/docs/datasets/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Docker](https://docs.docker.com/)
- [MLflow](https://mlflow.org/docs/latest/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [FAISS](https://faiss.ai/)
- [LangChain](https://docs.langchain.com/)
- [LlamaIndex](https://docs.llamaindex.ai/)

## Books and textbooks

Use publisher or author pages and legal open editions. Availability of free reading does not always mean unrestricted redistribution.

- [Python Tutorial](https://docs.python.org/3/tutorial/) — language fundamentals.
- [OpenIntro Statistics](https://www.openintro.org/book/os/) — statistics with exercises.
- [Dive into Deep Learning](https://d2l.ai/) — ML/deep learning theory with executable code.
- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) — introductory neural-network text.
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — Python tools for data analysis.
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/) — time-series and forecasting.
- [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) — NLP textbook draft.
- [A Course in Machine Learning](https://ciml.info/) — free online ML text by Hal Daumé III.
- [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — advanced statistical learning text; prerequisites are substantial.
- [Artificial Intelligence: A Modern Approach resources](https://aima.cs.berkeley.edu/) — companion material; textbook editions may be paid.

## Video lectures and explainers

- [3Blue1Brown](https://www.3blue1brown.com/) — visual mathematics.
- [MIT OpenCourseWare](https://ocw.mit.edu/) — university lectures and assignments.
- [Stanford Online / course pages](https://online.stanford.edu/) — courses and public materials; access varies.
- [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — course page links to available lecture videos.
- [Stanford CS231n](https://cs231n.stanford.edu/) — vision lectures and notes.
- [David Silver's RL course](https://www.davidsilver.uk/teaching/) — reinforcement learning lectures.

## Interactive learning and notebooks

- [Google Colab](https://colab.research.google.com/) — hosted notebooks; compute availability is dynamic and not guaranteed.
- [Kaggle Notebooks](https://www.kaggle.com/code) — notebooks, datasets, and competitions; compute quotas can change.
- [Jupyter](https://jupyter.org/) — notebook ecosystem.
- [Python Tutor](https://pythontutor.com/) — visualize Python execution.
- [VisuAlgo](https://visualgo.net/en) — data structures and algorithms.
- [SQLBolt](https://sqlbolt.com/) — interactive SQL lessons.
- [Kaggle Learn](https://www.kaggle.com/learn) — hands-on exercises.

## GitHub repositories and practical implementations

- [scikit-learn](https://github.com/scikit-learn/scikit-learn) — ML algorithms and pipelines.
- [PyTorch examples](https://github.com/pytorch/examples) — model examples.
- [Hugging Face Transformers](https://github.com/huggingface/transformers) — transformer library and examples.
- [Hugging Face Diffusers](https://github.com/huggingface/diffusers) — diffusion models.
- [OpenAI Whisper](https://github.com/openai/whisper) — speech recognition.
- [FAISS](https://github.com/facebookresearch/faiss) — vector similarity search.
- [pgvector](https://github.com/pgvector/pgvector) — vector search for PostgreSQL.
- [DVC](https://github.com/iterative/dvc) — data versioning and pipelines.
- [MLflow](https://github.com/mlflow/mlflow) — experiment tracking and ML lifecycle.
- [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — RL environments.
- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) — RL algorithms.
- [AIMA Python](https://github.com/aimacode/aima-python) — educational AI algorithms.

Check each repository's license, recent activity, dependencies, and compatibility before relying on it.

# Practice and Assessment Framework

Use this checklist at the end of every stage:

- [ ] I can explain the main concepts without reading the tutorial.
- [ ] I completed the core exercises.
- [ ] I implemented the stage's project.
- [ ] I can explain design choices and trade-offs.
- [ ] I tested normal inputs, edge cases, and failure behavior.
- [ ] I documented the setup and dependencies.
- [ ] I evaluated the result with an appropriate method.
- [ ] I recorded limitations and what I would improve next.
- [ ] I can answer questions about the project without relying on generated explanations.

## A practical scoring rubric

Use this as a self-review tool, not a formal certification.

| Dimension | 0 — Not yet | 1 — Guided | 2 — Independent |
|---|---|---|---|
| Concepts | Cannot explain core ideas | Explains with notes or prompts | Explains with accurate examples |
| Implementation | No working implementation | Works after substantial copying | Implements and debugs independently |
| Evaluation | No defined tests or metrics | Uses a basic metric/test | Selects and justifies suitable tests/metrics |
| Reproducibility | Setup unclear | Partial setup notes | Reproducible environment and instructions |
| Limitations | Cannot identify failures | Names obvious failures | Tests and documents meaningful failure modes |

A reasonable advancement rule is to score at least **7/10** and have no zero in implementation or evaluation. If a stage is not yet mastered, repeat the project with a different dataset or problem rather than simply rewatching the material.

## Common mistakes across the roadmap

- Skipping programming and mathematics entirely.
- Studying many courses in parallel without finishing exercises.
- Using a large neural network before establishing a baseline.
- Evaluating on training data or repeatedly tuning against the test set.
- Confusing accuracy with usefulness or reliability.
- Copying generated code without understanding it.
- Treating benchmarks as complete evidence of real-world performance.
- Ignoring data and model licenses.
- Putting secrets or sensitive datasets in public repositories.
- Building an autonomous agent before defining permissions, stop conditions, and failure handling.

# Example Learning Schedules

These schedules are planning examples, not guarantees. Progress depends on prior knowledge, weekly study time, mathematical preparation, and project scope.

## 3-month introductory path

**Best for:** Understanding the landscape and building a first small ML project.

- Month 1: Stages 0–2 — AI orientation, developer tools, Python.
- Month 2: Stage 3 essentials plus Stage 4 introductory algebra, vectors, and probability; start NumPy/Pandas.
- Month 3: Stages 5 and 8 introductory concepts; complete one small scikit-learn project and document it.

**Outcome:** Basic Python fluency and one evaluated beginner ML project. This is not advanced AI engineering.

## 6-month practical AI developer path

**Best for:** Learners who can study consistently and want to build practical applications.

- Month 1: Stages 0–3; Python and developer workflow.
- Month 2: Stage 4 essentials and Stage 5 data analysis.
- Month 3: Stages 6–8; data preparation and classical ML.
- Month 4: Stage 10 foundations and selected NLP/transformer concepts.
- Month 5: Stages 15–18; prompting, APIs, embeddings, and a basic RAG app.
- Month 6: Stages 23–24 essentials; deploy, evaluate, and document a capstone.

**Outcome:** A practical prototype with tests and evaluation. Deep research competence generally requires more time.

## 12-month comprehensive AI engineering path

- Months 1–2: Stages 0–3 — programming, tools, algorithms.
- Months 3–4: Stage 4 mathematics and Stages 5–6 data skills.
- Months 5–6: Stages 7–9 classical AI and ML.
- Months 7–8: Stages 10–13 deep learning, vision/NLP foundations, transformers.
- Months 9–10: Stages 14–20 generative AI, APIs, retrieval, RAG, fine-tuning, agents.
- Month 11: Stages 23–24 deployment, evaluation, and security.
- Month 12: Stage 27 capstone plus selected Stage 25 research reading.

**Outcome:** A broader applied foundation, not guaranteed mastery of every branch.

## Research-oriented long-term path

1. Complete programming, algorithms, mathematics, statistics, and ML foundations.
2. Study deep learning and choose one research specialization.
3. Read papers with a consistent structured template.
4. Reproduce published baselines before proposing changes.
5. Learn research methodology, ablations, uncertainty, and limitations.
6. Build a reproducible portfolio and seek feedback from experienced researchers.
7. Consider formal graduate study when the chosen research role benefits from it.

# Free-First Learning Strategy

Prioritize high-quality public resources before paying for a course or compute.

For each subject, aim for:
1. One primary free course or textbook, where suitable.
2. One official documentation source.
3. One exercise or notebook resource.
4. One implementation project.
5. One optional advanced reference.

Understand the difference:

- **Free to read:** The content can be accessed without payment; redistribution rights may still be restricted.
- **Free to audit:** Course material may be free, but certificates, grading, or some features may cost money.
- **Free course with paid certificate:** Learning access and credential costs differ.
- **Free software with paid hosting:** Software may be open source, while hosted infrastructure costs money.
- **Free trial:** Temporary access; not a durable free tier.
- **Open source:** Software is distributed under an identifiable license; review the license.
- **Open weights:** Model weights are available, but license and acceptable-use restrictions may still apply.
- **Free compute:** Subject to quotas, hardware availability, idle timeouts, and changing provider policies.

Avoid paying for several overlapping courses. Invest first in a strong foundation, consistent practice, and well-documented projects.

# Datasets and Computing

## Dataset portals

- [Kaggle Datasets](https://www.kaggle.com/datasets) — community datasets and competitions; inspect the dataset page and license.
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — classic ML datasets and metadata.
- [Hugging Face Datasets](https://huggingface.co/datasets) — datasets for NLP, vision, audio, and other tasks; licenses vary.
- [Google Dataset Search](https://datasetsearch.research.google.com/) — discovery across dataset-hosting sites.
- [Google Research resources](https://research.google/resources/) — datasets and research resources.
- [Papers with Code](https://paperswithcode.com/) — discover datasets, benchmarks, papers, and implementations.
- [COCO](https://cocodataset.org/) — computer-vision dataset and benchmark.
- [Common Voice](https://commonvoice.mozilla.org/) — multilingual speech dataset; review dataset-specific terms.
- [OpenML](https://www.openml.org/) — datasets and machine-learning experiment resources.

**Before use:** Check the license, collection method, permitted purposes, personal information, potential bias, and whether the dataset is appropriate for your intended use.

## Compute and development environments

- [Google Colab](https://colab.research.google.com/) — browser notebooks; free GPU/TPU access may be available but is restricted and not guaranteed.
- [Kaggle Notebooks](https://www.kaggle.com/code) — notebook environment with platform-specific compute quotas.
- [Hugging Face Spaces](https://huggingface.co/docs/hub/spaces-overview) — deploy demos; CPU/static options and paid hardware differ.
- [Jupyter](https://jupyter.org/) — run notebooks locally.
- [Ollama](https://ollama.com/) — run supported models locally; memory and performance depend on hardware and model size.
- [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — official explanation of dynamic resource limits.

**Practical strategy:** Start with CPU-friendly datasets and small models. Use hosted GPUs only when needed. Avoid designing a learning plan around the assumption that a specific free GPU will always be available.

# Glossary

- **Artificial intelligence (AI):** Broad field concerned with systems that perform tasks associated with intelligent behavior.
- **Machine learning (ML):** Methods that fit patterns from data to make predictions or decisions.
- **Deep learning:** ML using neural networks with multiple learned layers.
- **Model:** A parameterized or structured system used to map inputs to outputs.
- **Training:** Process of fitting model parameters or structure to data or experience.
- **Inference:** Using a trained or configured model to produce outputs.
- **Dataset:** A collection of examples or records used for analysis, training, or evaluation.
- **Feature:** An input variable or representation used by a model.
- **Label:** Target value supplied for supervised learning.
- **Loss function:** Numerical objective used to quantify model error during optimization.
- **Gradient descent:** Optimization method that updates parameters using gradient information.
- **Neural network:** A model composed of interconnected computational layers.
- **Transformer:** Neural architecture built around attention mechanisms and related components.
- **LLM:** Large language model trained to process or generate language.
- **Token:** A unit used by a model's tokenizer to represent text or other input.
- **Embedding:** A vector representation that encodes useful properties of an item.
- **Vector database/index:** System for storing and searching vector representations.
- **RAG:** Retrieval-augmented generation; a system retrieves external context before generating an answer.
- **Fine-tuning:** Further training or adaptation of a pretrained model for a task or domain.
- **Agent:** An AI system that selects actions or uses tools toward a goal within some control structure.
- **Evaluation:** Systematic measurement of model or application behavior against defined criteria.
- **Overfitting:** When a model fits training data too closely and generalizes poorly.
- **Data leakage:** Information enters training or model selection that would not legitimately be available at prediction time.
- **MLOps:** Practices for deploying, monitoring, versioning, and maintaining ML systems.
- **Multimodal AI:** AI that processes or produces more than one modality, such as text, images, audio, or video.
- **Inference latency:** Time required to produce an inference result.
- **Quantization:** Representing model values with lower numerical precision to reduce memory or computation, often with accuracy trade-offs.
- **Benchmark:** A defined dataset/task and evaluation procedure used to compare systems.
- **Model drift:** Change in data or relationships that can reduce model performance over time.
- **Baseline:** A simple or established method used as a comparison point.
- **Ablation study:** Experiment that removes or changes components to measure their contribution.
- **Calibration:** Agreement between predicted confidence/probability and observed outcomes.
- **Distribution shift:** Difference between data encountered in deployment and data used during training or evaluation.

# Contribution Guidelines

Contributions that improve sequencing, correctness, accessibility, or practical value are welcome.

For each proposed resource, include:
1. Resource name and canonical URL.
2. Subject and roadmap stage.
3. Resource format and actual topics covered.
4. Prerequisites and target level.
5. Cost/access status only when verified.
6. License information where applicable.
7. Date checked and evidence that the link matches the description.
8. Why it adds value beyond existing entries.

Please:
- Prefer official and original sources.
- Avoid duplicate resources and broken links.
- Do not claim a resource is free, open source, or licensed for redistribution without evidence.
- Do not add unauthorized copies of copyrighted books.
- Keep the roadmap dependency-aware and beginner-friendly.
- Label outdated or archived material clearly.
- Use concise Markdown and test anchors after major structural changes.

# Verification Methodology

This directory was researched and reviewed on **2026-10-25** using public web search and original provider, university, project, or documentation pages where available.

Verification labels used in this README:
- **Official resource:** Published by the provider, university, project owner, or standards organization.
- **Established educational resource:** A recognized educational project or course with a clear learning purpose.
- **Research/resource index:** Useful for discovery, but individual papers, repositories, and datasets must be checked separately.
- **Availability varies:** Access, pricing, compute, versions, or course materials may change by region, date, or account.
- **Supplementary:** Useful alongside the primary curriculum but not a substitute for a complete course.

A link being included does not mean every module, license, price, or access condition has been independently audited. Links to documentation portals may require navigation to the relevant page. Official pages are preferred for changing APIs and tools; older resources are retained where foundational explanations remain useful.

## Final Quality Checklist

- [ ] Learning order is logical and prerequisites are identified.
- [ ] Every major stage has learning resources and hands-on work.
- [ ] Core topics lead to an implementation or evaluation task.
- [ ] Projects increase in complexity.
- [ ] Free, paid, open-source, and open-weight resources are distinguished.
- [ ] Dataset and model licenses are reviewed before use.
- [ ] The README is navigable through Markdown anchors.
- [ ] The project includes limitations and evaluation, not just a demo.
- [ ] Resource descriptions are not treated as guarantees of current availability.

## Expanded Free Resource Library — 40 Resources per Subject

This directory provides **40 resource links for each of the 30 subjects below**. Resources are cross-listed when they genuinely support multiple topics. The directory prioritizes official documentation, university course materials, open textbooks, free tutorials, public datasets, interactive practice, and open-source implementations.

**Important cost distinction:** “Free” here means that learning materials or a useful learning component can be accessed without purchasing a course. It does not guarantee a free certificate, unlimited cloud/GPU compute, free hosted inference, commercial-use rights, or unrestricted model licensing. Some providers require a free account; check current terms before use. A link to a dataset or model is not permission to use it for every purpose.

**Use the library efficiently:** for each subject, select one primary course or textbook, one official documentation source, one practice resource, and one implementation/project resource. Treat the rest as alternatives and deeper references. Links are curated from established providers and project documentation; check that pages and terms remain current.


### Python: 40 Resources


1. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Real Python tutorials (free articles)](https://realpython.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [AIMA Python](https://github.com/aimacode/aima-python) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Python](https://docs.python.org/3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Python standard library](https://docs.python.org/3/library/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Python Packaging User Guide](https://packaging.python.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Python Tutor](https://pythontutor.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Papers with Code](https://paperswithcode.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Exercism Python track](https://exercism.org/tracks/python) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Think Python (free book)](https://allendowney.github.io/ThinkPython/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Python Koans](https://github.com/gregmalcolm/python_koans) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Papers with Code datasets](https://paperswithcode.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Paul's Online Math Notes](https://tutorial.math.lamar.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Kaggle Notebooks](https://www.kaggle.com/code) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Data structures and algorithms: 40 Resources


1. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [COCO dataset](https://cocodataset.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Google Research publications](https://research.google/pubs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Hugging Face Datasets](https://huggingface.co/docs/datasets/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Kaggle Datasets](https://www.kaggle.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face Datasets](https://huggingface.co/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Google Research resources](https://research.google/resources/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [CP-Algorithms](https://cp-algorithms.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Papers with Code datasets](https://paperswithcode.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [AI Incident Database](https://incidentdatabase.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [pandas getting started](https://pandas.pydata.org/docs/getting_started/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [pandas](https://pandas.pydata.org/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Mathematics for AI: 40 Resources


1. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [MIT OCW Mathematics for Computer Science](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [NumPy linear algebra](https://numpy.org/doc/stable/reference/routines.linalg.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Khan Academy — Calculus](https://www.khanacademy.org/math/calculus-1) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [OpenStax Calculus](https://openstax.org/subjects/math) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Paul's Online Math Notes](https://tutorial.math.lamar.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [3Blue1Brown — Essence of Calculus](https://www.3blue1brown.com/topics/calculus) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Khan Academy](https://www.khanacademy.org/math) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Linear algebra: 40 Resources


1. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [3Blue1Brown — Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [NumPy linear algebra](https://numpy.org/doc/stable/reference/routines.linalg.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [pgvector](https://github.com/pgvector/pgvector) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Anthropic API documentation](https://docs.anthropic.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Calculus: 40 Resources


1. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [LangChain](https://docs.langchain.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Khan Academy — Calculus](https://www.khanacademy.org/math/calculus-1) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [3Blue1Brown — Essence of Calculus](https://www.3blue1brown.com/topics/calculus) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [OpenStax Calculus](https://openstax.org/subjects/math) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Probability and statistics: 40 Resources


1. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [OpenIntro Statistics](https://www.openintro.org/book/os/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Anthropic API documentation](https://docs.anthropic.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Pydantic documentation](https://docs.pydantic.dev/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Ollama documentation](https://docs.ollama.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [LiteLLM documentation](https://docs.litellm.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### SQL and data engineering: 40 Resources


1. [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [PostgreSQL](https://www.postgresql.org/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [AI Incident Database](https://incidentdatabase.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [pandas getting started](https://pandas.pydata.org/docs/getting_started/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [pandas](https://pandas.pydata.org/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [SQLBolt](https://sqlbolt.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [DuckDB documentation](https://duckdb.org/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [DVC documentation](https://dvc.org/doc) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [COCO dataset](https://cocodataset.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [DVC](https://dvc.org/doc/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Hugging Face Datasets](https://huggingface.co/docs/datasets/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [DVC](https://github.com/iterative/dvc) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Kaggle Datasets](https://www.kaggle.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Hugging Face Datasets](https://huggingface.co/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [DAIR.AI Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Papers with Code datasets](https://paperswithcode.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [OpenAI prompting guide](https://developers.openai.com/api/docs/guides/prompt-engineering) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Classical AI: 40 Resources


1. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [MIT OCW Artificial Intelligence](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Google Research publications](https://research.google/pubs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Google Research resources](https://research.google/resources/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [UNESCO AI ethics](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Machine learning: 40 Resources


1. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [A Course in Machine Learning](https://ciml.info/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Dive into Deep Learning](https://d2l.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Introduction to Statistical Learning](https://www.statlearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [scikit-learn](https://scikit-learn.org/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [scikit-learn](https://github.com/scikit-learn/scikit-learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [NumPy Learn](https://numpy.org/learn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Learn Prompting](https://learnprompting.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Model Context Protocol documentation](https://modelcontextprotocol.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [OpenLearn AI matters](https://www.open.edu/openlearn/education-development/ai-matters) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Fairlearn documentation](https://fairlearn.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [TensorFlow](https://www.tensorflow.org/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Advanced machine learning: 40 Resources


1. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [A Course in Machine Learning](https://ciml.info/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Dive into Deep Learning](https://d2l.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Introduction to Statistical Learning](https://www.statlearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Forecasting: Principles and Practice](https://otexts.com/fpp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Deep learning: 40 Resources


1. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Dive into Deep Learning](https://d2l.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [PyTorch](https://docs.pytorch.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Introduction to Statistical Learning](https://www.statlearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [TensorFlow](https://www.tensorflow.org/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [A Course in Machine Learning](https://ciml.info/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [PyTorch examples](https://github.com/pytorch/examples) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Torchvision](https://pytorch.org/vision/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### PyTorch: 40 Resources


1. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Torchvision](https://pytorch.org/vision/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [PyTorch](https://docs.pytorch.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [PyTorch examples](https://github.com/pytorch/examples) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [TensorFlow](https://www.tensorflow.org/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Real Python tutorials (free articles)](https://realpython.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.



### TensorFlow and Keras: 40 Resources


1. [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [TensorFlow](https://www.tensorflow.org/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Real Python tutorials (free articles)](https://realpython.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Paul's Online Math Notes](https://tutorial.math.lamar.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Computer vision: 40 Resources


1. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Torchvision](https://pytorch.org/vision/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [MIT OCW Mathematics for Computer Science](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-spring-2015/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [COCO dataset](https://cocodataset.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [arXiv computer science AI](https://arxiv.org/list/cs.AI/recent) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.



### NLP: 40 Resources


1. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [NLTK Book](https://www.nltk.org/book/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [spaCy course](https://course.spacy.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Model Context Protocol documentation](https://modelcontextprotocol.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [AI2 AllenNLP resources](https://allenai.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Forecasting: Principles and Practice](https://otexts.com/fpp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Transformers: 40 Resources


1. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Sentence Transformers documentation](https://www.sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Sentence Transformers documentation](https://sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### LLMs: 40 Resources


1. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Anthropic API documentation](https://docs.anthropic.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Ollama documentation](https://docs.ollama.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [LiteLLM documentation](https://docs.litellm.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [LlamaIndex documentation](https://docs.llamaindex.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Meta Llama documentation](https://www.llama.com/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [OpenAI prompting guide](https://developers.openai.com/api/docs/guides/prompt-engineering) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [OpenAI API documentation](https://developers.openai.com/api/docs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [OpenAI evaluation best practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Model Context Protocol documentation](https://modelcontextprotocol.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [OpenAI Spinning Up](https://spinningup.openai.com/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Ollama](https://ollama.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [llama.cpp](https://github.com/ggml-org/llama.cpp) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [OpenAI Cookbook](https://cookbook.openai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Hugging Face Diffusers documentation](https://huggingface.co/docs/diffusers/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Hugging Face TRL documentation](https://huggingface.co/docs/trl/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Hugging Face task guides](https://huggingface.co/tasks) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Whisper repository](https://github.com/openai/whisper) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Hugging Face Datasets](https://huggingface.co/docs/datasets/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Hugging Face Diffusers](https://github.com/huggingface/diffusers) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Hugging Face Datasets](https://huggingface.co/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Hugging Face Spaces](https://huggingface.co/docs/hub/spaces-overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [TRL documentation](https://huggingface.co/docs/trl/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Generative AI: 40 Resources


1. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Model Context Protocol documentation](https://modelcontextprotocol.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Hugging Face Diffusers documentation](https://huggingface.co/docs/diffusers/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face TRL documentation](https://huggingface.co/docs/trl/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Hugging Face task guides](https://huggingface.co/tasks) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Hugging Face Datasets](https://huggingface.co/docs/datasets/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Hugging Face Diffusers](https://github.com/huggingface/diffusers) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Hugging Face Datasets](https://huggingface.co/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Hugging Face Spaces](https://huggingface.co/docs/hub/spaces-overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [TRL documentation](https://huggingface.co/docs/trl/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Prompt engineering: 40 Resources


1. [OpenAI prompting guide](https://developers.openai.com/api/docs/guides/prompt-engineering) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Prompting Guide](https://www.promptingguide.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [DAIR.AI Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Google Gemini prompting strategies](https://ai.google.dev/gemini-api/docs/prompting-strategies) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Learn Prompting](https://learnprompting.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Python Packaging User Guide](https://packaging.python.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Hugging Face task guides](https://huggingface.co/tasks) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Google PAIR Guidebook](https://pair.withgoogle.com/guidebook/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [OpenAI Cookbook](https://cookbook.openai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [OpenAI evaluation best practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Embeddings and vector databases: 40 Resources


1. [Sentence Transformers documentation](https://www.sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [pgvector](https://github.com/pgvector/pgvector) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Sentence Transformers documentation](https://sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Chroma documentation](https://docs.trychroma.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [FAISS documentation](https://faiss.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Qdrant documentation](https://qdrant.tech/documentation/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [AI Incident Database](https://incidentdatabase.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Information retrieval: 40 Resources


1. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Google Research publications](https://research.google/pubs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Google Research resources](https://research.google/resources/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### RAG: 40 Resources


1. [Elasticsearch vector search](https://www.elastic.co/guide/en/elasticsearch/reference/current/knn-search.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [LlamaIndex documentation](https://docs.llamaindex.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Ragas documentation](https://docs.ragas.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [LangChain](https://docs.langchain.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [pgvector](https://github.com/pgvector/pgvector) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Google Research publications](https://research.google/pubs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Google Research resources](https://research.google/resources/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Fine-tuning: 40 Resources


1. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Sentence Transformers documentation](https://www.sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Hugging Face TRL documentation](https://huggingface.co/docs/trl/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Model Context Protocol documentation](https://modelcontextprotocol.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [TRL documentation](https://huggingface.co/docs/trl/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Sentence Transformers documentation](https://sbert.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### AI agents: 40 Resources


1. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [CrewAI documentation](https://docs.crewai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [LangGraph documentation](https://docs.langchain.com/oss/python/langgraph/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [AutoGen documentation](https://microsoft.github.io/autogen/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Microsoft AutoGen repository](https://github.com/microsoft/autogen) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Reinforcement learning: 40 Resources


1. [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Dive into Deep Learning](https://d2l.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Introduction to Statistical Learning](https://www.statlearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [A Course in Machine Learning](https://ciml.info/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Gymnasium documentation](https://gymnasium.farama.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Gymnasium](https://github.com/Farama-Foundation/Gymnasium) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Multimodal AI: 40 Resources


1. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Torchvision tutorials](https://pytorch.org/vision/stable/index.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Torchvision](https://pytorch.org/vision/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Hugging Face Diffusion Models course](https://huggingface.co/learn/diffusion-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Hugging Face Transformers documentation](https://huggingface.co/docs/transformers/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Hugging Face Diffusers documentation](https://huggingface.co/docs/diffusers/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Hugging Face sentence-transformers guide](https://huggingface.co/docs/hub/sentence-transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Hugging Face TRL documentation](https://huggingface.co/docs/trl/index) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [Hugging Face Transformers training guide](https://huggingface.co/docs/transformers/training) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Model cards on Hugging Face](https://huggingface.co/docs/hub/model-cards) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Hugging Face task guides](https://huggingface.co/tasks) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Hugging Face Datasets](https://huggingface.co/docs/datasets/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Hugging Face Transformers](https://github.com/huggingface/transformers) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [Hugging Face Diffusers](https://github.com/huggingface/diffusers) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Hugging Face Datasets](https://huggingface.co/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Hugging Face Spaces](https://huggingface.co/docs/hub/spaces-overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Hugging Face PEFT documentation](https://huggingface.co/docs/peft/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [TRL documentation](https://huggingface.co/docs/trl/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### MLOps and deployment: 40 Resources


1. [Full Stack Deep Learning](https://fullstackdeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Dive into Deep Learning](https://d2l.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/training/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [LangChain learning guides](https://docs.langchain.com/oss/python/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Docker getting started](https://docs.docker.com/get-started/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Docker](https://docs.docker.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [DVC documentation](https://dvc.org/doc) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Introduction to Statistical Learning](https://www.statlearning.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [MLflow RAG tutorial](https://mlflow.org/docs/latest/genai/flavors/langchain/notebooks/langchain-retriever/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [David Silver's Reinforcement Learning course](https://www.davidsilver.uk/teaching/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [MLflow documentation](https://mlflow.org/docs/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [DVC](https://dvc.org/doc/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [FastAPI](https://fastapi.tiangolo.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [A Course in Machine Learning](https://ciml.info/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [DVC](https://github.com/iterative/dvc) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [MLflow](https://github.com/mlflow/mlflow) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [UCI Machine Learning Repository](https://archive.ics.uci.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.



### AI safety and evaluation: 40 Resources


1. [SHAP documentation](https://shap.readthedocs.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [OpenAI evaluation best practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [OWASP GenAI Security Project](https://genai.owasp.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Google Responsible AI](https://ai.google/responsibility/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [NIST AI Resource Center](https://airc.nist.gov/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Weights & Biases course](https://www.wandb.courses/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Microsoft Responsible AI](https://www.microsoft.com/en-us/ai/responsible-ai) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [AI Fairness 360](https://aif360.res.ibm.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.



### Research methodology: 40 Resources


1. [Papers with Code](https://paperswithcode.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Papers with Code datasets](https://paperswithcode.com/datasets) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [arXiv](https://arxiv.org/) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [OpenReview](https://openreview.net/) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [NeurIPS proceedings](https://proceedings.neurips.cc/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [ICML proceedings](https://proceedings.mlr.press/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [Google Research publications](https://research.google/pubs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Google Research resources](https://research.google/resources/) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [Made With ML](https://madewithml.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [arXiv computer science AI](https://arxiv.org/list/cs.AI/recent) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [Anthropic prompt engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [Google PAIR Guidebook](https://pair.withgoogle.com/guidebook/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [Kaggle Notebooks](https://www.kaggle.com/code) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [FAISS](https://github.com/facebookresearch/faiss) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [AIMA Python](https://github.com/aimacode/aima-python) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [Google Dataset Search](https://datasetsearch.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.



### AI infrastructure: 40 Resources


1. [Ollama documentation](https://docs.ollama.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

2. [Docker getting started](https://docs.docker.com/get-started/) — Free learning material, documentation, or practice reference; review current access and usage terms.

3. [Docker](https://docs.docker.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

4. [Google Colab](https://colab.research.google.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

5. [Ollama](https://ollama.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

6. [Google Colab FAQ](https://research.google.com/colaboratory/faq.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

7. [llama.cpp](https://github.com/ggml-org/llama.cpp) — Free learning material, documentation, or practice reference; review current access and usage terms.

8. [Google Machine Learning — introductory courses](https://developers.google.com/machine-learning/) — Free learning material, documentation, or practice reference; review current access and usage terms.

9. [Harvard CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.

10. [The Missing Semester of Your CS Education — MIT](https://missing.csail.mit.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

11. [Python `venv` documentation](https://docs.python.org/3/library/venv.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

12. [The Python Tutorial](https://docs.python.org/3/tutorial/) — Free learning material, documentation, or practice reference; review current access and usage terms.

13. [CS50's Introduction to Programming with Python](https://cs50.harvard.edu/python/) — Free learning material, documentation, or practice reference; review current access and usage terms.

14. [pytest documentation](https://docs.pytest.org/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

15. [MIT OpenCourseWare — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — Free learning material, documentation, or practice reference; review current access and usage terms.

16. [Python `collections` documentation](https://docs.python.org/3/library/collections.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

17. [MIT OpenCourseWare — Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — Free learning material, documentation, or practice reference; review current access and usage terms.

18. [SciPy documentation](https://docs.scipy.org/doc/scipy/) — Free learning material, documentation, or practice reference; review current access and usage terms.

19. [Harvard Stat 110](https://stat110.hsites.harvard.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

20. [SciPy statistics](https://docs.scipy.org/doc/scipy/reference/stats.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

21. [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

22. [Jupyter documentation](https://docs.jupyter.org/en/latest/) — Free learning material, documentation, or practice reference; review current access and usage terms.

23. [Polars user guide](https://docs.pola.rs/) — Free learning material, documentation, or practice reference; review current access and usage terms.

24. [Great Expectations documentation](https://docs.greatexpectations.io/) — Free learning material, documentation, or practice reference; review current access and usage terms.

25. [Berkeley CS188 — Introduction to AI](https://inst.eecs.berkeley.edu/~cs188/) — Free learning material, documentation, or practice reference; review current access and usage terms.

26. [AIMA resources](https://aima.cs.berkeley.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

27. [Kaggle Learn](https://www.kaggle.com/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

28. [Google ML advanced courses](https://developers.google.com/machine-learning) — Free learning material, documentation, or practice reference; review current access and usage terms.

29. [XGBoost documentation](https://xgboost.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

30. [LightGBM documentation](https://lightgbm.readthedocs.io/en/stable/) — Free learning material, documentation, or practice reference; review current access and usage terms.

31. [Evidently documentation](https://docs.evidentlyai.com/) — Free learning material, documentation, or practice reference; review current access and usage terms.

32. [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Free learning material, documentation, or practice reference; review current access and usage terms.

33. [Stanford CS231n](https://cs231n.stanford.edu/) — Free learning material, documentation, or practice reference; review current access and usage terms.

34. [OpenCV tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html) — Free learning material, documentation, or practice reference; review current access and usage terms.

35. [Hugging Face computer vision course materials](https://huggingface.co/learn) — Free learning material, documentation, or practice reference; review current access and usage terms.

36. [Stanford CS224N](https://web.stanford.edu/class/cs224n/) — Free learning material, documentation, or practice reference; review current access and usage terms.

37. [Hugging Face NLP course](https://huggingface.co/learn/nlp-course) — Free learning material, documentation, or practice reference; review current access and usage terms.

38. [Speech and Language Processing — Jurafsky and Martin](https://web.stanford.edu/~jurafsky/slp3/) — Free learning material, documentation, or practice reference; review current access and usage terms.

39. [Stanford CS25: Transformers United](https://web.stanford.edu/class/cs25/) — Free learning material, documentation, or practice reference; review current access and usage terms.

40. [Mistral documentation](https://docs.mistral.ai/) — Free learning material, documentation, or practice reference; review current access and usage terms.



# Disclaimer

External resources are maintained by their respective owners and may change, move, become unavailable, or alter pricing, APIs, model access, and licensing. Inclusion does not imply endorsement. Verify the current terms and requirements before use. AI-generated outputs can be incorrect, incomplete, biased, or unsafe; evaluate them before relying on them in professional or high-impact settings. Research papers and preprints may be preliminary or subject to revision.

**Last reviewed:** 2026-10-25
