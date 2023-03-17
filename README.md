# MLFlow Recitation
Code for the 03/16 MlFlow Recitation.


Accompanying Colab Notebook: https://colab.research.google.com/drive/1hPxMl7u73Nq0T_7_apE4-AkQlToU2f6G?usp=sharing

From https://github.com/mlflow/mlflow/tree/master/examples/multistep_workflow

This MLproject aims to be a fully self-contained example of how to chain together multiple different MLflow runs which each encapsulate a transformation or training step, allowing a clear definition of the interface between the steps, as well as allowing for caching and reuse of the intermediate results.

At a high level, our goal is to predict users' ratings of movie given a history of their ratings for other movies. This example is based on [this webinar](https://www.databricks.com/blog/2018/07/13/scalable-end-to-end-deep-learning-using-tensorflow-and-databricks-on-demand-webinar-and-faq-now-available.html) by @brookewenig and @smurching.

![image](https://user-images.githubusercontent.com/14112602/225777789-ac07c66e-37bc-49f0-8156-26d173f81fc8.png)

