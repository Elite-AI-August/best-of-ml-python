<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Machine Learning with Python
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome machine learning Python libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://github.com/ml-tooling/best-of" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-900-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-ml-python/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-ml-python?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 900 awesome open-source projects with a total of 3.4M stars grouped into 34 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-ml-python/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Machine Learning Frameworks](#machine-learning-frameworks) _56 projects_
- [Data Visualization](#data-visualization) _51 projects_
- [Text Data & NLP](#text-data--nlp) _96 projects_
- [Image Data](#image-data) _60 projects_
- [Graph Data](#graph-data) _36 projects_
- [Audio Data](#audio-data) _28 projects_
- [Geospatial Data](#geospatial-data) _22 projects_
- [Financial Data](#financial-data) _25 projects_
- [Time Series Data](#time-series-data) _26 projects_
- [Medical Data](#medical-data) _19 projects_
- [Tabular Data](#tabular-data) _5 projects_
- [Optical Character Recognition](#optical-character-recognition) _12 projects_
- [Data Containers & Structures](#data-containers--structures) _0 projects_
- [Data Loading & Extraction](#data-loading--extraction) _2 projects_
- [Web Scraping & Crawling](#web-scraping--crawling) _1 projects_
- [Data Pipelines & Streaming](#data-pipelines--streaming) _43 projects_
- [Distributed Machine Learning](#distributed-machine-learning) _33 projects_
- [Hyperparameter Optimization & AutoML](#hyperparameter-optimization--automl) _47 projects_
- [Reinforcement Learning](#reinforcement-learning) _23 projects_
- [Recommender Systems](#recommender-systems) _16 projects_
- [Privacy Machine Learning](#privacy-machine-learning) _6 projects_
- [Workflow & Experiment Tracking](#workflow--experiment-tracking) _39 projects_
- [Model Serialization & Deployment](#model-serialization--deployment) _16 projects_
- [Model Interpretability](#model-interpretability) _52 projects_
- [Vector Similarity Search (ANN)](#vector-similarity-search-ann) _12 projects_
- [Probabilistics & Statistics](#probabilistics--statistics) _22 projects_
- [Adversarial Robustness](#adversarial-robustness) _9 projects_
- [GPU Utilities](#gpu-utilities) _18 projects_
- [Tensorflow Utilities](#tensorflow-utilities) _15 projects_
- [Jax Utilities](#jax-utilities) _2 projects_
- [Sklearn Utilities](#sklearn-utilities) _17 projects_
- [Pytorch Utilities](#pytorch-utilities) _32 projects_
- [Database Clients](#database-clients) _1 projects_
- [Others](#others) _61 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow related project
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn related project
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; PyTorch related project
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet related project
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark related project
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle related project
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas related project
- <img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Jax related project

<br>

## Machine Learning Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose machine learning and deep learning frameworks._

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇55 ·  ⭐ 170K) - An Open Source Machine Learning Framework for Everyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 4K · 🔀 87K · 📦 200K · 📋 35K - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 18M / month · 📦 14K · ⏱️ 23.05.2022):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 3.3M · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 66M · ⭐ 2K · ⏱️ 02.06.2022):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇51 ·  ⭐ 50K) - scikit-learn: machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 2.6K · 🔀 23K · 📥 800 · 📦 360K · 📋 10K - 22% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 35M / month · 📦 25K · ⏱️ 19.05.2022):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 13M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇49 ·  ⭐ 56K) - Tensors and Dynamic neural networks in Python with strong GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 3.3K · 🔀 16K · 📥 3.6K · 📋 28K - 35% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 10M / month · 📦 7K · ⏱️ 10.03.2022):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 17M · ⏱️ 10.03.2022):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥇44 ·  ⭐ 55K) - Deep Learning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1.1K · 🔀 19K · 📋 11K - 2% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 11M / month · 📦 300 · ⏱️ 13.05.2022):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 2.3M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇44 ·  ⭐ 23K) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 560 · 🔀 8.4K · 📥 4.2K · 📦 32K · 📋 4.5K - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 10M / month · 📦 1.3K · ⏱️ 09.05.2022):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2.7M · ⏱️ 17.02.2022):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥇44 ·  ⭐ 18K) - Composable transformations of Python+NumPy programs: differentiate,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 400 · 🔀 1.6K · 📦 4.5K · 📋 3.4K - 32% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 440K / month · 📦 300 · ⏱️ 16.05.2022):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 320K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/pytorch-lightning">pytorch-lightning</a></b> (🥈43 ·  ⭐ 19K) - The lightweight PyTorch wrapper for high-performance.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/pytorch-lightning) (👨‍💻 680 · 🔀 2.4K · 📥 6.9K · 📦 9.2K · 📋 5.1K - 9% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 4.3M / month · 📦 380 · ⏱️ 01.06.2022):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 450K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥈43 ·  ⭐ 7.4K) - Statsmodels: statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 370 · 🔀 2.4K · 📥 26 · 📦 64K · 📋 4.8K - 47% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 12M / month · 📦 4.5K · ⏱️ 08.02.2022):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 6.2M · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈42 ·  ⭐ 33K) - Apache Spark Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 2.7K · 🔀 26K · ⏱️ 02.06.2022):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 21M / month · 📦 830 · ⏱️ 18.02.2022):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1.7M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥈42 ·  ⭐ 14K) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 260 · 🔀 3.5K · 📥 150K · 📦 13K · 📋 2.7K - 8% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 7.4M / month · 📦 630 · ⏱️ 07.01.2022):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 1M · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈41 ·  ⭐ 22K · 📈) - The fastai deep learning library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 610 · 🔀 7.2K · 📦 10K · 📋 1.6K - 7% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 300K / month · 📦 300 · ⏱️ 01.05.2022):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈41 ·  ⭐ 18K) - PArallel Distributed Deep LEarning: Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 740 · 🔀 4.5K · 📥 15K · 📦 120 · 📋 16K - 18% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 100K / month · 📦 48 · ⏱️ 09.05.2022):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈40 ·  ⭐ 6.5K) - A fast, scalable, high performance Gradient Boosting on Decision.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 990 · 🔀 1K · 📥 81K · 📋 1.8K - 21% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 2.6M / month · 📦 230 · ⏱️ 19.05.2022):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 1M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈39 ·  ⭐ 20K · 📉) - Lightweight, Portable, Flexible Distributed/Mobile Deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 970 · 🔀 6.9K · 📥 25K · 📋 9.7K - 20% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 350K / month · 📦 280 · ⏱️ 17.05.2022):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 7.6K · 📦 5 · ⏱️ 02.05.2022):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈38 ·  ⭐ 15K) - Cloud-native neural search framework for kind of data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 150 · 🔀 1.9K · 📦 290 · 📋 1.5K - 4% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 60K / month · 📦 2 · ⏱️ 02.06.2022):
	```
	pip install jina
	```
- [Conda](https://anaconda.org/conda-forge/jina-core) (📥 5.8K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge jina-core
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 1.1M · ⭐ 7 · ⏱️ 02.06.2022):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈37 ·  ⭐ 9.6K · 💤) - Theano was a Python library that allows you to define, optimize, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.5K · 📦 13K · 📋 2.8K - 24% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/theano) (📥 250K / month · 📦 2.8K · ⏱️ 27.07.2020):
	```
	pip install theano
	```
- [Conda](https://anaconda.org/conda-forge/theano) (📥 2M · ⏱️ 16.03.2022):
	```
	conda install -c conda-forge theano
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈37 ·  ⭐ 2.5K) - A refreshing functional take on deep learning, compatible with your favorite.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 52 · 🔀 250 · 📦 22K · 📋 130 - 17% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 6.2M / month · 📦 620 · ⏱️ 02.06.2022):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 2M · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥈36 ·  ⭐ 19K) - Apache Flink Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.5K · 🔀 11K · ⏱️ 02.06.2022):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 17K / month · 📦 15 · ⏱️ 26.04.2022):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈36 ·  ⭐ 3K) - Flax is a neural network library for JAX that is designed for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 150 · 🔀 340 · 📥 42 · 📦 980 · 📋 520 - 22% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax) (📥 200K / month · 📦 69 · ⏱️ 23.05.2022):
	```
	pip install flax
	```
- [Conda](https://anaconda.org/conda-forge/flax) (📥 4.3K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge flax
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈35 ·  ⭐ 8K) - Vowpal Wabbit is a machine learning system which pushes the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 320 · 🔀 1.8K · 📋 1.2K - 11% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 60K / month · 📦 30 · ⏱️ 06.04.2022):
	```
	pip install vowpalwabbit
	```
- [Conda](https://anaconda.org/conda-forge/vowpalwabbit) (📥 61K · ⏱️ 07.04.2022):
	```
	conda install -c conda-forge vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈35 ·  ⭐ 5.7K) - A flexible framework of neural networks for deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 320 · 🔀 1.4K · 📦 2.6K · 📋 2K - 0% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 20K / month · 📦 400 · ⏱️ 05.01.2022):
	```
	pip install chainer
	```
- [Conda](https://anaconda.org/conda-forge/chainer) (📥 7.7K · ⏱️ 21.01.2022):
	```
	conda install -c conda-forge chainer
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥈33 ·  ⭐ 8.3K) - Data-centric declarative deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 120 · 🔀 980 · 📦 120 · 📋 750 - 27% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 3.6K / month · 📦 9 · ⏱️ 23.05.2022):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥈33 ·  ⭐ 590) - TensorFlow ROCm port. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 4K · 🔀 68 · 📥 20 · 📋 330 - 17% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 13K / month · 📦 5 · ⏱️ 11.04.2022):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥉32 ·  ⭐ 11K · 💤) - Turi Create simplifies the development of custom machine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/turicreate) (👨‍💻 85 · 🔀 1.1K · 📥 6.1K · 📦 310 · 📋 1.8K - 27% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/apple/turicreate
	```
- [PyPi](https://pypi.org/project/turicreate) (📥 31K / month · 📦 19 · ⏱️ 30.09.2020):
	```
	pip install turicreate
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉32 ·  ⭐ 6.2K) - A Neural Net Training Interface on TensorFlow, with focus.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 58 · 🔀 1.8K · 📥 130 · 📦 1K · 📋 1.3K - 0% open · ⏱️ 04.05.2022):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 18K / month · 📦 46 · ⏱️ 22.01.2021):
	```
	pip install tensorpack
	```
- [Conda](https://anaconda.org/conda-forge/tensorpack) (📥 1.3K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉32 ·  ⭐ 4K) - mlpack: a scalable C++ machine learning library --. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mlpack/mlpack) (👨‍💻 290 · 🔀 1.4K · 📋 1.5K - 6% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/mlpack/mlpack
	```
- [PyPi](https://pypi.org/project/mlpack) (📥 200 / month · 📦 1 · ⏱️ 28.10.2020):
	```
	pip install mlpack
	```
- [Conda](https://anaconda.org/conda-forge/mlpack) (📥 100K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge mlpack
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥉32 ·  ⭐ 4K) - High-level library to help with training and evaluating neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 170 · 🔀 540 · 📋 1.1K - 12% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 170K / month · 📦 83 · ⏱️ 02.06.2022):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 89K · ⏱️ 04.05.2022):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥉31 ·  ⭐ 9.3K) - TensorFlow-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/sonnet) (👨‍💻 53 · 🔀 1.3K · 📦 850 · 📋 180 - 13% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 22K / month · 📦 52 · ⏱️ 27.03.2020):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 14K · ⏱️ 14.11.2020):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥉31 ·  ⭐ 5.1K) - Deep learning operations reinvented (for pytorch, tensorflow, jax and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 17 · 🔀 220 · 📦 2.9K · 📋 110 - 30% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 3.7M / month · 📦 200 · ⏱️ 04.03.2022):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 16K · ⏱️ 04.03.2022):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉31 ·  ⭐ 1.9K) - JAX-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/dm-haiku) (👨‍💻 61 · 🔀 150 · 📦 450 · 📋 160 - 22% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
- [PyPi](https://pypi.org/project/dm-haiku) (📥 94K / month · 📦 30 · ⏱️ 14.02.2022):
	```
	pip install dm-haiku
	```
- [Conda](https://anaconda.org/conda-forge/dm-haiku) (📥 2.8K · ⏱️ 14.02.2022):
	```
	conda install -c conda-forge dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉31 ·  ⭐ 1K) - ktrain is a Python library that makes deep learning and AI more.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 15 · 🔀 240 · 📦 290 · ⏱️ 22.05.2022):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 28K / month · 📦 3 · ⏱️ 20.05.2022):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥉30 ·  ⭐ 3.3K) - DyNet: The Dynamic Neural Network Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/clab/dynet) (👨‍💻 160 · 🔀 700 · 📥 5.9K · 📦 210 · 📋 920 - 28% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/clab/dynet
	```
- [PyPi](https://pypi.org/project/dyNET) (📥 22K / month · 📦 28 · ⏱️ 21.10.2020):
	```
	pip install dyNET
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉30 ·  ⭐ 2.5K) - Neural Network Libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 66 · 🔀 320 · 📥 540 · 📋 80 - 41% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 3.4K / month · 📦 53 · ⏱️ 01.05.2022):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉29 ·  ⭐ 4.5K) - A scikit-learn compatible neural network library that wraps.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 49 · 🔀 300 · 📦 510 · 📋 440 - 11% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 22K / month · 📦 33 · ⏱️ 31.10.2021):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 550K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉26 ·  ⭐ 1.8K) - Fast and Easy Infinite Neural Networks in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 22 · 🔀 200 · 📥 230 · 📦 37 · 📋 120 - 35% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 2.8K / month · 📦 1 · ⏱️ 23.02.2022):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉24 ·  ⭐ 4.6K) - MACE is a deep learning inference framework optimized for mobile.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XiaoMi/mace) (👨‍💻 63 · 🔀 800 · 📥 1.4K · 📋 670 - 7% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/XiaoMi/mace
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉23 ·  ⭐ 1.4K) - fklearn: Functional Machine Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 43 · 🔀 160 · 📦 12 · 📋 45 - 51% open · ⏱️ 18.04.2022):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn) (📥 6K / month · ⏱️ 30.12.2021):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/towhee-io/towhee">Towhee</a></b> (🥉23 ·  ⭐ 510) - A framework that provides a simple API for developing ML-driven data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/towhee-io/towhee) (👨‍💻 26 · 🔀 91 · 📥 17 · 📋 380 - 12% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/towhee-io/towhee
	```
- [PyPi](https://pypi.org/project/towhee) (📥 510 / month · ⏱️ 13.05.2022):
	```
	pip install towhee
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉22 ·  ⭐ 680) - Machine learning framework for both deep learning and traditional.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 31 · 🔀 110 · 📋 75 - 38% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/neoml-lib/neoml
	```
- [PyPi](https://pypi.org/project/neoml) (📥 390 / month · ⏱️ 31.05.2022):
	```
	pip install neoml
	```
</details>
<details><summary><b><a href="https://github.com/google/objax">Objax</a></b> (🥉21 ·  ⭐ 690) - Objax is a machine learning framework that provides an Object.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/objax) (👨‍💻 22 · 🔀 59 · 📦 21 · 📋 100 - 42% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/google/objax
	```
- [PyPi](https://pypi.org/project/objax) (📥 360 / month · 📦 2 · ⏱️ 31.01.2022):
	```
	pip install objax
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉20 ·  ⭐ 1.4K) - ThunderSVM: A Fast SVM Library on GPUs and CPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 34 · 🔀 190 · 📥 2.4K · 📋 210 - 29% open · ⏱️ 09.04.2022):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 890 / month · ⏱️ 13.03.2020):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/serengil/chefboost">chefboost</a></b> (🥉20 ·  ⭐ 330) - A Lightweight Decision Tree Framework supporting regular algorithms:.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/chefboost) (👨‍💻 6 · 🔀 87 · 📦 23 · 📋 29 - 17% open · ⏱️ 21.05.2022):

	```
	git clone https://github.com/serengil/chefboost
	```
- [PyPi](https://pypi.org/project/chefboost) (📥 700 / month · ⏱️ 16.02.2022):
	```
	pip install chefboost
	```
</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉18 ·  ⭐ 370) - A High Level API for Deep Learning in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/poets-ai/elegy) (👨‍💻 17 · 🔀 25 · 📋 96 - 31% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/poets-ai/elegy
	```
- [PyPi](https://pypi.org/project/elegy) (📥 720 / month · ⏱️ 22.04.2022):
	```
	pip install elegy
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈37 ·  ⭐ 11K) - A toolkit for making real world machine learning and data analysis.. <code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code>
- <b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉32 ·  ⭐ 9.6K · 💀) - Deep learning library featuring a higher-level API for TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉31 ·  ⭐ 17K · 💀) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉28 ·  ⭐ 7.2K) - In-Database Machine Learning. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉28 ·  ⭐ 6.3K · 💀) - Numenta Platform for Intelligent Computing is an implementation.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉28 ·  ⭐ 3.8K · 💀) - Lightweight library to build and train neural networks in Theano. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉26 ·  ⭐ 2.9K · 💀) - Unified and efficient Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉25 ·  ⭐ 3K · 💀) - High performance, easy-to-use, and scalable machine learning (ML).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉24 ·  ⭐ 710 · 💀) - NeuPy is a Tensorflow based python library for prototyping and building.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉23 ·  ⭐ 3.9K · 💀) - Intel Nervana reference deep learning framework committed to best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉21 ·  ⭐ 630 · 💀) - torchbearer: A model fitting library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉16 ·  ⭐ 620 · 💀) - ThunderGBM: Fast GBDTs and Random Forests on GPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉15 ·  ⭐ 3.8K · 💀) - Learning embeddings for classification, retrieval and ranking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose and task-specific data visualization libraries._

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇49 ·  ⭐ 16K) - matplotlib: plotting with Python. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.4K · 🔀 6.4K · 📦 570K · 📋 8.9K - 20% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 29M / month · 📦 55K · ⏱️ 03.05.2022):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 12M · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥇43 ·  ⭐ 16K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 600 · 🔀 3.9K · 📦 52K · 📋 6.9K - 10% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 2.6M / month · 📦 3.5K · ⏱️ 18.05.2022):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 7.4M · ⏱️ 19.05.2022):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇43 ·  ⭐ 9.5K) - Statistical data visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 170 · 🔀 1.6K · 📥 220 · 📦 160K · 📋 2K - 5% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 10M / month · 📦 8.8K · ⏱️ 16.08.2021):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 3.9M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇42 ·  ⭐ 12K) - The interactive graphing library for Python (includes Plotly Express). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 200 · 🔀 2.1K · 📦 10 · 📋 2.4K - 49% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly) (📥 7.7M / month · 📦 4K · ⏱️ 11.05.2022):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 2.6M · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge plotly
	```
- [npm](https://www.npmjs.com/package/plotlywidget) (📥 45K / month · 📦 4 · ⏱️ 12.01.2021):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇39 ·  ⭐ 17K) - Analytical Web Apps for Python, R, Julia, and Jupyter. No JavaScript Required. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 120 · 🔀 1.7K · 📦 190 · 📋 1.3K - 47% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 880K / month · 📦 1.2K · ⏱️ 11.05.2022):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 470K · ⏱️ 12.05.2022):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/ydataai/pandas-profiling">pandas-profiling</a></b> (🥇38 ·  ⭐ 9K) - Create HTML profiling reports from pandas DataFrame.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ydataai/pandas-profiling) (👨‍💻 88 · 🔀 1.3K · 📦 8K · 📋 580 - 19% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/ydataai/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.1M / month · 📦 160 · ⏱️ 27.09.2021):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 210K · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇38 ·  ⭐ 7.5K · 📉) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 140 · 🔀 660 · 📦 28K · 📋 1.6K - 14% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 8.9M / month · 📦 340 · ⏱️ 29.12.2021):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 1.2M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈35 ·  ⭐ 2.2K) - With Holoviews, your data visualizes itself. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 120 · 🔀 360 · 📋 2.8K - 31% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 320K / month · 📦 220 · ⏱️ 26.05.2022):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 730K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge holoviews
	```
- [npm](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 1.5K / month · ⏱️ 24.05.2020):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈35 ·  ⭐ 1.2K) - Simple Python interface for Graphviz. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 18 · 🔀 180 · 📦 32K · 📋 140 - 4% open · ⏱️ 17.04.2022):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 11M / month · 📦 3K · ⏱️ 16.04.2022):
	```
	pip install graphviz
	```
- [Conda](https://anaconda.org/anaconda/python-graphviz) (📥 21K · ⏱️ 04.02.2021):
	```
	conda install -c anaconda python-graphviz
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈34 ·  ⭐ 12K) - Python Echarts Plotting Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 30 · 🔀 2.7K · 📦 2.3K · 📋 1.6K - 0% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts) (📥 94K / month · 📦 220 · ⏱️ 16.11.2021):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥈34 ·  ⭐ 5.6K) - Uniform Manifold Approximation and Projection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 100 · 🔀 640 · 📦 5.4K · 📋 620 - 53% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 730K / month · 📦 320 · ⏱️ 13.04.2022):
	```
	pip install umap-learn
	```
- [Conda](https://anaconda.org/conda-forge/umap-learn) (📥 1.1M · ⏱️ 14.04.2022):
	```
	conda install -c conda-forge umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥈34 ·  ⭐ 2.8K) - Fast data visualization and GUI tools for scientific / engineering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyqtgraph/pyqtgraph) (👨‍💻 220 · 🔀 920 · 📋 1K - 31% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/pyqtgraph/pyqtgraph
	```
- [PyPi](https://pypi.org/project/pyqtgraph) (📥 92K / month · 📦 790 · ⏱️ 04.03.2022):
	```
	pip install pyqtgraph
	```
- [Conda](https://anaconda.org/conda-forge/pyqtgraph) (📥 250K · ⏱️ 05.03.2022):
	```
	conda install -c conda-forge pyqtgraph
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈34 ·  ⭐ 1.3K) - 3D plotting and mesh analysis through a streamlined interface for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 91 · 🔀 250 · 📥 650 · 📦 760 · 📋 820 - 30% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 76K / month · 📦 100 · ⏱️ 18.04.2022):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 170K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥈33 ·  ⭐ 1.3K) - Visualize, create, and debug image and video datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 40 · 🔀 170 · 📦 120 · 📋 800 - 33% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone) (📥 18K / month · 📦 1 · ⏱️ 26.05.2022):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥈32 ·  ⭐ 8.8K) - A little word cloud generator in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 65 · 🔀 2.2K · 📋 480 - 23% open · ⏱️ 26.04.2022):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 750K / month · 📦 710 · ⏱️ 11.11.2020):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 280K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥈32 ·  ⭐ 4.5K) - A data visualization and analytics component, especially.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 70 · 🔀 470 · 📦 250 · 📋 520 - 16% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 3K / month · 📦 9 · ⏱️ 14.03.2022):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 68K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.5K / month · ⏱️ 13.05.2022):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥈32 ·  ⭐ 3.1K) - A grammar of graphics for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 95 · 🔀 170 · 📋 490 - 12% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 240K / month · 📦 200 · ⏱️ 25.03.2021):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 170K · ⏱️ 25.03.2021):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥈32 ·  ⭐ 2.9K) - High-performance interactive 2D/3D data visualization library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 170 · 🔀 590 · 📦 760 · 📋 1.3K - 21% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy) (📥 50K / month · 📦 96 · ⏱️ 18.04.2022):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 230K · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge vispy
	```
- [npm](https://www.npmjs.com/package/vispy) (📥 37 / month · ⏱️ 15.03.2020):
	```
	npm install vispy
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈32 ·  ⭐ 2.8K) - Quickly and accurately render even the largest data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 47 · 🔀 350 · 📦 1.1K · 📋 500 - 25% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 47K / month · 📦 95 · ⏱️ 07.05.2022):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 310K · ⏱️ 26.04.2022):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈31 ·  ⭐ 3.3K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 58 · 🔀 460 · 📦 31 · 📋 590 - 38% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 85K / month · 📦 92 · ⏱️ 11.02.2022):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 970K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 27K / month · 📦 10 · ⏱️ 11.02.2022):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥉30 ·  ⭐ 3.4K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 23 · 🔀 280 · 📦 380 · 📋 460 - 8% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 66K / month · 📦 12 · ⏱️ 29.05.2022):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 120K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥉30 ·  ⭐ 3.2K) - Missing data visualization module for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 17 · 🔀 410 · 📦 7.5K · 📋 120 - 5% open · ⏱️ 27.02.2022):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 1M / month · 📦 120 · ⏱️ 27.02.2022):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 160K · ⏱️ 15.02.2020):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥉29 ·  ⭐ 640) - Library for exploring and validating machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 24 · 🔀 120 · 📥 360 · 📦 480 · 📋 160 - 23% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 1.6M / month · 📦 27 · ⏱️ 16.05.2022):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥉29 ·  ⭐ 560) - A high-level plotting API for pandas, dask, xarray, and networkx built on.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 36 · 🔀 68 · 📦 1.3K · 📋 420 - 34% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 130K / month · 📦 62 · ⏱️ 09.05.2022):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 170K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉27 ·  ⭐ 820) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 29 · 🔀 180 · 📦 19 · 📋 220 - 33% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 56K / month · 📦 38 · ⏱️ 26.02.2021):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 390K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [npm](https://www.npmjs.com/package/jupyter-threejs) (📥 5.6K / month · 📦 7 · ⏱️ 26.02.2021):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉26 ·  ⭐ 1.7K) - A Python toolbox for gaining geometric insights into high-dimensional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContextLab/hypertools) (👨‍💻 21 · 🔀 160 · 📥 14 · 📦 190 · 📋 190 - 36% open · ⏱️ 12.02.2022):

	```
	git clone https://github.com/ContextLab/hypertools
	```
- [PyPi](https://pypi.org/project/hypertools) (📥 830 / month · 📦 10 · ⏱️ 12.02.2022):
	```
	pip install hypertools
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉26 ·  ⭐ 1K) - Extensible, parallel implementations of t-SNE. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 10 · 🔀 120 · 📦 340 · 📋 100 - 3% open · ⏱️ 18.03.2022):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne) (📥 16K / month · 📦 10 · ⏱️ 18.03.2022):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 140K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉26 ·  ⭐ 740) - An open-source plotting library for statistical data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 16 · 🔀 33 · 📥 270 · 📦 16 · 📋 250 - 29% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 1.9K / month · 📦 1 · ⏱️ 21.03.2022):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉25 ·  ⭐ 330) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 11 · 🔀 59 · 📋 94 - 12% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 5.7K / month · 📦 84 · ⏱️ 10.02.2022):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 480K · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉24 ·  ⭐ 2.3K) - HiPlot makes understanding high dimensional data easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 8 · 🔀 120 · 📦 4 · 📋 78 - 15% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot) (📥 16K / month · 📦 11 · ⏱️ 31.05.2022):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 86K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉24 ·  ⭐ 700) - Automatically Visualize any dataset, any size with a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 12 · 🔀 100 · 📦 190 · 📋 54 - 7% open · ⏱️ 28.04.2022):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz) (📥 55K / month · 📦 6 · ⏱️ 28.04.2022):
	```
	pip install autoviz
	```
- [Conda](https://anaconda.org/conda-forge/autoviz) (📥 5K · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge autoviz
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉23 ·  ⭐ 2K · 💤) - Visualize and compare datasets, target values and associations, with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 6 · 🔀 200 · 📋 100 - 28% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 90K / month · 📦 5 · ⏱️ 08.07.2021):
	```
	pip install sweetviz
	```
- [Conda](https://anaconda.org/conda-forge/sweetviz) (📥 10K · ⏱️ 09.07.2021):
	```
	conda install -c conda-forge sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉22 ·  ⭐ 560) - Ternary plotting library for python with matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 27 · 🔀 140 · 📥 17 · 📦 93 · 📋 120 - 22% open · ⏱️ 27.02.2022):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 14K / month · 📦 21 · ⏱️ 17.02.2021):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 62K · ⏱️ 17.02.2021):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/ing-bank/popmon">Popmon</a></b> (🥉22 ·  ⭐ 310) - Monitor the stability of a Pandas or Spark dataframe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ing-bank/popmon) (👨‍💻 14 · 🔀 20 · 📥 14 · 📦 11 · 📋 37 - 51% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/ing-bank/popmon
	```
- [PyPi](https://pypi.org/project/popmon) (📥 12K / month · 📦 2 · ⏱️ 27.05.2022):
	```
	pip install popmon
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉21 ·  ⭐ 780) - Bokeh Plotting Backend for Pandas and GeoPandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 14 · 🔀 100 · 📋 97 - 31% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 13K / month · 📦 11 · ⏱️ 11.04.2021):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉20 ·  ⭐ 490) - Make Waffle Charts in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gyli/PyWaffle) (👨‍💻 6 · 🔀 90 · 📦 130 · 📋 16 - 25% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/gyli/PyWaffle
	```
- [PyPi](https://pypi.org/project/pywaffle) (📥 3.1K / month · 📦 1 · ⏱️ 21.12.2021):
	```
	pip install pywaffle
	```
- [Conda](https://anaconda.org/conda-forge/pywaffle) (📥 4.6K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge pywaffle
	```
</details>
<details><summary><b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉20 ·  ⭐ 420) - Joyplots in Python with matplotlib & pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/leotac/joypy) (👨‍💻 6 · 🔀 47 · 📦 160 · 📋 48 - 22% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/leotac/joypy
	```
- [PyPi](https://pypi.org/project/joypy) (📥 26K / month · 📦 5 · ⏱️ 19.12.2021):
	```
	pip install joypy
	```
- [Conda](https://anaconda.org/conda-forge/joypy) (📥 14K · ⏱️ 28.12.2020):
	```
	conda install -c conda-forge joypy
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/SciTools/cartopy">cartopy</a></b> (🥈31 ·  ⭐ 1.1K) - Cartopy - a cartographic python library with matplotlib support. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥉29 ·  ⭐ 2.6K · 💀) - Productivity Tools for Plotly + Pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉27 ·  ⭐ 6.9K · 💀) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 3.2K · 💀) - Python library that makes it easy for data scientists to create.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉24 ·  ⭐ 1.7K · 💀) - Parallel t-SNE implementation with Python and Torch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉23 ·  ⭐ 460 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉22 ·  ⭐ 680 · 💀) - python partial dependence plot toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉21 ·  ⭐ 2.7K) - A GUI for Pandas DataFrames. <code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉19 ·  ⭐ 270) - Dimensionality reduction in very large datasets using Siamese.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉17 ·  ⭐ 390 · 💀) - A python package for animating plots build on matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 340 · 💀) - Interactive plotting for Pandas using Vega-Lite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉16 ·  ⭐ 290 · 💤) - datadescribe: Pythonic EDA Accelerator for Data Science. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉16 ·  ⭐ 190 · 💀) - Draw interactive NetworkX graphs with Altair. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉12 ·  ⭐ 28 · 💀) - nptsne is a numpy compatible python binary package that offers a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Text Data & NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing, cleaning, manipulating, and analyzing text data as well as libraries for NLP tasks such as language detection, fuzzy matching, classification, seq2seq learning, conversational AI, keyword extraction, and translation._

<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇49 ·  ⭐ 64K) - Transformers: State-of-the-art Machine Learning for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 1.3K · 🔀 15K · 📥 1.5K · 📦 29K · 📋 9.5K - 5% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 7.6M / month · 📦 900 · ⏱️ 13.05.2022):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 220K · ⏱️ 22.05.2022):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇44 ·  ⭐ 24K) - Industrial-strength Natural Language Processing (NLP) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 680 · 🔀 3.8K · 📥 3.1K · 📦 40K · 📋 5.1K - 1% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy) (📥 6.8M / month · 📦 2.3K · ⏱️ 05.04.2022):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 2.7M · ⏱️ 03.05.2022):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇43 ·  ⭐ 11K · 📉) - Suite of libraries and programs for symbolic and statistical natural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 420 · 🔀 2.6K · 📦 140K · 📋 1.6K - 13% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 14M / month · 📦 12K · ⏱️ 09.02.2022):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 1.3M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇42 ·  ⭐ 13K) - Topic Modelling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 430 · 🔀 4.2K · 📥 3.8K · 📦 34K · 📋 1.8K - 21% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 7.2M / month · 📦 2.9K · ⏱️ 01.05.2022):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 800K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥇39 ·  ⭐ 14K) - Open source machine learning framework to automate text- and voice-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 540 · 🔀 4K · 📋 6.6K - 14% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 160K / month · 📦 59 · ⏱️ 20.05.2022):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥇39 ·  ⭐ 12K) - A very simple framework for state-of-the-art Natural Language Processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/flairNLP/flair) (👨‍💻 230 · 🔀 1.9K · 📦 1.4K · 📋 1.9K - 5% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/flairNLP/flair
	```
- [PyPi](https://pypi.org/project/flair) (📥 92K / month · 📦 72 · ⏱️ 20.05.2022):
	```
	pip install flair
	```
- [Conda](https://anaconda.org/conda-forge/python-flair) (📥 7.9K · ⏱️ 21.05.2022):
	```
	conda install -c conda-forge python-flair
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇38 ·  ⭐ 11K) - An open-source NLP research library, built on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 260 · 🔀 2.2K · 📥 46 · 📦 2.5K · 📋 2.5K - 3% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 68K / month · 📦 180 · ⏱️ 14.04.2022):
	```
	pip install allennlp
	```
