# Awesome Software Engineering for Machine Learning [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/SE-ML/awesome-seml/blob/master/contributing.md)

Software Engineering for Machine Learning are techniques and guidelines for building ML applications that do not concern the core ML problem  -- e.g. the development of new algorithms -- but rather the surrounding activities like data ingestion, coding, testing, versioning, deployment, quality control, and team collaboration.
Good software engineering practices enhance development, deployment and maintenance of production level applications using machine learning components.

⭐ Must-read

🎓 Scientific publication


<br>
Based on this literature, we compiled a survey on the adoption of software engineering practices for applications with machine learning components. 

This survey research is described in the publication [Adoption and Effects of Software Engineering Best Practices in Machine Learning](https://arxiv.org/abs/2007.14130).

Feel free to [take and share the survey](https://se-ml.github.io/survey) and to [read more](https://se-ml.github.io/practices)!



## Contents

- [Broad Overviews](#broad-overviews)
- [Data Management](#data-management)
- [Model Training](#model-training)
- [Deployment and Operation](#deployment-and-operation)
- [Social Aspects](#social-aspects)
- [Governance](#governance)
- [Tooling](#tooling)

## Broad Overviews

These resources cover all aspects.

- [Best Practices for Machine Learning Applications](https://pdfs.semanticscholar.org/2869/6212a4a204783e9dd3953f06e103c02c6972.pdf)
- [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) 🎓⭐
- [Machine Learning Engineering Best Practices](https://se-ml.github.io/practices/) ⭐
- [Rules of Machine Learning: Best Practices for ML Engineering](https://developers.google.com/machine-learning/guides/rules-of-ml) ⭐
- [wtware Engineering for Machine Learning: A Case Study](https://www.microsoft.com/en-us/research/publication/software-engineering-for-machine-learning-a-case-study/) 🎓⭐


## Data Management

How to manage the data sets you use in machine learning.

- [A Survey on Data Collection for Machine Learning A Big Data - AI Integration Perspective_2019](https://deepai.org/publication/a-survey-on-data-collection-for-machine-learning-a-big-data-ai-integration-perspective) 🎓
- [Automating Large-Scale Data Quality Verification](http://www.vldb.org/pvldb/vol11/p1781-schelter.pdf) 🎓
- [Data management challenges in production machine learning](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46178.pdf)
- [How to organize data labelling for ML](https://www.altexsoft.com/blognp/datascience/how-to-organize-data-labeling-for-machine-learning-approaches-and-tools/)
- [The curse of big data labeling and three ways to solve it](https://aws.amazon.com/blogs/apn/the-curse-of-big-data-labeling-and-three-ways-to-solve-it/)
- [The Data Linter: Lightweight, Automated Sanity Checking for ML Data Sets](http://learningsys.org/nips17/assets/papers/paper_19.pdf) 🎓
- [The ultimate guide to data labeling for ML](https://www.cloudfactory.com/data-labeling-guide)


## Model Training

How to organize your model training experiments.

- [10 Best Practices for Deep Learning](https://nanonets.com/blog/10-best-practices-deep-learning/#track-model-experiments)
- [Apples-to-apples in cross-validation studies: pitfalls in classifier performance measurement](https://dl.acm.org/doi/abs/10.1145/1882471.1882479) 🎓
- [How do you manage your Machine Learning Experiments?](https://medium.com/@hadyelsahar/how-do-you-manage-your-machine-learning-experiments-ab87508348ac)
- [Machine Learning Testing: Survey, Landscapes and Horizons](https://arxiv.org/pdf/1906.10742.pdf) 🎓
- [Nitpicking Machine Learning Technical Debt](https://matthewmcateer.me/blog/machine-learning-technical-debt/)
- [On Comparing Classifiers: Pitfalls to Avoid and a Recommended Approach](https://link.springer.com/article/10.1023/A:1009752403260) 🎓⭐
- [On human intellect and machine failures: Troubleshooting integrative machine learning systems](https://arxiv.org/pdf/1611.08309.pdf) 🎓
- [Pitfalls and Best Practices in Algorithm Configuration](https://www.jair.org/index.php/jair/article/download/11420/26488/) 🎓
- [Pitfalls of supervised feature selection](https://academic.oup.com/bioinformatics/article/26/3/440/213774) 🎓
- [Preparing and Architecting for Machine Learning](https://www.gartner.com/en/documents/3889770/preparing-and-architecting-for-machine-learning-2018-upd)
- [Preliminary Systematic Literature Review of Machine Learning System Development Process](https://arxiv.org/abs/1910.05528) 🎓
- [Software development best practices in a deep learning environment](https://towardsdatascience.com/software-development-best-practices-in-a-deep-learning-environment-a1769e9859b1)
- [Testing and Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging)
- [What Went Wrong and Why? Diagnosing Situated Interaction Failures in the Wild](https://www.microsoft.com/en-us/research/publication/what-went-wrong-and-why-diagnosing-situated-interaction-failures-in-the-wild/) 🎓


## Deployment and Operation

How to deploy and operate your models in a production environment.

- [Best Practices in Machine Learning Infrastructure](https://algorithmia.com/blog/best-practices-in-machine-learning-infrastructure)
- [Continuous Delivery for Machine Learning](https://martinfowler.com/articles/cd4ml.html) ⭐
- [Continuous Training for Production ML in the TensorFlow Extended (TFX) Platform](https://www.usenix.org/system/files/opml19papers-baylor.pdf) 🎓
- [Fairness Indicators: Scalable Infrastructure for Fair ML Systems](https://ai.googleblog.com/2019/12/fairness-indicators-scalable.html) 🎓
- [Machine Learning Logistics](https://mapr.com/ebook/machine-learning-logistics/)
- [Machine learning: Moving from experiments to production](https://blog.codecentric.de/en/2019/03/machine-learning-experiments-production/)
- [ML Ops: Machine Learning as an engineered disciplined](https://towardsdatascience.com/ml-ops-machine-learning-as-an-engineering-discipline-b86ca4874a3f)
- [Model Governance Reducing the Anarchy of Production](https://www.usenix.org/conference/atc18/presentation/sridhar) 🎓
- [ModelOps: Cloud-based lifecycle management for reliable and trusted AI](http://hummer.io/docs/2019-ic2e-modelops.pdf)
- [Operational Machine Learning](https://www.kdnuggets.com/2018/04/operational-machine-learning-successful-mlops.html)
- [Scaling Machine Learning as a Service](http://proceedings.mlr.press/v67/li17a/li17a.pdf)🎓
- [TFX: A tensorflow-based Production-Scale ML Platform](https://dl.acm.org/doi/pdf/10.1145/3097983.3098021?download=true) 🎓
- [The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction](https://research.google/pubs/pub46555/) 🎓
- [Versioning for end-to-end machine learning pipelines](https://doi.org/10.1145/3076246.3076248) 🎓



## Social Aspects

How to organize teams and projects to ensure effective collaboration and accountability.

- [Data Scientists in Software Teams: State of the Art and Challenges](http://web.cs.ucla.edu/~miryung/Publications/tse2017-datascientists.pdf) 🎓
- [Machine Learning Interviews](https://github.com/chiphuyen/machine-learning-systems-design/blob/master/build/build1/consolidated.pdf)
- [Managing Machine Learning Projects](https://d1.awsstatic.com/whitepapers/aws-managing-ml-projects.pdf)
- [Principled Machine Learning: Practices and Tools for Efficient Collaboration](https://dev.to/robogeek/principled-machine-learning-4eho)


## Governance
- [Responsible AI practices](https://ai.google/responsibilities/responsible-ai-practices/) ⭐
- [Toward Trustworthy AI Development: Mechanisms for Supporting Verifiable Claims](https://arxiv.org/abs/2004.07213)

## Tooling

Tooling can make your life easier.

We only share open source tools, or commercial platforms that offer substantial free packages for research.

- [Airflow](https://airflow.apache.org/) - Programmatically author, schedule and monitor workflows.
- [Auto-PyTorch](https://github.com/automl/Auto-PyTorch) - Automatic architecture search and hyperparameter optimization for PyTorch.
- [Ax](https://ax.dev) - Optimize any kind of experiment, including machine learning experiments, A/B tests, and simulations.
- [Data Version Control (DVC)](https://dvc.org/) - DVC is a data and ML experiments management tool.
- [Facets Overview / Facets Dive](https://pair-code.github.io/facets/) - Robust visualizations to aid in understanding machine learning datasets.
- [Git Large File System (LFS)](https://git-lfs.github.com/) - Replaces large files such as datasets with text pointers inside Git.
- [HParams](https://github.com/PetrochukM/HParams) - A thoughtful approach to configuration management for machine learning projects.
- [Kubeflow](https://www.kubeflow.org/) - A platform for data scientists who want to build and experiment with ML pipelines.
- [Label Studio](https://github.com/heartexlabs/label-studio) - A multi-type data labeling and annotation tool with standardized output format.
- [MLFlow](https://mlflow.org/) - Manage the ML lifecycle, including experimentation, deployment, and a central model registry.
- [Neptune.ai](https://neptune.ai/) - Experiment tracking tool bringing organization and collaboration to data science projects.
- [Neuraxle](https://github.com/Neuraxio/Neuraxle) -  Sklearn-like framework for hyperparameter tuning and AutoML in deep learning projects.
- [OpenML](https://www.openml.org) - An inclusive movement to build an open, organized, online ecosystem for machine learning.
- [Spark Machine Learning](https://spark.apache.org/mllib/) - Spark’s ML library consisting of common learning algorithms and utilities.
- [Sacred](https://github.com/IDSIA/sacred) - A tool to help you configure, organize, log and reproduce experiments.
- [TensorBoard](https://www.tensorflow.org/tensorboard/) - TensorFlow's Visualization Toolkit.
- [Tensorflow Extended (TFX)](https://www.tensorflow.org/tfx/) - An end-to-end platform for deploying production ML pipelines.
- [Weights & Biases](https://www.wandb.com/) - Experiment tracking, model optimization, and dataset versioning.


## Contribute

Contributions welcomed! Read the [contribution guidelines](contributing.md) first
