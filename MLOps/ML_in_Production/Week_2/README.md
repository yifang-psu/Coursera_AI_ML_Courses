### Week 2: Select and Train a Model

* **What is this week's course about?**
  * This week is about model strategies and key challenges in model development. It covers error analysis and strategies to work with different data types. It also addresses how to cope with class imbalance and highly skewed data sets.

* **Learning Objectives:**
  * Identify the key challenges in model development.
  * Describe how performance on a small set of disproportionately important examples may be more crucial than performance on the majority of examples.
  * Explain how rare classes in your training data can affect performance.
  * Define three ways of establishing a baseline for your performance.
  * Define structured vs. unstructured data.
  * Identify when to consider deployment constraints when choosing a model.
  * List the steps involved in getting started with ML modeling.
  * Describe the iterative process for error analysis.
  * Identify the key factors in deciding what to prioritize when working to improve model accuracy.
  * Describe methods you might use for data augmentation given audio data vs. image data.
  * Explain the problems you can have training on a highly skewed dataset.
  * Identify a use case in which adding more data to your training dataset could actually hurt performance.
  * Describe the key components of experiment tracking.

* **Reading List:**
  * [Establishing a baseline](https://blog.ml.cmu.edu/2020/08/31/3-baselines/)
  * [Error analysis](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/responsible-machine-learning-with-error-analysis/ba-p/2141774)
  * [Experiment tracking](https://neptune.ai/blog/ml-experiment-tracking)

* **Research Paper Reading List:**
  * [Brundage, M., Avin, S., Wang, J., Belfield, H., Krueger, G., Hadfield, G., … Anderljung, M. (n.d.). Toward trustworthy AI development: Mechanisms for supporting verifiable claim](http://arxiv.org/abs/2004.07213v2)
  * [Nakkiran, P., Kaplun, G., Bansal, Y., Yang, T., Barak, B., & Sutskever, I. (2019). Deep double descent: Where bigger models and more data hurt](http://arxiv.org/abs/1912.02292)
  
* **Programming Assignment:**  
  * [C1W2_Ungraded_Lab_Redirect](https://colab.research.google.com/github/https-deeplearning-ai/MLEP-public/blob/main/course1/week2-ungraded-lab/C1W2_Ungraded_Lab_Birds_Cats_Dogs.ipynb)
  * Alternatively, the [ungraded ipynb file is here](https://github.com/yifang-psu/Coursera_AI_ML_Courses/blob/main/MLOps/ML_in_Production/Week_2/C1W2_Ungraded_Lab_Birds_Cats_Dogs.ipynb)
  * In this ungraded lab you will get hands on experience working with data at various levels. In particular you will:
    - Manually move images around the filesystem so they are stored in a structure suitable for model training.
    - Clean up the dataset as it presents some corrupted images and other issues.
    - See how class imbalance negatively affects model evaluation.
    - Solve overfitting problems by using Data Augmentation techniques.