- [Conda](https://anaconda.org/conda-forge/allennlp) (📥 61K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge allennlp
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairseq">fairseq</a></b> (🥇36 ·  ⭐ 17K) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairseq) (👨‍💻 390 · 🔀 4.5K · 📥 240 · 📦 810 · 📋 3.4K - 16% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq) (📥 55K / month · 📦 37 · ⏱️ 05.01.2021):
	```
	pip install fairseq
	```
- [Conda](https://anaconda.org/conda-forge/fairseq) (📥 15K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge fairseq
	```
</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇36 ·  ⭐ 12K · 💤) - ChatterBot is a machine learning, conversational dialog engine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gunthercox/ChatterBot) (👨‍💻 100 · 🔀 4.1K · 📦 4.4K · 📋 1.6K - 20% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/gunthercox/ChatterBot
	```
- [PyPi](https://pypi.org/project/chatterbot) (📥 80K / month · 📦 350 · ⏱️ 22.08.2020):
	```
	pip install chatterbot
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥇35 ·  ⭐ 8.9K) - A framework for training and evaluating AI models on a variety of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 180 · 🔀 1.8K · 📦 77 · 📋 1.3K - 6% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 1.8K / month · 📦 3 · ⏱️ 30.03.2022):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥇35 ·  ⭐ 7.8K) - Multilingual Sentence & Image Embeddings with BERT. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 79 · 🔀 1.5K · 📦 3.3K · 📋 1.4K - 51% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 3.8M / month · 📦 110 · ⏱️ 10.02.2022):
	```
	pip install sentence-transformers
	```
- [Conda](https://anaconda.org/conda-forge/sentence-transformers) (📥 22K · ⏱️ 20.02.2022):
	```
	conda install -c conda-forge sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥇35 ·  ⭐ 6.1K) - Official Stanford NLP Python Library for Many Human Languages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 48 · 🔀 790 · 📦 1.1K · 📋 710 - 12% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 440K / month · 📦 67 · ⏱️ 23.04.2022):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/stanfordnlp/stanza) (📥 5.2K · ⏱️ 23.04.2022):
	```
	conda install -c stanfordnlp stanza
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥇35 ·  ⭐ 2.7K) - State of the Art Natural Language Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 120 · 🔀 560 · 📋 680 - 8% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 1.7M / month · 📦 11 · ⏱️ 05.05.2022):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈34 ·  ⭐ 24K) - Library for fast text representation and classification. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/fastText) (👨‍💻 59 · 🔀 4.4K · 📦 3K · 📋 1.1K - 43% open · ⏱️ 04.03.2022):

	```
	git clone https://github.com/facebookresearch/fastText
	```
- [PyPi](https://pypi.org/project/fasttext) (📥 510K / month · 📦 180 · ⏱️ 28.04.2020):
	```
	pip install fasttext
	```
- [Conda](https://anaconda.org/conda-forge/fasttext) (📥 30K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge fasttext
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥈34 ·  ⭐ 8.2K · 💤) - Simple, Pythonic, text processing--Sentiment analysis, part-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 35 · 🔀 1.1K · 📥 99 · 📦 20K · 📋 260 - 39% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob) (📥 940K / month · 📦 1.4K · ⏱️ 15.12.2021):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 160K · ⏱️ 24.02.2019):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥈34 ·  ⭐ 5.9K) - Unsupervised text tokenizer for Neural Network-based text.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 66 · 🔀 810 · 📥 21K · 📦 15K · 📋 530 - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 7.4M / month · 📦 390 · ⏱️ 18.06.2021):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 190K · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈33 ·  ⭐ 5.7K) - Fast State-of-the-Art Tokenizers optimized for Research and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 56 · 🔀 470 · 📦 49 · 📋 640 - 29% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 7.7M / month · 📦 120 · ⏱️ 13.04.2022):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 180K · ⏱️ 21.05.2022):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈33 ·  ⭐ 3.4K) - A python library for accurate and scalable fuzzy matching, record.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 64 · 🔀 480 · 📦 220 · 📋 740 - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 300K / month · 📦 48 · ⏱️ 21.05.2022):
	```
	pip install dedupe
	```
- [Conda](https://anaconda.org/conda-forge/dedupe) (📥 4.3K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge dedupe
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈33 ·  ⭐ 3K) - Data loaders and abstractions for text and NLP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 130 · 🔀 720 · 📋 720 - 44% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 140K / month · 📦 440 · ⏱️ 10.03.2022):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈33 ·  ⭐ 950) - Making text a first-class citizen in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 89 · 🔀 220 · 📦 1.9K · 📋 220 - 40% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text) (📥 4.7M / month · 📦 78 · ⏱️ 18.05.2022):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈31 ·  ⭐ 5.8K) - An open source library for deep learning end-to-end dialog.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmipt/DeepPavlov) (👨‍💻 67 · 🔀 1K · 📦 270 · 📋 630 - 12% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 11K / month · 📦 6 · ⏱️ 31.05.2022):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈31 ·  ⭐ 5.6K) - Open Source Neural Machine Translation in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 170 · 🔀 2.1K · 📦 140 · 📋 1.3K - 8% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 6.3K / month · 📦 9 · ⏱️ 14.09.2021):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥈31 ·  ⭐ 4.8K) - Haystack is an open source NLP framework that leverages Transformer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 120 · 🔀 760 · 📥 13 · 📋 1.4K - 15% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 1.2K / month · 📦 85 · ⏱️ 15.12.2021):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥈31 ·  ⭐ 4.3K · 📈) - NeMo: a toolkit for conversational AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 150 · 🔀 970 · 📥 6.2K · 📋 1.1K - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 19K / month · 📦 7 · ⏱️ 26.04.2022):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈31 ·  ⭐ 1.7K) - a python library for doing approximate and phonetic matching of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 25 · 🔀 150 · 📦 3.7K · 📋 110 - 9% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish) (📥 2.1M / month · 📦 400 · ⏱️ 07.01.2022):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 230K · ⏱️ 08.04.2022):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈30 ·  ⭐ 3.2K) - Fixes mojibake and other glitches in Unicode text, after the fact. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 110 · 📦 5.8K · 📋 130 - 9% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/rspeer/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 1.7M / month · 📦 490 · ⏱️ 09.02.2022):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 160K · ⏱️ 13.03.2022):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥈30 ·  ⭐ 560) - Snowball compiler and stemming algorithms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 28 · 🔀 160 · 📦 4 · 📋 77 - 42% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 6.7M / month · 📦 6.7K · ⏱️ 16.11.2021):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 4.4M · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/makcedward/nlpaug">nlpaug</a></b> (🥈29 ·  ⭐ 3.3K) - Data augmentation for NLP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/makcedward/nlpaug) (👨‍💻 30 · 🔀 370 · 📦 330 · 📋 180 - 20% open · ⏱️ 03.04.2022):

	```
	git clone https://github.com/makcedward/nlpaug
	```
- [PyPi](https://pypi.org/project/nlpaug) (📥 75K / month · 📦 14 · ⏱️ 23.12.2021):
	```
	pip install nlpaug
	```
- [Conda](https://anaconda.org/conda-forge/nlpaug) (📥 1.9K · ⏱️ 25.12.2021):
	```
	conda install -c conda-forge nlpaug
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈29 ·  ⭐ 2.8K) - Module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 22 · 🔀 470 · 📦 1.3K · 📋 100 - 13% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 23K / month · 📦 100 · ⏱️ 21.04.2022):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 1K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈29 ·  ⭐ 2.4K · 💤) - Toolkit that enables easy text preprocessing, datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 82 · 🔀 520 · 📦 820 · 📋 560 - 46% open · ⏱️ 24.08.2021):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 64K / month · 📦 22 · ⏱️ 13.08.2020):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥈29 ·  ⭐ 1.2K) - A full spaCy pipeline and models for scientific/biomedical documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 23 · 🔀 150 · 📦 470 · 📋 260 - 14% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 22K / month · 📦 17 · ⏱️ 10.03.2022):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥈28 ·  ⭐ 6.3K) - A natural language modeling framework based on PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 230 · 🔀 800 · 📥 290 · 📦 110 · 📋 220 - 66% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/pytext
	```
- [PyPi](https://pypi.org/project/pytext-nlp) (📥 290 / month · 📦 1 · ⏱️ 08.06.2020):
	```
	pip install pytext-nlp
	```
</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈28 ·  ⭐ 3.6K) - VADER Sentiment Analysis. VADER (Valence Aware Dictionary and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cjhutto/vaderSentiment) (👨‍💻 11 · 🔀 860 · 📦 3.8K · 📋 110 - 30% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/cjhutto/vaderSentiment
	```
- [PyPi](https://pypi.org/project/vadersentiment) (📥 190K / month · 📦 170 · ⏱️ 22.05.2020):
	```
	pip install vadersentiment
	```
- [Conda](https://anaconda.org/conda-forge/vadersentiment) (📥 8.7K · ⏱️ 22.03.2021):
	```
	conda install -c conda-forge vadersentiment
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈28 ·  ⭐ 2.8K · 💤) - Compute distance between sequences. 30+ algorithms, pure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 11 · 🔀 230 · 📥 660 · 📦 2.2K · ⏱️ 29.11.2021):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 540K / month · 📦 39 · ⏱️ 27.10.2021):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 110K · ⏱️ 27.10.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈28 ·  ⭐ 1.8K) - Python implementation of TextRank algorithms (textgraphs) for phrase.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 18 · 🔀 330 · 📦 260 · 📋 87 - 29% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 19K / month · 📦 13 · ⏱️ 06.03.2022):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈28 ·  ⭐ 720) - The Classical Language Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 120 · 🔀 310 · 📥 25 · 📦 200 · 📋 520 - 4% open · ⏱️ 01.05.2022):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 1.4K / month · 📦 42 · ⏱️ 26.04.2022):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥈27 ·  ⭐ 10K) - Automatically decrypt encryptions without knowing the key or cipher, decode.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 46 · 🔀 620 · 📋 290 - 17% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 19K / month · ⏱️ 06.06.2021):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 16K · ⭐ 7 · ⏱️ 27.05.2022):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥈27 ·  ⭐ 4.2K) - Code for the paper Exploring the Limits of Transfer Learning with a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 48 · 🔀 580 · 📦 100 · 📋 400 - 15% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 7.5K / month · 📦 2 · ⏱️ 18.10.2021):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥈27 ·  ⭐ 2.6K) - fastNLP: A Modularized and Extensible NLP Framework. Currently still.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 54 · 🔀 420 · 📥 66 · 📦 80 · 📋 200 - 23% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp) (📥 1.3K / month · 📦 3 · ⏱️ 04.02.2019):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥈27 ·  ⭐ 2.5K · 💤) - Fast Coreference Resolution in spaCy with Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/neuralcoref) (👨‍💻 21 · 🔀 440 · 📥 400 · 📦 500 · 📋 300 - 16% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/huggingface/neuralcoref
	```
- [PyPi](https://pypi.org/project/neuralcoref) (📥 96K / month · 📦 14 · ⏱️ 08.04.2019):
	```
	pip install neuralcoref
	```
- [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 11K · ⏱️ 21.02.2020):
	```
	conda install -c conda-forge neuralcoref
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈27 ·  ⭐ 1.1K) - Use pretrained transformers like BERT, XLNet and GPT-2.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 18 · 🔀 140 · 📦 510 · ⏱️ 02.06.2022):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 97K / month · 📦 20 · ⏱️ 02.06.2022):
	```
	pip install spacy-transformers
	```
- [Conda](https://anaconda.org/conda-forge/spacy-transformers) (📥 1.4K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/dwyl/english-words">english-words</a></b> (🥉26 ·  ⭐ 7.2K) - A text file containing 479k English words for all your.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/dwyl/english-words) (👨‍💻 27 · 🔀 1.4K · 📋 92 - 68% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/dwyl/english-words
	```
- [PyPi](https://pypi.org/project/english-words) (📥 15K / month · 📦 6 · ⏱️ 29.01.2022):
	```
	pip install english-words
	```
</details>
<details><summary><b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥉26 ·  ⭐ 1.9K · 📉) - NLP, before and after spaCy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/chartbeat-labs/textacy) (👨‍💻 32 · 🔀 230 · 📋 250 - 11% open · ⏱️ 06.03.2022):

	```
	git clone https://github.com/chartbeat-labs/textacy
	```
- [PyPi](https://pypi.org/project/textacy) (📥 41K / month · 📦 100 · ⏱️ 06.12.2021):
	```
	pip install textacy
	```
- [Conda](https://anaconda.org/conda-forge/textacy) (📥 110K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge textacy
	```
</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉24 ·  ⭐ 3.7K · 💤) - Facilitating the design, comparison and sharing of deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NTMC-Community/MatchZoo) (👨‍💻 36 · 🔀 910 · 📦 10 · 📋 460 - 6% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/NTMC-Community/MatchZoo
	```
- [PyPi](https://pypi.org/project/matchzoo) (📥 94 / month · ⏱️ 24.10.2019):
	```
	pip install matchzoo
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥉24 ·  ⭐ 2.1K · 💤) - Basic Utilities for PyTorch Natural Language Processing.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 250 · 📦 380 · 📋 67 - 26% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 6.3K / month · 📦 17 · ⏱️ 04.11.2019):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉24 ·  ⭐ 1.8K) - Beautiful visualizations of how language differs among document.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 12 · 🔀 250 · 📦 280 · 📋 87 - 19% open · ⏱️ 26.03.2022):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 3.9K / month · 📦 10 · ⏱️ 26.03.2022):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 62K · ⏱️ 26.03.2022):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉24 ·  ⭐ 1.7K) - Super easy library for BERT based NLP models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 36 · 🔀 330 · 📋 250 - 61% open · ⏱️ 12.04.2022):

	```
	git clone https://github.com/utterworks/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 1.8K / month · 📦 2 · ⏱️ 12.04.2022):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉23 ·  ⭐ 2.9K) - Python package to easily retrain OpenAIs GPT-2 text-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/gpt-2-simple) (👨‍💻 21 · 🔀 600 · 📥 300 · 📋 250 - 61% open · ⏱️ 22.05.2022):

	```
	git clone https://github.com/minimaxir/gpt-2-simple
	```
- [PyPi](https://pypi.org/project/gpt-2-simple) (📥 5.4K / month · 📦 5 · ⏱️ 18.10.2021):
	```
	pip install gpt-2-simple
	```
</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉23 ·  ⭐ 2.3K · 💤) - Kashgari is a production-level NLP Transfer learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BrikerMan/Kashgari) (👨‍💻 21 · 🔀 430 · 📦 52 · 📋 370 - 10% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/BrikerMan/Kashgari
	```
- [PyPi](https://pypi.org/project/kashgari-tf) (📥 100 / month · 📦 2 · ⏱️ 18.10.2019):
	```
	pip install kashgari-tf
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥉23 ·  ⭐ 1.4K · 💤) - Contextually-keyed word vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 17 · 🔀 230 · 📥 30K · 📦 150 · 📋 110 - 18% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 3.9K / month · 📦 8 · ⏱️ 19.04.2021):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 25K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/recognai/rubrix">rubrix</a></b> (🥉23 ·  ⭐ 1.1K) - Rubrix, open-source framework for data-centric NLP. Data annotation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/recognai/rubrix) (👨‍💻 19 · 🔀 92 · 📋 540 - 5% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/recognai/rubrix
	```
- [PyPi](https://pypi.org/project/rubrix) (📥 1K / month · ⏱️ 31.05.2022):
	```
	pip install rubrix
	```
- [Conda](https://anaconda.org/conda-forge/rubrix) (📥 1.7K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge rubrix
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉23 ·  ⭐ 1.1K) - Sequence-to-sequence framework with a focus on Neural Machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 56 · 🔀 310 · 📥 14 · 📋 280 - 2% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 1.1K / month · 📦 2 · ⏱️ 05.05.2022):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉22 ·  ⭐ 2.5K · 💤) - Text preprocessing, representation and visualization from zero to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 18 · 🔀 210 · 📥 90 · 📋 140 - 55% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 22K / month · 📦 4 · ⏱️ 01.07.2021):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/qdrant/qdrant">qdrant</a></b> (🥉22 ·  ⭐ 1.8K) - Qdrant - vector similarity search engine with extended filtering.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/qdrant/qdrant) (👨‍💻 25 · 🔀 93 · 📋 210 - 23% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/qdrant/qdrant
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenPrompt">OpenPrompt</a></b> (🥉22 ·  ⭐ 1.5K) - An Open-Source Framework for Prompt-Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenPrompt) (👨‍💻 14 · 🔀 160 · 📦 9 · 📋 120 - 3% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/thunlp/OpenPrompt
	```
- [PyPi](https://pypi.org/project/openprompt) (📥 760 / month · ⏱️ 15.04.2022):
	```
	pip install openprompt
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥉22 ·  ⭐ 1.5K) - Fast & easy transfer learning for NLP. Harvesting language models.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepset-ai/FARM) (👨‍💻 37 · 🔀 220 · 📋 440 - 8% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/deepset-ai/FARM
	```
- [PyPi](https://pypi.org/project/farm) (📥 4.3K / month · 📦 2 · ⏱️ 10.06.2021):
	```
	pip install farm
	```
- [Conda](https://anaconda.org/conda-forge/farm) (📥 1.1K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge farm
	```
</details>
<details><summary><b><a href="https://github.com/unitaryai/detoxify">detoxify</a></b> (🥉22 ·  ⭐ 430) - Trained models & code to predict toxic comments on all 3 Jigsaw.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unitaryai/detoxify) (👨‍💻 6 · 🔀 53 · 📥 44K · 📦 90 · 📋 34 - 50% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/unitaryai/detoxify
	```
- [PyPi](https://pypi.org/project/detoxify) (📥 12K / month · 📦 2 · ⏱️ 12.04.2022):
	```
	pip install detoxify
	```
</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉21 ·  ⭐ 4.2K · 💤) - Python package for performing Entity and Text Matching using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anhaidgroup/deepmatcher) (👨‍💻 7 · 🔀 1.6K · 📦 19 · 📋 83 - 72% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/anhaidgroup/deepmatcher
	```
- [PyPi](https://pypi.org/project/deepmatcher) (📥 910 / month · ⏱️ 13.06.2021):
	```
	pip install deepmatcher
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉21 ·  ⭐ 2.8K · 💤) - A model library for exploring state-of-the-art deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 37 · 🔀 440 · 📦 8 · 📋 130 - 15% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 98 / month · ⏱️ 12.04.2020):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/lightseq">lightseq</a></b> (🥉21 ·  ⭐ 2.2K) - LightSeq: A High Performance Library for Sequence Processing and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/lightseq) (👨‍💻 11 · 🔀 230 · 📥 630 · 📋 180 - 54% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/bytedance/lightseq
	```
- [PyPi](https://pypi.org/project/lightseq) (📥 660 / month · ⏱️ 26.01.2022):
	```
	pip install lightseq
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉21 ·  ⭐ 660) - Scikit-learn style model finetuning for NLP. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 19 · 🔀 71 · 📦 9 · 📋 140 - 15% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 190 / month · 📦 2 · ⏱️ 20.12.2021):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/nyu-mll/jiant">jiant</a></b> (🥉20 ·  ⭐ 1.4K) - jiant is an nlp toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nyu-mll/jiant) (👨‍💻 57 · 🔀 270 · 📦 2 · 📋 550 - 11% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/nyu-mll/jiant
	```
- [PyPi](https://pypi.org/project/jiant) (📥 61 / month · ⏱️ 10.05.2021):
	```
	pip install jiant
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉16 ·  ⭐ 3.7K) - An Open-Source Package for Neural Relation Extraction (NRE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 10 · 🔀 940 · 📋 350 - 5% open · ⏱️ 06.04.2022):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/TextBox">TextBox</a></b> (🥉16 ·  ⭐ 360) - TextBox is an open-source library for building text generation system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RUCAIBox/TextBox) (👨‍💻 14 · 🔀 64 · 📦 5 · 📋 20 - 15% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/RUCAIBox/TextBox
	```
- [PyPi](https://pypi.org/project/textbox) (📥 78 / month · ⏱️ 15.04.2021):
	```
	pip install textbox
	```
</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉16 ·  ⭐ 340 · 💤) - Camphr - NLP libary for creating pipeline components. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/PKSHATechnology-Research/camphr) (👨‍💻 7 · 🔀 17 · 📋 28 - 7% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/PKSHATechnology-Research/camphr
	```
- [PyPi](https://pypi.org/project/camphr) (📥 240 / month · 📦 2 · ⏱️ 28.07.2021):
	```
	pip install camphr
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 740) - Translate - a PyTorch Language Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/translate) (👨‍💻 87 · 🔀 180 · 📋 93 - 70% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/pytorch/translate
	```
- [PyPi](https://pypi.org/project/pytorch-translate) (📥 5 / month · ⏱️ 01.05.2018):
	```
	pip install pytorch-translate
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉14 ·  ⭐ 400) - An Analysis Toolkit for Natural Language Generation (Translation,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 47 · 📦 6 · 📋 16 - 43% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 81 / month · ⏱️ 07.08.2020):
	```
	pip install vizseq
	```
</details>
<details><summary>Show 29 hidden projects...</summary>

- <b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥈32 ·  ⭐ 8.7K · 💤) - Fuzzy String Matching in Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥈27 ·  ⭐ 2K · 💀) - Stand-alone language identification system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉26 ·  ⭐ 2K · 💀) - Multilingual text (NLP) processing toolkit. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉25 ·  ⭐ 5.2K · 💀) - Extract Keywords from sentence or Replace keywords in sentences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉25 ·  ⭐ 4.7K · 💀) - Easily train your own text-generating neural network of any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉25 ·  ⭐ 3.7K · 💀) - Snips Python library to extract meaning from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉23 ·  ⭐ 800 · 💀) - Unsupervised text tokenizer focused on computational efficiency. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mchaput/whoosh">whoosh</a></b> (🥉23 ·  ⭐ 240) - Pure-Python full-text search library. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉22 ·  ⭐ 2.3K · 💀) - Toolkit for Machine Learning, Natural Language Processing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉22 ·  ⭐ 1.4K · 💀) - Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉22 ·  ⭐ 440 · 💀) - pySBD (Python Sentence Boundary Disambiguation) is a rule-based sentence.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/EricFillion/happy-transformer">happy-transformer</a></b> (🥉22 ·  ⭐ 290) - A package built on top of Hugging Faces transformers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code>
- <b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - DELTA is a deep learning based natural language and speech.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉21 ·  ⭐ 140 · 💀) - Get list of common stop words in various languages in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Ki6an/fastT5">fastT5</a></b> (🥉20 ·  ⭐ 300) - boost inference speed of T5 models by 5x & reduce the model size by 3x. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉20 ·  ⭐ 230 · 💀) - Yet another Python binding for fastText. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉19 ·  ⭐ 300 · 💤) - Textpipe: clean and extract metadata from text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉18 ·  ⭐ 1.6K · 💀) - Named-entity recognition using neural networks. Easy-to-use and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉18 ·  ⭐ 230) - scikit-learn wrappers for Python fastText. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/koursaros-ai/nboost">nboost</a></b> (🥉17 ·  ⭐ 620 · 💀) - NBoost is a scalable, search-api-boosting platform for deploying.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/dsfsi/textaugment">textaugment</a></b> (🥉17 ·  ⭐ 240) - TextAugment: Text Augmentation Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉15 ·  ⭐ 230 · 💀) - Easy training and deployment of seq2seq models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉15 ·  ⭐ 220 · 💀) - NeuralQA: A Usable Library for Question Answering on Large Datasets.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jaidevd/numerizer">numerizer</a></b> (🥉15 ·  ⭐ 140) - A Python module to convert natural language numerics into ints and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/BLINK">BLINK</a></b> (🥉14 ·  ⭐ 880 · 💀) - Entity Linker solution. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/MartinoMensio/spacy-dbpedia-spotlight">spacy-dbpedia-spotlight</a></b> (🥉14 ·  ⭐ 62) - A spaCy wrapper for DBpedia Spotlight. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code>
- <b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉13 ·  ⭐ 290 · 💀) - NLP library designed for reproducible experimentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉13 ·  ⭐ 200 · 💀) - Summarization, translation, sentiment-analysis, text-generation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉12 ·  ⭐ 180 · 💀) - Text vectorization tool to outperform TFIDF for classification.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Image Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for image & video processing, manipulation, and augmentation as well as libraries for computer vision tasks such as facial recognition, object detection, and classification._

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇47 ·  ⭐ 9.8K · 📈) - The friendly PIL fork (Python Imaging Library). <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 400 · 🔀 1.9K · 📦 750K · 📋 2.6K - 5% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 47M / month · 📦 63K · ⏱️ 17.05.2022):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 15M · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇44 ·  ⭐ 4.9K) - Image processing in Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/scikit-image/scikit-image) (👨‍💻 550 · 🔀 2K · 📦 100K · 📋 2.5K - 25% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/scikit-image/scikit-image
	```
- [PyPi](https://pypi.org/project/scikit-image) (📥 9.5M / month · 📦 9.3K · ⏱️ 17.02.2022):
	```
	pip install scikit-image
	```
- [Conda](https://anaconda.org/conda-forge/scikit-image) (📥 3.5M · ⏱️ 18.02.2022):
	```
	conda install -c conda-forge scikit-image
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥇42 ·  ⭐ 12K) - Datasets, Transforms and Models specific to Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 490 · 🔀 5.9K · 📥 6.1K · 📋 2.5K - 28% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 5.8M / month · 📦 3.6K · ⏱️ 10.03.2022):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 250K · ⏱️ 29.03.2022):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥇38 ·  ⭐ 19K) - PyTorch image models, scripts, pretrained weights --.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/pytorch-image-models) (👨‍💻 75 · 🔀 3.1K · 📥 1.3M · 📦 3.1K · 📋 510 - 12% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
- [PyPi](https://pypi.org/project/timm) (📥 3.8M / month · 📦 94 · ⏱️ 15.05.2022):
	```
	pip install timm
	```
- [Conda](https://anaconda.org/conda-forge/timm) (📥 18K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge timm
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥇37 ·  ⭐ 20K) - OpenMMLab Detection Toolbox and Benchmark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 340 · 🔀 7.3K · 📦 390 · 📋 5.9K - 9% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
- [PyPi](https://pypi.org/project/mmdet) (📥 35K / month · 📦 9 · ⏱️ 01.06.2022):
	```
	pip install mmdet
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥇37 ·  ⭐ 9.3K) - Video editing with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 150 · 🔀 1.2K · 📦 16K · 📋 1.2K - 24% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 3.7M / month · 📦 750 · ⏱️ 05.10.2020):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 110K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥈36 ·  ⭐ 1K) - Python library for reading and writing image data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 90 · 🔀 210 · 📥 260 · 📦 62K · 📋 450 - 12% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 17M / month · 📦 2.6K · ⏱️ 30.05.2022):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 2.9M · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥈35 ·  ⭐ 6.6K) - Open Source Differentiable Computer Vision Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 170 · 🔀 650 · 📥 320 · 📦 1.3K · 📋 590 - 27% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 360K / month · 📦 54 · ⏱️ 17.05.2022):
	```
	pip install kornia
	```
- [Conda](https://anaconda.org/conda-forge/kornia) (📥 17K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge kornia
	```
</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈34 ·  ⭐ 12K) - State-of-the-art 2D and 3D Face Analysis Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepinsight/insightface) (👨‍💻 45 · 🔀 3.8K · 📦 170 · 📋 1.9K - 54% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/deepinsight/insightface
	```
- [PyPi](https://pypi.org/project/insightface) (📥 20K / month · 📦 5 · ⏱️ 29.01.2022):
	```
	pip install insightface
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥈34 ·  ⭐ 2.8K) - Automated CI toolchain to produce precompiled opencv-python,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 38 · 🔀 550 · 📋 540 - 7% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/opencv/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 5.5M / month · 📦 8.9K · ⏱️ 09.03.2022):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈33 ·  ⭐ 45K · 💤) - The worlds simplest facial recognition api for Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 47 · 🔀 12K · 📥 460 · 📋 1.2K - 54% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 58K / month · 📦 210 · ⏱️ 21.08.2018):
	```
	pip install face_recognition
	```
- [Conda](https://anaconda.org/conda-forge/face_recognition) (📥 6.8K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈33 ·  ⭐ 21K) - Detectron2 is a platform for object detection, segmentation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 210 · 🔀 5.7K · 📦 620 · 📋 3K - 6% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [PyPi](https://pypi.org/project/detectron2) (📥 1 / month · 📦 3 · ⏱️ 06.02.2020):
	```
	pip install detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 55K · ⏱️ 25.04.2022):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥈33 ·  ⭐ 10K) - Fast image augmentation library and an easy-to-use wrapper.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 100 · 🔀 1.3K · 📦 8K · 📋 640 - 45% open · ⏱️ 13.02.2022):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 250K / month · 📦 210 · ⏱️ 04.10.2021):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 38K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈33 ·  ⭐ 5.2K) - Gluon CV Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 120 · 🔀 1.1K · 📦 760 · 📋 820 - 7% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 600K / month · 📦 59 · ⏱️ 02.06.2022):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥈32 ·  ⭐ 7.8K) - Object Detection toolkit based on PaddlePaddle. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 97 · 🔀 2K · 📦 19 · 📋 3.6K - 21% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
- [PyPi](https://pypi.org/project/paddledet) (📥 250 / month · ⏱️ 24.04.2022):
	```
	pip install paddledet
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥈32 ·  ⭐ 1.2K) - The ctypes-based simple ImageMagick binding for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 98 · 🔀 200 · 📥 7.6K · 📦 11K · 📋 370 - 4% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 340K / month · 📦 690 · ⏱️ 17.08.2021):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 12K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleSeg">PaddleSeg</a></b> (🥈31 ·  ⭐ 4.9K) - Easy-to-use image segmentation library with awesome pre-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleSeg) (👨‍💻 78 · 🔀 1.1K · 📦 570 · 📋 1.1K - 49% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleSeg
	```
- [PyPi](https://pypi.org/project/paddleseg) (📥 1.3K / month · 📦 2 · ⏱️ 20.04.2022):
	```
	pip install paddleseg
	```
</details>
<details><summary><b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈31 ·  ⭐ 4.1K) - A series of convenience functions to make basic image processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyImageSearch/imutils) (👨‍💻 21 · 🔀 960 · 📦 26K · 📋 220 - 65% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/PyImageSearch/imutils
	```
- [PyPi](https://pypi.org/project/imutils) (📥 290K / month · 📦 760 · ⏱️ 15.01.2021):
	```
	pip install imutils
	```
- [Conda](https://anaconda.org/conda-forge/imutils) (📥 85K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge imutils
	```
</details>
<details><summary><b><a href="https://github.com/serengil/deepface">deepface</a></b> (🥈31 ·  ⭐ 3.9K) - A Lightweight Face Recognition and Facial Attribute Analysis (Age,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/deepface) (👨‍💻 25 · 🔀 880 · 📦 600 · 📋 450 - 0% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/serengil/deepface
	```
- [PyPi](https://pypi.org/project/deepface) (📥 34K / month · 📦 3 · ⏱️ 10.05.2022):
	```
	pip install deepface
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈30 ·  ⭐ 2.4K · 💤) - A Python Perceptual Image Hashing Module. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 20 · 🔀 300 · 📦 5.2K · 📋 110 - 12% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash) (📥 1.4M / month · 📦 320 · ⏱️ 15.07.2021):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 180K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥈29 ·  ⭐ 10K) - Implementation of Vision Transformer, a simple way to achieve.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 15 · 🔀 1.7K · 📦 110 · 📋 190 - 48% open · ⏱️ 04.05.2022):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 21K / month · 📦 3 · ⏱️ 04.05.2022):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉28 ·  ⭐ 4.7K) - Image augmentation library in Python for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 22 · 🔀 850 · 📦 460 · 📋 200 - 63% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor) (📥 17K / month · 📦 29 · ⏱️ 27.04.2022):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉27 ·  ⭐ 2.2K) - A High-performance cross-platform Video Processing Python framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 9 · 🔀 180 · 📥 590 · 📦 200 · 📋 220 - 0% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 5.4K / month · 📦 5 · ⏱️ 11.02.2022):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/obss/sahi">sahi</a></b> (🥉27 ·  ⭐ 1.7K) - A lightweight vision library for performing large scale object detection/.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/obss/sahi) (👨‍💻 12 · 🔀 260 · 📥 460 · 📦 66 · 📋 150 - 12% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/obss/sahi
	```
- [PyPi](https://pypi.org/project/sahi) (📥 56K / month · 📦 5 · ⏱️ 28.05.2022):
	```
	pip install sahi
	```
- [Conda](https://anaconda.org/conda-forge/sahi) (📥 3.3K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge sahi
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉26 ·  ⭐ 5.7K · 💤) - 2D and 3D Face alignment library build using pytorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 23 · 🔀 1.2K · 📋 270 - 20% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 10K / month · 📦 8 · ⏱️ 14.09.2021):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/Layout-Parser/layout-parser">layout-parser</a></b> (🥉26 ·  ⭐ 3K) - A Unified Toolkit for Deep Learning Based Document Image.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Layout-Parser/layout-parser) (👨‍💻 8 · 🔀 290 · 📦 73 · 📋 94 - 48% open · ⏱️ 05.04.2022):

	```
	git clone https://github.com/Layout-Parser/layout-parser
	```
- [PyPi](https://pypi.org/project/layoutparser) (📥 5.1K / month · 📦 2 · ⏱️ 06.04.2022):
	```
	pip install layoutparser
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorchvideo">pytorchvideo</a></b> (🥉26 ·  ⭐ 2.5K) - A deep learning library for video understanding research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorchvideo) (👨‍💻 36 · 🔀 260 · 📋 130 - 42% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/pytorchvideo
	```
- [PyPi](https://pypi.org/project/pytorchvideo) (📥 16K / month · 📦 5 · ⏱️ 20.01.2022):
	```
	pip install pytorchvideo
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉26 ·  ⭐ 1.6K) - A python library for self-supervised learning on images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 18 · 🔀 120 · 📦 36 · 📋 320 - 19% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 3.2K / month · 📦 1 · ⏱️ 24.05.2022):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉26 ·  ⭐ 750) - Computer Vision in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luispedro/mahotas) (👨‍💻 32 · 🔀 140 · 📦 820 · 📋 78 - 21% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/luispedro/mahotas
	```
- [PyPi](https://pypi.org/project/mahotas) (📥 8.7K / month · 📦 110 · ⏱️ 14.10.2021):
	```
	pip install mahotas
	```
- [Conda](https://anaconda.org/conda-forge/mahotas) (📥 320K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge mahotas
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉26 ·  ⭐ 400) - python binding for libvips using cffi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 13 · 🔀 39 · 📦 320 · 📋 280 - 37% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 17K / month · 📦 39 · ⏱️ 18.04.2022):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 19K · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉25 ·  ⭐ 4.9K) - A modular framework for vision & language multimodal research from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 100 · 🔀 820 · 📦 12 · 📋 620 - 30% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 460 / month · 📦 1 · ⏱️ 12.06.2020):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥉25 ·  ⭐ 2.9K) - Pretrained Pytorch face detection (MTCNN) and facial.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 14 · 🔀 640 · 📥 300K · 📦 780 · 📋 150 - 40% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 15K / month · 📦 11 · ⏱️ 10.03.2021):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉25 ·  ⭐ 1.8K · 💤) - MTCNN face detection implementation for TensorFlow, as a PIP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipazc/mtcnn) (👨‍💻 15 · 🔀 450 · 📦 2.3K · 📋 100 - 62% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/ipazc/mtcnn
	```
- [PyPi](https://pypi.org/project/mtcnn) (📥 32K / month · 📦 43 · ⏱️ 09.07.2021):
	```
	pip install mtcnn
	```
- [Conda](https://anaconda.org/conda-forge/mtcnn) (📥 4.9K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge mtcnn
	```
</details>
<details><summary><b><a href="https://github.com/airctic/icevision">icevision</a></b> (🥉24 ·  ⭐ 700) - An Agnostic Computer Vision Framework - Pluggable to any Training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airctic/icevision) (👨‍💻 39 · 🔀 110 · 📋 550 - 8% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/airctic/icevision
	```
- [PyPi](https://pypi.org/project/icevision) (📥 3.9K / month · 📦 5 · ⏱️ 10.02.2022):
	```
	pip install icevision
	```
</details>
<details><summary><b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉24 ·  ⭐ 670) - An open-source application for biological image analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/CellProfiler/CellProfiler) (👨‍💻 130 · 🔀 310 · 📥 2.7K · 📦 8 · 📋 3.1K - 6% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/CellProfiler/CellProfiler
	```
- [PyPi](https://pypi.org/project/cellprofiler) (📥 720 / month · ⏱️ 04.09.2017):
	```
	pip install cellprofiler
	```
</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉23 ·  ⭐ 3.6K · 💤) - Super-scale your images and run experiments with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/image-super-resolution) (👨‍💻 10 · 🔀 620 · 📦 84 · 📋 200 - 44% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/idealo/image-super-resolution
	```
- [PyPi](https://pypi.org/project/ISR) (📥 4.5K / month · 📦 5 · ⏱️ 08.01.2020):
	```
	pip install ISR
	```
- [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 210 · ⏱️ 01.04.2019):
	```
	docker pull idealo/image-super-resolution-gpu
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vissl">vissl</a></b> (🥉23 ·  ⭐ 2.6K) - VISSL is FAIRs library of extensible, modular and scalable components.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/vissl) (👨‍💻 32 · 🔀 270 · 📦 7 · 📋 150 - 32% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/vissl
	```
- [PyPi](https://pypi.org/project/vissl) (📥 760 / month · 📦 1 · ⏱️ 02.11.2021):
	```
	pip install vissl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉23 ·  ⭐ 2.6K) - TensorFlow Graphics: Differentiable Graphics Layers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 36 · 🔀 340 · 📋 220 - 59% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 3.6K / month · 📦 4 · ⏱️ 03.12.2021):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉23 ·  ⭐ 1.5K) - An end-to-end PyTorch framework for image and video.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 76 · 🔀 260 · 📋 110 - 46% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 2.2K / month · 📦 2 · ⏱️ 09.07.2021):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 13K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉23 ·  ⭐ 1.4K) - Lightweight Python library for adding real-time object tracking to any.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 12 · 🔀 130 · 📥 110 · 📋 61 - 21% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 4K / month · 📦 1 · ⏱️ 30.05.2022):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/deep-daze">deep-daze</a></b> (🥉22 ·  ⭐ 4.2K) - Simple command line tool for text to image generation using OpenAIs.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lucidrains/deep-daze) (👨‍💻 14 · 🔀 310 · 📦 38 · 📋 160 - 55% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/lucidrains/deep-daze
	```
- [PyPi](https://pypi.org/project/deep-daze) (📥 2.1K / month · ⏱️ 13.03.2022):
	```
	pip install deep-daze
	```
</details>
<details><summary><b><a href="https://github.com/ProvenanceLabs/image-match">image-match</a></b> (🥉21 ·  ⭐ 2.7K · 💤) - Quickly search over billions of images. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ProvenanceLabs/image-match) (👨‍💻 19 · 🔀 400 · 📋 110 - 57% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/ProvenanceLabs/image-match
	```
- [PyPi](https://pypi.org/project/image_match) (📥 500 / month · 📦 4 · ⏱️ 13.02.2017):
	```
	pip install image_match
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉20 ·  ⭐ 1.9K) - Codebase for Image Classification Research, written in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 16 · 🔀 220 · 📦 5 · 📋 81 - 30% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/pycls
	```
- [PyPi](https://pypi.org/project/pycls) (📥 1K / month · ⏱️ 05.09.2020):
	```
	pip install pycls
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉19 ·  ⭐ 8.9K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 25 · 🔀 1.6K · 📋 430 - 37% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉19 ·  ⭐ 4.8K) - PySlowFast: video understanding codebase from FAIR for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 27 · 🔀 930 · 📦 7 · 📋 520 - 51% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
- [PyPi](https://pypi.org/project/pyslowfast) (📥 13 / month · ⏱️ 15.01.2020):
	```
	pip install pyslowfast
	```
</details>
<details><summary><b><a href="https://github.com/google-research/scenic">scenic</a></b> (🥉19 ·  ⭐ 1K) - Scenic: A Jax Library for Computer Vision Research and Beyond. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/scenic) (👨‍💻 37 · 🔀 120 · 📦 20 · 📋 64 - 53% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/google-research/scenic
	```
</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉17 ·  ⭐ 620 · 💤) - A lightweight Computer Vision library. Scale your models, not boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jasmcaus/caer) (👨‍💻 8 · 🔀 110 · 📥 19 · 📋 15 - 13% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/jasmcaus/caer
	```
- [PyPi](https://pypi.org/project/caer) (📥 3.4K / month · 📦 1 · ⏱️ 13.10.2021):
	```
	pip install caer
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈36 ·  ⭐ 9.1K) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code>
- <b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥈35 ·  ⭐ 13K · 💀) - Image augmentation for machine learning experiments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈30 ·  ⭐ 7K · 💀) - A python library built to empower developers to build applications and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥈29 ·  ⭐ 6K) - PyTorch3D is FAIRs library of reusable components for deep.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉27 ·  ⭐ 1.8K) - The friendly PIL fork. <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code>
- <b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥉27 ·  ⭐ 1.5K · 💀) - ChainerCV: a Library for Deep Learning in Computer Vision. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉26 ·  ⭐ 3.9K · 💀) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉22 ·  ⭐ 4K · 💀) - Finding duplicate images made easy!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉22 ·  ⭐ 2.4K · 💀) - Deep Learning toolkit for Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉21 ·  ⭐ 860 · 💀) - Nudity detection with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Oulu-IMEDS/solt">solt</a></b> (🥉16 ·  ⭐ 260 · 💀) - Streaming over lightweight data transformations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qanastek/HugsVision">HugsVision</a></b> (🥉15 ·  ⭐ 160) - HugsVision is a easy to use huggingface wrapper for state-of-the-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>huggingface</code>
- <b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉14 ·  ⭐ 64 · 🐣) - Pytorch framework for doing deep learning on point.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Graph Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for graph processing, clustering, embedding, and machine learning tasks._

<details><summary><b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇44 ·  ⭐ 11K) - Network Analysis in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/networkx/networkx) (👨‍💻 600 · 🔀 2.6K · 📥 60 · 📦 110K · 📋 2.9K - 12% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/networkx/networkx
	```
- [PyPi](https://pypi.org/project/networkx) (📥 22M / month · 📦 13K · ⏱️ 21.05.2022):
	```
	pip install networkx
	```
- [Conda](https://anaconda.org/conda-forge/networkx) (📥 6.5M · ⏱️ 21.05.2022):
	```
	conda install -c conda-forge networkx
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥇38 ·  ⭐ 15K) - Graph Neural Network Library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 270 · 🔀 2.6K · 📋 2.6K - 37% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 87K / month · 📦 43 · ⏱️ 12.03.2022):
	```
	pip install torch-geometric
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_geometric) (📥 6.7K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇36 ·  ⭐ 9.7K) - Python package built to ease deep learning on graph, on top of existing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 210 · 🔀 2.3K · 📦 9 · 📋 1.6K - 15% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 26K / month · 📦 45 · ⏱️ 16.03.2022):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈27 ·  ⭐ 2.4K · 💤) - StellarGraph - Machine Learning on Graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stellargraph/stellargraph) (👨‍💻 36 · 🔀 360 · 📦 140 · 📋 1K - 27% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/stellargraph/stellargraph
	```
- [PyPi](https://pypi.org/project/stellargraph) (📥 21K / month · 📦 5 · ⏱️ 30.06.2020):
	```
	pip install stellargraph
	```
</details>
<details><summary><b><a href="https://github.com/graphistry/pygraphistry">pygraphistry</a></b> (🥈27 ·  ⭐ 1.6K) - PyGraphistry is a Python library to quickly load, shape,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graphistry/pygraphistry) (👨‍💻 21 · 🔀 160 · 📦 69 · 📋 210 - 42% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/graphistry/pygraphistry
	```
- [PyPi](https://pypi.org/project/graphistry) (📥 2.4K / month · 📦 4 · ⏱️ 13.05.2022):
	```
	pip install graphistry
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥈27 ·  ⭐ 1.4K) - Benchmark datasets, data loaders, and evaluators for graph machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 19 · 🔀 290 · 📦 300 · 📋 210 - 3% open · ⏱️ 14.05.2022):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 11K / month · 📦 13 · ⏱️ 23.02.2022):
	```
	pip install ogb
	```
- [Conda](https://anaconda.org/conda-forge/ogb) (📥 8.1K · ⏱️ 23.02.2022):
	```
	conda install -c conda-forge ogb
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥈27 ·  ⭐ 1.3K) - Paddle Graph Learning (PGL) is an efficient and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 26 · 🔀 240 · 📦 26 · 📋 120 - 39% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl) (📥 5.9K / month · 📦 2 · ⏱️ 21.04.2022):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈26 ·  ⭐ 2.1K) - Graph Neural Networks with Keras and Tensorflow 2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 20 · 🔀 290 · 📦 130 · 📋 230 - 19% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 6.7K / month · 📦 2 · ⏱️ 09.04.2022):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈26 ·  ⭐ 860) - A Python library for learning and evaluating knowledge graph embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 28 · 🔀 120 · 📥 140 · 📋 410 - 29% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 1.7K / month · 📦 3 · ⏱️ 24.05.2022):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥈25 ·  ⭐ 3.1K) - Generate embeddings from large-scale graph-structured.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/PyTorch-BigGraph) (👨‍💻 27 · 🔀 410 · 📥 130 · 📋 190 - 28% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/PyTorch-BigGraph
	```
- [PyPi](https://pypi.org/project/torchbiggraph) (📥 280K / month · 📦 3 · ⏱️ 01.05.2019):
	```
	pip install torchbiggraph
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥈25 ·  ⭐ 1.6K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 21 · 🔀 240 · 📋 110 - 11% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 2.2K / month · 📦 2 · ⏱️ 04.04.2022):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/graph4ai/graph4nlp">graph4nlp</a></b> (🥉23 ·  ⭐ 1.3K) - Graph4nlp is the library for the easy use of Graph Neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graph4ai/graph4nlp) (👨‍💻 27 · 🔀 160 · 📋 160 - 7% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/graph4ai/graph4nlp
	```
- [PyPi](https://pypi.org/project/graph4nlp) (📥 120 / month · ⏱️ 20.01.2022):
	```
	pip install graph4nlp
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥉23 ·  ⭐ 910) - Implementation of the node2vec algorithm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 11 · 🔀 210 · 📋 76 - 1% open · ⏱️ 30.04.2022):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 160K / month · 📦 15 · ⏱️ 30.04.2022):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 21K · ⏱️ 25.04.2020):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥉22 ·  ⭐ 520) - PyTorch Extension Library of Optimized Graph Cluster.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 20 · 🔀 95 · 📋 100 - 13% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 12K / month · 📦 27 · ⏱️ 11.03.2022):
	```
	pip install torch-cluster
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_cluster) (📥 31K · ⏱️ 06.04.2022):
	```
	conda install -c conda-forge pytorch_cluster
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/jraph">jraph</a></b> (🥉20 ·  ⭐ 910) - A Graph Neural Network Library in Jax. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/jraph) (👨‍💻 16 · 🔀 58 · 📦 19 · 📋 22 - 45% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/deepmind/jraph
	```
- [PyPi](https://pypi.org/project/jraph) (📥 1.4K / month · 📦 2 · ⏱️ 19.11.2021):
	```
	pip install jraph
	```
- [Conda](https://anaconda.org/conda-forge/jraph) (📥 410 · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge jraph
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/deepsnap">deepsnap</a></b> (🥉19 ·  ⭐ 420 · 💤) - Python library assists deep learning on graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/deepsnap) (👨‍💻 15 · 🔀 46 · 📥 8 · 📦 22 · 📋 39 - 38% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/snap-stanford/deepsnap
	```
- [PyPi](https://pypi.org/project/deepsnap) (📥 440 / month · 📦 1 · ⏱️ 05.09.2021):
	```
	pip install deepsnap
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉18 ·  ⭐ 800) - An autoML framework & toolkit for machine learning on graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 13 · 🔀 92 · 📋 20 - 30% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 6 / month · ⏱️ 23.12.2020):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/kglib">kglib</a></b> (🥉16 ·  ⭐ 510 · 💤) - Grakn Knowledge Graph Library (ML R&D). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/kglib) (👨‍💻 7 · 🔀 88 · 📥 210 · 📋 62 - 19% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/vaticle/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 45 / month · ⏱️ 19.08.2020):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/GraphGym">GraphGym</a></b> (🥉15 ·  ⭐ 1K) - Platform for designing and evaluating Graph Neural Networks (GNN). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/GraphGym) (👨‍💻 5 · 🔀 120 · 📥 13 · 📦 2 · 📋 26 - 15% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/snap-stanford/GraphGym
	```
- [PyPi](https://pypi.org/project/graphgym) (📥 59 / month · ⏱️ 24.03.2022):
	```
	pip install graphgym
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/ptgnn">ptgnn</a></b> (🥉13 ·  ⭐ 320) - A PyTorch Graph Neural Network Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/ptgnn) (👨‍💻 7 · 🔀 39 · 📦 1 · 📋 7 - 28% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/microsoft/ptgnn
	```
- [PyPi](https://pypi.org/project/ptgnn) (📥 99 / month · ⏱️ 21.10.2021):
	```
	pip install ptgnn
	```
</details>
<details><summary>Show 16 hidden projects...</summary>

- <b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥇31 ·  ⭐ 980) - Python interface for igraph. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈27 ·  ⭐ 2.5K · 💤) - PYthon svg GrAph plotting Library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈25 ·  ⭐ 1.6K · 📈) - Karate Club: An API Oriented Open-source Python Framework.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈24 ·  ⭐ 1.8K · 💀) - Python library for Representation Learning on Knowledge.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/divelab/DIG">DIG</a></b> (🥉22 ·  ⭐ 1.1K) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉21 ·  ⭐ 2.4K · 💀) - DeepWalk - Deep Learning for Graphs. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉20 ·  ⭐ 5.1K · 💀) - Build Graph Nets in Tensorflow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉19 ·  ⭐ 150) - Python Implementation and Extension of RDF2Vec. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉17 ·  ⭐ 390 · 💀) - semantic similarity framework for knowledge graph. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉17 ·  ⭐ 250 · 💤) - Analyze Data with Pandas-based Networks. Documentation:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 2.8K · 💀) - Implementation and experiments of graph embedding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉15 ·  ⭐ 3.1K · 💀) - An Open-Source Package for Knowledge Embedding (KE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉15 ·  ⭐ 2.8K · 💀) - A distributed graph deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉15 ·  ⭐ 2.7K · 💀) - Representation learning on large graphs using stochastic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉15 ·  ⭐ 1.6K · 💀) - An Open-Source Package for Network Embedding (NE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉12 ·  ⭐ 1K · 💀) - GraphVite: A General and High-performance Graph Embedding System. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Audio Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for audio analysis, manipulation, transformation, and extraction, as well as speech recognition and music generation tasks._

<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇36 ·  ⭐ 5.1K) - End-to-End Speech Processing Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 270 · 🔀 1.6K · 📥 76 · 📦 51 · 📋 1.9K - 18% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 8.6K / month · 📦 1 · ⏱️ 28.05.2022):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/DeepSpeech">DeepSpeech</a></b> (🥇34 ·  ⭐ 20K · 💤) - DeepSpeech is an open source embedded (offline, on-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mozilla/DeepSpeech) (👨‍💻 160 · 🔀 3.5K · 📥 850K · 📦 760 · 📋 2.1K - 5% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/mozilla/DeepSpeech
	```
- [PyPi](https://pypi.org/project/deepspeech) (📥 11K / month · 📦 37 · ⏱️ 19.12.2020):
	```
	pip install deepspeech
	```
- [Conda](https://anaconda.org/conda-forge/deepspeech) (📥 540 · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge deepspeech
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥇34 ·  ⭐ 1.7K) - Data manipulation and transformation for audio signal.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 160 · 🔀 420 · 📋 640 - 27% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 580K / month · 📦 140 · ⏱️ 10.03.2022):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥈33 ·  ⭐ 5.2K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 97 · 🔀 800 · 📋 970 - 4% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 970K / month · 📦 1.2K · ⏱️ 15.02.2022):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 470K · ⏱️ 15.02.2022):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥈32 ·  ⭐ 18K) - Magenta: Music and Art Generation with Machine Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.6K · 📦 360 · 📋 920 - 37% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 4.4K / month · 📦 36 · ⏱️ 12.11.2020):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈31 ·  ⭐ 6.3K) - Speech recognition module for Python, supporting several.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 45 · 🔀 2K · 📋 520 - 45% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 270K / month · 📦 700 · ⏱️ 05.12.2017):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 140K · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥈31 ·  ⭐ 6.2K) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 92 · 🔀 810 · 📦 12K · 📋 480 - 45% open · ⏱️ 14.05.2022):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 1.6M / month · 📦 900 · ⏱️ 10.03.2021):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 24K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/speechbrain/speechbrain">speechbrain</a></b> (🥈31 ·  ⭐ 4.1K) - A PyTorch-based Speech Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/speechbrain/speechbrain) (👨‍💻 160 · 🔀 770 · 📦 180 · 📋 670 - 21% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/speechbrain/speechbrain
	```
- [PyPi](https://pypi.org/project/speechbrain) (📥 9.7K / month · 📦 2 · ⏱️ 20.12.2021):
	```
	pip install speechbrain
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥈29 ·  ⭐ 4.8K) - Python Audio Analysis Library: Feature Extraction,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 26 · 🔀 1.1K · 📦 270 · 📋 290 - 59% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 26K / month · 📦 19 · ⏱️ 07.02.2022):
	```
	pip install pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥈28 ·  ⭐ 2.7K) - On-device wake word detection powered by deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 31 · 🔀 390 · 📦 9 · ⏱️ 27.05.2022):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 1.4K / month · 📦 11 · ⏱️ 12.05.2022):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥈28 ·  ⭐ 530) - Read audio and music meta data and duration of MP3, OGG, OPUS, MP4, M4A,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 21 · 🔀 89 · 📦 530 · 📋 90 - 12% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 94K / month · 📦 70 · ⏱️ 12.03.2022):
	```
	pip install tinytag
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈28 ·  ⭐ 400) - cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 21 · 🔀 93 · 📦 8.5K · 📋 79 - 39% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 940K / month · 📦 320 · ⏱️ 20.10.2020):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 430K · ⏱️ 10.04.2022):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥉27 ·  ⭐ 20K) - Deezer source separation library including pretrained models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 19 · 🔀 2.2K · 📥 1.7M · 📋 680 - 20% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 13K / month · 📦 5 · ⏱️ 03.09.2021):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 64K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/coqui-ai/TTS">Coqui TTS</a></b> (🥉27 ·  ⭐ 5K) - - a deep learning toolkit for Text-to-Speech, battle-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coqui-ai/TTS) (👨‍💻 91 · 🔀 500 · 📥 170K · 📋 340 - 7% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/coqui-ai/TTS
	```
- [PyPi](https://pypi.org/project/tts) (📥 5.6K / month · ⏱️ 14.07.2017):
	```
	pip install tts
	```
- [Conda](https://anaconda.org/conda-forge/tts) (📥 1.9K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge tts
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉26 ·  ⭐ 2.2K) - DDSP: Differentiable Digital Signal Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 31 · 🔀 250 · 📦 26 · 📋 140 - 17% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 3.1K / month · 📦 1 · ⏱️ 25.05.2022):
	```
	pip install ddsp
	```
- [Conda](https://anaconda.org/conda-forge/ddsp) (📥 11K · ⏱️ 08.06.2020):
	```
	conda install -c conda-forge ddsp
	```
</details>
<details><summary><b><a href="https://github.com/iver56/audiomentations">audiomentations</a></b> (🥉25 ·  ⭐ 990) - A Python library for audio data augmentation. Inspired by.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/iver56/audiomentations) (👨‍💻 21 · 🔀 120 · 📦 140 · 📋 120 - 24% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/iver56/audiomentations
	```
- [PyPi](https://pypi.org/project/audiomentations) (📥 4.1K / month · 📦 1 · ⏱️ 30.05.2022):
	```
	pip install audiomentations
	```
</details>
<details><summary><b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉25 ·  ⭐ 910) - Python audio and music signal processing library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/CPJKU/madmom) (👨‍💻 20 · 🔀 150 · 📦 200 · 📋 260 - 21% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/CPJKU/madmom
	```
- [PyPi](https://pypi.org/project/madmom) (📥 2.6K / month · 📦 27 · ⏱️ 14.11.2018):
	```
	pip install madmom
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉25 ·  ⭐ 450) - SoundFile is an audio library based on libsndfile, CFFI, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 24 · 🔀 69 · 📥 3.3K · 📋 170 - 39% open · ⏱️ 23.02.2022):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile) (📥 1.1M / month · 📦 540 · ⏱️ 27.11.2019):
	```
	pip install soundfile
	```
- [Conda](https://anaconda.org/anaconda/pysoundfile):
	```
	conda install -c anaconda pysoundfile
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉23 ·  ⭐ 820) - kapre: Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 140 · 📥 22 · 📦 1.6K · 📋 94 - 12% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 3.4K / month · 📦 14 · ⏱️ 21.01.2022):
	```
	pip install kapre
	```
</details>
<details><summary><b><a href="https://github.com/KinWaiCheuk/nnAudio">nnAudio</a></b> (🥉21 ·  ⭐ 680) - Audio processing by using pytorch 1D convolution network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KinWaiCheuk/nnAudio) (👨‍💻 13 · 🔀 66 · 📦 54 · 📋 49 - 24% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/KinWaiCheuk/nnAudio
	```
- [PyPi](https://pypi.org/project/nnAudio) (📥 34K / month · 📦 1 · ⏱️ 24.12.2021):
	```
	pip install nnAudio
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈28 ·  ⭐ 2.7K) - a library for audio and music analysis. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥉27 ·  ⭐ 2.1K) - C++ library for audio and music analysis, description and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉24 ·  ⭐ 2.1K · 💀) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉22 ·  ⭐ 6K · 💀) - Deep learning for Text to Speech (Discussion forum:.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉22 ·  ⭐ 5.7K · 💀) - Audio fingerprinting and recognition in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Parisson/TimeSide">TimeSide</a></b> (🥉21 ·  ⭐ 320) - Scalable audio processing framework written in Python with a.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉18 ·  ⭐ 210 · 💀) - A library for augmenting annotated audio data. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉17 ·  ⭐ 270) - Fast PyTorch based DSP for audio and 1D signals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Geospatial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to load, process, analyze, and write geographic data as well as libraries for spatial analysis, map visualization, and geocoding._

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇42 ·  ⭐ 9.9K) - WebGL2 powered visualization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 200 · 🔀 1.8K · 📦 4.1K · 📋 2.4K - 6% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck) (📥 940K / month · 📦 23 · ⏱️ 25.10.2021):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 110K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge pydeck
	```
- [npm](https://www.npmjs.com/package/deck.gl) (📥 290K / month · 📦 380 · ⏱️ 01.06.2022):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/shapely/shapely">Shapely</a></b> (🥇37 ·  ⭐ 2.8K) - Manipulation and analysis of geometric objects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shapely/shapely) (👨‍💻 130 · 🔀 460 · 📥 45 · 📦 30K · 📋 880 - 18% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/shapely/shapely
	```
- [PyPi](https://pypi.org/project/shapely) (📥 6.9M / month · 📦 3.8K · ⏱️ 03.05.2022):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 3.7M · ⏱️ 05.05.2022):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/rasterio/rasterio">Rasterio</a></b> (🥇36 ·  ⭐ 1.7K) - Rasterio reads and writes geospatial raster datasets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasterio/rasterio) (👨‍💻 130 · 🔀 470 · 📥 760 · 📦 5K · 📋 1.5K - 9% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/rasterio/rasterio
	```
- [PyPi](https://pypi.org/project/rasterio) (📥 760K / month · 📦 780 · ⏱️ 10.05.2022):
	```
	pip install rasterio
	```
- [Conda](https://anaconda.org/conda-forge/rasterio) (📥 1.5M · ⏱️ 11.03.2022):
	```
	conda install -c conda-forge rasterio
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥈35 ·  ⭐ 5.8K) - Python Data. Leaflet.js Maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 130 · 🔀 2.1K · 📦 16K · 📋 950 - 23% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 900K / month · 📦 660 · ⏱️ 19.11.2021):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 800K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥈35 ·  ⭐ 3.2K) - Python tools for geographic data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 170 · 🔀 720 · 📥 1.5K · 📦 14K · 📋 1.3K - 30% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 2.3M / month · 📦 1.1K · ⏱️ 16.10.2021):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 1.6M · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈35 ·  ⭐ 760) - Python interface to PROJ (cartographic projections and coordinate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 49 · 🔀 180 · 📦 14K · 📋 490 - 2% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 4.4M / month · 📦 1.7K · ⏱️ 22.04.2022):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 3.5M · ⏱️ 24.04.2022):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥈34 ·  ⭐ 3.6K) - Geocoding library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 130 · 🔀 570 · 📦 39K · 📋 260 - 10% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 3.7M / month · 📦 3.9K · ⏱️ 11.07.2021):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 710K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈33 ·  ⭐ 1.3K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 78 · 🔀 330 · 📦 1.8K · 📋 490 - 38% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 72K / month · 📦 110 · ⏱️ 14.04.2022):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 830K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 50K / month · 📦 2 · ⏱️ 14.04.2022):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈33 ·  ⭐ 920) - Fiona reads and writes geographic data files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 66 · 🔀 180 · 📦 8.7K · 📋 680 - 11% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 2.6M / month · 📦 780 · ⏱️ 07.02.2022):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 2.9M · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉31 ·  ⭐ 1.3K) - Documentation and samples for ArcGIS API for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 80 · 🔀 910 · 📥 3.5K · 📋 450 - 12% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 73K / month · 📦 26 · ⏱️ 02.06.2022):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 7K · ⭐ 34 · ⏱️ 04.02.2022):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉29 ·  ⭐ 720) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 48 · 🔀 95 · 📦 9.4K · 📋 84 - 26% open · ⏱️ 07.05.2022):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 750K / month · 📦 1.1K · ⏱️ 09.08.2019):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 510K · ⏱️ 11.08.2019):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉27 ·  ⭐ 1K) - PySAL: Python Spatial Analysis Library Meta-Package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 75 · 🔀 270 · 📋 610 - 1% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 19K / month · 📦 30 · ⏱️ 30.01.2022):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 440K · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉26 ·  ⭐ 410) - Simple, concise geographical visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 27 · 🔀 68 · 📋 300 - 34% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 11K / month · 📦 26 · ⏱️ 08.03.2022):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 110K · ⏱️ 08.03.2022):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉26 ·  ⭐ 370) - A package built to support working with spatial data using open source.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 40 · 🔀 140 · 📦 140 · 📋 220 - 8% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 8K / month · 📦 7 · ⏱️ 01.10.2021):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 44K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥈33 ·  ⭐ 1.4K · 💀) - Python Geocoder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉30 ·  ⭐ 840) - Python package for earth-observing satellite data processing. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉27 ·  ⭐ 770) - Search and download Copernicus Sentinel satellite images. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉24 ·  ⭐ 740 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 ·  ⭐ 610 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉21 ·  ⭐ 970 · 💀) - python toolbox for visualizing geographical data and making maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉21 ·  ⭐ 250) - pure-Python (Numpy optional) 3D coordinate conversions for geospace ecef.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/marceloprates/prettymaps">prettymaps</a></b> (🥉17 ·  ⭐ 8K) - A small set of Python functions to draw pretty maps from.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Financial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for algorithmic stock/crypto trading, risk analytics, backtesting, technical analysis, and other tasks on financial data._

<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇34 ·  ⭐ 7.1K) - Download market data from Yahoo! Finances API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 53 · 🔀 1.6K · 📦 12K · 📋 800 - 57% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 330K / month · 📦 140 · ⏱️ 30.01.2022):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 43K · ⏱️ 10.07.2021):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥇32 ·  ⭐ 8.6K) - Qlib is an AI-oriented quantitative investment platform, which aims to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 94 · 🔀 1.5K · 📥 280 · 📦 19 · 📋 550 - 29% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 3.1K / month · ⏱️ 24.04.2022):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈30 ·  ⭐ 3K) - Technical Analysis Library using Pandas and Numpy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bukosabino/ta) (👨‍💻 28 · 🔀 700 · 📦 1.2K · 📋 210 - 53% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/bukosabino/ta
	```
- [PyPi](https://pypi.org/project/ta) (📥 71K / month · 📦 33 · ⏱️ 16.04.2022):
	```
	pip install ta
	```
- [Conda](https://anaconda.org/conda-forge/ta) (📥 3.2K · ⏱️ 21.04.2022):
	```
	conda install -c conda-forge ta
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥈27 ·  ⭐ 3.6K · 💤) - A python wrapper for Alpha Vantage API for financial data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 39 · 🔀 640 · 📋 260 - 5% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 15K / month · 📦 100 · ⏱️ 26.08.2018):
	```
	pip install alpha_vantage
	```
- [Conda](https://anaconda.org/conda-forge/alpha_vantage) (📥 1.2K · ⏱️ 14.01.2021):
	```
	conda install -c conda-forge alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥈27 ·  ⭐ 1.8K) - Python sync/async framework for Interactive Brokers API. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 30 · 🔀 480 · 📋 400 - 1% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync) (📥 7.2K / month · 📦 19 · ⏱️ 28.11.2021):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 16K · ⏱️ 29.11.2021):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥈27 ·  ⭐ 1.1K) - ffn - a financial function library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 26 · 🔀 200 · 📦 200 · 📋 97 - 17% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn) (📥 29K / month · 📦 25 · ⏱️ 21.04.2021):
	```
	pip install ffn
	```
- [Conda](https://anaconda.org/conda-forge/ffn) (📥 870 · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge ffn
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥉26 ·  ⭐ 1.4K) - bt - flexible backtesting for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 25 · 🔀 310 · 📦 110 · 📋 290 - 20% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 4.4K / month · 📦 21 · ⏱️ 21.04.2021):
	```
	pip install bt
	```
- [Conda](https://anaconda.org/conda-forge/bt) (📥 4.4K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge bt
	```
</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥉25 ·  ⭐ 3.9K) - An open source reinforcement learning framework for training,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensortrade-org/tensortrade) (👨‍💻 61 · 🔀 880 · 📦 36 · 📋 230 - 15% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/tensortrade-org/tensortrade
	```
- [PyPi](https://pypi.org/project/tensortrade) (📥 560 / month · 📦 1 · ⏱️ 10.05.2021):
	```
	pip install tensortrade
	```
- [Conda](https://anaconda.org/conda-forge/tensortrade) (📥 1.1K · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge tensortrade
	```
</details>
<details><summary><b><a href="https://github.com/scrtlabs/catalyst">Enigma Catalyst</a></b> (🥉25 ·  ⭐ 2.3K · 💤) - An Algorithmic Trading Library for Crypto-Assets in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scrtlabs/catalyst) (👨‍💻 150 · 🔀 700 · 📦 25 · 📋 490 - 27% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/scrtlabs/catalyst
	```
- [PyPi](https://pypi.org/project/enigma-catalyst) (📥 560 / month · 📦 2 · ⏱️ 11.11.2018):
	```
	pip install enigma-catalyst
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉24 ·  ⭐ 3.1K) - High-performance TensorFlow library for quantitative.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 39 · 🔀 420 · 📋 45 - 48% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 1.5K / month · 📦 2 · ⏱️ 31.05.2022):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉24 ·  ⭐ 1K) - Supply a wrapper ``StockDataFrame`` based on the ``pandas.DataFrame``.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jealous/stockstats) (👨‍💻 8 · 🔀 260 · 📦 470 · 📋 85 - 9% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jealous/stockstats
	```
- [PyPi](https://pypi.org/project/stockstats) (📥 8.3K / month · 📦 29 · ⏱️ 07.01.2022):
	```
	pip install stockstats
	```
</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉22 ·  ⭐ 4K · 💤) - Github.com/CryptoSignal - #1 Quant Trading & Technical.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CryptoSignal/Crypto-Signal) (👨‍💻 28 · 🔀 1K · 📋 260 - 20% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/CryptoSignal/crypto-signal
	```
- [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 140K · ⭐ 7 · ⏱️ 03.09.2020):
	```
	docker pull shadowreaver/crypto-signal
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉19 ·  ⭐ 2.9K) - Python library for backtesting trading strategies & analyzing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 450 · 📥 40 · 📦 5 · 📋 26 - 88% open · ⏱️ 05.04.2022):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 120 / month · ⏱️ 07.10.2021):
	```
	pip install finmarketpy
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇32 ·  ⭐ 15K · 💀) - Zipline, a Pythonic Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥈29 ·  ⭐ 8.8K · 💤) - Python Backtesting library for trading strategies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥈29 ·  ⭐ 4.4K · 💀) - Portfolio and risk analytics in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/bashtage/arch">arch</a></b> (🥈29 ·  ⭐ 920) - ARCH models in Python. <code><a href="https://tldrlegal.com/search?q=NCSA">❗️NCSA</a></code>
- <b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈27 ·  ⭐ 2.3K · 💀) - Performance analysis of predictive (alpha) stock factors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥉26 ·  ⭐ 930 · 💀) - Common financial risk and performance metrics. Used by zipline.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉25 ·  ⭐ 3.7K · 💀) - Python Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉24 ·  ⭐ 1.6K · 💤) - Common financial technical indicators implemented in Pandas. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉19 ·  ⭐ 2.5K) - Backtest trading strategies in Python. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/fmilthaler/FinQuant">FinQuant</a></b> (🥉18 ·  ⭐ 770 · 💀) - A program for financial portfolio management, analysis and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.5K · 💀) - Find big moving stocks before they move using machine.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/alvarobartt/pyrtfolio">pyrtfolio</a></b> (🥉7 ·  ⭐ 110 · 💀) - Python package to generate stock portfolios. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Time Series Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for forecasting, anomaly detection, feature extraction, and machine learning on time-series and sequential data._

<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥇35 ·  ⭐ 5.4K) - A unified framework for machine learning with time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alan-turing-institute/sktime) (👨‍💻 170 · 🔀 850 · 📥 76 · 📦 450 · 📋 1.2K - 35% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 170K / month · 📦 23 · ⏱️ 13.05.2022):
	```
	pip install sktime
	```
- [Conda](https://anaconda.org/conda-forge/sktime-all-extras) (📥 4.4K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge sktime-all-extras
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥇34 ·  ⭐ 15K) - Tool for producing high quality forecasts for time series data that has.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 150 · 🔀 4.2K · 📥 650 · 📋 1.8K - 11% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 1.5M / month · 📦 130 · ⏱️ 05.09.2020):
	```
	pip install fbprophet
	```
- [Conda](https://anaconda.org/conda-forge/prophet) (📥 49K · ⏱️ 23.08.2021):
	```
	conda install -c conda-forge prophet
	```
</details>
<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇33 ·  ⭐ 1.2K) - A statistical library designed to fill the void in Pythons time series.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 21 · 🔀 210 · 📦 2.1K · 📋 280 - 9% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 1.2M / month · 📦 51 · ⏱️ 22.02.2022):
	```
	pip install pmdarima
	```
- [Conda](https://anaconda.org/conda-forge/pmdarima) (📥 40K · ⏱️ 24.02.2022):
	```
	conda install -c conda-forge pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥈31 ·  ⭐ 2.3K · 📈) - STUMPY is a powerful and scalable Python library for modern time.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 29 · 🔀 220 · 📦 210 · 📋 320 - 11% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy) (📥 300K / month · 📦 4 · ⏱️ 31.03.2022):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 39K · ⏱️ 31.03.2022):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥈31 ·  ⭐ 2K) - Time series forecasting with PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 29 · 🔀 320 · 📋 470 - 46% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 62K / month · 📦 4 · ⏱️ 23.05.2022):
	```
	pip install pytorch-forecasting
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-forecasting) (📥 19K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/ourownstory/neural_prophet">NeuralProphet</a></b> (🥈30 ·  ⭐ 2.3K) - NeuralProphet: A simple forecasting package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ourownstory/neural_prophet) (👨‍💻 21 · 🔀 280 · 📦 84 · 📋 270 - 26% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/ourownstory/neural_prophet
	```
- [PyPi](https://pypi.org/project/neuralprophet) (📥 71K / month · ⏱️ 22.03.2022):
	```
	pip install neuralprophet
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥈30 ·  ⭐ 2.1K) - A machine learning toolkit dedicated to time-series data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 36 · 🔀 270 · 📦 500 · 📋 270 - 32% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 110K / month · 📦 19 · ⏱️ 16.08.2021):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 260K · ⏱️ 15.01.2022):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈29 ·  ⭐ 6.4K) - Automatic extraction of relevant features from time series:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 82 · 🔀 970 · 📋 480 - 9% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 470K / month · 📦 55 · ⏱️ 21.12.2021):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 170K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈29 ·  ⭐ 4.1K) - A python library for easy manipulation and forecasting of time series. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 53 · 🔀 420 · 📦 60 · 📋 470 - 34% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 9K / month · 📦 2 · ⏱️ 13.04.2022):
	```
	pip install u8darts
	```
- [Conda](https://anaconda.org/conda-forge/u8darts-all) (📥 4.6K · ⏱️ 14.04.2022):
	```
	conda install -c conda-forge u8darts-all
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 340 · ⏱️ 13.04.2022):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥈28 ·  ⭐ 2.7K) - Probabilistic time series modeling in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluon-ts) (👨‍💻 87 · 🔀 560 · 📋 740 - 40% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 94K / month · 📦 6 · ⏱️ 28.04.2022):
	```
	pip install gluonts
	```
- [Conda](https://anaconda.org/anaconda/gluonts) (📥 46 · ⏱️ 14.10.2021):
	```
	conda install -c anaconda gluonts
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥈25 ·  ⭐ 1.3K) - A Python package for time series classification. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 11 · 🔀 130 · 📦 210 · 📋 61 - 57% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 140K / month · 📦 11 · ⏱️ 31.10.2021):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 11K · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥉24 ·  ⭐ 1.1K) - Real-time stream processing for python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 45 · 🔀 130 · 📦 300 · 📋 250 - 41% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz) (📥 14K / month · 📦 29 · ⏱️ 04.10.2021):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 310K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/Nixtla/statsforecast">StatsForecast</a></b> (🥉23 ·  ⭐ 680) - Lightning fast forecasting with statistical and econometric models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Nixtla/statsforecast) (👨‍💻 9 · 🔀 42 · 📋 45 - 37% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Nixtla/statsforecast
	```
- [PyPi](https://pypi.org/project/statsforecast) (📥 46K / month · 📦 3 · ⏱️ 09.05.2022):
	```
	pip install statsforecast
	```
- [Conda](https://anaconda.org/conda-forge/statsforecast) (📥 4.6K · ⏱️ 09.05.2022):
	```
	conda install -c conda-forge statsforecast
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/greykite">greykite</a></b> (🥉19 ·  ⭐ 1.5K) - A flexible, intuitive and fast forecasting library. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/greykite) (👨‍💻 7 · 🔀 67 · 📦 9 · 📋 62 - 14% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/linkedin/greykite
	```
- [PyPi](https://pypi.org/project/greykite) (📥 35K / month · ⏱️ 15.12.2021):
	```
	pip install greykite
	```
</details>
<details><summary><b><a href="https://github.com/fraunhoferportugal/tsfel">TSFEL</a></b> (🥉19 ·  ⭐ 510) - An intuitive library to extract features from time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fraunhoferportugal/tsfel) (👨‍💻 14 · 🔀 67 · 📦 36 · 📋 50 - 14% open · ⏱️ 16.03.2022):

	```
	git clone https://github.com/fraunhoferportugal/tsfel
	```
- [PyPi](https://pypi.org/project/tsfel) (📥 4.4K / month · ⏱️ 14.02.2021):
	```
	pip install tsfel
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉19 ·  ⭐ 430) - Automatically build ARIMA, SARIMAX, VAR, FB Prophet and XGBoost.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 6 · 🔀 81 · 📋 72 - 13% open · ⏱️ 13.02.2022):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 1.4K / month · ⏱️ 31.01.2022):
	```
	pip install auto-ts
	```
</details>
<details><summary><b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉16 ·  ⭐ 440) - AtsPy: Automated Time Series Models in Python (by @firmai). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/firmai/atspy) (👨‍💻 5 · 🔀 86 · 📦 6 · 📋 20 - 90% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/firmai/atspy
	```
- [PyPi](https://pypi.org/project/atspy) (📥 2.4K / month · ⏱️ 24.04.2020):
	```
	pip install atspy
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥈25 ·  ⭐ 2K · 💀) - Open source time series library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉21 ·  ⭐ 1K · 💀) - Anomaly Detection and Correlation library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉21 ·  ⭐ 520 · 💀) - Python module for machine learning time series:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉21 ·  ⭐ 380 · 💀) - Module for statistical learning, with a particular emphasis on time-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉20 ·  ⭐ 680 · 💀) - A Python library for detecting patterns and anomalies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Nixtla/neuralforecast">NeuralForecast</a></b> (🥉20 ·  ⭐ 610) - Scalable and user friendly neural forecasting algorithms.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉20 ·  ⭐ 420 · 💀) - A python library for Bayesian time series modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉19 ·  ⭐ 820 · 💀) - A Python toolkit for rule-based/unsupervised anomaly detection in time.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/arundo/tsaug">tsaug</a></b> (🥉14 ·  ⭐ 240 · 💀) - A Python package for time series augmentation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Medical Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing and analyzing medical data such as MRIs, EEGs, genomic data, and other medical imaging formats._

<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥇36 ·  ⭐ 1.9K) - MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 290 · 🔀 1K · 📦 1.6K · 📋 4.1K - 9% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 41K / month · 📦 210 · ⏱️ 12.05.2022):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 200K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥇35 ·  ⭐ 870) - Machine learning for NeuroImaging in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nilearn/nilearn) (👨‍💻 180 · 🔀 460 · 📥 58 · 📦 1.6K · 📋 1.6K - 17% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/nilearn/nilearn
	```
- [PyPi](https://pypi.org/project/nilearn) (📥 22K / month · 📦 240 · ⏱️ 13.04.2022):
	```
	pip install nilearn
	```
- [Conda](https://anaconda.org/conda-forge/nilearn) (📥 150K · ⏱️ 13.04.2022):
	```
	conda install -c conda-forge nilearn
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥈34 ·  ⭐ 630) - Workflows and interfaces for neuroimaging packages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 240 · 🔀 490 · 📦 940 · 📋 1.3K - 29% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 49K / month · 📦 160 · ⏱️ 16.05.2022):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 470K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈33 ·  ⭐ 3K) - AI Toolkit for Healthcare Imaging. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 97 · 🔀 590 · 📦 330 · 📋 1.7K - 12% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 48K / month · 📦 19 · ⏱️ 01.06.2022):
	```
	pip install monai
	```
- [Conda](https://anaconda.org/conda-forge/monai) (📥 820 · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge monai
	```
</details>
<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥈33 ·  ⭐ 1.9K) - Survival analysis in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 100 · 🔀 470 · 📦 900 · 📋 860 - 26% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 330K / month · 📦 110 · ⏱️ 15.03.2022):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 190K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈33 ·  ⭐ 800) - Scalable genomic data analysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 79 · 🔀 210 · 📦 68 · 📋 2K - 2% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 29K / month · 📦 11 · ⏱️ 16.05.2022):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈33 ·  ⭐ 470) - Python package to access a cacophony of neuro-imaging file formats. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nipy/nibabel) (👨‍💻 95 · 🔀 230 · 📦 7.2K · 📋 460 - 30% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/nipy/nibabel
	```
- [PyPi](https://pypi.org/project/nibabel) (📥 180K / month · 📦 970 · ⏱️ 07.02.2022):
	```
	pip install nibabel
	```
- [Conda](https://anaconda.org/conda-forge/nibabel) (📥 440K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge nibabel
	```
</details>
<details><summary><b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈31 ·  ⭐ 510) - DIPY is the paragon 3D/4D+ imaging library in Python. Contains generic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dipy/dipy) (👨‍💻 130 · 🔀 360 · 📦 570 · 📋 810 - 18% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/dipy/dipy
	```
- [PyPi](https://pypi.org/project/dipy) (📥 12K / month · 📦 80 · ⏱️ 11.03.2022):
	```
	pip install dipy
	```
- [Conda](https://anaconda.org/conda-forge/dipy) (📥 300K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge dipy
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉23 ·  ⭐ 2.5K · 📉) - DeepVariant is an analysis pipeline that uses a deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 21 · 🔀 610 · 📥 3.9K · 📋 490 - 0% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 41K · ⏱️ 16.12.2021):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉14 ·  ⭐ 1.1K) - The Medical Detection Toolkit contains 2D + 3D.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) (👨‍💻 3 · 🔀 290 · 📋 130 - 33% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉25 ·  ⭐ 1.3K · 💀) - [unmaintained] An open-source convolutional neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉23 ·  ⭐ 320 · 💀) - Neuroimaging in Python FMRI analysis package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉23 ·  ⭐ 200) - An open-source toolkit for large-scale genomic analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉22 ·  ⭐ 1.3K · 💀) - Deep Learning Toolkit for Medical Image Analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉22 ·  ⭐ 410 · 💀) - Medical image processing in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉21 ·  ⭐ 270 · 💀) - Brain Imaging Analysis Kit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉16 ·  ⭐ 780 · 💀) - A medical imaging framework for Pytorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉13 ·  ⭐ 110 · 💀) - A deep learning python package for neuroimaging data. Made by:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉12 ·  ⭐ 1.4K · 💀) - Many studies have shown that the performance on deep learning is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Tabular Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing tabular and structured data._

<details><summary><b><a href="https://github.com/manujosephv/pytorch_tabular">pytorch_tabular</a></b> (🥈19 ·  ⭐ 600 · 📈) - A standard framework for modelling Deep Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/manujosephv/pytorch_tabular) (👨‍💻 9 · 🔀 61 · 📋 60 - 26% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/manujosephv/pytorch_tabular
	```
- [PyPi](https://pypi.org/project/pytorch_tabular) (📥 1.6K / month · 📦 1 · ⏱️ 01.09.2021):
	```
	pip install pytorch_tabular
	```
</details>
<details><summary><b><a href="https://github.com/carefree0910/carefree-learn">carefree-learn</a></b> (🥈19 ·  ⭐ 360) - Deep Learning PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/carefree0910/carefree-learn) (👨‍💻 1 · 🔀 33 · 📦 2 · ⏱️ 30.05.2022):

	```
	git clone https://github.com/carefree0910/carefree-learn
	```
- [PyPi](https://pypi.org/project/carefree-learn) (📥 100 / month · ⏱️ 29.04.2022):
	```
	pip install carefree-learn
	```
</details>
<details><summary><b><a href="https://github.com/firmai/deltapy">deltapy</a></b> (🥉11 ·  ⭐ 430) - DeltaPy - Tabular Data Augmentation (by @firmai). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/firmai/deltapy) (👨‍💻 4 · 🔀 43 · 📦 2 · 📋 3 - 66% open · ⏱️ 01.03.2022):

	```
	git clone https://github.com/firmai/deltapy
	```
- [PyPi](https://pypi.org/project/deltapy) (📥 130 / month · ⏱️ 09.04.2020):
	```
	pip install deltapy
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/AnotherSamWilson/miceforest">miceforest</a></b> (🥇22 ·  ⭐ 160) - Multiple Imputation with Random Forests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/upgini/upgini">upgini</a></b> (🥉17 ·  ⭐ 28 · 🐣) - Low-code feature search library for supervised machine learning.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Optical Character Recognition

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for optical character recognition (OCR) and text extraction from images or videos._

<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥇38 ·  ⭐ 22K) - Awesome multilingual OCR toolkits based on PaddlePaddle.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 110 · 🔀 4.5K · 📦 660 · 📋 4.6K - 24% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 61K / month · 📦 6 · ⏱️ 10.05.2022):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇35 ·  ⭐ 15K) - Ready-to-use OCR with 80+ supported languages and all popular writing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 100 · 🔀 2.1K · 📥 1.6M · 📦 1.2K · 📋 560 - 20% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr) (📥 100K / month · 📦 36 · ⏱️ 02.06.2022):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈33 ·  ⭐ 4.2K) - Python-tesseract is an optical character recognition (OCR) tool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 41 · 🔀 600 · 📋 300 - 5% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 620K / month · 📦 940 · ⏱️ 19.02.2022):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 500K · ⏱️ 15.03.2022):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/ocrmypdf/OCRmyPDF">OCRmyPDF</a></b> (🥈30 ·  ⭐ 6.5K) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/ocrmypdf/OCRmyPDF) (👨‍💻 68 · 🔀 570 · 📋 870 - 10% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/ocrmypdf/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf) (📥 25K / month · 📦 12 · ⏱️ 26.05.2022):
	```
	pip install ocrmypdf
	```
- [Conda](https://anaconda.org/conda-forge/ocrmypdf) (📥 11K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈29 ·  ⭐ 1.6K · 💤) - A Python wrapper for the tesseract-ocr API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 26 · 🔀 220 · 📦 660 · 📋 250 - 32% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 61K / month · 📦 67 · ⏱️ 19.06.2021):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 71K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmocr">MMOCR</a></b> (🥉28 ·  ⭐ 2.5K) - OpenMMLab Text Detection, Recognition and Understanding Toolbox. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmocr) (👨‍💻 50 · 🔀 440 · 📦 13 · 📋 560 - 16% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/open-mmlab/mmocr
	```
- [PyPi](https://pypi.org/project/mmocr) (📥 2.5K / month · 📦 1 · ⏱️ 05.05.2022):
	```
	pip install mmocr
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉23 ·  ⭐ 1K) - A packaged and flexible version of the CRAFT text detector and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 15 · 🔀 270 · 📥 270K · 📋 170 - 38% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 6.7K / month · 📦 2 · ⏱️ 19.05.2022):
	```
	pip install keras-ocr
	```
- [Conda](https://anaconda.org/anaconda/keras-ocr) (📥 60 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉21 ·  ⭐ 920) - Line based ATR Engine based on OCRopy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 19 · 🔀 190 · 📋 250 - 20% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 660 / month · 📦 2 · ⏱️ 13.11.2018):
	```
	pip install calamari_ocr
	```
</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉21 ·  ⭐ 910 · 💤) - A Tensorflow model for text recognition (CNN + seq2seq.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emedvedev/attention-ocr) (👨‍💻 27 · 🔀 240 · 📦 19 · 📋 150 - 16% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/emedvedev/attention-ocr
	```
- [PyPi](https://pypi.org/project/aocr) (📥 210 / month · ⏱️ 19.04.2019):
	```
	pip install aocr
	```
</details>
<details><summary><b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉18 ·  ⭐ 2K) - A set of tools for extracting tables from PDF files helping to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/WZBSocialScienceCenter/pdftabextract) (👨‍💻 2 · 🔀 340 · 📦 39 · 📋 21 - 14% open · ⏱️ 07.03.2022):

	```
	git clone https://github.com/WZBSocialScienceCenter/pdftabextract
	```
- [PyPi](https://pypi.org/project/pdftabextract) (📥 560 / month · 📦 1 · ⏱️ 09.01.2018):
	```
	pip install pdftabextract
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉19 ·  ⭐ 1.3K · 💀) - Detect text blocks and OCR poorly scanned PDFs in bulk. Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 370 · 💀) - An optical music recognition (OMR) system. Converts sheet.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Data Containers & Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose data containers & structures as well as utilities & extensions for pandas._

<br>

## Data Loading & Extraction

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for loading, collecting, and extracting data from a variety of data sources and formats._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-loading--extraction">best-of-python - Data Extraction</a></b> ( ⭐ 2.2K)  - Collection of data-loading and -extraction libraries.

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-containers--dataframes">best-of-python - Data Containers</a></b> ( ⭐ 2.2K)  - Collection of data-container, dataframe, and pandas-..

<br>

## Web Scraping & Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for web scraping, crawling, downloading, and mining as well as libraries._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python#web-scraping--crawling">best-of-web-python - Web Scraping</a></b> ( ⭐ 1.6K)  - Collection of web-scraping and crawling libraries.

<br>

## Data Pipelines & Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data batch- and stream-processing, workflow automation, job scheduling, and other data pipeline tasks._

<details><summary><b><a href="https://github.com/celery/celery">Celery</a></b> (🥇46 ·  ⭐ 19K) - Asynchronous task queue/job queue based on distributed message passing. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.2K · 🔀 4.3K · 📦 70K · 📋 4.7K - 11% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 5.5M / month · 📦 15K · ⏱️ 29.05.2022):
	```
	pip install celery
	```
- [Conda](https://anaconda.org/conda-forge/celery) (📥 850K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge celery
	```
</details>
<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥇45 ·  ⭐ 27K) - Platform to programmatically author, schedule, and monitor workflows. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 2.4K · 🔀 11K · 📥 300K · 📋 5.7K - 16% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 6.9M / month · 📦 470 · ⏱️ 01.06.2022):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 620K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 73M · ⭐ 340 · ⏱️ 01.06.2022):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥇39 ·  ⭐ 5.5K) - Unified programming model to define and execute data processing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1.3K · 🔀 3.5K · ⏱️ 02.06.2022):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 6.9M / month · 📦 150 · ⏱️ 25.05.2022):
	```
	pip install apache-beam
	```
- [Conda](https://anaconda.org/conda-forge/apache-beam-with-aws) (📥 11K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge apache-beam-with-aws
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥇38 ·  ⭐ 9.2K · 📈) - The easiest way to automate your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 330 · 🔀 900 · 📦 800 · 📋 2.3K - 23% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 250K / month · 📦 64 · ⏱️ 24.05.2022):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 270K · ⏱️ 28.04.2022):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇38 ·  ⭐ 8.3K · 📉) - Simple job queues for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 260 · 🔀 1.3K · 📦 10K · 📋 960 - 18% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 580K / month · 📦 1.7K · ⏱️ 07.12.2021):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 72K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥈37 ·  ⭐ 16K) - Luigi is a Python module that helps you build complex pipelines of batch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 590 · 🔀 2.3K · 📦 1.7K · 📋 970 - 10% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 580K / month · 📦 400 · ⏱️ 23.09.2020):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 10K · 📦 2 · ⏱️ 02.05.2022):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥈37 ·  ⭐ 6.7K) - Always know what to expect from your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 290 · 🔀 950 · 📋 1.3K - 15% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 7M / month · 📦 32 · ⏱️ 26.05.2022):
	```
	pip install great_expectations
	```
- [Conda](https://anaconda.org/conda-forge/great-expectations) (📥 380K · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge great-expectations
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥈37 ·  ⭐ 4.8K) - An orchestration platform for the development, production, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 210 · 🔀 610 · 📦 390 · 📋 4.2K - 23% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 290K / month · 📦 90 · ⏱️ 31.05.2022):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 520K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥈37 ·  ⭐ 2.8K) - Computing with Python functions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 110 · 🔀 320 · 📦 190K · 📋 730 - 45% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib) (📥 25M / month · 📦 4.9K · ⏱️ 07.10.2021):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 9M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt-core">dbt</a></b> (🥈36 ·  ⭐ 4.9K) - dbt enables data analysts and engineers to transform their data using the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbt-labs/dbt-core) (👨‍💻 220 · 🔀 900 · 📥 370 · 📦 490 · 📋 2.8K - 11% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/dbt-labs/dbt-core
	```
- [PyPi](https://pypi.org/project/dbt) (📥 1.5M / month · 📦 30 · ⏱️ 06.12.2021):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 200K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/kedro-org/kedro">Kedro</a></b> (🥈35 ·  ⭐ 7.3K) - A Python framework for creating reproducible, maintainable and modular.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kedro-org/kedro) (👨‍💻 150 · 🔀 660 · 📦 880 · 📋 770 - 14% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/kedro-org/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 340K / month · 📦 38 · ⏱️ 09.05.2022):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Activeloop</a></b> (🥈31 ·  ⭐ 4.6K) - Dataset format for AI. Build, manage, query & visualize datasets.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/activeloopai/Hub) (👨‍💻 97 · 🔀 380 · 📋 370 - 14% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 5.7K / month · 📦 53 · ⏱️ 18.05.2022):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥈31 ·  ⭐ 2.4K) - The fastest way to build data pipelines. Develop iteratively,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 48 · 🔀 160 · 📦 42 · 📋 710 - 28% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 5.1K / month · 📦 5 · ⏱️ 02.06.2022):
	```
	pip install ploomber
	```
- [Conda](https://anaconda.org/conda-forge/ploomber) (📥 8.2K · ⏱️ 30.05.2022):
	```
	conda install -c conda-forge ploomber
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈31 ·  ⭐ 1.8K) - TFX is an end-to-end platform for deploying production ML pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 140 · 🔀 580 · 📋 780 - 32% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 340K / month · 📦 12 · ⏱️ 26.05.2022):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/combust/mleap">mleap</a></b> (🥈31 ·  ⭐ 1.4K) - MLeap: Deploy ML Pipelines to Production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/combust/mleap) (👨‍💻 73 · 🔀 300 · 📦 180 · 📋 440 - 20% open · ⏱️ 03.05.2022):

	```
	git clone https://github.com/combust/mleap
	```
- [PyPi](https://pypi.org/project/mleap) (📥 230K / month · 📦 26 · ⏱️ 04.04.2022):
	```
	pip install mleap
	```
- [Conda](https://anaconda.org/conda-forge/mleap) (📥 47K · ⏱️ 05.04.2022):
	```
	conda install -c conda-forge mleap
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈31 ·  ⭐ 1K) - Python Extract Transform and Load Tables of Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 54 · 🔀 170 · 📦 730 · 📋 440 - 17% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 200K / month · 📦 74 · ⏱️ 25.04.2022):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 76K · ⏱️ 26.04.2022):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥉30 ·  ⭐ 4K) - a little task queue for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 66 · 🔀 330 · 📦 940 · ⏱️ 31.05.2022):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 170K / month · 📦 160 · ⏱️ 28.12.2021):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 24K · ⏱️ 16.10.2019):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥉27 ·  ⭐ 2.1K) - ZenML : Build portable, production-ready MLOps pipelines... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zenml-io/zenml) (👨‍💻 32 · 🔀 160 · 📋 88 - 23% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/zenml-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 1.3K / month · ⏱️ 24.05.2022):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉27 ·  ⭐ 1.2K) - Agile Data Preparation Workflows madeeasy with Pandas, Dask,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 25 · 🔀 210 · 📋 230 - 13% open · ⏱️ 04.05.2022):

	```
	git clone https://github.com/hi-primus/optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 41K / month · ⏱️ 30.05.2019):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥉26 ·  ⭐ 2K · 💤) - Python library for creating data pipelines with chain functional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 25 · 🔀 120 · 📦 440 · 📋 130 - 6% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 140K / month · 📦 15 · ⏱️ 12.01.2021):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉26 ·  ⭐ 1.5K) - Run Python in Apache Storm topologies. Pythonic API, CLI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 42 · 🔀 220 · 📦 54 · 📋 330 - 21% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 4.1K / month · 📦 27 · ⏱️ 10.01.2022):
	```
	pip install streamparse
	```
</details>
<details><summary><b><a href="https://github.com/whylabs/whylogs">whylogs</a></b> (🥉26 ·  ⭐ 1.2K) - Open standard for end-to-end data and ML monitoring for any scale in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whylabs/whylogs) (👨‍💻 21 · 🔀 60 · 📥 50 · 📋 170 - 35% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/whylabs/whylogs
	```
- [PyPi](https://pypi.org/project/whylogs) (📥 21K / month · 📦 2 · ⏱️ 01.06.2022):
	```
	pip install whylogs
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/arq">arq</a></b> (🥉25 ·  ⭐ 1.2K) - Fast job queuing and RPC in python with asyncio and redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/arq) (👨‍💻 39 · 🔀 100 · 📦 230 · 📋 140 - 26% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/samuelcolvin/arq
	```
- [PyPi](https://pypi.org/project/arq) (📥 23K / month · 📦 11 · ⏱️ 09.03.2022):
	```
	pip install arq
	```
- [Conda](https://anaconda.org/conda-forge/arq) (📥 2.3K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge arq
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉23 ·  ⭐ 1.3K) - Concurrent data pipelines in Python . <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 12 · 🔀 80 · 📋 58 - 25% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 14K / month · 📦 9 · ⏱️ 06.01.2022):
	```
	pip install pypeln
	```
- [Conda](https://anaconda.org/conda-forge/pypeln) (📥 6.6K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge pypeln
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉23 ·  ⭐ 1.1K) - Python task queue using Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 25 · 🔀 62 · 📦 22 · 📋 68 - 48% open · ⏱️ 25.04.2022):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 1.4K / month · 📦 10 · ⏱️ 02.12.2021):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉22 ·  ⭐ 670) - Easy pipelines for pandas DataFrames. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 10 · 🔀 35 · 📦 41 · 📋 45 - 28% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 1.9K / month · 📦 5 · ⏱️ 12.05.2022):
	```
	pip install pdpipe
	```
- [Conda](https://anaconda.org/conda-forge/pdpipe) (📥 4.6K · ⏱️ 18.05.2022):
	```
	conda install -c conda-forge pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉18 ·  ⭐ 1.9K) - Deep Learning Pipelines for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/spark-deep-learning) (👨‍💻 17 · 🔀 460 · 📦 22 · 📋 100 - 74% open · ⏱️ 21.03.2022):

	```
	git clone https://github.com/databricks/spark-deep-learning
	```
</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉18 ·  ⭐ 1.6K) - A Python stream processing engine modeled after Yahoo! Pipes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerevu/riko) (👨‍💻 18 · 🔀 75 · 📋 30 - 73% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/nerevu/riko
	```
- [PyPi](https://pypi.org/project/riko) (📥 280 / month · 📦 1 · ⏱️ 28.12.2021):
	```
	pip install riko
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉18 ·  ⭐ 940 · 💤) - Python library for building highly effective data science.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 12 · 🔀 71 · 📦 20 · 📋 23 - 43% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 340 / month · ⏱️ 06.10.2021):
	```
	pip install d6tflow
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 1.9K) - A lightweight opinionated ETL framework, halfway between plain.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 17 · 🔀 94 · 📦 9 · 📋 38 - 63% open · ⏱️ 30.04.2022):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 380 / month · ⏱️ 29.05.2022):
	```
	pip install mara-pipelines
	```
</details>
<details><summary><b><a href="https://github.com/kubeflow-kale/kale">kale</a></b> (🥉17 ·  ⭐ 530 · 💤) - Kubeflows superfood for Data Scientists. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kubeflow-kale/kale) (👨‍💻 10 · 🔀 110 · 📋 160 - 52% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/kubeflow-kale/kale
	```
- [PyPi](https://pypi.org/project/kubeflow-kale) (📥 870 / month · ⏱️ 19.05.2021):
	```
	pip install kubeflow-kale
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈31 ·  ⭐ 2.6K · 💀) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/robinhood/faust">faust</a></b> (🥉30 ·  ⭐ 6.2K · 💀) - Python Stream Processing. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/databand-ai/dbnd">dbnd</a></b> (🥉26 ·  ⭐ 220) - DBND is an agile pipeline framework that helps data engineering teams.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉24 ·  ⭐ 1.5K · 💀) - Extract Transform Load for Python 3.5+. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉22 ·  ⭐ 2.7K · 💀) - Python clone of Spark, a MapReduce alike framework in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉22 ·  ⭐ 250 · 💀) - A pure Python implementation of Apache Sparks RDD and DStream.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉21 ·  ⭐ 870 · 💀) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉19 ·  ⭐ 340) - ML pipeline orchestration and model deployments on.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉19 ·  ⭐ 180) - BatchFlow helps you conveniently work with random or sequential.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉16 ·  ⭐ 170) - Fluent data pipelines for python and your shell. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉15 ·  ⭐ 1.2K · 💀) - Python Fast Dataflow programming framework for Data pipeline work(.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/vincentclaes/datajob">datajob</a></b> (🥉14 ·  ⭐ 92) - Build and deploy a serverless data pipeline on AWS with no effort. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Distributed Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that provide capabilities to distribute and parallelize machine learning tasks across large-scale compute infrastructure._

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇43 ·  ⭐ 21K) - An open source framework that provides a simple, universal API for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 700 · 🔀 3.6K · 📦 4.9K · 📋 10K - 22% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 1.2M / month · 📦 270 · ⏱️ 16.05.2022):
	```
	pip install ray
	```
- [Conda](https://anaconda.org/conda-forge/ray-tune) (📥 31K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge ray-tune
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇43 ·  ⭐ 10K) - Parallel computing with task scheduling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 540 · 🔀 1.5K · 📦 37K · 📋 4.4K - 16% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 6M / month · 📦 2.6K · ⏱️ 26.05.2022):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 5.7M · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇41 ·  ⭐ 1.4K) - A distributed task scheduler for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 270 · 🔀 620 · 📦 24K · 📋 2.9K - 38% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 5M / month · 📦 1.2K · ⏱️ 26.05.2022):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 7M · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥇36 ·  ⭐ 12K) - Distributed training framework for TensorFlow, Keras, PyTorch, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/horovod/horovod) (👨‍💻 150 · 🔀 2K · 📦 600 · 📋 2K - 15% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/horovod/horovod
	```
- [PyPi](https://pypi.org/project/horovod) (📥 70K / month · 📦 30 · ⏱️ 21.04.2022):
	```
	pip install horovod
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/h2o-3">H2O-3</a></b> (🥈33 ·  ⭐ 5.8K) - H2O is an Open Source, Distributed, Fast & Scalable Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/h2oai/h2o-3) (👨‍💻 230 · 🔀 1.9K · ⏱️ 01.06.2022):

	```
	git clone https://github.com/h2oai/h2o-3
	```
- [PyPi](https://pypi.org/project/h2o) (📥 410K / month · 📦 76 · ⏱️ 26.05.2022):
	```
	pip install h2o
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈32 ·  ⭐ 6.8K) - DeepSpeed is a deep learning optimization library that makes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 100 · 🔀 800 · 📦 260 · 📋 920 - 51% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 110K / month · 📦 10 · ⏱️ 25.05.2022):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 14K · ⭐ 3 · ⏱️ 09.03.2022):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈32 ·  ⭐ 3.9K) - Building Large-Scale AI Applications for Distributed Big Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 140 · 🔀 990 · 📦 36 · 📋 1.3K - 35% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 6.4K / month · 📦 1 · ⏱️ 02.06.2022):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4) (📦 4 · ⏱️ 20.04.2021):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈32 ·  ⭐ 2.2K) - IPython Parallel: Interactive Parallel Computing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 110 · 🔀 890 · 📋 330 - 16% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 48K / month · 📦 290 · ⏱️ 09.05.2022):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 610K · ⏱️ 10.05.2022):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈31 ·  ⭐ 1.8K) - PyTorch extensions for high performance and large scale training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 61 · 🔀 180 · 📦 300 · 📋 310 - 21% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 160K / month · 📦 15 · ⏱️ 09.03.2022):
	```
	pip install fairscale
	```
- [Conda](https://anaconda.org/conda-forge/fairscale) (📥 19K · ⏱️ 22.03.2022):
	```
	conda install -c conda-forge fairscale
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/metrics">metrics</a></b> (🥈31 ·  ⭐ 880) - Machine learning metrics for distributed, scalable PyTorch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/metrics) (👨‍💻 140 · 🔀 190 · 📥 690 · 📦 3.1K · 📋 370 - 15% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/PyTorchLightning/metrics
	```
- [PyPi](https://pypi.org/project/metrics) (📥 3.2K / month · 📦 14 · ⏱️ 28.04.2018):
	```
	pip install metrics
	```
- [Conda](https://anaconda.org/conda-forge/torchmetrics) (📥 350K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge torchmetrics
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥈29 ·  ⭐ 800) - Scalable Machine Learning with Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 74 · 🔀 230 · 📦 620 · 📋 490 - 50% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 81K / month · 📦 57 · ⏱️ 27.05.2022):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 320K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥈28 ·  ⭐ 3.8K) - TensorFlowOnSpark brings TensorFlow programs to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 34 · 🔀 970 · 📋 360 - 1% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 540K / month · 📦 5 · ⏱️ 21.04.2022):
	```
	pip install tensorflowonspark
	```
- [Conda](https://anaconda.org/conda-forge/tensorflowonspark) (📥 10K · ⏱️ 27.03.2022):
	```
	conda install -c conda-forge tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">SynapseML</a></b> (🥈28 ·  ⭐ 3.3K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 92 · 🔀 670 · 📋 580 - 42% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/synapseml) (📥 33K / month · 📦 1 · ⏱️ 12.01.2022):
	```
	pip install synapseml
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈28 ·  ⭐ 1.4K) - Petastorm library enables single machine or distributed training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 44 · 🔀 240 · 📥 310 · 📦 70 · 📋 280 - 50% open · ⏱️ 21.04.2022):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 82K / month · 📦 6 · ⏱️ 19.02.2022):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥉27 ·  ⭐ 1.3K) - Mesh TensorFlow: Model Parallelism Made Easier. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 48 · 🔀 220 · 📦 680 · 📋 110 - 87% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 22K / month · 📦 32 · ⏱️ 15.05.2022):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉27 ·  ⭐ 540) - Python bindings for MPI. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 20 · 🔀 77 · 📥 4.9K · 📋 77 - 16% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 210K / month · 📦 580 · ⏱️ 15.12.2021):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 1.1M · ⏱️ 04.04.2022):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥉26 ·  ⭐ 1.5K) - Distributed Deep learning with Keras & Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/elephas) (👨‍💻 27 · 🔀 300 · 📦 56 · 📋 160 - 11% open · ⏱️ 30.03.2022):

	```
	git clone https://github.com/maxpumperla/elephas
	```
- [PyPi](https://pypi.org/project/elephas) (📥 98K / month · 📦 3 · ⏱️ 30.03.2022):
	```
	pip install elephas
	```
- [Conda](https://anaconda.org/conda-forge/elephas) (📥 8.2K · ⏱️ 02.06.2021):
	```
	conda install -c conda-forge elephas
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉25 ·  ⭐ 2.5K) - Distributed Tensorflow, Keras and PyTorch on Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 100 · 🔀 710 · 📦 3 · 📋 1.4K - 39% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo) (📥 3.1K / month · 📦 1 · ⏱️ 01.06.2022):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥉23 ·  ⭐ 3.3K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 92 · 🔀 670 · 📋 580 - 42% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/mmlspark) (📥 2 / month · ⏱️ 18.03.2020):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉22 ·  ⭐ 630) - Python 3.6+ toolbox for submitting jobs to Slurm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 20 · 🔀 65 · 📋 67 - 31% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 20K / month · 📦 6 · ⏱️ 07.04.2022):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 6.1K · ⏱️ 10.02.2021):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉21 ·  ⭐ 2.6K) - a distributed deep learning platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 79 · 🔀 790 · 📦 1 · 📋 97 - 41% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 460 · ⏱️ 09.08.2021):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 280 · ⭐ 4 · ⏱️ 31.05.2022):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉21 ·  ⭐ 1K) - Decentralized deep learning in PyTorch. Built to train models on thousands.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 20 · 🔀 62 · 📦 7 · 📋 120 - 33% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 4.5K / month · 📦 1 · ⏱️ 20.12.2021):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉20 ·  ⭐ 3.2K) - A high performance and generic framework for distributed DNN training. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/byteps) (👨‍💻 19 · 🔀 450 · 📋 260 - 38% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/bytedance/byteps
	```
- [PyPi](https://pypi.org/project/byteps) (📥 69 / month · ⏱️ 02.08.2021):
	```
	pip install byteps
	```
- [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.3K · ⏱️ 03.03.2020):
	```
	docker pull bytepsimage/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/kingoflolz/mesh-transformer-jax">mesh-transformer-jax</a></b> (🥉17 ·  ⭐ 4.1K) - Model parallel transformers in JAX and Haiku. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kingoflolz/mesh-transformer-jax) (👨‍💻 23 · 🔀 530 · 📋 180 - 12% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/kingoflolz/mesh-transformer-jax
	```
</details>
<details><summary><b><a href="https://github.com/tunib-ai/parallelformers">parallelformers</a></b> (🥉15 ·  ⭐ 470) - Parallelformers: An Efficient Model Parallelization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tunib-ai/parallelformers) (👨‍💻 4 · 🔀 28 · 📦 7 · 📋 18 - 38% open · ⏱️ 02.03.2022):

	```
	git clone https://github.com/tunib-ai/parallelformers
	```
- [PyPi](https://pypi.org/project/parallelformers) (📥 200 / month · ⏱️ 29.12.2021):
	```
	pip install parallelformers
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈31 ·  ⭐ 4.7K) - Distributed Evolutionary Algorithms in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉21 ·  ⭐ 760 · 💀) - [DEPRECATED] Tensorflow wrapper for DataFrames on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepmind/launchpad">launchpad</a></b> (🥉21 ·  ⭐ 270) - Launchpad is a library that simplifies writing distributed.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉19 ·  ⭐ 280 · 💤) - Distributed scikit-learn meta-estimators in PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉19 ·  ⭐ 240 · 💤) - Massively parallel self-organizing maps: accelerate training on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉17 ·  ⭐ 970 · 💀) - Distributed Computing for AI Made Simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉14 ·  ⭐ 43 · 💤) - Distributed machine learning made simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/petuum/autodist">autodist</a></b> (🥉11 ·  ⭐ 120 · 💀) - Simple Distributed Deep Learning on TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Hyperparameter Optimization & AutoML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for hyperparameter optimization, automl and neural architecture search._

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇39 ·  ⭐ 6.5K) - A hyperparameter optimization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/optuna/optuna) (👨‍💻 200 · 🔀 700 · 📦 3.4K · 📋 1.2K - 10% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/optuna/optuna
	```
- [PyPi](https://pypi.org/project/optuna) (📥 3.9M / month · 📦 200 · ⏱️ 12.04.2022):
	```
	pip install optuna
	```
- [Conda](https://anaconda.org/conda-forge/optuna) (📥 280K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge optuna
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇36 ·  ⭐ 12K) - An open source AutoML toolkit for automate machine learning lifecycle,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 170 · 🔀 1.6K · 📦 230 · 📋 1.6K - 18% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 14K / month · 📦 30 · ⏱️ 18.04.2022):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇34 ·  ⭐ 8.5K) - AutoML library for deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 140 · 🔀 1.4K · 📥 4.7K · 📦 330 · 📋 820 - 10% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 46K / month · 📦 10 · ⏱️ 30.04.2022):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥇33 ·  ⭐ 6.3K) - Automated Machine Learning with scikit-learn. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 79 · 🔀 1.2K · 📥 36 · 📦 290 · 📋 890 - 12% open · ⏱️ 24.04.2022):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 38K / month · 📦 30 · ⏱️ 04.05.2022):
	```
	pip install auto-sklearn
	```
- [Conda](https://anaconda.org/conda-forge/auto-sklearn) (📥 4.6K · ⏱️ 18.02.2022):
	```
	conda install -c conda-forge auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥇33 ·  ⭐ 6.2K · 💤) - Distributed Asynchronous Hyperparameter Optimization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hyperopt/hyperopt) (👨‍💻 93 · 🔀 970 · 📦 6.7K · 📋 610 - 61% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/hyperopt/hyperopt
	```
- [PyPi](https://pypi.org/project/hyperopt) (📥 2.1M / month · 📦 420 · ⏱️ 17.11.2021):
	```
	pip install hyperopt
	```
- [Conda](https://anaconda.org/conda-forge/hyperopt) (📥 420K · ⏱️ 30.04.2022):
	```
	conda install -c conda-forge hyperopt
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥇33 ·  ⭐ 2.5K) - Hyperparameter tuning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 48 · 🔀 330 · 📦 1.4K · 📋 390 - 44% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner) (📥 600K / month · 📦 41 · ⏱️ 25.03.2022):
	```
	pip install keras-tuner
	```
- [Conda](https://anaconda.org/conda-forge/keras-tuner) (📥 6.6K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥇33 ·  ⭐ 2.3K) - Bayesian optimization in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 74 · 🔀 260 · 📦 250 · 📋 260 - 23% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 170K / month · 📦 13 · ⏱️ 21.04.2022):
	```
	pip install botorch
	```
- [Conda](https://anaconda.org/conda-forge/botorch) (📥 26K · ⏱️ 22.04.2022):
	```
	conda install -c conda-forge botorch
	```
</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥈32 ·  ⭐ 6.2K) - An open source python library for automated feature engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 65 · 🔀 820 · 📋 800 - 21% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 130K / month · 📦 64 · ⏱️ 27.05.2022):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 86K · ⏱️ 31.05.2022):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈32 ·  ⭐ 1.8K) - Adaptive Experimentation Platform. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 120 · 🔀 200 · 📦 280 · 📋 430 - 11% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 150K / month · 📦 15 · ⏱️ 26.04.2022):
	```
	pip install ax-platform
	```
- [Conda](https://anaconda.org/conda-forge/ax-platform) (📥 1.4K · ⏱️ 27.04.2022):
	```
	conda install -c conda-forge ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈31 ·  ⭐ 4.5K) - AutoGluon: AutoML for Image, Text, and Tabular Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/autogluon) (👨‍💻 73 · 🔀 590 · 📦 120 · 📋 700 - 23% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 69K / month · 📦 4 · ⏱️ 02.06.2022):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈31 ·  ⭐ 3.3K) - A Python toolbox for performing gradient-free optimization. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 49 · 🔀 310 · 📦 340 · 📋 260 - 41% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 42K / month · 📦 18 · ⏱️ 08.03.2022):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 26K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥈31 ·  ⭐ 2.3K · 💤) - Sequential model-based optimization with a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scikit-optimize/scikit-optimize) (👨‍💻 76 · 🔀 420 · 📦 2.7K · 📋 620 - 37% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-optimize/scikit-optimize
	```
- [PyPi](https://pypi.org/project/scikit-optimize) (📥 920K / month · 📦 170 · ⏱️ 12.10.2021):
	```
	pip install scikit-optimize
	```
- [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 550K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge scikit-optimize
	```
</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈28 ·  ⭐ 1.5K) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autonomio/talos) (👨‍💻 22 · 🔀 260 · 📦 140 · 📋 390 - 5% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/autonomio/talos
	```
- [PyPi](https://pypi.org/project/talos) (📥 1.8K / month · 📦 7 · ⏱️ 28.05.2022):
	```
	pip install talos
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈27 ·  ⭐ 2.1K · 💤) - Keras + Hyperopt: A very simple wrapper for convenient.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 21 · 🔀 300 · 📦 240 · 📋 250 - 37% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 13K / month · 📦 24 · ⏱️ 28.02.2019):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈26 ·  ⭐ 1.9K · 📉) - Python package for AutoML on Tabular Data with Feature.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 17 · 🔀 270 · 📦 45 · 📋 480 - 18% open · ⏱️ 14.04.2022):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 9.3K / month · 📦 2 · ⏱️ 02.03.2022):
	```
	pip install mljar-supervised
	```
- [Conda](https://anaconda.org/conda-forge/mljar-supervised) (📥 1.7K · ⏱️ 02.03.2022):
	```
	conda install -c conda-forge mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥉24 ·  ⭐ 3.4K · 💤) - Fast and flexible AutoML with learning guarantees. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/adanet) (👨‍💻 27 · 🔀 520 · 📦 43 · 📋 110 - 57% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/tensorflow/adanet
	```
- [PyPi](https://pypi.org/project/adanet) (📥 510 / month · 📦 2 · ⏱️ 09.07.2020):
	```
	pip install adanet
	```
</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉24 ·  ⭐ 520) - The worlds cleanest AutoML framework - Do hyperparameter tuning with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Neuraxio/Neuraxle) (👨‍💻 7 · 🔀 53 · 📦 32 · 📋 320 - 24% open · ⏱️ 11.05.2022):

	```
	git clone https://github.com/Neuraxio/Neuraxle
	```
- [PyPi](https://pypi.org/project/neuraxle) (📥 380 / month · 📦 1 · ⏱️ 15.04.2022):
	```
	pip install neuraxle
	```
</details>
<details><summary><b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉22 ·  ⭐ 540) - a distributed Hyperband implementation on Steroids. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/automl/HpBandSter) (👨‍💻 11 · 🔀 110 · 📦 220 · 📋 92 - 61% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/automl/HpBandSter
	```
- [PyPi](https://pypi.org/project/hpbandster) (📥 46K / month · 📦 10 · ⏱️ 06.11.2018):
	```
	pip install hpbandster
	```
- [Conda](https://anaconda.org/conda-forge/hpbandster) (📥 1.7K · ⏱️ 11.12.2020):
	```
	conda install -c conda-forge hpbandster
	```
</details>
<details><summary><b><a href="https://github.com/SimonBlanke/Hyperactive">Hyperactive</a></b> (🥉22 ·  ⭐ 400) - An optimization and data collection toolbox for convenient and fast.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SimonBlanke/Hyperactive) (👨‍💻 4 · 🔀 32 · 📥 100 · 📦 15 · 📋 45 - 11% open · ⏱️ 21.05.2022):

	```
	git clone https://github.com/SimonBlanke/Hyperactive
	```
- [PyPi](https://pypi.org/project/hyperactive) (📥 620 / month · 📦 3 · ⏱️ 04.05.2022):
	```
	pip install hyperactive
	```
</details>
<details><summary><b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉21 ·  ⭐ 360) - Lazy Predict help build a lot of basic models without much code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/shankarpandala/lazypredict) (👨‍💻 17 · 🔀 64 · 📦 300 · 📋 63 - 46% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/shankarpandala/lazypredict
	```
- [PyPi](https://pypi.org/project/lazypredict) (📥 6.7K / month · ⏱️ 17.02.2021):
	```
	pip install lazypredict
	```
- [Conda](https://anaconda.org/conda-forge/lazypredict) (📥 430 · ⏱️ 24.08.2021):
	```
	conda install -c conda-forge lazypredict
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉21 ·  ⭐ 340) - Automatically Build Multiple ML Models with a Single Line of Code... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 6 · 🔀 77 · 📦 16 · 📋 19 - 21% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 1.6K / month · 📦 2 · ⏱️ 01.06.2022):
	```
	pip install autoviml
	```
</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉20 ·  ⭐ 700 · 💤) - Use evolutionary algorithms instead of gridsearch in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rsteca/sklearn-deap) (👨‍💻 22 · 🔀 110 · 📦 33 · 📋 55 - 38% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/rsteca/sklearn-deap
	```
- [PyPi](https://pypi.org/project/sklearn-deap) (📥 1.2K / month · 📦 2 · ⏱️ 30.07.2021):
	```
	pip install sklearn-deap
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉19 ·  ⭐ 780) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 3 · 🔀 160 · 📦 3 · 📋 41 - 29% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 100 / month · ⏱️ 29.08.2020):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/google/model_search">model_search</a></b> (🥉11 ·  ⭐ 3.2K) - AutoML algorithms for model architecture search at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/model_search) (👨‍💻 1 · 🔀 360 · 📋 50 - 70% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google/model_search
	```
</details>
<details><summary>Show 23 hidden projects...</summary>

- <b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥈32 ·  ⭐ 8.6K) - A Python Automated Machine Learning tool that optimizes machine.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥈32 ·  ⭐ 6K · 💀) - A Python implementation of global optimization with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥈28 ·  ⭐ 230) - Asynchronous Distributed Hyperparameter Optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈26 ·  ⭐ 820 · 💀) - Gaussian Process Optimization using GPy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥈26 ·  ⭐ 700) - Sequential Model-based Algorithm Configuration. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉23 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - MLBox is a powerful Automated Machine Learning python library. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉22 ·  ⭐ 390 · 💀) - optimization routines for hyperparameter tuning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉22 ·  ⭐ 240) - Use advanced feature engineering strategies and select best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉20 ·  ⭐ 720 · 💀) - Python library to easily log experiments and parallelize.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉20 ·  ⭐ 640 · 💀) - An open source python library for scalable Bayesian optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉19 ·  ⭐ 310 · 💀) - Hyperparameter optimization that enables researchers to.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉18 ·  ⭐ 520 · 💀) - Auto Tune Models - A multi-tenant, multi-data system for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉17 ·  ⭐ 1.5K · 💀) - Open-source implementation of Google Vizier for hyper parameters.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - A web-based application for quick, scalable, and automated.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉16 ·  ⭐ 690 · 💀) - Easy hyperparameter optimization and automatic result.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉16 ·  ⭐ 200 · 💀) - A package for parallelizing the fit and flexibly scoring of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉15 ·  ⭐ 1.8K · 💀) - Provide an input CSV and a target field to predict, generate a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.6K · 💀) - PyTorch implementation of Efficient Neural Architecture Search via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉13 ·  ⭐ 190 · 💀) - An automatic ML model optimization tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉12 ·  ⭐ 100 · 💀) - Better, faster hyper-parameter optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 940 · 💀) - Genetic neural architecture search with Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉9 ·  ⭐ 120 · 💀) - A toolset for black-box hyperparameter optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating reinforcement learning & agent-based systems._

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇42 ·  ⭐ 28K) - A toolkit for developing and comparing reinforcement learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 360 · 🔀 7.8K · 📦 30K · 📋 1.7K - 6% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 670K / month · 📦 2.4K · ⏱️ 27.05.2022):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 110K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇33 ·  ⭐ 2.3K) - TF-Agents: A reliable, scalable and easy to use TensorFlow.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 120 · 🔀 630 · 📦 810 · 📋 560 - 23% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 240K / month · 📦 14 · ⏱️ 20.04.2022):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/AI4Finance-Foundation/FinRL">FinRL</a></b> (🥇30 ·  ⭐ 5K) - FinRL: The first open-source project for financial reinforcement learning... <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/AI4Finance-Foundation/FinRL) (👨‍💻 64 · 🔀 1.2K · 📦 11 · 📋 400 - 13% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/AI4Finance-Foundation/FinRL
	```
- [PyPi](https://pypi.org/project/finrl) (📥 270 / month · ⏱️ 08.01.2022):
	```
	pip install finrl
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈29 ·  ⭐ 9.8K) - Dopamine is a research framework for fast prototyping of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 15 · 🔀 1.3K · 📋 170 - 51% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 46K / month · 📦 37 · ⏱️ 20.05.2022):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥈29 ·  ⭐ 2.7K) - A library of reinforcement learning components and agents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/acme) (👨‍💻 68 · 🔀 330 · 📦 80 · 📋 210 - 19% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 3.5K / month · 📦 2 · ⏱️ 10.02.2022):
	```
	pip install dm-acme
	```
- [Conda](https://anaconda.org/conda-forge/dm-acme) (📥 2.3K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈29 ·  ⭐ 1.4K) - Doom-based AI Research Platform for Reinforcement Learning from Raw.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwydmuch/ViZDoom) (👨‍💻 47 · 🔀 340 · 📥 12K · 📦 140 · 📋 430 - 20% open · ⏱️ 07.05.2022):

	```
	git clone https://github.com/mwydmuch/ViZDoom
	```
- [PyPi](https://pypi.org/project/vizdoom) (📥 1.4K / month · 📦 14 · ⏱️ 18.04.2022):
	```
	pip install vizdoom
	```
</details>
<details><summary><b><a href="https://github.com/tensorlayer/TensorLayer">TensorLayer</a></b> (🥈28 ·  ⭐ 7K) - Deep Learning and Reinforcement Learning Library for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorlayer/TensorLayer) (👨‍💻 130 · 🔀 1.6K · 📥 1.4K · 📋 470 - 5% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/tensorlayer/tensorlayer
	```
- [PyPi](https://pypi.org/project/tensorlayer) (📥 2.7K / month · 📦 40 · ⏱️ 15.02.2022):
	```
	pip install tensorlayer
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉27 ·  ⭐ 2.6K) - A high-performance distributed training framework for Reinforcement.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 30 · 🔀 710 · 📦 91 · 📋 380 - 19% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 810 / month · 📦 1 · ⏱️ 13.05.2022):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥉26 ·  ⭐ 3.1K) - Tensorforce: a TensorFlow library for applied.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 82 · 🔀 520 · 📋 640 - 2% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 1.8K / month · 📦 27 · ⏱️ 07.09.2019):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉26 ·  ⭐ 1.5K) - A toolkit for reproducible reinforcement learning research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 78 · 🔀 260 · 📦 41 · 📋 1K - 20% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 510 / month · 📦 2 · ⏱️ 23.03.2021):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉25 ·  ⭐ 3.5K · 💤) - A fork of OpenAI Baselines, implementations of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hill-a/stable-baselines) (👨‍💻 110 · 🔀 690 · 📋 920 - 12% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/hill-a/stable-baselines
	```
- [PyPi](https://pypi.org/project/stable-baselines) (📥 8.6K / month · 📦 34 · ⏱️ 06.04.2021):
	```
	pip install stable-baselines
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥉23 ·  ⭐ 810) - A library of reinforcement learning building blocks in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/rlax) (👨‍💻 17 · 🔀 62 · 📦 50 · 📋 24 - 50% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/deepmind/rlax
	```
- [PyPi](https://pypi.org/project/rlax) (📥 4.1K / month · 📦 1 · ⏱️ 24.02.2022):
	```
	pip install rlax
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉22 ·  ⭐ 3.1K · 💤) - TensorFlow Reinforcement Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/trfl) (👨‍💻 13 · 🔀 380 · 📦 81 · 📋 22 - 27% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/deepmind/trfl
	```
- [PyPi](https://pypi.org/project/trfl) (📥 4.6K / month · 📦 3 · ⏱️ 16.08.2021):
	```
	pip install trfl
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉22 ·  ⭐ 850) - PFRL: a PyTorch-based deep reinforcement learning library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 16 · 🔀 110 · 📦 42 · 📋 66 - 40% open · ⏱️ 14.03.2022):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 1.5K / month · 📦 1 · ⏱️ 07.07.2021):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉21 ·  ⭐ 3.2K) - A platform for Reasoning systems (Reinforcement Learning,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 130 · 🔀 440 · 📋 120 - 35% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
- [PyPi](https://pypi.org/project/reagent) (📥 10 / month · ⏱️ 27.05.2020):
	```
	pip install reagent
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉21 ·  ⭐ 2.2K · 💤) - Reinforcement Learning Coach by Intel AI Lab enables easy.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 35 · 🔀 420 · 📋 270 - 32% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 200 / month · 📦 2 · ⏱️ 10.10.2019):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/google-research/rliable">rliable</a></b> (🥉12 ·  ⭐ 420) - [NeurIPS21 Outstanding Paper] Library for reliable evaluation on RL.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/rliable) (👨‍💻 2 · 🔀 22 · 📦 10 · ⏱️ 18.04.2022):

	```
	git clone https://github.com/google-research/rliable
	```
- [PyPi](https://pypi.org/project/rliable`):
	```
	pip install rliable`
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/openai/baselines">baselines</a></b> (🥈29 ·  ⭐ 13K · 💀) - OpenAI Baselines: high-quality implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥈29 ·  ⭐ 5.3K · 💀) - Deep Reinforcement Learning for Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥉23 ·  ⭐ 1.1K · 💀) - ChainerRL is a deep reinforcement learning library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉18 ·  ⭐ 6.7K) - A customisable 3D platform for agent-based AI research. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉18 ·  ⭐ 6.3K · 💀) - Game Agent Framework. Helping you create AIs / Bots that learn to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/enlite-ai/maze">Maze</a></b> (🥉12 ·  ⭐ 210) - Maze Applied Reinforcement Learning Framework. <code><a href="https://tldrlegal.com/search?q=Custom">❗️Custom</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating recommendation systems._

<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥇34 ·  ⭐ 13K) - Best Practices on Recommendation Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/recommenders) (👨‍💻 120 · 🔀 2.3K · 📥 180 · 📦 28 · 📋 700 - 19% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/microsoft/recommenders
	```
- [PyPi](https://pypi.org/project/recommenders) (📥 110K / month · 📦 2 · ⏱️ 01.04.2022):
	```
	pip install recommenders
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇30 ·  ⭐ 2.8K) - Fast Python Collaborative Filtering for Implicit Feedback Datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 30 · 🔀 530 · 📦 600 · 📋 400 - 18% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 140K / month · 📦 31 · ⏱️ 29.01.2022):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 350K · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥈29 ·  ⭐ 1.3K) - TensorFlow Recommenders is a library for building.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 33 · 🔀 190 · 📦 110 · 📋 270 - 55% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 2.9M / month · 📦 1 · ⏱️ 23.08.2021):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈28 ·  ⭐ 2.5K) - Learning to Rank in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 28 · 🔀 430 · 📋 290 - 18% open · ⏱️ 26.04.2022):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 72K / month · 📦 11 · ⏱️ 16.11.2021):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥈26 ·  ⭐ 4K · 📉) - A Python implementation of LightFM, a hybrid recommendation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 620 · 📦 740 · 📋 450 - 22% open · ⏱️ 09.03.2022):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 410K / month · 📦 45 · ⏱️ 27.11.2020):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 120K · ⏱️ 09.03.2022):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥈26 ·  ⭐ 1.9K) - A unified, comprehensive and efficient recommendation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 45 · 🔀 350 · 📋 420 - 13% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 1.9K / month · ⏱️ 25.02.2022):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 1.6K · ⏱️ 25.02.2022):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥉25 ·  ⭐ 590) - A Comparative Framework for Multimodal Recommender Systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 13 · 🔀 96 · 📦 110 · 📋 93 - 5% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 120K / month · 📦 15 · ⏱️ 19.02.2022):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 220K · ⏱️ 19.02.2022):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉20 ·  ⭐ 400) - A library of metrics for evaluating recommender systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 16 · 🔀 85 · 📦 25 · 📋 21 - 42% open · ⏱️ 17.04.2022):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 860 / month · ⏱️ 26.04.2022):
	```
	pip install recmetrics
	```
</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉18 ·  ⭐ 410 · 💤) - Case Recommender: A Flexible and Extensible Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/caserec/CaseRecommender) (👨‍💻 11 · 🔀 79 · 📦 10 · 📋 27 - 25% open · ⏱️ 25.11.2021):

	```
	git clone https://github.com/caserec/CaseRecommender
	```
- [PyPi](https://pypi.org/project/caserecommender) (📥 180 / month · ⏱️ 25.11.2021):
	```
	pip install caserecommender
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥈27 ·  ⭐ 5.4K · 💀) - A Python scikit for building and analyzing recommender.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉21 ·  ⭐ 1.2K · 💀) - A TensorFlow recommendation algorithm and framework in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉21 ·  ⭐ 980 · 💀) - fastFM: A Library for Factorization Machines. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lenskit/lkpy">lkpy</a></b> (🥉21 ·  ⭐ 210) - Python recommendation toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉18 ·  ⭐ 2.7K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ShopRunner/collie">Collie</a></b> (🥉17 ·  ⭐ 89) - A library for preparing, training, and evaluating scalable deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ylongqi/openrec">OpenRec</a></b> (🥉16 ·  ⭐ 390 · 💀) - OpenRec is an open-source and modular library for neural network-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Privacy Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for encrypted and privacy-preserving machine learning using methods like federated learning & differential privacy._

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇35 ·  ⭐ 8.1K) - A library for answering questions using data you cannot see. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenMined/PySyft) (👨‍💻 440 · 🔀 1.8K · 📋 3.1K - 11% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/OpenMined/PySyft
	```
- [PyPi](https://pypi.org/project/syft) (📥 5.1K / month · 📦 5 · ⏱️ 30.05.2022):
	```
	pip install syft
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈27 ·  ⭐ 1.2K) - Training PyTorch models with differential privacy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 50 · 🔀 200 · 📥 45 · 📦 110 · 📋 180 - 20% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 5.2K / month · 📦 11 · ⏱️ 06.05.2022):
	```
	pip install opacus
	```
- [Conda](https://anaconda.org/conda-forge/opacus) (📥 820 · ⏱️ 06.05.2022):
	```
	conda install -c conda-forge opacus
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥈26 ·  ⭐ 4.3K) - An Industrial Grade Federated Learning Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 74 · 🔀 1.3K · 📋 1.2K - 33% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/FederatedAI/FATE
	```
- [PyPi](https://pypi.org/project/ETAF) (📥 15 / month · ⏱️ 06.05.2020):
	```
	pip install ETAF
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥉25 ·  ⭐ 1.6K) - Library for training machine learning models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 46 · 🔀 350 · 📥 71 · 📋 150 - 43% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 32K / month · 📦 7 · ⏱️ 22.02.2022):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉24 ·  ⭐ 1K) - A Framework for Encrypted Machine Learning in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tf-encrypted/tf-encrypted) (👨‍💻 28 · 🔀 180 · 📦 61 · 📋 420 - 40% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/tf-encrypted/tf-encrypted
	```
- [PyPi](https://pypi.org/project/tf-encrypted) (📥 680 / month · 📦 9 · ⏱️ 07.03.2022):
	```
	pip install tf-encrypted
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉23 ·  ⭐ 1.1K) - A framework for Privacy Preserving Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 29 · 🔀 170 · 📦 18 · 📋 150 - 16% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 240 / month · ⏱️ 09.09.2021):
	```
	pip install crypten
	```
</details>
<br>

## Workflow & Experiment Tracking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to organize, track, and visualize machine learning experiments._

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇43 ·  ⭐ 5.9K) - TensorFlows Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 280 · 🔀 1.5K · 📦 110K · 📋 1.7K - 33% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 16M / month · 📦 2.4K · ⏱️ 20.01.2022):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 3M · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇41 ·  ⭐ 12K) - Open source platform for the machine learning lifecycle. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 420 · 🔀 2.7K · 📋 2.5K - 41% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 11M / month · 📦 310 · ⏱️ 28.05.2022):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 580K · ⏱️ 28.05.2022):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥇37 ·  ⭐ 9.8K) - Data Version Control | Git for Data & Models | ML Experiments Management. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 270 · 🔀 930 · 📥 87K · 📋 3.7K - 17% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 490K / month · 📦 47 · ⏱️ 28.04.2022):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 1.1M · ⏱️ 01.05.2022):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇37 ·  ⭐ 1.6K) - A library for training and deploying machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 260 · 🔀 780 · 📦 1.4K · 📋 1.1K - 33% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 9.9M / month · 📦 51 · ⏱️ 31.05.2022):
	```
	pip install sagemaker
	```
- [Conda](https://anaconda.org/conda-forge/sagemaker-python-sdk) (📥 280K · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge sagemaker-python-sdk
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥈36 ·  ⭐ 5.7K) - An open-source, low-code machine learning library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 78 · 🔀 1.3K · 📥 570 · 📦 2.2K · 📋 1.6K - 15% open · ⏱️ 01.05.2022):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 430K / month · 📦 13 · ⏱️ 10.04.2022):
	```
	pip install pycaret
	```
- [Conda](https://anaconda.org/conda-forge/pycaret) (📥 10K · ⏱️ 18.04.2022):
	```
	conda install -c conda-forge pycaret
	```
</details>
<details><summary><b><a href="https://github.com/wandb/client">wandb client</a></b> (🥈36 ·  ⭐ 3.9K) - A tool for visualizing and tracking your machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/client) (👨‍💻 110 · 🔀 320 · 📋 1.9K - 25% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 3.6M / month · 📦 260 · ⏱️ 26.05.2022):
	```
	pip install wandb
	```
- [Conda](https://anaconda.org/conda-forge/wandb) (📥 59K · ⏱️ 26.05.2022):
	```
	conda install -c conda-forge wandb
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈35 ·  ⭐ 3.3K) - Python notebooks with ML and deep learning examples with Azure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 60 · 🔀 2.1K · 📥 460 · 📋 1.3K - 21% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.5M / month · 📦 46 · ⏱️ 25.05.2022):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥈34 ·  ⭐ 7.3K · 📈) - tensorboard for pytorch (and chainer, mxnet, numpy, ...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 71 · 🔀 850 · 📥 350 · 📦 20K · 📋 440 - 16% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 3.5M / month · 📦 880 · ⏱️ 22.02.2022):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 700K · ⏱️ 23.02.2022):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈33 ·  ⭐ 3.2K) - ClearML - Auto-Magical CI/CD to streamline your ML workflow... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 49 · 🔀 430 · 📥 430 · 📦 250 · 📋 540 - 41% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 79K / month · 📦 8 · ⏱️ 24.05.2022):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈33 ·  ⭐ 1.4K) - This is the development home of the workflow management system.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 250 · 🔀 330 · 📦 1.1K · 📋 1K - 59% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 52K / month · 📦 210 · ⏱️ 31.05.2022):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 440K · ⏱️ 31.05.2022):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈31 ·  ⭐ 5.7K) - Build and manage real-life data science projects with ease!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 52 · 🔀 510 · 📦 290 · 📋 450 - 49% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 50K / month · 📦 9 · ⏱️ 27.05.2022):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 42K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈31 ·  ⭐ 3.8K) - Sacred is a tool to help you configure, organize, log and reproduce.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 97 · 🔀 340 · 📦 1.4K · 📋 540 - 16% open · ⏱️ 28.03.2022):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 52K / month · 📦 100 · ⏱️ 14.12.2020):
	```
	pip install sacred
	```
- [Conda](https://anaconda.org/conda-forge/sacred) (📥 460 · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge sacred
	```
</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈31 ·  ⭐ 2.9K) - Accelerated deep learning R&D. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/catalyst-team/catalyst) (👨‍💻 100 · 🔀 360 · 📦 550 · 📋 330 - 0% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/catalyst-team/catalyst
	```
- [PyPi](https://pypi.org/project/catalyst) (📥 2.7M / month · 📦 29 · ⏱️ 29.04.2022):
	```
	pip install catalyst
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥈31 ·  ⭐ 2.5K) - Aim easy-to-use and performant open-source ML experiment tracker. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 38 · 🔀 150 · 📦 80 · 📋 550 - 32% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 47K / month · 📦 4 · ⏱️ 02.06.2022):
	```
	pip install aim
	```
- [Conda](https://anaconda.org/conda-forge/aim) (📥 12K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge aim
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈30 ·  ⭐ 4.4K) - Deep Learning Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 31 · 🔀 580 · 📥 180 · 📦 1.2K · 📋 410 - 18% open · ⏱️ 01.04.2022):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 93K / month · 📦 23 · ⏱️ 06.01.2022):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥉28 ·  ⭐ 470) - For recording and retrieving metadata associated with ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 15 · 🔀 98 · 📥 1.7K · 📦 220 · 📋 87 - 28% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 670K / month · 📦 19 · ⏱️ 10.05.2022):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉27 ·  ⭐ 710) - Experiment tracking, ML developer tools. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 20 · 🔀 63 · 📥 1 · 📦 51 · 📋 360 - 44% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 3.2K / month · ⏱️ 11.05.2022):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉26 ·  ⭐ 1.2K) - Live training loss plot in Jupyter Notebook for Keras,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stared/livelossplot) (👨‍💻 17 · 🔀 140 · 📦 800 · 📋 74 - 5% open · ⏱️ 04.04.2022):

	```
	git clone https://github.com/stared/livelossplot
	```
- [PyPi](https://pypi.org/project/livelossplot) (📥 71K / month · 📦 11 · ⏱️ 04.04.2022):
	```
	pip install livelossplot
	```
</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉24 ·  ⭐ 1.1K) - Monitor deep learning model training and hardware usage from your mobile.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/labmlai/labml) (👨‍💻 7 · 🔀 78 · 📦 49 · 📋 26 - 53% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/labmlai/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 3.9K / month · 📦 6 · ⏱️ 12.05.2022):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉21 ·  ⭐ 1.5K) - Lore makes machine learning approachable for Software Engineers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/instacart/lore) (👨‍💻 26 · 🔀 130 · 📦 19 · 📋 45 - 57% open · ⏱️ 11.04.2022):

	```
	git clone https://github.com/instacart/lore
	```
- [PyPi](https://pypi.org/project/lore) (📥 730 / month · 📦 1 · ⏱️ 02.02.2022):
	```
	pip install lore
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉21 ·  ⭐ 370 · 💤) - Studio: Simplify and expedite model building process. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 21 · 🔀 52 · 📦 5 · 📋 250 - 22% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml) (📥 820 / month · ⏱️ 14.09.2021):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/replicate/keepsake">keepsake</a></b> (🥉18 ·  ⭐ 1.6K) - Version control for machine learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/replicate/keepsake) (👨‍💻 17 · 🔀 64 · 📋 190 - 65% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/replicate/keepsake
	```
- [PyPi](https://pypi.org/project/keepsake) (📥 500 / month · ⏱️ 11.03.2021):
	```
	pip install keepsake
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/neptune-ai/neptune-client">Neptune.ai</a></b> (🥈29 ·  ⭐ 290) - Experiment tracking tool and model registry. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥉28 ·  ⭐ 4.8K · 💀) - Official Kaggle API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉24 ·  ⭐ 2.4K · 💀) - Knock Knock: Get notified when your training ends with only two.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉23 ·  ⭐ 1.4K · 💀) - Simple tools for logging and visualizing, loading and training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉23 ·  ⭐ 250) - Gokart solves reproducibility, task dependencies, constraints of good code,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉21 ·  ⭐ 3.2K · 💀) - Debugging, monitoring and visualization for Python Machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉21 ·  ⭐ 1.6K · 💀) - Neural network graphs and training metrics for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉21 ·  ⭐ 530) - SciKit-Learn Laboratory (SKLL) makes it easy to run machine.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉21 ·  ⭐ 330 · 💀) - pyspark methods to enhance developer productivity. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉20 ·  ⭐ 620 · 💀) - Log TensorBoard events without touching TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉19 ·  ⭐ 330 · 💀) - Logging MXNet data for visualization in TensorBoard. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉18 ·  ⭐ 340 · 💀) - Open source production model management tool for data scientists. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gradsflow/chitra">chitra</a></b> (🥉17 ·  ⭐ 190) - A multi-functional library for full-stack Deep Learning. Simplifies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉16 ·  ⭐ 130 · 💀) - Lightweight, Python library for fast and reproducible experimentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google/caliban">caliban</a></b> (🥉14 ·  ⭐ 430 · 💀) - Research workflows made easy, locally and in the Cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉13 ·  ⭐ 120 · 💤) - Experiment tracking for machine and deep learning projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉8 ·  ⭐ 9 · 💀) - Train off-the-shelf machine learning models in one.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Model Serialization & Deployment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to serialize models to files, convert between a variety of model formats, and optimize models for deployment._

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇41 ·  ⭐ 13K) - Open standard for machine learning interoperability. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 240 · 🔀 2.7K · 📥 18K · 📦 7K · 📋 2K - 13% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 1.2M / month · 📦 370 · ⏱️ 17.02.2022):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 420K · ⏱️ 24.04.2022):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇32 ·  ⭐ 2.7K) - Core ML tools contain supporting tools for Core ML model.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 120 · 🔀 400 · 📥 4.2K · 📦 910 · 📋 1K - 33% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 96K / month · 📦 140 · ⏱️ 22.02.2022):
	```
	pip install coremltools
	```
- [Conda](https://anaconda.org/conda-forge/coremltools) (📥 31K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge coremltools
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/huggingface_hub">huggingface_hub</a></b> (🥈31 ·  ⭐ 430) - All the open source things related to the Hugging Face Hub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/huggingface_hub) (👨‍💻 63 · 🔀 100 · 📋 240 - 33% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/huggingface/huggingface_hub
	```
- [PyPi](https://pypi.org/project/huggingface_hub) (📥 6.3M / month · 📦 82 · ⏱️ 24.05.2022):
	```
	pip install huggingface_hub
	```
- [Conda](https://anaconda.org/conda-forge/huggingface_hub) (📥 150K · ⏱️ 25.05.2022):
	```
	conda install -c conda-forge huggingface_hub
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈30 ·  ⭐ 2.6K) - Serve, optimize and scale PyTorch models in production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 120 · 🔀 520 · 📥 1.8K · 📋 890 - 14% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 22K / month · 📦 9 · ⏱️ 13.05.2022):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 24K · ⏱️ 13.05.2022):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 1M · ⭐ 12 · ⏱️ 13.05.2022):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/openai/triton">triton</a></b> (🥈29 ·  ⭐ 3.7K) - Development repository for the Triton language and compiler. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/triton) (👨‍💻 41 · 🔀 290 · 📦 100 · 📋 200 - 37% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/openai/triton
	```
- [PyPi](https://pypi.org/project/triton) (📥 92K / month · 📦 3 · ⏱️ 02.06.2022):
	```
	pip install triton
	```
</details>
<details><summary><b><a href="https://github.com/bentoml/BentoML">BentoML</a></b> (🥈28 ·  ⭐ 3.5K) - The Unified Model Serving Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bentoml/BentoML) (👨‍💻 110 · 🔀 400 · 📥 1.5K · 📋 590 - 9% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/bentoml/BentoML
	```
- [PyPi](https://pypi.org/project/bentoml) (📥 37K / month · 📦 3 · ⏱️ 30.05.2022):
	```
	pip install bentoml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥈26 ·  ⭐ 2.8K) - Hummingbird compiles trained ML models into tensor computation for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 29 · 🔀 220 · 📥 170 · 📦 32 · 📋 240 - 20% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 2.8K / month · ⏱️ 25.04.2022):
	```
	pip install hummingbird-ml
	```
- [Conda](https://anaconda.org/conda-forge/hummingbird-ml) (📥 7.8K · ⏱️ 02.05.2022):
	```
	conda install -c conda-forge hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥈26 ·  ⭐ 2.1K) - Transform ML models into a native code (Java, C, Python, Go, JavaScript,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 13 · 🔀 190 · 📥 17 · 📦 35 · 📋 90 - 26% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 41K / month · 📦 3 · ⏱️ 26.04.2022):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥉25 ·  ⭐ 7.8K) - Production infrastructure for machine learning at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 24 · 🔀 590 · 📋 1.1K - 9% open · ⏱️ 23.04.2022):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.7K / month · 📦 1 · ⏱️ 10.01.2022):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉25 ·  ⭐ 1.2K) - Transpile trained scikit-learn estimators to C, Java,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nok/sklearn-porter) (👨‍💻 12 · 🔀 160 · 📦 43 · 📋 76 - 55% open · ⏱️ 22.05.2022):

	```
	git clone https://github.com/nok/sklearn-porter
	```
- [PyPi](https://pypi.org/project/sklearn-porter) (📥 300 / month · 📦 1 · ⏱️ 18.12.2019):
	```
	pip install sklearn-porter
	```
</details>
<details><summary><b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉19 ·  ⭐ 800 · 💤) - PyTorch to Keras model convertor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gmalivenko/pytorch2keras) (👨‍💻 13 · 🔀 130 · 📦 46 · 📋 120 - 44% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/gmalivenko/pytorch2keras
	```
- [PyPi](https://pypi.org/project/pytorch2keras) (📥 670 / month · 📦 1 · ⏱️ 14.05.2020):
	```
	pip install pytorch2keras
	```
</details>
<details><summary><b><a href="https://github.com/nebuly-ai/nebullvm">nebullvm</a></b> (🥉17 ·  ⭐ 1.2K · 🐣) - Easy-to-use library to boost AI inference leveraging state-of-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nebuly-ai/nebullvm) (👨‍💻 7 · 🔀 52 · 📦 1 · 📋 38 - 60% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/nebuly-ai/nebullvm
	```
- [PyPi](https://pypi.org/project/nebullvm) (📥 510 / month · ⏱️ 10.05.2022):
	```
	pip install nebullvm
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥉25 ·  ⭐ 5.6K · 💀) - MMdnn is a set of tools to help users inter-operate among different deep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉21 ·  ⭐ 190) - Highly optimized inference engine for Binarized.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉16 ·  ⭐ 350 · 💀) - Deploy tensorflow graphs for fast evaluation and export to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/backprop-ai/backprop">backprop</a></b> (🥉13 ·  ⭐ 230 · 💀) - Backprop makes it simple to use, finetune, and deploy state-of-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Model Interpretability

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to visualize, explain, debug, evaluate, and interpret machine learning models._

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇40 ·  ⭐ 16K) - A game theoretic approach to explain the output of any machine learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/slundberg/shap) (👨‍💻 180 · 🔀 2.4K · 📦 5.5K · 📋 2K - 69% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 4.9M / month · 📦 220 · ⏱️ 20.10.2021):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 1.2M · ⏱️ 23.01.2022):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇34 ·  ⭐ 1.2K) - Exploratory analysis of Bayesian models with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 120 · 🔀 280 · 📥 110 · 📦 2.3K · 📋 730 - 20% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 490K / month · 📦 100 · ⏱️ 13.05.2022):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 720K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/lutzroeder/netron">Netron</a></b> (🥇33 ·  ⭐ 19K) - Visualizer for neural network, deep learning, and machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lutzroeder/netron) (👨‍💻 2 · 🔀 2.2K · 📥 45K · 📦 7 · 📋 800 - 2% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/lutzroeder/netron
	```
- [PyPi](https://pypi.org/project/netron) (📥 11K / month · 📦 66 · ⏱️ 27.05.2022):
	```
	pip install netron
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇32 ·  ⭐ 9.8K · 💤) - Lime: Explaining the predictions of any machine learning classifier. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/lime) (👨‍💻 61 · 🔀 1.6K · 📦 2.3K · 📋 570 - 7% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/marcotcr/lime
	```
- [PyPi](https://pypi.org/project/lime) (📥 550K / month · 📦 110 · ⏱️ 26.06.2020):
	```
	pip install lime
	```
- [Conda](https://anaconda.org/conda-forge/lime) (📥 100K · ⏱️ 28.06.2020):
	```
	conda install -c conda-forge lime
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇32 ·  ⭐ 4.8K) - Fit interpretable models. Explain blackbox machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 29 · 🔀 580 · 📦 210 · 📋 290 - 31% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 92K / month · 📦 8 · ⏱️ 23.09.2021):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥇31 ·  ⭐ 3.2K) - Model interpretability and understanding for PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 83 · 🔀 330 · 📦 560 · 📋 370 - 23% open · ⏱️ 19.05.2022):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 53K / month · 📦 19 · ⏱️ 03.03.2022):
	```
	pip install captum
	```
- [Conda](https://anaconda.org/conda-forge/captum) (📥 1K · ⏱️ 04.03.2022):
	```
	conda install -c conda-forge captum
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥇31 ·  ⭐ 1.2K) - Model analysis tools for TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 43 · 🔀 250 · 📋 76 - 35% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 840K / month · 📦 21 · ⏱️ 16.05.2022):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/py-why/dowhy">DoWhy</a></b> (🥈30 ·  ⭐ 4.1K · 📈) - DoWhy is a Python library for causal inference that supports explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-why/dowhy) (👨‍💻 52 · 🔀 620 · 📥 29 · 📦 110 · 📋 200 - 27% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 110K / month · 📦 4 · ⏱️ 20.03.2022):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 5.5K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/MAIF/shapash">shapash</a></b> (🥈30 ·  ⭐ 1.7K) - Shapash makes Machine Learning models transparent and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MAIF/shapash) (👨‍💻 34 · 🔀 230 · 📦 74 · 📋 120 - 15% open · ⏱️ 09.05.2022):

	```
	git clone https://github.com/MAIF/shapash
	```
- [PyPi](https://pypi.org/project/shapash) (📥 17K / month · 📦 1 · ⏱️ 09.05.2022):
	```
	pip install shapash
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈30 ·  ⭐ 1.6K) - Algorithms for explaining machine learning models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 18 · 🔀 190 · 📦 170 · 📋 300 - 42% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 24K / month · 📦 24 · ⏱️ 18.05.2022):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥈29 ·  ⭐ 3.6K) - Visual analysis and diagnostic tools to facilitate machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 110 · 🔀 520 · 📋 670 - 13% open · ⏱️ 29.05.2022):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 630K / month · 📦 62 · ⏱️ 19.02.2022):
	```
	pip install yellowbrick
	```
- [Conda](https://anaconda.org/conda-forge/yellowbrick) (📥 27K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥈28 ·  ⭐ 2.1K) - A python library for decision tree visualization and model interpretation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 19 · 🔀 270 · 📦 390 · 📋 120 - 20% open · ⏱️ 29.04.2022):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 110K / month · 📦 14 · ⏱️ 29.04.2022):
	```
	pip install dtreeviz
	```
- [Conda](https://anaconda.org/conda-forge/dtreeviz) (📥 11K · ⏱️ 29.04.2022):
	```
	conda install -c conda-forge dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥈28 ·  ⭐ 1.3K) - A Python package to assess and improve fairness of machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 67 · 🔀 310 · 📋 380 - 44% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 97K / month · 📦 13 · ⏱️ 07.07.2021):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 18K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈28 ·  ⭐ 1.2K) - Quickly build Explainable AI dashboards that show the inner.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 14 · 🔀 160 · 📦 110 · 📋 180 - 6% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 39K / month · 📦 3 · ⏱️ 02.04.2022):
	```
	pip install explainerdashboard
	```
- [Conda](https://anaconda.org/conda-forge/explainerdashboard) (📥 16K · ⏱️ 15.02.2022):
	```
	conda install -c conda-forge explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈26 ·  ⭐ 1.7K) - A comprehensive set of fairness metrics for datasets and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 49 · 🔀 550 · 📦 160 · 📋 140 - 55% open · ⏱️ 05.05.2022):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 8K / month · 📦 8 · ⏱️ 04.03.2021):
	```
	pip install aif360
	```
- [Conda](https://anaconda.org/conda-forge/aif360) (📥 2.1K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge aif360
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈26 ·  ⭐ 500) - This project provides responsible AI user interfaces.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 24 · 🔀 120 · 📦 29 · 📋 260 - 19% open · ⏱️ 26.05.2022):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 11K / month · 📦 3 · ⏱️ 18.05.2022):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥈25 ·  ⭐ 1.7K · 💤) - Beyond Accuracy: Behavioral Testing of NLP models with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 12 · 🔀 160 · 📦 130 · 📋 92 - 13% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 47K / month · 📦 3 · ⏱️ 24.05.2021):
	```
	pip install checklist
	```
- [Conda](https://anaconda.org/conda-forge/checklist) (📥 3K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge checklist
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥈25 ·  ⭐ 1.1K) - Interpretability and explainability of data and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 29 · 🔀 220 · 📦 45 · 📋 64 - 59% open · ⏱️ 18.02.2022):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 1.1K / month · 📦 1 · ⏱️ 28.10.2020):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥉24 ·  ⭐ 770) - Interpretable ML package for concise, transparent, and accurate predictive.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 11 · 🔀 74 · 📦 17 · 📋 33 - 27% open · ⏱️ 28.05.2022):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 3.2K / month · ⏱️ 22.05.2022):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥉23 ·  ⭐ 1.5K · 💤) - A Python library that helps data scientists to infer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 22 · 🔀 170 · 📦 39 · 📋 110 - 19% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 1.5K / month · 📦 2 · ⏱️ 11.11.2021):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉22 ·  ⭐ 2.9K) - The Language Interpretability Tool: Interactively analyze NLP models for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 18 · 🔀 300 · 📦 10 · 📋 130 - 48% open · ⏱️ 15.03.2022):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp) (📥 1.2K / month · ⏱️ 21.12.2021):
	```
	pip install lit-nlp
	```
- [Conda](https://anaconda.org/conda-forge/lit-nlp) (📥 36K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉22 ·  ⭐ 640 · 💤) - Public facing deeplift repo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kundajelab/deeplift) (👨‍💻 11 · 🔀 150 · 📦 59 · 📋 84 - 42% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/kundajelab/deeplift
	```
- [PyPi](https://pypi.org/project/deeplift) (📥 880 / month · 📦 4 · ⏱️ 11.11.2020):
	```
	pip install deeplift
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥉21 ·  ⭐ 980) - Layers Outputs and Gradients in Keras. Made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 16 · 🔀 180 · 📦 140 · 📋 86 - 5% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 1.1K / month · 📦 5 · ⏱️ 19.06.2021):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉21 ·  ⭐ 930) - Interpretability Methods for tf.keras models with Tensorflow 2.x. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sicara/tf-explain) (👨‍💻 17 · 🔀 98 · 📦 120 · 📋 91 - 43% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/sicara/tf-explain
	```
- [PyPi](https://pypi.org/project/tf-explain) (📥 2.1K / month · 📦 7 · ⏱️ 18.11.2021):
	```
	pip install tf-explain
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉21 ·  ⭐ 840) - Generate Diverse Counterfactual Explanations for any machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 12 · 🔀 120 · 📋 130 - 48% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 54K / month · 📦 4 · ⏱️ 02.06.2022):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉21 ·  ⭐ 680) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 130 · 📋 110 - 53% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 7K / month · 📦 3 · ⏱️ 12.10.2021):
	```
	pip install witwidget
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard-plugin-wit) (📥 1M · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge tensorboard-plugin-wit
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 4.6K / month · ⏱️ 12.10.2021):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉21 ·  ⭐ 320) - Machine learning model evaluation made easy: plots,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/edublancas/sklearn-evaluation) (👨‍💻 8 · 🔀 31 · 📦 46 · 📋 39 - 23% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/edublancas/sklearn-evaluation
	```
- [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 1.2K / month · 📦 2 · ⏱️ 16.04.2022):
	```
	pip install sklearn-evaluation
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉20 ·  ⭐ 980 · 💤) - A toolbox to iNNvestigate neural networks predictions!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 19 · 🔀 220 · 📋 240 - 29% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 320 / month · 📦 1 · ⏱️ 14.11.2020):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/jalammar/ecco">ecco</a></b> (🥉19 ·  ⭐ 1.4K) - Explain, analyze, and visualize NLP language models. Ecco creates.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jalammar/ecco) (👨‍💻 10 · 🔀 94 · 📥 17 · 📦 7 · 📋 36 - 38% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/jalammar/ecco
	```
- [PyPi](https://pypi.org/project/ecco) (📥 330 / month · 📦 1 · ⏱️ 09.01.2022):
	```
	pip install ecco
	```
- [Conda](https://anaconda.org/conda-forge/ecco) (📥 440 · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge ecco
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉19 ·  ⭐ 520 · 💤) - Code for the TCAV ML interpretability project. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tcav) (👨‍💻 19 · 🔀 130 · 📦 12 · 📋 61 - 11% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/tensorflow/tcav
	```
- [PyPi](https://pypi.org/project/tcav) (📥 130 / month · 📦 3 · ⏱️ 23.02.2021):
	```
	pip install tcav
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉17 ·  ⭐ 820 · 💤) - XAI - An eXplainability toolbox for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EthicalML/xai) (👨‍💻 3 · 🔀 120 · 📦 15 · 📋 9 - 22% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/EthicalML/xai
	```
- [PyPi](https://pypi.org/project/xai) (📥 170 / month · 📦 6 · ⏱️ 30.10.2021):
	```
	pip install xai
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉17 ·  ⭐ 470) - Leave One Feature Out Importance. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 3 · 🔀 53 · 📦 19 · 📋 20 - 20% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 470 / month · 📦 1 · ⏱️ 27.04.2022):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉16 ·  ⭐ 700 · 💤) - Code for High-Precision Model-Agnostic Explanations paper. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/anchor) (👨‍💻 10 · 🔀 97 · 📋 70 - 27% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/marcotcr/anchor
	```
- [PyPi](https://pypi.org/project/anchor_exp) (📥 1.2K / month · ⏱️ 26.06.2020):
	```
	pip install anchor_exp
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret-text">interpret-text</a></b> (🥉14 ·  ⭐ 320) - A library that incorporates state-of-the-art explainers for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret-text) (👨‍💻 17 · 🔀 57 · 📋 74 - 78% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/interpretml/interpret-text
	```
- [PyPi](https://pypi.org/project/interpret-text) (📥 66 / month · ⏱️ 07.12.2021):
	```
	pip install interpret-text
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈29 ·  ⭐ 2.5K · 💀) - A library for debugging/inspecting machine learning classifiers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥈29 ·  ⭐ 1.6K · 💀) - Python library for interactive topic model visualization... <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥈27 ·  ⭐ 4.4K · 💀) - A collection of infrastructure and tools for research in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈27 ·  ⭐ 2.2K · 💀) - An intuitive library to add plotting functionality to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥈25 ·  ⭐ 2.9K · 💀) - Neural network visualization toolkit for keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepchecks/deepchecks">Deep Checks</a></b> (🥈25 ·  ⭐ 1.5K) - Test Suites for Validating ML Models & Data. Deepchecks is.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉24 ·  ⭐ 1K) - moDel Agnostic Language for Exploration and eXplanation. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉22 ·  ⭐ 710 · 💀) - Package for interpreting scikit-learns decision tree.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥉22 ·  ⭐ 500 · 💀) - Code to compute permutation and drop-column.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉21 ·  ⭐ 480 · 💀) - Bias and Fairness Audit Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉20 ·  ⭐ 1K) - Python Library for Model Interpretation/Explanations. <code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code>
- <b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉19 ·  ⭐ 260) - Tensorflows Fairness Evaluation and Visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉18 ·  ⭐ 280) - a tool that leverages rich metadata and lineage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉16 ·  ⭐ 670 · 💀) - Visualization toolkit for neural networks in PyTorch! Demo --. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉15 ·  ⭐ 320 · 💀) - Explainable AI framework for data scientists. Explain & debug any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉14 ·  ⭐ 80 · 💤) - Contextual AI adds explainability to different stages of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉12 ·  ⭐ 99 · 💀) - Tools for training explainable models using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉11 ·  ⭐ 37) - Bias Detector is a python package for detecting bias in machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Vector Similarity Search (ANN)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Approximate Nearest Neighbor Search and Vector Indexing/Similarity Search._

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 2.9K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥇38 ·  ⭐ 10K) - Vector database for scalable similarity search and AI applications. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 210 · 🔀 1.5K · 📥 30K · 📋 5.2K - 5% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 38K / month · 📦 16 · ⏱️ 02.04.2022):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 960K · ⭐ 19 · ⏱️ 13.05.2022):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥇34 ·  ⭐ 17K) - A library for efficient similarity search and clustering of dense vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 98 · 🔀 2.6K · 📦 640 · 📋 1.8K - 9% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 38K / month · 📦 16 · ⏱️ 02.04.2022):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 330K · ⏱️ 09.02.2022):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥈32 ·  ⭐ 9.9K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 81 · 🔀 1K · 📦 2.1K · 📋 340 - 10% open · ⏱️ 25.03.2022):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 1.3M / month · 📦 240 · ⏱️ 18.09.2020):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/python-annoy) (📥 240K · ⏱️ 23.04.2022):
	```
	conda install -c conda-forge python-annoy
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥈31 ·  ⭐ 2.8K) - Non-Metric Space Library (NMSLIB): An efficient similarity search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/nmslib) (👨‍💻 48 · 🔀 380 · 📦 620 · 📋 400 - 15% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/nmslib/nmslib
	```
- [PyPi](https://pypi.org/project/nmslib) (📥 100K / month · 📦 47 · ⏱️ 03.02.2021):
	```
	pip install nmslib
	```
- [Conda](https://anaconda.org/conda-forge/nmslib) (📥 53K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge nmslib
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥈29 ·  ⭐ 620) - A Python nearest neighbor descent for approximate nearest neighbors. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 20 · 🔀 85 · 📦 1.7K · 📋 100 - 48% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 3.3M / month · 📦 26 · ⏱️ 14.05.2022):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 630K · ⏱️ 15.05.2022):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥉28 ·  ⭐ 2K) - Header-only C++/python library for fast approximate nearest neighbors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 56 · 🔀 360 · 📦 240 · 📋 250 - 51% open · ⏱️ 16.04.2022):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib) (📥 360K / month · 📦 24 · ⏱️ 14.02.2022):
	```
	pip install hnswlib
	```
- [Conda](https://anaconda.org/conda-forge/hnswlib) (📥 41K · ⏱️ 16.04.2022):
	```
	conda install -c conda-forge hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉20 ·  ⭐ 900) - Nearest Neighbor Search with Neighborhood Graph and Tree for High-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 13 · 🔀 91 · 📋 100 - 14% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 17K / month · 📦 8 · ⏱️ 16.05.2022):
	```
	pip install ngt
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉23 ·  ⭐ 1.5K · 💀) - A fast, efficient universal vector embedding utility package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉21 ·  ⭐ 710 · 💀) - Python framework for fast (approximated) nearest neighbour search in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kakao/n2">N2</a></b> (🥉19 ·  ⭐ 520 · 💀) - TOROS N2 - lightweight approximate Nearest Neighbor library which runs.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 900 · 💀) - Approximate Nearest Neighbor Search for Sparse Data in Python!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Probabilistics & Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries providing capabilities for probabilistic programming/reasoning, bayesian inference, gaussian processes, or statistics._

<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥇40 ·  ⭐ 6.6K) - Probabilistic Programming in Python: Bayesian Modeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pymc-devs/pymc) (👨‍💻 380 · 🔀 1.6K · 📥 1.9K · 📦 630 · 📋 2.7K - 7% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pymc-devs/pymc
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 350K / month · 📦 240 · ⏱️ 15.03.2022):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 410K · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥇37 ·  ⭐ 3.7K) - Probabilistic reasoning and statistical analysis in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 450 · 🔀 970 · 📋 1.2K - 44% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 940K / month · 📦 310 · ⏱️ 14.02.2022):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 58K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇33 ·  ⭐ 7.5K) - Deep universal probabilistic programming with Python and PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 130 · 🔀 920 · 📦 730 · 📋 980 - 21% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 220K / month · 📦 59 · ⏱️ 24.03.2022):
	```
	pip install pyro-ppl
	```
- [Conda](https://anaconda.org/conda-forge/pyro-ppl) (📥 9.8K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥈32 ·  ⭐ 2.5K) - Hidden Markov Models in Python, with scikit-learn like API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 40 · 🔀 700 · 📦 1.3K · 📋 390 - 13% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 290K / month · 📦 130 · ⏱️ 10.02.2022):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 120K · ⏱️ 12.02.2022):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥈32 ·  ⭐ 2.1K) - Python Library for learning (Structure and Parameter), inference.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 110 · 🔀 630 · 📥 150 · 📦 360 · 📋 790 - 28% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 91K / month · 📦 11 · ⏱️ 30.03.2022):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈32 ·  ⭐ 1.6K) - Gaussian processes in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 78 · 🔀 420 · 📦 360 · 📋 780 - 17% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 25K / month · 📦 29 · ⏱️ 10.05.2022):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 12K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥈31 ·  ⭐ 2.8K) - A highly efficient and modular implementation of Gaussian Processes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 93 · 🔀 420 · 📦 590 · 📋 1.1K - 26% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 190K / month · 📦 38 · ⏱️ 04.12.2021):
	```
	pip install gpytorch
	```
- [Conda](https://anaconda.org/conda-forge/gpytorch) (📥 34K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/twopirllc/pandas-ta">pandas-ta</a></b> (🥈29 ·  ⭐ 2.5K) - Technical Analysis Indicators - Pandas TA is an easy to use.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/twopirllc/pandas-ta) (👨‍💻 44 · 🔀 560 · 📦 670 · 📋 390 - 13% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/twopirllc/pandas-ta
	```
- [PyPi](https://pypi.org/project/pandas-ta) (📥 70K / month · 📦 16 · ⏱️ 28.07.2021):
	```
	pip install pandas-ta
	```
- [Conda](https://anaconda.org/conda-forge/pandas-ta) (📥 870 · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge pandas-ta
	```
</details>
<details><summary><b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥈29 ·  ⭐ 830 · 💤) - Describing statistical models in Python using symbolic formulas. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pydata/patsy) (👨‍💻 16 · 🔀 94 · 📦 52K · 📋 140 - 51% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/pydata/patsy
	```
- [PyPi](https://pypi.org/project/patsy) (📥 10M / month · 📦 2.6K · ⏱️ 26.09.2021):
	```
	pip install patsy
	```
- [Conda](https://anaconda.org/conda-forge/patsy) (📥 4.8M · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge patsy
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥉28 ·  ⭐ 2.9K) - Fast, flexible and easy to use probabilistic modelling in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 65 · 🔀 530 · 📦 700 · 📋 660 - 7% open · ⏱️ 21.02.2022):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 36K / month · 📦 46 · ⏱️ 21.02.2022):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 86K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉28 ·  ⭐ 600) - Sensitivity Analysis Library in Python. Contains Sobol, Morris, FAST, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 36 · 🔀 180 · 📋 280 - 16% open · ⏱️ 19.04.2022):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 130K / month · 📦 58 · ⏱️ 06.02.2022):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 81K · ⏱️ 04.09.2021):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉27 ·  ⭐ 1.4K) - A Python package for Bayesian forecasting with object-oriented design.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/orbit) (👨‍💻 16 · 🔀 99 · 📦 6 · 📋 370 - 16% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/uber/orbit
	```
- [PyPi](https://pypi.org/project/orbit-ml) (📥 88K / month · 📦 1 · ⏱️ 28.04.2022):
	```
	pip install orbit-ml
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉25 ·  ⭐ 780) - BAyesian Model-Building Interface (Bambi) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 25 · 🔀 86 · 📦 28 · 📋 250 - 15% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 4.8K / month · 📦 3 · ⏱️ 18.05.2022):
	```
	pip install bambi
	```
- [Conda](https://anaconda.org/conda-forge/bambi) (📥 8.1K · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge bambi
	```
</details>
<details><summary><b><a href="https://github.com/baal-org/baal">Baal</a></b> (🥉19 ·  ⭐ 600) - Library to enable Bayesian active learning in your research or labeling.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/baal-org/baal) (👨‍💻 14 · 🔀 54 · 📋 75 - 24% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 800 / month · 📦 1 · ⏱️ 03.05.2022):
	```
	pip install baal
	```
- [Conda](https://anaconda.org/conda-forge/baal) (📥 1.6K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge baal
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥈31 ·  ⭐ 2.3K · 💀) - Python Kalman filtering and optimal estimation library. Implements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉28 ·  ⭐ 4.7K · 💀) - A probabilistic programming language in TensorFlow. Deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥉28 ·  ⭐ 1.1K) - Statistical package in Python based on Pandas. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉25 ·  ⭐ 190) - PyStan, a Python interface to Stan, a platform for statistical modeling... <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉22 ·  ⭐ 240) - Multiple Pairwise Comparisons (Post Hoc) Tests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉21 ·  ⭐ 510 · 💀) - Bayesian inference in HSMMs and HMMs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉20 ·  ⭐ 190) - Functional tensors for probabilistic programming. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉15 ·  ⭐ 2.1K · 💀) - A probabilistic programming library for Bayesian deep learning,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Adversarial Robustness

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing the robustness of machine learning models against attacks with adversarial/malicious examples._

<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥇33 ·  ⭐ 3K) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 99 · 🔀 830 · 📦 230 · 📋 690 - 13% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 6.5K / month · 📦 7 · ⏱️ 24.05.2022):
	```
	pip install adversarial-robustness-toolbox
	```
- [Conda](https://anaconda.org/conda-forge/adversarial-robustness-toolbox) (📥 9.6K · ⏱️ 24.05.2022):
	```
	conda install -c conda-forge adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈30 ·  ⭐ 2.2K) - A Python toolbox to create adversarial examples that fool neural networks.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bethgelab/foolbox) (👨‍💻 32 · 🔀 400 · 📦 290 · 📋 350 - 6% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/bethgelab/foolbox
	```
- [PyPi](https://pypi.org/project/foolbox) (📥 2.9K / month · 📦 13 · ⏱️ 02.04.2022):
	```
	pip install foolbox
	```
- [Conda](https://anaconda.org/conda-forge/foolbox) (📥 6K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge foolbox
	```
</details>
<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥈29 ·  ⭐ 5.5K · 💤) - An adversarial example library for constructing attacks,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 130 · 🔀 1.3K · 📦 320 · 📋 450 - 5% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 1.4K / month · 📦 11 · ⏱️ 24.07.2021):
	```
	pip install cleverhans
	```
- [Conda](https://anaconda.org/conda-forge/cleverhans) (📥 3K · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge cleverhans
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈29 ·  ⭐ 2K) - TextAttack is a Python framework for adversarial attacks, data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 52 · 🔀 250 · 📦 78 · 📋 210 - 19% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 6.7K / month · 📦 7 · ⏱️ 25.05.2022):
	```
	pip install textattack
	```
- [Conda](https://anaconda.org/conda-forge/textattack) (📥 2.9K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge textattack
	```
</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉19 ·  ⭐ 700) - A library for experimenting with, training and evaluating neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MadryLab/robustness) (👨‍💻 13 · 🔀 140 · 📦 77 · 📋 74 - 24% open · ⏱️ 14.02.2022):

	```
	git clone https://github.com/MadryLab/robustness
	```
- [PyPi](https://pypi.org/project/robustness) (📥 1.2K / month · 📦 2 · ⏱️ 01.12.2020):
	```
	pip install robustness
	```
- [Conda](https://anaconda.org/conda-forge/robustness) (📥 3.6K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge robustness
	```
</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉18 ·  ⭐ 1.2K) - Advbox is a toolbox to generate adversarial examples that fool neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/advboxes/AdvBox) (👨‍💻 19 · 🔀 240 · 📋 38 - 21% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/advboxes/AdvBox
	```
- [PyPi](https://pypi.org/project/advbox) (📥 28 / month · ⏱️ 05.12.2018):
	```
	pip install advbox
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉23 ·  ⭐ 1.1K) - A Toolbox for Adversarial Robustness Research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/textflint/textflint">textflint</a></b> (🥉16 ·  ⭐ 560) - Unified Multilingual Robustness Evaluation Toolkit for Natural.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/airbnb/artificial-adversary">Adversary</a></b> (🥉15 ·  ⭐ 360 · 💀) - Tool to generate adversarial text examples and test machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## GPU Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that require and make use of CUDA/GPU system capabilities to optimize data handling and machine learning tasks._

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇38 ·  ⭐ 6.1K) - NumPy & SciPy for GPU. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cupy/cupy) (👨‍💻 300 · 🔀 600 · 📥 32K · 📦 1K · 📋 1.8K - 22% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/cupy/cupy
	```
- [PyPi](https://pypi.org/project/cupy) (📥 26K / month · 📦 160 · ⏱️ 26.05.2022):
	```
	pip install cupy
	```
- [Conda](https://anaconda.org/conda-forge/cupy) (📥 1.5M · ⏱️ 01.06.2022):
	```
	conda install -c conda-forge cupy
	```
- [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 55K · ⭐ 7 · ⏱️ 26.05.2022):
	```
	docker pull cupy/cupy
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥇31 ·  ⭐ 4.8K) - cuDF - GPU DataFrame Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 240 · 🔀 600 · 📋 4.6K - 15% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1.4K / month · 📦 5 · ⏱️ 01.06.2020):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥈29 ·  ⭐ 2.8K) - cuML - RAPIDS Machine Learning Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 150 · 🔀 400 · 📋 2K - 33% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 750 / month · 📦 3 · ⏱️ 01.06.2020):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥈29 ·  ⭐ 1.3K) - CUDA integration for Python, plus shiny features. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pycuda) (👨‍💻 76 · 🔀 260 · 📦 1.3K · 📋 220 - 29% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/inducer/pycuda
	```
- [PyPi](https://pypi.org/project/pycuda) (📥 30K / month · 📦 190 · ⏱️ 03.04.2021):
	```
	pip install pycuda
	```
- [Conda](https://anaconda.org/conda-forge/pycuda) (📥 69K · ⏱️ 05.05.2022):
	```
	conda install -c conda-forge pycuda
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈28 ·  ⭐ 6.4K) - A PyTorch Extension: Tools for easy mixed precision and distributed.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 93 · 🔀 1K · 📦 1K · 📋 1K - 58% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 85K · ⏱️ 06.04.2022):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈28 ·  ⭐ 3.8K) - ArrayFire: a general purpose GPU library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 81 · 🔀 490 · 📥 2.4K · 📋 1.5K - 15% open · ⏱️ 12.05.2022):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 660 / month · 📦 5 · ⏱️ 22.02.2022):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥈28 ·  ⭐ 2.9K) - A simple command-line utility for querying and monitoring GPU status. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 13 · 🔀 220 · 📦 1.9K · 📋 83 - 26% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 610K / month · 📦 99 · ⏱️ 02.01.2021):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 130K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉24 ·  ⭐ 3.9K) - A GPU-accelerated library containing highly optimized building blocks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 74 · 🔀 500 · 📋 1.2K - 16% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥉24 ·  ⭐ 1K) - cuGraph - RAPIDS Graph Analytics Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 85 · 🔀 200 · 📋 830 - 10% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 180 / month · 📦 1 · ⏱️ 01.06.2020):
	```
	pip install cugraph
	```
- [Conda](https://anaconda.org/conda-forge/libcugraph) (📥 7.1K · ⏱️ 29.04.2021):
	```
	conda install -c conda-forge libcugraph
	```
</details>
<details><summary><b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥉23 ·  ⭐ 890) - Python interface to GPU-powered libraries. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lebedov/scikit-cuda) (👨‍💻 46 · 🔀 170 · 📦 190 · 📋 220 - 22% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/lebedov/scikit-cuda
	```
- [PyPi](https://pypi.org/project/scikit-cuda) (📥 590 / month · 📦 44 · ⏱️ 27.05.2019):
	```
	pip install scikit-cuda
	```
</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉21 ·  ⭐ 1.8K · 💤) - BlazingSQL is a lightweight, GPU accelerated, SQL engine for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/BlazingDB/blazingsql) (👨‍💻 49 · 🔀 170 · 📋 720 - 18% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/BlazingDB/blazingsql
	```
- [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 940 · ⏱️ 11.11.2019):
	```
	conda install -c blazingsql blazingsql-protocol
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉20 ·  ⭐ 870) - General purpose GPU compute framework built on Vulkan to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 19 · 🔀 61 · 📥 160 · 📦 3 · 📋 180 - 32% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/KomputeProject/kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 120 / month · ⏱️ 13.04.2022):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉19 ·  ⭐ 600) - GPU accelerated signal processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cusignal) (👨‍💻 38 · 🔀 91 · 📋 130 - 11% open · ⏱️ 23.05.2022):

	```
	git clone https://github.com/rapidsai/cusignal
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥉22 ·  ⭐ 870 · 💀) - A Python module for getting the GPU status from NVIDA GPUs using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥉21 ·  ⭐ 200) - Python 3 Bindings for NVML library. Get NVIDIA GPU status inside your.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉20 ·  ⭐ 80 · 💀) - Python 3 Bindings for the NVIDIA Management Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉15 ·  ⭐ 660 · 💀) - Library for faster pinned CPU - GPU transfer in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉13 ·  ⭐ 150) - jupyter/ipython experiment containers for GPU and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Tensorflow Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend TensorFlow with additional capabilities._

<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇36 ·  ⭐ 1.5K) - Useful extra functionality for TensorFlow 2.x maintained by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 190 · 🔀 520 · 📦 6.5K · 📋 930 - 23% open · ⏱️ 24.05.2022):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 1.4M / month · 📦 170 · ⏱️ 21.05.2022):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥇35 ·  ⭐ 3.3K) - TFDS is a collection of datasets ready to use with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 260 · 🔀 1.3K · 📋 1.2K - 47% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.1M / month · 📦 160 · ⏱️ 02.06.2022):
	```
	pip install tensorflow-datasets
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-datasets) (📥 4.7K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥇35 ·  ⭐ 3.1K) - A library for transfer learning by reusing parts of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 90 · 🔀 1.6K · 📦 12K · 📋 640 - 2% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 5.8M / month · 📦 280 · ⏱️ 14.04.2021):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 63K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥈34 ·  ⭐ 12K) - Library of deep learning models and datasets designed to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 240 · 🔀 3K · 📦 1.2K · 📋 1.2K - 45% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 12K / month · 📦 93 · ⏱️ 17.06.2020):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈33 ·  ⭐ 920) - Input pipeline framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 200 · 📦 880 · 📋 190 - 19% open · ⏱️ 25.05.2022):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 3.6M / month · 📦 56 · ⏱️ 13.05.2022):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈32 ·  ⭐ 1.2K) - A toolkit to optimize ML models for deployment for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 67 · 🔀 280 · 📦 1.8K · 📋 320 - 52% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 170K / month · 📦 20 · ⏱️ 18.03.2022):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-preprocessing">Keras-Preprocessing</a></b> (🥉29 ·  ⭐ 1K) - Utilities for working with image data, text data, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-preprocessing) (👨‍💻 52 · 🔀 440 · 📋 200 - 47% open · ⏱️ 17.02.2022):

	```
	git clone https://github.com/keras-team/keras-preprocessing
	```
- [PyPi](https://pypi.org/project/keras-preprocessing) (📥 11M / month · 📦 1.5K · ⏱️ 14.05.2020):
	```
	pip install keras-preprocessing
	```
- [Conda](https://anaconda.org/conda-forge/keras-preprocessing) (📥 1.3M · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge keras-preprocessing
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉29 ·  ⭐ 560) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 94 · 🔀 230 · 📋 520 - 35% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 210K / month · 📦 24 · ⏱️ 18.05.2022):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉26 ·  ⭐ 2K · 💤) - Implementation of EfficientNet model. Keras and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/efficientnet) (👨‍💻 10 · 🔀 460 · 📥 240K · 📦 1K · 📋 120 - 51% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/qubvel/efficientnet
	```
- [PyPi](https://pypi.org/project/efficientnet) (📥 140K / month · 📦 10 · ⏱️ 15.09.2020):
	```
	pip install efficientnet
	```
- [Conda](https://anaconda.org/anaconda/efficientnet) (📥 92 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda efficientnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉26 ·  ⭐ 920) - Training neural models with structured signals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 33 · 🔀 170 · 📦 230 · 📋 62 - 4% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 16K / month · 📦 2 · ⏱️ 18.08.2020):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉23 ·  ⭐ 330) - The TensorFlow Cloud repository provides APIs that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 27 · 🔀 69 · 📦 150 · 📋 81 - 67% open · ⏱️ 24.03.2022):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 160K / month · 📦 1 · ⏱️ 17.06.2021):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉22 ·  ⭐ 610) - Data compression in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 14 · 🔀 210 · 📋 84 - 2% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 1.3K / month · 📦 1 · ⏱️ 30.05.2022):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉21 ·  ⭐ 780) - TensorFlow implementation of an arbitrary order Factorization Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geffy/tffm) (👨‍💻 10 · 🔀 190 · 📦 11 · 📋 40 - 45% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/geffy/tffm
	```
- [PyPi](https://pypi.org/project/tffm) (📥 1.9K / month · 📦 1 · ⏱️ 17.01.2022):
	```
	pip install tffm
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉20 ·  ⭐ 790) - Framework-agnostic implementation for state-of-the-art saliency.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/saliency) (👨‍💻 15 · 🔀 160 · 📦 29 · 📋 40 - 35% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/PAIR-code/saliency
	```
- [PyPi](https://pypi.org/project/saliency) (📥 500 / month · 📦 3 · ⏱️ 03.05.2021):
	```
	pip install saliency
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉20 ·  ⭐ 1K · 💀) - High level network definitions with pre-trained weights in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Jax Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Jax with additional capabilities._

<details><summary><b><a href="https://github.com/patrick-kidger/equinox">equinox</a></b> (🥇23 ·  ⭐ 570) - Callable PyTrees and filtered transforms = neural networks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/patrick-kidger/equinox) (👨‍💻 6 · 🔀 30 · 📦 20 · 📋 45 - 13% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/patrick-kidger/equinox
	```
- [PyPi](https://pypi.org/project/equinox) (📥 1.3K / month · 📦 4 · ⏱️ 06.05.2022):
	```
	pip install equinox
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/ucl-bug/jaxdf">jaxdf</a></b> (🥉9 ·  ⭐ 50) - A JAX-based research framework for writing differentiable.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Sklearn Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend scikit-learn with additional capabilities._

<details><summary><b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇36 ·  ⭐ 4K · 📈) - A library of extension and helper modules for Pythons data.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/mlxtend) (👨‍💻 90 · 🔀 770 · 📦 6K · 📋 430 - 28% open · ⏱️ 27.05.2022):

	```
	git clone https://github.com/rasbt/mlxtend
	```
- [PyPi](https://pypi.org/project/mlxtend) (📥 1.7M / month · 📦 150 · ⏱️ 27.05.2022):
	```
	pip install mlxtend
	```
- [Conda](https://anaconda.org/conda-forge/mlxtend) (📥 210K · ⏱️ 27.05.2022):
	```
	conda install -c conda-forge mlxtend
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇34 ·  ⭐ 5.9K) - A Python Package to Tackle the Curse of Imbalanced.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 63 · 🔀 1.2K · 📦 11K · 📋 510 - 9% open · ⏱️ 16.05.2022):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 2.8M / month · 📦 260 · ⏱️ 16.05.2022):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 220K · ⏱️ 16.05.2022):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥇34 ·  ⭐ 1.9K) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 52 · 🔀 360 · 📦 3.5K · 📋 250 - 25% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 3.8M / month · 📦 23 · ⏱️ 14.10.2018):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 160K · ⏱️ 10.05.2022):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈25 ·  ⭐ 3.3K) - Genetic Algorithm, Particle Swarm Optimization, Simulated.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 14 · 🔀 760 · 📦 75 · 📋 150 - 27% open · ⏱️ 08.04.2022):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 2.4K / month · 📦 6 · ⏱️ 14.01.2022):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈25 ·  ⭐ 1.1K · 💤) - Multivariate imputation and matrix completion.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/iskandr/fancyimpute) (👨‍💻 12 · 🔀 170 · 📦 1.2K · 📋 110 - 0% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/iskandr/fancyimpute
	```
- [PyPi](https://pypi.org/project/fancyimpute) (📥 15K / month · 📦 29 · ⏱️ 21.10.2021):
	```
	pip install fancyimpute
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈25 ·  ⭐ 820) - Extra blocks for scikit-learn pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 50 · 🔀 86 · 📦 50 · 📋 240 - 9% open · ⏱️ 20.04.2022):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 14K / month · 📦 6 · ⏱️ 20.04.2022):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 19K · ⏱️ 21.04.2022):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥉23 ·  ⭐ 1.6K) - Large-scale linear classification, regression and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/lightning) (👨‍💻 17 · 🔀 200 · 📥 230 · 📦 100 · 📋 93 - 54% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/scikit-learn-contrib/lightning
	```
- [PyPi](https://pypi.org/project/sklearn-contrib-lightning) (📥 2.1K / month · 📦 6 · ⏱️ 30.01.2022):
	```
	pip install sklearn-contrib-lightning
	```
- [Conda](https://anaconda.org/conda-forge/sklearn-contrib-lightning) (📥 170K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge sklearn-contrib-lightning
	```
</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥉23 ·  ⭐ 650 · 💤) - scikit-learn cross validators for iterative.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trent-b/iterative-stratification) (👨‍💻 6 · 🔀 62 · 📦 210 · 📋 19 - 21% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/trent-b/iterative-stratification
	```
- [PyPi](https://pypi.org/project/iterative-stratification) (📥 2.7M / month · 📦 8 · ⏱️ 03.10.2021):
	```
	pip install iterative-stratification
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥉23 ·  ⭐ 580 · 💤) - (AAAI 20) A Python Toolbox for Machine Learning Model.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (👨‍💻 1 · 🔀 99 · 📦 460 · 📋 14 - 78% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 32K / month · 📦 3 · ⏱️ 02.04.2022):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉19 ·  ⭐ 400 · 💤) - A Python library for dynamic classifier and ensemble selection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 13 · 🔀 73 · 📦 25 · 📋 140 - 11% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 570 / month · 📦 2 · ⏱️ 08.02.2021):
	```
	pip install deslib
	```
</details>
<details><summary><b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉17 ·  ⭐ 340) - Topological Data Analysis for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-tda/scikit-tda) (👨‍💻 4 · 🔀 43 · 📦 31 · 📋 19 - 78% open · ⏱️ 13.03.2022):

	```
	git clone https://github.com/scikit-tda/scikit-tda
	```
- [PyPi](https://pypi.org/project/scikit-tda) (📥 1.3K / month · ⏱️ 03.08.2021):
	```
	pip install scikit-tda
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥈26 ·  ⭐ 400 · 💀) - scikit-learn inspired API for CRFsuite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈25 ·  ⭐ 750 · 💀) - A scikit-learn based module for multi-label et. al... <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉21 ·  ⭐ 460 · 💀) - machine learning with logical rules in Python. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉20 ·  ⭐ 140) - Fast solver for L1-type problems: Lasso, sparse Logisitic regression,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉17 ·  ⭐ 110 · 💤) - Data Analysis Baseline Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉16 ·  ⭐ 200) - Scikit-learn compatible estimation of general graphical models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Pytorch Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Pytorch with additional capabilities._

<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇33 ·  ⭐ 4.5K) - The easiest way to use deep metric learning in your application. Modular,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 24 · 🔀 550 · 📦 270 · 📋 360 - 14% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 2.7M / month · 📦 10 · ⏱️ 28.05.2022):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 7K · ⏱️ 28.05.2022):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/accelerate">accelerate</a></b> (🥇33 ·  ⭐ 2.5K) - A simple way to train and use PyTorch models with multi-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/accelerate) (👨‍💻 44 · 🔀 170 · 📦 550 · 📋 270 - 31% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/huggingface/accelerate
	```
- [PyPi](https://pypi.org/project/accelerate) (📥 2.8M / month · 📦 13 · ⏱️ 20.05.2022):
	```
	pip install accelerate
	```
- [Conda](https://anaconda.org/conda-forge/accelerate) (📥 2.3K · ⏱️ 23.05.2022):
	```
	conda install -c conda-forge accelerate
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/lightning-flash">lightning-flash</a></b> (🥇29 ·  ⭐ 1.5K) - Your PyTorch AI Factory - Flash enables you to easily.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/lightning-flash) (👨‍💻 69 · 🔀 170 · 📦 82 · 📋 460 - 6% open · ⏱️ 11.05.2022):

	```
	git clone https://github.com/PyTorchLightning/lightning-flash
	```
- [PyPi](https://pypi.org/project/lightning-flash) (📥 7.2K / month · 📦 3 · ⏱️ 11.05.2022):
	```
	pip install lightning-flash
	```
- [Conda](https://anaconda.org/conda-forge/lightning-flash) (📥 1.8K · ⏱️ 12.05.2022):
	```
	conda install -c conda-forge lightning-flash
	```
</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥈27 ·  ⭐ 2.4K · 💤) - torch-optimizer -- collection of optimizers for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 25 · 🔀 240 · 📦 600 · 📋 45 - 35% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 51K / month · 📦 23 · ⏱️ 31.10.2021):
	```
	pip install torch_optimizer
	```
- [Conda](https://anaconda.org/conda-forge/torch-optimizer) (📥 1.5K · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge torch-optimizer
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈25 ·  ⭐ 4.1K) - Differentiable ODE solvers with full GPU support and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 20 · 🔀 730 · 📦 250 · 📋 180 - 22% open · ⏱️ 22.04.2022):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 6.7K / month · 📦 20 · ⏱️ 22.04.2022):
	```
	pip install torchdiffeq
	```
- [Conda](https://anaconda.org/conda-forge/torchdiffeq) (📥 5.2K · ⏱️ 03.06.2021):
	```
	conda install -c conda-forge torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥈25 ·  ⭐ 640) - PyTorch Extension Library of Optimized Autograd Sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 25 · 🔀 89 · 📋 180 - 17% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 23K / month · 📦 37 · ⏱️ 11.03.2022):
	```
	pip install torch-sparse
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_sparse) (📥 89K · ⏱️ 17.05.2022):
	```
	conda install -c conda-forge pytorch_sparse
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈24 ·  ⭐ 1.7K) - PyTorch implementation of TabNet paper :.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 19 · 🔀 340 · 📋 240 - 15% open · ⏱️ 23.03.2022):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 18K / month · 📦 7 · ⏱️ 02.02.2021):
	```
	pip install pytorch-tabnet
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-tabnet) (📥 530 · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈24 ·  ⭐ 1.2K) - PyTorch extensions for fast R&D prototyping and Kaggle.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 7 · 🔀 96 · 📋 28 - 21% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 8.8K / month · 📦 6 · ⏱️ 10.03.2022):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥈24 ·  ⭐ 990) - PyTorch Extension Library of Optimized Scatter Operations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 20 · 🔀 120 · 📋 260 - 8% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 29K / month · 📦 43 · ⏱️ 22.10.2021):
	```
	pip install torch-scatter
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_scatter) (📥 79K · ⏱️ 21.03.2022):
	```
	conda install -c conda-forge pytorch_scatter
	```
</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥈23 ·  ⭐ 1.6K · 💤) - A collection of extensions and data-loaders for few-shot.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tristandeleu/pytorch-meta) (👨‍💻 12 · 🔀 210 · 📦 90 · 📋 140 - 34% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tristandeleu/pytorch-meta
	```
- [PyPi](https://pypi.org/project/torchmeta) (📥 3.3K / month · ⏱️ 20.09.2021):
	```
	pip install torchmeta
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥈23 ·  ⭐ 1.5K · 💤) - Pretrained EfficientNet, EfficientNet-Lite, MixNet,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) (👨‍💻 5 · 🔀 190 · 📦 100 · 📋 53 - 3% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/rwightman/gen-efficientnet-pytorch
	```
- [PyPi](https://pypi.org/project/geffnet) (📥 15K / month · 📦 1 · ⏱️ 08.07.2021):
	```
	pip install geffnet
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥉22 ·  ⭐ 1.4K · 💤) - higher is a pytorch library allowing users to obtain higher.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/higher) (👨‍💻 9 · 🔀 98 · 📦 140 · 📋 99 - 49% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/facebookresearch/higher
	```
- [PyPi](https://pypi.org/project/higher) (📥 21K / month · 📦 2 · ⏱️ 14.07.2020):
	```
	pip install higher
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉21 ·  ⭐ 840) - An implementation of Performer, a linear attention-based.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/performer-pytorch) (👨‍💻 6 · 🔀 110 · 📦 46 · 📋 76 - 43% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/lucidrains/performer-pytorch
	```
- [PyPi](https://pypi.org/project/performer-pytorch) (📥 17K / month · 📦 4 · ⏱️ 02.02.2022):
	```
	pip install performer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥉20 ·  ⭐ 1.7K · 💤) - Reformer, the efficient Transformer, in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 10 · 🔀 240 · 📋 120 - 11% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 3.9K / month · ⏱️ 06.11.2021):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉20 ·  ⭐ 980 · 💤) - Differentiable SDE solvers with GPU support and efficient.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 5 · 🔀 100 · 📦 15 · 📋 48 - 14% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/google-research/torchsde
	```
- [PyPi](https://pypi.org/project/torchsde) (📥 750 / month · ⏱️ 20.07.2021):
	```
	pip install torchsde
	```
- [Conda](https://anaconda.org/conda-forge/torchsde) (📥 9.5K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge torchsde
	```
</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉19 ·  ⭐ 1K) - Fast, general, and tested differentiable structured prediction.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/harvardnlp/pytorch-struct) (👨‍💻 16 · 🔀 81 · 📋 54 - 44% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/harvardnlp/pytorch-struct
	```
- [PyPi](https://pypi.org/project/torch-struct) (📥 58K / month · ⏱️ 14.02.2021):
	```
	pip install torch-struct
	```
</details>
<details><summary><b><a href="https://github.com/szagoruyko/pytorchviz">pytorchviz</a></b> (🥉18 ·  ⭐ 2.2K · 💤) - A small package to create visualizations of PyTorch execution.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/szagoruyko/pytorchviz) (👨‍💻 6 · 🔀 230 · 📦 680 · 📋 56 - 37% open · ⏱️ 15.06.2021):

	```
	git clone https://github.com/szagoruyko/pytorchviz
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉18 ·  ⭐ 1K) - Tez is a super-simple and lightweight Trainer for PyTorch. It also.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/tez) (👨‍💻 1 · 🔀 130 · 📦 27 · 📋 32 - 50% open · ⏱️ 10.05.2022):

	```
	git clone https://github.com/abhishekkrthakur/tez
	```
- [PyPi](https://pypi.org/project/tez) (📥 660 / month · 📦 2 · ⏱️ 15.04.2022):
	```
	pip install tez
	```
</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉17 ·  ⭐ 6K) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geohot/tinygrad) (👨‍💻 59 · 🔀 600 · 📦 2 · 📋 110 - 19% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉16 ·  ⭐ 640) - The goal of this library is to generate more helpful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/tensor-sensor) (👨‍💻 4 · 🔀 33 · 📦 7 · 📋 23 - 34% open · ⏱️ 07.04.2022):

	```
	git clone https://github.com/parrt/tensor-sensor
	```
- [PyPi](https://pypi.org/project/tensor-sensor) (📥 1.8K / month · ⏱️ 11.12.2021):
	```
	pip install tensor-sensor
	```
- [Conda](https://anaconda.org/conda-forge/tensor-sensor) (📥 310 · ⏱️ 11.12.2021):
	```
	conda install -c conda-forge tensor-sensor
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/madgrad">madgrad</a></b> (🥉15 ·  ⭐ 760) - MADGRAD Optimization Method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/madgrad) (👨‍💻 2 · 🔀 55 · 📦 25 · 📋 8 - 12% open · ⏱️ 10.03.2022):

	```
	git clone https://github.com/facebookresearch/madgrad
	```
- [PyPi](https://pypi.org/project/madgrad) (📥 7.6K / month · ⏱️ 08.03.2022):
	```
	pip install madgrad
	```
</details>
<details><summary><b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉15 ·  ⭐ 370 · 💤) - High-level batteries-included neural network training library for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/achaiah/pywick) (👨‍💻 4 · 🔀 38 · 📦 6 · 📋 14 - 14% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/achaiah/pywick
	```
- [PyPi](https://pypi.org/project/pywick) (📥 33 / month · ⏱️ 22.10.2021):
	```
	pip install pywick
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇32 ·  ⭐ 8.5K · 💀) - Pretrained ConvNets for pytorch: NASNet, ResNeXt,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈27 ·  ⭐ 7K · 💀) - A PyTorch implementation of EfficientNet and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈27 ·  ⭐ 3.6K · 💀) - Model summary in PyTorch similar to `model.summary()`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈23 ·  ⭐ 2K · 💀) - Training RNNs as Fast as CNNs (https://arxiv.org/abs/1709.02755). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥉21 ·  ⭐ 520) - A simplified framework and utilities for PyTorch. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉20 ·  ⭐ 2.9K · 💀) - An optimizer that trains as fast as Adam and as good as SGD. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉20 ·  ⭐ 1.5K · 💤) - pip install antialiased-cnns to improve stability and.. <code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉17 ·  ⭐ 1.5K · 💀) - Implementation of LambdaNetworks, a new approach to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉16 ·  ⭐ 2.1K · 💀) - A tiny scalar-valued autograd engine and a neural net library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TorchDrift/TorchDrift">TorchDrift</a></b> (🥉13 ·  ⭐ 210 · 💤) - Drift Detection for your PyTorch Models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#database-clients">best-of-python - DB Clients</a></b> ( ⭐ 2.2K)  - Collection of database clients for python.

<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇49 ·  ⭐ 9.7K) - Ecosystem of open-source software for mathematics, science, and engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.3K · 🔀 4.2K · 📥 350K · 📦 520K · 📋 8.6K - 20% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 45M / month · 📦 58K · ⏱️ 18.05.2022):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 23M · ⏱️ 20.05.2022):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇44 ·  ⭐ 9.3K) - A computer algebra system written in pure Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.1K · 🔀 3.7K · 📥 450K · 📦 43K · 📋 12K - 35% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 1.7M / month · 📦 4.1K · ⏱️ 20.03.2022):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 2.1M · ⏱️ 20.03.2022):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥇38 ·  ⭐ 19K) - Streamlit The fastest way to build data apps in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 140 · 🔀 1.7K · 📦 310 · 📋 2.4K - 23% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 970K / month · 📦 400 · ⏱️ 01.06.2022):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇36 ·  ⭐ 5.7K) - A Comprehensive and Scalable Python Library for Outlier Detection (Anomaly.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 39 · 🔀 1.1K · 📦 1.3K · 📋 260 - 50% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 480K / month · 📦 32 · ⏱️ 13.05.2022):
	```
	pip install pyod
	```
- [Conda](https://anaconda.org/conda-forge/pyod) (📥 22K · ⏱️ 13.05.2022):
	```
	conda install -c conda-forge pyod
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇34 ·  ⭐ 3.6K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 190 · 🔀 1.3K · 📦 94 · 📋 1.5K - 31% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 8.7K / month · 📦 5 · ⏱️ 01.06.2022):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 10K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge deepchem
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥇33 ·  ⭐ 6.2K) - An open source multi-tool for exploring and publishing data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 64 · 🔀 410 · 📥 39 · 📦 670 · 📋 1.3K - 26% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 250K / month · 📦 160 · ⏱️ 02.05.2022):
	```
	pip install datasette
	```
- [Conda](https://anaconda.org/conda-forge/datasette) (📥 4.2K · ⏱️ 24.03.2022):
	```
	conda install -c conda-forge datasette
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥇32 ·  ⭐ 8K) - Awesome pre-trained models toolkit based on PaddlePaddle.(300+.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 61 · 🔀 1.6K · 📥 570 · 📦 800 · 📋 1.1K - 40% open · ⏱️ 15.04.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 16K / month · 📦 5 · ⏱️ 28.12.2021):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥇32 ·  ⭐ 7.2K · 📉) - Wrap UIs around any model, share with anyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 74 · 🔀 450 · 📦 1 · 📋 720 - 20% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio) (📥 280K / month · 📦 20 · ⏱️ 01.06.2022):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥇32 ·  ⭐ 5.8K) - Efficiently computes derivatives of numpy code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 51 · 🔀 820 · 📦 3.5K · 📋 390 - 42% open · ⏱️ 08.04.2022):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.2M / month · 📦 280 · ⏱️ 08.04.2022):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 210K · ⏱️ 25.07.2019):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/datalad/datalad">datalad</a></b> (🥇32 ·  ⭐ 320) - Keep code, data, containers under control with git and git-annex. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/datalad/datalad) (👨‍💻 47 · 🔀 90 · 📋 3.5K - 13% open · ⏱️ 31.05.2022):

	```
	git clone https://github.com/datalad/datalad
	```
- [PyPi](https://pypi.org/project/datalad) (📥 7K / month · 📦 54 · ⏱️ 12.05.2022):
	```
	pip install datalad
	```
- [Conda](https://anaconda.org/conda-forge/datalad) (📥 210K · ⏱️ 12.05.2022):
	```
	conda install -c conda-forge datalad
	```
</details>
<details><summary><b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈31 ·  ⭐ 7.8K · 💤) - Open-source simulator for autonomous driving research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carla-simulator/carla) (👨‍💻 140 · 🔀 2.3K · 📦 180 · 📋 3.9K - 14% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/carla-simulator/carla
	```
- [PyPi](https://pypi.org/project/carla) (📥 19K / month · 📦 3 · ⏱️ 17.11.2021):
	```
	pip install carla
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥈31 ·  ⭐ 3.4K) - Online machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 80 · 🔀 380 · 📦 120 · 📋 380 - 3% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/online-ml/river
	```
- [PyPi](https://pypi.org/project/river) (📥 7.6K / month · 📦 12 · ⏱️ 28.05.2022):
	```
	pip install river
	```
- [Conda](https://anaconda.org/conda-forge/river) (📥 8.5K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge river
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥈31 ·  ⭐ 890) - OpenCL integration for Python, plus shiny features. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pyopencl) (👨‍💻 91 · 🔀 230 · 📦 740 · 📋 310 - 22% open · ⏱️ 21.05.2022):

	```
	git clone https://github.com/inducer/pyopencl
	```
- [PyPi](https://pypi.org/project/pyopencl) (📥 30K / month · 📦 190 · ⏱️ 19.05.2022):
	```
	pip install pyopencl
	```
- [Conda](https://anaconda.org/conda-forge/pyopencl) (📥 610K · ⏱️ 29.05.2022):
	```
	conda install -c conda-forge pyopencl
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈30 ·  ⭐ 2.2K) - A high performance implementation of HDBSCAN clustering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 78 · 🔀 400 · 📦 1.4K · 📋 430 - 62% open · ⏱️ 02.05.2022):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 400K / month · 📦 150 · ⏱️ 08.02.2022):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 1.1M · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈30 ·  ⭐ 1.7K) - Ahead of Time compiler for numeric kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 66 · 🔀 170 · 📦 150 · 📋 760 - 14% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 340K / month · 📦 14 · ⏱️ 14.12.2021):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 230K · ⏱️ 10.04.2022):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/PennyLaneAI/pennylane">PennyLane</a></b> (🥈30 ·  ⭐ 1.4K) - PennyLane is a cross-platform Python library for differentiable.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PennyLaneAI/pennylane) (👨‍💻 99 · 🔀 360 · 📥 60 · 📋 710 - 25% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/PennyLaneAI/PennyLane
	```
- [PyPi](https://pypi.org/project/pennylane) (📥 12K / month · 📦 32 · ⏱️ 09.05.2022):
	```
	pip install pennylane
	```
- [Conda](https://anaconda.org/conda-forge/pennylane) (📥 1.2K · ⏱️ 01.05.2022):
	```
	conda install -c conda-forge pennylane
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈30 ·  ⭐ 1.1K · 💤) - A Python data analysis library that is optimized for humans instead of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 49 · 🔀 140 · 📦 940 · 📋 680 - 7% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 3.9M / month · 📦 130 · ⏱️ 15.07.2021):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 83K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/nicodv/kmodes">kmodes</a></b> (🥈30 ·  ⭐ 1K) - Python implementations of the k-modes and k-prototypes clustering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nicodv/kmodes) (👨‍💻 21 · 🔀 370 · 📦 1.2K · 📋 150 - 10% open · ⏱️ 09.05.2022):

	```
	git clone https://github.com/nicodv/kmodes
	```
- [PyPi](https://pypi.org/project/kmodes) (📥 370K / month · 📦 26 · ⏱️ 14.04.2022):
	```
	pip install kmodes
	```
- [Conda](https://anaconda.org/conda-forge/kmodes) (📥 9.3K · ⏱️ 15.04.2022):
	```
	conda install -c conda-forge kmodes
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈30 ·  ⭐ 920) - Clean APIs for data cleaning. Python implementation of R package Janitor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 100 · 🔀 150 · 📦 180 · 📋 480 - 22% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/pyjanitor-devs/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 23K / month · 📦 11 · ⏱️ 03.05.2022):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 120K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/adapter-hub/adapter-transformers">adapter-transformers</a></b> (🥈30 ·  ⭐ 840) - Huggingface Transformers + Adapters =. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code></summary>

- [GitHub](https://github.com/adapter-hub/adapter-transformers) (👨‍💻 1.3K · 🔀 140 · 📦 76 · 📋 180 - 29% open · ⏱️ 01.06.2022):

	```
	git clone https://github.com/Adapter-Hub/adapter-transformers
	```
- [PyPi](https://pypi.org/project/adapter-transformers) (📥 40K / month · 📦 5 · ⏱️ 18.05.2022):
	```
	pip install adapter-transformers
	```
</details>
<details><summary><b><a href="https://github.com/uber/causalml">causalml</a></b> (🥈29 ·  ⭐ 3K) - Uplift modeling and causal inference with machine learning algorithms. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/causalml) (👨‍💻 41 · 🔀 480 · 📦 50 · 📋 260 - 17% open · ⏱️ 20.05.2022):

	```
	git clone https://github.com/uber/causalml
	```
- [PyPi](https://pypi.org/project/causalml) (📥 50K / month · 📦 1 · ⏱️ 14.03.2022):
	```
	pip install causalml
	```
</details>
<details><summary><b><a href="https://github.com/tensorly/tensorly">tensorly</a></b> (🥈29 ·  ⭐ 1.2K) - TensorLy: Tensor Learning in Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/tensorly/tensorly) (👨‍💻 52 · 🔀 240 · 📦 260 · 📋 190 - 26% open · ⏱️ 06.05.2022):

	```
	git clone https://github.com/tensorly/tensorly
	```
- [PyPi](https://pypi.org/project/tensorly) (📥 5.1K / month · 📦 30 · ⏱️ 08.11.2021):
	```
	pip install tensorly
	```
- [Conda](https://anaconda.org/conda-forge/tensorly) (📥 250K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge tensorly
	```
</details>
<details><summary><b><a href="https://github.com/mars-project/mars">Mars</a></b> (🥈28 ·  ⭐ 2.4K) - Mars is a tensor-based unified framework for large-scale data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mars-project/mars) (👨‍💻 45 · 🔀 300 · 📋 1.1K - 16% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/mars-project/mars
	```
- [PyPi](https://pypi.org/project/pymars) (📥 30K / month · 📦 1 · ⏱️ 10.05.2022):
	```
	pip install pymars
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi-detect">alibi-detect</a></b> (🥈28 ·  ⭐ 1.3K) - Algorithms for outlier, adversarial and drift detection. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi-detect) (👨‍💻 16 · 🔀 140 · 📦 91 · 📋 240 - 34% open · ⏱️ 30.05.2022):

	```
	git clone https://github.com/SeldonIO/alibi-detect
	```
- [PyPi](https://pypi.org/project/alibi-detect) (📥 22K / month · 📦 5 · ⏱️ 01.06.2022):
	```
	pip install alibi-detect
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥈28 ·  ⭐ 1.1K) - Genetic Programming in Python, with a scikit-learn inspired API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 11 · 🔀 200 · 📦 250 · 📋 190 - 17% open · ⏱️ 03.05.2022):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 5.9K / month · 📦 10 · ⏱️ 03.05.2022):
	```
	pip install gplearn
	```
- [Conda](https://anaconda.org/conda-forge/gplearn) (📥 2.3K · ⏱️ 04.05.2022):
	```
	conda install -c conda-forge gplearn
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥉27 ·  ⭐ 6.9K) - Trax Deep Learning with Clear Code and Speed. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 78 · 🔀 700 · 📦 54 · 📋 210 - 41% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 4.6K / month · ⏱️ 26.10.2021):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥉27 ·  ⭐ 1.3K) - Execute Python code on the fly and display results in Tableau visualizations:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 46 · 🔀 460 · 📦 91 · 📋 290 - 3% open · ⏱️ 31.03.2022):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 21K / month · 📦 2 · ⏱️ 20.01.2022):
	```
	pip install tabpy
	```
- [Conda](https://anaconda.org/anaconda/tabpy-client) (📥 2.9K · ⏱️ 02.05.2022):
	```
	conda install -c anaconda tabpy-client
	```
</details>
<details><summary><b><a href="https://github.com/sepandhaghighi/pycm">pycm</a></b> (🥉27 ·  ⭐ 1.2K) - Multi-class confusion matrix library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sepandhaghighi/pycm) (👨‍💻 17 · 🔀 110 · 📦 140 · 📋 180 - 6% open · ⏱️ 27.04.2022):

	```
	git clone https://github.com/sepandhaghighi/pycm
	```
- [PyPi](https://pypi.org/project/pycm) (📥 37K / month · 📦 13 · ⏱️ 27.04.2022):
	```
	pip install pycm
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/AugLy">AugLy</a></b> (🥉26 ·  ⭐ 4.5K) - A data augmentations library for audio, image, text, and video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/AugLy) (👨‍💻 23 · 🔀 240 · 📦 38 · 📋 66 - 19% open · ⏱️ 15.05.2022):

	```
	git clone https://github.com/facebookresearch/AugLy
	```
- [PyPi](https://pypi.org/project/augly) (📥 1.3K / month · 📦 3 · ⏱️ 28.03.2022):
	```
	pip install augly
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥉26 ·  ⭐ 1.2K) - Metric learning algorithms in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 22 · 🔀 220 · 📦 210 · 📋 170 - 30% open · ⏱️ 11.03.2022):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 13K / month · 📦 11 · ⏱️ 02.07.2020):
	```
	pip install metric-learn
	```
- [Conda](https://anaconda.org/conda-forge/metric-learn) (📥 5.8K · ⏱️ 02.07.2020):
	```
	conda install -c conda-forge metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/ContinualAI/avalanche">avalanche</a></b> (🥉25 ·  ⭐ 940) - Avalanche: an End-to-End Library for Continual Learning based on PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContinualAI/avalanche) (👨‍💻 57 · 🔀 150 · 📦 9 · 📋 510 - 13% open · ⏱️ 02.06.2022):

	```
	git clone https://github.com/ContinualAI/avalanche
	```
- [PyPi](https://pypi.org/project/avalanche-lib) (📥 700 / month · ⏱️ 16.12.2021):
	```
	pip install avalanche-lib
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉25 ·  ⭐ 930 · 💤) - A research toolkit for particle swarm optimization in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 43 · 🔀 300 · 📦 170 · 📋 210 - 7% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 13K / month · 📦 6 · ⏱️ 03.01.2021):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉25 ·  ⭐ 800) - Python factor analysis library (PCA, CA, MCA, MFA, FAMD). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 12 · 🔀 140 · 📦 210 · 📋 110 - 35% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 80K / month · 📦 5 · ⏱️ 06.10.2020):
	```
	pip install prince
	```
- [Conda](https://anaconda.org/conda-forge/prince-factor-analysis) (📥 9.9K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge prince-factor-analysis
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉24 ·  ⭐ 830) - Machine learning, statistics, and data mining for astronomy and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 280 · 📋 150 - 40% open · ⏱️ 17.05.2022):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 1.5K / month · 📦 33 · ⏱️ 01.03.2022):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 29K · ⏱️ 02.03.2022):
	```
	conda install -c conda-forge astroml
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉24 ·  ⭐ 470) - Working with molecular structures in pandas DataFrames. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/biopandas) (👨‍💻 10 · 🔀 98 · 📦 100 · 📋 43 - 39% open · ⏱️ 13.05.2022):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 4.2K / month · 📦 14 · ⏱️ 13.05.2022):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 110K · ⏱️ 13.05.2022):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉24 ·  ⭐ 440) - Find pyspark to make it importable. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minrk/findspark) (👨‍💻 15 · 🔀 67 · 📦 2.5K · 📋 23 - 52% open · ⏱️ 11.02.2022):

	```
	git clone https://github.com/minrk/findspark
	```
- [PyPi](https://pypi.org/project/findspark) (📥 2.3M / month · 📦 140 · ⏱️ 11.02.2022):
	```
	pip install findspark
	```
- [Conda](https://anaconda.org/conda-forge/findspark) (📥 650K · ⏱️ 11.02.2022):
	```
	conda install -c conda-forge findspark
	```
</details>
<details><summary><b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉23 ·  ⭐ 860 · 💤) - Feature engineering package with sklearn like functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/solegalli/feature_engine) (👨‍💻 24 · 🔀 200 · ⏱️ 06.08.2021):

	```
	git clone https://github.com/solegalli/feature_engine
	```
- [PyPi](https://pypi.org/project/feature_engine) (📥 82K / month · 📦 66 · ⏱️ 05.05.2022):
	```
	pip install feature_engine
	```
- [Conda](https://anaconda.org/conda-forge/feature_engine) (📥 9.3K · ⏱️ 05.05.2022):
	```
	conda install -c conda-forge feature_engine
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉21 ·  ⭐ 2.7K · 💤) - StreamAlert is a serverless, realtime data analysis.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/streamalert) (👨‍💻 33 · 🔀 320 · 📋 340 - 24% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/airbnb/streamalert
	```
</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉20 ·  ⭐ 320 · 💤) - Data imputations library to preprocess datasets with missing data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eltonlaw/impyute) (👨‍💻 11 · 🔀 44 · 📦 140 · 📋 64 - 42% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/eltonlaw/impyute
	```
- [PyPi](https://pypi.org/project/impyute) (📥 4K / month · 📦 3 · ⏱️ 29.04.2019):
	```
	pip install impyute
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉19 ·  ⭐ 320) - (MLSys 21) An Acceleration System for Large-scare Unsupervised Heterogeneous.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (👨‍💻 1 · 🔀 41 · 📦 420 · 📋 9 - 66% open · ⏱️ 11.04.2022):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 26K / month · ⏱️ 01.10.2021):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/pykale/pykale">pykale</a></b> (🥉18 ·  ⭐ 340) - Knowledge-Aware machine LEarning (KALE): accessible machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pykale/pykale) (👨‍💻 16 · 🔀 45 · 📋 98 - 14% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/pykale/pykale
	```
- [PyPi](https://pypi.org/project/pykale) (📥 61 / month · ⏱️ 12.04.2022):
	```
	pip install pykale
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/apricot">apricot</a></b> (🥉17 ·  ⭐ 420 · 💤) - apricot implements submodular optimization for the purpose of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/apricot) (👨‍💻 4 · 🔀 40 · 📥 10 · 📦 26 · 📋 25 - 28% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/jmschrei/apricot
	```
- [PyPi](https://pypi.org/project/apricot-select) (📥 350 / month · 📦 3 · ⏱️ 28.09.2020):
	```
	pip install apricot-select
	```
</details>
<details><summary><b><a href="https://github.com/SforAiDl/KD_Lib">KD-Lib</a></b> (🥉17 ·  ⭐ 390) - A Pytorch Knowledge Distillation library for benchmarking and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/SforAiDl/KD_Lib) (👨‍💻 6 · 🔀 34 · 📋 59 - 22% open · ⏱️ 18.05.2022):

	```
	git clone https://github.com/SforAiDl/KD_Lib
	```
- [PyPi](https://pypi.org/project/KD-Lib) (📥 140 / month · ⏱️ 18.05.2022):
	```
	pip install KD-Lib
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈30 ·  ⭐ 190) - Fast matrix-multiplication as a self-contained Python library no.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/deepmind/pysc2">pysc2</a></b> (🥈28 ·  ⭐ 7.5K · 💀) - StarCraft II Learning Environment. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/JustGlowing/minisom">minisom</a></b> (🥉27 ·  ⭐ 1.1K) - MiniSom is a minimalistic implementation of the Self Organizing.. <code><a href="https://tldrlegal.com/search?q=CC-BY-3.0">❗️CC-BY-3.0</a></code>
- <b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥉27 ·  ⭐ 960 · 💀) - pyclustring is a Python, C++ data mining library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/cleanlab/cleanlab">cleanlab</a></b> (🥉26 ·  ⭐ 3.5K) - The standard data-centric AI package for data quality and machine.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/modAL-python/modAL">modAL</a></b> (🥉24 ·  ⭐ 1.7K · 💀) - A modular active learning framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Project-MONAI/MONAILabel">MONAILabel</a></b> (🥉23 ·  ⭐ 240) - MONAI Label is an intelligent open source image labeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vecxoz/vecstack">vecstack</a></b> (🥉22 ·  ⭐ 660 · 💀) - Python package for stacking (machine learning technique). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/flennerhag/mlens">mlens</a></b> (🥉21 ·  ⭐ 740 · 💀) - ML-Ensemble high performance ensemble learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ml-tooling/opyrator">opyrator</a></b> (🥉20 ·  ⭐ 2.6K · 💀) - Turns your machine learning code into microservices with web API,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kLabUM/rrcf">rrcf</a></b> (🥉19 ·  ⭐ 380 · 💀) - Implementation of the Robust Random Cut Forest algorithm for anomaly.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/EpistasisLab/scikit-rebate">scikit-rebate</a></b> (🥉19 ·  ⭐ 360 · 💀) - A scikit-learn-compatible Python implementation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/alegonz/baikal">baikal</a></b> (🥉18 ·  ⭐ 590 · 💀) - A graph-based functional API for building complex scikit-learn.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pandas-ml/pandas-ml">pandas-ml</a></b> (🥉18 ·  ⭐ 290 · 💀) - pandas, scikit-learn, xgboost and seaborn integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/NeuralCompression">NeuralCompression</a></b> (🥉14 ·  ⭐ 250) - A collection of tools for neural compression enthusiasts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dstackai/dstack">dstack</a></b> (🥉14 ·  ⭐ 45 · 🐣) - dstack: continuous training in the cloud. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jrieke/traingenerator">traingenerator</a></b> (🥉13 ·  ⭐ 1.2K · 💀) - A web app to generate template code for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Palashio/nylon">nylon</a></b> (🥉12 ·  ⭐ 77 · 💤) - An intelligent, flexible grammar of machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>

---

## Related Resources

- [**Papers With Code**](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.
- [**Sotabench**](https://sotabench.com): Discover & compare open-source ML models.
- [**Google Dataset Search**](https://toolbox.google.com/datasetsearch): Dataset search engine by Google.
- [**Dataset List**](https://www.datasetlist.com/): List of the biggest ML datasets from across the web.
- [**Awesome Public Datasets**](https://github.com/awesomedata/awesome-public-datasets): A topic-centric list of open datasets.
- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-python-dev**](https://github.com/ml-tooling/best-of-python-dev): A ranked list of awesome python developer tools and libraries.
- [**best-of-web-python**](https://github.com/ml-tooling/best-of-web-python): A ranked list of awesome python libraries for web development.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-ml-python/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-ml-python/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
