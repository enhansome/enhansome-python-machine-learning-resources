# Awesome python machine learning resources with stars

<!-- markdownlint-disable -->

<h1 align="center">
    python机器学习资源与工具库大全
    <br>
</h1>

<p align="center">
    <strong>python机器学习开源工具库资源大全，划分子版块并梳理排行，每周自动更新</strong>
</p>

<p align="center">
    <a href="#Contents" title="项目数量"><img src="https://img.shields.io/badge/projects-820-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="欢迎完善"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/HanXinzi-AI/awesome-python-machine-learning-resources/releases" title="最近更新"><img src="https://img.shields.io/github/release-date/HanXinzi-AI/awesome-python-machine-learning-resources?color=green&label=updated"></a>
</p>

本资源清单包含820个python机器学习相关的开源工具资源，这些热门工具总共分成32个不同的子板块，这些项目目前在github上已经收到3.5M个点赞。所有的工具资源每周会自动从GitHub和工具维护平台采集信息，并更新排行展示。本清单参考[best-of模板](https://github.com/best-of-lists/best-of) ⭐ 1,890 | 🐛 21 | 📅 2026-08-20完成，内容参考了[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,132 | 🐛 26 | 🌐 Python | 📅 2026-08-21，欢迎大家提PR丰富本清单。

## 目录

* [机器学习框架](#机器学习框架) *54 个项目*
* [数据可视化](#数据可视化) *49 个项目*
* [文本数据和NLP](#文本数据和NLP) *82 个项目*
* [图像数据与CV](#图像数据与CV) *49 个项目*
* [图数据处理](#图数据处理) *29 个项目*
* [音频处理](#音频处理) *23 个项目*
* [地理Geo处理](#地理Geo处理) *22 个项目*
* [金融数据处理](#金融数据处理) *23 个项目*
* [时间序列](#时间序列) *20 个项目*
* [医疗领域](#医疗领域) *19 个项目*
* [光学字符识别OCR](#光学字符识别OCR) *11 个项目*
* [数据容器和结构](#数据容器和结构) *28 个项目*
* [数据读写与提取](#数据读写与提取) *23 个项目*
* [网页抓取和爬虫](#网页抓取和爬虫) *1 个项目*
* [数据管道和流处理](#数据管道和流处理) *36 个项目*
* [分布式机器学习](#分布式机器学习) *26 个项目*
* [超参数优化和AutoML](#超参数优化和AutoML) *45 个项目*
* [强化学习](#强化学习) *19 个项目*
* [推荐系统](#推荐系统) *13 个项目*
* [隐私机器学习](#隐私机器学习) *6 个项目*
* [工作流程和实验跟踪](#工作流程和实验跟踪) *35 个项目*
* [模型序列化和转换](#模型序列化和转换) *11 个项目*
* [模型的可解释性](#模型的可解释性) *46 个项目*
* [向量相似度搜索（ANN）](#向量相似度搜索（ANN）) *12 个项目*
* [概率统计](#概率统计) *21 个项目*
* [对抗学习与鲁棒性](#对抗学习与鲁棒性) *7 个项目*
* [GPU实用程序](#GPU实用程序) *18 个项目*
* [Tensorflow实用程序](#Tensorflow实用程序) *13 个项目*
* [Sklearn实用程序](#Sklearn实用程序) *17 个项目*
* [Pytorch实用程序](#Pytorch实用程序) *27 个项目*
* [数据库客户端](#数据库客户端) *1 个项目*
* [中文自然语言处理](#中文自然语言处理) *2 个项目*
* [Others](#Others) *33 个项目*

## 图标解释

* 🥇🥈🥉  综合项目质量分
* ⭐️  github上star的数量
* 🐣  小于6个月的新项目
* 💤  非活跃项目(6个月未更新)
* 💀  沉寂项目(12个月未更新)
* 📈📉  项目趋势(向上or向下)
* ➕  最近添加的项目
* ❗️  警告(例如 项目没有license)
* 👨‍💻  项目的开发贡献者数量
* 🔀  项目被fork的数量
* 📋  项目issue的数量
* ⏱️  项目包上次更新时间
* 📥  工具库被下载次数
* 📦  项目依赖的工具库数量
* <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">  Tensorflow相关项目
* <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">  Sklearn相关项目
* <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">  pytorch相关项目
* <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">  MxNet相关项目
* <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">  Apache Spark相关项目
* <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">  Jupyter相关项目
* <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">  PaddlePaddle相关项目
* <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">  Pandas相关项目

<br>

## 机器学习框架

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*通用机器学习和深度学习框架。*

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇44 ·  ⭐ 170K) - 适用于所有人的开源机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/tensorflow) ⭐ 197,374 | 🐛 2,946 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 4.1K · 🔀 70K · 📦 210K · 📋 35K - 5% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/tensorflow/tensorflow
  ```
* [PyPi](https://pypi.org/project/tensorflow) (📥 14M / month):
  ```
  pip install tensorflow
  ```
* [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 3.6M · ⏱️ 20.07.2022):
  ```
  conda install -c conda-forge tensorflow
  ```
* [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 67M · ⭐ 2K · ⏱️ 25.08.2022):
  ```
  docker pull tensorflow/tensorflow
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇39 ·  ⭐ 51K) - scikit-learn：基于Python的机器学习工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn/scikit-learn) ⭐ 67,034 | 🐛 2,126 | 🌐 Python | 📅 2026-08-21 (👨‍💻 2.7K · 🔀 23K · 📥 810 · 📦 390K · 📋 9.6K - 16% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/scikit-learn/scikit-learn
  ```
* [PyPi](https://pypi.org/project/scikit-learn) (📥 31M / month):
  ```
  pip install scikit-learn
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 15M · ⏱️ 05.08.2022):
  ```
  conda install -c conda-forge scikit-learn
  ```

</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇37 ·  ⭐ 23K) - 可扩展，高效和分布式梯度增强（GBDT，GBRT等）的boosting工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/dmlc/xgboost) ⭐ 28,689 | 🐛 422 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 570 · 🔀 7.9K · 📥 5K · 📦 35K · 📋 4.5K - 5% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/dmlc/xgboost
  ```
* [PyPi](https://pypi.org/project/xgboost) (📥 8.3M / month):
  ```
  pip install xgboost
  ```
* [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2.9M · ⏱️ 12.08.2022):
  ```
  conda install -c conda-forge xgboost
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥇35 ·  ⭐ 14K) - 快速，分布式，高性能梯度提升（GBT，GBDT，GBRT等）的boosting工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/LightGBM) ⭐ 18,708 | 🐛 511 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 270 · 🔀 3.5K · 📥 160K · 📦 15K · 📋 2.8K - 7% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/microsoft/LightGBM
  ```
* [PyPi](https://pypi.org/project/lightgbm) (📥 6M / month):
  ```
  pip install lightgbm
  ```
* [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 1.2M · ⏱️ 08.01.2022):
  ```
  conda install -c conda-forge lightgbm
  ```

</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥇34 ·  ⭐ 23K) - Fastai深度学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/fastai/fastai) ⭐ 28,120 | 🐛 267 | 🌐 Jupyter Notebook | 📅 2026-08-15 (👨‍💻 210 · 🔀 7.1K · 📦 11K · 📋 1.7K - 6% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/fastai/fastai
  ```
* [PyPi](https://pypi.org/project/fastai) (📥 280K / month):
  ```
  pip install fastai
  ```

</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥇34 ·  ⭐ 2.6K) - 深度学习工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/explosion/thinc) ⭐ 2,890 | 🐛 16 | 🌐 Python | 📅 2026-03-27 (👨‍💻 53 · 🔀 240 · 📦 23K · 📋 120 - 11% open · ⏱️ 05.08.2022):

  ```
  git clone https://github.com/explosion/thinc
  ```
* [PyPi](https://pypi.org/project/thinc) (📥 4.1M / month):
  ```
  pip install thinc
  ```
* [Conda](https://anaconda.org/conda-forge/thinc) (📥 2.2M · ⏱️ 08.07.2022):
  ```
  conda install -c conda-forge thinc
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥈33 ·  ⭐ 58K) - 具有强大GPU的Python中的张量和动态神经网络构建工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/pytorch) ⭐ 102,559 | 🐛 17,302 | 🌐 Python | 📅 2026-08-23 (👨‍💻 3.5K · 🔀 16K · 📥 5.6K · 📋 28K - 32% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/pytorch/pytorch
  ```
* [PyPi](https://pypi.org/project/torch) (📥 8.5M / month):
  ```
  pip install torch
  ```
* [Conda](https://anaconda.org/pytorch/pytorch) (📥 19M · ⏱️ 04.08.2022):
  ```
  conda install -c pytorch pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈33 ·  ⭐ 11K) - 进行现实世界机器学习和数据分析的工具包。<code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code></summary>

* [GitHub](https://github.com/davisking/dlib) ⭐ 14,433 | 🐛 38 | 🌐 C++ | 📅 2026-08-11 (👨‍💻 180 · 🔀 2.7K · 📥 25K · 📦 16K · 📋 2.1K - 1% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/davisking/dlib
  ```
* [PyPi](https://pypi.org/project/dlib) (📥 91K / month):
  ```
  pip install dlib
  ```
* [Conda](https://anaconda.org/conda-forge/dlib) (📥 460K · ⏱️ 08.05.2022):
  ```
  conda install -c conda-forge dlib
  ```

</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥈32 ·  ⭐ 56K) - 易上手的深度学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/keras-team/keras) ⭐ 64,247 | 🐛 236 | 🌐 Python | 📅 2026-08-21 (👨‍💻 1.1K · 🔀 18K · 📋 11K - 2% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/keras-team/keras
  ```
* [PyPi](https://pypi.org/project/keras) (📥 8.4M / month):
  ```
  pip install keras
  ```
* [Conda](https://anaconda.org/conda-forge/keras) (📥 2.5M · ⏱️ 19.05.2022):
  ```
  conda install -c conda-forge keras
  ```

</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈32 ·  ⭐ 34K) - Apache Spark Python API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/apache/spark) ⭐ 43,865 | 🐛 478 | 🌐 Scala | 📅 2026-08-23 (👨‍💻 2.7K · 🔀 25K · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/apache/spark
  ```
* [PyPi](https://pypi.org/project/pyspark) (📥 25M / month):
  ```
  pip install pyspark
  ```
* [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1.9M · ⏱️ 27.07.2022):
  ```
  conda install -c conda-forge pyspark
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈32 ·  ⭐ 19K) - paddlepaddle机器学习与深度学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/Paddle) ⭐ 24,062 | 🐛 1,505 | 🌐 C++ | 📅 2026-08-20 (👨‍💻 810 · 🔀 4.5K · 📥 15K · 📦 140 · 📋 15K - 14% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/Paddle
  ```
* [PyPi](https://pypi.org/project/paddlepaddle) (📥 79K / month):
  ```
  pip install paddlepaddle
  ```

</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈32 ·  ⭐ 16K) - 在云端构建神经搜索的简便方法库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/jina-ai/jina) ⭐ 21,863 | 🐛 26 | 🌐 Python | 📅 2025-03-24 (👨‍💻 150 · 🔀 1.9K · 📦 350 · 📋 1.6K - 1% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jina-ai/jina
  ```
* [PyPi](https://pypi.org/project/jina) (📥 88K / month):
  ```
  pip install jina
  ```
* [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 1.1M · ⭐ 7 · ⏱️ 23.08.2022):
  ```
  docker pull jinaai/jina
  ```

</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥈32 ·  ⭐ 7.7K) - Statsmodels：Python中的统计建模和计量经济学工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/statsmodels/statsmodels) ⭐ 11,589 | 🐛 2,830 | 🌐 Python | 📅 2026-08-23 (👨‍💻 380 · 🔀 2.4K · 📥 26 · 📦 68K · 📋 4.8K - 46% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/statsmodels/statsmodels
  ```
* [PyPi](https://pypi.org/project/statsmodels) (📥 8.8M / month):
  ```
  pip install statsmodels
  ```
* [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 7M · ⏱️ 09.06.2022):
  ```
  conda install -c conda-forge statsmodels
  ```

</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥈31 ·  ⭐ 20K) - Python + NumPy程序工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/google/jax) ⭐ 36,207 | 🐛 2,471 | 🌐 Python | 📅 2026-08-23 (👨‍💻 440 · 🔀 1.8K · 📦 5.3K · 📋 3.4K - 24% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/google/jax
  ```
* [PyPi](https://pypi.org/project/jax) (📥 610K / month):
  ```
  pip install jax
  ```
* [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 410K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge jaxlib
  ```

</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈31 ·  ⭐ 5.7K) - 灵活的深度学习神经网络框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/chainer/chainer) ⭐ 5,924 | 🐛 15 | 🌐 Python | 📅 2023-08-28 (👨‍💻 320 · 🔀 1.3K · 📦 2.7K · 📋 2K - 0% open · ⏱️ 29.06.2022):

  ```
  git clone https://github.com/chainer/chainer
  ```
* [PyPi](https://pypi.org/project/chainer) (📥 23K / month):
  ```
  pip install chainer
  ```

</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈30 ·  ⭐ 9.6K · 💤) - Theano是一个Python神经网络工具库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Theano/Theano) ⭐ 9,998 | 🐛 699 | 🌐 Python | 📅 2024-01-15 (👨‍💻 380 · 🔀 2.4K · 📦 13K · 📋 2.7K - 21% open · ⏱️ 23.11.2021):

  ```
  git clone https://github.com/Theano/Theano
  ```
* [PyPi](https://pypi.org/project/theano) (📥 270K / month):
  ```
  pip install theano
  ```
* [Conda](https://anaconda.org/conda-forge/theano) (📥 2.1M · ⏱️ 16.03.2022):
  ```
  conda install -c conda-forge theano
  ```

</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥈30 ·  ⭐ 5.5K) - 重塑了深度学习操作（用于pytorch，tensorflow，jax等）的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/arogozhnikov/einops) ⭐ 9,576 | 🐛 39 | 🌐 Python | 📅 2026-07-05 (👨‍💻 20 · 🔀 240 · 📦 3.9K · 📋 120 - 28% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/arogozhnikov/einops
  ```
* [PyPi](https://pypi.org/project/einops) (📥 1M / month):
  ```
  pip install einops
  ```
* [Conda](https://anaconda.org/conda-forge/einops) (📥 25K · ⏱️ 04.03.2022):
  ```
  conda install -c conda-forge einops
  ```

</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈29 ·  ⭐ 20K) - 轻巧，灵活的分布式/移动深度学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/apache/incubator-mxnet) ⚠️ Archived (👨‍💻 980 · 🔀 6.5K · 📥 25K · 📋 9.5K - 18% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/apache/incubator-mxnet
  ```
* [PyPi](https://pypi.org/project/mxnet) (📥 410K / month):
  ```
  pip install mxnet
  ```
* [Conda](https://anaconda.org/anaconda/mxnet) (📥 8K · ⏱️ 02.05.2022):
  ```
  conda install -c anaconda mxnet
  ```

</details>
<details><summary><b><a href="https://github.com/Lightning-AI/lightning">pytorch-lightning</a></b> (🥈29 ·  ⭐ 20K · 📉) - 轻巧而具备高性能的PyTorch上层封装工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Lightning-AI/lightning) ⭐ 31,300 | 🐛 1,084 | 🌐 Python | 📅 2026-08-09 (👨‍💻 740 · 🔀 2.5K · 📥 8K · 📋 5.3K - 8% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/PyTorchLightning/pytorch-lightning
  ```
* [PyPi](https://pypi.org/project/pytorch-lightning) (📥 1.8M / month):
  ```
  pip install pytorch-lightning
  ```
* [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 520K · ⏱️ 18.08.2022):
  ```
  conda install -c conda-forge pytorch-lightning
  ```

</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈28 ·  ⭐ 8K) - Vowpal Wabbit是一个推动机器学习的机器学习系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) ⭐ 8,706 | 🐛 1 | 🌐 C++ | 📅 2026-08-18 (👨‍💻 320 · 🔀 1.7K · 📋 1.2K - 10% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/VowpalWabbit/vowpal_wabbit
  ```
* [PyPi](https://pypi.org/project/vowpalwabbit) (📥 92K / month):
  ```
  pip install vowpalwabbit
  ```

</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈28 ·  ⭐ 6.7K) - 快速，可扩展，高性能的梯度决策提升工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/catboost/catboost) ⭐ 9,075 | 🐛 714 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 1K · 🔀 990 · 📥 86K · 📋 1.9K - 21% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/catboost/catboost
  ```
* [PyPi](https://pypi.org/project/catboost) (📥 2.7M / month):
  ```
  pip install catboost
  ```
* [Conda](https://anaconda.org/conda-forge/catboost) (📥 1.1M · ⏱️ 19.05.2022):
  ```
  conda install -c conda-forge catboost
  ```

</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈28 ·  ⭐ 3.5K) - Flax是专为.NET设计的用于JAX的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

* [GitHub](https://github.com/google/flax) ⭐ 7,300 | 🐛 510 | 🌐 Jupyter Notebook | 📅 2026-08-21 (👨‍💻 170 · 🔀 380 · 📥 42 · 📦 1.3K · 📋 550 - 17% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/google/flax
  ```
* [PyPi](https://pypi.org/project/flax) (📥 310K / month):
  ```
  pip install flax
  ```

</details>
<details><summary><b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥈28 ·  ⭐ 3.3K) - DyNet：动态神经网络工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/clab/dynet) ⭐ 3,436 | 🐛 233 | 🌐 C++ | 📅 2023-12-01 (👨‍💻 160 · 🔀 670 · 📥 6.9K · 📦 220 · 📋 920 - 27% open · ⏱️ 14.08.2022):

  ```
  git clone https://github.com/clab/dynet
  ```
* [PyPi](https://pypi.org/project/dyNET) (📥 20K / month):
  ```
  pip install dyNET
  ```

</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥉27 ·  ⭐ 20K) - Apache Flink Python API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/flink) ⭐ 26,282 | 🐛 374 | 🌐 Java | 📅 2026-08-23 (👨‍💻 1.6K · 🔀 11K · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/apache/flink
  ```
* [PyPi](https://pypi.org/project/apache-flink) (📥 54K / month):
  ```
  pip install apache-flink
  ```

</details>
<details><summary><b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉27 ·  ⭐ 9.6K · 💀) - 深度学习库，基于TensorFlow构建上层简单易用的API。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tflearn/tflearn) ⭐ 9,575 | 🐛 579 | 🌐 Python | 📅 2024-05-06 (👨‍💻 130 · 🔀 2.3K · 📦 4.1K · 📋 910 - 60% open · ⏱️ 30.11.2020):

  ```
  git clone https://github.com/tflearn/tflearn
  ```
* [PyPi](https://pypi.org/project/tflearn) (📥 16K / month):
  ```
  pip install tflearn
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥉27 ·  ⭐ 9.4K) - 基于TensorFlow的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepmind/sonnet) ⭐ 9,961 | 🐛 43 | 🌐 Python | 📅 2026-07-07 (👨‍💻 54 · 🔀 1.2K · 📦 900 · 📋 180 - 14% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/deepmind/sonnet
  ```
* [PyPi](https://pypi.org/project/dm-sonnet) (📥 24K / month):
  ```
  pip install dm-sonnet
  ```
* [Conda](https://anaconda.org/conda-forge/sonnet) (📥 16K · ⏱️ 14.11.2020):
  ```
  conda install -c conda-forge sonnet
  ```

</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥉27 ·  ⭐ 8.5K) - 路德维希（Ludwig）是一个工具箱，可用于深度学习训练和评估。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ludwig-ai/ludwig) ⭐ 11,746 | 🐛 1 | 🌐 Python | 📅 2026-08-17 (👨‍💻 130 · 🔀 960 · 📦 130 · 📋 820 - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/ludwig-ai/ludwig
  ```
* [PyPi](https://pypi.org/project/ludwig) (📥 1.8K / month):
  ```
  pip install ludwig
  ```

</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉27 ·  ⭐ 6.2K) - TensorFlow上的神经网络训练接口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorpack/tensorpack) ⭐ 6,285 | 🐛 14 | 🌐 Python | 📅 2023-08-06 (👨‍💻 58 · 🔀 1.8K · 📥 140 · 📦 1.1K · 📋 1.3K - 0% open · ⏱️ 04.05.2022):

  ```
  git clone https://github.com/tensorpack/tensorpack
  ```
* [PyPi](https://pypi.org/project/tensorpack) (📥 19K / month):
  ```
  pip install tensorpack
  ```

</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉26 ·  ⭐ 4.6K) - 封装成scikit-learn接口模式的神经网络库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/skorch-dev/skorch) ⭐ 6,172 | 🐛 65 | 🌐 Jupyter Notebook | 📅 2026-08-10 (👨‍💻 50 · 🔀 310 · 📦 550 · 📋 440 - 9% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/skorch-dev/skorch
  ```
* [PyPi](https://pypi.org/project/skorch) (📥 31K / month):
  ```
  pip install skorch
  ```
* [Conda](https://anaconda.org/conda-forge/skorch) (📥 610K · ⏱️ 30.11.2021):
  ```
  conda install -c conda-forge skorch
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥉26 ·  ⭐ 4K) - 用于训练和评估神经等一系列操作的高级深度学习工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/ignite) ⭐ 4,777 | 🐛 190 | 🌐 Python | 📅 2026-08-17 (👨‍💻 180 · 🔀 540 · 📋 1.1K - 10% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytorch/ignite
  ```
* [PyPi](https://pypi.org/project/pytorch-ignite) (📥 150K / month):
  ```
  pip install pytorch-ignite
  ```
* [Conda](https://anaconda.org/pytorch/ignite) (📥 99K · ⏱️ 04.05.2022):
  ```
  conda install -c pytorch ignite
  ```

</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉26 ·  ⭐ 1K) - ktrain是一个Python库，可以使深度学习和AI更简单。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/amaiya/ktrain) ⭐ 1,268 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-02-06 (👨‍💻 15 · 🔀 240 · 📦 330 · 📋 420 - 0% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/amaiya/ktrain
  ```
* [PyPi](https://pypi.org/project/ktrain) (📥 20K / month):
  ```
  pip install ktrain
  ```

</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥉25 ·  ⭐ 11K · 💤) - Turi Create简化了自定义机器学习的开发。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/apple/turicreate) ⚠️ Archived (👨‍💻 85 · 🔀 1.1K · 📥 6.8K · 📦 320 · 📋 1.8K - 27% open · ⏱️ 29.11.2021):

  ```
  git clone https://github.com/apple/turicreate
  ```
* [PyPi](https://pypi.org/project/turicreate) (📥 20K / month):
  ```
  pip install turicreate
  ```

</details>
<details><summary><b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉25 ·  ⭐ 3K) - 高性能，易于使用且可扩展的机器学习（ML）工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/aksnzhy/xlearn) ⭐ 3,091 | 🐛 194 | 🌐 C++ | 📅 2023-08-28 (👨‍💻 30 · 🔀 510 · 📥 3.4K · 📦 93 · 📋 300 - 61% open · ⏱️ 05.06.2022):

  ```
  git clone https://github.com/aksnzhy/xlearn
  ```
* [PyPi](https://pypi.org/project/xlearn) (📥 5.2K / month):
  ```
  pip install xlearn
  ```

</details>
<details><summary><b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉24 ·  ⭐ 6.3K · 💀) - Numenta智能计算平台。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/numenta/nupic) ⭐ 6,351 | 🐛 465 | 🌐 Python | 📅 2024-12-03 (👨‍💻 120 · 🔀 1.6K · 📦 110 · 📋 1.8K - 25% open · ⏱️ 23.10.2019):

  ```
  git clone https://github.com/numenta/nupic
  ```
* [PyPi](https://pypi.org/project/nupic) (📥 1.4K / month):
  ```
  pip install nupic
  ```

</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉24 ·  ⭐ 1.4K) - fklearn：机器学习工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nubank/fklearn) ⭐ 1,547 | 🐛 43 | 🌐 Jupyter Notebook | 📅 2026-06-10 (👨‍💻 47 · 🔀 160 · 📦 13 · 📋 48 - 54% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/nubank/fklearn
  ```
* [PyPi](https://pypi.org/project/fklearn) (📥 12K / month):
  ```
  pip install fklearn
  ```

</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥉24 ·  ⭐ 610) - TensorFlow ROCm端口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) ⭐ 704 | 🐛 95 | 🌐 C++ | 📅 2026-08-21 (👨‍💻 4.1K · 🔀 71 · 📥 20 · 📋 330 - 16% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
  ```
* [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 1.7K / month):
  ```
  pip install tensorflow-rocm
  ```

</details>
<details><summary><b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉23 ·  ⭐ 4.1K) - mlpack：可扩展的C++机器学习库-。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/mlpack/mlpack) ⭐ 5,701 | 🐛 13 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 290 · 🔀 1.4K · 📋 1.4K - 2% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/mlpack/mlpack
  ```
* [PyPi](https://pypi.org/project/mlpack) (📥 630 / month):
  ```
  pip install mlpack
  ```
* [Conda](https://anaconda.org/conda-forge/mlpack) (📥 110K · ⏱️ 09.11.2021):
  ```
  conda install -c conda-forge mlpack
  ```

</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉23 ·  ⭐ 2.6K) - 神经网络工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/sony/nnabla) ⚠️ Archived (👨‍💻 67 · 🔀 310 · 📥 540 · 📋 72 - 31% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/sony/nnabla
  ```
* [PyPi](https://pypi.org/project/nnabla) (📥 2.8K / month):
  ```
  pip install nnabla
  ```

</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉23 ·  ⭐ 1.8K) - Python中的快速简便的无限神经网络。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/google/neural-tangents) ⚠️ Archived (👨‍💻 23 · 🔀 200 · 📥 240 · 📦 47 · 📋 120 - 34% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/google/neural-tangents
  ```
* [PyPi](https://pypi.org/project/neural-tangents) (📥 1.5K / month):
  ```
  pip install neural-tangents
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉22 ·  ⭐ 17K · 💀) - Microsoft认知工具包（CNTK），一种开源的深度学习工具包。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/microsoft/CNTK) ⚠️ Archived (👨‍💻 270 · 🔀 4.3K · 📥 14K · 📋 3.3K - 22% open · ⏱️ 31.03.2020):

  ```
  git clone https://github.com/microsoft/CNTK
  ```
* [PyPi](https://pypi.org/project/cntk) (📥 730 / month):
  ```
  pip install cntk
  ```

</details>
<details><summary><b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉22 ·  ⭐ 3.8K · 💀) - 轻量级的库，用于在Theano中构建和训练神经网络。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Lasagne/Lasagne) ⭐ 3,857 | 🐛 139 | 🌐 Python | 📅 2022-03-26 (👨‍💻 72 · 🔀 930 · 📦 920 · 📋 520 - 22% open · ⏱️ 20.11.2019):

  ```
  git clone https://github.com/Lasagne/Lasagne
  ```
* [PyPi](https://pypi.org/project/lasagne) (📥 1.4K / month):
  ```
  pip install lasagne
  ```

</details>
<details><summary><b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉22 ·  ⭐ 2.9K · 💀) - 统一高效的机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/shogun-toolbox/shogun) ⭐ 3,080 | 🐛 426 | 🌐 C++ | 📅 2023-12-19 (👨‍💻 250 · 🔀 1K · 📋 1.5K - 27% open · ⏱️ 08.12.2020):

  ```
  git clone https://github.com/shogun-toolbox/shogun
  ```
* [Conda](https://anaconda.org/conda-forge/shogun) (📥 120K · ⏱️ 25.06.2018):
  ```
  conda install -c conda-forge shogun
  ```
* [Docker Hub](https://hub.docker.com/r/shogun/shogun) (📥 1.5K · ⭐ 1 · ⏱️ 31.01.2019):
  ```
  docker pull shogun/shogun
  ```

</details>
<details><summary><b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉22 ·  ⭐ 710 · 💀) - NeuPy是一个基于Tensorflow的python库，用于原型设计和构建。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/itdxer/neupy) ⭐ 736 | 🐛 39 | 🌐 Python | 📅 2024-11-18 (👨‍💻 7 · 🔀 150 · 📦 130 · 📋 270 - 12% open · ⏱️ 02.09.2019):

  ```
  git clone https://github.com/itdxer/neupy
  ```
* [PyPi](https://pypi.org/project/neupy) (📥 3.5K / month):
  ```
  pip install neupy
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉21 ·  ⭐ 2.1K) - 基于JAX的神经网络库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/deepmind/dm-haiku) ⭐ 3,274 | 🐛 105 | 🌐 Python | 📅 2026-08-06 (👨‍💻 63 · 🔀 170 · 📦 540 · 📋 180 - 26% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/deepmind/dm-haiku
  ```

</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉20 ·  ⭐ 4.7K) - MACE是针对移动设备优化的深度学习推理框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/XiaoMi/mace) ⭐ 5,044 | 🐛 62 | 🌐 C++ | 📅 2024-06-17 (👨‍💻 64 · 🔀 790 · 📥 1.4K · 📋 660 - 7% open · ⏱️ 30.05.2022):

  ```
  git clone https://github.com/XiaoMi/mace
  ```

</details>
<details><summary><b><a href="https://github.com/google/objax">Objax</a></b> (🥉20 ·  ⭐ 720) - Objax是加速研究与应用的开源深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

* [GitHub](https://github.com/google/objax) ⚠️ Archived (👨‍💻 23 · 🔀 60 · 📦 25 · 📋 98 - 38% open · ⏱️ 12.07.2022):

  ```
  git clone https://github.com/google/objax
  ```
* [PyPi](https://pypi.org/project/objax) (📥 440 / month):
  ```
  pip install objax
  ```

</details>
<details><summary><b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉19 ·  ⭐ 9.7K) - 为各种现有数据库提供预测性AI层。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/mindsdb/mindsdb) ⭐ 39,637 | 🐛 2 | 🌐 Makefile | 📅 2026-08-21 (👨‍💻 130 · 🔀 1K · 📋 1.2K - 11% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/mindsdb/mindsdb
  ```
* [PyPi](https://pypi.org/project/mindsdb) (📥 2.9K / month):
  ```
  pip install mindsdb
  ```

</details>
<details><summary><b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉19 ·  ⭐ 3.9K · 💀) - 英特尔Nervana深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/NervanaSystems/neon) ⚠️ Archived (👨‍💻 110 · 🔀 800 · 📥 340 · 📋 390 - 21% open · ⏱️ 22.05.2019):

  ```
  git clone https://github.com/NervanaSystems/neon
  ```
* [PyPi](https://pypi.org/project/nervananeon) (📥 32 / month):
  ```
  pip install nervananeon
  ```

</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉19 ·  ⭐ 1.4K) - ThunderSVM：在GPU和CPU上的快速SVM库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Xtra-Computing/thundersvm) ⭐ 1,621 | 🐛 87 | 🌐 C++ | 📅 2024-04-01 (👨‍💻 34 · 🔀 190 · 📥 2.5K · 📋 210 - 29% open · ⏱️ 09.04.2022):

  ```
  git clone https://github.com/Xtra-Computing/thundersvm
  ```
* [PyPi](https://pypi.org/project/thundersvm) (📥 350 / month):
  ```
  pip install thundersvm
  ```

</details>
<details><summary><b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉19 ·  ⭐ 630 · 💀) - torchbearer：PyTorch的模型拟合库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorchbearer/torchbearer) ⭐ 641 | 🐛 10 | 🌐 Python | 📅 2023-12-04 (👨‍💻 13 · 🔀 66 · 📦 64 · 📋 250 - 4% open · ⏱️ 26.03.2021):

  ```
  git clone https://github.com/pytorchbearer/torchbearer
  ```
* [PyPi](https://pypi.org/project/torchbearer) (📥 700 / month):
  ```
  pip install torchbearer
  ```

</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉18 ·  ⭐ 400) - Elegy是Jax的与框架无关的Trainer工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code>jax</code></summary>

* [GitHub](https://github.com/poets-ai/elegy) ⭐ 472 | 🐛 47 | 🌐 Python | 📅 2022-12-15 (👨‍💻 17 · 🔀 26 · 📋 100 - 34% open · ⏱️ 23.05.2022):

  ```
  git clone https://github.com/poets-ai/elegy
  ```
* [PyPi](https://pypi.org/project/elegy) (📥 1K / month):
  ```
  pip install elegy
  ```

</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉17 ·  ⭐ 640) - ThunderGBM：GPU上的快速GBDT和随机森林。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Xtra-Computing/thundergbm) ⭐ 715 | 🐛 39 | 🌐 C++ | 📅 2025-03-19 (👨‍💻 10 · 🔀 82 · 📋 74 - 50% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/Xtra-Computing/thundergbm
  ```
* [PyPi](https://pypi.org/project/thundergbm) (📥 240 / month):
  ```
  pip install thundergbm
  ```

</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉15 ·  ⭐ 690) - neoml是可以用于深度学习和传统机器学习的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/neoml-lib/neoml) ⭐ 794 | 🐛 34 | 🌐 C++ | 📅 2025-11-26 (👨‍💻 32 · 🔀 110 · 📋 62 - 22% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/neoml-lib/neoml
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉12 ·  ⭐ 3.8K · 💀) - 学习embedding嵌入用于分类，检索和排序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/StarSpace) ⚠️ Archived (👨‍💻 17 · 🔀 510 · 📋 200 - 24% open · ⏱️ 13.12.2019):

  ```
  git clone https://github.com/facebookresearch/StarSpace
  ```

</details>
<br>

## 数据可视化

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*通用和特定于任务的数据可视化库。*

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇36 ·  ⭐ 16K) - matplotlib：Python绘图工具库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/matplotlib/matplotlib) ⭐ 23,103 | 🐛 1,471 | 🌐 Python | 📅 2026-08-23 (👨‍💻 1.4K · 🔀 6.3K · 📦 610K · 📋 8.8K - 17% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/matplotlib/matplotlib
  ```
* [PyPi](https://pypi.org/project/matplotlib) (📥 28M / month):
  ```
  pip install matplotlib
  ```
* [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 13M · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge matplotlib
  ```

</details>
<details><summary><b><a href="https://github.com/ydataai/pandas-profiling">pandas-profiling</a></b> (🥇33 ·  ⭐ 9.4K) - 从pandas DataFrame创建HTML分析报告。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ydataai/pandas-profiling) ⭐ 13,682 | 🐛 325 | 🌐 Python | 📅 2026-04-22 (👨‍💻 92 · 🔀 1.3K · 📦 8.8K · 📋 580 - 19% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pandas-profiling/pandas-profiling
  ```
* [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.2M / month):
  ```
  pip install pandas-profiling
  ```
* [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 270K · ⏱️ 02.05.2022):
  ```
  conda install -c conda-forge pandas-profiling
  ```

</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇33 ·  ⭐ 7.7K) - 用于Python的声明式统计可视化库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/altair-viz/altair) ⭐ 10,458 | 🐛 145 | 🌐 Python | 📅 2026-08-16 (👨‍💻 140 · 🔀 650 · 📦 32K · 📋 1.6K - 13% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/altair-viz/altair
  ```
* [PyPi](https://pypi.org/project/altair) (📥 7.3M / month):
  ```
  pip install altair
  ```
* [Conda](https://anaconda.org/conda-forge/altair) (📥 1.3M · ⏱️ 29.12.2021):
  ```
  conda install -c conda-forge altair
  ```

</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇32 ·  ⭐ 17K) - 适用于Python，R，Julia和Jupyter的分析型Web应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/plotly/dash) ⭐ 24,380 | 🐛 540 | 🌐 Python | 📅 2026-08-23 (👨‍💻 120 · 🔀 1.7K · 📦 220 · 📋 1.3K - 47% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/plotly/dash
  ```
* [PyPi](https://pypi.org/project/dash) (📥 1M / month):
  ```
  pip install dash
  ```
* [Conda](https://anaconda.org/conda-forge/dash) (📥 590K · ⏱️ 03.08.2022):
  ```
  conda install -c conda-forge dash
  ```

</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇32 ·  ⭐ 12K) - 适用于Python的交互式图形库（包括Plotly Express）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/plotly/plotly.py) ⭐ 18,751 | 🐛 780 | 🌐 Python | 📅 2026-08-21 (👨‍💻 200 · 🔀 2.1K · 📦 12 · 📋 2.4K - 49% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/plotly/plotly.py
  ```
* [PyPi](https://pypi.org/project/plotly) (📥 8.6M / month):
  ```
  pip install plotly
  ```
* [Conda](https://anaconda.org/conda-forge/plotly) (📥 3M · ⏱️ 14.08.2022):
  ```
  conda install -c conda-forge plotly
  ```
* [NPM](https://www.npmjs.com/package/plotlywidget) (📥 46K / month):
  ```
  npm install plotlywidget
  ```

</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥇32 ·  ⭐ 5.7K) - 均匀流形逼近和投影。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/lmcinnes/umap) ⭐ 8,254 | 🐛 525 | 🌐 Python | 📅 2026-08-21 (👨‍💻 100 · 🔀 630 · 📦 6K · 📋 640 - 52% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/lmcinnes/umap
  ```
* [PyPi](https://pypi.org/project/umap-learn) (📥 650K / month):
  ```
  pip install umap-learn
  ```

</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈30 ·  ⭐ 1.3K) - Graphviz的简单Python界面。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/xflr6/graphviz) ⭐ 1,804 | 🐛 10 | 🌐 Python | 📅 2026-07-11 (👨‍💻 19 · 🔀 180 · 📦 34K · 📋 140 - 4% open · ⏱️ 27.07.2022):

  ```
  git clone https://github.com/xflr6/graphviz
  ```
* [PyPi](https://pypi.org/project/graphviz) (📥 10M / month):
  ```
  pip install graphviz
  ```

</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥈29 ·  ⭐ 9.7K · 📉) - 使用matplotlib进行统计数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/mwaskom/seaborn) ⭐ 14,007 | 🐛 229 | 🌐 Python | 📅 2026-07-06 (👨‍💻 170 · 🔀 1.6K · 📥 230 · 📋 2.1K - 4% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/mwaskom/seaborn
  ```
* [PyPi](https://pypi.org/project/seaborn) (📥 7.6M / month):
  ```
  pip install seaborn
  ```
* [Conda](https://anaconda.org/conda-forge/seaborn) (📥 4.5M · ⏱️ 16.08.2021):
  ```
  conda install -c conda-forge seaborn
  ```

</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈29 ·  ⭐ 2.8K) - 快速准确地渲染大数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/holoviz/datashader) ⭐ 3,558 | 🐛 143 | 🌐 Python | 📅 2026-08-19 (👨‍💻 49 · 🔀 340 · 📦 1.3K · 📋 500 - 23% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/holoviz/datashader
  ```
* [PyPi](https://pypi.org/project/datashader) (📥 42K / month):
  ```
  pip install datashader
  ```
* [Conda](https://anaconda.org/conda-forge/datashader) (📥 370K · ⏱️ 10.08.2022):
  ```
  conda install -c conda-forge datashader
  ```

</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥈28 ·  ⭐ 17K) - 浏览器中的Python交互式数据可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/bokeh/bokeh) ⭐ 20,433 | 🐛 845 | 🌐 Python | 📅 2026-08-23 (👨‍💻 610 · 🔀 3.9K · 📦 150 · 📋 7K - 9% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/bokeh/bokeh
  ```
* [PyPi](https://pypi.org/project/bokeh) (📥 3.7M / month):
  ```
  pip install bokeh
  ```
* [Conda](https://anaconda.org/conda-forge/bokeh) (📥 8.3M · ⏱️ 15.08.2022):
  ```
  conda install -c conda-forge bokeh
  ```

</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈28 ·  ⭐ 13K) - Python Echarts绘图库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pyecharts/pyecharts) ⭐ 15,776 | 🐛 4 | 🌐 Python | 📅 2026-08-04 (👨‍💻 30 · 🔀 2.7K · 📦 2.4K · 📋 1.6K - 1% open · ⏱️ 25.04.2022):

  ```
  git clone https://github.com/pyecharts/pyecharts
  ```
* [PyPi](https://pypi.org/project/pyecharts) (📥 44K / month):
  ```
  pip install pyecharts
  ```

</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥈28 ·  ⭐ 3.3K) - 在缺失值和混乱数据下，用于数据可视化的python模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ResidentMario/missingno) ⭐ 4,212 | 🐛 14 | 🌐 Python | 📅 2024-05-14 (👨‍💻 17 · 🔀 410 · 📦 8.3K · 📋 120 - 6% open · ⏱️ 27.02.2022):

  ```
  git clone https://github.com/ResidentMario/missingno
  ```
* [PyPi](https://pypi.org/project/missingno) (📥 1M / month):
  ```
  pip install missingno
  ```
* [Conda](https://anaconda.org/conda-forge/missingno) (📥 210K · ⏱️ 15.02.2020):
  ```
  conda install -c conda-forge missingno
  ```

</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈27 ·  ⭐ 3.6K) - pandas数据结构的可视化工具。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/man-group/dtale) ⭐ 5,216 | 🐛 70 | 🌐 TypeScript | 📅 2026-07-24 (👨‍💻 27 · 🔀 290 · 📦 460 · 📋 470 - 8% open · ⏱️ 07.08.2022):

  ```
  git clone https://github.com/man-group/dtale
  ```
* [PyPi](https://pypi.org/project/dtale) (📥 100K / month):
  ```
  pip install dtale
  ```
* [Conda](https://anaconda.org/conda-forge/dtale) (📥 150K · ⏱️ 07.08.2022):
  ```
  conda install -c conda-forge dtale
  ```

</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈27 ·  ⭐ 3.3K) - 用于IPython / Jupyter笔记本的绘图库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/bqplot/bqplot) ⭐ 3,693 | 🐛 278 | 🌐 TypeScript | 📅 2026-05-07 (👨‍💻 59 · 🔀 440 · 📦 34 · 📋 570 - 36% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/bqplot/bqplot
  ```
* [PyPi](https://pypi.org/project/bqplot) (📥 81K / month):
  ```
  pip install bqplot
  ```
* [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1M · ⏱️ 22.08.2022):
  ```
  conda install -c conda-forge bqplot
  ```
* [NPM](https://www.npmjs.com/package/bqplot) (📥 9.3K / month):
  ```
  npm install bqplot
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥈27 ·  ⭐ 660) - 用于探索和验证机器学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/data-validation) ⭐ 782 | 🐛 16 | 🌐 Python | 📅 2026-08-14 (👨‍💻 24 · 🔀 130 · 📥 370 · 📦 540 · 📋 150 - 16% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/tensorflow/data-validation
  ```
* [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 1.1M / month):
  ```
  pip install tensorflow-data-validation
  ```

</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥈27 ·  ⭐ 620) - 用于构建的pandas，dask，xarray和networkx的高级绘图API。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/holoviz/hvplot) ⭐ 1,356 | 🐛 397 | 🌐 Python | 📅 2026-08-20 (👨‍💻 37 · 🔀 73 · 📦 1.6K · 📋 480 - 37% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/holoviz/hvplot
  ```
* [PyPi](https://pypi.org/project/hvplot) (📥 160K / month):
  ```
  pip install hvplot
  ```
* [Conda](https://anaconda.org/conda-forge/hvplot) (📥 210K · ⏱️ 09.05.2022):
  ```
  conda install -c conda-forge hvplot
  ```

</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥈26 ·  ⭐ 8.9K) - Python中的词云生成器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/amueller/word_cloud) ⭐ 10,536 | 🐛 138 | 🌐 Python | 📅 2026-01-22 (👨‍💻 65 · 🔀 2.2K · 📋 470 - 20% open · ⏱️ 27.06.2022):

  ```
  git clone https://github.com/amueller/word_cloud
  ```
* [PyPi](https://pypi.org/project/wordcloud) (📥 690K / month):
  ```
  pip install wordcloud
  ```
* [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 310K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge wordcloud
  ```

</details>
<details><summary><b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥈26 ·  ⭐ 2.6K · 💀) - Plotly + Pandas的生产力工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/santosjorge/cufflinks) ⭐ 3,094 | 🐛 104 | 🌐 Jupyter Notebook | 📅 2024-07-03 (👨‍💻 38 · 🔀 600 · 📦 6.5K · 📋 210 - 41% open · ⏱️ 25.02.2021):

  ```
  git clone https://github.com/santosjorge/cufflinks
  ```
* [PyPi](https://pypi.org/project/cufflinks) (📥 310K / month):
  ```
  pip install cufflinks
  ```

</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈26 ·  ⭐ 2.3K) - 使用Holoviews，您的数据可以可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/holoviz/holoviews) ⭐ 2,905 | 🐛 1,052 | 🌐 Python | 📅 2026-08-22 (👨‍💻 120 · 🔀 350 · 📋 2.8K - 31% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/holoviz/holoviews
  ```
* [PyPi](https://pypi.org/project/holoviews) (📥 380K / month):
  ```
  pip install holoviews
  ```
* [Conda](https://anaconda.org/conda-forge/holoviews) (📥 850K · ⏱️ 07.07.2022):
  ```
  conda install -c conda-forge holoviews
  ```
* [NPM](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 840 / month):
  ```
  npm install @pyviz/jupyterlab_pyviz
  ```

</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈26 ·  ⭐ 1.4K) - 通过简化的界面进行3D绘图和网格分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pyvista/pyvista) ⭐ 3,781 | 🐛 596 | 🌐 Python | 📅 2026-08-23 (👨‍💻 100 · 🔀 280 · 📥 660 · 📦 900 · 📋 920 - 28% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/pyvista/pyvista
  ```
* [PyPi](https://pypi.org/project/pyvista) (📥 46K / month):
  ```
  pip install pyvista
  ```
* [Conda](https://anaconda.org/conda-forge/pyvista) (📥 210K · ⏱️ 01.08.2022):
  ```
  conda install -c conda-forge pyvista
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉25 ·  ⭐ 7K · 💀) - 机器学习数据集的可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PAIR-code/facets) ⚠️ Archived (👨‍💻 28 · 🔀 850 · 📦 130 · 📋 150 - 50% open · ⏱️ 06.05.2021):

  ```
  git clone https://github.com/pair-code/facets
  ```
* [PyPi](https://pypi.org/project/facets-overview) (📥 300K / month):
  ```
  pip install facets-overview
  ```

</details>
<details><summary><b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 3.2K · 💀) - Python库，使数据科学家可以轻松创建。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/spotify/chartify) ⭐ 3,638 | 🐛 54 | 🌐 Python | 📅 2024-10-16 (👨‍💻 21 · 🔀 280 · 📦 65 · 📋 72 - 56% open · ⏱️ 05.02.2021):

  ```
  git clone https://github.com/spotify/chartify
  ```
* [PyPi](https://pypi.org/project/chartify) (📥 10K / month):
  ```
  pip install chartify
  ```
* [Conda](https://anaconda.org/conda-forge/chartify) (📥 21K · ⏱️ 07.11.2020):
  ```
  conda install -c conda-forge chartify
  ```

</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥉24 ·  ⭐ 2.9K) - 高性能交互式2D / 3D数据可视化库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/vispy/vispy) ⭐ 3,584 | 🐛 388 | 🌐 Python | 📅 2026-08-21 (👨‍💻 180 · 🔀 580 · 📦 820 · 📋 1.3K - 20% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/vispy/vispy
  ```
* [PyPi](https://pypi.org/project/vispy) (📥 51K / month):
  ```
  pip install vispy
  ```
* [Conda](https://anaconda.org/conda-forge/vispy) (📥 270K · ⏱️ 05.07.2022):
  ```
  conda install -c conda-forge vispy
  ```
* [NPM](https://www.npmjs.com/package/vispy) (📥 10 / month):
  ```
  npm install vispy
  ```

</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉24 ·  ⭐ 1.7K) - 一个Python工具箱，用于获得对高维的几何洞察力。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ContextLab/hypertools) ⭐ 1,887 | 🐛 5 | 🌐 Python | 📅 2026-07-24 (👨‍💻 21 · 🔀 150 · 📥 20 · 📦 210 · 📋 190 - 35% open · ⏱️ 12.02.2022):

  ```
  git clone https://github.com/ContextLab/hypertools
  ```
* [PyPi](https://pypi.org/project/hypertools) (📥 550 / month):
  ```
  pip install hypertools
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉24 ·  ⭐ 830) - Jupyter-Three.js桥。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jupyter-widgets/pythreejs) ⭐ 988 | 🐛 77 | 🌐 JavaScript | 📅 2024-10-10 (👨‍💻 30 · 🔀 170 · 📦 21 · 📋 220 - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/jupyter-widgets/pythreejs
  ```
* [PyPi](https://pypi.org/project/pythreejs) (📥 64K / month):
  ```
  pip install pythreejs
  ```
* [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 410K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge pythreejs
  ```
* [NPM](https://www.npmjs.com/package/jupyter-threejs) (📥 4.6K / month):
  ```
  npm install jupyter-threejs
  ```

</details>
<details><summary><b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥉23 ·  ⭐ 2.9K) - 用于科学/工程的快速数据可视化和GUI工具。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/pyqtgraph/pyqtgraph) ⭐ 4,403 | 🐛 494 | 🌐 Python | 📅 2026-08-23 (👨‍💻 230 · 🔀 930 · 📋 1K - 31% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/pyqtgraph/pyqtgraph
  ```
* [PyPi](https://pypi.org/project/pyqtgraph) (📥 100K / month):
  ```
  pip install pyqtgraph
  ```
* [Conda](https://anaconda.org/conda-forge/pyqtgraph) (📥 280K · ⏱️ 05.03.2022):
  ```
  conda install -c conda-forge pyqtgraph
  ```

</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥉23 ·  ⭐ 1.8K) - 可视化，创建和调试图像和视频数据集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/voxel51/fiftyone) ⭐ 11,031 | 🐛 677 | 🌐 TypeScript | 📅 2026-08-23 (👨‍💻 46 · 🔀 220 · 📦 160 · 📋 890 - 31% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/voxel51/fiftyone
  ```
* [PyPi](https://pypi.org/project/fiftyone) (📥 21K / month):
  ```
  pip install fiftyone
  ```

</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉23 ·  ⭐ 1K) - t-SNE的可扩展并行实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/pavlin-policar/openTSNE) ⭐ 1,621 | 🐛 7 | 🌐 Python | 📅 2026-08-02 (👨‍💻 10 · 🔀 120 · 📦 380 · 📋 110 - 5% open · ⏱️ 18.03.2022):

  ```
  git clone https://github.com/pavlin-policar/openTSNE
  ```
* [PyPi](https://pypi.org/project/opentsne) (📥 21K / month):
  ```
  pip install opentsne
  ```
* [Conda](https://anaconda.org/conda-forge/opentsne) (📥 150K · ⏱️ 27.05.2022):
  ```
  conda install -c conda-forge opentsne
  ```

</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉23 ·  ⭐ 580) - 带有matplotlib的python三元绘图库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/marcharper/python-ternary) ⭐ 779 | 🐛 37 | 🌐 Python | 📅 2024-06-12 (👨‍💻 27 · 🔀 140 · 📥 18 · 📦 100 · 📋 130 - 25% open · ⏱️ 27.02.2022):

  ```
  git clone https://github.com/marcharper/python-ternary
  ```
* [PyPi](https://pypi.org/project/python-ternary) (📥 27K / month):
  ```
  pip install python-ternary
  ```
* [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 66K · ⏱️ 17.02.2021):
  ```
  conda install -c conda-forge python-ternary
  ```

</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉22 ·  ⭐ 2.1K) - 可视化和比较数据集，目标值和相关性。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/fbdesignpro/sweetviz) ⭐ 3,118 | 🐛 41 | 🌐 Python | 📅 2026-04-11 (👨‍💻 6 · 🔀 210 · 📋 100 - 28% open · ⏱️ 08.06.2022):

  ```
  git clone https://github.com/fbdesignpro/sweetviz
  ```
* [PyPi](https://pypi.org/project/sweetviz) (📥 64K / month):
  ```
  pip install sweetviz
  ```

</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉22 ·  ⭐ 780) - 一个用于统计数据的开源绘图库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/JetBrains/lets-plot) ⭐ 1,778 | 🐛 144 | 🌐 Kotlin | 📅 2026-07-02 (👨‍💻 17 · 🔀 34 · 📥 300 · 📦 17 · 📋 270 - 27% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/JetBrains/lets-plot
  ```
* [PyPi](https://pypi.org/project/lets-plot) (📥 1.8K / month):
  ```
  pip install lets-plot
  ```

</details>
<details><summary><b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉22 ·  ⭐ 700 · 💀) - python部分依赖图工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/SauceCat/PDPbox) ⭐ 860 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2024-09-03 (👨‍💻 7 · 🔀 110 · 📦 510 · 📋 60 - 36% open · ⏱️ 14.03.2021):

  ```
  git clone https://github.com/SauceCat/PDPbox
  ```
* [PyPi](https://pypi.org/project/pdpbox) (📥 34K / month):
  ```
  pip install pdpbox
  ```
* [Conda](https://anaconda.org/conda-forge/pdpbox) (📥 13K · ⏱️ 14.03.2021):
  ```
  conda install -c conda-forge pdpbox
  ```

</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥉21 ·  ⭐ 4.8K) - 通过WebAssembly进行流式透视显示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/finos/perspective) ⭐ 11,130 | 🐛 60 | 🌐 Rust | 📅 2026-08-10 (👨‍💻 72 · 🔀 490 · 📦 4 · 📋 540 - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/finos/perspective
  ```
* [PyPi](https://pypi.org/project/perspective-python) (📥 3K / month):
  ```
  pip install perspective-python
  ```
* [NPM](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.4K / month):
  ```
  npm install @finos/perspective-jupyterlab
  ```

</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥉21 ·  ⭐ 3.2K) - Python的图形语法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/has2k1/plotnine) ⭐ 4,758 | 🐛 85 | 🌐 Python | 📅 2026-08-15 (👨‍💻 96 · 🔀 170 · 📋 500 - 13% open · ⏱️ 01.07.2022):

  ```
  git clone https://github.com/has2k1/plotnine
  ```
* [PyPi](https://pypi.org/project/plotnine) (📥 350K / month):
  ```
  pip install plotnine
  ```
* [Conda](https://anaconda.org/conda-forge/plotnine) (📥 190K · ⏱️ 02.07.2022):
  ```
  conda install -c conda-forge plotnine
  ```

</details>
<details><summary><b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉21 ·  ⭐ 1.7K · 💀) - 使用Python和Torch并行执行t-SNE。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/DmitryUlyanov/Multicore-TSNE) ⭐ 1,909 | 🐛 41 | 🌐 C++ | 📅 2024-02-06 (👨‍💻 15 · 🔀 200 · 📦 310 · 📋 58 - 63% open · ⏱️ 19.08.2020):

  ```
  git clone https://github.com/DmitryUlyanov/Multicore-TSNE
  ```
* [PyPi](https://pypi.org/project/MulticoreTSNE) (📥 19K / month):
  ```
  pip install MulticoreTSNE
  ```
* [Conda](https://anaconda.org/conda-forge/multicore-tsne) (📥 18K · ⏱️ 09.11.2021):
  ```
  conda install -c conda-forge multicore-tsne
  ```

</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉20 ·  ⭐ 890) - 自动显示任意行的任何大小的任何数据集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/AutoViML/AutoViz) ⭐ 1,896 | 🐛 2 | 🌐 Python | 📅 2024-06-10 (👨‍💻 12 · 🔀 120 · 📦 240 · 📋 59 - 5% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/AutoViML/AutoViz
  ```
* [PyPi](https://pypi.org/project/autoviz) (📥 52K / month):
  ```
  pip install autoviz
  ```

</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉20 ·  ⭐ 500) - 用Python作图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/gyli/PyWaffle) ⭐ 599 | 🐛 6 | 🌐 Python | 📅 2024-06-16 (👨‍💻 6 · 🔀 92 · 📦 150 · 📋 18 - 22% open · ⏱️ 08.06.2022):

  ```
  git clone https://github.com/gyli/PyWaffle
  ```
* [PyPi](https://pypi.org/project/pywaffle) (📥 8.3K / month):
  ```
  pip install pywaffle
  ```

</details>
<details><summary><b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉19 ·  ⭐ 2.7K) - pandas Dataframe的GUI。<code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/adamerose/PandasGUI) ⭐ 3,257 | 🐛 82 | 🌐 Python | 📅 2025-05-30 (👨‍💻 13 · 🔀 180 · 📦 170 · 📋 160 - 27% open · ⏱️ 16.03.2022):

  ```
  git clone https://github.com/adamerose/pandasgui
  ```
* [PyPi](https://pypi.org/project/pandasgui) (📥 3.7K / month):
  ```
  pip install pandasgui
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉19 ·  ⭐ 2.3K) - HiPlot使理解高维数据变得容易。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/hiplot) ⚠️ Archived (👨‍💻 8 · 🔀 120 · 📦 5 · 📋 80 - 15% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/facebookresearch/hiplot
  ```
* [PyPi](https://pypi.org/project/hiplot) (📥 27K / month):
  ```
  pip install hiplot
  ```
* [Conda](https://anaconda.org/conda-forge/hiplot) (📥 98K · ⏱️ 31.05.2022):
  ```
  conda install -c conda-forge hiplot
  ```

</details>
<details><summary><b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉19 ·  ⭐ 470 · 💀) - Jupyter/IPython的Dragndrop数据透视表和图表。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/nicolaskruchten/jupyter_pivottablejs) ⭐ 708 | 🐛 26 | 🌐 Python | 📅 2024-03-15 (👨‍💻 3 · 🔀 62 · 📦 260 · 📋 58 - 29% open · ⏱️ 04.12.2018):

  ```
  git clone https://github.com/nicolaskruchten/jupyter_pivottablejs
  ```
* [PyPi](https://pypi.org/project/pivottablejs) (📥 14K / month):
  ```
  pip install pivottablejs
  ```

</details>
<details><summary><b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉19 ·  ⭐ 440 · 💤) - 带有matplotlib和pandas的Python中的Joyplots。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/leotac/joypy) ⭐ 611 | 🐛 20 | 🌐 Jupyter Notebook | 📅 2024-03-21 (👨‍💻 6 · 🔀 47 · 📦 190 · 📋 47 - 21% open · ⏱️ 19.12.2021):

  ```
  git clone https://github.com/sbebo/joypy
  ```
* [PyPi](https://pypi.org/project/joypy) (📥 13K / month):
  ```
  pip install joypy
  ```
* [Conda](https://anaconda.org/conda-forge/joypy) (📥 15K · ⏱️ 28.12.2020):
  ```
  conda install -c conda-forge joypy
  ```

</details>
<details><summary><b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉19 ·  ⭐ 280) - 使用算法对非常大的数据集进行降维。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/beringresearch/ivis) ⭐ 345 | 🐛 4 | 🌐 Python | 📅 2025-11-10 (👨‍💻 10 · 🔀 35 · 📦 26 · 📋 57 - 5% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/beringresearch/ivis
  ```
* [PyPi](https://pypi.org/project/ivis) (📥 330 / month):
  ```
  pip install ivis
  ```

</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉18 ·  ⭐ 800) - pandas和GeoPandas的Bokeh绘图后端。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) ⭐ 881 | 🐛 41 | 🌐 Python | 📅 2024-04-10 (👨‍💻 14 · 🔀 100 · 📋 98 - 31% open · ⏱️ 25.03.2022):

  ```
  git clone https://github.com/PatrikHlobil/Pandas-Bokeh
  ```
* [PyPi](https://pypi.org/project/pandas-bokeh) (📥 14K / month):
  ```
  pip install pandas-bokeh
  ```

</details>
<details><summary><b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉18 ·  ⭐ 400 · 💀) - 用于在patpliblib上构建动画图的python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/t-makaro/animatplot) ⭐ 419 | 🐛 17 | 🌐 Python | 📅 2024-08-29 (👨‍💻 7 · 🔀 34 · 📦 35 · 📋 30 - 43% open · ⏱️ 05.10.2020):

  ```
  git clone https://github.com/t-makaro/animatplot
  ```
* [PyPi](https://pypi.org/project/animatplot) (📥 260 / month):
  ```
  pip install animatplot
  ```
* [Conda](https://anaconda.org/conda-forge/animatplot) (📥 9K · ⏱️ 06.10.2020):
  ```
  conda install -c conda-forge animatplot
  ```

</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉18 ·  ⭐ 330) - 适用于Vega和Vega-Lite的IPython/Jupyter笔记本模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/vega/ipyvega) ⭐ 389 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2025-04-01 (👨‍💻 11 · 🔀 55 · 📋 95 - 13% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/vega/ipyvega
  ```
* [PyPi](https://pypi.org/project/vega) (📥 7.3K / month):
  ```
  pip install vega
  ```
* [Conda](https://anaconda.org/conda-forge/vega) (📥 500K · ⏱️ 10.02.2022):
  ```
  conda install -c conda-forge vega
  ```

</details>
<details><summary><b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 340 · 💀) - 使用Vega-Lite交互式绘制pandas数据图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/altair-viz/pdvega) ⚠️ Archived (👨‍💻 9 · 🔀 31 · 📦 67 · 📋 26 - 61% open · ⏱️ 29.03.2019):

  ```
  git clone https://github.com/altair-viz/pdvega
  ```
* [PyPi](https://pypi.org/project/pdvega) (📥 56 / month):
  ```
  pip install pdvega
  ```

</details>
<details><summary><b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉14 ·  ⭐ 290 · 💤) - 数据描述：Pythonic EDA数据科学加速器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/data-describe/data-describe) ⭐ 300 | 🐛 77 | 🌐 Python | 📅 2023-02-22 (👨‍💻 14 · 🔀 18 · 📋 240 - 28% open · ⏱️ 19.11.2021):

  ```
  git clone https://github.com/data-describe/data-describe
  ```
* [PyPi](https://pypi.org/project/data-describe) (📥 2.6K / month):
  ```
  pip install data-describe
  ```

</details>
<details><summary><b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉14 ·  ⭐ 200 · 💀) - 使用Altair绘制交互式NetworkX图形。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Zsailer/nx_altair) ⭐ 228 | 🐛 10 | 🌐 Python | 📅 2023-09-27 (👨‍💻 3 · 🔀 23 · 📋 10 - 60% open · ⏱️ 02.06.2020):

  ```
  git clone https://github.com/Zsailer/nx_altair
  ```
* [PyPi](https://pypi.org/project/nx-altair) (📥 1.5K / month):
  ```
  pip install nx-altair
  ```

</details>
<details><summary><b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉11 ·  ⭐ 29 · 💀) - nptsne是numpy兼容的python二进制包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/biovault/nptsne) ⭐ 34 | 🐛 7 | 🌐 C | 📅 2026-04-24 (👨‍💻 3 · 🔀 2 · 📦 4 · 📋 13 - 53% open · ⏱️ 03.02.2021):

  ```
  git clone https://github.com/biovault/nptsne
  ```
* [PyPi](https://pypi.org/project/nptsne) (📥 70 / month):
  ```
  pip install nptsne
  ```

</details>
<br>

## 文本数据和NLP

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于处理，清理，处理和分析文本数据的库，以及用于NLP任务的库，例如语言检测，模糊匹配，文本分类，seq2seq学习，智能对话，关键字提取和机器翻译。*

<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇38 ·  ⭐ 24K) - Python中的工业级自然语言处理（NLP）工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/explosion/spaCy) ⭐ 33,840 | 🐛 237 | 🌐 Python | 📅 2026-08-07 (👨‍💻 700 · 🔀 3.8K · 📥 3.1K · 📦 43K · 📋 5.2K - 1% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/explosion/spaCy
  ```
* [PyPi](https://pypi.org/project/spacy) (📥 4.7M / month):
  ```
  pip install spacy
  ```
* [Conda](https://anaconda.org/conda-forge/spacy) (📥 2.8M · ⏱️ 27.07.2022):
  ```
  conda install -c conda-forge spacy
  ```

</details>
<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇37 ·  ⭐ 69K) - transformers：先进的自然语言模型库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/huggingface/transformers) ⭐ 164,372 | 🐛 2,407 | 🌐 Python | 📅 2026-08-23 (👨‍💻 1.4K · 🔀 15K · 📥 1.5K · 📦 34K · 📋 9.9K - 4% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/huggingface/transformers
  ```
* [PyPi](https://pypi.org/project/transformers) (📥 6.1M / month):
  ```
  pip install transformers
  ```
* [Conda](https://anaconda.org/conda-forge/transformers) (📥 370K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge transformers
  ```

</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇36 ·  ⭐ 13K) - 主题模型工具库。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

* [GitHub](https://github.com/RaRe-Technologies/gensim) ⭐ 16,478 | 🐛 438 | 🌐 Python | 📅 2025-11-01 (👨‍💻 430 · 🔀 4K · 📥 3.8K · 📦 36K · 📋 1.8K - 20% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/RaRe-Technologies/gensim
  ```
* [PyPi](https://pypi.org/project/gensim) (📥 4.9M / month):
  ```
  pip install gensim
  ```
* [Conda](https://anaconda.org/conda-forge/gensim) (📥 860K · ⏱️ 29.07.2022):
  ```
  conda install -c conda-forge gensim
  ```

</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥇34 ·  ⭐ 8.3K) - BERT和XLNet的句子嵌入。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/UKPLab/sentence-transformers) ⭐ 19,029 | 🐛 1,318 | 🌐 Python | 📅 2026-08-21 (👨‍💻 93 · 🔀 1.6K · 📦 4K · 📋 1.5K - 51% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/UKPLab/sentence-transformers
  ```
* [PyPi](https://pypi.org/project/sentence-transformers) (📥 1.5M / month):
  ```
  pip install sentence-transformers
  ```

</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇33 ·  ⭐ 11K) - 基于PyTorch的开源NLP研究库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/allenai/allennlp) ⚠️ Archived (👨‍💻 260 · 🔀 2.1K · 📥 47 · 📦 2.7K · 📋 2.5K - 3% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/allenai/allennlp
  ```
* [PyPi](https://pypi.org/project/allennlp) (📥 72K / month):
  ```
  pip install allennlp
  ```

</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇33 ·  ⭐ 11K) - 用于符号和统计自然的库和程序套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nltk/nltk) ⭐ 14,701 | 🐛 231 | 🌐 Python | 📅 2026-08-20 (👨‍💻 430 · 🔀 2.5K · 📦 150K · 📋 1.6K - 13% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/nltk/nltk
  ```
* [PyPi](https://pypi.org/project/nltk) (📥 12M / month):
  ```
  pip install nltk
  ```
* [Conda](https://anaconda.org/conda-forge/nltk) (📥 1.4M · ⏱️ 29.12.2021):
  ```
  conda install -c conda-forge nltk
  ```

</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥇33 ·  ⭐ 6.1K) - 用于基于神经网络的文本的预处理器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/google/sentencepiece) ⭐ 12,038 | 🐛 5 | 🌐 C++ | 📅 2026-08-16 (👨‍💻 68 · 🔀 810 · 📥 22K · 📦 17K · 📋 540 - 2% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/google/sentencepiece
  ```
* [PyPi](https://pypi.org/project/sentencepiece) (📥 5.6M / month):
  ```
  pip install sentencepiece
  ```
* [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 220K · ⏱️ 08.04.2022):
  ```
  conda install -c conda-forge sentencepiece
  ```

</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇32 ·  ⭐ 12K · 💀) - ChatterBot是机器学习的对话引擎。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/gunthercox/ChatterBot) ⭐ 14,509 | 🐛 75 | 🌐 Python | 📅 2026-08-23 (👨‍💻 100 · 🔀 4K · 📦 4.5K · 📋 1.6K - 19% open · ⏱️ 01.06.2021):

  ```
  git clone https://github.com/gunthercox/ChatterBot
  ```
* [PyPi](https://pypi.org/project/chatterbot) (📥 71K / month):
  ```
  pip install chatterbot
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥇31 ·  ⭐ 24K) - 用于快速文本表示和分类的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/fastText) ⚠️ Archived (👨‍💻 59 · 🔀 4.3K · 📦 3.2K · 📋 1K - 41% open · ⏱️ 04.03.2022):

  ```
  git clone https://github.com/facebookresearch/fastText
  ```
* [PyPi](https://pypi.org/project/fasttext) (📥 810K / month):
  ```
  pip install fasttext
  ```
* [Conda](https://anaconda.org/conda-forge/fasttext) (📥 36K · ⏱️ 16.04.2022):
  ```
  conda install -c conda-forge fasttext
  ```

</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥇31 ·  ⭐ 8.3K · 💤) - 包含情感分析、词性标注等等功能的NLP工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/sloria/TextBlob) ⭐ 9,544 | 🐛 71 | 🌐 Python | 📅 2026-08-18 (👨‍💻 35 · 🔀 1K · 📥 100 · 📦 22K · 📋 250 - 37% open · ⏱️ 22.10.2021):

  ```
  git clone https://github.com/sloria/TextBlob
  ```
* [PyPi](https://pypi.org/project/textblob) (📥 860K / month):
  ```
  pip install textblob
  ```
* [Conda](https://anaconda.org/conda-forge/textblob) (📥 170K · ⏱️ 24.02.2019):
  ```
  conda install -c conda-forge textblob
  ```

</details>
<details><summary><b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥈30 ·  ⭐ 12K) - 一个用于最先进的自然语言处理的非常简单的框架。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/flairNLP/flair) ⭐ 14,383 | 🐛 31 | 🌐 Python | 📅 2025-10-27 (👨‍💻 230 · 🔀 1.6K · 📦 1.6K · 📋 1.9K - 6% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/flairNLP/flair
  ```
* [PyPi](https://pypi.org/project/flair) (📥 170K / month):
  ```
  pip install flair
  ```

</details>
<details><summary><b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥈30 ·  ⭐ 8.7K · 💤) - Python中的模糊字符串匹配。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

* [GitHub](https://github.com/seatgeek/fuzzywuzzy) ⚠️ Archived (👨‍💻 70 · 🔀 870 · 📦 14K · 📋 180 - 43% open · ⏱️ 09.09.2021):

  ```
  git clone https://github.com/seatgeek/fuzzywuzzy
  ```
* [PyPi](https://pypi.org/project/fuzzywuzzy) (📥 7.3M / month):
  ```
  pip install fuzzywuzzy
  ```
* [Conda](https://anaconda.org/conda-forge/fuzzywuzzy) (📥 380K · ⏱️ 18.11.2020):
  ```
  conda install -c conda-forge fuzzywuzzy
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairseq">fairseq</a></b> (🥈29 ·  ⭐ 19K) - 用Python编写的Facebook AI Research Sequence-to-Sequence工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/fairseq) ⚠️ Archived (👨‍💻 400 · 🔀 4.7K · 📥 260 · 📦 920 · 📋 3.5K - 18% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/pytorch/fairseq
  ```
* [PyPi](https://pypi.org/project/fairseq) (📥 40K / month):
  ```
  pip install fairseq
  ```

</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈29 ·  ⭐ 2.9K) - 计算序列之间的距离，包含30多种算法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/life4/textdistance) ⭐ 3,539 | 🐛 10 | 🌐 Python | 📅 2025-04-18 (👨‍💻 12 · 🔀 230 · 📥 830 · 📦 2.6K · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/life4/textdistance
  ```
* [PyPi](https://pypi.org/project/textdistance) (📥 640K / month):
  ```
  pip install textdistance
  ```
* [Conda](https://anaconda.org/conda-forge/textdistance) (📥 180K · ⏱️ 21.08.2022):
  ```
  conda install -c conda-forge textdistance
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈29 ·  ⭐ 980) - TensorFlow文本处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/text) ⭐ 1,292 | 🐛 235 | 🌐 C++ | 📅 2026-08-21 (👨‍💻 91 · 🔀 230 · 📦 2.2K · 📋 180 - 18% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/tensorflow/text
  ```
* [PyPi](https://pypi.org/project/tensorflow-text) (📥 2.2M / month):
  ```
  pip install tensorflow-text
  ```

</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈28 ·  ⭐ 2.4K · 💤) - 可轻松进行文本预处理，数据集加载和处理的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/dmlc/gluon-nlp) ⚠️ Archived (👨‍💻 82 · 🔀 490 · 📦 920 · 📋 530 - 44% open · ⏱️ 24.08.2021):

  ```
  git clone https://github.com/dmlc/gluon-nlp
  ```
* [PyPi](https://pypi.org/project/gluonnlp) (📥 160K / month):
  ```
  pip install gluonnlp
  ```

</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈27 ·  ⭐ 5.8K) - 一个用于深度学习端到端对话的开源库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepmipt/DeepPavlov) ⭐ 6,990 | 🐛 56 | 🌐 Python | 📅 2025-08-06 (👨‍💻 67 · 🔀 1K · 📦 280 · 📋 620 - 8% open · ⏱️ 31.05.2022):

  ```
  git clone https://github.com/deepmipt/DeepPavlov
  ```
* [PyPi](https://pypi.org/project/deeppavlov) (📥 8K / month):
  ```
  pip install deeppavlov
  ```

</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈27 ·  ⭐ 5.7K) - PyTorch中的开源神经机器翻译。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/OpenNMT/OpenNMT-py) ⭐ 7,012 | 🐛 23 | 🌐 Python | 📅 2025-10-14 (👨‍💻 180 · 🔀 2K · 📦 150 · 📋 1.3K - 6% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/OpenNMT/OpenNMT-py
  ```
* [PyPi](https://pypi.org/project/OpenNMT-py) (📥 5.2K / month):
  ```
  pip install OpenNMT-py
  ```

</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥈27 ·  ⭐ 2.9K) - 最先进的自然语言处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/JohnSnowLabs/spark-nlp) ⭐ 4,157 | 🐛 25 | 🌐 Scala | 📅 2026-08-20 (👨‍💻 130 · 🔀 570 · 📋 700 - 5% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/JohnSnowLabs/spark-nlp
  ```
* [PyPi](https://pypi.org/project/spark-nlp) (📥 2.4M / month):
  ```
  pip install spark-nlp
  ```

</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈27 ·  ⭐ 1.1K) - 使用经过预训练的transformer模型，例如BERT，XLNet和GPT-2。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

* [GitHub](https://github.com/explosion/spacy-transformers) ⭐ 1,408 | 🐛 2 | 🌐 Python | 📅 2026-03-27 (👨‍💻 18 · 🔀 140 · 📦 610 · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/explosion/spacy-transformers
  ```
* [PyPi](https://pypi.org/project/spacy-transformers) (📥 100K / month):
  ```
  pip install spacy-transformers
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥈26 ·  ⭐ 9.4K) - 一个用于训练和评估AI模型的框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/ParlAI) ⚠️ Archived (👨‍💻 200 · 🔀 1.8K · 📦 87 · 📋 1.4K - 5% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/facebookresearch/ParlAI
  ```
* [PyPi](https://pypi.org/project/parlai) (📥 3.4K / month):
  ```
  pip install parlai
  ```

</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈26 ·  ⭐ 5.8K) - 针对研究和应用进行了优化的快速最先进的分词器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/huggingface/tokenizers) ⭐ 10,986 | 🐛 270 | 🌐 Rust | 📅 2026-08-21 (👨‍💻 59 · 🔀 480 · 📦 51 · 📋 650 - 30% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/huggingface/tokenizers
  ```
* [PyPi](https://pypi.org/project/tokenizers) (📥 5.9M / month):
  ```
  pip install tokenizers
  ```
* [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 330K · ⏱️ 21.05.2022):
  ```
  conda install -c conda-forge tokenizers
  ```

</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈26 ·  ⭐ 2.9K) - 自动汇总文本文档和HTML页面的模块。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/miso-belica/sumy) ⭐ 3,701 | 🐛 7 | 🌐 Python | 📅 2026-08-14 (👨‍💻 23 · 🔀 470 · 📦 1.4K · 📋 110 - 15% open · ⏱️ 31.07.2022):

  ```
  git clone https://github.com/miso-belica/sumy
  ```
* [PyPi](https://pypi.org/project/sumy) (📥 21K / month):
  ```
  pip install sumy
  ```

</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈26 ·  ⭐ 1.7K · 💤) - 一个python库，用于进行文本相似度和距离计算。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/jamesturk/jellyfish) ⭐ 2,228 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-07-24 (👨‍💻 25 · 🔀 140 · 📦 4.1K · 📋 110 - 10% open · ⏱️ 07.01.2022):

  ```
  git clone https://github.com/jamesturk/jellyfish
  ```
* [PyPi](https://pypi.org/project/jellyfish) (📥 2.6M / month):
  ```
  pip install jellyfish
  ```
* [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 300K · ⏱️ 08.04.2022):
  ```
  conda install -c conda-forge jellyfish
  ```

</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥈25 ·  ⭐ 15K) - 开源机器学习框架，可处理文本和语音多场景问题。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/RasaHQ/rasa) ⭐ 21,302 | 🐛 154 | 🌐 Python | 📅 2026-07-24 (👨‍💻 550 · 🔀 4K · 📋 6.6K - 12% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/RasaHQ/rasa
  ```
* [PyPi](https://pypi.org/project/rasa) (📥 170K / month):
  ```
  pip install rasa
  ```

</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥈25 ·  ⭐ 6.2K) - 斯坦福NLP官方Python语言库，支持多种语言。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/stanfordnlp/stanza) ⭐ 7,866 | 🐛 92 | 🌐 Python | 📅 2026-08-23 (👨‍💻 48 · 🔀 790 · 📦 1.2K · 📋 720 - 11% open · ⏱️ 23.04.2022):

  ```
  git clone https://github.com/stanfordnlp/stanza
  ```
* [PyPi](https://pypi.org/project/stanza) (📥 330K / month):
  ```
  pip install stanza
  ```
* [Conda](https://anaconda.org/stanfordnlp/stanza) (📥 5.6K · ⏱️ 23.04.2022):
  ```
  conda install -c stanfordnlp stanza
  ```

</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈25 ·  ⭐ 3.3K) - 修复Unicode文本中的故障功能的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/rspeer/python-ftfy) ⭐ 4,061 | 🐛 25 | 🌐 Python | 📅 2024-10-30 (👨‍💻 18 · 🔀 110 · 📦 6.6K · 📋 130 - 9% open · ⏱️ 09.02.2022):

  ```
  git clone https://github.com/LuminosoInsight/python-ftfy
  ```
* [PyPi](https://pypi.org/project/ftfy) (📥 2.1M / month):
  ```
  pip install ftfy
  ```
* [Conda](https://anaconda.org/conda-forge/ftfy) (📥 180K · ⏱️ 13.03.2022):
  ```
  conda install -c conda-forge ftfy
  ```

</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥈25 ·  ⭐ 2.7K) - fastNLP：模块化和可扩展的NLP框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/fastnlp/fastNLP) ⭐ 3,141 | 🐛 71 | 🌐 Python | 📅 2023-06-05 (👨‍💻 59 · 🔀 420 · 📥 66 · 📦 90 · 📋 190 - 22% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/fastnlp/fastNLP
  ```
* [PyPi](https://pypi.org/project/fastnlp) (📥 2.5K / month):
  ```
  pip install fastnlp
  ```

</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥈25 ·  ⭐ 2.6K · 💀) - 基于SpaCy的神经网络实现快速共指解析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/huggingface/neuralcoref) ⭐ 2,892 | 🐛 65 | 🌐 C | 📅 2023-04-13 (👨‍💻 21 · 🔀 440 · 📥 450 · 📦 520 · 📋 300 - 16% open · ⏱️ 22.06.2021):

  ```
  git clone https://github.com/huggingface/neuralcoref
  ```
* [PyPi](https://pypi.org/project/neuralcoref) (📥 270K / month):
  ```
  pip install neuralcoref
  ```
* [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 12K · ⏱️ 21.02.2020):
  ```
  conda install -c conda-forge neuralcoref
  ```

</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈25 ·  ⭐ 1.9K) - TextRank的Python实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/DerwenAI/pytextrank) ⭐ 2,218 | 🐛 26 | 🌐 Python | 📅 2026-06-24 (👨‍💻 18 · 🔀 300 · 📦 280 · 📋 89 - 19% open · ⏱️ 27.07.2022):

  ```
  git clone https://github.com/DerwenAI/pytextrank
  ```
* [PyPi](https://pypi.org/project/pytextrank) (📥 70K / month):
  ```
  pip install pytextrank
  ```

</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥈25 ·  ⭐ 1.2K) - 完整的科学/生物医学的SpaCy应用案例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/allenai/scispacy) ⭐ 1,985 | 🐛 56 | 🌐 Python | 📅 2025-12-04 (👨‍💻 24 · 🔀 160 · 📦 500 · 📋 260 - 10% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/allenai/scispacy
  ```
* [PyPi](https://pypi.org/project/scispacy) (📥 21K / month):
  ```
  pip install scispacy
  ```

</details>
<details><summary><b><a href="https://github.com/WojciechMula/pyahocorasick">pyahocorasick</a></b> (🥈25 ·  ⭐ 740) - Python文本工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/WojciechMula/pyahocorasick) ⭐ 1,120 | 🐛 33 | 🌐 C | 📅 2026-04-27 (👨‍💻 24 · 🔀 110 · 📦 1.2K · 📋 120 - 20% open · ⏱️ 04.05.2022):

  ```
  git clone https://github.com/WojciechMula/pyahocorasick
  ```
* [PyPi](https://pypi.org/project/pyahocorasick) (📥 400K / month):
  ```
  pip install pyahocorasick
  ```
* [Conda](https://anaconda.org/conda-forge/pyahocorasick) (📥 150K · ⏱️ 15.04.2022):
  ```
  conda install -c conda-forge pyahocorasick
  ```

</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥈24 ·  ⭐ 11K) - 在不知道密钥或密码的情况下自动解密加密。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Ciphey/Ciphey) ⭐ 21,577 | 🐛 2 | 🌐 Rust | 📅 2026-08-18 (👨‍💻 46 · 🔀 650 · 📋 290 - 15% open · ⏱️ 28.06.2022):

  ```
  git clone https://github.com/Ciphey/Ciphey
  ```
* [PyPi](https://pypi.org/project/ciphey) (📥 23K / month):
  ```
  pip install ciphey
  ```
* [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 16K · ⭐ 8 · ⏱️ 27.05.2022):
  ```
  docker pull remnux/ciphey
  ```

</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈24 ·  ⭐ 3.7K) - VADER情感分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/cjhutto/vaderSentiment) ⭐ 5,050 | 🐛 56 | 🌐 Python | 📅 2026-03-02 (👨‍💻 11 · 🔀 880 · 📦 4.1K · 📋 110 - 31% open · ⏱️ 01.04.2022):

  ```
  git clone https://github.com/cjhutto/vaderSentiment
  ```
* [PyPi](https://pypi.org/project/vadersentiment) (📥 190K / month):
  ```
  pip install vadersentiment
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈24 ·  ⭐ 3.1K) - 文本和NLP的数据加载器和抽象。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/text) ⚠️ Archived (👨‍💻 140 · 🔀 700 · 📋 670 - 33% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/pytorch/text
  ```
* [PyPi](https://pypi.org/project/torchtext) (📥 270K / month):
  ```
  pip install torchtext
  ```

</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥈24 ·  ⭐ 2.1K · 💀) - PyTorch自然语言处理（NLP）的基本实用程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PetrochukM/PyTorch-NLP) ⚠️ Archived (👨‍💻 18 · 🔀 250 · 📦 410 · 📋 67 - 26% open · ⏱️ 10.07.2021):

  ```
  git clone https://github.com/PetrochukM/PyTorch-NLP
  ```
* [PyPi](https://pypi.org/project/pytorch-nlp) (📥 6K / month):
  ```
  pip install pytorch-nlp
  ```

</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈24 ·  ⭐ 740) - 古典语言工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/cltk/cltk) ⭐ 917 | 🐛 5 | 🌐 Python | 📅 2026-08-01 (👨‍💻 120 · 🔀 310 · 📥 25 · 📦 210 · 📋 530 - 5% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/cltk/cltk
  ```
* [PyPi](https://pypi.org/project/cltk) (📥 480 / month):
  ```
  pip install cltk
  ```

</details>
<details><summary><b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉23 ·  ⭐ 5.2K · 💀) - 从句子中提取关键字或替换句子中的关键字。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/vi3k6i5/flashtext) ⭐ 5,712 | 🐛 70 | 🌐 Python | 📅 2025-04-13 (👨‍💻 7 · 🔀 570 · 📦 850 · 📋 100 - 49% open · ⏱️ 03.05.2020):

  ```
  git clone https://github.com/vi3k6i5/flashtext
  ```
* [PyPi](https://pypi.org/project/flashtext) (📥 730K / month):
  ```
  pip install flashtext
  ```

</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥉23 ·  ⭐ 3.5K) - 一个用于准确和可扩展的模糊匹配的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/dedupeio/dedupe) ⭐ 4,505 | 🐛 90 | 🌐 Python | 📅 2025-07-29 (👨‍💻 64 · 🔀 460 · 📦 230 · 📋 760 - 7% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/dedupeio/dedupe
  ```
* [PyPi](https://pypi.org/project/dedupe) (📥 330K / month):
  ```
  pip install dedupe
  ```

</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥉23 ·  ⭐ 580 · 💤) - Snowball编译器和词干算法。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/snowballstem/snowball) ⭐ 874 | 🐛 30 | 🌐 C | 📅 2026-08-22 (👨‍💻 28 · 🔀 160 · 📦 4 · 📋 60 - 26% open · ⏱️ 17.12.2021):

  ```
  git clone https://github.com/snowballstem/snowball
  ```
* [PyPi](https://pypi.org/project/snowballstemmer) (📥 7.6M / month):
  ```
  pip install snowballstemmer
  ```
* [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 4.9M · ⏱️ 17.11.2021):
  ```
  conda install -c conda-forge snowballstemmer
  ```

</details>
<details><summary><b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉23 ·  ⭐ 470 · 💀) - pySBD（Python句子边界歧义消除）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/nipunsadvilkar/pySBD) ⭐ 931 | 🐛 33 | 🌐 Python | 📅 2024-08-20 (👨‍💻 6 · 🔀 58 · 📦 390 · 📋 65 - 21% open · ⏱️ 11.02.2021):

  ```
  git clone https://github.com/nipunsadvilkar/pySBD
  ```
* [PyPi](https://pypi.org/project/pysbd) (📥 52K / month):
  ```
  pip install pysbd
  ```

</details>
<details><summary><b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉23 ·  ⭐ 140 · 💀) - 获取Python中各种语言的常用停用词表。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Alir3z4/python-stop-words) ⭐ 164 | 🐛 2 | 🌐 Python | 📅 2025-11-03 (👨‍💻 8 · 🔀 26 · 📦 1.6K · 📋 12 - 25% open · ⏱️ 23.07.2018):

  ```
  git clone https://github.com/Alir3z4/python-stop-words
  ```
* [PyPi](https://pypi.org/project/stop-words) (📥 550K / month):
  ```
  pip install stop-words
  ```

</details>
<details><summary><b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉22 ·  ⭐ 4.7K · 💀) - 轻松地训练自己的文本生成神经网络。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/minimaxir/textgenrnn) ⭐ 4,923 | 🐛 145 | 🌐 Python | 📅 2022-07-17 (👨‍💻 19 · 🔀 720 · 📥 740 · 📦 1K · 📋 220 - 57% open · ⏱️ 14.07.2020):

  ```
  git clone https://github.com/minimaxir/textgenrnn
  ```
* [PyPi](https://pypi.org/project/textgenrnn) (📥 460 / month):
  ```
  pip install textgenrnn
  ```

</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥉22 ·  ⭐ 4.6K) - NeMo：用于智能对话的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/NVIDIA/NeMo) ⭐ 18,267 | 🐛 276 | 🌐 Python | 📅 2026-08-23 (👨‍💻 170 · 🔀 1.1K · 📥 15K · 📋 1.2K - 3% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/NVIDIA/NeMo
  ```
* [PyPi](https://pypi.org/project/nemo-toolkit) (📥 18K / month):
  ```
  pip install nemo-toolkit
  ```

</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥉22 ·  ⭐ 4.4K) - 探索迁移学习的论文源码<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) ⭐ 6,544 | 🐛 106 | 🌐 Python | 📅 2026-07-08 (👨‍💻 50 · 🔀 590 · 📦 110 · 📋 390 - 12% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/google-research/text-to-text-transfer-transformer
  ```
* [PyPi](https://pypi.org/project/t5) (📥 11K / month):
  ```
  pip install t5
  ```

</details>
<details><summary><b><a href="https://github.com/daviddrysdale/python-phonenumbers">phonenumbers</a></b> (🥉22 ·  ⭐ 3.1K) - Google的libphonenumber的Python端口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,766 | 🐛 11 | 🌐 Python | 📅 2026-08-14 (👨‍💻 26 · 🔀 370 · 📋 150 - 2% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/daviddrysdale/python-phonenumbers
  ```
* [PyPi](https://pypi.org/project/phonenumbers) (📥 4.6M / month):
  ```
  pip install phonenumbers
  ```
* [Conda](https://anaconda.org/conda-forge/phonenumbers) (📥 610K · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge phonenumbers
  ```

</details>
<details><summary><b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥉22 ·  ⭐ 2K · 💀) - 独立的语言识别系统。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/saffsd/langid.py) ⭐ 2,462 | 🐛 28 | 🌐 Python | 📅 2020-01-01 (👨‍💻 9 · 🔀 280 · 📦 1.1K · 📋 71 - 35% open · ⏱️ 15.07.2017):

  ```
  git clone https://github.com/saffsd/langid.py
  ```
* [PyPi](https://pypi.org/project/langid) (📥 380K / month):
  ```
  pip install langid
  ```

</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉22 ·  ⭐ 1.9K) - 文件之间语言分布的漂亮可视化效果。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/JasonKessler/scattertext) ⭐ 2,341 | 🐛 23 | 🌐 Python | 📅 2026-07-04 (👨‍💻 12 · 🔀 250 · 📦 310 · 📋 89 - 17% open · ⏱️ 26.03.2022):

  ```
  git clone https://github.com/JasonKessler/scattertext
  ```
* [PyPi](https://pypi.org/project/scattertext) (📥 2.4K / month):
  ```
  pip install scattertext
  ```
* [Conda](https://anaconda.org/conda-forge/scattertext) (📥 66K · ⏱️ 26.03.2022):
  ```
  conda install -c conda-forge scattertext
  ```

</details>
<details><summary><b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉22 ·  ⭐ 1.5K · 💀) - 双向LSTM-CRF和ELMo实现，可用于命名实体识别和文本分类等任务。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Hironsan/anago) ⭐ 1,482 | 🐛 46 | 🌐 Python | 📅 2022-12-07 (👨‍💻 11 · 🔀 360 · 📦 30 · 📋 110 - 33% open · ⏱️ 01.04.2021):

  ```
  git clone https://github.com/Hironsan/anago
  ```
* [PyPi](https://pypi.org/project/anago) (📥 1.2K / month):
  ```
  pip install anago
  ```

</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥉22 ·  ⭐ 1.4K · 💤) - 上下文相关性构建词向量。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/explosion/sense2vec) ⭐ 1,679 | 🐛 23 | 🌐 Python | 📅 2026-03-27 (👨‍💻 17 · 🔀 220 · 📥 36K · 📦 170 · 📋 110 - 18% open · ⏱️ 16.08.2021):

  ```
  git clone https://github.com/explosion/sense2vec
  ```
* [PyPi](https://pypi.org/project/sense2vec) (📥 3.5K / month):
  ```
  pip install sense2vec
  ```
* [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 27K · ⏱️ 14.07.2021):
  ```
  conda install -c conda-forge sense2vec
  ```

</details>
<details><summary><b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉21 ·  ⭐ 3.7K · 💀) - 从文本中提取含义的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/snipsco/snips-nlu) ⭐ 3,973 | 🐛 67 | 🌐 Python | 📅 2023-05-22 (👨‍💻 22 · 🔀 490 · 📋 260 - 23% open · ⏱️ 03.05.2021):

  ```
  git clone https://github.com/snipsco/snips-nlu
  ```
* [PyPi](https://pypi.org/project/snips-nlu) (📥 2.3K / month):
  ```
  pip install snips-nlu
  ```

</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉21 ·  ⭐ 2.5K) - 文本预处理，表示和可视化从入门到精通。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jbesomi/texthero) ⭐ 2,907 | 🐛 82 | 🌐 Python | 📅 2023-08-29 (👨‍💻 19 · 🔀 220 · 📥 92 · 📋 110 - 45% open · ⏱️ 19.07.2022):

  ```
  git clone https://github.com/jbesomi/texthero
  ```
* [PyPi](https://pypi.org/project/texthero) (📥 23K / month):
  ```
  pip install texthero
  ```

</details>
<details><summary><b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉21 ·  ⭐ 2.3K · 💀) - 机器学习，自然语言处理等工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/asyml/texar) ⭐ 2,389 | 🐛 40 | 🌐 Python | 📅 2026-07-21 (👨‍💻 43 · 🔀 360 · 📦 26 · 📋 160 - 19% open · ⏱️ 29.07.2020):

  ```
  git clone https://github.com/asyml/texar
  ```
* [PyPi](https://pypi.org/project/texar) (📥 65 / month):
  ```
  pip install texar
  ```

</details>
<details><summary><b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉21 ·  ⭐ 2K · 💀) - 多语言文本（NLP）处理工具包。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/aboSamoor/polyglot) ⭐ 2,361 | 🐛 170 | 🌐 Python | 📅 2023-11-10 (👨‍💻 26 · 🔀 310 · 📦 750 · 📋 210 - 68% open · ⏱️ 22.09.2020):

  ```
  git clone https://github.com/aboSamoor/polyglot
  ```
* [PyPi](https://pypi.org/project/polyglot) (📥 53K / month):
  ```
  pip install polyglot
  ```

</details>
<details><summary><b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉21 ·  ⭐ 820 · 💀) - 用于基于神经网络的文本的预处理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/VKCOM/YouTokenToMe) ⚠️ Archived (👨‍💻 6 · 🔀 61 · 📦 290 · 📋 54 - 55% open · ⏱️ 28.01.2021):

  ```
  git clone https://github.com/vkcom/youtokentome
  ```
* [PyPi](https://pypi.org/project/youtokentome) (📥 30K / month):
  ```
  pip install youtokentome
  ```

</details>
<details><summary><b><a href="https://github.com/jaraco/inflect">inflect</a></b> (🥉21 ·  ⭐ 690) - 辅助功能，正确生成复数，序数，不定冠词，转换数字。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jaraco/inflect) ⭐ 1,083 | 🐛 65 | 🌐 Python | 📅 2026-04-13 (👨‍💻 45 · 🔀 74 · 📋 91 - 18% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/jaraco/inflect
  ```
* [PyPi](https://pypi.org/project/inflect) (📥 2.5M / month):
  ```
  pip install inflect
  ```
* [Conda](https://anaconda.org/conda-forge/inflect) (📥 240K · ⏱️ 31.07.2022):
  ```
  conda install -c conda-forge inflect
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥉20 ·  ⭐ 6.4K) - 基于PyTorch的自然语言建模框架。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/pytext) ⚠️ Archived (👨‍💻 230 · 🔀 790 · 📥 300 · 📦 110 · 📋 140 - 45% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/facebookresearch/pytext
  ```
* [PyPi](https://pypi.org/project/pytext-nlp) (📥 180 / month):
  ```
  pip install pytext-nlp
  ```

</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉20 ·  ⭐ 3.7K · 💀) - 便于深层设计，比较和共享的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/NTMC-Community/MatchZoo) ⭐ 3,849 | 🐛 34 | 🌐 Python | 📅 2024-08-02 (👨‍💻 36 · 🔀 900 · 📦 11 · 📋 460 - 7% open · ⏱️ 02.06.2021):

  ```
  git clone https://github.com/NTMC-Community/MatchZoo
  ```
* [PyPi](https://pypi.org/project/matchzoo) (📥 63 / month):
  ```
  pip install matchzoo
  ```

</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉20 ·  ⭐ 2.9K) - 用于探索最先进的深度学习的模型库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/IntelLabs/nlp-architect) ⚠️ Archived (👨‍💻 37 · 🔀 430 · 📦 8 · 📋 130 - 11% open · ⏱️ 29.06.2022):

  ```
  git clone https://github.com/IntelLabs/nlp-architect
  ```
* [PyPi](https://pypi.org/project/nlp-architect) (📥 170 / month):
  ```
  pip install nlp-architect
  ```

</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥉20 ·  ⭐ 1.6K) - NLP的快速和轻松迁移学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepset-ai/FARM) ⚠️ Archived (👨‍💻 37 · 🔀 220 · 📋 400 - 0% open · ⏱️ 25.04.2022):

  ```
  git clone https://github.com/deepset-ai/FARM
  ```
* [PyPi](https://pypi.org/project/farm) (📥 4.4K / month):
  ```
  pip install farm
  ```

</details>
<details><summary><b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉20 ·  ⭐ 1.5K · 💀) - DELTA是一个基于深度学习的自然语言和语音处理平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Delta-ML/delta) ⚠️ Archived (👨‍💻 41 · 🔀 290 · 📋 75 - 1% open · ⏱️ 17.12.2020):

  ```
  git clone https://github.com/Delta-ML/delta
  ```
* [PyPi](https://pypi.org/project/delta-nlp) (📥 14 / month):
  ```
  pip install delta-nlp
  ```
* [Docker Hub](https://hub.docker.com/r/zh794390558/delta) (📥 13K · ⏱️ 03.08.2021):
  ```
  docker pull zh794390558/delta
  ```

</details>
<details><summary><b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉20 ·  ⭐ 230 · 💀) - fastText的另一个Python接口。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/vrasneur/pyfasttext) ⭐ 224 | 🐛 20 | 🌐 Python | 📅 2018-12-08 (👨‍💻 4 · 🔀 30 · 📥 350 · 📦 240 · 📋 49 - 42% open · ⏱️ 08.12.2018):

  ```
  git clone https://github.com/vrasneur/pyfasttext
  ```
* [PyPi](https://pypi.org/project/pyfasttext) (📥 3.4K / month):
  ```
  pip install pyfasttext
  ```

</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥉19 ·  ⭐ 5.2K) - 用于构建自然语言搜索的端到端Python框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/deepset-ai/haystack) ⭐ 26,293 | 🐛 103 | 🌐 Python | 📅 2026-08-22 (👨‍💻 140 · 🔀 830 · 📥 15 · 📋 1.5K - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/deepset-ai/haystack
  ```
* [PyPi](https://pypi.org/project/haystack) (📥 870 / month):
  ```
  pip install haystack
  ```

</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉19 ·  ⭐ 2.3K · 💀) - Kashgari是工业级的NLP迁移学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/BrikerMan/Kashgari) ⭐ 2,381 | 🐛 28 | 🌐 Python | 📅 2024-09-03 (👨‍💻 21 · 🔀 440 · 📦 54 · 📋 370 - 11% open · ⏱️ 09.07.2021):

  ```
  git clone https://github.com/BrikerMan/Kashgari
  ```
* [PyPi](https://pypi.org/project/kashgari-tf) (📥 44 / month):
  ```
  pip install kashgari-tf
  ```

</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉19 ·  ⭐ 1.8K) - 用于基于BERT的NLP模型的简单易用工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/utterworks/fast-bert) ⭐ 1,917 | 🐛 162 | 🌐 Python | 📅 2024-08-19 (👨‍💻 36 · 🔀 330 · 📋 250 - 61% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/kaushaltrivedi/fast-bert
  ```
* [PyPi](https://pypi.org/project/fast-bert) (📥 1.4K / month):
  ```
  pip install fast-bert
  ```

</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉19 ·  ⭐ 1.1K) - 序列到序列框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/awslabs/sockeye) ⭐ 1,215 | 🐛 12 | 🌐 Python | 📅 2024-10-24 (👨‍💻 57 · 🔀 300 · 📥 15 · 📋 280 - 2% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/awslabs/sockeye
  ```
* [PyPi](https://pypi.org/project/sockeye) (📥 370 / month):
  ```
  pip install sockeye
  ```

</details>
<details><summary><b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉18 ·  ⭐ 3K) - 可轻松重新训练OpenAI的GPT-2文本模型的Python软件包。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/minimaxir/gpt-2-simple) ⭐ 3,398 | 🐛 178 | 🌐 Python | 📅 2022-12-14 (👨‍💻 21 · 🔀 600 · 📥 340 · 📋 250 - 61% open · ⏱️ 22.05.2022):

  ```
  git clone https://github.com/minimaxir/gpt-2-simple
  ```
* [PyPi](https://pypi.org/project/gpt-2-simple) (📥 3.8K / month):
  ```
  pip install gpt-2-simple
  ```

</details>
<details><summary><b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥉18 ·  ⭐ 2K) - spaCy之前和之后的NLP。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/chartbeat-labs/textacy) ⭐ 2,239 | 🐛 35 | 🌐 Python | 📅 2023-09-22 (👨‍💻 32 · 🔀 230 · 📋 250 - 11% open · ⏱️ 06.03.2022):

  ```
  git clone https://github.com/chartbeat-labs/textacy
  ```
* [PyPi](https://pypi.org/project/textacy) (📥 38K / month):
  ```
  pip install textacy
  ```
* [Conda](https://anaconda.org/conda-forge/textacy) (📥 110K · ⏱️ 06.02.2022):
  ```
  conda install -c conda-forge textacy
  ```

</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉18 ·  ⭐ 660) - 针对NLP的Scikit风格模型微调。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/IndicoDataSolutions/finetune) ⭐ 720 | 🐛 78 | 🌐 Python | 📅 2026-05-05 (👨‍💻 19 · 🔀 71 · 📦 9 · 📋 140 - 15% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/IndicoDataSolutions/finetune
  ```
* [PyPi](https://pypi.org/project/finetune) (📥 96 / month):
  ```
  pip install finetune
  ```

</details>
<details><summary><b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉18 ·  ⭐ 230) - 适用于Python fastText的scikit-learn包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/shaypal5/skift) ⭐ 234 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-06-07 (👨‍💻 9 · 🔀 23 · 📦 12 · 📋 11 - 9% open · ⏱️ 07.06.2022):

  ```
  git clone https://github.com/shaypal5/skift
  ```
* [PyPi](https://pypi.org/project/skift) (📥 1.1K / month):
  ```
  pip install skift
  ```

</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉17 ·  ⭐ 440 · 💀) - 用于实体和文本匹配的Python包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/anhaidgroup/deepmatcher) ⭐ 622 | 🐛 75 | 🌐 Python | 📅 2024-06-18 (👨‍💻 7 · 🔀 98 · 📦 21 · 📋 86 - 72% open · ⏱️ 13.06.2021):

  ```
  git clone https://github.com/anhaidgroup/deepmatcher
  ```
* [PyPi](https://pypi.org/project/deepmatcher) (📥 1.1K / month):
  ```
  pip install deepmatcher
  ```

</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉16 ·  ⭐ 340 · 💤) - 适用于Transformers，Udify，ELmo等的spaCy插件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

* [GitHub](https://github.com/PKSHATechnology-Research/camphr) ⭐ 336 | 🐛 4 | 🌐 Python | 📅 2022-12-09 (👨‍💻 7 · 🔀 16 · 📋 28 - 7% open · ⏱️ 18.08.2021):

  ```
  git clone https://github.com/PKSHATechnology-Research/camphr
  ```
* [PyPi](https://pypi.org/project/camphr) (📥 75 / month):
  ```
  pip install camphr
  ```

</details>
<details><summary><b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉16 ·  ⭐ 300 · 💀) - Textpipe：从文本中清理并提取元数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/textpipe/textpipe) ⚠️ Archived (👨‍💻 28 · 🔀 23 · 📦 8 · 📋 40 - 37% open · ⏱️ 09.06.2021):

  ```
  git clone https://github.com/textpipe/textpipe
  ```
* [PyPi](https://pypi.org/project/textpipe) (📥 150 / month):
  ```
  pip install textpipe
  ```

</details>
<details><summary><b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉15 ·  ⭐ 1.6K · 💀) - 使用神经网络的命名实体识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Franck-Dernoncourt/NeuroNER) ⭐ 1,723 | 🐛 91 | 🌐 Python | 📅 2023-03-24 (👨‍💻 7 · 🔀 460 · 📋 150 - 55% open · ⏱️ 02.10.2019):

  ```
  git clone https://github.com/Franck-Dernoncourt/NeuroNER
  ```
* [PyPi](https://pypi.org/project/pyneuroner) (📥 100 / month):
  ```
  pip install pyneuroner
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 760) - Translate-PyTorch NLP库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/translate) ⚠️ Archived (👨‍💻 87 · 🔀 180 · 📋 38 - 28% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/pytorch/translate
  ```
* [PyPi](https://pypi.org/project/pytorch-translate) (📥 10 / month):
  ```
  pip install pytorch-translate
  ```

</details>
<details><summary><b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉15 ·  ⭐ 220 · 💀) - NeuralQA：用于对大型数据集进行问答构建。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/victordibia/neuralqa) ⭐ 234 | 🐛 43 | 🌐 JavaScript | 📅 2023-06-07 (👨‍💻 3 · 🔀 30 · 📦 4 · 📋 28 - 71% open · ⏱️ 16.12.2020):

  ```
  git clone https://github.com/victordibia/neuralqa
  ```
* [PyPi](https://pypi.org/project/neuralqa) (📥 68 / month):
  ```
  pip install neuralqa
  ```

</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉14 ·  ⭐ 3.8K) - 神经关系提取（NRE）的开源软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/thunlp/OpenNRE) ⭐ 4,467 | 🐛 19 | 🌐 Python | 📅 2024-01-10 (👨‍💻 10 · 🔀 950 · 📋 350 - 2% open · ⏱️ 06.04.2022):

  ```
  git clone https://github.com/thunlp/OpenNRE
  ```

</details>
<details><summary><b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉14 ·  ⭐ 290 · 💀) - 用于可重复的实验的NLP库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/feedly/transfer-nlp) ⚠️ Archived (👨‍💻 7 · 🔀 17 · 📋 23 - 13% open · ⏱️ 28.05.2020):

  ```
  git clone https://github.com/feedly/transfer-nlp
  ```
* [PyPi](https://pypi.org/project/transfer-nlp) (📥 100 / month):
  ```
  pip install transfer-nlp
  ```

</details>
<details><summary><b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉14 ·  ⭐ 200 · 💀) - 文本摘要，翻译，情感分析，文本生成等实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/abelriboulot/onnxt5) ⭐ 255 | 🐛 10 | 🌐 Python | 📅 2022-11-02 (👨‍💻 3 · 🔀 23 · 📦 1 · 📋 15 - 46% open · ⏱️ 28.01.2021):

  ```
  git clone https://github.com/abelriboulot/onnxt5
  ```
* [PyPi](https://pypi.org/project/onnxt5) (📥 57 / month):
  ```
  pip install onnxt5
  ```

</details>
<details><summary><b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉14 ·  ⭐ 180) - 胜过TF-IDF文本向量化工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/textvec/textvec) ⭐ 198 | 🐛 5 | 🌐 Python | 📅 2025-11-26 (👨‍💻 10 · 🔀 23 · 📦 4 · 📋 9 - 33% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/textvec/textvec
  ```
* [PyPi](https://pypi.org/project/textvec) (📥 26 / month):
  ```
  pip install textvec
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉13 ·  ⭐ 400) - 用于自然语言生成的分析工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/vizseq) ⭐ 457 | 🐛 7 | 🌐 Python | 📅 2026-08-18 (👨‍💻 3 · 🔀 49 · 📦 6 · 📋 15 - 40% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/facebookresearch/vizseq
  ```
* [PyPi](https://pypi.org/project/vizseq) (📥 59 / month):
  ```
  pip install vizseq
  ```

</details>
<details><summary><b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉11 ·  ⭐ 230 · 💀) - 轻松训练和部署seq2seq模型。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/as-ideas/headliner) ⚠️ Archived (👨‍💻 2 · 🔀 41 · 📦 3 · 📋 14 - 7% open · ⏱️ 14.02.2020):

  ```
  git clone https://github.com/as-ideas/headliner
  ```
* [PyPi](https://pypi.org/project/headliner) (📥 120 / month):
  ```
  pip install headliner
  ```

</details>
<br>

## 图像数据与CV

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于图像和视频处理，操纵和扩充的库，以及用于计算机视觉任务（例如面部识别，对象检测和图像分类）的库。*

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇36 ·  ⭐ 10K · 📈) - 友好的PIL分支（Python Imaging Library）。<code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

* [GitHub](https://github.com/python-pillow/Pillow) ⭐ 13,773 | 🐛 163 | 🌐 Python | 📅 2026-08-22 (👨‍💻 410 · 🔀 1.7K · 📦 820K · 📋 2.6K - 3% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/python-pillow/Pillow
  ```
* [PyPi](https://pypi.org/project/Pillow) (📥 45M / month):
  ```
  pip install Pillow
  ```
* [Conda](https://anaconda.org/conda-forge/pillow) (📥 18M · ⏱️ 13.08.2022):
  ```
  conda install -c conda-forge pillow
  ```

</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥇34 ·  ⭐ 9.5K) - 使用Python进行视频编辑。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Zulko/moviepy) ⭐ 14,861 | 🐛 93 | 🌐 Python | 📅 2026-08-11 (👨‍💻 150 · 🔀 1.2K · 📦 18K · 📋 1.2K - 24% open · ⏱️ 01.06.2022):

  ```
  git clone https://github.com/Zulko/moviepy
  ```
* [PyPi](https://pypi.org/project/moviepy) (📥 2.5M / month):
  ```
  pip install moviepy
  ```
* [Conda](https://anaconda.org/conda-forge/moviepy) (📥 130K · ⏱️ 16.04.2022):
  ```
  conda install -c conda-forge moviepy
  ```

</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇33 ·  ⭐ 1.1K) - 用于读取和写入图像数据的Python库。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/imageio/imageio) ⭐ 1,711 | 🐛 130 | 🌐 Python | 📅 2026-08-15 (👨‍💻 91 · 🔀 220 · 📥 360 · 📦 67K · 📋 470 - 12% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/imageio/imageio
  ```
* [PyPi](https://pypi.org/project/imageio) (📥 12M / month):
  ```
  pip install imageio
  ```
* [Conda](https://anaconda.org/conda-forge/imageio) (📥 3.5M · ⏱️ 08.08.2022):
  ```
  conda install -c conda-forge imageio
  ```

</details>
<details><summary><b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥇32 ·  ⭐ 13K · 💀) - 用于机器学习实验的图像增强。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/aleju/imgaug) ⭐ 14,740 | 🐛 311 | 🌐 Python | 📅 2024-07-30 (👨‍💻 36 · 🔀 2.3K · 📦 11K · 📋 490 - 55% open · ⏱️ 01.06.2020):

  ```
  git clone https://github.com/aleju/imgaug
  ```
* [PyPi](https://pypi.org/project/imgaug) (📥 390K / month):
  ```
  pip install imgaug
  ```
* [Conda](https://anaconda.org/conda-forge/imgaug) (📥 83K · ⏱️ 31.12.2021):
  ```
  conda install -c conda-forge imgaug
  ```

</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥇32 ·  ⭐ 11K) - 快速的图像增强库和易于使用的包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/albumentations-team/albumentations) ⚠️ Archived (👨‍💻 110 · 🔀 1.4K · 📦 9.1K · 📋 660 - 41% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/albumentations-team/albumentations
  ```
* [PyPi](https://pypi.org/project/albumentations) (📥 370K / month):
  ```
  pip install albumentations
  ```
* [Conda](https://anaconda.org/conda-forge/albumentations) (📥 49K · ⏱️ 12.07.2022):
  ```
  conda install -c conda-forge albumentations
  ```

</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥇32 ·  ⭐ 7K) - PyTorch的开源可微分计算机视觉库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/kornia/kornia) ⭐ 11,324 | 🐛 98 | 🌐 Python | 📅 2026-08-21 (👨‍💻 170 · 🔀 680 · 📥 430 · 📦 1.7K · 📋 600 - 26% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/kornia/kornia
  ```
* [PyPi](https://pypi.org/project/kornia) (📥 470K / month):
  ```
  pip install kornia
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇32 ·  ⭐ 5K) - Python中的图像处理。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/scikit-image/scikit-image) ⭐ 6,576 | 🐛 943 | 🌐 Python | 📅 2026-08-17 (👨‍💻 560 · 🔀 2K · 📦 110K · 📋 2.3K - 19% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/scikit-image/scikit-image
  ```
* [PyPi](https://pypi.org/project/scikit-image) (📥 5.3M / month):
  ```
  pip install scikit-image
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-image) (📥 3.8M · ⏱️ 10.08.2022):
  ```
  conda install -c conda-forge scikit-image
  ```

</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥇32 ·  ⭐ 1.2K) - 用于Python的基于ctypes的简单ImageMagick接口。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/emcconville/wand) ⭐ 1,480 | 🐛 29 | 🌐 Python | 📅 2026-08-06 (👨‍💻 100 · 🔀 190 · 📥 8.5K · 📦 12K · 📋 380 - 4% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/emcconville/wand
  ```
* [PyPi](https://pypi.org/project/wand) (📥 450K / month):
  ```
  pip install wand
  ```

</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥈31 ·  ⭐ 21K) - PyTorch图像模型，脚本，预训练权重。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rwightman/pytorch-image-models) ⭐ 37,084 | 🐛 62 | 🌐 Python | 📅 2026-08-21 (👨‍💻 79 · 🔀 3.3K · 📥 1.7M · 📦 4.3K · 📋 570 - 9% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/rwightman/pytorch-image-models
  ```

</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈29 ·  ⭐ 5.3K) - Gluon CV工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/dmlc/gluon-cv) ⭐ 5,916 | 🐛 61 | 🌐 Python | 📅 2024-11-25 (👨‍💻 120 · 🔀 1.2K · 📦 840 · 📋 810 - 5% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/dmlc/gluon-cv
  ```
* [PyPi](https://pypi.org/project/gluoncv) (📥 570K / month):
  ```
  pip install gluoncv
  ```

</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈29 ·  ⭐ 2.5K · 💤) - Python感知图像哈希模块。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/JohannesBuchner/imagehash) ⭐ 3,862 | 🐛 26 | 🌐 Python | 📅 2025-04-17 (👨‍💻 20 · 🔀 300 · 📦 5.8K · 📋 110 - 13% open · ⏱️ 07.09.2021):

  ```
  git clone https://github.com/JohannesBuchner/imagehash
  ```
* [PyPi](https://pypi.org/project/ImageHash) (📥 1.4M / month):
  ```
  pip install ImageHash
  ```
* [Conda](https://anaconda.org/conda-forge/imagehash) (📥 230K · ⏱️ 15.07.2021):
  ```
  conda install -c conda-forge imagehash
  ```

</details>
<details><summary><b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈28 ·  ⭐ 4.2K · 💤) - 图像处理库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/PyImageSearch/imutils) ⭐ 4,591 | 🐛 163 | 🌐 Python | 📅 2024-06-24 (👨‍💻 21 · 🔀 980 · 📦 27K · 📋 160 - 53% open · ⏱️ 27.01.2022):

  ```
  git clone https://github.com/jrosebr1/imutils
  ```
* [PyPi](https://pypi.org/project/imutils) (📥 330K / month):
  ```
  pip install imutils
  ```
* [Conda](https://anaconda.org/conda-forge/imutils) (📥 97K · ⏱️ 26.08.2022):
  ```
  conda install -c conda-forge imutils
  ```

</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥈27 ·  ⭐ 21K) - OpenMMLab检测工具箱。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/open-mmlab/mmdetection) ⭐ 32,888 | 🐛 1,960 | 🌐 Python | 📅 2024-08-21 (👨‍💻 350 · 🔀 6.9K · 📦 550 · 📋 6.2K - 9% open · ⏱️ 28.07.2022):

  ```
  git clone https://github.com/open-mmlab/mmdetection
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥈27 ·  ⭐ 12K) - 计算机视觉的数据集，转换和模型。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/vision) ⭐ 17,875 | 🐛 1,194 | 🌐 Python | 📅 2026-08-23 (👨‍💻 500 · 🔀 6K · 📥 11K · 📋 2.5K - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytorch/vision
  ```
* [PyPi](https://pypi.org/project/torchvision) (📥 3.9M / month):
  ```
  pip install torchvision
  ```
* [Conda](https://anaconda.org/conda-forge/torchvision) (📥 340K · ⏱️ 24.07.2022):
  ```
  conda install -c conda-forge torchvision
  ```

</details>
<details><summary><b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈27 ·  ⭐ 9.5K) - 一个用于OpenGL，Op​​enGL ES，Vulkan，窗口和输入的多平台库。<code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code></summary>

* [GitHub](https://github.com/glfw/glfw) ⭐ 15,272 | 🐛 760 | 🌐 C | 📅 2026-08-04 (👨‍💻 180 · 🔀 3.5K · 📥 2.9M · 📦 1 · 📋 1.6K - 25% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/glfw/glfw
  ```
* [PyPi](https://pypi.org/project/glfw) (📥 220K / month):
  ```
  pip install glfw
  ```
* [Conda](https://anaconda.org/conda-forge/glfw) (📥 68K · ⏱️ 23.07.2022):
  ```
  conda install -c conda-forge glfw
  ```

</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈26 ·  ⭐ 12K) - MXNet和PyTorch上的人脸分析项目。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepinsight/insightface) ⭐ 29,561 | 🐛 1,266 | 🌐 Python | 📅 2026-07-27 (👨‍💻 46 · 🔀 3.9K · 📦 180 · 📋 2K - 55% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/deepinsight/insightface
  ```
* [PyPi](https://pypi.org/project/insightface) (📥 21K / month):
  ```
  pip install insightface
  ```

</details>
<details><summary><b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈26 ·  ⭐ 7.2K · 💀) - python库旨在使开发人员能够构建应用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/OlafenwaMoses/ImageAI) ⭐ 8,874 | 🐛 321 | 🌐 Python | 📅 2024-08-03 (👨‍💻 15 · 🔀 1.9K · 📥 780K · 📦 1.2K · 📋 690 - 37% open · ⏱️ 08.05.2021):

  ```
  git clone https://github.com/OlafenwaMoses/ImageAI
  ```
* [PyPi](https://pypi.org/project/imageai) (📥 8.9K / month):
  ```
  pip install imageai
  ```

</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈25 ·  ⭐ 46K) - 简单的面部识别API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ageitgey/face_recognition) ⭐ 56,682 | 🐛 832 | 🌐 Python | 📅 2026-06-25 (👨‍💻 54 · 🔀 12K · 📥 470 · 📋 1.2K - 53% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/ageitgey/face_recognition
  ```
* [PyPi](https://pypi.org/project/face_recognition) (📥 39K / month):
  ```
  pip install face_recognition
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈25 ·  ⭐ 22K) - Detectron2是Facebook FAIR的高级目标检测平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/detectron2) ⭐ 34,684 | 🐛 587 | 🌐 Python | 📅 2026-08-19 (👨‍💻 210 · 🔀 5.7K · 📦 710 · 📋 3.1K - 7% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/facebookresearch/detectron2
  ```
* [Conda](https://anaconda.org/conda-forge/detectron2) (📥 78K · ⏱️ 25.04.2022):
  ```
  conda install -c conda-forge detectron2
  ```

</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥈25 ·  ⭐ 11K) - 实现视觉transformer，一种简单的方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lucidrains/vit-pytorch) ⭐ 25,487 | 🐛 142 | 🌐 Python | 📅 2026-08-02 (👨‍💻 15 · 🔀 1.8K · 📦 140 · 📋 190 - 47% open · ⏱️ 27.07.2022):

  ```
  git clone https://github.com/lucidrains/vit-pytorch
  ```
* [PyPi](https://pypi.org/project/vit-pytorch) (📥 19K / month):
  ```
  pip install vit-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥈25 ·  ⭐ 3K · 💤) - 预训练的Pytorch人脸检测（MTCNN）和识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/timesler/facenet-pytorch) ⭐ 5,161 | 🐛 85 | 🌐 Python | 📅 2025-09-16 (👨‍💻 14 · 🔀 650 · 📥 390K · 📦 850 · 📋 150 - 39% open · ⏱️ 13.12.2021):

  ```
  git clone https://github.com/timesler/facenet-pytorch
  ```
* [PyPi](https://pypi.org/project/facenet-pytorch) (📥 18K / month):
  ```
  pip install facenet-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥈25 ·  ⭐ 2.9K · 📈) - 自动化的CI工具链可生成预编译的opencv-python。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/opencv/opencv-python) ⭐ 5,362 | 🐛 196 | 🌐 Python | 📅 2026-08-20 (👨‍💻 39 · 🔀 580 · 📋 570 - 7% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/skvark/opencv-python
  ```
* [PyPi](https://pypi.org/project/opencv-python) (📥 5.6M / month):
  ```
  pip install opencv-python
  ```

</details>
<details><summary><b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥈25 ·  ⭐ 1.5K · 💀) - ChainerCV：一个用于计算机视觉深度学习的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/chainer/chainercv) ⚠️ Archived (👨‍💻 39 · 🔀 300 · 📦 300 · 📋 200 - 18% open · ⏱️ 07.01.2020):

  ```
  git clone https://github.com/chainer/chainercv
  ```
* [PyPi](https://pypi.org/project/chainercv) (📥 3.2K / month):
  ```
  pip install chainercv
  ```

</details>
<details><summary><b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥈25 ·  ⭐ 770) - Python中的计算机视觉。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/luispedro/mahotas) ⭐ 888 | 🐛 24 | 🌐 Python | 📅 2026-06-12 (👨‍💻 32 · 🔀 140 · 📦 870 · 📋 79 - 20% open · ⏱️ 28.06.2022):

  ```
  git clone https://github.com/luispedro/mahotas
  ```
* [PyPi](https://pypi.org/project/mahotas) (📥 11K / month):
  ```
  pip install mahotas
  ```
* [Conda](https://anaconda.org/conda-forge/mahotas) (📥 330K · ⏱️ 28.07.2022):
  ```
  conda install -c conda-forge mahotas
  ```

</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉24 ·  ⭐ 2.4K) - 高性能跨平台视频处理Python框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/abhiTronix/vidgear) ⭐ 3,721 | 🐛 1 | 🌐 Python | 📅 2026-05-18 (👨‍💻 13 · 🔀 190 · 📥 640 · 📦 230 · 📋 230 - 1% open · ⏱️ 06.07.2022):

  ```
  git clone https://github.com/abhiTronix/vidgear
  ```
* [PyPi](https://pypi.org/project/vidgear) (📥 6.5K / month):
  ```
  pip install vidgear
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥉23 ·  ⭐ 6.4K) - PyTorch3D是FAIR的深度学习可重用组件库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/pytorch3d) ⭐ 9,953 | 🐛 313 | 🌐 Python | 📅 2026-08-19 (👨‍💻 96 · 🔀 940 · 📦 270 · 📋 1.1K - 7% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/facebookresearch/pytorch3d
  ```
* [PyPi](https://pypi.org/project/pytorch3d) (📥 14K / month):
  ```
  pip install pytorch3d
  ```
* [Conda](https://anaconda.org/pytorch3d/pytorch3d) (📥 60K · ⏱️ 14.08.2022):
  ```
  conda install -c pytorch3d pytorch3d
  ```

</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉23 ·  ⭐ 5.8K · 💤) - 使用pytorch构建2D和3D人脸对齐库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/1adrianb/face-alignment) ⭐ 7,539 | 🐛 91 | 🌐 Python | 📅 2026-04-06 (👨‍💻 23 · 🔀 1.2K · 📋 280 - 21% open · ⏱️ 04.08.2021):

  ```
  git clone https://github.com/1adrianb/face-alignment
  ```
* [PyPi](https://pypi.org/project/face-alignment) (📥 9.6K / month):
  ```
  pip install face-alignment
  ```

</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉23 ·  ⭐ 4.8K) - Python中的图像增强库，用于机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mdbloice/Augmentor) ⭐ 5,133 | 🐛 139 | 🌐 Python | 📅 2024-03-21 (👨‍💻 22 · 🔀 820 · 📦 480 · 📋 190 - 61% open · ⏱️ 24.05.2022):

  ```
  git clone https://github.com/mdbloice/Augmentor
  ```
* [PyPi](https://pypi.org/project/Augmentor) (📥 16K / month):
  ```
  pip install Augmentor
  ```

</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉23 ·  ⭐ 1.8K · 💀) - TensorFlow的MTCNN人脸检测实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ipazc/mtcnn) ⭐ 2,484 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2024-10-08 (👨‍💻 15 · 🔀 460 · 📦 2.6K · 📋 100 - 62% open · ⏱️ 09.07.2021):

  ```
  git clone https://github.com/ipazc/mtcnn
  ```
* [PyPi](https://pypi.org/project/mtcnn) (📥 23K / month):
  ```
  pip install mtcnn
  ```

</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉23 ·  ⭐ 1.7K) - 一个用于对图像进行自监督学习的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lightly-ai/lightly) ⭐ 3,795 | 🐛 97 | 🌐 Python | 📅 2026-08-21 (👨‍💻 19 · 🔀 140 · 📦 46 · 📋 330 - 20% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/lightly-ai/lightly
  ```
* [PyPi](https://pypi.org/project/lightly) (📥 3.3K / month):
  ```
  pip install lightly
  ```

</details>
<details><summary><b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉22 ·  ⭐ 4.1K · 💀) - 图像查重。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/idealo/imagededup) ⭐ 5,665 | 🐛 38 | 🌐 Python | 📅 2025-08-15 (👨‍💻 10 · 🔀 370 · 📦 26 · 📋 93 - 36% open · ⏱️ 23.11.2020):

  ```
  git clone https://github.com/idealo/imagededup
  ```
* [PyPi](https://pypi.org/project/imagededup) (📥 1.3K / month):
  ```
  pip install imagededup
  ```

</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉22 ·  ⭐ 440) - 使用cffi的libvips的python接口。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/libvips/pyvips) ⭐ 811 | 🐛 2 | 🌐 Python | 📅 2026-07-31 (👨‍💻 14 · 🔀 40 · 📦 350 · 📋 300 - 36% open · ⏱️ 13.08.2022):

  ```
  git clone https://github.com/libvips/pyvips
  ```
* [PyPi](https://pypi.org/project/pyvips) (📥 19K / month):
  ```
  pip install pyvips
  ```
* [Conda](https://anaconda.org/conda-forge/pyvips) (📥 29K · ⏱️ 24.07.2022):
  ```
  conda install -c conda-forge pyvips
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥉21 ·  ⭐ 8.3K) - 对象检测和实例分割工具箱。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/PaddleDetection) ⭐ 14,379 | 🐛 939 | 🌐 Python | 📅 2026-05-28 (👨‍💻 100 · 🔀 2.1K · 📦 30 · 📋 3.8K - 20% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/PaddleDetection
  ```

</details>
<details><summary><b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉21 ·  ⭐ 4K) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/qubvel/segmentation_models) ⭐ 4,923 | 🐛 274 | 🌐 Python | 📅 2024-08-21 (👨‍💻 14 · 🔀 910 · 📋 480 - 46% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/qubvel/segmentation_models
  ```
* [PyPi](https://pypi.org/project/segmentation_models) (📥 26K / month):
  ```
  pip install segmentation_models
  ```

</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉21 ·  ⭐ 3.8K · 💀) - 图像超精度变换。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/idealo/image-super-resolution) ⚠️ Archived (👨‍💻 10 · 🔀 630 · 📦 97 · 📋 200 - 45% open · ⏱️ 02.06.2021):

  ```
  git clone https://github.com/idealo/image-super-resolution
  ```
* [PyPi](https://pypi.org/project/ISR) (📥 4.5K / month):
  ```
  pip install ISR
  ```
* [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 220 · ⏱️ 01.04.2019):
  ```
  docker pull idealo/image-super-resolution-gpu
  ```

</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉21 ·  ⭐ 1.6K) - 轻量级Python库，用于向其中添加实时2D对象跟踪。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/tryolabs/norfair) ⭐ 2,677 | 🐛 31 | 🌐 Python | 📅 2025-04-30 (👨‍💻 18 · 🔀 150 · 📥 200 · 📋 75 - 16% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/tryolabs/norfair
  ```
* [PyPi](https://pypi.org/project/norfair) (📥 7.3K / month):
  ```
  pip install norfair
  ```

</details>
<details><summary><b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉21 ·  ⭐ 700) - 生物图像分析的开源应用程序。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/CellProfiler/CellProfiler) ⭐ 1,133 | 🐛 307 | 🌐 Python | 📅 2026-08-21 (👨‍💻 130 · 🔀 320 · 📥 3.4K · 📦 9 · 📋 3.1K - 5% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/CellProfiler/CellProfiler
  ```
* [PyPi](https://pypi.org/project/cellprofiler) (📥 900 / month):
  ```
  pip install cellprofiler
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉20 ·  ⭐ 5K) - 来自视觉和语言多模态研究的模块化框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/mmf) ⭐ 5,633 | 🐛 150 | 🌐 Python | 📅 2026-07-07 (👨‍💻 100 · 🔀 840 · 📦 12 · 📋 620 - 30% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/facebookresearch/mmf
  ```
* [PyPi](https://pypi.org/project/mmf) (📥 240 / month):
  ```
  pip install mmf
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉20 ·  ⭐ 2.7K) - TensorFlow图神经网络：可微分的图layer<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/graphics) ⭐ 2,781 | 🐛 146 | 🌐 Python | 📅 2026-07-14 (👨‍💻 36 · 🔀 340 · 📋 160 - 45% open · ⏱️ 04.04.2022):

  ```
  git clone https://github.com/tensorflow/graphics
  ```
* [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 2.7K / month):
  ```
  pip install tensorflow-graphics
  ```

</details>
<details><summary><b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉20 ·  ⭐ 860 · 💀) - 使用Python进行裸露检测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/hhatto/nude.py) ⭐ 921 | 🐛 9 | 🌐 Python | 📅 2020-11-23 (👨‍💻 12 · 🔀 130 · 📦 2.6K · 📋 10 - 70% open · ⏱️ 23.11.2020):

  ```
  git clone https://github.com/hhatto/nude.py
  ```
* [PyPi](https://pypi.org/project/nudepy) (📥 9.5K / month):
  ```
  pip install nudepy
  ```

</details>
<details><summary><b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉19 ·  ⭐ 2.4K · 💀) - 用于计算机视觉的深度学习工具包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tryolabs/luminoth) ⭐ 2,402 | 🐛 62 | 🌐 Python | 📅 2023-03-24 (👨‍💻 15 · 🔀 400 · 📥 13K · 📦 41 · 📋 180 - 28% open · ⏱️ 07.01.2020):

  ```
  git clone https://github.com/tryolabs/luminoth
  ```
* [PyPi](https://pypi.org/project/luminoth) (📥 610 / month):
  ```
  pip install luminoth
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉19 ·  ⭐ 1.5K) - 用于图像和视频的端到端PyTorch框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/ClassyVision) ⚠️ Archived (👨‍💻 76 · 🔀 260 · 📋 76 - 17% open · ⏱️ 03.08.2022):

  ```
  git clone https://github.com/facebookresearch/ClassyVision
  ```
* [PyPi](https://pypi.org/project/classy_vision) (📥 2K / month):
  ```
  pip install classy_vision
  ```
* [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 14K · ⏱️ 22.03.2022):
  ```
  conda install -c conda-forge classy_vision
  ```

</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉18 ·  ⭐ 630 · 💤) - 轻量级的计算机视觉库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jasmcaus/caer) ⭐ 814 | 🐛 1 | 🌐 Python | 📅 2026-07-25 (👨‍💻 8 · 🔀 74 · 📥 19 · 📋 15 - 13% open · ⏱️ 13.10.2021):

  ```
  git clone https://github.com/jasmcaus/caer
  ```
* [PyPi](https://pypi.org/project/caer) (📥 3K / month):
  ```
  pip install caer
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉17 ·  ⭐ 9.6K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/detr) ⚠️ Archived (👨‍💻 25 · 🔀 1.7K · 📋 440 - 38% open · ⏱️ 07.03.2022):

  ```
  git clone https://github.com/facebookresearch/detr
  ```

</details>
<details><summary><b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉17 ·  ⭐ 1.9K · 💤) - 友好的PIL fork。<code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

* [GitHub](https://github.com/uploadcare/pillow-simd) ⭐ 2,284 | 🐛 21 | 🌐 Python | 📅 2026-07-06 (👨‍💻 380 · 🔀 74 · 📋 77 - 14% open · ⏱️ 17.01.2022):

  ```
  git clone https://github.com/uploadcare/pillow-simd
  ```
* [PyPi](https://pypi.org/project/pillow-simd) (📥 51K / month):
  ```
  pip install pillow-simd
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉16 ·  ⭐ 5K) - PySlowFast：来自FAIR的视频理解代码库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/SlowFast) ⭐ 7,407 | 🐛 444 | 🌐 Python | 📅 2026-03-16 (👨‍💻 28 · 🔀 960 · 📦 10 · 📋 550 - 52% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/facebookresearch/SlowFast
  ```

</details>
<details><summary><b><a href="https://github.com/ProvenanceLabs/image-match">image-match</a></b> (🥉16 ·  ⭐ 2.8K · 💤) - 快速搜索数十亿张图像。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ProvenanceLabs/image-match) ⭐ 2,978 | 🐛 64 | 🌐 Python | 📅 2022-12-06 (👨‍💻 19 · 🔀 380 · 📋 100 - 53% open · ⏱️ 21.09.2021):

  ```
  git clone https://github.com/EdjoLabs/image-match
  ```
* [PyPi](https://pypi.org/project/image_match) (📥 590 / month):
  ```
  pip install image_match
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉15 ·  ⭐ 2K) - 用PyTorch编写的图像分类研究代码库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/pycls) ⚠️ Archived (👨‍💻 17 · 🔀 230 · 📦 6 · 📋 78 - 28% open · ⏱️ 12.07.2022):

  ```
  git clone https://github.com/facebookresearch/pycls
  ```

</details>
<details><summary><b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉14 ·  ⭐ 93 · 💤) - 用于在点云上进行深度学习的Pytorch框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/nicolas-chaulet/torch-points3d) ⭐ 268 | 🐛 0 | 📅 2021-12-10 (👨‍💻 29 · 🔀 19 · ⏱️ 10.12.2021):

  ```
  git clone https://github.com/nicolas-chaulet/torch-points3d
  ```
* [PyPi](https://pypi.org/project/torch-points3d) (📥 570 / month):
  ```
  pip install torch-points3d
  ```

</details>
<br>

## 图数据处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于图数据处理，聚类，图嵌入和机器学习任务的库。*

<details><summary><b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇32 ·  ⭐ 11K) - Python中的网络分析。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/networkx/networkx) ⭐ 17,217 | 🐛 323 | 🌐 Python | 📅 2026-08-21 (👨‍💻 610 · 🔀 2.6K · 📥 60 · 📦 120K · 📋 2.8K - 5% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/networkx/networkx
  ```
* [PyPi](https://pypi.org/project/networkx) (📥 19M / month):
  ```
  pip install networkx
  ```
* [Conda](https://anaconda.org/conda-forge/networkx) (📥 7.8M · ⏱️ 22.08.2022):
  ```
  conda install -c conda-forge networkx
  ```

</details>
<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇29 ·  ⭐ 10K) - 在现有基础之上构建的Python软件包，用于简化图上的深度学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/dmlc/dgl) ⭐ 14,280 | 🐛 607 | 🌐 Python | 📅 2025-07-31 (👨‍💻 230 · 🔀 2.4K · 📦 30 · 📋 1.7K - 13% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/dmlc/dgl
  ```
* [PyPi](https://pypi.org/project/dgl) (📥 32K / month):
  ```
  pip install dgl
  ```

</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥇28 ·  ⭐ 15K) - PyTorch的几何深度学习扩展库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pyg-team/pytorch_geometric) ⭐ 24,024 | 🐛 1,310 | 🌐 Python | 📅 2026-08-17 (👨‍💻 300 · 🔀 2.7K · 📋 2.6K - 35% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/rusty1s/pytorch_geometric
  ```
* [PyPi](https://pypi.org/project/torch-geometric) (📥 92K / month):
  ```
  pip install torch-geometric
  ```

</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥇28 ·  ⭐ 1.4K) - 用于图机器学习的基准数据集，数据加载器和评估器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/snap-stanford/ogb) ⭐ 2,093 | 🐛 43 | 🌐 Python | 📅 2025-05-06 (👨‍💻 23 · 🔀 310 · 📦 380 · 📋 230 - 0% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/snap-stanford/ogb
  ```
* [PyPi](https://pypi.org/project/ogb) (📥 80K / month):
  ```
  pip install ogb
  ```

</details>
<details><summary><b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥈27 ·  ⭐ 1K) - Igraph的Python接口。<code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code></summary>

* [GitHub](https://github.com/igraph/python-igraph) ⭐ 1,460 | 🐛 68 | 🌐 Python | 📅 2026-05-14 (👨‍💻 61 · 🔀 220 · 📥 460K · 📦 850 · 📋 410 - 9% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/igraph/python-igraph
  ```
* [PyPi](https://pypi.org/project/python-igraph) (📥 260K / month):
  ```
  pip install python-igraph
  ```
* [Conda](https://anaconda.org/conda-forge/igraph) (📥 320K · ⏱️ 13.06.2022):
  ```
  conda install -c conda-forge igraph
  ```

</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈25 ·  ⭐ 2.5K · 💤) - StellarGraph-图机器学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/stellargraph/stellargraph) ⭐ 3,060 | 🐛 326 | 🌐 Python | 📅 2024-04-10 (👨‍💻 36 · 🔀 380 · 📦 160 · 📋 1K - 27% open · ⏱️ 29.10.2021):

  ```
  git clone https://github.com/stellargraph/stellargraph
  ```
* [PyPi](https://pypi.org/project/stellargraph) (📥 22K / month):
  ```
  pip install stellargraph
  ```

</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈25 ·  ⭐ 2.1K) - 使用Keras和Tensorflow 2的图神经网络。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/danielegrattarola/spektral) ⭐ 2,395 | 🐛 74 | 🌐 Python | 📅 2024-01-21 (👨‍💻 24 · 🔀 300 · 📦 140 · 📋 230 - 16% open · ⏱️ 22.07.2022):

  ```
  git clone https://github.com/danielegrattarola/spektral
  ```
* [PyPi](https://pypi.org/project/spektral) (📥 6.8K / month):
  ```
  pip install spektral
  ```

</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈23 ·  ⭐ 1.7K) - 面向API的开源Python框架。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/benedekrozemberczki/karateclub) ⭐ 2,286 | 🐛 12 | 🌐 Python | 📅 2024-07-17 (👨‍💻 15 · 🔀 210 · 📦 100 · ⏱️ 20.08.2022):

  ```
  git clone https://github.com/benedekrozemberczki/karateclub
  ```
* [PyPi](https://pypi.org/project/karateclub) (📥 2.8K / month):
  ```
  pip install karateclub
  ```

</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥈23 ·  ⭐ 1.7K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) ⭐ 2,993 | 🐛 30 | 🌐 Python | 📅 2026-05-30 (👨‍💻 23 · 🔀 250 · 📋 120 - 5% open · ⏱️ 02.08.2022):

  ```
  git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
  ```
* [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 1.8K / month):
  ```
  pip install torch-geometric-temporal
  ```

</details>
<details><summary><b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈22 ·  ⭐ 1.8K · 💀) - 用于知识表示学习的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Accenture/AmpliGraph) ⭐ 2,237 | 🐛 30 | 🌐 Python | 📅 2026-08-06 (👨‍💻 19 · 🔀 210 · 📦 25 · 📋 210 - 12% open · ⏱️ 25.05.2021):

  ```
  git clone https://github.com/Accenture/AmpliGraph
  ```
* [PyPi](https://pypi.org/project/ampligraph) (📥 1.2K / month):
  ```
  pip install ampligraph
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥈22 ·  ⭐ 1.4K) - paddle图机器学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/PGL) ⭐ 1,585 | 🐛 63 | 🌐 Python | 📅 2023-12-11 (👨‍💻 28 · 🔀 270 · 📦 33 · 📋 150 - 35% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/PGL
  ```
* [PyPi](https://pypi.org/project/pgl) (📥 1.8K / month):
  ```
  pip install pgl
  ```

</details>
<details><summary><b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈21 ·  ⭐ 2.5K · 💤) - PYthon svg GrAph绘图库。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

* [GitHub](https://github.com/Kozea/pygal) ⭐ 2,769 | 🐛 200 | 🌐 Python | 📅 2026-07-21 (👨‍💻 71 · 🔀 390 · 📋 400 - 39% open · ⏱️ 24.11.2021):

  ```
  git clone https://github.com/Kozea/pygal
  ```
* [PyPi](https://pypi.org/project/pygal) (📥 120K / month):
  ```
  pip install pygal
  ```
* [Conda](https://anaconda.org/conda-forge/pygal) (📥 20K · ⏱️ 04.06.2019):
  ```
  conda install -c conda-forge pygal
  ```

</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈21 ·  ⭐ 960) - 一个用于学习和评估知识图嵌入的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pykeen/pykeen) ⭐ 2,031 | 🐛 133 | 🌐 Python | 📅 2026-08-22 (👨‍💻 31 · 🔀 130 · 📥 140 · 📋 420 - 13% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pykeen/pykeen
  ```
* [PyPi](https://pypi.org/project/pykeen) (📥 1.4K / month):
  ```
  pip install pykeen
  ```

</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥈21 ·  ⭐ 950) - node2vec算法的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/eliorc/node2vec) ⭐ 1,301 | 🐛 0 | 🌐 Python | 📅 2025-10-06 (👨‍💻 11 · 🔀 200 · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/eliorc/node2vec
  ```
* [PyPi](https://pypi.org/project/node2vec) (📥 78K / month):
  ```
  pip install node2vec
  ```
* [Conda](https://anaconda.org/conda-forge/node2vec) (📥 22K · ⏱️ 25.04.2020):
  ```
  conda install -c conda-forge node2vec
  ```

</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥈21 ·  ⭐ 560) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rusty1s/pytorch_cluster) ⭐ 928 | 🐛 21 | 🌐 C++ | 📅 2026-06-05 (👨‍💻 25 · 🔀 100 · 📋 110 - 17% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/rusty1s/pytorch_cluster
  ```
* [PyPi](https://pypi.org/project/torch-cluster) (📥 27K / month):
  ```
  pip install torch-cluster
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉19 ·  ⭐ 3.1K) - 从大型图网络结构生成embedding嵌入。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/PyTorch-BigGraph) ⚠️ Archived (👨‍💻 27 · 🔀 410 · 📥 140 · 📋 190 - 26% open · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/facebookresearch/PyTorch-BigGraph
  ```
* [PyPi](https://pypi.org/project/torchbiggraph) (📥 320K / month):
  ```
  pip install torchbiggraph
  ```

</details>
<details><summary><b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉19 ·  ⭐ 2.5K · 💀) - DeepWalk-图的深度学习。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/phanein/deepwalk) ⭐ 2,759 | 🐛 46 | 🌐 Python | 📅 2023-06-14 (👨‍💻 10 · 🔀 810 · 📦 56 · 📋 110 - 24% open · ⏱️ 02.04.2020):

  ```
  git clone https://github.com/phanein/deepwalk
  ```
* [PyPi](https://pypi.org/project/deepwalk) (📥 3.1K / month):
  ```
  pip install deepwalk
  ```

</details>
<details><summary><b><a href="https://github.com/vaticle/typedb-ml">kglib</a></b> (🥉17 ·  ⭐ 520) - Grakn知识图库（ML R＆D）。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/vaticle/typedb-ml) ⚠️ Archived (👨‍💻 9 · 🔀 88 · 📥 210 · 📋 60 - 16% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/graknlabs/kglib
  ```
* [PyPi](https://pypi.org/project/grakn-kglib) (📥 26 / month):
  ```
  pip install grakn-kglib
  ```

</details>
<details><summary><b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 3K) - 图嵌入算法的实现和实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/shenweichen/GraphEmbedding) ⭐ 3,845 | 🐛 37 | 🌐 Python | 📅 2026-04-26 (👨‍💻 9 · 🔀 860 · 📦 21 · 📋 57 - 59% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/shenweichen/GraphEmbedding
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉15 ·  ⭐ 5.2K · 💀) - 在Tensorflow中构建图神经网络。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepmind/graph_nets) ⭐ 5,406 | 🐛 9 | 🌐 Python | 📅 2022-12-12 (👨‍💻 10 · 🔀 770 · 📋 120 - 2% open · ⏱️ 04.12.2020):

  ```
  git clone https://github.com/deepmind/graph_nets
  ```
* [PyPi](https://pypi.org/project/graph-nets) (📥 1K / month):
  ```
  pip install graph-nets
  ```

</details>
<details><summary><b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉15 ·  ⭐ 2.8K · 💀) - 分布式图深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/alibaba/euler) ⭐ 2,897 | 🐛 222 | 🌐 C++ | 📅 2023-08-19 (👨‍💻 3 · 🔀 550 · 📋 320 - 67% open · ⏱️ 29.07.2020):

  ```
  git clone https://github.com/alibaba/euler
  ```
* [PyPi](https://pypi.org/project/euler-gl) (📥 15 / month):
  ```
  pip install euler-gl
  ```

</details>
<details><summary><b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉15 ·  ⭐ 260 · 💀) - 使用基于pandas的网络分析数据。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepgraph/deepgraph) ⭐ 349 | 🐛 4 | 🌐 Python | 📅 2026-03-10 (👨‍💻 2 · 🔀 38 · 📦 5 · 📋 14 - 64% open · ⏱️ 14.06.2021):

  ```
  git clone https://github.com/deepgraph/deepgraph
  ```
* [PyPi](https://pypi.org/project/deepgraph) (📥 290 / month):
  ```
  pip install deepgraph
  ```
* [Conda](https://anaconda.org/conda-forge/deepgraph) (📥 130K · ⏱️ 19.04.2022):
  ```
  conda install -c conda-forge deepgraph
  ```

</details>
<details><summary><b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉15 ·  ⭐ 160) - RDF2Vec的Python实现和扩展。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/IBCNServices/pyRDF2Vec) ⭐ 268 | 🐛 25 | 🌐 Python | 📅 2026-08-10 (👨‍💻 6 · 🔀 32 · 📋 61 - 14% open · ⏱️ 06.05.2022):

  ```
  git clone https://github.com/IBCNServices/pyRDF2Vec
  ```
* [PyPi](https://pypi.org/project/pyrdf2vec) (📥 300 / month):
  ```
  pip install pyrdf2vec
  ```

</details>
<details><summary><b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉14 ·  ⭐ 2.8K · 💀) - 大型图上的表示学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/williamleif/GraphSAGE) ⭐ 3,719 | 🐛 122 | 🌐 Python | 📅 2024-08-04 (👨‍💻 9 · 🔀 770 · 📋 160 - 62% open · ⏱️ 19.09.2018):

  ```
  git clone https://github.com/williamleif/GraphSAGE
  ```

</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉14 ·  ⭐ 1.6K · 💀) - 神经关系提取（NRE）的开源软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/thunlp/OpenNE) ⭐ 1,706 | 🐛 10 | 🌐 Python | 📅 2024-01-10 (👨‍💻 10 · 🔀 480 · 📋 97 - 1% open · ⏱️ 12.08.2019):

  ```
  git clone https://github.com/thunlp/OpenNE
  ```

</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉14 ·  ⭐ 840) - 用于图上机器学习的autoML框架和工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/THUMNLab/AutoGL) ⭐ 1,140 | 🐛 22 | 🌐 Python | 📅 2025-11-20 (👨‍💻 13 · 🔀 98 · 📋 23 - 34% open · ⏱️ 19.04.2022):

  ```
  git clone https://github.com/THUMNLab/AutoGL
  ```
* [PyPi](https://pypi.org/project/auto-graph-learning):
  ```
  pip install auto-graph-learning
  ```

</details>
<details><summary><b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉14 ·  ⭐ 400 · 💀) - 知识图的语义相似性框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/gsi-upm/sematch) ⭐ 441 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2023-11-07 (👨‍💻 5 · 🔀 100 · 📦 34 · 📋 33 - 42% open · ⏱️ 27.03.2019):

  ```
  git clone https://github.com/gsi-upm/sematch
  ```
* [PyPi](https://pypi.org/project/sematch) (📥 130 / month):
  ```
  pip install sematch
  ```

</details>
<details><summary><b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉12 ·  ⭐ 1.1K · 💀) - GraphVite：通用的高性能图形嵌入系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/DeepGraphLearning/graphvite) ⭐ 1,269 | 🐛 56 | 🌐 C++ | 📅 2024-06-14 (🔀 140 · 📋 100 - 42% open · ⏱️ 14.01.2021):

  ```
  git clone https://github.com/DeepGraphLearning/graphvite
  ```
* [Conda](https://anaconda.org/milagraph/graphvite) (📥 4.4K · ⏱️ 19.03.2020):
  ```
  conda install -c milagraph graphvite
  ```

</details>
<details><summary><b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉11 ·  ⭐ 3.2K · 💀) - 神经关系提取（NRE）的开源软件包。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/thunlp/OpenKE) ⭐ 4,044 | 🐛 32 | 🌐 Python | 📅 2024-01-10 (👨‍💻 10 · 🔀 900 · 📋 350 - 1% open · ⏱️ 06.04.2021):

  ```
  git clone https://github.com/thunlp/OpenKE
  ```

</details>
<br>

## 音频处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于音频分析，处理，转换和提取以及语音识别和音乐生成任务的库。*

<details><summary><b><a href="https://github.com/mozilla/DeepSpeech">DeepSpeech</a></b> (🥇30 ·  ⭐ 20K · 💤) - DeepSpeech是开源的语音转文本引擎。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/mozilla/DeepSpeech) ⚠️ Archived (👨‍💻 160 · 🔀 3.4K · 📥 880K · 📦 800 · 📋 2.1K - 5% open · ⏱️ 17.11.2021):

  ```
  git clone https://github.com/mozilla/DeepSpeech
  ```
* [PyPi](https://pypi.org/project/deepspeech) (📥 9.4K / month):
  ```
  pip install deepspeech
  ```

</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥇30 ·  ⭐ 6.3K) - 使用简单易用的高级界面处理音频。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jiaaro/pydub) ⭐ 9,792 | 🐛 421 | 🌐 Python | 📅 2026-03-19 (👨‍💻 92 · 🔀 840 · 📦 14K · 📋 490 - 46% open · ⏱️ 14.05.2022):

  ```
  git clone https://github.com/jiaaro/pydub
  ```
* [PyPi](https://pypi.org/project/pydub) (📥 1.6M / month):
  ```
  pip install pydub
  ```
* [Conda](https://anaconda.org/conda-forge/pydub) (📥 28K · ⏱️ 13.03.2021):
  ```
  conda install -c conda-forge pydub
  ```

</details>
<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇29 ·  ⭐ 5.4K) - 端到端语音处理工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/espnet/espnet) ⭐ 9,933 | 🐛 57 | 🌐 Python | 📅 2026-08-17 (👨‍💻 280 · 🔀 1.6K · 📥 76 · 📦 67 · 📋 1.9K - 15% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/espnet/espnet
  ```
* [PyPi](https://pypi.org/project/espnet) (📥 11K / month):
  ```
  pip install espnet
  ```

</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥈27 ·  ⭐ 18K) - 借助机器智能进行音乐和艺术创作。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/magenta/magenta) ⚠️ Archived (👨‍💻 150 · 🔀 3.5K · 📦 380 · 📋 890 - 34% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/magenta/magenta
  ```
* [PyPi](https://pypi.org/project/magenta) (📥 3.9K / month):
  ```
  pip install magenta
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥈27 ·  ⭐ 1.8K) - 音频信号的数据处理和转换。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/audio) ⭐ 2,926 | 🐛 339 | 🌐 Python | 📅 2026-08-23 (👨‍💻 170 · 🔀 450 · 📋 640 - 20% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/pytorch/audio
  ```
* [PyPi](https://pypi.org/project/torchaudio) (📥 730K / month):
  ```
  pip install torchaudio
  ```

</details>
<details><summary><b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈26 ·  ⭐ 2.8K · 💤) - 用于音频和音乐分析的库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/aubio/aubio) ⭐ 3,754 | 🐛 157 | 🌐 C | 📅 2026-04-10 (👨‍💻 24 · 🔀 340 · 📦 310 · 📋 310 - 41% open · ⏱️ 25.01.2022):

  ```
  git clone https://github.com/aubio/aubio
  ```
* [PyPi](https://pypi.org/project/aubio) (📥 1.5K / month):
  ```
  pip install aubio
  ```
* [Conda](https://anaconda.org/conda-forge/aubio) (📥 540K · ⏱️ 13.07.2022):
  ```
  conda install -c conda-forge aubio
  ```

</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥈24 ·  ⭐ 20K) - Deezer源分离库，包括预训练的模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deezer/spleeter) ⭐ 28,400 | 🐛 278 | 🌐 Python | 📅 2026-06-18 (👨‍💻 19 · 🔀 2.2K · 📥 1.8M · 📋 680 - 21% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/deezer/spleeter
  ```
* [PyPi](https://pypi.org/project/spleeter) (📥 10K / month):
  ```
  pip install spleeter
  ```
* [Conda](https://anaconda.org/conda-forge/spleeter) (📥 68K · ⏱️ 30.06.2020):
  ```
  conda install -c conda-forge spleeter
  ```

</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈24 ·  ⭐ 6.5K) - 适用于Python的语音识别模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Uberi/speech_recognition) ⭐ 8,986 | 🐛 311 | 🌐 Python | 📅 2026-07-31 (👨‍💻 47 · 🔀 2K · 📋 510 - 44% open · ⏱️ 02.08.2022):

  ```
  git clone https://github.com/Uberi/speech_recognition
  ```
* [PyPi](https://pypi.org/project/SpeechRecognition) (📥 330K / month):
  ```
  pip install SpeechRecognition
  ```
* [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 140K · ⏱️ 13.12.2021):
  ```
  conda install -c conda-forge speechrecognition
  ```

</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥈24 ·  ⭐ 4.9K) - Python音频分析库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/tyiannak/pyAudioAnalysis) ⭐ 6,254 | 🐛 205 | 🌐 Python | 📅 2025-08-04 (👨‍💻 26 · 🔀 1.1K · 📦 290 · 📋 290 - 59% open · ⏱️ 19.04.2022):

  ```
  git clone https://github.com/tyiannak/pyAudioAnalysis
  ```
* [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 21K / month):
  ```
  pip install pyAudioAnalysis
  ```

</details>
<details><summary><b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥈24 ·  ⭐ 2.2K) - C++库，用于音频和音乐分析，描述等。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/MTG/essentia) ⭐ 3,699 | 🐛 425 | 🌐 C++ | 📅 2026-07-22 (👨‍💻 74 · 🔀 460 · 📦 320 · 📋 950 - 36% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/MTG/essentia
  ```
* [PyPi](https://pypi.org/project/essentia) (📥 3.9K / month):
  ```
  pip install essentia
  ```

</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥉23 ·  ⭐ 5.4K) - 用于音频和音乐分析的Python库。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

* [GitHub](https://github.com/librosa/librosa) ⭐ 8,571 | 🐛 51 | 🌐 Python | 📅 2026-08-22 (👨‍💻 110 · 🔀 810 · 📋 1K - 4% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/librosa/librosa
  ```
* [PyPi](https://pypi.org/project/librosa) (📥 1.2M / month):
  ```
  pip install librosa
  ```
* [Conda](https://anaconda.org/conda-forge/librosa) (📥 510K · ⏱️ 27.06.2022):
  ```
  conda install -c conda-forge librosa
  ```

</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉23 ·  ⭐ 560) - 读取音乐元数据和MP3，OGG，OPUS，MP4，M4A，FLAC，WMA等的长度。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/devsnd/tinytag) ⭐ 832 | 🐛 6 | 🌐 Python | 📅 2026-08-23 (👨‍💻 22 · 🔀 88 · 📦 580 · 📋 93 - 12% open · ⏱️ 13.08.2022):

  ```
  git clone https://github.com/devsnd/tinytag
  ```
* [PyPi](https://pypi.org/project/tinytag) (📥 85K / month):
  ```
  pip install tinytag
  ```

</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉22 ·  ⭐ 850) - kapre：Keras音频预处理器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/keunwoochoi/kapre) ⭐ 947 | 🐛 16 | 🌐 Python | 📅 2026-05-17 (👨‍💻 13 · 🔀 140 · 📥 22 · 📦 1.8K · 📋 94 - 12% open · ⏱️ 04.07.2022):

  ```
  git clone https://github.com/keunwoochoi/kapre
  ```
* [PyPi](https://pypi.org/project/kapre) (📥 3.6K / month):
  ```
  pip install kapre
  ```

</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉21 ·  ⭐ 2.8K) - 深度学习支持的设备上唤醒词识别。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Picovoice/porcupine) ⭐ 4,916 | 🐛 0 | 🌐 Python | 📅 2026-08-12 (👨‍💻 31 · 🔀 380 · 📦 9 · 📋 390 - 0% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/Picovoice/Porcupine
  ```
* [PyPi](https://pypi.org/project/pvporcupine) (📥 1.2K / month):
  ```
  pip install pvporcupine
  ```

</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉21 ·  ⭐ 2.2K) - DDSP：微分数字信号处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/magenta/ddsp) ⭐ 3,342 | 🐛 54 | 🌐 Python | 📅 2026-07-09 (👨‍💻 31 · 🔀 250 · 📦 28 · 📋 140 - 18% open · ⏱️ 16.05.2022):

  ```
  git clone https://github.com/magenta/ddsp
  ```
* [PyPi](https://pypi.org/project/ddsp) (📥 3K / month):
  ```
  pip install ddsp
  ```

</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉21 ·  ⭐ 470) - SoundFile是基于libsndfile，CFFI等的音频库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/bastibe/python-soundfile) ⭐ 848 | 🐛 135 | 🌐 Python | 📅 2026-07-14 (👨‍💻 24 · 🔀 75 · 📥 4K · 📋 170 - 39% open · ⏱️ 23.02.2022):

  ```
  git clone https://github.com/bastibe/python-soundfile
  ```
* [PyPi](https://pypi.org/project/soundfile) (📥 1.1M / month):
  ```
  pip install soundfile
  ```

</details>
<details><summary><b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉20 ·  ⭐ 2.1K · 💀) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jameslyons/python_speech_features) ⭐ 2,423 | 🐛 25 | 🌐 Python | 📅 2021-10-20 (👨‍💻 19 · 🔀 590 · 📋 71 - 28% open · ⏱️ 31.12.2020):

  ```
  git clone https://github.com/jameslyons/python_speech_features
  ```
* [PyPi](https://pypi.org/project/python_speech_features) (📥 150K / month):
  ```
  pip install python_speech_features
  ```

</details>
<details><summary><b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉19 ·  ⭐ 6.2K · 💀) - 文本到语音的深度学习。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

* [GitHub](https://github.com/mozilla/TTS) ⭐ 10,168 | 🐛 37 | 🌐 Jupyter Notebook | 📅 2023-11-09 (👨‍💻 56 · 🔀 930 · 📥 2.6K · 📋 540 - 0% open · ⏱️ 12.02.2021):

  ```
  git clone https://github.com/mozilla/TTS
  ```

</details>
<details><summary><b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉19 ·  ⭐ 5.8K · 💀) - Python中的音频指纹识别。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/worldveil/dejavu) ⭐ 6,782 | 🐛 132 | 🌐 Python | 📅 2024-04-22 (👨‍💻 22 · 🔀 1.3K · 📦 23 · 📋 210 - 39% open · ⏱️ 03.06.2020):

  ```
  git clone https://github.com/worldveil/dejavu
  ```
* [PyPi](https://pypi.org/project/PyDejavu) (📥 67 / month):
  ```
  pip install PyDejavu
  ```

</details>
<details><summary><b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉19 ·  ⭐ 950 · 💤) - Python音频和音乐信号处理库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/CPJKU/madmom) ⭐ 1,696 | 🐛 81 | 🌐 Python | 📅 2026-03-20 (👨‍💻 20 · 🔀 150 · 📦 210 · 📋 240 - 16% open · ⏱️ 06.01.2022):

  ```
  git clone https://github.com/CPJKU/madmom
  ```
* [PyPi](https://pypi.org/project/madmom) (📥 1.7K / month):
  ```
  pip install madmom
  ```

</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥉19 ·  ⭐ 410 · 📉) - 跨库（GStreamer + Core Audio + MAD + FFmpeg）音频编解码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/beetbox/audioread) ⭐ 538 | 🐛 45 | 🌐 Python | 📅 2026-04-09 (👨‍💻 22 · 🔀 94 · 📋 80 - 38% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/beetbox/audioread
  ```
* [PyPi](https://pypi.org/project/audioread) (📥 1.2M / month):
  ```
  pip install audioread
  ```
* [Conda](https://anaconda.org/conda-forge/audioread) (📥 480K · ⏱️ 14.08.2022):
  ```
  conda install -c conda-forge audioread
  ```

</details>
<details><summary><b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉17 ·  ⭐ 210 · 💀) - 用于扩充带注释的音频数据的库。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

* [GitHub](https://github.com/bmcfee/muda) ⭐ 238 | 🐛 9 | 🌐 Python | 📅 2021-05-03 (👨‍💻 7 · 🔀 32 · 📦 15 · 📋 50 - 12% open · ⏱️ 03.05.2021):

  ```
  git clone https://github.com/bmcfee/muda
  ```
* [PyPi](https://pypi.org/project/muda) (📥 110 / month):
  ```
  pip install muda
  ```

</details>
<details><summary><b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉15 ·  ⭐ 280 · 💤) - 基于PyTorch的快速DSP，用于音频和一维信号。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/adefossez/julius) ⭐ 462 | 🐛 1 | 🌐 Python | 📅 2026-06-03 (👨‍💻 2 · 🔀 18 · 📦 120 · ⏱️ 28.01.2022):

  ```
  git clone https://github.com/adefossez/julius
  ```
* [PyPi](https://pypi.org/project/julius) (📥 24K / month):
  ```
  pip install julius
  ```

</details>
<br>

## 地理Geo处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于加载，处理，分析和写入geo地理数据的库，以及用于空间分析，地图可视化和地理编码的库。*

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇35 ·  ⭐ 10K) - WebGL2支持的地理空间可视化图层。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/visgl/deck.gl) ⭐ 14,510 | 🐛 478 | 🌐 TypeScript | 📅 2026-08-23 (👨‍💻 200 · 🔀 1.7K · 📦 4.5K · 📋 2.5K - 5% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/visgl/deck.gl
  ```
* [PyPi](https://pypi.org/project/pydeck) (📥 790K / month):
  ```
  pip install pydeck
  ```
* [Conda](https://anaconda.org/conda-forge/pydeck) (📥 170K · ⏱️ 26.10.2021):
  ```
  conda install -c conda-forge pydeck
  ```
* [NPM](https://www.npmjs.com/package/deck.gl) (📥 320K / month):
  ```
  npm install deck.gl
  ```

</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥇32 ·  ⭐ 3.7K) - 适用于Python的地址解析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/geopy/geopy) ⭐ 4,852 | 🐛 53 | 🌐 Python | 📅 2026-07-12 (👨‍💻 130 · 🔀 580 · 📦 41K · 📋 260 - 7% open · ⏱️ 07.08.2022):

  ```
  git clone https://github.com/geopy/geopy
  ```
* [PyPi](https://pypi.org/project/geopy) (📥 5M / month):
  ```
  pip install geopy
  ```
* [Conda](https://anaconda.org/conda-forge/geopy) (📥 780K · ⏱️ 12.07.2021):
  ```
  conda install -c conda-forge geopy
  ```

</details>
<details><summary><b><a href="https://github.com/shapely/shapely">Shapely</a></b> (🥇31 ·  ⭐ 2.9K) - 操作和分析几何对象。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/shapely/shapely) ⭐ 4,491 | 🐛 236 | 🌐 Python | 📅 2026-08-20 (👨‍💻 130 · 🔀 460 · 📥 220 · 📦 32K · 📋 910 - 17% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/Toblerity/Shapely
  ```
* [PyPi](https://pypi.org/project/shapely) (📥 8M / month):
  ```
  pip install shapely
  ```
* [Conda](https://anaconda.org/conda-forge/shapely) (📥 4.3M · ⏱️ 18.08.2022):
  ```
  conda install -c conda-forge shapely
  ```

</details>
<details><summary><b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥇31 ·  ⭐ 1.5K · 💀) - Python Geocoder。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/DenisCarriere/geocoder) ⭐ 1,656 | 🐛 123 | 🌐 Python | 📅 2024-04-20 (👨‍💻 73 · 🔀 260 · 📦 5.3K · 📋 290 - 25% open · ⏱️ 12.10.2018):

  ```
  git clone https://github.com/DenisCarriere/geocoder
  ```
* [PyPi](https://pypi.org/project/geocoder) (📥 580K / month):
  ```
  pip install geocoder
  ```
* [Conda](https://anaconda.org/conda-forge/geocoder) (📥 110K · ⏱️ 27.06.2019):
  ```
  conda install -c conda-forge geocoder
  ```

</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥈30 ·  ⭐ 3.3K) - 用于地理数据的Python工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/geopandas/geopandas) ⭐ 5,226 | 🐛 431 | 🌐 Python | 📅 2026-08-12 (👨‍💻 180 · 🔀 700 · 📥 1.6K · 📦 15K · 📋 1.3K - 26% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/geopandas/geopandas
  ```
* [PyPi](https://pypi.org/project/geopandas) (📥 2.9M / month):
  ```
  pip install geopandas
  ```
* [Conda](https://anaconda.org/conda-forge/geopandas) (📥 1.9M · ⏱️ 24.07.2022):
  ```
  conda install -c conda-forge geopandas
  ```

</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈30 ·  ⭐ 1.3K) - Jupyter-Leaflet.js桥。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jupyter-widgets/ipyleaflet) ⭐ 1,538 | 🐛 300 | 🌐 TypeScript | 📅 2026-05-07 (👨‍💻 80 · 🔀 320 · 📦 2.6K · 📋 500 - 36% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/jupyter-widgets/ipyleaflet
  ```
* [PyPi](https://pypi.org/project/ipyleaflet) (📥 110K / month):
  ```
  pip install ipyleaflet
  ```
* [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 870K · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge ipyleaflet
  ```
* [NPM](https://www.npmjs.com/package/jupyter-leaflet) (📥 50K / month):
  ```
  npm install jupyter-leaflet
  ```

</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈30 ·  ⭐ 940) - Fiona读写地理数据文件。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/Toblerity/Fiona) ⭐ 1,248 | 🐛 57 | 🌐 Python | 📅 2025-02-20 (👨‍💻 66 · 🔀 170 · 📦 9.4K · 📋 680 - 10% open · ⏱️ 01.03.2022):

  ```
  git clone https://github.com/Toblerity/Fiona
  ```
* [PyPi](https://pypi.org/project/fiona) (📥 3.1M / month):
  ```
  pip install fiona
  ```
* [Conda](https://anaconda.org/conda-forge/fiona) (📥 3.3M · ⏱️ 30.05.2022):
  ```
  conda install -c conda-forge fiona
  ```

</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈29 ·  ⭐ 780) - 与PROJ的Python界面（图形投影和坐标。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pyproj4/pyproj) ⭐ 1,220 | 🐛 58 | 🌐 Python | 📅 2026-08-21 (👨‍💻 52 · 🔀 180 · 📦 16K · 📋 500 - 1% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/pyproj4/pyproj
  ```
* [PyPi](https://pypi.org/project/pyproj) (📥 5M / month):
  ```
  pip install pyproj
  ```
* [Conda](https://anaconda.org/conda-forge/pyproj) (📥 4M · ⏱️ 17.06.2022):
  ```
  conda install -c conda-forge pyproj
  ```

</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥈28 ·  ⭐ 5.9K) - Leaflet.js地图的Python数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/python-visualization/folium) ⭐ 7,393 | 🐛 70 | 🌐 Python | 📅 2026-08-23 (👨‍💻 130 · 🔀 2.1K · 📦 18K · 📋 940 - 22% open · ⏱️ 06.05.2022):

  ```
  git clone https://github.com/python-visualization/folium
  ```
* [PyPi](https://pypi.org/project/folium) (📥 820K / month):
  ```
  pip install folium
  ```
* [Conda](https://anaconda.org/conda-forge/folium) (📥 1.1M · ⏱️ 03.12.2021):
  ```
  conda install -c conda-forge folium
  ```

</details>
<details><summary><b><a href="https://github.com/rasterio/rasterio">Rasterio</a></b> (🥉27 ·  ⭐ 1.8K) - Rasterio读写地理空间栅格数据集。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/rasterio/rasterio) ⭐ 2,564 | 🐛 156 | 🌐 Python | 📅 2026-08-20 (👨‍💻 130 · 🔀 470 · 📥 760 · 📦 5.4K · 📋 1.6K - 8% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/mapbox/rasterio
  ```
* [PyPi](https://pypi.org/project/rasterio) (📥 600K / month):
  ```
  pip install rasterio
  ```
* [Conda](https://anaconda.org/conda-forge/rasterio) (📥 1.7M · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge rasterio
  ```

</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉27 ·  ⭐ 740) - GeoJSON的Python接口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/jazzband/geojson) ⭐ 993 | 🐛 24 | 🌐 Python | 📅 2026-06-06 (👨‍💻 48 · 🔀 93 · 📦 10K · 📋 85 - 25% open · ⏱️ 07.05.2022):

  ```
  git clone https://github.com/jazzband/geojson
  ```
* [PyPi](https://pypi.org/project/geojson) (📥 780K / month):
  ```
  pip install geojson
  ```
* [Conda](https://anaconda.org/conda-forge/geojson) (📥 560K · ⏱️ 11.08.2019):
  ```
  conda install -c conda-forge geojson
  ```

</details>
<details><summary><b><a href="https://github.com/rasterio/rasterio">Cartopy</a></b> (🥉26 ·  ⭐ 1.8K) - Rasterio读写地理空间栅格数据集。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/rasterio/rasterio) ⭐ 2,564 | 🐛 156 | 🌐 Python | 📅 2026-08-20 (👨‍💻 130 · 🔀 470 · 📥 760 · 📦 5.4K · 📋 1.6K - 8% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/mapbox/rasterio
  ```
* [PyPi](https://pypi.org/project/Cartopy) (📥 120K / month):
  ```
  pip install Cartopy
  ```
* [Conda](https://anaconda.org/conda-forge/cartopy) (📥 2.3M · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge cartopy
  ```

</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉25 ·  ⭐ 430) - 使用Python进行简单，简洁的地理可视化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/holoviz/geoviews) ⭐ 633 | 🐛 116 | 🌐 Python | 📅 2026-08-21 (👨‍💻 28 · 🔀 66 · 📦 470 · 📋 300 - 34% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/holoviz/geoviews
  ```
* [PyPi](https://pypi.org/project/geoviews) (📥 7.7K / month):
  ```
  pip install geoviews
  ```
* [Conda](https://anaconda.org/conda-forge/geoviews) (📥 120K · ⏱️ 08.03.2022):
  ```
  conda install -c conda-forge geoviews
  ```

</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉24 ·  ⭐ 1.4K) - ArcGIS API for Python的文档和示例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Esri/arcgis-python-api) ⭐ 2,190 | 🐛 81 | 🌐 Python | 📅 2026-08-06 (👨‍💻 81 · 🔀 910 · 📥 5.2K · 📋 470 - 8% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/Esri/arcgis-python-api
  ```
* [PyPi](https://pypi.org/project/arcgis) (📥 45K / month):
  ```
  pip install arcgis
  ```
* [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 7.2K · ⭐ 35 · ⏱️ 17.06.2022):
  ```
  docker pull esridocker/arcgis-api-python-notebook
  ```

</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉23 ·  ⭐ 1.1K) - PySAL：Python空间分析库元包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/pysal/pysal) ⭐ 1,521 | 🐛 24 | 🌐 Python | 📅 2026-08-03 (👨‍💻 77 · 🔀 260 · 📋 610 - 1% open · ⏱️ 23.07.2022):

  ```
  git clone https://github.com/pysal/pysal
  ```
* [PyPi](https://pypi.org/project/pysal) (📥 30K / month):
  ```
  pip install pysal
  ```
* [Conda](https://anaconda.org/conda-forge/pysal) (📥 450K · ⏱️ 01.08.2022):
  ```
  conda install -c conda-forge pysal
  ```

</details>
<details><summary><b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉22 ·  ⭐ 790) - 搜索和下载哥白尼前哨卫星图像。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/sentinelsat/sentinelsat) ⚠️ Archived (👨‍💻 42 · 🔀 200 · 📥 230 · 📦 350 · 📋 330 - 2% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/sentinelsat/sentinelsat
  ```
* [PyPi](https://pypi.org/project/sentinelsat) (📥 13K / month):
  ```
  pip install sentinelsat
  ```

</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉22 ·  ⭐ 620 · 💀) - 使用Mapbox GL JS可视化Python Jupyter笔记本中的数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/mapbox/mapboxgl-jupyter) ⭐ 679 | 🐛 43 | 🌐 Python | 📅 2025-02-06 (👨‍💻 21 · 🔀 130 · 📦 140 · 📋 99 - 32% open · ⏱️ 19.04.2021):

  ```
  git clone https://github.com/mapbox/mapboxgl-jupyter
  ```
* [PyPi](https://pypi.org/project/mapboxgl) (📥 11K / month):
  ```
  pip install mapboxgl
  ```

</details>
<details><summary><b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉21 ·  ⭐ 850) - 用于地球观测卫星数据处理的Python软件包。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/pytroll/satpy) ⭐ 1,204 | 🐛 561 | 🌐 Python | 📅 2026-08-21 (👨‍💻 130 · 🔀 240 · 📦 72 · 📋 790 - 38% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytroll/satpy
  ```
* [PyPi](https://pypi.org/project/satpy) (📥 1.1K / month):
  ```
  pip install satpy
  ```
* [Conda](https://anaconda.org/conda-forge/satpy) (📥 100K · ⏱️ 15.08.2022):
  ```
  conda install -c conda-forge satpy
  ```

</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉21 ·  ⭐ 380 · 💤) - 使用开放源代码处理空间数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/earthlab/earthpy) ⭐ 536 | 🐛 44 | 🌐 Python | 📅 2026-08-16 (👨‍💻 40 · 🔀 140 · 📦 160 · 📋 230 - 8% open · ⏱️ 20.12.2021):

  ```
  git clone https://github.com/earthlab/earthpy
  ```
* [PyPi](https://pypi.org/project/earthpy) (📥 8.4K / month):
  ```
  pip install earthpy
  ```
* [Conda](https://anaconda.org/conda-forge/earthpy) (📥 49K · ⏱️ 04.10.2021):
  ```
  conda install -c conda-forge earthpy
  ```

</details>
<details><summary><b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉19 ·  ⭐ 970 · 💀) - python工具箱，用于可视化地理数据和制作地图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/andrea-cuttone/geoplotlib) ⭐ 1,037 | 🐛 34 | 🌐 Python | 📅 2022-06-13 (👨‍💻 8 · 🔀 160 · 📦 150 · 📋 44 - 56% open · ⏱️ 06.05.2019):

  ```
  git clone https://github.com/andrea-cuttone/geoplotlib
  ```
* [PyPi](https://pypi.org/project/geoplotlib) (📥 880 / month):
  ```
  pip install geoplotlib
  ```

</details>
<details><summary><b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉18 ·  ⭐ 740 · 💀) - Google为Jupyter笔记本电脑映射。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pbugnion/gmaps) ⭐ 766 | 🐛 80 | 🌐 Python | 📅 2026-04-13 (👨‍💻 16 · 🔀 140 · 📦 1 · 📋 200 - 32% open · ⏱️ 22.07.2019):

  ```
  git clone https://github.com/pbugnion/gmaps
  ```
* [PyPi](https://pypi.org/project/gmaps) (📥 9K / month):
  ```
  pip install gmaps
  ```
* [Conda](https://anaconda.org/conda-forge/gmaps) (📥 270K · ⏱️ 02.08.2019):
  ```
  conda install -c conda-forge gmaps
  ```
* [NPM](https://www.npmjs.com/package/jupyter-gmaps) (📥 1.8K / month):
  ```
  npm install jupyter-gmaps
  ```

</details>
<details><summary><b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉18 ·  ⭐ 270) - 纯Python实现（Numpy可选）的3D坐标转换。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/geospace-code/pymap3d) ⭐ 442 | 🐛 6 | 🌐 Python | 📅 2026-06-22 (👨‍💻 11 · 🔀 68 · 📋 38 - 2% open · ⏱️ 03.07.2022):

  ```
  git clone https://github.com/geospace-code/pymap3d
  ```
* [PyPi](https://pypi.org/project/pymap3d) (📥 50K / month):
  ```
  pip install pymap3d
  ```
* [Conda](https://anaconda.org/conda-forge/pymap3d) (📥 29K · ⏱️ 04.07.2022):
  ```
  conda install -c conda-forge pymap3d
  ```

</details>
<br>

## 金融数据处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于算法股票/加密交易，风险分析，回测，技术分析以及其他金融数据任务的库。*

<details><summary><b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇30 ·  ⭐ 15K · 💀) - Zipline，一个Pythonic算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/quantopian/zipline) ⭐ 20,061 | 🐛 370 | 🌐 Python | 📅 2024-02-13 (👨‍💻 160 · 🔀 4K · 📦 880 · 📋 970 - 32% open · ⏱️ 14.10.2020):

  ```
  git clone https://github.com/quantopian/zipline
  ```
* [PyPi](https://pypi.org/project/zipline) (📥 3.1K / month):
  ```
  pip install zipline
  ```

</details>
<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇30 ·  ⭐ 7.5K) - Yahoo! 金融市场数据下载器（+更快的Pandas数据加载读取器）。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ranaroussi/yfinance) ⭐ 25,061 | 🐛 146 | 🌐 Python | 📅 2026-08-20 (👨‍💻 60 · 🔀 1.6K · 📦 13K · 📋 810 - 56% open · ⏱️ 11.07.2022):

  ```
  git clone https://github.com/ranaroussi/yfinance
  ```
* [PyPi](https://pypi.org/project/yfinance) (📥 500K / month):
  ```
  pip install yfinance
  ```
* [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 51K · ⏱️ 10.07.2021):
  ```
  conda install -c ranaroussi yfinance
  ```

</details>
<details><summary><b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥇27 ·  ⭐ 9.2K · 💀) - 用于交易策略的Python Backtesting库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/mementum/backtrader) ⭐ 22,933 | 🐛 63 | 🌐 Python | 📅 2024-08-19 (👨‍💻 52 · 🔀 2.7K · 📦 1.1K · ⏱️ 17.07.2021):

  ```
  git clone https://github.com/mementum/backtrader
  ```
* [PyPi](https://pypi.org/project/backtrader) (📥 13K / month):
  ```
  pip install backtrader
  ```

</details>
<details><summary><b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥈26 ·  ⭐ 4.5K · 💀) - Python中的投资组合和风险分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/quantopian/pyfolio) ⭐ 6,404 | 🐛 166 | 🌐 Jupyter Notebook | 📅 2023-12-23 (👨‍💻 56 · 🔀 1.4K · 📦 450 · 📋 400 - 34% open · ⏱️ 15.07.2020):

  ```
  git clone https://github.com/quantopian/pyfolio
  ```
* [PyPi](https://pypi.org/project/pyfolio) (📥 6.5K / month):
  ```
  pip install pyfolio
  ```
* [Conda](https://anaconda.org/conda-forge/pyfolio) (📥 9.3K · ⏱️ 16.05.2020):
  ```
  conda install -c conda-forge pyfolio
  ```

</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈26 ·  ⭐ 3.2K) - 使用Pandas和Numpy的技术分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/bukosabino/ta) ⭐ 5,179 | 🐛 156 | 🌐 Jupyter Notebook | 📅 2026-03-18 (👨‍💻 29 · 🔀 720 · 📦 1.4K · 📋 200 - 51% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/bukosabino/ta
  ```
* [PyPi](https://pypi.org/project/ta) (📥 71K / month):
  ```
  pip install ta
  ```

</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥈26 ·  ⭐ 1.3K) - ffn-Python的金融函数库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pmorissette/ffn) ⭐ 2,636 | 🐛 8 | 🌐 Python | 📅 2026-08-13 (👨‍💻 28 · 🔀 220 · 📦 220 · 📋 100 - 20% open · ⏱️ 01.07.2022):

  ```
  git clone https://github.com/pmorissette/ffn
  ```
* [PyPi](https://pypi.org/project/ffn) (📥 37K / month):
  ```
  pip install ffn
  ```

</details>
<details><summary><b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈25 ·  ⭐ 2.4K · 💀) - 股票因子预测分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/quantopian/alphalens) ⭐ 4,424 | 🐛 50 | 🌐 Jupyter Notebook | 📅 2024-02-12 (👨‍💻 25 · 🔀 880 · 📦 570 · 📋 180 - 20% open · ⏱️ 27.04.2020):

  ```
  git clone https://github.com/quantopian/alphalens
  ```
* [PyPi](https://pypi.org/project/alphalens) (📥 13K / month):
  ```
  pip install alphalens
  ```
* [Conda](https://anaconda.org/conda-forge/alphalens) (📥 16K · ⏱️ 16.05.2020):
  ```
  conda install -c conda-forge alphalens
  ```

</details>
<details><summary><b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥈25 ·  ⭐ 970 · 💀) - 常见的金融风险和绩效指标。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/quantopian/empyrical) ⭐ 1,507 | 🐛 37 | 🌐 Python | 📅 2024-07-26 (👨‍💻 22 · 🔀 300 · 📦 940 · 📋 49 - 46% open · ⏱️ 14.10.2020):

  ```
  git clone https://github.com/quantopian/empyrical
  ```
* [PyPi](https://pypi.org/project/empyrical) (📥 28K / month):
  ```
  pip install empyrical
  ```
* [Conda](https://anaconda.org/conda-forge/empyrical) (📥 18K · ⏱️ 14.10.2020):
  ```
  conda install -c conda-forge empyrical
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥈24 ·  ⭐ 9.5K) - Qlib是一个面向AI的量化投资平台。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/microsoft/qlib) ⭐ 47,874 | 🐛 470 | 🌐 Python | 📅 2026-07-23 (👨‍💻 100 · 🔀 1.7K · 📥 330 · 📦 27 · 📋 600 - 27% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/microsoft/qlib
  ```
* [PyPi](https://pypi.org/project/pyqlib) (📥 2.4K / month):
  ```
  pip install pyqlib
  ```

</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈24 ·  ⭐ 1.5K) - bt-Python的灵活回测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pmorissette/bt) ⭐ 2,964 | 🐛 84 | 🌐 Python | 📅 2026-08-07 (👨‍💻 27 · 🔀 320 · 📦 130 · 📋 300 - 20% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/pmorissette/bt
  ```
* [PyPi](https://pypi.org/project/bt) (📥 5.5K / month):
  ```
  pip install bt
  ```

</details>
<details><summary><b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉23 ·  ⭐ 1.7K) - 基于pandas实现的通用金融技术指标。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

* [GitHub](https://github.com/peerchemist/finta) ⚠️ Archived (👨‍💻 28 · 🔀 550 · 📦 260 · 📋 85 - 24% open · ⏱️ 24.07.2022):

  ```
  git clone https://github.com/peerchemist/finta
  ```
* [PyPi](https://pypi.org/project/finta) (📥 7.7K / month):
  ```
  pip install finta
  ```

</details>
<details><summary><b><a href="https://github.com/bashtage/arch">arch</a></b> (🥉23 ·  ⭐ 970) - Python中的ARCH模型。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/bashtage/arch) ⭐ 1,554 | 🐛 51 | 🌐 Python | 📅 2026-08-10 (👨‍💻 31 · 🔀 210 · 📦 620 · 📋 180 - 8% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/bashtage/arch
  ```
* [PyPi](https://pypi.org/project/arch) (📥 320K / month):
  ```
  pip install arch
  ```

</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥉22 ·  ⭐ 3.9K) - 一个开放源代码的强化学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/tensortrade-org/tensortrade) ⭐ 7,038 | 🐛 48 | 🌐 Python | 📅 2026-02-19 (👨‍💻 61 · 🔀 890 · 📦 36 · 📋 230 - 16% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/tensortrade-org/tensortrade
  ```
* [PyPi](https://pypi.org/project/tensortrade) (📥 490 / month):
  ```
  pip install tensortrade
  ```

</details>
<details><summary><b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉22 ·  ⭐ 3.7K · 💀) - Python算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/gbeced/pyalgotrade) ⚠️ Archived (👨‍💻 11 · 🔀 1.2K · 📦 110 · 📋 120 - 31% open · ⏱️ 21.08.2018):

  ```
  git clone https://github.com/gbeced/pyalgotrade
  ```
* [PyPi](https://pypi.org/project/pyalgotrade) (📥 480 / month):
  ```
  pip install pyalgotrade
  ```

</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥉21 ·  ⭐ 3.7K · 💀) - 用于金融数据的Alpha Vantage API的python包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/RomelTorres/alpha_vantage) ⭐ 4,898 | 🐛 3 | 🌐 Python | 📅 2026-07-26 (👨‍💻 39 · 🔀 640 · 📋 260 - 2% open · ⏱️ 14.06.2021):

  ```
  git clone https://github.com/RomelTorres/alpha_vantage
  ```
* [PyPi](https://pypi.org/project/alpha_vantage) (📥 17K / month):
  ```
  pip install alpha_vantage
  ```

</details>
<details><summary><b><a href="https://github.com/scrtlabs/catalyst">Enigma Catalyst</a></b> (🥉21 ·  ⭐ 2.4K · 💤) - Python中加密资产的算法交易库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/scrtlabs/catalyst) ⚠️ Archived (👨‍💻 150 · 🔀 700 · 📦 25 · 📋 480 - 25% open · ⏱️ 22.09.2021):

  ```
  git clone https://github.com/enigmampc/catalyst
  ```
* [PyPi](https://pypi.org/project/enigma-catalyst) (📥 430 / month):
  ```
  pip install enigma-catalyst
  ```

</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉20 ·  ⭐ 3.2K) - 用于量化投资的高性能TensorFlow库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/google/tf-quant-finance) ⭐ 5,477 | 🐛 42 | 🌐 Python | 📅 2026-08-06 (👨‍💻 41 · 🔀 420 · 📋 40 - 37% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/google/tf-quant-finance
  ```
* [PyPi](https://pypi.org/project/tf-quant-finance) (📥 4.8K / month):
  ```
  pip install tf-quant-finance
  ```

</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥉20 ·  ⭐ 1.9K) - 用于Interactive Brokers API的Python同步/异步框架。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/erdewit/ib_insync) ⚠️ Archived (👨‍💻 31 · 🔀 490 · 📋 420 - 1% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/erdewit/ib_insync
  ```
* [PyPi](https://pypi.org/project/ib_insync) (📥 7.4K / month):
  ```
  pip install ib_insync
  ```
* [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 20K · ⏱️ 29.11.2021):
  ```
  conda install -c conda-forge ib-insync
  ```

</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉19 ·  ⭐ 4.1K) - CryptoSignal量化交易技术。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/CryptoSignal/Crypto-Signal) ⭐ 5,616 | 🐛 60 | 🌐 Python | 📅 2024-07-07 (👨‍💻 28 · 🔀 1.1K · 📋 260 - 20% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/CryptoSignal/crypto-signal
  ```
* [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 140K · ⭐ 7 · ⏱️ 03.09.2020):
  ```
  docker pull shadowreaver/crypto-signal
  ```

</details>
<details><summary><b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉19 ·  ⭐ 1K · 💤) - 提供StockDataFrame包装器<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/jealous/stockstats) ⭐ 1,486 | 🐛 12 | 🌐 Python | 📅 2026-06-19 (👨‍💻 8 · 🔀 260 · 📦 530 · 📋 87 - 11% open · ⏱️ 07.01.2022):

  ```
  git clone https://github.com/jealous/stockstats
  ```
* [PyPi](https://pypi.org/project/stockstats) (📥 6.2K / month):
  ```
  pip install stockstats
  ```

</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉18 ·  ⭐ 3K) - Python库，用于回测交易策略和分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/cuemacro/finmarketpy) ⭐ 3,805 | 🐛 38 | 🌐 Python | 📅 2026-04-16 (👨‍💻 14 · 🔀 440 · 📥 40 · 📦 5 · 📋 26 - 88% open · ⏱️ 05.04.2022):

  ```
  git clone https://github.com/cuemacro/finmarketpy
  ```
* [PyPi](https://pypi.org/project/finmarketpy) (📥 100 / month):
  ```
  pip install finmarketpy
  ```

</details>
<details><summary><b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉17 ·  ⭐ 2.8K) - 回溯Python中的交易策略。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/kernc/backtesting.py) ⭐ 8,878 | 🐛 67 | 🌐 Python | 📅 2026-08-05 (👨‍💻 15 · 🔀 550 · 📋 330 - 17% open · ⏱️ 27.03.2022):

  ```
  git clone https://github.com/kernc/backtesting.py
  ```
* [PyPi](https://pypi.org/project/backtesting) (📥 7.4K / month):
  ```
  pip install backtesting
  ```

</details>
<details><summary><b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.5K · 💀) - 使用机器学习在股票大波动之前找到它。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/tradytics/surpriver) ⭐ 1,874 | 🐛 13 | 🌐 Python | 📅 2021-08-13 (👨‍💻 6 · 🔀 280 · 📋 15 - 60% open · ⏱️ 21.09.2020):

  ```
  git clone https://github.com/tradytics/surpriver
  ```

</details>
<br>

## 时间序列

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于按时间序列和顺序数据进行预测，异常检测，特征提取和机器学习的库。*

<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇30 ·  ⭐ 1.2K · 📈) - 一个统计数据库，旨在填补Python时间序列中的空白。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/alkaline-ml/pmdarima) ⭐ 1,733 | 🐛 65 | 🌐 Python | 📅 2025-11-17 (👨‍💻 21 · 🔀 210 · 📦 2.5K · 📋 280 - 9% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/alkaline-ml/pmdarima
  ```
* [PyPi](https://pypi.org/project/pmdarima) (📥 1.5M / month):
  ```
  pip install pmdarima
  ```

</details>
<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥇27 ·  ⭐ 5.6K) - 具有时间序列的机器学习的统一框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/alan-turing-institute/sktime) ⭐ 9,960 | 🐛 2,385 | 🌐 Python | 📅 2026-08-23 (👨‍💻 190 · 🔀 890 · 📥 76 · 📦 560 · 📋 1.3K - 33% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/alan-turing-institute/sktime
  ```
* [PyPi](https://pypi.org/project/sktime) (📥 260K / month):
  ```
  pip install sktime
  ```

</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥈26 ·  ⭐ 2.4K) - STUMPY是一个功能强大且可扩展的Python库，用于矩阵计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/TDAmeritrade/stumpy) ⭐ 4,149 | 🐛 80 | 🌐 Python | 📅 2026-08-22 (👨‍💻 31 · 🔀 230 · 📦 260 · 📋 340 - 11% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/TDAmeritrade/stumpy
  ```
* [PyPi](https://pypi.org/project/stumpy) (📥 170K / month):
  ```
  pip install stumpy
  ```
* [Conda](https://anaconda.org/conda-forge/stumpy) (📥 48K · ⏱️ 31.03.2022):
  ```
  conda install -c conda-forge stumpy
  ```

</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥈25 ·  ⭐ 15K) - 产生具有时间序列数据的高质量预测的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebook/prophet) ⭐ 20,364 | 🐛 453 | 🌐 Python | 📅 2026-08-15 (👨‍💻 150 · 🔀 4.2K · 📥 810 · 📋 1.9K - 13% open · ⏱️ 07.07.2022):

  ```
  git clone https://github.com/facebook/prophet
  ```
* [PyPi](https://pypi.org/project/fbprophet) (📥 1.7M / month):
  ```
  pip install fbprophet
  ```

</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈25 ·  ⭐ 4.6K) - 一个易于操作和预测时间序列的python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/unit8co/darts) ⭐ 9,500 | 🐛 228 | 🌐 Python | 📅 2026-08-21 (👨‍💻 61 · 🔀 480 · 📦 92 · 📋 600 - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/unit8co/darts
  ```
* [PyPi](https://pypi.org/project/u8darts) (📥 6.4K / month):
  ```
  pip install u8darts
  ```
* [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 360 · ⏱️ 12.08.2022):
  ```
  docker pull unit8/darts
  ```

</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥈25 ·  ⭐ 2.2K) - 专门用于时间序列数据的机器学习工具包。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tslearn-team/tslearn) ⭐ 3,171 | 🐛 87 | 🌐 Python | 📅 2026-08-22 (👨‍💻 39 · 🔀 280 · 📦 560 · 📋 280 - 32% open · ⏱️ 17.06.2022):

  ```
  git clone https://github.com/tslearn-team/tslearn
  ```
* [PyPi](https://pypi.org/project/tslearn) (📥 100K / month):
  ```
  pip install tslearn
  ```
* [Conda](https://anaconda.org/conda-forge/tslearn) (📥 270K · ⏱️ 15.01.2022):
  ```
  conda install -c conda-forge tslearn
  ```

</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥈25 ·  ⭐ 2.2K) - 使用PyTorch进行时间序列预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jdb78/pytorch-forecasting) ⭐ 4,973 | 🐛 801 | 🌐 Python | 📅 2026-08-22 (👨‍💻 32 · 🔀 350 · 📋 510 - 49% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/jdb78/pytorch-forecasting
  ```
* [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 74K / month):
  ```
  pip install pytorch-forecasting
  ```

</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈23 ·  ⭐ 6.6K · 💤) - 从时间序列中自动提取相关特征。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/blue-yonder/tsfresh) ⭐ 9,294 | 🐛 71 | 🌐 Jupyter Notebook | 📅 2026-07-06 (👨‍💻 82 · 🔀 1K · 📋 490 - 10% open · ⏱️ 21.12.2021):

  ```
  git clone https://github.com/blue-yonder/tsfresh
  ```
* [PyPi](https://pypi.org/project/tsfresh) (📥 420K / month):
  ```
  pip install tsfresh
  ```
* [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 220K · ⏱️ 21.12.2021):
  ```
  conda install -c conda-forge tsfresh
  ```

</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥈23 ·  ⭐ 1.3K) - 用于时间序列分类的Python软件包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/johannfaouzi/pyts) ⭐ 1,876 | 🐛 52 | 🌐 Python | 📅 2025-06-18 (👨‍💻 11 · 🔀 140 · 📦 240 · 📋 64 - 59% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/johannfaouzi/pyts
  ```
* [PyPi](https://pypi.org/project/pyts) (📥 140K / month):
  ```
  pip install pyts
  ```
* [Conda](https://anaconda.org/conda-forge/pyts) (📥 13K · ⏱️ 31.10.2021):
  ```
  conda install -c conda-forge pyts
  ```

</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥈23 ·  ⭐ 1.1K) - python的实时流处理。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/python-streamz/streamz) ⭐ 1,303 | 🐛 121 | 🌐 Python | 📅 2026-04-07 (👨‍💻 45 · 🔀 140 · 📦 310 · 📋 240 - 39% open · ⏱️ 27.07.2022):

  ```
  git clone https://github.com/python-streamz/streamz
  ```
* [PyPi](https://pypi.org/project/streamz) (📥 12K / month):
  ```
  pip install streamz
  ```
* [Conda](https://anaconda.org/conda-forge/streamz) (📥 380K · ⏱️ 28.07.2022):
  ```
  conda install -c conda-forge streamz
  ```

</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥉22 ·  ⭐ 2.9K) - Python中的概率时间序列建模。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/awslabs/gluon-ts) ⭐ 5,228 | 🐛 475 | 🌐 Python | 📅 2026-07-31 (👨‍💻 93 · 🔀 580 · 📋 740 - 31% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/awslabs/gluon-ts
  ```
* [PyPi](https://pypi.org/project/gluonts) (📥 140K / month):
  ```
  pip install gluonts
  ```

</details>
<details><summary><b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉22 ·  ⭐ 2K · 💀) - 适用于Python的开源时间序列库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/RJT1990/pyflux) ⭐ 2,135 | 🐛 93 | 🌐 Python | 📅 2023-10-24 (👨‍💻 6 · 🔀 220 · 📦 220 · 📋 150 - 56% open · ⏱️ 16.12.2018):

  ```
  git clone https://github.com/RJT1990/pyflux
  ```
* [PyPi](https://pypi.org/project/pyflux) (📥 150K / month):
  ```
  pip install pyflux
  ```

</details>
<details><summary><b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉20 ·  ⭐ 1K · 💀) - 异常检测和相关库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/linkedin/luminol) ⭐ 1,230 | 🐛 35 | 🌐 Python | 📅 2025-08-22 (👨‍💻 8 · 🔀 200 · 📦 66 · 📋 36 - 66% open · ⏱️ 09.01.2018):

  ```
  git clone https://github.com/linkedin/luminol
  ```
* [PyPi](https://pypi.org/project/luminol) (📥 32K / month):
  ```
  pip install luminol
  ```

</details>
<details><summary><b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉18 ·  ⭐ 850 · 💀) - 一个Python工具包，用于基于规则的/无监督的异常检测。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

* [GitHub](https://github.com/arundo/adtk) ⭐ 1,211 | 🐛 54 | 🌐 Python | 📅 2024-08-01 (👨‍💻 11 · 🔀 100 · 📋 67 - 46% open · ⏱️ 17.04.2020):

  ```
  git clone https://github.com/arundo/adtk
  ```
* [PyPi](https://pypi.org/project/adtk) (📥 280K / month):
  ```
  pip install adtk
  ```

</details>
<details><summary><b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉18 ·  ⭐ 420 · 💀) - 用于贝叶斯时间序列建模的python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/wwrechard/pydlm) ⭐ 489 | 🐛 38 | 🌐 Python | 📅 2026-08-16 (👨‍💻 6 · 🔀 91 · 📦 27 · 📋 43 - 81% open · ⏱️ 22.10.2019):

  ```
  git clone https://github.com/wwrechard/pydlm
  ```
* [PyPi](https://pypi.org/project/pydlm) (📥 27K / month):
  ```
  pip install pydlm
  ```

</details>
<details><summary><b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉18 ·  ⭐ 400 · 💀) - 统计学习模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/X-DataInitiative/tick) ⭐ 551 | 🐛 86 | 🌐 Python | 📅 2026-06-15 (👨‍💻 16 · 🔀 84 · 📥 200 · 📦 66 · 📋 220 - 25% open · ⏱️ 15.06.2020):

  ```
  git clone https://github.com/X-DataInitiative/tick
  ```
* [PyPi](https://pypi.org/project/tick) (📥 980 / month):
  ```
  pip install tick
  ```

</details>
<details><summary><b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉17 ·  ⭐ 690 · 💀) - 一个用于检测模式和异常的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/target/matrixprofile-ts) ⚠️ Archived (👨‍💻 15 · 🔀 97 · 📦 19 · 📋 53 - 35% open · ⏱️ 25.04.2020):

  ```
  git clone https://github.com/target/matrixprofile-ts
  ```
* [PyPi](https://pypi.org/project/matrixprofile-ts) (📥 520 / month):
  ```
  pip install matrixprofile-ts
  ```

</details>
<details><summary><b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉17 ·  ⭐ 520) - 机器学习时间序列的Python模块。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/dmbee/seglearn) ⭐ 575 | 🐛 5 | 🌐 Python | 📅 2022-08-27 (👨‍💻 14 · 🔀 61 · 📦 11 · 📋 29 - 20% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/dmbee/seglearn
  ```
* [PyPi](https://pypi.org/project/seglearn) (📥 970 / month):
  ```
  pip install seglearn
  ```

</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉17 ·  ⭐ 470) - 自动实现ARIMA，SARIMAX，VAR，FB Prophet和XGBoost等模型时序建模。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/AutoViML/Auto_TS) ⭐ 764 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-08-20 (👨‍💻 6 · 🔀 86 · 📋 75 - 8% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/AutoViML/Auto_TS
  ```
* [PyPi](https://pypi.org/project/auto-ts) (📥 4.4K / month):
  ```
  pip install auto-ts
  ```

</details>
<details><summary><b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉13 ·  ⭐ 450 · 💤) - AtsPy：Python中的自动时间序列模型。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/firmai/atspy) ⭐ 520 | 🐛 26 | 🌐 Python | 📅 2022-11-21 (👨‍💻 5 · 🔀 85 · 📦 6 · 📋 21 - 90% open · ⏱️ 18.12.2021):

  ```
  git clone https://github.com/firmai/atspy
  ```
* [PyPi](https://pypi.org/project/atspy) (📥 350 / month):
  ```
  pip install atspy
  ```

</details>
<br>

## 医疗领域

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于处理和分析MRI，EEG，基因组数据和其他医学成像格式等医学数据的库。*

<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥇31 ·  ⭐ 640) - 神经影像软件包的工作流程和接口。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nipy/nipype) ⭐ 834 | 🐛 433 | 🌐 Python | 📅 2026-07-20 (👨‍💻 240 · 🔀 460 · 📦 1K · 📋 1.3K - 28% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/nipy/nipype
  ```
* [PyPi](https://pypi.org/project/nipype) (📥 54K / month):
  ```
  pip install nipype
  ```
* [Conda](https://anaconda.org/conda-forge/nipype) (📥 490K · ⏱️ 14.07.2022):
  ```
  conda install -c conda-forge nipype
  ```

</details>
<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥇30 ·  ⭐ 1.9K) - Python中的生存分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/CamDavidsonPilon/lifelines) ⭐ 2,605 | 🐛 296 | 🌐 Python | 📅 2026-03-07 (👨‍💻 100 · 🔀 480 · 📦 1K · 📋 870 - 25% open · ⏱️ 17.07.2022):

  ```
  git clone https://github.com/CamDavidsonPilon/lifelines
  ```
* [PyPi](https://pypi.org/project/lifelines) (📥 370K / month):
  ```
  pip install lifelines
  ```
* [Conda](https://anaconda.org/conda-forge/lifelines) (📥 210K · ⏱️ 18.05.2022):
  ```
  conda install -c conda-forge lifelines
  ```

</details>
<details><summary><b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈28 ·  ⭐ 490) - Python软件包，用于访问神经影像文件格式。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/nipy/nibabel) ⭐ 788 | 🐛 156 | 🌐 Python | 📅 2026-08-03 (👨‍💻 94 · 🔀 230 · 📦 7.9K · 📋 440 - 26% open · ⏱️ 20.08.2022):

  ```
  git clone https://github.com/nipy/nibabel
  ```
* [PyPi](https://pypi.org/project/nibabel) (📥 230K / month):
  ```
  pip install nibabel
  ```
* [Conda](https://anaconda.org/conda-forge/nibabel) (📥 470K · ⏱️ 18.06.2022):
  ```
  conda install -c conda-forge nibabel
  ```

</details>
<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥈27 ·  ⭐ 2K) - MNE：Python中的磁脑图（MEG）和脑电图（EEG）。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/mne-tools/mne-python) ⭐ 3,492 | 🐛 629 | 🌐 Python | 📅 2026-08-23 (👨‍💻 310 · 🔀 1K · 📦 1.8K · 📋 4.2K - 9% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/mne-tools/mne-python
  ```
* [PyPi](https://pypi.org/project/mne) (📥 48K / month):
  ```
  pip install mne
  ```
* [Conda](https://anaconda.org/conda-forge/mne) (📥 220K · ⏱️ 24.08.2022):
  ```
  conda install -c conda-forge mne
  ```

</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈27 ·  ⭐ 820) - 可扩展的基因组数据分析。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/hail-is/hail) ⭐ 1,069 | 🐛 362 | 🌐 Python | 📅 2026-08-23 (👨‍💻 81 · 🔀 210 · 📦 75 · 📋 2K - 0% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/hail-is/hail
  ```
* [PyPi](https://pypi.org/project/hail) (📥 240K / month):
  ```
  pip install hail
  ```

</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈25 ·  ⭐ 3.3K) - 用于医疗成像的AI工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Project-MONAI/MONAI) ⭐ 8,626 | 🐛 529 | 🌐 Python | 📅 2026-08-20 (👨‍💻 110 · 🔀 640 · 📦 460 · 📋 1.9K - 11% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/Project-MONAI/MONAI
  ```
* [PyPi](https://pypi.org/project/monai) (📥 48K / month):
  ```
  pip install monai
  ```

</details>
<details><summary><b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥈24 ·  ⭐ 880) - Python中NeuroImaging的机器学习。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/nilearn/nilearn) ⭐ 1,424 | 🐛 294 | 🌐 Python | 📅 2026-08-21 (👨‍💻 190 · 🔀 450 · 📥 64 · 📦 1.7K · 📋 1.6K - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/nilearn/nilearn
  ```
* [PyPi](https://pypi.org/project/nilearn) (📥 38K / month):
  ```
  pip install nilearn
  ```
* [Conda](https://anaconda.org/conda-forge/nilearn) (📥 180K · ⏱️ 24.08.2022):
  ```
  conda install -c conda-forge nilearn
  ```

</details>
<details><summary><b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈24 ·  ⭐ 540) - DIPY是Python中的Paragon 3D/4D +影像库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/dipy/dipy) ⭐ 835 | 🐛 140 | 🌐 Python | 📅 2026-08-22 (👨‍💻 130 · 🔀 340 · 📦 600 · 📋 780 - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/dipy/dipy
  ```
* [PyPi](https://pypi.org/project/dipy) (📥 13K / month):
  ```
  pip install dipy
  ```
* [Conda](https://anaconda.org/conda-forge/dipy) (📥 320K · ⏱️ 15.03.2022):
  ```
  conda install -c conda-forge dipy
  ```

</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉22 ·  ⭐ 2.6K) - DeepVariant是使用深度神经网络的分析管道。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/google/deepvariant) ⭐ 3,786 | 🐛 6 | 🌐 Python | 📅 2026-03-19 (👨‍💻 24 · 🔀 620 · 📥 4.1K · 📋 500 - 1% open · ⏱️ 02.06.2022):

  ```
  git clone https://github.com/google/deepvariant
  ```
* [Conda](https://anaconda.org/bioconda/deepvariant) (📥 44K · ⏱️ 05.06.2022):
  ```
  conda install -c bioconda deepvariant
  ```

</details>
<details><summary><b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉22 ·  ⭐ 1.3K · 💀) - 开源医疗卷积神经网络工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/NifTK/NiftyNet) ⚠️ Archived (👨‍💻 59 · 🔀 390 · 📦 38 · 📋 320 - 30% open · ⏱️ 21.04.2020):

  ```
  git clone https://github.com/NifTK/NiftyNet
  ```
* [PyPi](https://pypi.org/project/niftynet) (📥 260 / month):
  ```
  pip install niftynet
  ```

</details>
<details><summary><b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉22 ·  ⭐ 430 · 💀) - Python中的医学图像处理。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/loli/medpy) ⭐ 620 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-09-03 (👨‍💻 14 · 🔀 120 · 📦 700 · 📋 80 - 15% open · ⏱️ 01.05.2020):

  ```
  git clone https://github.com/loli/medpy
  ```
* [PyPi](https://pypi.org/project/MedPy) (📥 13K / month):
  ```
  pip install MedPy
  ```

</details>
<details><summary><b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉22 ·  ⭐ 210) - 一个用于大规模基因组分析的开源工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/projectglow/glow) ⭐ 307 | 🐛 60 | 🌐 Scala | 📅 2026-06-28 (👨‍💻 21 · 🔀 78 · 📋 130 - 40% open · ⏱️ 09.05.2022):

  ```
  git clone https://github.com/projectglow/glow
  ```
* [PyPi](https://pypi.org/project/glow.py) (📥 140K / month):
  ```
  pip install glow.py
  ```

</details>
<details><summary><b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉18 ·  ⭐ 1.3K · 💀) - 用于医学图像分析的深度学习工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/DLTK/DLTK) ⭐ 1,458 | 🐛 15 | 🌐 Python | 📅 2023-03-24 (👨‍💻 9 · 🔀 390 · 📦 23 · 📋 31 - 22% open · ⏱️ 21.01.2019):

  ```
  git clone https://github.com/DLTK/DLTK
  ```
* [PyPi](https://pypi.org/project/dltk) (📥 100 / month):
  ```
  pip install dltk
  ```

</details>
<details><summary><b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉18 ·  ⭐ 320 · 💀) - Python FMRI分析软件包中的Neuroimaging。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/nipy/nipy) ⭐ 414 | 🐛 40 | 🌐 Python | 📅 2024-12-24 (👨‍💻 63 · 🔀 130 · 📋 150 - 26% open · ⏱️ 29.03.2021):

  ```
  git clone https://github.com/nipy/nipy
  ```
* [PyPi](https://pypi.org/project/nipy) (📥 1.5K / month):
  ```
  pip install nipy
  ```
* [Conda](https://anaconda.org/conda-forge/nipy) (📥 95K · ⏱️ 04.05.2020):
  ```
  conda install -c conda-forge nipy
  ```

</details>
<details><summary><b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉18 ·  ⭐ 280 · 💀) - 脑成像分析套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/brainiak/brainiak) ⭐ 372 | 🐛 99 | 🌐 Python | 📅 2026-08-07 (👨‍💻 34 · 🔀 130 · 📦 16 · 📋 200 - 37% open · ⏱️ 28.05.2021):

  ```
  git clone https://github.com/brainiak/brainiak
  ```
* [PyPi](https://pypi.org/project/brainiak) (📥 180 / month):
  ```
  pip install brainiak
  ```
* [Docker Hub](https://hub.docker.com/r/brainiak/brainiak) (📥 760 · ⭐ 1 · ⏱️ 15.10.2020):
  ```
  docker pull brainiak/brainiak
  ```

</details>
<details><summary><b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉15 ·  ⭐ 790 · 💀) - Pytorch的医学成像框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/perone/medicaltorch) ⭐ 872 | 🐛 17 | 🌐 Python | 📅 2024-04-26 (👨‍💻 8 · 🔀 110 · 📦 12 · 📋 22 - 59% open · ⏱️ 16.04.2021):

  ```
  git clone https://github.com/perone/medicaltorch
  ```
* [PyPi](https://pypi.org/project/medicaltorch) (📥 210 / month):
  ```
  pip install medicaltorch
  ```

</details>
<details><summary><b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉14 ·  ⭐ 1.4K · 💀) - Transfer Learning for 3D Medical Image Analysis的论文实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Tencent/MedicalNet) ⭐ 2,253 | 🐛 75 | 🌐 Python | 📅 2025-11-27 (🔀 370 · 📋 70 - 78% open · ⏱️ 27.08.2020):

  ```
  git clone https://github.com/Tencent/MedicalNet
  ```

</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉14 ·  ⭐ 1.1K) - Medical Detection Toolkit包含2D + 3D。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) ⭐ 1,354 | 🐛 48 | 🌐 Python | 📅 2024-06-17 (👨‍💻 3 · 🔀 280 · 📋 120 - 30% open · ⏱️ 04.04.2022):

  ```
  git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
  ```

</details>
<details><summary><b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉11 ·  ⭐ 110 · 💀) - 用于神经影像数据的深度学习python软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/QTIM-Lab/DeepNeuro) ⭐ 131 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2020-06-24 (👨‍💻 6 · 🔀 34 · 📦 1 · 📋 41 - 60% open · ⏱️ 24.06.2020):

  ```
  git clone https://github.com/QTIM-Lab/DeepNeuro
  ```
* [PyPi](https://pypi.org/project/deepneuro) (📥 20 / month):
  ```
  pip install deepneuro
  ```

</details>
<br>

## 光学字符识别OCR

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于光学字符识别（OCR）和从图像或视频中提取文本的库。*

<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇31 ·  ⭐ 16K) - 即用型OCR，具有80多种受支持的语言和所有流行的手写文字。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/JaidedAI/EasyOCR) ⭐ 29,930 | 🐛 530 | 🌐 Python | 📅 2025-12-05 (👨‍💻 110 · 🔀 2.2K · 📥 2M · 📦 1.5K · 📋 640 - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/JaidedAI/EasyOCR
  ```
* [PyPi](https://pypi.org/project/easyocr) (📥 84K / month):
  ```
  pip install easyocr
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥇27 ·  ⭐ 24K) - 基于PaddlePaddle的多语言OCR工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 88,157 | 🐛 235 | 🌐 Python | 📅 2026-07-22 (👨‍💻 110 · 🔀 4.9K · 📦 780 · 📋 5.1K - 25% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/PaddleOCR
  ```
* [PyPi](https://pypi.org/project/paddleocr) (📥 38K / month):
  ```
  pip install paddleocr
  ```

</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈26 ·  ⭐ 1.7K) - 用于tesseract-ocr API的Python包装器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/sirfz/tesserocr) ⭐ 2,171 | 🐛 46 | 🌐 Python | 📅 2026-08-04 (👨‍💻 26 · 🔀 220 · 📦 700 · 📋 250 - 31% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/sirfz/tesserocr
  ```
* [PyPi](https://pypi.org/project/tesserocr) (📥 49K / month):
  ```
  pip install tesserocr
  ```
* [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 81K · ⏱️ 04.05.2022):
  ```
  conda install -c conda-forge tesserocr
  ```

</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈25 ·  ⭐ 4.4K) - Python-tesseract是一种光学字符识别（OCR）工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/madmaze/pytesseract) ⭐ 6,382 | 🐛 21 | 🌐 Python | 📅 2026-07-13 (👨‍💻 41 · 🔀 600 · 📋 310 - 4% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/madmaze/pytesseract
  ```
* [PyPi](https://pypi.org/project/pytesseract) (📥 670K / month):
  ```
  pip install pytesseract
  ```
* [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 520K · ⏱️ 15.03.2022):
  ```
  conda install -c conda-forge pytesseract
  ```

</details>
<details><summary><b><a href="https://github.com/ocrmypdf/OCRmyPDF">OCRmyPDF</a></b> (🥈22 ·  ⭐ 7K) - OCRmyPDF将OCR文本层添加到扫描的PDF文件中使用。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

* [GitHub](https://github.com/ocrmypdf/OCRmyPDF) ⭐ 34,551 | 🐛 96 | 🌐 Python | 📅 2026-08-22 (👨‍💻 74 · 🔀 590 · 📋 880 - 9% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/jbarlow83/OCRmyPDF
  ```
* [PyPi](https://pypi.org/project/ocrmypdf) (📥 25K / month):
  ```
  pip install ocrmypdf
  ```

</details>
<details><summary><b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉19 ·  ⭐ 2K) - 一组用于从PDF文件提取表格的工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/WZBSocialScienceCenter/pdftabextract) ⭐ 2,255 | 🐛 5 | 🌐 Python | 📅 2022-06-24 (👨‍💻 3 · 🔀 350 · 📦 42 · 📋 21 - 14% open · ⏱️ 24.06.2022):

  ```
  git clone https://github.com/WZBSocialScienceCenter/pdftabextract
  ```
* [PyPi](https://pypi.org/project/pdftabextract) (📥 660 / month):
  ```
  pip install pdftabextract
  ```

</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉19 ·  ⭐ 940) - 基于OCRopy的基于行的ATR引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Calamari-OCR/calamari) ⭐ 1,197 | 🐛 66 | 🌐 Python | 📅 2026-06-23 (👨‍💻 19 · 🔀 190 · 📋 250 - 19% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/Calamari-OCR/calamari
  ```
* [PyPi](https://pypi.org/project/calamari_ocr) (📥 430 / month):
  ```
  pip install calamari_ocr
  ```

</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉19 ·  ⭐ 920 · 💤) - 用于文本识别的Tensorflow模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/emedvedev/attention-ocr) ⭐ 1,086 | 🐛 27 | 🌐 Python | 📅 2023-10-20 (👨‍💻 27 · 🔀 240 · 📦 20 · 📋 150 - 15% open · ⏱️ 29.10.2021):

  ```
  git clone https://github.com/emedvedev/attention-ocr
  ```
* [PyPi](https://pypi.org/project/aocr) (📥 96 / month):
  ```
  pip install aocr
  ```

</details>
<details><summary><b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉18 ·  ⭐ 1.3K · 💀) - 批量检测文本块和OCR扫描不良的PDF。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jlsutherland/doc2text) ⭐ 1,278 | 🐛 16 | 🌐 Python | 📅 2020-12-01 (👨‍💻 5 · 🔀 95 · 📦 60 · 📋 21 - 57% open · ⏱️ 01.12.2020):

  ```
  git clone https://github.com/jlsutherland/doc2text
  ```
* [PyPi](https://pypi.org/project/doc2text) (📥 1.8K / month):
  ```
  pip install doc2text
  ```

</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉18 ·  ⭐ 1.1K) - CRAFT文本检测器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/faustomorales/keras-ocr) ⭐ 1,474 | 🐛 103 | 🌐 Python | 📅 2025-09-22 (👨‍💻 15 · 🔀 270 · 📥 300K · 📋 180 - 38% open · ⏱️ 19.05.2022):

  ```
  git clone https://github.com/faustomorales/keras-ocr
  ```
* [PyPi](https://pypi.org/project/keras-ocr) (📥 5.8K / month):
  ```
  pip install keras-ocr
  ```

</details>
<details><summary><b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉11 ·  ⭐ 400) - 光学音乐识别（OMR）系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/aashrafh/Mozart) ⭐ 710 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2022-08-24 (👨‍💻 5 · 🔀 58 · 📋 12 - 25% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/aashrafh/Mozart
  ```

</details>
<br>

## 数据容器和结构

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*通用数据容器和结构以及pandas的实用程序和扩展。*

<details><summary><b><a href="https://github.com/pandas-dev/pandas">pandas</a></b> (🥇39 ·  ⭐ 35K) - 灵活而强大的数据分析/操作库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pandas-dev/pandas) ⭐ 49,552 | 🐛 2,777 | 🌐 Python | 📅 2026-08-23 (👨‍💻 3.1K · 🔀 15K · 📥 160K · 📦 800K · 📋 23K - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pandas-dev/pandas
  ```
* [PyPi](https://pypi.org/project/pandas) (📥 100M / month):
  ```
  pip install pandas
  ```
* [Conda](https://anaconda.org/conda-forge/pandas) (📥 29M · ⏱️ 24.08.2022):
  ```
  conda install -c conda-forge pandas
  ```

</details>
<details><summary><b><a href="https://github.com/numpy/numpy">numpy</a></b> (🥇38 ·  ⭐ 21K) - 使用Python进行科学计算的基本软件包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/numpy/numpy) ⭐ 32,589 | 🐛 2,333 | 🌐 Python | 📅 2026-08-23 (👨‍💻 1.5K · 🔀 7K · 📥 560K · 📦 1.2M · 📋 11K - 18% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/numpy/numpy
  ```
* [PyPi](https://pypi.org/project/numpy) (📥 130M / month):
  ```
  pip install numpy
  ```
* [Conda](https://anaconda.org/conda-forge/numpy) (📥 38M · ⏱️ 16.08.2022):
  ```
  conda install -c conda-forge numpy
  ```

</details>
<details><summary><b><a href="https://github.com/h5py/h5py">h5py</a></b> (🥇36 ·  ⭐ 1.8K) - 适用于Python的HDF5-h5py软件包，HDF5的Pythonic接口。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/h5py/h5py) ⭐ 2,248 | 🐛 349 | 🌐 Python | 📅 2026-08-21 (👨‍💻 180 · 🔀 450 · 📥 2.1K · 📦 170K · 📋 1.3K - 16% open · ⏱️ 01.07.2022):

  ```
  git clone https://github.com/h5py/h5py
  ```
* [PyPi](https://pypi.org/project/h5py) (📥 12M / month):
  ```
  pip install h5py
  ```
* [Conda](https://anaconda.org/conda-forge/h5py) (📥 8.8M · ⏱️ 14.08.2022):
  ```
  conda install -c conda-forge h5py
  ```

</details>
<details><summary><b><a href="https://github.com/apache/arrow">Arrow</a></b> (🥈33 ·  ⭐ 10K) - Apache Arrow定义了一种在内存中表示tabular data的格式。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/arrow) ⭐ 17,043 | 🐛 2,586 | 🌐 C++ | 📅 2026-08-22 (👨‍💻 930 · 🔀 2.4K · 📦 77 · 📋 840 - 6% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/apache/arrow
  ```
* [PyPi](https://pypi.org/project/pyarrow) (📥 68M / month):
  ```
  pip install pyarrow
  ```
* [Conda](https://anaconda.org/conda-forge/arrow) (📥 1.1M · ⏱️ 27.01.2022):
  ```
  conda install -c conda-forge arrow
  ```

</details>
<details><summary><b><a href="https://github.com/modin-project/modin">Modin</a></b> (🥈29 ·  ⭐ 7.7K) - Modin：通过更改一行来加快Pandas工作流程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/modin-project/modin) ⭐ 10,390 | 🐛 713 | 🌐 Python | 📅 2026-02-10 (👨‍💻 100 · 🔀 540 · 📥 200K · 📦 710 · 📋 2.9K - 30% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/modin-project/modin
  ```
* [PyPi](https://pypi.org/project/modin) (📥 180K / month):
  ```
  pip install modin
  ```

</details>
<details><summary><b><a href="https://github.com/pydata/xarray">xarray</a></b> (🥈29 ·  ⭐ 2.7K) - Python中带有N-D标签的数组和数据集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/pydata/xarray) ⭐ 4,190 | 🐛 1,425 | 🌐 Python | 📅 2026-08-19 (👨‍💻 390 · 🔀 800 · 📦 12K · 📋 3.4K - 26% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pydata/xarray
  ```
* [PyPi](https://pypi.org/project/xarray) (📥 1.6M / month):
  ```
  pip install xarray
  ```
* [Conda](https://anaconda.org/conda-forge/xarray) (📥 5.7M · ⏱️ 26.07.2022):
  ```
  conda install -c conda-forge xarray
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/sklearn-pandas">sklearn-pandas</a></b> (🥈29 ·  ⭐ 2.6K) - pandas与sklearn集成。<code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/sklearn-pandas) ⭐ 2,842 | 🐛 43 | 🌐 Python | 📅 2023-06-08 (👨‍💻 39 · 🔀 380 · 📦 4.4K · 📋 150 - 16% open · ⏱️ 17.07.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/sklearn-pandas
  ```
* [PyPi](https://pypi.org/project/sklearn-pandas) (📥 580K / month):
  ```
  pip install sklearn-pandas
  ```

</details>
<details><summary><b><a href="https://github.com/ekzhu/datasketch">datasketch</a></b> (🥈29 ·  ⭐ 1.8K) - MinHash, LSH, LSH Forest, Weighted MinHash, HyperLogLog等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ekzhu/datasketch) ⭐ 2,956 | 🐛 58 | 🌐 Python | 📅 2026-08-09 (👨‍💻 24 · 🔀 240 · 📥 19 · 📦 440 · 📋 140 - 25% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/ekzhu/datasketch
  ```
* [PyPi](https://pypi.org/project/datasketch) (📥 720K / month):
  ```
  pip install datasketch
  ```

</details>
<details><summary><b><a href="https://github.com/pydata/bottleneck">Bottleneck</a></b> (🥈29 ·  ⭐ 780) - 用C编写的快速NumPy数组函数。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/pydata/bottleneck) ⭐ 1,181 | 🐛 60 | 🌐 Python | 📅 2026-08-09 (👨‍💻 25 · 🔀 80 · 📦 35K · 📋 220 - 15% open · ⏱️ 02.07.2022):

  ```
  git clone https://github.com/pydata/bottleneck
  ```
* [PyPi](https://pypi.org/project/Bottleneck) (📥 430K / month):
  ```
  pip install Bottleneck
  ```
* [Conda](https://anaconda.org/conda-forge/bottleneck) (📥 2.5M · ⏱️ 03.07.2022):
  ```
  conda install -c conda-forge bottleneck
  ```

</details>
<details><summary><b><a href="https://github.com/databricks/koalas">Koalas</a></b> (🥈28 ·  ⭐ 3.2K · 💤) - Apache Spark上的pandas API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/databricks/koalas) ⭐ 3,371 | 🐛 108 | 🌐 Python | 📅 2024-03-20 (👨‍💻 51 · 🔀 330 · 📥 1K · 📦 220 · 📋 580 - 16% open · ⏱️ 21.10.2021):

  ```
  git clone https://github.com/databricks/koalas
  ```
* [PyPi](https://pypi.org/project/koalas) (📥 1.6M / month):
  ```
  pip install koalas
  ```
* [Conda](https://anaconda.org/conda-forge/koalas) (📥 180K · ⏱️ 20.10.2021):
  ```
  conda install -c conda-forge koalas
  ```

</details>
<details><summary><b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥈28 ·  ⭐ 3.1K · 💀) - NumPy和Pandas连接到大数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/blaze/blaze) ⭐ 3,189 | 🐛 268 | 🌐 Python | 📅 2023-09-29 (👨‍💻 65 · 🔀 360 · 📦 8.3K · 📋 750 - 33% open · ⏱️ 15.08.2019):

  ```
  git clone https://github.com/blaze/blaze
  ```
* [PyPi](https://pypi.org/project/blaze) (📥 8.1K / month):
  ```
  pip install blaze
  ```
* [Conda](https://anaconda.org/conda-forge/blaze) (📥 200K · ⏱️ 15.07.2018):
  ```
  conda install -c conda-forge blaze
  ```

</details>
<details><summary><b><a href="https://github.com/vaexio/vaex">Vaex</a></b> (🥉26 ·  ⭐ 7.3K) - 用于Python，ML的核外混合Apache Arrow / NumPy DataFrame可视化等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/vaexio/vaex) ⭐ 8,508 | 🐛 552 | 🌐 Python | 📅 2026-04-01 (👨‍💻 70 · 🔀 550 · 📥 240 · 📦 310 · 📋 1.1K - 31% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/vaexio/vaex
  ```
* [PyPi](https://pypi.org/project/vaex) (📥 44K / month):
  ```
  pip install vaex
  ```
* [Conda](https://anaconda.org/conda-forge/vaex) (📥 140K · ⏱️ 27.07.2022):
  ```
  conda install -c conda-forge vaex
  ```

</details>
<details><summary><b><a href="https://github.com/zarr-developers/zarr-python">zarr</a></b> (🥉26 ·  ⭐ 970) - Python的分块，压缩N维数组的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/zarr-developers/zarr-python) ⭐ 2,042 | 🐛 505 | 🌐 Python | 📅 2026-08-22 (👨‍💻 65 · 🔀 160 · 📦 1.4K · 📋 500 - 38% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/zarr-developers/zarr-python
  ```
* [PyPi](https://pypi.org/project/zarr) (📥 120K / month):
  ```
  pip install zarr
  ```
* [Conda](https://anaconda.org/conda-forge/zarr) (📥 1.6M · ⏱️ 23.06.2022):
  ```
  conda install -c conda-forge zarr
  ```

</details>
<details><summary><b><a href="https://github.com/pydata/numexpr">numexpr</a></b> (🥉25 ·  ⭐ 1.8K) - 适用于Python，NumPy，PyTables等的快速数值数组表达式评估器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pydata/numexpr) ⭐ 2,534 | 🐛 3 | 🌐 Python | 📅 2026-08-17 (👨‍💻 63 · 🔀 180 · 📥 62 · 📋 330 - 18% open · ⏱️ 19.07.2022):

  ```
  git clone https://github.com/pydata/numexpr
  ```
* [PyPi](https://pypi.org/project/numexpr) (📥 2.6M / month):
  ```
  pip install numexpr
  ```
* [Conda](https://anaconda.org/conda-forge/numexpr) (📥 4.7M · ⏱️ 17.07.2022):
  ```
  conda install -c conda-forge numexpr
  ```

</details>
<details><summary><b><a href="https://github.com/PyTables/PyTables">PyTables</a></b> (🥉25 ·  ⭐ 1.1K) - 一个Python包，用于管理大量数据。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/PyTables/PyTables) ⭐ 1,372 | 🐛 153 | 🌐 Python | 📅 2026-08-23 (👨‍💻 110 · 🔀 210 · 📥 170 · 📋 650 - 22% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/PyTables/PyTables
  ```
* [PyPi](https://pypi.org/project/tables) (📥 1M / month):
  ```
  pip install tables
  ```
* [Conda](https://anaconda.org/conda-forge/pytables) (📥 4.6M · ⏱️ 13.08.2022):
  ```
  conda install -c conda-forge pytables
  ```

</details>
<details><summary><b><a href="https://github.com/man-group/arctic">Arctic</a></b> (🥉24 ·  ⭐ 2.8K) - Arctic是用于数字数据的高性能数据存储。<code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

* [GitHub](https://github.com/man-group/arctic) ⭐ 3,085 | 🐛 97 | 🌐 Python | 📅 2024-04-08 (👨‍💻 76 · 🔀 530 · 📥 190 · 📦 180 · 📋 530 - 14% open · ⏱️ 02.03.2022):

  ```
  git clone https://github.com/man-group/arctic
  ```
* [PyPi](https://pypi.org/project/arctic) (📥 6.4K / month):
  ```
  pip install arctic
  ```
* [Conda](https://anaconda.org/conda-forge/arctic) (📥 21K · ⏱️ 11.05.2022):
  ```
  conda install -c conda-forge arctic
  ```

</details>
<details><summary><b><a href="https://github.com/nalepae/pandarallel">Pandaral·lel</a></b> (🥉24 ·  ⭐ 2.4K) - A simple and efficient tool to parallelize Pandas.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/nalepae/pandarallel) ⭐ 3,799 | 🐛 99 | 🌐 Python | 📅 2024-07-09 (👨‍💻 20 · 🔀 150 · 📋 170 - 46% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/nalepae/pandarallel
  ```
* [PyPi](https://pypi.org/project/pandarallel) (📥 520K / month):
  ```
  pip install pandarallel
  ```

</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/swifter">swifter</a></b> (🥉24 ·  ⭐ 2.1K) - 一个可以对pandas Dataframe或者series做高效function映射的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jmcarpenter2/swifter) ⭐ 2,635 | 🐛 26 | 🌐 Python | 📅 2024-03-20 (👨‍💻 17 · 🔀 97 · 📦 660 · 📋 120 - 7% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/jmcarpenter2/swifter
  ```
* [PyPi](https://pypi.org/project/swifter) (📥 270K / month):
  ```
  pip install swifter
  ```
* [Conda](https://anaconda.org/conda-forge/swifter) (📥 150K · ⏱️ 17.08.2022):
  ```
  conda install -c conda-forge swifter
  ```

</details>
<details><summary><b><a href="https://github.com/yhat/pandasql">pandasql</a></b> (🥉24 ·  ⭐ 1.1K · 💀) - pandas的sqldf。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/yhat/pandasql) ⚠️ Archived (👨‍💻 15 · 🔀 150 · 📦 1.5K · 📋 70 - 65% open · ⏱️ 01.02.2017):

  ```
  git clone https://github.com/yhat/pandasql
  ```
* [PyPi](https://pypi.org/project/pandasql) (📥 1.6M / month):
  ```
  pip install pandasql
  ```

</details>
<details><summary><b><a href="https://github.com/Blosc/bcolz">bcolz</a></b> (🥉24 ·  ⭐ 940 · 💀) - 可以压缩的列式数据容器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Blosc/bcolz) ⚠️ Archived (👨‍💻 33 · 🔀 130 · 📦 1.8K · 📋 240 - 50% open · ⏱️ 10.09.2020):

  ```
  git clone https://github.com/Blosc/bcolz
  ```
* [PyPi](https://pypi.org/project/bcolz) (📥 14K / month):
  ```
  pip install bcolz
  ```
* [Conda](https://anaconda.org/conda-forge/bcolz) (📥 310K · ⏱️ 20.06.2022):
  ```
  conda install -c conda-forge bcolz
  ```

</details>
<details><summary><b><a href="https://github.com/msiemens/tinydb">TinyDB</a></b> (🥉23 ·  ⭐ 5.3K) - TinyDB：轻型面向文档的数据库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/msiemens/tinydb) ⭐ 7,557 | 🐛 8 | 🌐 Python | 📅 2026-08-10 (👨‍💻 78 · 🔀 450 · 📋 280 - 3% open · ⏱️ 23.07.2022):

  ```
  git clone https://github.com/msiemens/tinydb
  ```
* [PyPi](https://pypi.org/project/tinydb) (📥 390K / month):
  ```
  pip install tinydb
  ```
* [Conda](https://anaconda.org/conda-forge/tinydb) (📥 200K · ⏱️ 19.02.2022):
  ```
  conda install -c conda-forge tinydb
  ```

</details>
<details><summary><b><a href="https://github.com/InvestmentSystems/static-frame">StaticFrame</a></b> (🥉22 ·  ⭐ 310) - 类似Pandas的DataFrame的不可变且仅增长的高效数据结构实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/InvestmentSystems/static-frame) ⭐ 483 | 🐛 45 | 🌐 Python | 📅 2026-08-11 (👨‍💻 20 · 🔀 26 · 📦 11 · 📋 450 - 9% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/InvestmentSystems/static-frame
  ```
* [PyPi](https://pypi.org/project/static-frame) (📥 1.6K / month):
  ```
  pip install static-frame
  ```
* [Conda](https://anaconda.org/conda-forge/static-frame) (📥 180K · ⏱️ 14.08.2022):
  ```
  conda install -c conda-forge static-frame
  ```

</details>
<details><summary><b><a href="https://github.com/h2oai/datatable">datatable</a></b> (🥉20 ·  ⭐ 1.6K) - 一个用于处理二维表格数据的Python包。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

* [GitHub](https://github.com/h2oai/datatable) ⭐ 1,876 | 🐛 183 | 🌐 C++ | 📅 2026-07-27 (👨‍💻 33 · 🔀 140 · 📥 1.7K · 📋 1.4K - 10% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/h2oai/datatable
  ```
* [PyPi](https://pypi.org/project/datatable) (📥 67K / month):
  ```
  pip install datatable
  ```

</details>
<details><summary><b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉20 ·  ⭐ 700 · 💀) - pickleDB是使用Python的json的开源键值存储。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/patx/pickledb) ⭐ 1,072 | 🐛 18 | 🌐 Python | 📅 2026-05-10 (👨‍💻 12 · 🔀 110 · 📦 940 · 📋 57 - 28% open · ⏱️ 15.11.2019):

  ```
  git clone https://github.com/patx/pickledb
  ```
* [PyPi](https://pypi.org/project/pickledb) (📥 38K / month):
  ```
  pip install pickledb
  ```

</details>
<details><summary><b><a href="https://github.com/xhochy/fletcher">fletcher</a></b> (🥉19 ·  ⭐ 220 · 💀) - 由Apache Arrow支持的Pandas ExtensionDType/Array。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/xhochy/fletcher) ⚠️ Archived (👨‍💻 24 · 🔀 33 · 📥 13 · 📦 4 · 📋 74 - 45% open · ⏱️ 18.02.2021):

  ```
  git clone https://github.com/xhochy/fletcher
  ```
* [PyPi](https://pypi.org/project/fletcher) (📥 620 / month):
  ```
  pip install fletcher
  ```
* [Conda](https://anaconda.org/conda-forge/fletcher) (📥 46K · ⏱️ 04.11.2021):
  ```
  conda install -c conda-forge fletcher
  ```

</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/bounter">Bounter</a></b> (🥉18 ·  ⭐ 940 · 💀) - 使用有限内存的高效计数器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/RaRe-Technologies/bounter) ⭐ 930 | 🐛 19 | 🌐 Python | 📅 2022-11-20 (👨‍💻 8 · 🔀 44 · 📦 26 · 📋 25 - 64% open · ⏱️ 24.05.2021):

  ```
  git clone https://github.com/RaRe-Technologies/bounter
  ```
* [PyPi](https://pypi.org/project/bounter) (📥 170 / month):
  ```
  pip install bounter
  ```

</details>
<details><summary><b><a href="https://github.com/polyaxon/datatile">Pandas Summary</a></b> (🥉16 ·  ⭐ 430) - pandas Dataframe的describe函数功能扩展。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/polyaxon/datatile) ⭐ 534 | 🐛 7 | 🌐 Python | 📅 2026-08-15 (👨‍💻 8 · 🔀 39 · 📋 13 - 46% open · ⏱️ 14.08.2022):

  ```
  git clone https://github.com/mouradmourafiq/pandas-summary
  ```
* [PyPi](https://pypi.org/project/pandas-summary) (📥 46K / month):
  ```
  pip install pandas-summary
  ```

</details>
<details><summary><b><a href="https://github.com/firmai/pandapy">PandaPy</a></b> (🥉10 ·  ⭐ 510 · 💤) - PandaPy：具有NumPy的速度，性能高于pandas的表格数据实现。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/firmai/pandapy) ⭐ 547 | 🐛 2 | 🌐 Python | 📅 2021-10-20 (👨‍💻 3 · 🔀 58 · 📦 2 · 📋 2 - 50% open · ⏱️ 20.10.2021):

  ```
  git clone https://github.com/firmai/pandapy
  ```
* [PyPi](https://pypi.org/project/pandapy) (📥 71 / month):
  ```
  pip install pandapy
  ```

</details>
<br>

## 数据读写与提取

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于从各种数据源和格式加载，收集和提取数据的库。*

<details><summary><b><a href="https://github.com/joke2k/faker">Faker</a></b> (🥇37 ·  ⭐ 15K) - Faker是一个Python软件包，可为您生成伪造数据。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/joke2k/faker) ⭐ 19,375 | 🐛 31 | 🌐 Python | 📅 2026-08-21 (👨‍💻 470 · 🔀 1.6K · 📦 67K · 📋 580 - 2% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/joke2k/faker
  ```
* [PyPi](https://pypi.org/project/Faker) (📥 6.6M / month):
  ```
  pip install Faker
  ```
* [Conda](https://anaconda.org/conda-forge/faker) (📥 620K · ⏱️ 18.08.2022):
  ```
  conda install -c conda-forge faker
  ```

</details>
<details><summary><b><a href="https://github.com/huggingface/datasets">Datasets</a></b> (🥇32 ·  ⭐ 14K) - 具有ML模型的最大的即用型NLP数据集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/huggingface/datasets) ⭐ 21,853 | 🐛 1,296 | 🌐 Python | 📅 2026-08-18 (👨‍💻 440 · 🔀 1.8K · 📦 6K · 📋 1.7K - 26% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/huggingface/datasets
  ```
* [PyPi](https://pypi.org/project/datasets) (📥 1.2M / month):
  ```
  pip install datasets
  ```

</details>
<details><summary><b><a href="https://github.com/jazzband/tablib">Tablib</a></b> (🥇32 ·  ⭐ 4.2K) - 用于XLS，CSV，JSON，YAML和＆c中表格数据集的Python模块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jazzband/tablib) ⭐ 4,755 | 🐛 52 | 🌐 Python | 📅 2026-07-31 (👨‍💻 120 · 🔀 540 · 📦 15K · 📋 240 - 12% open · ⏱️ 11.07.2022):

  ```
  git clone https://github.com/jazzband/tablib
  ```
* [PyPi](https://pypi.org/project/tablib) (📥 1.2M / month):
  ```
  pip install tablib
  ```
* [Conda](https://anaconda.org/conda-forge/tablib) (📥 75K · ⏱️ 09.04.2022):
  ```
  conda install -c conda-forge tablib
  ```

</details>
<details><summary><b><a href="https://github.com/martinblech/xmltodict">xmltodict</a></b> (🥈31 ·  ⭐ 4.9K) - 像处理JSON一样处理XML。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/martinblech/xmltodict) ⭐ 5,750 | 🐛 5 | 🌐 Python | 📅 2026-08-19 (👨‍💻 49 · 🔀 430 · 📦 42K · 📋 220 - 27% open · ⏱️ 08.05.2022):

  ```
  git clone https://github.com/martinblech/xmltodict
  ```
* [PyPi](https://pypi.org/project/xmltodict) (📥 18M / month):
  ```
  pip install xmltodict
  ```
* [Conda](https://anaconda.org/conda-forge/xmltodict) (📥 1.9M · ⏱️ 08.05.2022):
  ```
  conda install -c conda-forge xmltodict
  ```

</details>
<details><summary><b><a href="https://github.com/ahupp/python-magic">python-magic</a></b> (🥈29 ·  ⭐ 2.2K) - 用于libmagic的python包装器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ahupp/python-magic) ⭐ 2,917 | 🐛 27 | 🌐 Python | 📅 2026-07-20 (👨‍💻 55 · 🔀 240 · 📦 31K · 📋 180 - 15% open · ⏱️ 20.06.2022):

  ```
  git clone https://github.com/ahupp/python-magic
  ```
* [PyPi](https://pypi.org/project/python-magic) (📥 5.9M / month):
  ```
  pip install python-magic
  ```
* [Conda](https://anaconda.org/conda-forge/python-magic) (📥 160K · ⏱️ 10.06.2022):
  ```
  conda install -c conda-forge python-magic
  ```

</details>
<details><summary><b><a href="https://github.com/python-excel/xlrd">xlrd</a></b> (🥈29 ·  ⭐ 2K · 💤) - xlrd是python语言中用于读取excel表格内容的库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/python-excel/xlrd) ⭐ 2,206 | 🐛 3 | 🌐 Python | 📅 2026-07-15 (👨‍💻 51 · 🔀 420 · 📦 100K · ⏱️ 21.08.2021):

  ```
  git clone https://github.com/python-excel/xlrd
  ```
* [PyPi](https://pypi.org/project/xlrd) (📥 18M / month):
  ```
  pip install xlrd
  ```
* [Conda](https://anaconda.org/conda-forge/xlrd) (📥 2.6M · ⏱️ 09.01.2021):
  ```
  conda install -c conda-forge xlrd
  ```

</details>
<details><summary><b><a href="https://github.com/wireservice/csvkit">csvkit</a></b> (🥈28 ·  ⭐ 5.1K) - 一套实用工具，可转换为CSV并操作。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/wireservice/csvkit) ⭐ 6,409 | 🐛 40 | 🌐 Python | 📅 2026-08-03 (👨‍💻 100 · 🔀 560 · 📦 1.1K · 📋 860 - 8% open · ⏱️ 11.04.2022):

  ```
  git clone https://github.com/wireservice/csvkit
  ```
* [PyPi](https://pypi.org/project/csvkit) (📥 160K / month):
  ```
  pip install csvkit
  ```
* [Conda](https://anaconda.org/conda-forge/csvkit) (📥 67K · ⏱️ 20.03.2022):
  ```
  conda install -c conda-forge csvkit
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥈28 ·  ⭐ 3.4K) - TFDS是一个高级数据集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/datasets) ⭐ 4,580 | 🐛 688 | 🌐 Python | 📅 2026-08-21 (👨‍💻 260 · 🔀 1.3K · 📋 980 - 36% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/tensorflow/datasets
  ```
* [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.2M / month):
  ```
  pip install tensorflow-datasets
  ```

</details>
<details><summary><b><a href="https://github.com/euske/pdfminer">PDFMiner</a></b> (🥈26 ·  ⭐ 4.9K · 💀) - Python PDF解析器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/euske/pdfminer) ⚠️ Archived (👨‍💻 28 · 🔀 980 · 📦 3.2K · 📋 240 - 82% open · ⏱️ 18.01.2020):

  ```
  git clone https://github.com/euske/pdfminer
  ```
* [PyPi](https://pypi.org/project/pdfminer) (📥 120K / month):
  ```
  pip install pdfminer
  ```
* [Conda](https://anaconda.org/conda-forge/pdfminer) (📥 24K · ⏱️ 15.02.2021):
  ```
  conda install -c conda-forge pdfminer
  ```

</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/smart_open">smart-open</a></b> (🥈26 ·  ⭐ 2.6K) - 用于大文件（S3，HDFS，gzip，bz2 ...）流传输的实用程序。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/RaRe-Technologies/smart_open) ⭐ 3,456 | 🐛 3 | 🌐 Python | 📅 2026-08-04 (👨‍💻 96 · 🔀 310 · 📋 360 - 16% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/RaRe-Technologies/smart_open
  ```
* [PyPi](https://pypi.org/project/smart-open) (📥 11M / month):
  ```
  pip install smart-open
  ```

</details>
<details><summary><b><a href="https://github.com/snorkel-team/snorkel">snorkel</a></b> (🥉25 ·  ⭐ 5.2K) - 在弱监督环境下快速生成训练数据的系统。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/snorkel-team/snorkel) ⭐ 5,999 | 🐛 19 | 🌐 Python | 📅 2026-06-08 (👨‍💻 78 · 🔀 820 · 📥 980 · 📦 190 · 📋 970 - 1% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/snorkel-team/snorkel
  ```
* [PyPi](https://pypi.org/project/snorkel) (📥 65K / month):
  ```
  pip install snorkel
  ```
* [Conda](https://anaconda.org/conda-forge/snorkel) (📥 30K · ⏱️ 29.07.2022):
  ```
  conda install -c conda-forge snorkel
  ```

</details>
<details><summary><b><a href="https://github.com/intake/intake">Intake</a></b> (🥉24 ·  ⭐ 800) - Intake是一个轻量级的程序包，用于查找，调查，加载等。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/intake/intake) ⭐ 1,084 | 🐛 115 | 🌐 Python | 📅 2026-06-18 (👨‍💻 78 · 🔀 120 · 📦 480 · 📋 310 - 27% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/intake/intake
  ```
* [PyPi](https://pypi.org/project/intake) (📥 21K / month):
  ```
  pip install intake
  ```
* [Conda](https://anaconda.org/conda-forge/intake) (📥 220K · ⏱️ 10.01.2022):
  ```
  conda install -c conda-forge intake
  ```

</details>
<details><summary><b><a href="https://github.com/deanmalmgren/textract">textract</a></b> (🥉23 ·  ⭐ 3.3K) - 从任何文档中提取文本。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/deanmalmgren/textract) ⭐ 4,696 | 🐛 70 | 🌐 HTML | 📅 2026-08-21 (👨‍💻 40 · 🔀 470 · 📋 210 - 39% open · ⏱️ 10.03.2022):

  ```
  git clone https://github.com/deanmalmgren/textract
  ```
* [PyPi](https://pypi.org/project/textract) (📥 120K / month):
  ```
  pip install textract
  ```
* [Conda](https://anaconda.org/conda-forge/textract) (📥 16K · ⏱️ 10.03.2022):
  ```
  conda install -c conda-forge textract
  ```

</details>
<details><summary><b><a href="https://github.com/sdv-dev/SDV">SDV</a></b> (🥉23 ·  ⭐ 980) - 用于表格，关系和时间序列数据的综合数据生成。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/sdv-dev/SDV) ⭐ 3,548 | 🐛 162 | 🌐 Python | 📅 2026-08-21 (👨‍💻 41 · 🔀 160 · 📦 81 · 📋 580 - 20% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/sdv-dev/SDV
  ```
* [PyPi](https://pypi.org/project/sdv) (📥 33K / month):
  ```
  pip install sdv
  ```

</details>
<details><summary><b><a href="https://github.com/frictionlessdata/tabulator-py">tabulator-py</a></b> (🥉22 ·  ⭐ 230 · 💀) - 用于读取和写入图像数据的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/frictionlessdata/tabulator-py) ⚠️ Archived (👨‍💻 27 · 🔀 42 · 📦 830 · ⏱️ 22.03.2021):

  ```
  git clone https://github.com/frictionlessdata/tabulator-py
  ```
* [PyPi](https://pypi.org/project/tabulator) (📥 210K / month):
  ```
  pip install tabulator
  ```
* [Conda](https://anaconda.org/conda-forge/tabulator-py) (📥 48K · ⏱️ 24.07.2018):
  ```
  conda install -c conda-forge tabulator-py
  ```

</details>
<details><summary><b><a href="https://github.com/pyexcel/pyexcel-xlsx">pyexcel-xlsx</a></b> (🥉22 ·  ⭐ 110 · 💀) - 一个包装器库，用于在xlsx和xlsm等文件格式中读取，操作和写入数据。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/pyexcel/pyexcel-xlsx) ⭐ 121 | 🐛 3 | 🌐 Python | 📅 2026-07-01 (👨‍💻 4 · 🔀 23 · 📥 51 · 📦 1.7K · 📋 34 - 26% open · ⏱️ 28.11.2020):

  ```
  git clone https://github.com/pyexcel/pyexcel-xlsx
  ```
* [PyPi](https://pypi.org/project/pyexcel-xlsx) (📥 88K / month):
  ```
  pip install pyexcel-xlsx
  ```
* [Conda](https://anaconda.org/conda-forge/pyexcel-xlsx) (📥 21K · ⏱️ 10.10.2020):
  ```
  conda install -c conda-forge pyexcel-xlsx
  ```

</details>
<details><summary><b><a href="https://github.com/okfn/messytables">messytables</a></b> (🥉21 ·  ⭐ 380 · 💀) - 解析混乱的表格数据的工具。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/okfn/messytables) ⭐ 394 | 🐛 37 | 🌐 HTML | 📅 2023-05-22 (👨‍💻 44 · 🔀 100 · 📦 250 · 📋 85 - 35% open · ⏱️ 13.11.2019):

  ```
  git clone https://github.com/okfn/messytables
  ```
* [PyPi](https://pypi.org/project/messytables) (📥 10K / month):
  ```
  pip install messytables
  ```

</details>
<details><summary><b><a href="https://github.com/turicas/rows">rows</a></b> (🥉20 ·  ⭐ 810) - 通用美观的表格数据界面。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

* [GitHub](https://github.com/turicas/rows) ⭐ 886 | 🐛 160 | 🌐 Python | 📅 2026-08-08 (👨‍💻 31 · 🔀 140 · 📥 38 · 📦 140 · 📋 290 - 49% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/turicas/rows
  ```
* [PyPi](https://pypi.org/project/rows) (📥 880 / month):
  ```
  pip install rows
  ```

</details>
<details><summary><b><a href="https://github.com/atlanhq/camelot">Camelot</a></b> (🥉19 ·  ⭐ 3.3K · 💀) - Camelot：简单的PDF表提取。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/atlanhq/camelot) ⚠️ Archived (👨‍💻 23 · 🔀 330 · 📋 360 - 23% open · ⏱️ 15.10.2019):

  ```
  git clone https://github.com/atlanhq/camelot
  ```
* [PyPi](https://pypi.org/project/camelot-py) (📥 79K / month):
  ```
  pip install camelot-py
  ```

</details>
<details><summary><b><a href="https://github.com/pydata/pandas-datareader">pandas-datareader</a></b> (🥉19 ·  ⭐ 2.4K) - 从各种各样的网络来源中提取数据。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pydata/pandas-datareader) ⭐ 3,238 | 🐛 146 | 🌐 Python | 📅 2026-07-21 (👨‍💻 85 · 🔀 590 · 📋 500 - 20% open · ⏱️ 16.03.2022):

  ```
  git clone https://github.com/pydata/pandas-datareader
  ```
* [PyPi](https://pypi.org/project/pandas-datareader) (📥 320K / month):
  ```
  pip install pandas-datareader
  ```
* [Conda](https://anaconda.org/conda-forge/pandas-datareader) (📥 190K · ⏱️ 14.07.2021):
  ```
  conda install -c conda-forge pandas-datareader
  ```

</details>
<details><summary><b><a href="https://github.com/shawnbrown/datatest">datatest</a></b> (🥉19 ·  ⭐ 260 · 💤) - 用于测试驱动的数据整理和数据验证的工具。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/shawnbrown/datatest) ⭐ 295 | 🐛 15 | 🌐 Python | 📅 2021-12-05 (👨‍💻 7 · 🔀 13 · 📦 74 · 📋 55 - 21% open · ⏱️ 05.12.2021):

  ```
  git clone https://github.com/shawnbrown/datatest
  ```
* [PyPi](https://pypi.org/project/datatest) (📥 8.3K / month):
  ```
  pip install datatest
  ```

</details>
<details><summary><b><a href="https://github.com/singer-io/getting-started">Singer</a></b> (🥉17 ·  ⭐ 1K · 💀) - 在数据库，Web API，文件，队列等之间移动数据的标准。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/singer-io/getting-started) ⭐ 1,345 | 🐛 29 | 🌐 Makefile | 📅 2025-08-08 (👨‍💻 26 · 🔀 140 · 📋 38 - 52% open · ⏱️ 29.04.2021):

  ```
  git clone https://github.com/singer-io/getting-started
  ```
* [PyPi](https://pypi.org/project/singer-python) (📥 270K / month):
  ```
  pip install singer-python
  ```

</details>
<details><summary><b><a href="https://foss.heptapod.net/openpyxl/openpyxl">openpyxl</a></b> (🥉16 ·  ⭐ 45) - 一个用于读取/写入Excel 2010 xlsx/xlsm文件的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [PyPi](https://pypi.org/project/openpyxl) (📥 35M / month):
  ```
  pip install openpyxl
  ```
* [GitLab](https://foss.heptapod.net/openpyxl/openpyxl) (🔀 0 · 📋 1.9K - 12% open · ⏱️ 07.07.2022):

  ```
  git clone https://foss.heptapod.net/openpyxl/openpyxl
  ```
* [Conda](https://anaconda.org/anaconda/openpyxl) (📥 98K · ⏱️ 07.07.2022):
  ```
  conda install -c anaconda openpyxl
  ```
* [Docker Hub](https://hub.docker.com/r/openpyxl/openpyxl-ci) (📥 1.2K · ⏱️ 13.09.2018):
  ```
  docker pull openpyxl/openpyxl-ci
  ```

</details>
<br>

## 网页抓取和爬虫

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于Web抓取、爬虫，下载和挖掘的库以及库。*

🔗 <b><a href="https://github.com/ml-tooling/best-of-web-python">Python Web Scraping</a></b> ( ⭐ 1.6K)  - Collection of web-scraping and crawling libraries.

<br>

## 数据管道和流处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于数据批处理和流处理，工作流自动化，作业调度和其他数据管道任务的库。*

<details><summary><b><a href="https://github.com/celery/celery">Celery</a></b> (🥇36 ·  ⭐ 20K) - 基于分布式消息传递的异步任务队列/作业队列。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/celery/celery) ⭐ 28,815 | 🐛 795 | 🌐 Python | 📅 2026-08-22 (👨‍💻 1.2K · 🔀 4.2K · 📦 75K · 📋 4.7K - 10% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/celery/celery
  ```
* [PyPi](https://pypi.org/project/celery) (📥 5.9M / month):
  ```
  pip install celery
  ```
* [Conda](https://anaconda.org/conda-forge/celery) (📥 930K · ⏱️ 29.05.2022):
  ```
  conda install -c conda-forge celery
  ```

</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇34 ·  ⭐ 16K) - Luigi是一个Python模块，可帮助您构建复杂的批处理管道。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/spotify/luigi) ⭐ 18,765 | 🐛 169 | 🌐 Python | 📅 2026-07-18 (👨‍💻 590 · 🔀 2.3K · 📦 1.8K · 📋 940 - 7% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/spotify/luigi
  ```
* [PyPi](https://pypi.org/project/luigi) (📥 670K / month):
  ```
  pip install luigi
  ```
* [Conda](https://anaconda.org/anaconda/luigi) (📥 11K · ⏱️ 02.05.2022):
  ```
  conda install -c anaconda luigi
  ```

</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥇33 ·  ⭐ 2.9K) - 使用Python函数进行计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/joblib/joblib) ⭐ 4,386 | 🐛 435 | 🌐 Python | 📅 2026-08-19 (👨‍💻 110 · 🔀 330 · 📦 210K · 📋 710 - 43% open · ⏱️ 20.05.2022):

  ```
  git clone https://github.com/joblib/joblib
  ```
* [PyPi](https://pypi.org/project/joblib) (📥 23M / month):
  ```
  pip install joblib
  ```
* [Conda](https://anaconda.org/conda-forge/joblib) (📥 11M · ⏱️ 07.10.2021):
  ```
  conda install -c conda-forge joblib
  ```

</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇32 ·  ⭐ 8.5K) - 适用于Python的简单作业队列。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/rq/rq) ⭐ 10,670 | 🐛 251 | 🌐 Python | 📅 2026-08-22 (👨‍💻 270 · 🔀 1.3K · 📦 11K · 📋 980 - 19% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/rq/rq
  ```
* [PyPi](https://pypi.org/project/rq) (📥 680K / month):
  ```
  pip install rq
  ```
* [Conda](https://anaconda.org/conda-forge/rq) (📥 76K · ⏱️ 30.06.2021):
  ```
  conda install -c conda-forge rq
  ```

</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥇32 ·  ⭐ 5.3K) - 用于机器学习，分析和ETL的数据协调器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/dagster-io/dagster) ⭐ 16,052 | 🐛 2,595 | 🌐 Python | 📅 2026-08-22 (👨‍💻 230 · 🔀 650 · 📦 500 · 📋 4.4K - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/dagster-io/dagster
  ```
* [PyPi](https://pypi.org/project/dagster) (📥 480K / month):
  ```
  pip install dagster
  ```
* [Conda](https://anaconda.org/conda-forge/dagster) (📥 610K · ⏱️ 12.08.2022):
  ```
  conda install -c conda-forge dagster
  ```

</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥈31 ·  ⭐ 5.8K) - 统一的编程模型，用于定义和执行数据处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/beam) ⭐ 8,647 | 🐛 3,970 | 🌐 Java | 📅 2026-08-23 (👨‍💻 1.3K · 🔀 3.5K · 📋 4.4K - 89% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/apache/beam
  ```
* [PyPi](https://pypi.org/project/apache-beam) (📥 6.6M / month):
  ```
  pip install apache-beam
  ```

</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt-core">dbt</a></b> (🥈30 ·  ⭐ 5.4K) - dbt（数据构建工具）方便数据分析人员和工程师快速使用。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/dbt-labs/dbt-core) ⭐ 13,682 | 🐛 1,565 | 🌐 Rust | 📅 2026-08-23 (👨‍💻 230 · 🔀 960 · 📥 520 · 📦 660 · 📋 3K - 10% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/fishtown-analytics/dbt
  ```
* [PyPi](https://pypi.org/project/dbt) (📥 170K / month):
  ```
  pip install dbt
  ```
* [Conda](https://anaconda.org/conda-forge/dbt) (📥 210K · ⏱️ 09.12.2021):
  ```
  conda install -c conda-forge dbt
  ```

</details>
<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥈29 ·  ⭐ 28K) - 代码实现的创建，安排和监视工作流的平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/airflow) ⭐ 46,587 | 🐛 1,921 | 🌐 Python | 📅 2026-08-23 (👨‍💻 2.5K · 🔀 11K · 📥 340K · 📋 6K - 11% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/apache/airflow
  ```
* [PyPi](https://pypi.org/project/apache-airflow) (📥 8.9M / month):
  ```
  pip install apache-airflow
  ```
* [Conda](https://anaconda.org/conda-forge/airflow) (📥 700K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge airflow
  ```
* [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 82M · ⭐ 380 · ⏱️ 23.08.2022):
  ```
  docker pull apache/airflow
  ```

</details>
<details><summary><b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈29 ·  ⭐ 2.6K · 💀) - 在Hadoop或Amazon Web Services上运行MapReduce作业。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Yelp/mrjob) ⭐ 2,613 | 🐛 217 | 🌐 Python | 📅 2026-04-02 (👨‍💻 140 · 🔀 580 · 📦 1.1K · 📋 1.3K - 15% open · ⏱️ 16.11.2020):

  ```
  git clone https://github.com/Yelp/mrjob
  ```
* [PyPi](https://pypi.org/project/mrjob) (📥 76K / month):
  ```
  pip install mrjob
  ```
* [Conda](https://anaconda.org/conda-forge/mrjob) (📥 490K · ⏱️ 06.02.2022):
  ```
  conda install -c conda-forge mrjob
  ```

</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥈28 ·  ⭐ 9.9K) - 自动化数据的最简单方法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PrefectHQ/prefect) ⭐ 23,661 | 🐛 855 | 🌐 Python | 📅 2026-08-23 (👨‍💻 60 · 🔀 950 · 📦 1.1K · 📋 2.6K - 25% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/PrefectHQ/prefect
  ```
* [PyPi](https://pypi.org/project/prefect) (📥 400K / month):
  ```
  pip install prefect
  ```
* [Conda](https://anaconda.org/conda-forge/prefect) (📥 310K · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge prefect
  ```

</details>
<details><summary><b><a href="https://github.com/kedro-org/kedro">Kedro</a></b> (🥈28 ·  ⭐ 7.5K) - 用于创建可重现，可维护和模块化的Python框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/kedro-org/kedro) ⭐ 10,964 | 🐛 146 | 🌐 Python | 📅 2026-08-21 (👨‍💻 160 · 🔀 680 · 📦 1K · 📋 870 - 17% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/quantumblacklabs/kedro
  ```
* [PyPi](https://pypi.org/project/kedro) (📥 420K / month):
  ```
  pip install kedro
  ```

</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈28 ·  ⭐ 1K) - Python提取转换并加载数据表。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/petl-developers/petl) ⭐ 1,315 | 🐛 88 | 🌐 Python | 📅 2026-08-19 (👨‍💻 55 · 🔀 170 · 📦 790 · 📋 440 - 16% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/petl-developers/petl
  ```
* [PyPi](https://pypi.org/project/petl) (📥 280K / month):
  ```
  pip install petl
  ```
* [Conda](https://anaconda.org/conda-forge/petl) (📥 120K · ⏱️ 22.08.2022):
  ```
  conda install -c conda-forge petl
  ```

</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥈26 ·  ⭐ 2.1K) - 用于创建具有链功能的数据管道的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/EntilZha/PyFunctional) ⭐ 2,488 | 🐛 12 | 🌐 Python | 📅 2025-03-13 (👨‍💻 26 · 🔀 110 · 📦 460 · 📋 130 - 5% open · ⏱️ 05.08.2022):

  ```
  git clone https://github.com/EntilZha/PyFunctional
  ```
* [PyPi](https://pypi.org/project/pyfunctional) (📥 230K / month):
  ```
  pip install pyfunctional
  ```

</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥈25 ·  ⭐ 7.1K) - 通过数据测试，文档编制和性能分析，帮助数据团队加速流水线效率。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/great-expectations/great_expectations) ⭐ 11,730 | 🐛 39 | 🌐 Python | 📅 2026-08-21 (👨‍💻 320 · 🔀 1K · 📋 1.4K - 12% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/great-expectations/great_expectations
  ```
* [PyPi](https://pypi.org/project/great_expectations) (📥 5.3M / month):
  ```
  pip install great_expectations
  ```

</details>
<details><summary><b><a href="https://github.com/robinhood/faust">faust</a></b> (🥈25 ·  ⭐ 6.3K · 💀) - Python流处理。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/robinhood/faust) ⭐ 6,824 | 🐛 279 | 🌐 Python | 📅 2024-07-27 (👨‍💻 94 · 🔀 530 · 📦 1.1K · 📋 460 - 48% open · ⏱️ 09.10.2020):

  ```
  git clone https://github.com/robinhood/faust
  ```
* [PyPi](https://pypi.org/project/faust) (📥 32K / month):
  ```
  pip install faust
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈25 ·  ⭐ 1.8K) - TFX是用于部署机器学习生产流水线的端到端平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/tfx) ⭐ 2,190 | 🐛 270 | 🌐 Python | 📅 2026-08-17 (👨‍💻 150 · 🔀 580 · 📋 780 - 26% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/tensorflow/tfx
  ```
* [PyPi](https://pypi.org/project/tfx) (📥 370K / month):
  ```
  pip install tfx
  ```

</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥉24 ·  ⭐ 2.6K) - 精益数据科学工作流程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ploomber/ploomber) ⚠️ Archived (👨‍💻 59 · 🔀 180 · 📦 51 · 📋 790 - 25% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/ploomber/ploomber
  ```
* [PyPi](https://pypi.org/project/ploomber) (📥 15K / month):
  ```
  pip install ploomber
  ```

</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉24 ·  ⭐ 1.5K) - 在Apache Storm拓扑中运行Python。 Pythonic API，CLI 等。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Parsely/streamparse) ⭐ 1,505 | 🐛 61 | 🌐 Python | 📅 2026-04-22 (👨‍💻 43 · 🔀 210 · 📦 55 · 📋 330 - 19% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/Parsely/streamparse
  ```
* [PyPi](https://pypi.org/project/streamparse) (📥 2.2K / month):
  ```
  pip install streamparse
  ```

</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Hub</a></b> (🥉23 ·  ⭐ 4.8K) - TensorFlow/PyTorch最快的非结构化数据集管理。<code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/activeloopai/Hub) ⭐ 9,227 | 🐛 66 | 🌐 C++ | 📅 2026-05-21 (👨‍💻 99 · 🔀 390 · 📋 380 - 11% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/activeloopai/Hub
  ```
* [PyPi](https://pypi.org/project/hub) (📥 3.7K / month):
  ```
  pip install hub
  ```

</details>
<details><summary><b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - 提取适用于Python 3.5+的Transform Load。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/python-bonobo/bonobo) ⭐ 1,613 | 🐛 107 | 🌐 Python | 📅 2023-05-12 (👨‍💻 37 · 🔀 130 · 📦 140 · 📋 180 - 39% open · ⏱️ 10.03.2021):

  ```
  git clone https://github.com/python-bonobo/bonobo
  ```
* [PyPi](https://pypi.org/project/bonobo) (📥 7.3K / month):
  ```
  pip install bonobo
  ```

</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉21 ·  ⭐ 1.2K) - 使用Redis的Python任务队列。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/closeio/tasktiger) ⭐ 1,466 | 🐛 50 | 🌐 Python | 📅 2026-08-18 (👨‍💻 24 · 🔀 64 · 📦 23 · 📋 58 - 37% open · ⏱️ 25.04.2022):

  ```
  git clone https://github.com/closeio/tasktiger
  ```
* [PyPi](https://pypi.org/project/tasktiger) (📥 1.5K / month):
  ```
  pip install tasktiger
  ```

</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉21 ·  ⭐ 680) - pandas DataFrames的简单管道。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pdpipe/pdpipe) ⭐ 729 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2026-08-01 (👨‍💻 10 · 🔀 42 · 📦 41 · 📋 51 - 31% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/pdpipe/pdpipe
  ```
* [PyPi](https://pypi.org/project/pdpipe) (📥 1.7K / month):
  ```
  pip install pdpipe
  ```

</details>
<details><summary><b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉20 ·  ⭐ 2.7K · 💀) - dpark是Python中与MapReduce相似的框架。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/douban/dpark) ⚠️ Archived (👨‍💻 35 · 🔀 540 · 📦 5 · 📋 61 - 1% open · ⏱️ 25.12.2020):

  ```
  git clone https://github.com/douban/dpark
  ```
* [PyPi](https://pypi.org/project/dpark) (📥 32 / month):
  ```
  pip install dpark
  ```

</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥉20 ·  ⭐ 2.3K) - ZenML：MLOps框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/zenml-io/zenml) ⭐ 5,560 | 🐛 157 | 🌐 Python | 📅 2026-08-23 (👨‍💻 46 · 🔀 190 · 📋 110 - 22% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/maiot-io/zenml
  ```
* [PyPi](https://pypi.org/project/zenml) (📥 2.5K / month):
  ```
  pip install zenml
  ```

</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉20 ·  ⭐ 1.4K) - Python中的并发数据管道。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/cgarciae/pypeln) ⭐ 1,596 | 🐛 35 | 🌐 Python | 📅 2023-07-20 (👨‍💻 13 · 🔀 80 · 📋 59 - 25% open · ⏱️ 23.06.2022):

  ```
  git clone https://github.com/cgarciae/pypeln
  ```
* [PyPi](https://pypi.org/project/pypeln) (📥 8.3K / month):
  ```
  pip install pypeln
  ```

</details>
<details><summary><b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉20 ·  ⭐ 250 · 💀) - Apache Spark的RDD和DStream的纯Python实现。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/svenkreiss/pysparkling) ⭐ 270 | 🐛 11 | 🌐 Python | 📅 2024-09-03 (👨‍💻 10 · 🔀 42 · 📦 120 · 📋 27 - 22% open · ⏱️ 22.02.2021):

  ```
  git clone https://github.com/svenkreiss/pysparkling
  ```
* [PyPi](https://pypi.org/project/pysparkling) (📥 13K / month):
  ```
  pip install pysparkling
  ```

</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉19 ·  ⭐ 1.2K) - 基于pandas、dask等的敏捷数据预处理工作流程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/hi-primus/optimus) ⭐ 1,536 | 🐛 30 | 🌐 Python | 📅 2024-12-02 (👨‍💻 23 · 🔀 210 · 📋 230 - 14% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/ironmussa/Optimus
  ```
* [PyPi](https://pypi.org/project/optimuspyspark) (📥 52K / month):
  ```
  pip install optimuspyspark
  ```

</details>
<details><summary><b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉19 ·  ⭐ 870 · 💀) - Mr. Queue - 使用Redis和gevent的Python中的分布式worker任务队列。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pricingassistant/mrq) ⭐ 892 | 🐛 63 | 🌐 Python | 📅 2023-06-13 (👨‍💻 40 · 🔀 110 · 📦 29 · 📋 170 - 30% open · ⏱️ 13.12.2020):

  ```
  git clone https://github.com/pricingassistant/mrq
  ```
* [PyPi](https://pypi.org/project/mrq) (📥 130 / month):
  ```
  pip install mrq
  ```

</details>
<details><summary><b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉19 ·  ⭐ 180) - BatchFlow可帮助您方便地使用随机或顺序调度数据进行机器学习任务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/analysiscenter/batchflow) ⭐ 205 | 🐛 44 | 🌐 Python | 📅 2026-07-10 (👨‍💻 32 · 🔀 40 · 📦 2 · 📋 100 - 28% open · ⏱️ 03.08.2022):

  ```
  git clone https://github.com/analysiscenter/batchflow
  ```
* [PyPi](https://pypi.org/project/batchflow) (📥 140 / month):
  ```
  pip install batchflow
  ```

</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉17 ·  ⭐ 1.9K) - 适用于Apache Spark的深度学习管道。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/databricks/spark-deep-learning) ⭐ 1,987 | 🐛 87 | 🌐 Python | 📅 2023-03-30 (👨‍💻 17 · 🔀 460 · 📦 24 · 📋 100 - 74% open · ⏱️ 21.03.2022):

  ```
  git clone https://github.com/databricks/spark-deep-learning
  ```

</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 1.9K) - 一个轻量级的ETL框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mara/mara-pipelines) ⭐ 2,089 | 🐛 26 | 🌐 Python | 📅 2023-12-15 (👨‍💻 17 · 🔀 89 · 📋 30 - 53% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/mara/mara-pipelines
  ```
* [PyPi](https://pypi.org/project/mara-pipelines) (📥 360 / month):
  ```
  pip install mara-pipelines
  ```

</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉15 ·  ⭐ 1.6K · 💤) - 一个模仿Yahoo!的Python流处理引擎。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/nerevu/riko) ⭐ 1,606 | 🐛 24 | 🌐 Python | 📅 2026-08-22 (👨‍💻 18 · 🔀 68 · 📋 29 - 72% open · ⏱️ 28.12.2021):

  ```
  git clone https://github.com/nerevu/riko
  ```
* [PyPi](https://pypi.org/project/riko) (📥 30 / month):
  ```
  pip install riko
  ```

</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉15 ·  ⭐ 940 · 💤) - Python库，用于构建高效的数据科学工作流程。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/d6t/d6tflow) ⭐ 948 | 🐛 11 | 🌐 Python | 📅 2026-06-28 (👨‍💻 12 · 🔀 71 · 📦 20 · 📋 23 - 43% open · ⏱️ 28.09.2021):

  ```
  git clone https://github.com/d6t/d6tflow
  ```
* [PyPi](https://pypi.org/project/d6tflow) (📥 120 / month):
  ```
  pip install d6tflow
  ```

</details>
<details><summary><b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉14 ·  ⭐ 170) - python中的流利数据管道。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/olirice/flupy) ⭐ 195 | 🐛 0 | 🌐 Python | 📅 2026-07-26 (👨‍💻 6 · 🔀 12 · ⏱️ 17.02.2022):

  ```
  git clone https://github.com/olirice/flupy
  ```
* [PyPi](https://pypi.org/project/flupy) (📥 73K / month):
  ```
  pip install flupy
  ```

</details>
<details><summary><b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉13 ·  ⭐ 400) - MLOps工具，用于将机器学习项目部署到Kubernetes。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/bodywork-ml/bodywork-core) ⚠️ Archived (👨‍💻 4 · 🔀 18 · 📦 10 · 📋 77 - 25% open · ⏱️ 04.07.2022):

  ```
  git clone https://github.com/bodywork-ml/bodywork-core
  ```
* [PyPi](https://pypi.org/project/bodywork-core):
  ```
  pip install bodywork-core
  ```

</details>
<details><summary><b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉12 ·  ⭐ 1.2K · 💀) - 适用于数据管道工作的Python快速数据流编程框架。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/kkyon/botflow) ⭐ 1,196 | 🐛 4 | 🌐 Python | 📅 2026-02-03 (👨‍💻 11 · 🔀 100 · 📦 1 · 📋 5 - 60% open · ⏱️ 23.05.2019):

  ```
  git clone https://github.com/kkyon/botflow
  ```
* [PyPi](https://pypi.org/project/botflow) (📥 23 / month):
  ```
  pip install botflow
  ```

</details>
<br>

## 分布式机器学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*提供在大型计算基础架构中分布和并行化机器学习任务的功能的库。*

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇35 ·  ⭐ 22K) - 一个开源代码框架，提供了用于构建分布式应用程序的简单通用API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ray-project/ray) ⭐ 43,585 | 🐛 3,518 | 🌐 Python | 📅 2026-08-23 (👨‍💻 740 · 🔀 3.7K · 📦 5.7K · 📋 11K - 21% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/ray-project/ray
  ```
* [PyPi](https://pypi.org/project/ray) (📥 1.8M / month):
  ```
  pip install ray
  ```

</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇32 ·  ⭐ 10K) - 具有任务调度的并行计算。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/dask/dask) ⭐ 13,894 | 🐛 1,312 | 🌐 Python | 📅 2026-08-17 (👨‍💻 550 · 🔀 1.5K · 📦 39K · 📋 4.4K - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/dask/dask
  ```
* [PyPi](https://pypi.org/project/dask) (📥 7.1M / month):
  ```
  pip install dask
  ```
* [Conda](https://anaconda.org/conda-forge/dask) (📥 6.4M · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge dask
  ```

</details>
<details><summary><b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥇30 ·  ⭐ 13K) - 基于TensorFlow，Keras，PyTorch，MXNet等的分布式训练框架。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/horovod/horovod) ⚠️ Archived (👨‍💻 160 · 🔀 2K · 📦 650 · 📋 2.1K - 15% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/horovod/horovod
  ```
* [PyPi](https://pypi.org/project/horovod) (📥 73K / month):
  ```
  pip install horovod
  ```

</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇30 ·  ⭐ 1.4K) - Dask的分布式任务调度规划程序。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/dask/distributed) ⭐ 1,679 | 🐛 1,511 | 🌐 Python | 📅 2026-08-23 (👨‍💻 280 · 🔀 620 · 📦 25K · 📋 2.9K - 33% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/dask/distributed
  ```
* [PyPi](https://pypi.org/project/distributed) (📥 4.9M / month):
  ```
  pip install distributed
  ```
* [Conda](https://anaconda.org/conda-forge/distributed) (📥 7.8M · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge distributed
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈28 ·  ⭐ 7.7K) - DeepSpeed是一个深度学习优化库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/microsoft/DeepSpeed) ⭐ 42,980 | 🐛 1,319 | 🌐 Python | 📅 2026-08-23 (👨‍💻 130 · 🔀 830 · 📦 340 · 📋 980 - 48% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/microsoft/DeepSpeed
  ```
* [PyPi](https://pypi.org/project/deepspeed) (📥 220K / month):
  ```
  pip install deepspeed
  ```
* [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 14K · ⭐ 3 · ⏱️ 06.06.2022):
  ```
  docker pull deepspeed/deepspeed
  ```

</details>
<details><summary><b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈27 ·  ⭐ 4.8K) - Python中的分布式进化算法。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code></summary>

* [GitHub](https://github.com/DEAP/deap) ⭐ 6,435 | 🐛 281 | 🌐 Python | 📅 2026-04-17 (👨‍💻 79 · 🔀 980 · 📦 2.8K · 📋 470 - 43% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/deap/deap
  ```
* [PyPi](https://pypi.org/project/deap) (📥 160K / month):
  ```
  pip install deap
  ```
* [Conda](https://anaconda.org/conda-forge/deap) (📥 200K · ⏱️ 08.08.2022):
  ```
  conda install -c conda-forge deap
  ```

</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈27 ·  ⭐ 1.5K) - Petastorm库单机或分布式训练。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/uber/petastorm) ⭐ 1,891 | 🐛 182 | 🌐 Python | 📅 2026-01-02 (👨‍💻 45 · 🔀 250 · 📥 340 · 📦 74 · 📋 280 - 49% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/uber/petastorm
  ```
* [PyPi](https://pypi.org/project/petastorm) (📥 63K / month):
  ```
  pip install petastorm
  ```

</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈26 ·  ⭐ 4K) - BigDL：适用于Apache Spark的分布式深度学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/intel-analytics/BigDL) ⚠️ Archived (👨‍💻 170 · 🔀 970 · 📦 38 · 📋 1.4K - 30% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/intel-analytics/BigDL
  ```
* [PyPi](https://pypi.org/project/bigdl) (📥 4K / month):
  ```
  pip install bigdl
  ```
* [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4):
  ```
  <dependency>
  	<groupId>com.intel.analytics.bigdl</groupId>
  	<artifactId>bigdl-SPARK_2.4</artifactId>
  	<version>[VERSION]</version>
  </dependency>
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈26 ·  ⭐ 1.8K) - PyTorch扩展用于高性能和大规模训练。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/fairscale) ⚠️ Archived (👨‍💻 63 · 🔀 180 · 📦 490 · 📋 320 - 21% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/facebookresearch/fairscale
  ```
* [PyPi](https://pypi.org/project/fairscale) (📥 230K / month):
  ```
  pip install fairscale
  ```

</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥈26 ·  ⭐ 1.5K) - 使用Keras和Spark进行分布式深度学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/maxpumperla/elephas) ⭐ 1,577 | 🐛 11 | 🌐 Python | 📅 2023-05-01 (👨‍💻 27 · 🔀 290 · 📦 56 · 📋 160 - 12% open · ⏱️ 30.03.2022):

  ```
  git clone https://github.com/maxpumperla/elephas
  ```
* [PyPi](https://pypi.org/project/elephas) (📥 120K / month):
  ```
  pip install elephas
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥈26 ·  ⭐ 1.3K) - Mesh TensorFlow：简化模型并行化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/mesh) ⚠️ Archived (👨‍💻 48 · 🔀 220 · 📦 710 · 📋 78 - 82% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/tensorflow/mesh
  ```
* [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 21K / month):
  ```
  pip install mesh-tensorflow
  ```

</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥉25 ·  ⭐ 820) - 使用Dask进行可扩展的机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/dask/dask-ml) ⭐ 951 | 🐛 283 | 🌐 Python | 📅 2025-09-27 (👨‍💻 76 · 🔀 230 · 📦 660 · 📋 440 - 45% open · ⏱️ 19.06.2022):

  ```
  git clone https://github.com/dask/dask-ml
  ```
* [PyPi](https://pypi.org/project/dask-ml) (📥 70K / month):
  ```
  pip install dask-ml
  ```
* [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 400K · ⏱️ 27.05.2022):
  ```
  conda install -c conda-forge dask-ml
  ```

</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥉23 ·  ⭐ 3.8K) - TensorFlowOnSpark将TensorFlow程序引入Spark。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/yahoo/TensorFlowOnSpark) ⭐ 3,845 | 🐛 16 | 🌐 Python | 📅 2023-07-10 (👨‍💻 34 · 🔀 920 · 📋 360 - 2% open · ⏱️ 21.04.2022):

  ```
  git clone https://github.com/yahoo/TensorFlowOnSpark
  ```
* [PyPi](https://pypi.org/project/tensorflowonspark) (📥 270K / month):
  ```
  pip install tensorflowonspark
  ```

</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉23 ·  ⭐ 2.5K) - Apache上的分布式Tensorflow，Keras和PyTorch。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/intel-analytics/analytics-zoo) ⚠️ Archived (👨‍💻 100 · 🔀 700 · 📦 3 · 📋 1.3K - 32% open · ⏱️ 01.06.2022):

  ```
  git clone https://github.com/intel-analytics/analytics-zoo
  ```
* [PyPi](https://pypi.org/project/analytics-zoo) (📥 2.2K / month):
  ```
  pip install analytics-zoo
  ```

</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉23 ·  ⭐ 1.1K) - PyTorch中的分布式深度学习。专为训练模型而设计。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/learning-at-home/hivemind) ⭐ 2,514 | 🐛 96 | 🌐 Python | 📅 2026-01-11 (👨‍💻 23 · 🔀 67 · 📦 10 · 📋 120 - 28% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/learning-at-home/hivemind
  ```
* [PyPi](https://pypi.org/project/hivemind) (📥 5.2K / month):
  ```
  pip install hivemind
  ```

</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉22 ·  ⭐ 570) - MPI的Python接口。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/mpi4py/mpi4py) ⭐ 920 | 🐛 4 | 🌐 Python | 📅 2026-08-23 (👨‍💻 21 · 🔀 78 · 📥 6.2K · 📋 84 - 11% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/mpi4py/mpi4py
  ```
* [PyPi](https://pypi.org/project/mpi4py) (📥 290K / month):
  ```
  pip install mpi4py
  ```
* [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 1.3M · ⏱️ 12.08.2022):
  ```
  conda install -c conda-forge mpi4py
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥉20 ·  ⭐ 3.5K) - 适用于Apache Spark的Microsoft机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/microsoft/SynapseML) ⭐ 5,238 | 🐛 144 | 🌐 Scala | 📅 2026-08-22 (👨‍💻 97 · 🔀 670 · 📋 570 - 39% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/Azure/mmlspark
  ```
* [PyPi](https://pypi.org/project/mmlspark) (📥 4 / month):
  ```
  pip install mmlspark
  ```

</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉19 ·  ⭐ 2.7K) - 分布式深度学习平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/apache/singa) ⭐ 3,606 | 🐛 55 | 🌐 C++ | 📅 2026-07-07 (👨‍💻 79 · 🔀 780 · 📦 1 · 📋 79 - 21% open · ⏱️ 01.06.2022):

  ```
  git clone https://github.com/apache/singa
  ```
* [Conda](https://anaconda.org/nusdbsystem/singa) (📥 510 · ⏱️ 09.08.2021):
  ```
  conda install -c nusdbsystem singa
  ```
* [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 690 · ⭐ 4 · ⏱️ 31.05.2022):
  ```
  docker pull apache/singa
  ```

</details>
<details><summary><b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉19 ·  ⭐ 760 · 💀) - 用于DataFrames的Tensorflow包装器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/databricks/tensorframes) ⭐ 744 | 🐛 54 | 🌐 Scala | 📅 2024-07-30 (👨‍💻 16 · 🔀 160 · 📋 92 - 53% open · ⏱️ 15.11.2019):

  ```
  git clone https://github.com/databricks/tensorframes
  ```
* [PyPi](https://pypi.org/project/tensorframes) (📥 40K / month):
  ```
  pip install tensorframes
  ```

</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉18 ·  ⭐ 2.3K) - Python中的交互式并行计算。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ipython/ipyparallel) ⭐ 2,647 | 🐛 74 | 🌐 Jupyter Notebook | 📅 2026-08-12 (👨‍💻 110 · 🔀 870 · 📋 330 - 15% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/ipython/ipyparallel
  ```
* [PyPi](https://pypi.org/project/ipyparallel) (📥 120K / month):
  ```
  pip install ipyparallel
  ```
* [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 670K · ⏱️ 21.06.2022):
  ```
  conda install -c conda-forge ipyparallel
  ```

</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉18 ·  ⭐ 680) - 用于将作业提交到Slurm的Python工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookincubator/submitit) ⭐ 1,635 | 🐛 62 | 🌐 Python | 📅 2026-01-14 (👨‍💻 23 · 🔀 74 · 📋 71 - 32% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/facebookincubator/submitit
  ```
* [PyPi](https://pypi.org/project/submitit) (📥 37K / month):
  ```
  pip install submitit
  ```
* [Conda](https://anaconda.org/conda-forge/submitit) (📥 8.1K · ⏱️ 10.02.2021):
  ```
  conda install -c conda-forge submitit
  ```

</details>
<details><summary><b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉18 ·  ⭐ 280 · 💀) - PySpark中的分布式scikit学习元估计器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Ibotta/sk-dist) ⚠️ Archived (👨‍💻 7 · 🔀 49 · 📦 10 · 📋 17 - 41% open · ⏱️ 07.07.2021):

  ```
  git clone https://github.com/Ibotta/sk-dist
  ```
* [PyPi](https://pypi.org/project/sk-dist) (📥 170K / month):
  ```
  pip install sk-dist
  ```

</details>
<details><summary><b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉17 ·  ⭐ 240 · 💤) - 大规模并行的自组织图：加速训练。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/peterwittek/somoclu) ⭐ 277 | 🐛 37 | 🌐 C | 📅 2025-12-20 (👨‍💻 19 · 🔀 62 · 📥 1.6K · 📋 130 - 18% open · ⏱️ 31.10.2021):

  ```
  git clone https://github.com/peterwittek/somoclu
  ```
* [PyPi](https://pypi.org/project/somoclu) (📥 980 / month):
  ```
  pip install somoclu
  ```
* [Conda](https://anaconda.org/conda-forge/somoclu) (📥 64K · ⏱️ 15.11.2021):
  ```
  conda install -c conda-forge somoclu
  ```

</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉16 ·  ⭐ 3.3K) - 分布式DNN训练的高性能通用框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/bytedance/byteps) ⚠️ Archived (👨‍💻 19 · 🔀 450 · 📋 260 - 38% open · ⏱️ 10.02.2022):

  ```
  git clone https://github.com/bytedance/byteps
  ```
* [PyPi](https://pypi.org/project/byteps) (📥 19 / month):
  ```
  pip install byteps
  ```
* [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.3K · ⏱️ 03.03.2020):
  ```
  docker pull bytepsimage/tensorflow
  ```

</details>
<details><summary><b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉16 ·  ⭐ 980 · 💀) - 简化了AI的分布式计算。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/uber/fiber) ⚠️ Archived (👨‍💻 5 · 🔀 110 · 📦 43 · 📋 25 - 68% open · ⏱️ 15.03.2021):

  ```
  git clone https://github.com/uber/fiber
  ```
* [PyPi](https://pypi.org/project/fiber) (📥 60 / month):
  ```
  pip install fiber
  ```

</details>
<details><summary><b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉13 ·  ⭐ 43 · 💤) - 分布式机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ml-tooling/lazycluster) ⚠️ Archived (👨‍💻 2 · 🔀 9 · 📦 17 · ⏱️ 19.08.2021):

  ```
  git clone https://github.com/ml-tooling/lazycluster
  ```
* [PyPi](https://pypi.org/project/lazycluster) (📥 42 / month):
  ```
  pip install lazycluster
  ```

</details>
<br>

## 超参数优化和AutoML

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于超参数优化，自动机器学习和神经体系结构搜索的库。*

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇34 ·  ⭐ 6.8K) - 超参数优化框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/optuna/optuna) ⭐ 14,689 | 🐛 16 | 🌐 Python | 📅 2026-08-21 (👨‍💻 200 · 🔀 730 · 📦 4K · 📋 1.2K - 7% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/optuna/optuna
  ```
* [PyPi](https://pypi.org/project/optuna) (📥 1.5M / month):
  ```
  pip install optuna
  ```
* [Conda](https://anaconda.org/conda-forge/optuna) (📥 320K · ⏱️ 06.07.2022):
  ```
  conda install -c conda-forge optuna
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇30 ·  ⭐ 12K) - 一个开源AutoML工具箱，用于自动化机器学习生命周期。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/nni) ⚠️ Archived (👨‍💻 180 · 🔀 1.6K · 📦 260 · 📋 1.7K - 17% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/microsoft/nni
  ```
* [PyPi](https://pypi.org/project/nni) (📥 10K / month):
  ```
  pip install nni
  ```

</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇30 ·  ⭐ 8.6K) - 用于深度学习的AutoML库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/keras-team/autokeras) ⭐ 9,326 | 🐛 160 | 🌐 Python | 📅 2025-11-25 (👨‍💻 140 · 🔀 1.3K · 📥 7.4K · 📦 350 · 📋 840 - 11% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/keras-team/autokeras
  ```
* [PyPi](https://pypi.org/project/autokeras) (📥 17K / month):
  ```
  pip install autokeras
  ```

</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥇30 ·  ⭐ 2.6K) - 简单易用的超参数调整。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/keras-team/keras-tuner) ⭐ 2,924 | 🐛 240 | 🌐 Python | 📅 2025-12-01 (👨‍💻 50 · 🔀 330 · 📦 1.6K · 📋 400 - 43% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/keras-team/keras-tuner
  ```
* [PyPi](https://pypi.org/project/keras-tuner) (📥 610K / month):
  ```
  pip install keras-tuner
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥇30 ·  ⭐ 2.4K · 💤) - SMBO模型优化实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/scikit-optimize/scikit-optimize) ⚠️ Archived (👨‍💻 76 · 🔀 420 · 📦 3K · 📋 600 - 35% open · ⏱️ 12.10.2021):

  ```
  git clone https://github.com/scikit-optimize/scikit-optimize
  ```
* [PyPi](https://pypi.org/project/scikit-optimize) (📥 790K / month):
  ```
  pip install scikit-optimize
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 570K · ⏱️ 15.12.2021):
  ```
  conda install -c conda-forge scikit-optimize
  ```

</details>
<details><summary><b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥈29 ·  ⭐ 8.7K) - Python自动化机器学习工具。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/EpistasisLab/tpot) ⭐ 10,051 | 🐛 312 | 🌐 Jupyter Notebook | 📅 2025-09-11 (👨‍💻 110 · 🔀 1.5K · 📦 1.6K · 📋 860 - 29% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/EpistasisLab/tpot
  ```
* [PyPi](https://pypi.org/project/tpot) (📥 41K / month):
  ```
  pip install tpot
  ```
* [Conda](https://anaconda.org/conda-forge/tpot) (📥 170K · ⏱️ 05.03.2021):
  ```
  conda install -c conda-forge tpot
  ```

</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥈29 ·  ⭐ 6.5K) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/automl/auto-sklearn) ⭐ 8,126 | 🐛 207 | 🌐 Python | 📅 2026-06-29 (👨‍💻 86 · 🔀 1.2K · 📥 37 · 📦 310 · 📋 920 - 12% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/automl/auto-sklearn
  ```
* [PyPi](https://pypi.org/project/auto-sklearn) (📥 40K / month):
  ```
  pip install auto-sklearn
  ```

</details>
<details><summary><b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥈29 ·  ⭐ 6.2K) - 全局优化的Python实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/fmfn/BayesianOptimization) ⭐ 8,692 | 🐛 7 | 🌐 Python | 📅 2026-08-21 (👨‍💻 35 · 🔀 1.3K · 📥 96 · 📦 1.3K · 📋 260 - 7% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/fmfn/BayesianOptimization
  ```
* [PyPi](https://pypi.org/project/bayesian-optimization) (📥 200K / month):
  ```
  pip install bayesian-optimization
  ```

</details>
<details><summary><b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥈28 ·  ⭐ 6.4K · 💤) - Python中的分布式异步超参数优化。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/hyperopt/hyperopt) ⭐ 7,592 | 🐛 9 | 🌐 Python | 📅 2026-08-17 (👨‍💻 93 · 🔀 860 · 📦 7.4K · 📋 610 - 61% open · ⏱️ 29.11.2021):

  ```
  git clone https://github.com/hyperopt/hyperopt
  ```
* [PyPi](https://pypi.org/project/hyperopt) (📥 1.8M / month):
  ```
  pip install hyperopt
  ```
* [Conda](https://anaconda.org/conda-forge/hyperopt) (📥 500K · ⏱️ 30.04.2022):
  ```
  conda install -c conda-forge hyperopt
  ```

</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈26 ·  ⭐ 4.7K) - AutoGluon：用于文本，图像和表格数据的AutoML。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/awslabs/autogluon) ⭐ 10,612 | 🐛 379 | 🌐 Python | 📅 2026-08-22 (👨‍💻 85 · 🔀 620 · 📦 160 · 📋 740 - 21% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/awslabs/autogluon
  ```
* [PyPi](https://pypi.org/project/autogluon) (📥 40K / month):
  ```
  pip install autogluon
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥈26 ·  ⭐ 2.3K) - PyTorch中的贝叶斯优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/botorch) ⭐ 3,588 | 🐛 94 | 🌐 Jupyter Notebook | 📅 2026-08-20 (👨‍💻 80 · 🔀 260 · 📦 300 · 📋 290 - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytorch/botorch
  ```
* [PyPi](https://pypi.org/project/botorch) (📥 210K / month):
  ```
  pip install botorch
  ```

</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈26 ·  ⭐ 1.9K) - 自适应实验平台。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebook/Ax) ⭐ 2,791 | 🐛 186 | 🌐 Python | 📅 2026-08-19 (👨‍💻 120 · 🔀 210 · 📦 310 · 📋 430 - 8% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/facebook/Ax
  ```
* [PyPi](https://pypi.org/project/ax-platform) (📥 160K / month):
  ```
  pip install ax-platform
  ```

</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈24 ·  ⭐ 2.1K · 💤) - Keras + Hyperopt：一个非常简单的包装，方便使用。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/maxpumperla/hyperas) ⭐ 2,173 | 🐛 97 | 🌐 Python | 📅 2023-01-05 (👨‍💻 21 · 🔀 300 · 📦 250 · 📋 250 - 37% open · ⏱️ 19.11.2021):

  ```
  git clone https://github.com/maxpumperla/hyperas
  ```
* [PyPi](https://pypi.org/project/hyperas) (📥 18K / month):
  ```
  pip install hyperas
  ```

</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈24 ·  ⭐ 2K) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mljar/mljar-supervised) ⭐ 3,286 | 🐛 130 | 🌐 Python | 📅 2026-07-27 (👨‍💻 19 · 🔀 280 · 📦 50 · 📋 490 - 19% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/mljar/mljar-supervised
  ```
* [PyPi](https://pypi.org/project/mljar-supervised) (📥 7.4K / month):
  ```
  pip install mljar-supervised
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈23 ·  ⭐ 3.3K) - 用于执行无梯度优化(gradient-free optimization)的Python工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/nevergrad) ⭐ 4,203 | 🐛 142 | 🌐 Python | 📅 2026-07-24 (👨‍💻 50 · 🔀 310 · 📦 370 · 📋 220 - 30% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/facebookresearch/nevergrad
  ```
* [PyPi](https://pypi.org/project/nevergrad) (📥 33K / month):
  ```
  pip install nevergrad
  ```
* [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 31K · ⏱️ 14.06.2021):
  ```
  conda install -c conda-forge nevergrad
  ```

</details>
<details><summary><b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈23 ·  ⭐ 830 · 💀) - 使用GPy进行高斯过程优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/SheffieldML/GPyOpt) ⚠️ Archived (👨‍💻 49 · 🔀 250 · 📦 310 · 📋 290 - 35% open · ⏱️ 05.11.2020):

  ```
  git clone https://github.com/SheffieldML/GPyOpt
  ```
* [PyPi](https://pypi.org/project/gpyopt) (📥 12K / month):
  ```
  pip install gpyopt
  ```

</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥈22 ·  ⭐ 6.3K) - 一个用于自动化特征工程的开源python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/alteryx/featuretools) ⭐ 7,665 | 🐛 168 | 🌐 Python | 📅 2026-07-27 (👨‍💻 67 · 🔀 800 · 📋 850 - 18% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/alteryx/featuretools
  ```
* [PyPi](https://pypi.org/project/featuretools) (📥 160K / month):
  ```
  pip install featuretools
  ```
* [Conda](https://anaconda.org/conda-forge/featuretools) (📥 100K · ⏱️ 18.08.2022):
  ```
  conda install -c conda-forge featuretools
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥈22 ·  ⭐ 3.4K · 💤) - 具有学习保证的快速灵活的AutoML。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/adanet) ⚠️ Archived (👨‍💻 27 · 🔀 520 · 📦 44 · 📋 110 - 56% open · ⏱️ 30.08.2021):

  ```
  git clone https://github.com/tensorflow/adanet
  ```
* [PyPi](https://pypi.org/project/adanet) (📥 490 / month):
  ```
  pip install adanet
  ```

</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈22 ·  ⭐ 1.5K) - TensorFlow，Keras和PyTorch的超参数优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/autonomio/talos) ⭐ 1,636 | 🐛 13 | 🌐 Python | 📅 2024-04-22 (👨‍💻 22 · 🔀 260 · 📦 150 · 📋 400 - 6% open · ⏱️ 23.04.2022):

  ```
  git clone https://github.com/autonomio/talos
  ```
* [PyPi](https://pypi.org/project/talos) (📥 750 / month):
  ```
  pip install talos
  ```

</details>
<details><summary><b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥈22 ·  ⭐ 240) - 异步分布式超参数优化。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/Epistimio/orion) ⭐ 304 | 🐛 225 | 🌐 Python | 📅 2026-04-11 (👨‍💻 27 · 🔀 43 · 📦 73 · 📋 350 - 52% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/Epistimio/orion
  ```
* [PyPi](https://pypi.org/project/orion) (📥 4.4K / month):
  ```
  pip install orion
  ```

</details>
<details><summary><b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉21 ·  ⭐ 1.3K · 💀) - MLBox是功能强大的自动机器学习python库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/AxeldeRomblay/MLBox) ⭐ 1,536 | 🐛 28 | 🌐 Python | 📅 2023-08-06 (👨‍💻 9 · 🔀 270 · 📦 28 · 📋 92 - 19% open · ⏱️ 25.08.2020):

  ```
  git clone https://github.com/AxeldeRomblay/MLBox
  ```
* [PyPi](https://pypi.org/project/mlbox) (📥 2.9K / month):
  ```
  pip install mlbox
  ```

</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉21 ·  ⭐ 540) - 类似于Sklearn的超参数调整和AutoML输入框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Neuraxio/Neuraxle) ⭐ 613 | 🐛 2 | 🌐 Python | 📅 2026-02-20 (👨‍💻 7 · 🔀 52 · 📦 34 · 📋 320 - 19% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/Neuraxio/Neuraxle
  ```
* [PyPi](https://pypi.org/project/neuraxle) (📥 490 / month):
  ```
  pip install neuraxle
  ```

</details>
<details><summary><b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉21 ·  ⭐ 390 · 💀) - 超参数优化的优化例程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/claesenm/optunity) ⭐ 428 | 🐛 52 | 🌐 Jupyter Notebook | 📅 2023-11-25 (👨‍💻 9 · 🔀 75 · 📥 67 · 📦 81 · 📋 97 - 50% open · ⏱️ 11.05.2020):

  ```
  git clone https://github.com/claesenm/optunity
  ```
* [PyPi](https://pypi.org/project/optunity) (📥 11K / month):
  ```
  pip install optunity
  ```

</details>
<details><summary><b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉20 ·  ⭐ 540) - 分布式自动化机器学习库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/automl/HpBandSter) ⭐ 633 | 🐛 66 | 🌐 Python | 📅 2022-10-16 (👨‍💻 11 · 🔀 110 · 📦 240 · 📋 89 - 60% open · ⏱️ 22.04.2022):

  ```
  git clone https://github.com/automl/HpBandSter
  ```
* [PyPi](https://pypi.org/project/hpbandster) (📥 22K / month):
  ```
  pip install hpbandster
  ```

</details>
<details><summary><b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉19 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ClimbsRocks/auto_ml) ⭐ 1,654 | 🐛 187 | 🌐 Python | 📅 2021-02-10 (👨‍💻 13 · 🔀 300 · 📥 42 · 📋 400 - 45% open · ⏱️ 25.03.2018):

  ```
  git clone https://github.com/ClimbsRocks/auto_ml
  ```
* [PyPi](https://pypi.org/project/auto_ml) (📥 840 / month):
  ```
  pip install auto_ml
  ```

</details>
<details><summary><b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉19 ·  ⭐ 380) - Lazy Predict帮助您无需大量代码即可构建许多基本模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/shankarpandala/lazypredict) ⭐ 3,346 | 🐛 1 | 🌐 Python | 📅 2026-04-26 (👨‍💻 17 · 🔀 67 · 📦 320 · 📋 66 - 48% open · ⏱️ 25.05.2022):

  ```
  git clone https://github.com/shankarpandala/lazypredict
  ```
* [PyPi](https://pypi.org/project/lazypredict) (📥 5.1K / month):
  ```
  pip install lazypredict
  ```

</details>
<details><summary><b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉19 ·  ⭐ 310 · 💀) - 超参数优化库。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/sherpa-ai/sherpa) ⭐ 347 | 🐛 19 | 🌐 JavaScript | 📅 2020-10-18 (👨‍💻 43 · 🔀 48 · 📦 23 · 📋 57 - 28% open · ⏱️ 18.10.2020):

  ```
  git clone https://github.com/sherpa-ai/sherpa
  ```
* [PyPi](https://pypi.org/project/parameter-sherpa) (📥 1.1K / month):
  ```
  pip install parameter-sherpa
  ```

</details>
<details><summary><b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥉18 ·  ⭐ 730) - Sequential Model-based算法的配置。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/automl/SMAC3) ⭐ 1,243 | 🐛 127 | 🌐 Python | 📅 2026-08-23 (👨‍💻 38 · 🔀 170 · 📋 400 - 18% open · ⏱️ 14.07.2022):

  ```
  git clone https://github.com/automl/SMAC3
  ```
* [PyPi](https://pypi.org/project/smac) (📥 50K / month):
  ```
  pip install smac
  ```

</details>
<details><summary><b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉18 ·  ⭐ 720 · 💀) - 可轻松记录实验并进行并行化的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/williamFalcon/test-tube) ⭐ 736 | 🐛 27 | 🌐 JavaScript | 📅 2022-07-22 (👨‍💻 16 · 🔀 67 · 📥 12 · 📋 44 - 52% open · ⏱️ 17.03.2020):

  ```
  git clone https://github.com/williamFalcon/test-tube
  ```
* [PyPi](https://pypi.org/project/test_tube) (📥 51K / month):
  ```
  pip install test_tube
  ```

</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉18 ·  ⭐ 700 · 💀) - 使用进化算法而非gridsearch的超参数优化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rsteca/sklearn-deap) ⭐ 771 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2024-02-10 (👨‍💻 22 · 🔀 120 · 📦 35 · 📋 50 - 32% open · ⏱️ 30.07.2021):

  ```
  git clone https://github.com/rsteca/sklearn-deap
  ```
* [PyPi](https://pypi.org/project/sklearn-deap) (📥 670 / month):
  ```
  pip install sklearn-deap
  ```

</details>
<details><summary><b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉18 ·  ⭐ 670) - 一个用于自动化特征工程的开源python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/dragonfly/dragonfly) ⭐ 893 | 🐛 43 | 🌐 Python | 📅 2023-06-19 (👨‍💻 13 · 🔀 210 · 📋 56 - 64% open · ⏱️ 14.07.2022):

  ```
  git clone https://github.com/dragonfly/dragonfly
  ```
* [PyPi](https://pypi.org/project/dragonfly-opt) (📥 35K / month):
  ```
  pip install dragonfly-opt
  ```

</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉17 ·  ⭐ 800) - 使用scikit-learn的自动化机器学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/ScottfreeLLC/AlphaPy) ⭐ 1,745 | 🐛 19 | 🌐 Python | 📅 2025-08-24 (👨‍💻 3 · 🔀 160 · 📦 3 · 📋 41 - 29% open · ⏱️ 23.04.2022):

  ```
  git clone https://github.com/ScottfreeLLC/AlphaPy
  ```
* [PyPi](https://pypi.org/project/alphapy) (📥 59 / month):
  ```
  pip install alphapy
  ```

</details>
<details><summary><b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉17 ·  ⭐ 520 · 💀) - 自动调整模型。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/HDI-Project/ATM) ⭐ 529 | 🐛 20 | 🌐 Python | 📅 2020-02-21 (👨‍💻 16 · 🔀 130 · 📦 12 · 📋 89 - 20% open · ⏱️ 21.02.2020):

  ```
  git clone https://github.com/HDI-Project/ATM
  ```
* [PyPi](https://pypi.org/project/atm) (📥 67 / month):
  ```
  pip install atm
  ```

</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉17 ·  ⭐ 360) - 用单行代码自动构建多个ML模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/AutoViML/Auto_ViML) ⭐ 548 | 🐛 0 | 🌐 Python | 📅 2025-01-30 (👨‍💻 6 · 🔀 81 · 📦 17 · 📋 21 - 19% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/AutoViML/Auto_ViML
  ```
* [PyPi](https://pypi.org/project/autoviml) (📥 460 / month):
  ```
  pip install autoviml
  ```

</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉17 ·  ⭐ 200 · 💀) - 并行化拟合与评估工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jmcarpenter2/parfit) ⭐ 199 | 🐛 8 | 🌐 Python | 📅 2024-02-13 (👨‍💻 4 · 🔀 25 · 📦 16 · 📋 11 - 54% open · ⏱️ 04.04.2020):

  ```
  git clone https://github.com/jmcarpenter2/parfit
  ```
* [PyPi](https://pypi.org/project/parfit) (📥 9.7K / month):
  ```
  pip install parfit
  ```

</details>
<details><summary><b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉16 ·  ⭐ 1.8K · 💀) - 提供输入CSV和目标字段以进行预测，自动生成可运行代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/minimaxir/automl-gs) ⭐ 1,867 | 🐛 28 | 🌐 Python | 📅 2019-10-22 (👨‍💻 7 · 🔀 160 · 📥 32 · 📋 30 - 80% open · ⏱️ 05.04.2019):

  ```
  git clone https://github.com/minimaxir/automl-gs
  ```
* [PyPi](https://pypi.org/project/automl_gs) (📥 22 / month):
  ```
  pip install automl_gs
  ```

</details>
<details><summary><b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉16 ·  ⭐ 270) - 自动化特征工程并进行特征选择的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/AutoViML/featurewiz) ⭐ 684 | 🐛 1 | 🌐 Python | 📅 2025-02-19 (👨‍💻 4 · 🔀 57 · 📦 14 · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/AutoViML/featurewiz
  ```
* [PyPi](https://pypi.org/project/featurewiz) (📥 6.5K / month):
  ```
  pip install featurewiz
  ```

</details>
<details><summary><b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉15 ·  ⭐ 1.5K · 💀) - Google Vizier的超参数开源实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/tobegit3hub/advisor) ⭐ 1,563 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2019-11-11 (👨‍💻 11 · 🔀 260 · 📋 32 - 59% open · ⏱️ 11.11.2019):

  ```
  git clone https://github.com/tobegit3hub/advisor
  ```
* [PyPi](https://pypi.org/project/advisor) (📥 34 / month):
  ```
  pip install advisor
  ```
* [Docker Hub](https://hub.docker.com/r/tobegit3hub/advisor) (📥 1.7K · ⏱️ 11.11.2019):
  ```
  docker pull tobegit3hub/advisor
  ```

</details>
<details><summary><b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉15 ·  ⭐ 1.3K · 💀) - 基于Web的应用程序，高效、可扩展且自动化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/reiinakano/xcessiv) ⭐ 1,265 | 🐛 22 | 🌐 Python | 📅 2018-06-06 (👨‍💻 6 · 🔀 110 · 📦 1 · 📋 34 - 61% open · ⏱️ 21.08.2017):

  ```
  git clone https://github.com/reiinakano/xcessiv
  ```
* [PyPi](https://pypi.org/project/xcessiv) (📥 10 / month):
  ```
  pip install xcessiv
  ```

</details>
<details><summary><b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉15 ·  ⭐ 690 · 💀) - 轻松进行超参数优化和自动结果评估。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/HunterMcGushion/hyperparameter_hunter) ⭐ 705 | 🐛 37 | 🌐 Python | 📅 2021-01-20 (👨‍💻 4 · 🔀 88 · 📥 330 · 📋 120 - 27% open · ⏱️ 20.01.2021):

  ```
  git clone https://github.com/HunterMcGushion/hyperparameter_hunter
  ```
* [PyPi](https://pypi.org/project/hyperparameter-hunter) (📥 61 / month):
  ```
  pip install hyperparameter-hunter
  ```

</details>
<details><summary><b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.6K · 💀) - Efficient Neural Architecture Search的Pytorch实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/carpedm20/ENAS-pytorch) ⭐ 2,719 | 🐛 40 | 🌐 Python | 📅 2023-07-06 (👨‍💻 6 · 🔀 470 · 📋 44 - 84% open · ⏱️ 16.06.2020):

  ```
  git clone https://github.com/carpedm20/ENAS-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉13 ·  ⭐ 190 · 💀) - 自动ML模型优化工具。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/LGE-ARC-AdvancedAI/auptimizer) ⭐ 199 | 🐛 22 | 🌐 Python | 📅 2023-01-27 (👨‍💻 11 · 🔀 22 · 📋 6 - 16% open · ⏱️ 03.03.2021):

  ```
  git clone https://github.com/LGE-ARC-AdvancedAI/auptimizer
  ```
* [PyPi](https://pypi.org/project/auptimizer) (📥 25 / month):
  ```
  pip install auptimizer
  ```

</details>
<details><summary><b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉12 ·  ⭐ 100 · 💀) - 更好更快的超参数优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/electricbrainio/hypermax) ⭐ 112 | 🐛 3 | 🌐 Python | 📅 2024-01-03 (👨‍💻 9 · 🔀 13 · 📦 4 · 📋 5 - 60% open · ⏱️ 02.08.2020):

  ```
  git clone https://github.com/electricbrainio/hypermax
  ```
* [PyPi](https://pypi.org/project/hypermax) (📥 30 / month):
  ```
  pip install hypermax
  ```

</details>
<details><summary><b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 940 · 💀) - 使用Keras进行遗传神经体系结构搜索。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/joeddav/devol) ⭐ 951 | 🐛 7 | 🌐 Python | 📅 2023-05-25 (👨‍💻 18 · 🔀 110 · 📋 27 - 25% open · ⏱️ 05.07.2020):

  ```
  git clone https://github.com/joeddav/devol
  ```

</details>
<details><summary><b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉10 ·  ⭐ 120 · 💀) - 黑盒超参数优化的工具集。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/gdikov/hypertunity) ⭐ 137 | 🐛 0 | 🌐 Python | 📅 2020-01-26 (👨‍💻 2 · 🔀 9 · 📦 2 · ⏱️ 26.01.2020):

  ```
  git clone https://github.com/gdikov/hypertunity
  ```
* [PyPi](https://pypi.org/project/hypertunity) (📥 18 / month):
  ```
  pip install hypertunity
  ```

</details>
<br>

## 强化学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于构建和评估强化学习和基于agent的系统的库。*

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇36 ·  ⭐ 28K) - 开发和比较强化学习的工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/openai/gym) ⚠️ Archived (👨‍💻 380 · 🔀 7.5K · 📦 32K · 📋 1.6K - 0% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/openai/gym
  ```
* [PyPi](https://pypi.org/project/gym) (📥 620K / month):
  ```
  pip install gym
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇27 ·  ⭐ 2.3K) - TF-Agents：可靠，可扩展且易于使用的TensorFlow的强化学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/agents) ⭐ 3,025 | 🐛 212 | 🌐 Python | 📅 2026-01-16 (👨‍💻 120 · 🔀 620 · 📦 880 · 📋 560 - 22% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/tensorflow/agents
  ```
* [PyPi](https://pypi.org/project/tf-agents) (📥 150K / month):
  ```
  pip install tf-agents
  ```

</details>
<details><summary><b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥈25 ·  ⭐ 5.3K · 💀) - Keras的深度强化学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/keras-rl/keras-rl) ⭐ 5,547 | 🐛 47 | 🌐 Python | 📅 2023-09-17 (👨‍💻 40 · 🔀 1.3K · 📦 610 · 📋 230 - 2% open · ⏱️ 11.11.2019):

  ```
  git clone https://github.com/keras-rl/keras-rl
  ```
* [PyPi](https://pypi.org/project/keras-rl) (📥 1.3K / month):
  ```
  pip install keras-rl
  ```

</details>
<details><summary><b><a href="https://github.com/openai/baselines">baselines</a></b> (🥈24 ·  ⭐ 13K · 💀) - OpenAI基线：强化学习的高质量实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/openai/baselines) ⭐ 16,763 | 🐛 502 | 🌐 Python | 📅 2024-08-01 (👨‍💻 110 · 🔀 3.5K · 📦 410 · 📋 830 - 47% open · ⏱️ 31.01.2020):

  ```
  git clone https://github.com/openai/baselines
  ```
* [PyPi](https://pypi.org/project/baselines) (📥 940 / month):
  ```
  pip install baselines
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥈24 ·  ⭐ 2.7K) - 强化学习组件和代理库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepmind/acme) ⭐ 4,045 | 🐛 100 | 🌐 Python | 📅 2026-08-01 (👨‍💻 75 · 🔀 340 · 📦 99 · 📋 210 - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/deepmind/acme
  ```
* [PyPi](https://pypi.org/project/dm-acme) (📥 5K / month):
  ```
  pip install dm-acme
  ```

</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥈23 ·  ⭐ 1.5K) - 用于可重复的强化学习研究的工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rlworkgroup/garage) ⭐ 2,124 | 🐛 234 | 🌐 Python | 📅 2023-05-04 (👨‍💻 78 · 🔀 260 · 📦 51 · 📋 1K - 19% open · ⏱️ 20.05.2022):

  ```
  git clone https://github.com/rlworkgroup/garage
  ```
* [PyPi](https://pypi.org/project/garage) (📥 460 / month):
  ```
  pip install garage
  ```

</details>
<details><summary><b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈23 ·  ⭐ 1.4K) - 人工智能强化学习工具库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/mwydmuch/ViZDoom) ⭐ 2,062 | 🐛 39 | 🌐 C++ | 📅 2026-08-21 (👨‍💻 49 · 🔀 330 · 📥 12K · 📦 150 · 📋 440 - 19% open · ⏱️ 26.06.2022):

  ```
  git clone https://github.com/mwydmuch/ViZDoom
  ```
* [PyPi](https://pypi.org/project/vizdoom) (📥 630 / month):
  ```
  pip install vizdoom
  ```

</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈22 ·  ⭐ 9.9K) - Dopamine是一个用于快速对强化学习进行原型制作的研究框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/google/dopamine) ⭐ 10,897 | 🐛 111 | 🌐 Jupyter Notebook | 📅 2026-03-24 (👨‍💻 15 · 🔀 1.3K · 📋 150 - 43% open · ⏱️ 13.06.2022):

  ```
  git clone https://github.com/google/dopamine
  ```
* [PyPi](https://pypi.org/project/dopamine-rl) (📥 49K / month):
  ```
  pip install dopamine-rl
  ```

</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥈22 ·  ⭐ 3.2K) - Tensorforce：一个基于TensorFlow的强化学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorforce/tensorforce) ⭐ 3,305 | 🐛 44 | 🌐 Python | 📅 2026-07-14 (👨‍💻 82 · 🔀 510 · 📋 650 - 3% open · ⏱️ 10.02.2022):

  ```
  git clone https://github.com/tensorforce/tensorforce
  ```
* [PyPi](https://pypi.org/project/tensorforce) (📥 1.2K / month):
  ```
  pip install tensorforce
  ```

</details>
<details><summary><b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥈22 ·  ⭐ 1.1K · 💀) - ChainerRL是建立在Chainer之上的深度强化学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/chainer/chainerrl) ⭐ 1,198 | 🐛 65 | 🌐 Python | 📅 2021-08-10 (👨‍💻 29 · 🔀 220 · 📦 130 · 📋 200 - 25% open · ⏱️ 17.04.2021):

  ```
  git clone https://github.com/chainer/chainerrl
  ```
* [PyPi](https://pypi.org/project/chainerrl) (📥 520 / month):
  ```
  pip install chainerrl
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥈22 ·  ⭐ 890) - 强化学习组件和代理库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>jax</code></summary>

* [GitHub](https://github.com/deepmind/rlax) ⭐ 1,439 | 🐛 24 | 🌐 Python | 📅 2026-08-06 (👨‍💻 19 · 🔀 66 · 📦 75 · 📋 19 - 21% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/deepmind/rlax
  ```
* [PyPi](https://pypi.org/project/rlax) (📥 5.3K / month):
  ```
  pip install rlax
  ```

</details>
<details><summary><b><a href="https://github.com/tensorlayer/TensorLayer">TensorLayer</a></b> (🥉21 ·  ⭐ 7.1K) - 深度学习和强化学习库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorlayer/TensorLayer) ⭐ 7,381 | 🐛 36 | 🌐 Python | 📅 2023-02-18 (👨‍💻 130 · 🔀 1.6K · 📥 1.4K · 📋 460 - 4% open · ⏱️ 23.04.2022):

  ```
  git clone https://github.com/tensorlayer/tensorlayer
  ```
* [PyPi](https://pypi.org/project/tensorlayer) (📥 1.5K / month):
  ```
  pip install tensorlayer
  ```

</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉20 ·  ⭐ 3.6K · 💤) - OpenAI Baselines的一个分支，强化学习的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/hill-a/stable-baselines) ⭐ 4,331 | 🐛 138 | 🌐 Python | 📅 2022-09-04 (👨‍💻 110 · 🔀 690 · 📋 920 - 11% open · ⏱️ 25.08.2021):

  ```
  git clone https://github.com/hill-a/stable-baselines
  ```
* [PyPi](https://pypi.org/project/stable-baselines) (📥 7.9K / month):
  ```
  pip install stable-baselines
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉20 ·  ⭐ 2.7K) - 强化学习高性能分布式训练框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/PARL) ⭐ 3,453 | 🐛 134 | 🌐 Python | 📅 2025-09-13 (👨‍💻 31 · 🔀 730 · 📦 94 · 📋 410 - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/PARL
  ```
* [PyPi](https://pypi.org/project/parl) (📥 500 / month):
  ```
  pip install parl
  ```

</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉20 ·  ⭐ 890) - PFRL：基于PyTorch的深度强化学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pfnet/pfrl) ⭐ 1,273 | 🐛 36 | 🌐 Python | 📅 2026-03-02 (👨‍💻 16 · 🔀 120 · 📦 54 · 📋 63 - 38% open · ⏱️ 14.03.2022):

  ```
  git clone https://github.com/pfnet/pfrl
  ```
* [PyPi](https://pypi.org/project/pfrl) (📥 410 / month):
  ```
  pip install pfrl
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉19 ·  ⭐ 3.1K · 💤) - TensorFlow强化学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepmind/trfl) ⭐ 3,131 | 🐛 6 | 🌐 Python | 📅 2022-12-08 (👨‍💻 13 · 🔀 380 · 📦 89 · 📋 20 - 20% open · ⏱️ 16.08.2021):

  ```
  git clone https://github.com/deepmind/trfl
  ```
* [PyPi](https://pypi.org/project/trfl) (📥 4.2K / month):
  ```
  pip install trfl
  ```

</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉18 ·  ⭐ 2.2K · 💀) - 英特尔AI实验室的强化学习训练器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 35 · 🔀 430 · 📋 260 - 30% open · ⏱️ 28.06.2021):

  ```
  git clone https://github.com/IntelLabs/coach
  ```
* [PyPi](https://pypi.org/project/rl_coach) (📥 120 / month):
  ```
  pip install rl_coach
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉17 ·  ⭐ 3.2K) - 推理系统平台。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/ReAgent) ⭐ 3,712 | 🐛 85 | 🌐 Python | 📅 2026-08-20 (👨‍💻 140 · 🔀 460 · 📋 100 - 25% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/facebookresearch/ReAgent
  ```

</details>
<details><summary><b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉15 ·  ⭐ 6.7K) - 可定制的3D平台，用于agent-based AI研究。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/deepmind/lab) ⭐ 7,373 | 🐛 66 | 🌐 C | 📅 2023-01-04 (👨‍💻 8 · 🔀 1.3K · 📋 220 - 25% open · ⏱️ 09.06.2022):

  ```
  git clone https://github.com/deepmind/lab
  ```

</details>
<br>

## 推荐系统

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于建立和评估推荐系统的库。*

<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥇26 ·  ⭐ 4.1K) - 全局优化的Python实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/lyst/lightfm) ⭐ 5,111 | 🐛 166 | 🌐 Python | 📅 2024-07-24 (👨‍💻 44 · 🔀 630 · 📦 790 · 📋 460 - 24% open · ⏱️ 19.07.2022):

  ```
  git clone https://github.com/lyst/lightfm
  ```
* [PyPi](https://pypi.org/project/lightfm) (📥 360K / month):
  ```
  pip install lightfm
  ```
* [Conda](https://anaconda.org/conda-forge/lightfm) (📥 130K · ⏱️ 09.03.2022):
  ```
  conda install -c conda-forge lightfm
  ```

</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇26 ·  ⭐ 2.9K) - 隐式反馈数据集的快速Python协同过滤。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/benfred/implicit) ⭐ 3,814 | 🐛 97 | 🌐 Python | 📅 2026-05-08 (👨‍💻 32 · 🔀 530 · 📥 95 · 📦 650 · 📋 420 - 16% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/benfred/implicit
  ```
* [PyPi](https://pypi.org/project/implicit) (📥 160K / month):
  ```
  pip install implicit
  ```
* [Conda](https://anaconda.org/conda-forge/implicit) (📥 390K · ⏱️ 29.01.2022):
  ```
  conda install -c conda-forge implicit
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥇26 ·  ⭐ 1.4K) - TensorFlow Recommenders是一个用于构建推荐系统的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/recommenders) ⭐ 2,026 | 🐛 280 | 🌐 Python | 📅 2026-07-08 (👨‍💻 37 · 🔀 200 · 📦 140 · 📋 280 - 49% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/tensorflow/recommenders
  ```
* [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 560K / month):
  ```
  pip install tensorflow-recommenders
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈23 ·  ⭐ 2.5K) - 在TensorFlow中学习推荐排序。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/ranking) ⚠️ Archived (👨‍💻 28 · 🔀 430 · 📋 290 - 19% open · ⏱️ 26.04.2022):

  ```
  git clone https://github.com/tensorflow/ranking
  ```
* [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 110K / month):
  ```
  pip install tensorflow_ranking
  ```

</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥈23 ·  ⭐ 630) - 多模态推荐系统的比较框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PreferredAI/cornac) ⭐ 1,053 | 🐛 25 | 🌐 Python | 📅 2026-08-11 (👨‍💻 15 · 🔀 100 · 📦 120 · 📋 100 - 8% open · ⏱️ 22.07.2022):

  ```
  git clone https://github.com/PreferredAI/cornac
  ```
* [PyPi](https://pypi.org/project/cornac) (📥 40K / month):
  ```
  pip install cornac
  ```
* [Conda](https://anaconda.org/conda-forge/cornac) (📥 240K · ⏱️ 19.02.2022):
  ```
  conda install -c conda-forge cornac
  ```

</details>
<details><summary><b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥉22 ·  ⭐ 5.5K) - 用于构建和分析推荐算法的Python scikit工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/NicolasHug/Surprise) ⭐ 6,806 | 🐛 80 | 🌐 Python | 📅 2026-05-30 (👨‍💻 43 · 🔀 920 · 📋 350 - 15% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/NicolasHug/Surprise
  ```
* [PyPi](https://pypi.org/project/scikit-surprise) (📥 120K / month):
  ```
  pip install scikit-surprise
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-surprise) (📥 250K · ⏱️ 18.11.2021):
  ```
  conda install -c conda-forge scikit-surprise
  ```

</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥉22 ·  ⭐ 2K) - 统一，全面，高效的推荐库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/RUCAIBox/RecBole) ⭐ 4,531 | 🐛 357 | 🌐 Python | 📅 2025-02-24 (👨‍💻 47 · 🔀 380 · 📋 460 - 13% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/RUCAIBox/RecBole
  ```
* [PyPi](https://pypi.org/project/recbole) (📥 6.7K / month):
  ```
  pip install recbole
  ```
* [Conda](https://anaconda.org/aibox/recbole) (📥 1.9K · ⏱️ 25.02.2022):
  ```
  conda install -c aibox recbole
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥉21 ·  ⭐ 14K) - 推荐系统最佳实践。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/recommenders) ⭐ 21,867 | 🐛 176 | 🌐 Python | 📅 2026-08-20 (👨‍💻 120 · 🔀 2.4K · 📥 230 · 📦 33 · 📋 710 - 20% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/microsoft/recommenders
  ```

</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉19 ·  ⭐ 1K · 💀) - fastFM：用于分解机的工具库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/ibayer/fastFM) ⭐ 1,086 | 🐛 51 | 🌐 Python | 📅 2022-07-17 (👨‍💻 20 · 🔀 200 · 📥 450 · 📦 97 · 📋 110 - 43% open · ⏱️ 24.03.2021):

  ```
  git clone https://github.com/ibayer/fastFM
  ```
* [PyPi](https://pypi.org/project/fastfm) (📥 370 / month):
  ```
  pip install fastfm
  ```

</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉19 ·  ⭐ 420) - 用于评估推荐系统的度量标准库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/statisticianinstilettos/recmetrics) ⭐ 580 | 🐛 20 | 🌐 Jupyter Notebook | 📅 2024-01-11 (👨‍💻 16 · 🔀 85 · 📦 29 · 📋 20 - 40% open · ⏱️ 17.04.2022):

  ```
  git clone https://github.com/statisticianinstilettos/recmetrics
  ```
* [PyPi](https://pypi.org/project/recmetrics) (📥 3.3K / month):
  ```
  pip install recmetrics
  ```

</details>
<details><summary><b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉18 ·  ⭐ 2.8K · 💀) - 使用PyTorch的深度推荐系统模型实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/maciejkula/spotlight) ⭐ 3,043 | 🐛 73 | 🌐 Python | 📅 2022-12-21 (👨‍💻 11 · 🔀 400 · 📋 110 - 56% open · ⏱️ 09.02.2020):

  ```
  git clone https://github.com/maciejkula/spotlight
  ```
* [Conda](https://anaconda.org/maciejkula/spotlight) (📥 7.6K · ⏱️ 27.05.2018):
  ```
  conda install -c maciejkula spotlight
  ```

</details>
<details><summary><b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉18 ·  ⭐ 1.2K · 💀) - TensorFlow推荐算法和框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jfkirk/tensorrec) ⭐ 1,299 | 🐛 40 | 🌐 Python | 📅 2023-05-22 (👨‍💻 9 · 🔀 220 · 📦 27 · 📋 130 - 28% open · ⏱️ 04.02.2020):

  ```
  git clone https://github.com/jfkirk/tensorrec
  ```
* [PyPi](https://pypi.org/project/tensorrec) (📥 470 / month):
  ```
  pip install tensorrec
  ```

</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉17 ·  ⭐ 420 · 💤) - Case Recommender：灵活且可扩展的Python推荐系统工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/caserec/CaseRecommender) ⭐ 499 | 🐛 6 | 🌐 Python | 📅 2024-01-10 (👨‍💻 11 · 🔀 79 · 📦 10 · 📋 25 - 20% open · ⏱️ 25.11.2021):

  ```
  git clone https://github.com/caserec/CaseRecommender
  ```
* [PyPi](https://pypi.org/project/caserecommender) (📥 130 / month):
  ```
  pip install caserecommender
  ```

</details>
<br>

## 隐私机器学习

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*使用联合学习和差异隐私之类的方法进行加密和保留隐私的机器学习的库。*

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇26 ·  ⭐ 8.3K) - 基于内部数据自动化回答问题的工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/OpenMined/PySyft) ⭐ 9,956 | 🐛 23 | 🌐 Python | 📅 2026-08-20 (👨‍💻 450 · 🔀 1.8K · 📋 3.1K - 1% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/OpenMined/PySyft
  ```
* [PyPi](https://pypi.org/project/syft) (📥 4K / month):
  ```
  pip install syft
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈24 ·  ⭐ 1.2K) - 使用不同的隐私训练PyTorch模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/opacus) ⭐ 1,951 | 🐛 82 | 🌐 Python | 📅 2026-07-13 (👨‍💻 55 · 🔀 220 · 📥 51 · 📦 130 · 📋 200 - 21% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytorch/opacus
  ```
* [PyPi](https://pypi.org/project/opacus) (📥 15K / month):
  ```
  pip install opacus
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥈23 ·  ⭐ 1.6K) - 用于训练机器学习模型的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/privacy) ⭐ 2,022 | 🐛 136 | 🌐 Python | 📅 2026-08-19 (👨‍💻 49 · 🔀 350 · 📥 80 · 📋 150 - 43% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/tensorflow/privacy
  ```
* [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 32K / month):
  ```
  pip install tensorflow-privacy
  ```

</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥉22 ·  ⭐ 4.4K) - 工业级联邦学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/FederatedAI/FATE) ⭐ 6,089 | 🐛 18 | 🌐 Python | 📅 2024-11-19 (👨‍💻 74 · 🔀 1.3K · 📋 1.3K - 36% open · ⏱️ 15.04.2022):

  ```
  git clone https://github.com/FederatedAI/FATE
  ```

</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉20 ·  ⭐ 1K) - TensorFlow中的加密机器学习框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tf-encrypted/tf-encrypted) ⭐ 1,243 | 🐛 144 | 🌐 Python | 📅 2024-09-25 (👨‍💻 28 · 🔀 180 · 📦 62 · 📋 420 - 37% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/tf-encrypted/tf-encrypted
  ```
* [PyPi](https://pypi.org/project/tf-encrypted) (📥 440 / month):
  ```
  pip install tf-encrypted
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉18 ·  ⭐ 1.1K) - 隐私保护的机器学习框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/CrypTen) ⚠️ Archived (👨‍💻 29 · 🔀 180 · 📦 21 · 📋 160 - 12% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/facebookresearch/CrypTen
  ```
* [PyPi](https://pypi.org/project/crypten) (📥 230 / month):
  ```
  pip install crypten
  ```

</details>
<br>

## 工作流程和实验跟踪

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*跟踪和可视化机器学习实验的工具库整理。*

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇37 ·  ⭐ 6K) - TensorFlow的可视化工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/tensorboard) ⭐ 7,205 | 🐛 751 | 🌐 TypeScript | 📅 2026-08-17 (👨‍💻 290 · 🔀 1.5K · 📦 120K · 📋 1.7K - 31% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/tensorflow/tensorboard
  ```
* [PyPi](https://pypi.org/project/tensorboard) (📥 14M / month):
  ```
  pip install tensorboard
  ```
* [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 3.2M · ⏱️ 11.08.2022):
  ```
  conda install -c conda-forge tensorboard
  ```

</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇33 ·  ⭐ 1.7K) - 一个用于训练和部署机器学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/aws/sagemaker-python-sdk) ⭐ 2,260 | 🐛 483 | 🌐 Python | 📅 2026-08-21 (👨‍💻 280 · 🔀 810 · 📦 1.6K · 📋 1.1K - 32% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/aws/sagemaker-python-sdk
  ```
* [PyPi](https://pypi.org/project/sagemaker) (📥 8.4M / month):
  ```
  pip install sagemaker
  ```

</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥇32 ·  ⭐ 6.1K) - Python中的开源代码，低代码机器学习库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pycaret/pycaret) ⭐ 9,831 | 🐛 32 | 🌐 Python | 📅 2026-07-23 (👨‍💻 99 · 🔀 1.4K · 📥 610 · 📦 2.4K · 📋 1.7K - 15% open · ⏱️ 13.08.2022):

  ```
  git clone https://github.com/pycaret/pycaret
  ```
* [PyPi](https://pypi.org/project/pycaret) (📥 580K / month):
  ```
  pip install pycaret
  ```

</details>
<details><summary><b><a href="https://github.com/wandb/wandb">wandb client</a></b> (🥇32 ·  ⭐ 4.6K) - 用于可视化和跟踪机器学习的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/wandb/wandb) ⭐ 11,237 | 🐛 950 | 🌐 Python | 📅 2026-08-23 (👨‍💻 120 · 🔀 340 · 📦 11K · 📋 1.9K - 24% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/wandb/client
  ```
* [PyPi](https://pypi.org/project/wandb) (📥 1.7M / month):
  ```
  pip install wandb
  ```

</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥈31 ·  ⭐ 7.4K) - pytorch（和链接器，mxnet，numpy，...）的张量板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/lanpa/tensorboardX) ⭐ 7,997 | 🐛 85 | 🌐 Python | 📅 2026-07-14 (👨‍💻 72 · 🔀 850 · 📥 350 · 📦 21K · 📋 430 - 15% open · ⏱️ 08.06.2022):

  ```
  git clone https://github.com/lanpa/tensorboardX
  ```
* [PyPi](https://pypi.org/project/tensorboardX) (📥 1.1M / month):
  ```
  pip install tensorboardX
  ```
* [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 780K · ⏱️ 07.06.2022):
  ```
  conda install -c conda-forge tensorboardx
  ```

</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥈30 ·  ⭐ 12K) - 机器学习生命周期的开源平台。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/mlflow/mlflow) ⭐ 27,632 | 🐛 2,070 | 🌐 Python | 📅 2026-08-22 (👨‍💻 470 · 🔀 2.8K · 📋 2.4K - 33% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/mlflow/mlflow
  ```
* [PyPi](https://pypi.org/project/mlflow) (📥 13M / month):
  ```
  pip install mlflow
  ```
* [Conda](https://anaconda.org/conda-forge/mlflow) (📥 740K · ⏱️ 19.08.2022):
  ```
  conda install -c conda-forge mlflow
  ```

</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈30 ·  ⭐ 3.9K) - Sacred是可帮助您配置，组织，记录和复现的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/IDSIA/sacred) ⭐ 4,374 | 🐛 107 | 🌐 Python | 📅 2025-10-22 (👨‍💻 100 · 🔀 350 · 📦 1.5K · 📋 540 - 16% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/IDSIA/sacred
  ```
* [PyPi](https://pypi.org/project/sacred) (📥 68K / month):
  ```
  pip install sacred
  ```

</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈29 ·  ⭐ 3.5K) - ClearML-自动精简工具套件。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/allegroai/clearml) ⭐ 6,836 | 🐛 512 | 🌐 Python | 📅 2026-08-23 (👨‍💻 52 · 🔀 460 · 📥 500 · 📦 290 · 📋 600 - 44% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/allegroai/clearml
  ```
* [PyPi](https://pypi.org/project/clearml) (📥 94K / month):
  ```
  pip install clearml
  ```
* [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
  ```
  docker pull allegroai/trains
  ```

</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈28 ·  ⭐ 5.9K) - 轻松构建和管理现实生活中的数据科学项目。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Netflix/metaflow) ⭐ 10,233 | 🐛 482 | 🌐 Python | 📅 2026-08-21 (👨‍💻 54 · 🔀 500 · 📦 310 · 📋 420 - 45% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/Netflix/metaflow
  ```
* [PyPi](https://pypi.org/project/metaflow) (📥 62K / month):
  ```
  pip install metaflow
  ```
* [Conda](https://anaconda.org/conda-forge/metaflow) (📥 63K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge metaflow
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈27 ·  ⭐ 4.4K) - 深度学习可视化工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/VisualDL) ⭐ 4,885 | 🐛 157 | 🌐 HTML | 📅 2025-01-22 (👨‍💻 32 · 🔀 590 · 📥 210 · 📦 1.3K · 📋 420 - 20% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/VisualDL
  ```
* [PyPi](https://pypi.org/project/visualdl) (📥 60K / month):
  ```
  pip install visualdl
  ```

</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈27 ·  ⭐ 3K) - 加快深度学习研发。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/catalyst-team/catalyst) ⭐ 3,382 | 🐛 5 | 🌐 Python | 📅 2026-07-08 (👨‍💻 100 · 🔀 340 · 📦 600 · 📋 340 - 1% open · ⏱️ 29.04.2022):

  ```
  git clone https://github.com/catalyst-team/catalyst
  ```
* [PyPi](https://pypi.org/project/catalyst) (📥 39K / month):
  ```
  pip install catalyst
  ```

</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈27 ·  ⭐ 1.5K) - 工作流管理系统snakemake。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/snakemake/snakemake) ⭐ 2,848 | 🐛 1,096 | 🌐 Python | 📅 2026-08-23 (👨‍💻 260 · 🔀 360 · 📦 1.2K · 📋 1.1K - 59% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/snakemake/snakemake
  ```
* [PyPi](https://pypi.org/project/snakemake) (📥 51K / month):
  ```
  pip install snakemake
  ```
* [Conda](https://anaconda.org/bioconda/snakemake) (📥 510K · ⏱️ 11.08.2022):
  ```
  conda install -c bioconda snakemake
  ```

</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥈26 ·  ⭐ 490) - 用于记录和检索与ML相关的元数据。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/google/ml-metadata) ⭐ 683 | 🐛 60 | 🌐 C++ | 📅 2026-08-14 (👨‍💻 15 · 🔀 95 · 📥 1.7K · 📦 240 · 📋 91 - 26% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/google/ml-metadata
  ```
* [PyPi](https://pypi.org/project/ml-metadata) (📥 480K / month):
  ```
  pip install ml-metadata
  ```

</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥈25 ·  ⭐ 10K) - 数据版本控制|针对数据和模型的Git。<code>|) - 数据版本控制|针对数据和模型的Git。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/iterative/dvc) ⭐ 15,836 | 🐛 201 | 🌐 Python | 📅 2026-08-19 (👨‍💻 270 · 🔀 950 · 📥 120K · 📋 3.8K - 16% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/iterative/dvc
  ```
* [PyPi](https://pypi.org/project/dvc) (📥 530K / month):
  ```
  pip install dvc
  ```
* [Conda](https://anaconda.org/conda-forge/dvc) (📥 1.2M · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge dvc
  ```

</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈25 ·  ⭐ 3.4K) - 带有ML的Python笔记本和带有Azure的深度学习示例。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Azure/MachineLearningNotebooks) ⭐ 4,427 | 🐛 400 | 🌐 Jupyter Notebook | 📅 2025-03-14 (👨‍💻 60 · 🔀 2.1K · 📥 460 · 📋 1.3K - 21% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/Azure/MachineLearningNotebooks
  ```
* [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.5M / month):
  ```
  pip install azureml-sdk
  ```

</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥉24 ·  ⭐ 2.7K) - 以一种非常简单的方式来记录，搜索和比较数千次ML训练。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/aimhubio/aim) ⭐ 6,240 | 🐛 468 | 🌐 Python | 📅 2026-08-23 (👨‍💻 42 · 🔀 160 · 📦 100 · 📋 630 - 21% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/aimhubio/aim
  ```
* [PyPi](https://pypi.org/project/aim) (📥 34K / month):
  ```
  pip install aim
  ```

</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉23 ·  ⭐ 1.2K) - Jupyter Notebook for Keras的实时训练loss图。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/stared/livelossplot) ⭐ 1,319 | 🐛 9 | 🌐 Python | 📅 2026-07-26 (👨‍💻 17 · 🔀 140 · 📦 840 · 📋 75 - 6% open · ⏱️ 04.04.2022):

  ```
  git clone https://github.com/stared/livelossplot
  ```
* [PyPi](https://pypi.org/project/livelossplot) (📥 63K / month):
  ```
  pip install livelossplot
  ```

</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉23 ·  ⭐ 1.2K) - 从您的手机监控深度学习模型训练和硬件使用情况。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/labmlai/labml) ⭐ 2,325 | 🐛 6 | 🌐 Python | 📅 2025-04-10 (👨‍💻 7 · 🔀 78 · 📦 54 · 📋 29 - 44% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/lab-ml/labml
  ```
* [PyPi](https://pypi.org/project/labml) (📥 3.2K / month):
  ```
  pip install labml
  ```

</details>
<details><summary><b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉22 ·  ⭐ 2.5K · 💀) - 当您的训练结束后通知您。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/huggingface/knockknock) ⭐ 2,828 | 🐛 36 | 🌐 Python | 📅 2023-06-23 (👨‍💻 18 · 🔀 210 · 📦 380 · 📋 39 - 41% open · ⏱️ 16.03.2020):

  ```
  git clone https://github.com/huggingface/knockknock
  ```
* [PyPi](https://pypi.org/project/knockknock) (📥 59K / month):
  ```
  pip install knockknock
  ```
* [Conda](https://anaconda.org/conda-forge/knockknock) (📥 10K · ⏱️ 17.03.2020):
  ```
  conda install -c conda-forge knockknock
  ```

</details>
<details><summary><b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥉21 ·  ⭐ 4.9K · 💀) - 官方Kaggle API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Kaggle/kaggle-api) ⭐ 7,509 | 🐛 141 | 🌐 Python | 📅 2026-08-21 (👨‍💻 36 · 🔀 940 · 📋 350 - 57% open · ⏱️ 15.03.2021):

  ```
  git clone https://github.com/Kaggle/kaggle-api
  ```
* [PyPi](https://pypi.org/project/kaggle) (📥 120K / month):
  ```
  pip install kaggle
  ```
* [Conda](https://anaconda.org/conda-forge/kaggle) (📥 95K · ⏱️ 17.12.2021):
  ```
  conda install -c conda-forge kaggle
  ```

</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉21 ·  ⭐ 730) - 实验跟踪，ML开发人员工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/guildai/guildai) ⭐ 905 | 🐛 238 | 🌐 Python | 📅 2025-04-29 (👨‍💻 21 · 🔀 66 · 📥 6 · 📦 58 · 📋 380 - 45% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/guildai/guildai
  ```
* [PyPi](https://pypi.org/project/guildai) (📥 3.1K / month):
  ```
  pip install guildai
  ```

</details>
<details><summary><b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉20 ·  ⭐ 1.6K · 💀) - 神经网络图和训练指标。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/waleedka/hiddenlayer) ⭐ 1,867 | 🐛 57 | 🌐 Python | 📅 2024-02-11 (👨‍💻 6 · 🔀 230 · 📦 130 · 📋 85 - 58% open · ⏱️ 24.04.2020):

  ```
  git clone https://github.com/waleedka/hiddenlayer
  ```
* [PyPi](https://pypi.org/project/hiddenlayer) (📥 1.7K / month):
  ```
  pip install hiddenlayer
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉20 ·  ⭐ 1.4K) - 用于记录和可视化，加载和训练的简单工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/tnt) ⭐ 1,721 | 🐛 99 | 🌐 Python | 📅 2026-08-18 (👨‍💻 53 · 🔀 200 · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/pytorch/tnt
  ```
* [PyPi](https://pypi.org/project/torchnet) (📥 8.8K / month):
  ```
  pip install torchnet
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉19 ·  ⭐ 3.2K · 💀) - Python机器学习的调试，监视和可视化。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/tensorwatch) ⭐ 3,472 | 🐛 54 | 🌐 Jupyter Notebook | 📅 2026-03-30 (👨‍💻 13 · 🔀 340 · 📦 86 · 📋 67 - 77% open · ⏱️ 15.01.2021):

  ```
  git clone https://github.com/microsoft/tensorwatch
  ```
* [PyPi](https://pypi.org/project/tensorwatch) (📥 5.3K / month):
  ```
  pip install tensorwatch
  ```

</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉19 ·  ⭐ 1.5K) - lore使机器学习对软件工程师更易上手，对机器学习研究人员更可维护。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/instacart/lore) ⭐ 1,544 | 🐛 21 | 🌐 Python | 📅 2023-05-13 (👨‍💻 26 · 🔀 120 · 📦 20 · 📋 35 - 45% open · ⏱️ 11.04.2022):

  ```
  git clone https://github.com/instacart/lore
  ```
* [PyPi](https://pypi.org/project/lore) (📥 530 / month):
  ```
  pip install lore
  ```

</details>
<details><summary><b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉19 ·  ⭐ 260) - 数据管道库luigi的包装。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/m3dev/gokart) ⭐ 342 | 🐛 33 | 🌐 Python | 📅 2026-08-07 (👨‍💻 34 · 🔀 45 · 📋 73 - 19% open · ⏱️ 02.08.2022):

  ```
  git clone https://github.com/m3dev/gokart
  ```
* [PyPi](https://pypi.org/project/gokart) (📥 1K / month):
  ```
  pip install gokart
  ```

</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉18 ·  ⭐ 380 · 💤) - Studio：简化和加快模型构建过程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/studioml/studio) ⭐ 383 | 🐛 58 | 🌐 Python | 📅 2024-07-06 (👨‍💻 21 · 🔀 51 · 📦 5 · 📋 250 - 22% open · ⏱️ 14.09.2021):

  ```
  git clone https://github.com/studioml/studio
  ```
* [PyPi](https://pypi.org/project/studioml) (📥 35 / month):
  ```
  pip install studioml
  ```

</details>
<details><summary><b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉18 ·  ⭐ 330 · 💀) - MXNet日志记录器，以在TensorBoard中进行可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/awslabs/mxboard) ⚠️ Archived (👨‍💻 9 · 🔀 46 · 📦 160 · 📋 31 - 51% open · ⏱️ 24.01.2020):

  ```
  git clone https://github.com/awslabs/mxboard
  ```
* [PyPi](https://pypi.org/project/mxboard) (📥 7.7K / month):
  ```
  pip install mxboard
  ```

</details>
<details><summary><b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉17 ·  ⭐ 350 · 💀) - pyspark方法可提高开发人员的工作效率。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/MrPowers/quinn) ⭐ 688 | 🐛 25 | 🌐 Python | 📅 2026-06-09 (👨‍💻 6 · 🔀 47 · 📋 24 - 58% open · ⏱️ 09.02.2021):

  ```
  git clone https://github.com/MrPowers/quinn
  ```
* [PyPi](https://pypi.org/project/quinn) (📥 770K / month):
  ```
  pip install quinn
  ```

</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉15 ·  ⭐ 620 · 💀) - 简易TensorBoard日志记录库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/TeamHG-Memex/tensorboard_logger) ⭐ 627 | 🐛 13 | 🌐 Python | 📅 2026-04-08 (👨‍💻 5 · 🔀 49 · 📋 24 - 37% open · ⏱️ 21.10.2019):

  ```
  git clone https://github.com/TeamHG-Memex/tensorboard_logger
  ```
* [PyPi](https://pypi.org/project/tensorboard_logger) (📥 56K / month):
  ```
  pip install tensorboard_logger
  ```

</details>
<details><summary><b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉15 ·  ⭐ 340 · 💀) - 面向数据科学家的开源生产模型管理工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/datmo/datmo) ⭐ 342 | 🐛 31 | 🌐 Python | 📅 2025-06-23 (👨‍💻 6 · 🔀 28 · 📦 5 · 📋 180 - 15% open · ⏱️ 29.11.2019):

  ```
  git clone https://github.com/datmo/datmo
  ```
* [PyPi](https://pypi.org/project/datmo) (📥 28 / month):
  ```
  pip install datmo
  ```

</details>
<details><summary><b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉15 ·  ⭐ 130 · 💀) - 轻量级的Python库，可进行快速且可重复的实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/minerva-ml/steppy) ⚠️ Archived (👨‍💻 5 · 🔀 33 · 📦 46 · 📋 63 - 20% open · ⏱️ 23.11.2018):

  ```
  git clone https://github.com/minerva-ml/steppy
  ```
* [PyPi](https://pypi.org/project/steppy) (📥 9 / month):
  ```
  pip install steppy
  ```

</details>
<details><summary><b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉14 ·  ⭐ 530 · 💤) - SciKit学习实验室（SKLL）使机器学习易于操作。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/EducationalTestingService/skll) ⭐ 560 | 🐛 21 | 🌐 Python | 📅 2025-06-12 (👨‍💻 37 · 🔀 65 · 📥 11 · 📦 38 · 📋 400 - 7% open · ⏱️ 21.12.2021):

  ```
  git clone https://github.com/EducationalTestingService/skll
  ```
* [PyPi](https://pypi.org/project/skll) (📥 140 / month):
  ```
  pip install skll
  ```

</details>
<details><summary><b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉14 ·  ⭐ 120 · 💤) - 机器和深度学习项目的实验跟踪。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/ModelChimp/modelchimp) ⭐ 128 | 🐛 42 | 🌐 JavaScript | 📅 2023-11-14 (👨‍💻 3 · 🔀 12 · 📋 14 - 28% open · ⏱️ 01.08.2021):

  ```
  git clone https://github.com/ModelChimp/modelchimp
  ```
* [PyPi](https://pypi.org/project/modelchimp) (📥 43 / month):
  ```
  pip install modelchimp
  ```
* [Docker Hub](https://hub.docker.com/r/modelchimp/modelchimp-server) (📥 660 · ⏱️ 09.04.2019):
  ```
  docker pull modelchimp/modelchimp-server
  ```

</details>
<details><summary><b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉7 ·  ⭐ 10 · 💀) - 一站式训练现成的机器学习模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jrieke/traintool) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-03-12 (⏱️ 12.03.2021):

  ```
  git clone https://github.com/jrieke/traintool
  ```
* [PyPi](https://pypi.org/project/traintool) (📥 10 / month):
  ```
  pip install traintool
  ```

</details>
<br>

## 模型序列化和转换

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于将模型序列化为文件，在各种模型格式之间进行转换以及优化模型以进行部署的库。*

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇32 ·  ⭐ 13K) - 机器学习互操作性的开放标准。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/onnx/onnx) ⭐ 21,349 | 🐛 287 | 🌐 Python | 📅 2026-08-23 (👨‍💻 250 · 🔀 2.9K · 📥 18K · 📦 8.1K · 📋 2K - 11% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/onnx/onnx
  ```
* [PyPi](https://pypi.org/project/onnx) (📥 1.6M / month):
  ```
  pip install onnx
  ```
* [Conda](https://anaconda.org/conda-forge/onnx) (📥 490K · ⏱️ 18.08.2022):
  ```
  conda install -c conda-forge onnx
  ```

</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇25 ·  ⭐ 2.8K) - 核心ML工具包含用于核心ML模型的支持工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/apple/coremltools) ⭐ 5,394 | 🐛 494 | 🌐 Python | 📅 2026-08-18 (👨‍💻 130 · 🔀 420 · 📥 4.4K · 📦 1K · 📋 970 - 28% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/apple/coremltools
  ```
* [PyPi](https://pypi.org/project/coremltools) (📥 93K / month):
  ```
  pip install coremltools
  ```

</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥇25 ·  ⭐ 2.2K) - 将ML模型转换成本机代码（Java，C，Python，Go，JavaScript）等。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,998 | 🐛 62 | 🌐 Python | 📅 2024-08-03 (👨‍💻 13 · 🔀 200 · 📥 32 · 📦 59 · 📋 92 - 26% open · ⏱️ 14.08.2022):

  ```
  git clone https://github.com/BayesWitnesses/m2cgen
  ```
* [PyPi](https://pypi.org/project/m2cgen) (📥 45K / month):
  ```
  pip install m2cgen
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈24 ·  ⭐ 2.8K) - 在PyTorch上进行模型服务。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/serve) ⚠️ Archived (👨‍💻 120 · 🔀 570 · 📥 2K · 📋 970 - 14% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pytorch/serve
  ```
* [PyPi](https://pypi.org/project/torchserve) (📥 17K / month):
  ```
  pip install torchserve
  ```
* [Conda](https://anaconda.org/pytorch/torchserve) (📥 33K · ⏱️ 13.05.2022):
  ```
  conda install -c pytorch torchserve
  ```
* [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 1M · ⭐ 15 · ⏱️ 19.07.2022):
  ```
  docker pull pytorch/torchserve
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥈23 ·  ⭐ 5.6K · 💀) - MMdnn是一组工具，可以帮助用户在不同的深度学习框架之间进行互操作。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/MMdnn) ⭐ 5,805 | 🐛 337 | 🌐 Python | 📅 2025-08-07 (👨‍💻 85 · 🔀 950 · 📥 3.6K · 📦 85 · 📋 610 - 52% open · ⏱️ 14.08.2020):

  ```
  git clone https://github.com/Microsoft/MMdnn
  ```
* [PyPi](https://pypi.org/project/mmdnn) (📥 580 / month):
  ```
  pip install mmdnn
  ```

</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥉22 ·  ⭐ 7.8K) - 具有成本效益的无服务器大规模计算。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/cortexlabs/cortex) ⭐ 8,011 | 🐛 132 | 🌐 Go | 📅 2024-06-12 (👨‍💻 24 · 🔀 580 · 📋 1.1K - 10% open · ⏱️ 23.04.2022):

  ```
  git clone https://github.com/cortexlabs/cortex
  ```
* [PyPi](https://pypi.org/project/cortex) (📥 1.7K / month):
  ```
  pip install cortex
  ```

</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥉22 ·  ⭐ 3K) - 蜂鸟将训练有素的机器学习模型编译为张量计算，以用于..<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/microsoft/hummingbird) ⭐ 3,544 | 🐛 75 | 🌐 Python | 📅 2025-07-17 (👨‍💻 31 · 🔀 240 · 📥 180 · 📦 39 · 📋 250 - 16% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/microsoft/hummingbird
  ```
* [PyPi](https://pypi.org/project/hummingbird-ml) (📥 3.9K / month):
  ```
  pip install hummingbird-ml
  ```

</details>
<details><summary><b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉20 ·  ⭐ 1.2K) - 将经过训练的scikit-learn估计器转换为C，Java等。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/nok/sklearn-porter) ⭐ 1,302 | 🐛 47 | 🌐 Python | 📅 2024-06-12 (👨‍💻 12 · 🔀 160 · 📦 44 · 📋 68 - 50% open · ⏱️ 22.05.2022):

  ```
  git clone https://github.com/nok/sklearn-porter
  ```
* [PyPi](https://pypi.org/project/sklearn-porter) (📥 340 / month):
  ```
  pip install sklearn-porter
  ```

</details>
<details><summary><b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉18 ·  ⭐ 810 · 💤) - PyTorch到Keras模型转换器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/gmalivenko/pytorch2keras) ⭐ 862 | 🐛 62 | 🌐 Python | 📅 2022-12-08 (👨‍💻 13 · 🔀 140 · 📦 51 · 📋 120 - 44% open · ⏱️ 06.08.2021):

  ```
  git clone https://github.com/nerox8664/pytorch2keras
  ```
* [PyPi](https://pypi.org/project/pytorch2keras) (📥 480 / month):
  ```
  pip install pytorch2keras
  ```

</details>
<details><summary><b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉17 ·  ⭐ 210) - 高度优化的二值化推理引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/larq/compute-engine) ⭐ 257 | 🐛 20 | 🌐 C++ | 📅 2026-07-30 (👨‍💻 18 · 🔀 32 · 📥 730 · 📦 6 · 📋 140 - 9% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/larq/compute-engine
  ```
* [PyPi](https://pypi.org/project/larq-compute-engine) (📥 870 / month):
  ```
  pip install larq-compute-engine
  ```

</details>
<details><summary><b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉14 ·  ⭐ 350 · 💀) - 部署张量流图以进行快速评估并导出到无tensorflow环境中基于numpy运行。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/riga/tfdeploy) ⭐ 353 | 🐛 12 | 🌐 Python | 📅 2025-01-04 (👨‍💻 4 · 🔀 36 · 📋 34 - 32% open · ⏱️ 08.01.2021):

  ```
  git clone https://github.com/riga/tfdeploy
  ```
* [PyPi](https://pypi.org/project/tfdeploy) (📥 9 / month):
  ```
  pip install tfdeploy
  ```

</details>
<br>

## 模型的可解释性

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于可视化，解释，调试，评估和解释机器学习模型的库。*

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇36 ·  ⭐ 17K) - 用于解释任何机器学习模型的输出的一种博弈论方法实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/slundberg/shap) ⭐ 25,698 | 🐛 1,010 | 🌐 Jupyter Notebook | 📅 2026-08-11 (👨‍💻 200 · 🔀 2.6K · 📦 6.4K · 📋 2K - 69% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/slundberg/shap
  ```
* [PyPi](https://pypi.org/project/shap) (📥 3.7M / month):
  ```
  pip install shap
  ```
* [Conda](https://anaconda.org/conda-forge/shap) (📥 1.4M · ⏱️ 20.06.2022):
  ```
  conda install -c conda-forge shap
  ```

</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇30 ·  ⭐ 10K · 💀) - Lime：解释任何机器学习分类器的预测。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/marcotcr/lime) ⭐ 12,166 | 🐛 133 | 🌐 JavaScript | 📅 2024-07-25 (👨‍💻 61 · 🔀 1.6K · 📦 2.6K · 📋 580 - 9% open · ⏱️ 29.07.2021):

  ```
  git clone https://github.com/marcotcr/lime
  ```
* [PyPi](https://pypi.org/project/lime) (📥 560K / month):
  ```
  pip install lime
  ```
* [Conda](https://anaconda.org/conda-forge/lime) (📥 110K · ⏱️ 28.06.2020):
  ```
  conda install -c conda-forge lime
  ```

</details>
<details><summary><b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥇29 ·  ⭐ 1.6K · 💀) - 用于交互式主题模型可视化的Python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/bmabey/pyLDAvis) ⭐ 1,851 | 🐛 81 | 🌐 Jupyter Notebook | 📅 2025-12-04 (👨‍💻 32 · 🔀 330 · 📦 3.8K · 📋 160 - 51% open · ⏱️ 24.03.2021):

  ```
  git clone https://github.com/bmabey/pyLDAvis
  ```
* [PyPi](https://pypi.org/project/pyldavis) (📥 640K / month):
  ```
  pip install pyldavis
  ```
* [Conda](https://anaconda.org/conda-forge/pyldavis) (📥 46K · ⏱️ 24.03.2021):
  ```
  conda install -c conda-forge pyldavis
  ```

</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇28 ·  ⭐ 4.9K) - 拟合可解释的模型。对机器学习黑匣子进行解释。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/interpretml/interpret) ⭐ 6,925 | 🐛 42 | 🌐 C++ | 📅 2026-08-17 (👨‍💻 31 · 🔀 590 · 📦 260 · 📋 300 - 32% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/interpretml/interpret
  ```
* [PyPi](https://pypi.org/project/interpret) (📥 90K / month):
  ```
  pip install interpret
  ```

</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥇28 ·  ⭐ 2.2K) - 用于决策树可视化和模型解释的python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/parrt/dtreeviz) ⭐ 3,155 | 🐛 75 | 🌐 Jupyter Notebook | 📅 2026-01-02 (👨‍💻 21 · 🔀 280 · 📦 450 · 📋 120 - 19% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/parrt/dtreeviz
  ```
* [PyPi](https://pypi.org/project/dtreeviz) (📥 96K / month):
  ```
  pip install dtreeviz
  ```

</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇28 ·  ⭐ 1.3K) - 使用Python探索性分析贝叶斯模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/arviz-devs/arviz) ⭐ 1,849 | 🐛 110 | 🌐 TeX | 📅 2026-08-17 (👨‍💻 130 · 🔀 290 · 📥 110 · 📦 2.7K · 📋 760 - 20% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/arviz-devs/arviz
  ```
* [PyPi](https://pypi.org/project/arviz) (📥 740K / month):
  ```
  pip install arviz
  ```
* [Conda](https://anaconda.org/conda-forge/arviz) (📥 810K · ⏱️ 13.07.2022):
  ```
  conda install -c conda-forge arviz
  ```

</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥈27 ·  ⭐ 3.4K) - PyTorch的模型可解释性和理解。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pytorch/captum) ⭐ 5,689 | 🐛 64 | 🌐 Python | 📅 2026-08-22 (👨‍💻 88 · 🔀 350 · 📦 650 · 📋 380 - 24% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/pytorch/captum
  ```
* [PyPi](https://pypi.org/project/captum) (📥 47K / month):
  ```
  pip install captum
  ```

</details>
<details><summary><b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈26 ·  ⭐ 2.2K · 💀) - 一个直观的库，可向其中添加绘图功能。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/reiinakano/scikit-plot) ⭐ 2,433 | 🐛 32 | 🌐 Python | 📅 2024-08-20 (👨‍💻 13 · 🔀 260 · 📦 2.3K · 📋 58 - 32% open · ⏱️ 19.08.2018):

  ```
  git clone https://github.com/reiinakano/scikit-plot
  ```
* [PyPi](https://pypi.org/project/scikit-plot) (📥 650K / month):
  ```
  pip install scikit-plot
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-plot) (📥 120K · ⏱️ 05.06.2019):
  ```
  conda install -c conda-forge scikit-plot
  ```

</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈26 ·  ⭐ 1.3K) - 快速构建可显示内部信息的可解释AI仪表板。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/oegedijk/explainerdashboard) ⭐ 2,510 | 🐛 0 | 🌐 Python | 📅 2026-02-11 (👨‍💻 15 · 🔀 160 · 📦 160 · 📋 180 - 8% open · ⏱️ 16.06.2022):

  ```
  git clone https://github.com/oegedijk/explainerdashboard
  ```
* [PyPi](https://pypi.org/project/explainerdashboard) (📥 59K / month):
  ```
  pip install explainerdashboard
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥈26 ·  ⭐ 1.2K) - TensorFlow的模型分析工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/model-analysis) ⭐ 1,265 | 🐛 19 | 🌐 Python | 📅 2026-08-14 (👨‍💻 47 · 🔀 240 · 📋 65 - 24% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/tensorflow/model-analysis
  ```
* [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 1M / month):
  ```
  pip install tensorflow-model-analysis
  ```

</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈25 ·  ⭐ 1.7K) - 监视和解释机器学习模型的算法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/SeldonIO/alibi) ⭐ 2,643 | 🐛 159 | 🌐 Python | 📅 2025-10-17 (👨‍💻 18 · 🔀 190 · 📦 190 · 📋 300 - 36% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/SeldonIO/alibi
  ```
* [PyPi](https://pypi.org/project/alibi) (📥 15K / month):
  ```
  pip install alibi
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥈24 ·  ⭐ 4.4K · 💀) - 用于神经科学研究的基础设施和工具的集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/lucid) ⚠️ Archived (👨‍💻 40 · 🔀 600 · 📦 650 · 📋 170 - 42% open · ⏱️ 19.03.2021):

  ```
  git clone https://github.com/tensorflow/lucid
  ```
* [PyPi](https://pypi.org/project/lucid) (📥 2K / month):
  ```
  pip install lucid
  ```

</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈24 ·  ⭐ 1.8K) - 一整套用于数据集的公平度量标准。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Trusted-AI/AIF360) ⭐ 2,857 | 🐛 220 | 🌐 Python | 📅 2026-06-15 (👨‍💻 52 · 🔀 580 · 📦 170 · 📋 140 - 54% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/Trusted-AI/AIF360
  ```
* [PyPi](https://pypi.org/project/aif360) (📥 7.3K / month):
  ```
  pip install aif360
  ```

</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥈24 ·  ⭐ 1.6K) - 一个可帮助数据科学家进行因果推断的Python库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 22 · 🔀 180 · 📦 53 · 📋 110 - 17% open · ⏱️ 06.07.2022):

  ```
  git clone https://github.com/quantumblacklabs/causalnex
  ```
* [PyPi](https://pypi.org/project/causalnex) (📥 1.3K / month):
  ```
  pip install causalnex
  ```

</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥈24 ·  ⭐ 1.1K) - 数据和机器学习的可解释性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/Trusted-AI/AIX360) ⭐ 1,795 | 🐛 55 | 🌐 Python | 📅 2026-08-08 (👨‍💻 31 · 🔀 240 · 📦 55 · 📋 65 - 56% open · ⏱️ 26.07.2022):

  ```
  git clone https://github.com/Trusted-AI/AIX360
  ```
* [PyPi](https://pypi.org/project/aix360) (📥 1.2K / month):
  ```
  pip install aix360
  ```

</details>
<details><summary><b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥈23 ·  ⭐ 2.9K · 💀) - 用于Keras的神经网络可视化工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/raghakot/keras-vis) ⭐ 2,991 | 🐛 116 | 🌐 Python | 📅 2022-02-07 (👨‍💻 10 · 🔀 630 · 📦 2.1K · 📋 210 - 52% open · ⏱️ 20.04.2020):

  ```
  git clone https://github.com/raghakot/keras-vis
  ```
* [PyPi](https://pypi.org/project/keras-vis) (📥 3.3K / month):
  ```
  pip install keras-vis
  ```

</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥈22 ·  ⭐ 3.7K) - 可视化分析和诊断工具，方便机器使用。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/DistrictDataLabs/yellowbrick) ⭐ 4,401 | 🐛 117 | 🌐 Python | 📅 2025-02-19 (👨‍💻 110 · 🔀 510 · 📋 670 - 11% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/DistrictDataLabs/yellowbrick
  ```
* [PyPi](https://pypi.org/project/yellowbrick) (📥 580K / month):
  ```
  pip install yellowbrick
  ```

</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈22 ·  ⭐ 2.6K · 💀) - 一个用于调试/检查机器学习分类器的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/TeamHG-Memex/eli5) ⭐ 2,788 | 🐛 162 | 🌐 Jupyter Notebook | 📅 2026-04-08 (👨‍💻 14 · 🔀 310 · 📋 250 - 55% open · ⏱️ 22.01.2020):

  ```
  git clone https://github.com/TeamHG-Memex/eli5
  ```
* [PyPi](https://pypi.org/project/eli5) (📥 480K / month):
  ```
  pip install eli5
  ```
* [Conda](https://anaconda.org/conda-forge/eli5) (📥 120K · ⏱️ 14.05.2022):
  ```
  conda install -c conda-forge eli5
  ```

</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥈22 ·  ⭐ 890) - 可解释的ML包，用于简洁，透明和准确的预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/csinva/imodels) ⭐ 1,617 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-08-03 (👨‍💻 13 · 🔀 83 · 📦 20 · 📋 40 - 35% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/csinva/imodels
  ```
* [PyPi](https://pypi.org/project/imodels) (📥 19K / month):
  ```
  pip install imodels
  ```

</details>
<details><summary><b><a href="https://github.com/py-why/dowhy">DoWhy</a></b> (🥉21 ·  ⭐ 5.1K) - DoWhy是用于因果推断的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/py-why/dowhy) ⭐ 8,276 | 🐛 231 | 🌐 Python | 📅 2026-08-23 (👨‍💻 60 · 🔀 700 · 📥 31 · 📋 250 - 31% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/Microsoft/dowhy
  ```
* [PyPi](https://pypi.org/project/dowhy) (📥 180K / month):
  ```
  pip install dowhy
  ```
* [Conda](https://anaconda.org/conda-forge/dowhy) (📥 8.2K · ⏱️ 19.07.2022):
  ```
  conda install -c conda-forge dowhy
  ```

</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥉21 ·  ⭐ 1.7K) - 超越准确性：使用CheckList对NLP模型进行行为测试。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/marcotcr/checklist) ⭐ 2,050 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2024-01-09 (👨‍💻 13 · 🔀 170 · 📦 150 · 📋 83 - 2% open · ⏱️ 12.08.2022):

  ```
  git clone https://github.com/marcotcr/checklist
  ```
* [PyPi](https://pypi.org/project/checklist) (📥 7.8K / month):
  ```
  pip install checklist
  ```

</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥉21 ·  ⭐ 1.4K) - 一个用于评估和改善机器公平性的Python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/fairlearn/fairlearn) ⭐ 2,273 | 🐛 122 | 🌐 Python | 📅 2026-08-22 (👨‍💻 68 · 🔀 310 · 📋 360 - 39% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/fairlearn/fairlearn
  ```
* [PyPi](https://pypi.org/project/fairlearn) (📥 230K / month):
  ```
  pip install fairlearn
  ```
* [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 20K · ⏱️ 07.07.2021):
  ```
  conda install -c conda-forge fairlearn
  ```

</details>
<details><summary><b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉21 ·  ⭐ 1.1K) - 用于模型探索和扩展的模块。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/ModelOriented/DALEX) ⭐ 1,485 | 🐛 31 | 🌐 Python | 📅 2026-07-15 (👨‍💻 20 · 🔀 140 · 📦 57 · 📋 370 - 5% open · ⏱️ 03.08.2022):

  ```
  git clone https://github.com/ModelOriented/DALEX
  ```
* [PyPi](https://pypi.org/project/dalex) (📥 9.5K / month):
  ```
  pip install dalex
  ```

</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥉21 ·  ⭐ 990) - 在Keras中分层输出和渐变。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/philipperemy/keract) ⭐ 1,059 | 🐛 3 | 🌐 Python | 📅 2025-04-07 (👨‍💻 16 · 🔀 180 · 📦 140 · 📋 87 - 5% open · ⏱️ 23.07.2022):

  ```
  git clone https://github.com/philipperemy/keract
  ```
* [PyPi](https://pypi.org/project/keract) (📥 900 / month):
  ```
  pip install keract
  ```

</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉21 ·  ⭐ 940) - 使用Tensorflow 2.x的tf.keras模型的可解释性方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/sicara/tf-explain) ⭐ 1,037 | 🐛 47 | 🌐 Python | 📅 2024-06-03 (👨‍💻 18 · 🔀 100 · 📦 130 · 📋 88 - 42% open · ⏱️ 30.06.2022):

  ```
  git clone https://github.com/sicara/tf-explain
  ```
* [PyPi](https://pypi.org/project/tf-explain) (📥 1.1K / month):
  ```
  pip install tf-explain
  ```

</details>
<details><summary><b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥉21 ·  ⭐ 510 · 💀) - 随机森林特征重要度计算。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/parrt/random-forest-importances) ⭐ 624 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-03-24 (👨‍💻 14 · 🔀 120 · 📦 100 · 📋 34 - 14% open · ⏱️ 30.01.2021):

  ```
  git clone https://github.com/parrt/random-forest-importances
  ```
* [PyPi](https://pypi.org/project/rfpimp) (📥 30K / month):
  ```
  pip install rfpimp
  ```

</details>
<details><summary><b><a href="https://github.com/ploomber/sklearn-evaluation">sklearn-evaluation</a></b> (🥉21 ·  ⭐ 340) - 机器学习模型评估变得容易。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/ploomber/sklearn-evaluation) ⚠️ Archived (👨‍💻 8 · 🔀 28 · 📦 49 · 📋 39 - 20% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/edublancas/sklearn-evaluation
  ```
* [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 1.7K / month):
  ```
  pip install sklearn-evaluation
  ```

</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉20 ·  ⭐ 890) - 生成任何机器学习的各种反事实说明。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/interpretml/DiCE) ⭐ 1,524 | 🐛 102 | 🌐 Python | 📅 2025-07-13 (👨‍💻 14 · 🔀 120 · 📋 130 - 44% open · ⏱️ 06.07.2022):

  ```
  git clone https://github.com/interpretml/DiCE
  ```
* [PyPi](https://pypi.org/project/dice-ml) (📥 140K / month):
  ```
  pip install dice-ml
  ```

</details>
<details><summary><b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉20 ·  ⭐ 720 · 💀) - 解释scikit-learn决策树的程序包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/andosa/treeinterpreter) ⭐ 759 | 🐛 26 | 🌐 Python | 📅 2023-07-18 (👨‍💻 11 · 🔀 140 · 📦 280 · 📋 23 - 82% open · ⏱️ 28.02.2021):

  ```
  git clone https://github.com/andosa/treeinterpreter
  ```
* [PyPi](https://pypi.org/project/treeinterpreter) (📥 150K / month):
  ```
  pip install treeinterpreter
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉19 ·  ⭐ 3K) - 语言可解释性工具：交互式分析NLP模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PAIR-code/lit) ⭐ 3,659 | 🐛 138 | 🌐 TypeScript | 📅 2026-07-29 (👨‍💻 18 · 🔀 310 · 📦 11 · 📋 110 - 37% open · ⏱️ 15.03.2022):

  ```
  git clone https://github.com/PAIR-code/lit
  ```
* [PyPi](https://pypi.org/project/lit-nlp) (📥 820 / month):
  ```
  pip install lit-nlp
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉19 ·  ⭐ 740 · 💤) - What-If工具的源代码/网页/演示。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/PAIR-code/what-if-tool) ⭐ 1,007 | 🐛 97 | 🌐 HTML | 📅 2026-06-21 (👨‍💻 20 · 🔀 140 · 📋 110 - 52% open · ⏱️ 05.01.2022):

  ```
  git clone https://github.com/PAIR-code/what-if-tool
  ```
* [PyPi](https://pypi.org/project/witwidget) (📥 11K / month):
  ```
  pip install witwidget
  ```
* [NPM](https://www.npmjs.com/package/wit-widget) (📥 5.9K / month):
  ```
  npm install wit-widget
  ```

</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉19 ·  ⭐ 650 · 💤) - Public facing deeplift repo。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/kundajelab/deeplift) ⭐ 881 | 🐛 43 | 🌐 Python | 📅 2022-04-28 (👨‍💻 11 · 🔀 150 · 📦 62 · 📋 85 - 43% open · ⏱️ 11.11.2021):

  ```
  git clone https://github.com/kundajelab/deeplift
  ```
* [PyPi](https://pypi.org/project/deeplift) (📥 530 / month):
  ```
  pip install deeplift
  ```

</details>
<details><summary><b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉19 ·  ⭐ 490 · 💀) - 偏差和公平审计工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/dssg/aequitas) ⭐ 771 | 🐛 55 | 🌐 Python | 📅 2026-05-12 (👨‍💻 16 · 🔀 90 · 📦 110 · 📋 61 - 65% open · ⏱️ 27.05.2021):

  ```
  git clone https://github.com/dssg/aequitas
  ```
* [PyPi](https://pypi.org/project/aequitas) (📥 2K / month):
  ```
  pip install aequitas
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉19 ·  ⭐ 300) - 模型解释与分析卡片工具库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/tensorflow/model-card-toolkit) ⚠️ Archived (👨‍💻 13 · 🔀 60 · 📦 10 · 📋 14 - 85% open · ⏱️ 28.04.2022):

  ```
  git clone https://github.com/tensorflow/model-card-toolkit
  ```
* [PyPi](https://pypi.org/project/model-card-toolkit) (📥 850 / month):
  ```
  pip install model-card-toolkit
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉19 ·  ⭐ 270) - Tensorflow的公平性评估和可视化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/fairness-indicators) ⭐ 358 | 🐛 32 | 🌐 Python | 📅 2026-07-10 (👨‍💻 33 · 🔀 68 · 📋 11 - 27% open · ⏱️ 26.07.2022):

  ```
  git clone https://github.com/tensorflow/fairness-indicators
  ```
* [PyPi](https://pypi.org/project/fairness-indicators) (📥 620 / month):
  ```
  pip install fairness-indicators
  ```

</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉18 ·  ⭐ 1K) - 神经网络预估分析工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/albermax/innvestigate) ⭐ 1,308 | 🐛 61 | 🌐 Python | 📅 2025-04-11 (👨‍💻 19 · 🔀 220 · 📥 16 · 📋 230 - 19% open · ⏱️ 01.08.2022):

  ```
  git clone https://github.com/albermax/innvestigate
  ```
* [PyPi](https://pypi.org/project/innvestigate) (📥 440 / month):
  ```
  pip install innvestigate
  ```

</details>
<details><summary><b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉17 ·  ⭐ 1K) - 用于模型解释/说明的Python库。<code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code></summary>

* [GitHub](https://github.com/oracle/Skater) (👨‍💻 36 · 🔀 170 · 📋 160 - 40% open · ⏱️ 11.02.2022):

  ```
  git clone https://github.com/oracle/Skater
  ```
* [PyPi](https://pypi.org/project/skater) (📥 3K / month):
  ```
  pip install skater
  ```
* [Conda](https://anaconda.org/conda-forge/skater) (📥 51K · ⏱️ 15.11.2021):
  ```
  conda install -c conda-forge skater
  ```

</details>
<details><summary><b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉17 ·  ⭐ 680 · 💀) - PyTorch中用于神经网络的可视化工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/MisaOgura/flashtorch) ⭐ 743 | 🐛 10 | 🌐 HTML | 📅 2023-09-21 (👨‍💻 2 · 🔀 84 · 📦 10 · 📋 31 - 29% open · ⏱️ 27.04.2021):

  ```
  git clone https://github.com/MisaOgura/flashtorch
  ```
* [PyPi](https://pypi.org/project/flashtorch) (📥 160 / month):
  ```
  pip install flashtorch
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉17 ·  ⭐ 530 · 💤) - TCAV ML可解释性项目的代码。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/tcav) ⭐ 654 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-07-22 (👨‍💻 19 · 🔀 130 · 📦 14 · 📋 61 - 11% open · ⏱️ 16.09.2021):

  ```
  git clone https://github.com/tensorflow/tcav
  ```
* [PyPi](https://pypi.org/project/tcav) (📥 48 / month):
  ```
  pip install tcav
  ```

</details>
<details><summary><b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉17 ·  ⭐ 320 · 💀) - 适用于数据科学家的可解释AI框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/explainX/explainx) ⭐ 451 | 🐛 6 | 🌐 Python | 📅 2026-07-13 (👨‍💻 4 · 🔀 42 · 📥 4 · 📋 26 - 34% open · ⏱️ 02.02.2021):

  ```
  git clone https://github.com/explainX/explainx
  ```
* [PyPi](https://pypi.org/project/explainx) (📥 1.9K / month):
  ```
  pip install explainx
  ```

</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉15 ·  ⭐ 840 · 💤) - XAI-用于机器学习的可解释性工具箱。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/EthicalML/xai) ⭐ 1,259 | 🐛 1 | 🌐 Python | 📅 2025-11-29 (👨‍💻 3 · 🔀 120 · 📦 19 · 📋 9 - 22% open · ⏱️ 30.10.2021):

  ```
  git clone https://github.com/EthicalML/xai
  ```
* [PyPi](https://pypi.org/project/xai) (📥 120 / month):
  ```
  pip install xai
  ```

</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉15 ·  ⭐ 720) - High-Precision Model-Agnostic Explanations论文代码。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/marcotcr/anchor) ⭐ 816 | 🐛 26 | 🌐 Jupyter Notebook | 📅 2022-07-19 (👨‍💻 10 · 🔀 99 · 📋 70 - 27% open · ⏱️ 19.07.2022):

  ```
  git clone https://github.com/marcotcr/anchor
  ```
* [PyPi](https://pypi.org/project/anchor_exp) (📥 1.2K / month):
  ```
  pip install anchor_exp
  ```

</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉15 ·  ⭐ 480) - Leave One Feature Out特征重要度。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/aerdem4/lofo-importance) ⭐ 870 | 🐛 3 | 🌐 Python | 📅 2025-02-14 (👨‍💻 3 · 🔀 56 · 📦 19 · 📋 18 - 11% open · ⏱️ 27.04.2022):

  ```
  git clone https://github.com/aerdem4/lofo-importance
  ```
* [PyPi](https://pypi.org/project/lofo-importance) (📥 310 / month):
  ```
  pip install lofo-importance
  ```

</details>
<details><summary><b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉13 ·  ⭐ 81 · 💤) - AI 模型可解释性工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/SAP/contextual-ai) ⚠️ Archived (👨‍💻 12 · 🔀 10 · 📋 12 - 8% open · ⏱️ 11.11.2021):

  ```
  git clone https://github.com/SAP/contextual-ai
  ```
* [PyPi](https://pypi.org/project/contextual-ai) (📥 65 / month):
  ```
  pip install contextual-ai
  ```

</details>
<details><summary><b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉11 ·  ⭐ 100 · 💀) - 训练可解释模型的工具。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/suinleelab/attributionpriors) ⭐ 128 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2021-03-19 (👨‍💻 6 · 🔀 10 · 📦 3 · 📋 5 - 40% open · ⏱️ 19.03.2021):

  ```
  git clone https://github.com/suinleelab/attributionpriors
  ```
* [PyPi](https://pypi.org/project/attributionpriors) (📥 18 / month):
  ```
  pip install attributionpriors
  ```

</details>
<details><summary><b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉11 ·  ⭐ 40 · 💤) - Bias Detector是用于检测机器偏差的python软件包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/intuit/bias-detector) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2024-02-04 (👨‍💻 4 · 🔀 11 · ⏱️ 20.12.2021):

  ```
  git clone https://github.com/intuit/bias-detector
  ```
* [PyPi](https://pypi.org/project/bias-detector) (📥 48 / month):
  ```
  pip install bias-detector
  ```

</details>
<br>

## 向量相似度搜索（ANN）

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于近似最近邻居搜索和向量索引/相似性搜索的库。*

🔗 <b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 3K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥇31 ·  ⭐ 10K) - C++/Python中的近似最近邻居实现，并针对内存使用进行了优化。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/spotify/annoy) ⭐ 14,288 | 🐛 86 | 🌐 C++ | 📅 2025-10-29 (👨‍💻 82 · 🔀 1K · 📦 2.2K · 📋 350 - 10% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/spotify/annoy
  ```
* [PyPi](https://pypi.org/project/annoy) (📥 1.5M / month):
  ```
  pip install annoy
  ```

</details>
<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥇29 ·  ⭐ 12K) - 一个开源的embedding嵌入向量相似度搜索引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/milvus-io/milvus) ⭐ 45,750 | 🐛 1,310 | 🌐 Go | 📅 2026-08-23 (👨‍💻 220 · 🔀 1.4K · 📥 44K · 📋 5.7K - 4% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/milvus-io/milvus
  ```
* [PyPi](https://pypi.org/project/pymilvus) (📥 130K / month):
  ```
  pip install pymilvus
  ```
* [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 1.3M · ⭐ 21 · ⏱️ 26.08.2022):
  ```
  docker pull milvusdb/milvus
  ```

</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥈28 ·  ⭐ 2.8K) - 非度量空间库（NMSLIB）：一种有效的相似度搜索。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nmslib/nmslib) ⭐ 3,589 | 🐛 74 | 🌐 C++ | 📅 2026-04-13 (👨‍💻 48 · 🔀 400 · 📦 660 · 📋 400 - 14% open · ⏱️ 31.05.2022):

  ```
  git clone https://github.com/nmslib/nmslib
  ```
* [PyPi](https://pypi.org/project/nmslib) (📥 120K / month):
  ```
  pip install nmslib
  ```
* [Conda](https://anaconda.org/conda-forge/nmslib) (📥 61K · ⏱️ 15.04.2022):
  ```
  conda install -c conda-forge nmslib
  ```

</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥈28 ·  ⭐ 660) - 适用于近似最近邻查找的Python库。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/lmcinnes/pynndescent) ⭐ 970 | 🐛 79 | 🌐 Python | 📅 2026-08-01 (👨‍💻 21 · 🔀 88 · 📦 2K · 📋 110 - 47% open · ⏱️ 21.07.2022):

  ```
  git clone https://github.com/lmcinnes/pynndescent
  ```
* [PyPi](https://pypi.org/project/pynndescent) (📥 610K / month):
  ```
  pip install pynndescent
  ```
* [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 850K · ⏱️ 15.05.2022):
  ```
  conda install -c conda-forge pynndescent
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥈27 ·  ⭐ 18K) - 一个用于高效相似性搜索和密集向量聚类的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/facebookresearch/faiss) ⭐ 40,796 | 🐛 288 | 🌐 C++ | 📅 2026-08-19 (👨‍💻 100 · 🔀 2.6K · 📦 720 · 📋 1.9K - 11% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/facebookresearch/faiss
  ```
* [PyPi](https://pypi.org/project/pymilvus) (📥 130K / month):
  ```
  pip install pymilvus
  ```
* [Conda](https://anaconda.org/conda-forge/faiss) (📥 450K · ⏱️ 09.02.2022):
  ```
  conda install -c conda-forge faiss
  ```

</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥈27 ·  ⭐ 2.1K) - 仅标头的C++/python库，用于快速近似最近邻查找。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/nmslib/hnswlib) ⭐ 5,308 | 🐛 286 | 🌐 C++ | 📅 2026-03-28 (👨‍💻 56 · 🔀 380 · 📦 280 · 📋 250 - 50% open · ⏱️ 16.04.2022):

  ```
  git clone https://github.com/nmslib/hnswlib
  ```
* [PyPi](https://pypi.org/project/hnswlib) (📥 430K / month):
  ```
  pip install hnswlib
  ```

</details>
<details><summary><b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉22 ·  ⭐ 1.5K · 💀) - 快速，高效的通用向量嵌入实用程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/plasticityai/magnitude) ⭐ 1,668 | 🐛 41 | 🌐 Python | 📅 2023-08-03 (👨‍💻 4 · 🔀 110 · 📦 240 · 📋 83 - 38% open · ⏱️ 17.07.2020):

  ```
  git clone https://github.com/plasticityai/magnitude
  ```
* [PyPi](https://pypi.org/project/pymagnitude) (📥 3.1K / month):
  ```
  pip install pymagnitude
  ```

</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉19 ·  ⭐ 930) - 最近邻搜索算法实现包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/yahoojapan/NGT) ⭐ 1,370 | 🐛 30 | 🌐 C++ | 📅 2026-07-27 (👨‍💻 14 · 🔀 94 · 📋 100 - 11% open · ⏱️ 15.08.2022):

  ```
  git clone https://github.com/yahoojapan/NGT
  ```
* [PyPi](https://pypi.org/project/ngt) (📥 16K / month):
  ```
  pip install ngt
  ```

</details>
<details><summary><b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉19 ·  ⭐ 710 · 💀) - 用于快速（近似）最近邻搜索的Python框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pixelogik/NearPy) ⭐ 771 | 🐛 28 | 🌐 Python | 📅 2023-02-23 (👨‍💻 18 · 🔀 140 · 📦 70 · 📋 62 - 38% open · ⏱️ 21.10.2018):

  ```
  git clone https://github.com/pixelogik/NearPy
  ```
* [PyPi](https://pypi.org/project/NearPy) (📥 1.3K / month):
  ```
  pip install NearPy
  ```

</details>
<details><summary><b><a href="https://github.com/kakao/n2">N2</a></b> (🥉18 ·  ⭐ 520 · 💀) - TOROS N2-快速运行的轻量级近似最近邻库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/kakao/n2) ⭐ 582 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2023-06-27 (👨‍💻 18 · 🔀 64 · 📦 23 · 📋 33 - 33% open · ⏱️ 20.05.2021):

  ```
  git clone https://github.com/kakao/n2
  ```
* [PyPi](https://pypi.org/project/n2) (📥 860 / month):
  ```
  pip install n2
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 900 · 💀) - C++/Python中的近似最近邻居实现，并针对内存使用进行了优化。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/facebookresearch/pysparnn) ⚠️ Archived (👨‍💻 5 · 🔀 140 · 📋 29 - 51% open · ⏱️ 31.01.2018):

  ```
  git clone https://github.com/facebookresearch/pysparnn
  ```

</details>
<br>

## 概率统计

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*提供概率编程/推理，贝叶斯推理，高斯过程或统计信息的功能的库。*

<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇30 ·  ⭐ 7.6K) - 使用Python和PyTorch进行深度通用概率编程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pyro-ppl/pyro) ⭐ 9,037 | 🐛 284 | 🌐 Python | 📅 2026-08-04 (👨‍💻 130 · 🔀 900 · 📦 820 · 📋 970 - 20% open · ⏱️ 05.08.2022):

  ```
  git clone https://github.com/pyro-ppl/pyro
  ```
* [PyPi](https://pypi.org/project/pyro-ppl) (📥 460K / month):
  ```
  pip install pyro-ppl
  ```

</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥇29 ·  ⭐ 2.8K) - 高斯过程的高效和模块化实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/cornellius-gp/gpytorch) ⭐ 3,905 | 🐛 411 | 🌐 Python | 📅 2026-07-10 (👨‍💻 99 · 🔀 420 · 📦 680 · 📋 1.1K - 24% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/cornellius-gp/gpytorch
  ```
* [PyPi](https://pypi.org/project/gpytorch) (📥 260K / month):
  ```
  pip install gpytorch
  ```

</details>
<details><summary><b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥇28 ·  ⭐ 2.4K) - Python卡尔曼过滤和最佳估计库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/rlabbe/filterpy) ⭐ 3,860 | 🐛 85 | 🌐 Python | 📅 2024-02-07 (👨‍💻 43 · 🔀 520 · 📦 1.6K · 📋 200 - 23% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/rlabbe/filterpy
  ```
* [PyPi](https://pypi.org/project/filterpy) (📥 760K / month):
  ```
  pip install filterpy
  ```
* [Conda](https://anaconda.org/conda-forge/filterpy) (📥 140K · ⏱️ 05.05.2020):
  ```
  conda install -c conda-forge filterpy
  ```

</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥇28 ·  ⭐ 1.7K) - TensorFlow中的高斯过程。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/GPflow/GPflow) ⭐ 1,916 | 🐛 168 | 🌐 Python | 📅 2026-08-10 (👨‍💻 78 · 🔀 410 · 📦 390 · 📋 780 - 15% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/GPflow/GPflow
  ```
* [PyPi](https://pypi.org/project/gpflow) (📥 16K / month):
  ```
  pip install gpflow
  ```
* [Conda](https://anaconda.org/conda-forge/gpflow) (📥 15K · ⏱️ 24.05.2022):
  ```
  conda install -c conda-forge gpflow
  ```

</details>
<details><summary><b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥈27 ·  ⭐ 1.2K) - 基于Pandas的Python统计软件包。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

* [GitHub](https://github.com/raphaelvallat/pingouin) ⭐ 1,928 | 🐛 14 | 🌐 Python | 📅 2026-04-05 (👨‍💻 33 · 🔀 110 · 📦 680 · 📋 220 - 14% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/raphaelvallat/pingouin
  ```
* [PyPi](https://pypi.org/project/pingouin) (📥 59K / month):
  ```
  pip install pingouin
  ```
* [Conda](https://anaconda.org/conda-forge/pingouin) (📥 66K · ⏱️ 24.06.2022):
  ```
  conda install -c conda-forge pingouin
  ```

</details>
<details><summary><b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥈27 ·  ⭐ 850) - 使用符号公式描述Python中的统计模型。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/pydata/patsy) ⭐ 989 | 🐛 78 | 🌐 Python | 📅 2026-08-17 (👨‍💻 17 · 🔀 88 · 📦 56K · 📋 130 - 46% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/pydata/patsy
  ```
* [PyPi](https://pypi.org/project/patsy) (📥 7.5M / month):
  ```
  pip install patsy
  ```
* [Conda](https://anaconda.org/conda-forge/patsy) (📥 5.5M · ⏱️ 26.09.2021):
  ```
  conda install -c conda-forge patsy
  ```

</details>
<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥈26 ·  ⭐ 6.9K) - Python中的概率编程。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/pymc-devs/pymc) ⭐ 9,720 | 🐛 480 | 🌐 Python | 📅 2026-08-17 (👨‍💻 410 · 🔀 1.6K · 📥 1.9K · 📦 690 · 📋 2.8K - 6% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/pymc-devs/pymc3
  ```
* [PyPi](https://pypi.org/project/pymc3) (📥 410K / month):
  ```
  pip install pymc3
  ```
* [Conda](https://anaconda.org/conda-forge/pymc3) (📥 440K · ⏱️ 20.05.2022):
  ```
  conda install -c conda-forge pymc3
  ```

</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈26 ·  ⭐ 2.9K) - 在Python中快速，灵活且易于使用的概率建模。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/jmschrei/pomegranate) ⭐ 3,541 | 🐛 44 | 🌐 Python | 📅 2025-03-06 (👨‍💻 66 · 🔀 530 · 📦 740 · 📋 670 - 8% open · ⏱️ 04.07.2022):

  ```
  git clone https://github.com/jmschrei/pomegranate
  ```
* [PyPi](https://pypi.org/project/pomegranate) (📥 53K / month):
  ```
  pip install pomegranate
  ```
* [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 95K · ⏱️ 16.11.2021):
  ```
  conda install -c conda-forge pomegranate
  ```

</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥈26 ·  ⭐ 2.6K) - Python中的隐马尔可夫模型，具有类似于scikit-learn的API。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/hmmlearn/hmmlearn) ⭐ 3,414 | 🐛 80 | 🌐 Python | 📅 2024-10-31 (👨‍💻 41 · 🔀 660 · 📦 1.4K · 📋 390 - 13% open · ⏱️ 04.07.2022):

  ```
  git clone https://github.com/hmmlearn/hmmlearn
  ```
* [PyPi](https://pypi.org/project/hmmlearn) (📥 110K / month):
  ```
  pip install hmmlearn
  ```
* [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 130K · ⏱️ 12.02.2022):
  ```
  conda install -c conda-forge hmmlearn
  ```

</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥉25 ·  ⭐ 2.1K) - 用于学习（结构和参数）和推理的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pgmpy/pgmpy) ⭐ 3,318 | 🐛 625 | 🌐 Python | 📅 2026-08-19 (👨‍💻 110 · 🔀 630 · 📥 160 · 📦 400 · 📋 770 - 24% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/pgmpy/pgmpy
  ```
* [PyPi](https://pypi.org/project/pgmpy) (📥 57K / month):
  ```
  pip install pgmpy
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥉24 ·  ⭐ 3.8K) - 概率推理与统计分析。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/probability) ⭐ 4,427 | 🐛 726 | 🌐 Jupyter Notebook | 📅 2026-08-06 (👨‍💻 460 · 🔀 960 · 📋 1.2K - 42% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/tensorflow/probability
  ```
* [PyPi](https://pypi.org/project/tensorflow-probability) (📥 910K / month):
  ```
  pip install tensorflow-probability
  ```
* [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 70K · ⏱️ 08.08.2022):
  ```
  conda install -c conda-forge tensorflow-probability
  ```

</details>
<details><summary><b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉23 ·  ⭐ 4.7K · 💀) - TensorFlow中的一种概率编程语言。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/blei-lab/edward) ⭐ 4,843 | 🐛 219 | 🌐 Jupyter Notebook | 📅 2024-03-18 (👨‍💻 87 · 🔀 750 · 📥 15 · 📦 270 · 📋 510 - 36% open · ⏱️ 25.07.2018):

  ```
  git clone https://github.com/blei-lab/edward
  ```
* [PyPi](https://pypi.org/project/edward) (📥 1.3K / month):
  ```
  pip install edward
  ```

</details>
<details><summary><b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉21 ·  ⭐ 1.5K) - 用于贝叶斯预测的Python软件包，具有面向对象的设计。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/uber/orbit) ⭐ 2,068 | 🐛 59 | 🌐 Python | 📅 2026-05-22 (👨‍💻 18 · 🔀 110 · 📦 9 · 📋 370 - 12% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/uber/orbit
  ```
* [PyPi](https://pypi.org/project/orbit-ml) (📥 300K / month):
  ```
  pip install orbit-ml
  ```

</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉20 ·  ⭐ 820) - Python中的贝叶斯模型构建接口（Bambi）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/bambinos/bambi) ⭐ 1,295 | 🐛 93 | 🌐 Python | 📅 2026-08-15 (👨‍💻 26 · 🔀 89 · 📦 32 · 📋 270 - 18% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/bambinos/bambi
  ```
* [PyPi](https://pypi.org/project/bambi) (📥 6.7K / month):
  ```
  pip install bambi
  ```

</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉20 ·  ⭐ 620) - Python（Numpy）中的灵敏度分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/SALib/SALib) ⭐ 1,005 | 🐛 73 | 🌐 Python | 📅 2026-07-17 (👨‍💻 37 · 🔀 190 · 📋 280 - 15% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/SALib/SALib
  ```
* [PyPi](https://pypi.org/project/salib) (📥 160K / month):
  ```
  pip install salib
  ```
* [Conda](https://anaconda.org/conda-forge/salib) (📥 90K · ⏱️ 04.09.2021):
  ```
  conda install -c conda-forge salib
  ```

</details>
<details><summary><b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉20 ·  ⭐ 250) - Python中的多个成对比较（Post Hoc）测试。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/maximtrp/scikit-posthocs) ⭐ 386 | 🐛 1 | 🌐 Python | 📅 2026-08-23 (👨‍💻 10 · 🔀 28 · 📥 25 · 📋 47 - 12% open · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/maximtrp/scikit-posthocs
  ```
* [PyPi](https://pypi.org/project/scikit-posthocs) (📥 40K / month):
  ```
  pip install scikit-posthocs
  ```

</details>
<details><summary><b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉19 ·  ⭐ 200) - 用于概率编程的函数张量。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/pyro-ppl/funsor) ⭐ 250 | 🐛 92 | 🌐 Python | 📅 2026-08-03 (👨‍💻 10 · 🔀 17 · 📦 32 · 📋 140 - 47% open · ⏱️ 08.04.2022):

  ```
  git clone https://github.com/pyro-ppl/funsor
  ```
* [PyPi](https://pypi.org/project/funsor) (📥 1.2K / month):
  ```
  pip install funsor
  ```

</details>
<details><summary><b><a href="https://github.com/baal-org/baal">Baal</a></b> (🥉18 ·  ⭐ 630) - 在深度网络中使用近似贝叶斯后验进行主动学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/baal-org/baal) ⭐ 935 | 🐛 20 | 🌐 Python | 📅 2025-12-03 (👨‍💻 16 · 🔀 60 · 📋 84 - 27% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/ElementAI/baal
  ```
* [PyPi](https://pypi.org/project/baal) (📥 740 / month):
  ```
  pip install baal
  ```

</details>
<details><summary><b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉18 ·  ⭐ 200) - PyStan是Stan的Python接口。<code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

* [GitHub](https://github.com/stan-dev/pystan) ⭐ 366 | 🐛 14 | 🌐 Python | 📅 2026-08-05 (👨‍💻 10 · 🔀 39 · 📋 180 - 2% open · ⏱️ 07.07.2022):

  ```
  git clone https://github.com/stan-dev/pystan
  ```
* [PyPi](https://pypi.org/project/pystan) (📥 2.8M / month):
  ```
  pip install pystan
  ```
* [Conda](https://anaconda.org/conda-forge/pystan) (📥 1.6M · ⏱️ 25.07.2022):
  ```
  conda install -c conda-forge pystan
  ```

</details>
<details><summary><b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉17 ·  ⭐ 520 · 💀) - HSMM和HMM中的贝叶斯推断。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/mattjj/pyhsmm) ⭐ 580 | 🐛 46 | 🌐 Python | 📅 2025-01-25 (👨‍💻 13 · 🔀 160 · 📦 25 · 📋 96 - 37% open · ⏱️ 24.08.2020):

  ```
  git clone https://github.com/mattjj/pyhsmm
  ```
* [PyPi](https://pypi.org/project/pyhsmm) (📥 85 / month):
  ```
  pip install pyhsmm
  ```

</details>
<details><summary><b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉14 ·  ⭐ 2.1K · 💀) - TensorFlow中的一种概率编程语言。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/thu-ml/zhusuan) ⭐ 2,219 | 🐛 13 | 🌐 Python | 📅 2022-12-17 (👨‍💻 20 · 🔀 400 · 📋 60 - 11% open · ⏱️ 05.08.2019):

  ```
  git clone https://github.com/thu-ml/zhusuan
  ```

</details>
<br>

## 对抗学习与鲁棒性

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于测试机器学习模型抵抗攻击性/恶意示例的鲁棒性的库。*

<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥇27 ·  ⭐ 2.3K) - 一个Python工具箱，用于创建欺骗神经网络的对抗示例。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/bethgelab/foolbox) ⭐ 2,972 | 🐛 29 | 🌐 Python | 📅 2025-12-03 (👨‍💻 32 · 🔀 400 · 📦 320 · 📋 350 - 5% open · ⏱️ 25.05.2022):

  ```
  git clone https://github.com/bethgelab/foolbox
  ```
* [PyPi](https://pypi.org/project/foolbox) (📥 5.4K / month):
  ```
  pip install foolbox
  ```

</details>
<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥈26 ·  ⭐ 5.6K · 💤) - 一个用于构造攻击的对抗性示例库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/cleverhans-lab/cleverhans) ⭐ 6,449 | 🐛 46 | 🌐 Jupyter Notebook | 📅 2024-04-10 (👨‍💻 130 · 🔀 1.3K · 📦 350 · 📋 450 - 5% open · ⏱️ 23.09.2021):

  ```
  git clone https://github.com/cleverhans-lab/cleverhans
  ```
* [PyPi](https://pypi.org/project/cleverhans) (📥 1.3K / month):
  ```
  pip install cleverhans
  ```

</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈26 ·  ⭐ 2.1K) - TextAttack是用于对抗攻击，数据的Python框架。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/QData/TextAttack) ⭐ 3,468 | 🐛 18 | 🌐 Python | 📅 2026-08-15 (👨‍💻 53 · 🔀 250 · 📦 93 · 📋 220 - 9% open · ⏱️ 14.08.2022):

  ```
  git clone https://github.com/QData/TextAttack
  ```
* [PyPi](https://pypi.org/project/textattack) (📥 6.6K / month):
  ```
  pip install textattack
  ```

</details>
<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥉24 ·  ⭐ 3.2K) - 对抗性鲁棒性工具箱（ART）- 用于机器学习的Python库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) ⭐ 6,194 | 🐛 19 | 🌐 Python | 📅 2025-12-12 (👨‍💻 110 · 🔀 850 · 📦 250 · 📋 710 - 12% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
  ```
* [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 5.6K / month):
  ```
  pip install adversarial-robustness-toolbox
  ```

</details>
<details><summary><b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉18 ·  ⭐ 1.1K) - 对抗性鲁棒性研究的工具箱。<code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/BorealisAI/advertorch) ⭐ 1,364 | 🐛 27 | 🌐 Jupyter Notebook | 📅 2023-09-14 (👨‍💻 21 · 🔀 170 · 📦 85 · 📋 52 - 34% open · ⏱️ 29.05.2022):

  ```
  git clone https://github.com/BorealisAI/advertorch
  ```
* [PyPi](https://pypi.org/project/advertorch) (📥 340 / month):
  ```
  pip install advertorch
  ```

</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉17 ·  ⭐ 720) - 一个用于实验，训练和评估神经网络的库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/MadryLab/robustness) ⭐ 946 | 🐛 30 | 🌐 Jupyter Notebook | 📅 2024-01-11 (👨‍💻 13 · 🔀 140 · 📦 81 · 📋 75 - 25% open · ⏱️ 14.02.2022):

  ```
  git clone https://github.com/MadryLab/robustness
  ```
* [PyPi](https://pypi.org/project/robustness) (📥 640 / month):
  ```
  pip install robustness
  ```

</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉15 ·  ⭐ 1.2K) - Advbox是一个工具箱，用于生成对抗示例。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/advboxes/AdvBox) ⭐ 1,404 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2023-02-15 (👨‍💻 19 · 🔀 240 · 📋 38 - 21% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/advboxes/AdvBox
  ```
* [PyPi](https://pypi.org/project/advbox) (📥 17 / month):
  ```
  pip install advbox
  ```

</details>
<br>

## GPU实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*需要并利用CUDA / GPU系统功能来优化数据处理和机器学习任务的库。*

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇32 ·  ⭐ 6.3K) - CUDA加速了与NumPy兼容的数组库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/cupy/cupy) ⭐ 12,268 | 🐛 706 | 🌐 Python | 📅 2026-08-20 (👨‍💻 310 · 🔀 590 · 📥 42K · 📦 1.2K · 📋 1.8K - 21% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/cupy/cupy
  ```
* [PyPi](https://pypi.org/project/cupy) (📥 20K / month):
  ```
  pip install cupy
  ```
* [Conda](https://anaconda.org/conda-forge/cupy) (📥 1.8M · ⏱️ 29.07.2022):
  ```
  conda install -c conda-forge cupy
  ```
* [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 55K · ⭐ 8 · ⏱️ 28.07.2022):
  ```
  docker pull cupy/cupy
  ```

</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥇28 ·  ⭐ 3K) - 一个简单的命令行实用程序，用于查询和监控GPU状态。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/wookayin/gpustat) ⭐ 4,392 | 🐛 30 | 🌐 Python | 📅 2026-05-30 (👨‍💻 14 · 🔀 220 · 📦 2.1K · 📋 86 - 22% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/wookayin/gpustat
  ```
* [PyPi](https://pypi.org/project/gpustat) (📥 820K / month):
  ```
  pip install gpustat
  ```
* [Conda](https://anaconda.org/conda-forge/gpustat) (📥 140K · ⏱️ 24.11.2020):
  ```
  conda install -c conda-forge gpustat
  ```

</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈25 ·  ⭐ 3.9K) - ArrayFire：通用GPU库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/arrayfire/arrayfire) ⭐ 4,902 | 🐛 318 | 🌐 C++ | 📅 2026-03-07 (👨‍💻 81 · 🔀 490 · 📥 2.7K · 📋 1.5K - 16% open · ⏱️ 09.07.2022):

  ```
  git clone https://github.com/arrayfire/arrayfire
  ```
* [PyPi](https://pypi.org/project/arrayfire) (📥 130K / month):
  ```
  pip install arrayfire
  ```

</details>
<details><summary><b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥈25 ·  ⭐ 900 · 💀) - 一个Python模块，用于从NVIDA GPU获取GPU状态。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/anderskm/gputil) ⭐ 1,214 | 🐛 31 | 🌐 Python | 📅 2026-07-18 (👨‍💻 13 · 🔀 98 · 📦 2.3K · 📋 26 - 46% open · ⏱️ 16.08.2019):

  ```
  git clone https://github.com/anderskm/gputil
  ```
* [PyPi](https://pypi.org/project/gputil) (📥 480K / month):
  ```
  pip install gputil
  ```

</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈24 ·  ⭐ 6.6K) - PyTorch扩展：易于实现混合精度和分布式的工具。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/NVIDIA/apex) ⭐ 8,992 | 🐛 772 | 🌐 Python | 📅 2026-08-17 (👨‍💻 100 · 🔀 1K · 📦 1.2K · 📋 1K - 53% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/NVIDIA/apex
  ```
* [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 100K · ⏱️ 06.04.2022):
  ```
  conda install -c conda-forge nvidia-apex
  ```

</details>
<details><summary><b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥈23 ·  ⭐ 210) - NVML库的Python3接口。在内部获取NVIDIA GPU状态。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/fbcotter/py3nvml) ⭐ 249 | 🐛 5 | 🌐 Python | 📅 2022-04-14 (👨‍💻 9 · 🔀 30 · 📦 510 · 📋 13 - 7% open · ⏱️ 14.04.2022):

  ```
  git clone https://github.com/fbcotter/py3nvml
  ```
* [PyPi](https://pypi.org/project/py3nvml) (📥 110K / month):
  ```
  pip install py3nvml
  ```
* [Conda](https://anaconda.org/conda-forge/py3nvml) (📥 31K · ⏱️ 20.06.2022):
  ```
  conda install -c conda-forge py3nvml
  ```

</details>
<details><summary><b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥈22 ·  ⭐ 1.4K) - 适用于Python的CUDA集成，有着出色的功能。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/inducer/pycuda) ⭐ 2,051 | 🐛 92 | 🌐 Python | 📅 2026-07-16 (👨‍💻 76 · 🔀 250 · 📦 1.5K · 📋 220 - 27% open · ⏱️ 16.08.2022):

  ```
  git clone https://github.com/inducer/pycuda
  ```
* [PyPi](https://pypi.org/project/pycuda) (📥 35K / month):
  ```
  pip install pycuda
  ```

</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥉20 ·  ⭐ 4.9K) - cuDF-GPU DataFrame库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/rapidsai/cudf) ⭐ 9,733 | 🐛 1,317 | 🌐 C++ | 📅 2026-08-23 (👨‍💻 250 · 🔀 630 · 📋 4.8K - 12% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/rapidsai/cudf
  ```
* [PyPi](https://pypi.org/project/cudf) (📥 1.8K / month):
  ```
  pip install cudf
  ```

</details>
<details><summary><b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥉20 ·  ⭐ 910) - GPU工具库的python接口。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/lebedov/scikit-cuda) ⭐ 989 | 🐛 63 | 🌐 Python | 📅 2023-10-15 (👨‍💻 46 · 🔀 170 · 📦 200 · 📋 220 - 22% open · ⏱️ 31.03.2022):

  ```
  git clone https://github.com/lebedov/scikit-cuda
  ```
* [PyPi](https://pypi.org/project/scikit-cuda) (📥 490 / month):
  ```
  pip install scikit-cuda
  ```

</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥉19 ·  ⭐ 2.9K) - cuML-RAPIDS机器学习库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/rapidsai/cuml) ⭐ 5,259 | 🐛 834 | 🌐 Python | 📅 2026-08-22 (👨‍💻 160 · 🔀 420 · 📋 2.1K - 32% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/rapidsai/cuml
  ```
* [PyPi](https://pypi.org/project/cuml) (📥 940 / month):
  ```
  pip install cuml
  ```

</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉18 ·  ⭐ 920) - 适用于跨供应商的通用GPU计算框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/KomputeProject/kompute) ⭐ 2,557 | 🐛 78 | 🌐 C++ | 📅 2026-08-15 (👨‍💻 19 · 🔀 64 · 📥 170 · 📦 4 · 📋 180 - 32% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/EthicalML/vulkan-kompute
  ```
* [PyPi](https://pypi.org/project/kp) (📥 87 / month):
  ```
  pip install kp
  ```

</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉17 ·  ⭐ 4K) - GPU加速的库，其中包含高度优化的构建块。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/NVIDIA/DALI) ⭐ 5,733 | 🐛 223 | 🌐 C++ | 📅 2026-08-19 (👨‍💻 77 · 🔀 500 · 📋 1.2K - 15% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/NVIDIA/DALI
  ```

</details>
<details><summary><b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉17 ·  ⭐ 86 · 💀) - NVIDIA Management Library的Python3接口。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/nicolargo/nvidia-ml-py3) ⚠️ Archived (👨‍💻 2 · 🔀 18 · 📦 6.2K · ⏱️ 06.03.2019):

  ```
  git clone https://github.com/nicolargo/nvidia-ml-py3
  ```
* [PyPi](https://pypi.org/project/nvidia-ml-py3) (📥 970K / month):
  ```
  pip install nvidia-ml-py3
  ```

</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥉16 ·  ⭐ 1.1K) - cuGraph-RAPIDS图形分析库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/rapidsai/cugraph) ⭐ 2,224 | 🐛 136 | 🌐 Cuda | 📅 2026-08-21 (👨‍💻 90 · 🔀 210 · 📋 990 - 20% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/rapidsai/cugraph
  ```
* [PyPi](https://pypi.org/project/cugraph) (📥 100 / month):
  ```
  pip install cugraph
  ```

</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉15 ·  ⭐ 1.8K · 💤) - BlazingSQL是一种用于GPU的轻量级，GPU加速的引擎。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/BlazingDB/blazingsql) ⭐ 2,011 | 🐛 146 | 🌐 C++ | 📅 2022-09-16 (👨‍💻 49 · 🔀 170 · 📋 710 - 17% open · ⏱️ 30.09.2021):

  ```
  git clone https://github.com/BlazingDB/blazingsql
  ```
* [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 950 · ⏱️ 11.11.2019):
  ```
  conda install -c blazingsql blazingsql-protocol
  ```

</details>
<details><summary><b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉14 ·  ⭐ 660 · 💀) - 用于更快的Pytorch中CPU-GPU传输的工具库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Santosh-Gupta/SpeedTorch) ⭐ 682 | 🐛 5 | 🌐 Python | 📅 2020-02-21 (👨‍💻 3 · 🔀 39 · 📦 4 · 📋 6 - 66% open · ⏱️ 21.02.2020):

  ```
  git clone https://github.com/Santosh-Gupta/SpeedTorch
  ```
* [PyPi](https://pypi.org/project/SpeedTorch) (📥 22 / month):
  ```
  pip install SpeedTorch
  ```

</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉14 ·  ⭐ 610) - GPU加速信号处理。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/rapidsai/cusignal) ⚠️ Archived (👨‍💻 39 · 🔀 96 · 📋 140 - 11% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/rapidsai/cusignal
  ```

</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉11 ·  ⭐ 150 · 💤) - jupyter/ipython实验容器。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/stas00/ipyexperiments) ⭐ 236 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-12-15 (👨‍💻 3 · 🔀 11 · 📦 6 · ⏱️ 07.12.2021):

  ```
  git clone https://github.com/stas00/ipyexperiments
  ```
* [PyPi](https://pypi.org/project/ipyexperiments) (📥 100 / month):
  ```
  pip install ipyexperiments
  ```

</details>
<br>

## Tensorflow实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*TensorFlow的拓展工具库。*

<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇33 ·  ⭐ 1.6K) - 由TensorFlow 2.x维护的有用额外功能。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/addons) ⚠️ Archived (👨‍💻 200 · 🔀 530 · 📦 7.2K · 📋 920 - 21% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/tensorflow/addons
  ```
* [PyPi](https://pypi.org/project/tensorflow-addons) (📥 2.2M / month):
  ```
  pip install tensorflow-addons
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥇31 ·  ⭐ 13K) - 设计深度学习模型和数据集的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/tensor2tensor) ⚠️ Archived (👨‍💻 240 · 🔀 3K · 📦 1.2K · 📋 1.2K - 45% open · ⏱️ 09.08.2022):

  ```
  git clone https://github.com/tensorflow/tensor2tensor
  ```
* [PyPi](https://pypi.org/project/tensor2tensor) (📥 8.9K / month):
  ```
  pip install tensor2tensor
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥇31 ·  ⭐ 3.2K) - 通过重用部分库来进行迁移学习的库。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/hub) ⭐ 3,523 | 🐛 6 | 🌐 Python | 📅 2025-01-17 (👨‍💻 94 · 🔀 1.6K · 📦 13K · 📋 650 - 2% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/tensorflow/hub
  ```
* [PyPi](https://pypi.org/project/tensorflow-hub) (📥 3.3M / month):
  ```
  pip install tensorflow-hub
  ```
* [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 67K · ⏱️ 18.04.2021):
  ```
  conda install -c conda-forge tensorflow-hub
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈30 ·  ⭐ 930 · 📈) - 输入管道框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/transform) ⭐ 988 | 🐛 43 | 🌐 Python | 📅 2026-08-14 (👨‍💻 27 · 🔀 190 · 📦 1K · 📋 190 - 17% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/tensorflow/transform
  ```
* [PyPi](https://pypi.org/project/tensorflow-transform) (📥 3.3M / month):
  ```
  pip install tensorflow-transform
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈29 ·  ⭐ 1.3K) - 用于优化ML模型以进行部署的工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/model-optimization) ⭐ 1,578 | 🐛 250 | 🌐 Python | 📅 2026-08-22 (👨‍💻 71 · 🔀 280 · 📦 2K · 📋 300 - 48% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/tensorflow/model-optimization
  ```
* [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 140K / month):
  ```
  pip install tensorflow-model-optimization
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉26 ·  ⭐ 930) - 用结构化信号训练神经模型。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/neural-structured-learning) ⭐ 1,010 | 🐛 1 | 🌐 Python | 📅 2026-07-21 (👨‍💻 34 · 🔀 170 · 📦 260 · 📋 65 - 3% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/tensorflow/neural-structured-learning
  ```
* [PyPi](https://pypi.org/project/neural-structured-learning) (📥 16K / month):
  ```
  pip install neural-structured-learning
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉25 ·  ⭐ 570) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/io) ⭐ 739 | 🐛 306 | 🌐 C++ | 📅 2026-06-25 (👨‍💻 94 · 🔀 210 · 📋 530 - 36% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/tensorflow/io
  ```
* [PyPi](https://pypi.org/project/tensorflow-io) (📥 440K / month):
  ```
  pip install tensorflow-io
  ```

</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉24 ·  ⭐ 2K · 💀) - EfficientNet模型的实现。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/qubvel/efficientnet) ⭐ 2,100 | 🐛 65 | 🌐 Python | 📅 2024-01-24 (👨‍💻 10 · 🔀 450 · 📥 240K · 📦 1.1K · 📋 110 - 48% open · ⏱️ 16.07.2021):

  ```
  git clone https://github.com/qubvel/efficientnet
  ```
* [PyPi](https://pypi.org/project/efficientnet) (📥 53K / month):
  ```
  pip install efficientnet
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉23 ·  ⭐ 330) - TensorFlow Cloud存储库提供的API。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/cloud) ⭐ 381 | 🐛 80 | 🌐 Python | 📅 2026-08-21 (👨‍💻 27 · 🔀 71 · 📦 170 · 📋 82 - 68% open · ⏱️ 24.03.2022):

  ```
  git clone https://github.com/tensorflow/cloud
  ```
* [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 150K / month):
  ```
  pip install tensorflow-cloud
  ```

</details>
<details><summary><b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉20 ·  ⭐ 1K · 💀) - 具有预先训练的权重的高级网络定义。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/taehoonlee/tensornets) ⭐ 996 | 🐛 17 | 🌐 Python | 📅 2021-01-02 (👨‍💻 6 · 🔀 180 · 📦 52 · 📋 58 - 27% open · ⏱️ 02.01.2021):

  ```
  git clone https://github.com/taehoonlee/tensornets
  ```
* [PyPi](https://pypi.org/project/tensornets) (📥 150 / month):
  ```
  pip install tensornets
  ```

</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉19 ·  ⭐ 640) - TensorFlow中的数据压缩。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tensorflow/compression) ⭐ 923 | 🐛 10 | 🌐 Python | 📅 2026-04-17 (👨‍💻 16 · 🔀 210 · 📋 87 - 2% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/tensorflow/compression
  ```
* [PyPi](https://pypi.org/project/tensorflow-compression) (📥 1K / month):
  ```
  pip install tensorflow-compression
  ```

</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉17 ·  ⭐ 810) - 与框架无关的实现，可实现最新的显着性。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PAIR-code/saliency) ⭐ 997 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2024-03-20 (👨‍💻 15 · 🔀 170 · 📦 41 · ⏱️ 13.05.2022):

  ```
  git clone https://github.com/PAIR-code/saliency
  ```
* [PyPi](https://pypi.org/project/saliency) (📥 1.3K / month):
  ```
  pip install saliency
  ```

</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉17 ·  ⭐ 780 · 💤) - 任意阶乘分解机的TensorFlow实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/geffy/tffm) ⭐ 777 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2022-01-17 (👨‍💻 10 · 🔀 180 · 📦 11 · 📋 40 - 45% open · ⏱️ 17.01.2022):

  ```
  git clone https://github.com/geffy/tffm
  ```
* [PyPi](https://pypi.org/project/tffm) (📥 1.5K / month):
  ```
  pip install tffm
  ```

</details>
<br>

## Sklearn实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*scikit-learn的拓展工具库。*

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇32 ·  ⭐ 6K) - 一个解决不平衡类别数据建模的Python程序包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) ⭐ 7,120 | 🐛 82 | 🌐 Python | 📅 2026-06-29 (👨‍💻 63 · 🔀 1.1K · 📦 12K · 📋 510 - 8% open · ⏱️ 16.05.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/imbalanced-learn
  ```
* [PyPi](https://pypi.org/project/imbalanced-learn) (📥 3.2M / month):
  ```
  pip install imbalanced-learn
  ```
* [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 250K · ⏱️ 16.05.2022):
  ```
  conda install -c conda-forge imbalanced-learn
  ```

</details>
<details><summary><b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇30 ·  ⭐ 4.1K) - 用于Python数据的扩展和帮助程序模块库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rasbt/mlxtend) ⭐ 5,165 | 🐛 138 | 🌐 Python | 📅 2026-08-05 (👨‍💻 90 · 🔀 760 · 📦 6.6K · 📋 420 - 25% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/rasbt/mlxtend
  ```
* [PyPi](https://pypi.org/project/mlxtend) (📥 1.4M / month):
  ```
  pip install mlxtend
  ```
* [Conda](https://anaconda.org/conda-forge/mlxtend) (📥 220K · ⏱️ 27.05.2022):
  ```
  conda install -c conda-forge mlxtend
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥇30 ·  ⭐ 2K) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/category_encoders) ⭐ 2,497 | 🐛 37 | 🌐 Python | 📅 2026-07-31 (👨‍💻 52 · 🔀 360 · 📦 3.8K · 📋 250 - 25% open · ⏱️ 02.06.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/category_encoders
  ```
* [PyPi](https://pypi.org/project/category_encoders) (📥 950K / month):
  ```
  pip install category_encoders
  ```
* [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 180K · ⏱️ 02.06.2022):
  ```
  conda install -c conda-forge category_encoders
  ```

</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈25 ·  ⭐ 1.1K · 💤) - 多元插补和矩阵补全算法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/iskandr/fancyimpute) ⭐ 1,281 | 🐛 3 | 🌐 Python | 📅 2023-10-25 (👨‍💻 12 · 🔀 160 · 📦 1.2K · 📋 110 - 1% open · ⏱️ 21.10.2021):

  ```
  git clone https://github.com/iskandr/fancyimpute
  ```
* [PyPi](https://pypi.org/project/fancyimpute) (📥 16K / month):
  ```
  pip install fancyimpute
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈24 ·  ⭐ 770) - 基于scikit-learn的多标签等模块。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-multilearn/scikit-multilearn) ⭐ 956 | 🐛 92 | 🌐 Python | 📅 2024-02-01 (👨‍💻 17 · 🔀 140 · 📦 820 · 📋 180 - 46% open · ⏱️ 09.07.2022):

  ```
  git clone https://github.com/scikit-multilearn/scikit-multilearn
  ```
* [PyPi](https://pypi.org/project/scikit-multilearn) (📥 87K / month):
  ```
  pip install scikit-multilearn
  ```

</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈23 ·  ⭐ 3.5K) - 遗传算法，粒子群优化等实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/guofei9987/scikit-opt) ⭐ 6,707 | 🐛 72 | 🌐 Python | 📅 2026-03-25 (👨‍💻 16 · 🔀 800 · 📦 83 · 📋 150 - 30% open · ⏱️ 15.07.2022):

  ```
  git clone https://github.com/guofei9987/scikit-opt
  ```
* [PyPi](https://pypi.org/project/scikit-opt) (📥 1.6K / month):
  ```
  pip install scikit-opt
  ```

</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈22 ·  ⭐ 880) - scikit学习管道的额外块。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/koaning/scikit-lego) ⭐ 1,407 | 🐛 33 | 🌐 Python | 📅 2026-08-09 (👨‍💻 52 · 🔀 90 · 📦 59 · 📋 240 - 9% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/koaning/scikit-lego
  ```
* [PyPi](https://pypi.org/project/scikit-lego) (📥 23K / month):
  ```
  pip install scikit-lego
  ```
* [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 23K · ⏱️ 06.06.2022):
  ```
  conda install -c conda-forge scikit-lego
  ```

</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥈22 ·  ⭐ 710) - scikit-learn交叉验证器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/trent-b/iterative-stratification) ⭐ 898 | 🐛 2 | 🌐 Python | 📅 2024-10-12 (👨‍💻 7 · 🔀 64 · 📦 220 · 📋 20 - 5% open · ⏱️ 06.06.2022):

  ```
  git clone https://github.com/trent-b/iterative-stratification
  ```
* [PyPi](https://pypi.org/project/iterative-stratification) (📥 35K / month):
  ```
  pip install iterative-stratification
  ```

</details>
<details><summary><b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥈22 ·  ⭐ 410 · 💀) - 用于CRFsuite的scikit-learn启发式API。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/TeamHG-Memex/sklearn-crfsuite) ⭐ 440 | 🐛 41 | 🌐 Python | 📅 2026-04-08 (👨‍💻 6 · 🔀 190 · 📦 4K · 📋 56 - 58% open · ⏱️ 05.12.2019):

  ```
  git clone https://github.com/TeamHG-Memex/sklearn-crfsuite
  ```
* [PyPi](https://pypi.org/project/sklearn-crfsuite) (📥 200K / month):
  ```
  pip install sklearn-crfsuite
  ```

</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥉20 ·  ⭐ 590) - （AAAI'20）用于机器学习模型的Python工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

* [GitHub](https://github.com/yzhao062/combo) ⭐ 661 | 🐛 16 | 🌐 Python | 📅 2023-01-14 (👨‍💻 2 · 🔀 100 · 📦 480 · 📋 13 - 76% open · ⏱️ 07.07.2022):

  ```
  git clone https://github.com/yzhao062/combo
  ```
* [PyPi](https://pypi.org/project/combo) (📥 35K / month):
  ```
  pip install combo
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉20 ·  ⭐ 480 · 💀) - 使用Python中的逻辑规则进行机器学习。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/skope-rules) ⭐ 664 | 🐛 36 | 🌐 Jupyter Notebook | 📅 2024-01-31 (👨‍💻 18 · 🔀 79 · 📦 130 · 📋 31 - 80% open · ⏱️ 23.10.2020):

  ```
  git clone https://github.com/scikit-learn-contrib/skope-rules
  ```
* [PyPi](https://pypi.org/project/skope-rules) (📥 96K / month):
  ```
  pip install skope-rules
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥉19 ·  ⭐ 1.6K · 💤) - 大规模线性分类，回归分析等。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/lightning) ⚠️ Archived (👨‍💻 17 · 🔀 180 · 📥 230 · 📦 100 · 📋 88 - 52% open · ⏱️ 30.01.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/lightning
  ```
* [PyPi](https://pypi.org/project/sklearn-contrib-lightning) (📥 1.7K / month):
  ```
  pip install sklearn-contrib-lightning
  ```
* [Conda](https://anaconda.org/conda-forge/sklearn-contrib-lightning) (📥 170K · ⏱️ 13.11.2021):
  ```
  conda install -c conda-forge sklearn-contrib-lightning
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉17 ·  ⭐ 420) - 一个用于动态分类器和集成选择的Python库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/DESlib) ⭐ 508 | 🐛 16 | 🌐 Python | 📅 2026-01-20 (👨‍💻 14 · 🔀 63 · 📦 29 · 📋 150 - 10% open · ⏱️ 07.06.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/DESlib
  ```
* [PyPi](https://pypi.org/project/deslib) (📥 340 / month):
  ```
  pip install deslib
  ```

</details>
<details><summary><b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉17 ·  ⭐ 160) - L1型问题的快速求解器：Lasso，稀疏Logisitic回归等<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/mathurinm/celer) ⭐ 244 | 🐛 22 | 🌐 Python | 📅 2025-06-10 (👨‍💻 11 · 🔀 25 · 📦 13 · 📋 90 - 20% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/mathurinm/celer
  ```
* [PyPi](https://pypi.org/project/celer) (📥 620 / month):
  ```
  pip install celer
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉16 ·  ⭐ 360) - Python的拓扑数据分析。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-tda/scikit-tda) ⭐ 578 | 🐛 4 | 🌐 Python | 📅 2026-08-03 (👨‍💻 4 · 🔀 44 · 📦 33 · 📋 19 - 78% open · ⏱️ 13.03.2022):

  ```
  git clone https://github.com/scikit-tda/scikit-tda
  ```
* [PyPi](https://pypi.org/project/scikit-tda) (📥 1.6K / month):
  ```
  pip install scikit-tda
  ```

</details>
<details><summary><b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉16 ·  ⭐ 210) - 通用图形模型的Scikit学习兼容估计。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/skggm/skggm) ⭐ 253 | 🐛 35 | 🌐 Python | 📅 2026-06-23 (👨‍💻 6 · 🔀 36 · 📦 8 · 📋 75 - 37% open · ⏱️ 11.03.2022):

  ```
  git clone https://github.com/skggm/skggm
  ```
* [PyPi](https://pypi.org/project/skggm) (📥 61 / month):
  ```
  pip install skggm
  ```

</details>
<details><summary><b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉13 ·  ⭐ 120 · 💀) - 数据分析基准库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/amueller/dabl) ⭐ 134 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-10-23 (👨‍💻 21 · 🔀 10 · ⏱️ 09.07.2021):

  ```
  git clone https://github.com/amueller/dabl
  ```
* [PyPi](https://pypi.org/project/dabl) (📥 2.1K / month):
  ```
  pip install dabl
  ```

</details>
<br>

## Pytorch实用程序

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*Pytorch的拓展工具库。*

<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇28 ·  ⭐ 4.7K) - 在应用程序中使用深度度量学习的最简单方法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) ⭐ 6,339 | 🐛 77 | 🌐 Python | 📅 2025-08-17 (👨‍💻 27 · 🔀 560 · 📦 320 · 📋 380 - 13% open · ⏱️ 13.08.2022):

  ```
  git clone https://github.com/KevinMusgrave/pytorch-metric-learning
  ```
* [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 90K / month):
  ```
  pip install pytorch-metric-learning
  ```
* [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 8K · ⏱️ 03.08.2022):
  ```
  conda install -c metric-learning pytorch-metric-learning
  ```

</details>
<details><summary><b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇27 ·  ⭐ 8.6K · 💀) - pytorch预训练的ConvNets：NASNet，ResNeXt等<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Cadene/pretrained-models.pytorch) ⭐ 9,098 | 🐛 109 | 🌐 Python | 📅 2022-04-22 (👨‍💻 22 · 🔀 1.8K · 📦 1.8K · 📋 180 - 46% open · ⏱️ 16.04.2020):

  ```
  git clone https://github.com/Cadene/pretrained-models.pytorch
  ```
* [PyPi](https://pypi.org/project/pretrainedmodels) (📥 170K / month):
  ```
  pip install pretrainedmodels
  ```

</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥇26 ·  ⭐ 2.5K · 💤) - torch-optimizer - pytorch的优化器集合。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/jettify/pytorch-optimizer) ⭐ 3,171 | 🐛 57 | 🌐 Python | 📅 2024-03-22 (👨‍💻 25 · 🔀 240 · 📦 670 · 📋 50 - 42% open · ⏱️ 11.11.2021):

  ```
  git clone https://github.com/jettify/pytorch-optimizer
  ```
* [PyPi](https://pypi.org/project/torch_optimizer) (📥 48K / month):
  ```
  pip install torch_optimizer
  ```

</details>
<details><summary><b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈25 ·  ⭐ 3.6K · 💀) - PyTorch中的模型摘要类似于`model.summary（）`。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/sksq96/pytorch-summary) ⭐ 4,053 | 🐛 141 | 🌐 Python | 📅 2024-03-02 (👨‍💻 11 · 🔀 400 · 📦 5.7K · 📋 140 - 69% open · ⏱️ 10.05.2021):

  ```
  git clone https://github.com/sksq96/pytorch-summary
  ```
* [PyPi](https://pypi.org/project/torchsummary) (📥 100K / month):
  ```
  pip install torchsummary
  ```

</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈24 ·  ⭐ 4.2K) - 具有完整GPU支持的可微分ODE求解器。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rtqichen/torchdiffeq) ⭐ 6,476 | 🐛 95 | 🌐 Python | 📅 2025-04-04 (👨‍💻 21 · 🔀 720 · 📦 300 · 📋 180 - 21% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/rtqichen/torchdiffeq
  ```
* [PyPi](https://pypi.org/project/torchdiffeq) (📥 25K / month):
  ```
  pip install torchdiffeq
  ```

</details>
<details><summary><b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈22 ·  ⭐ 2.1K · 💀) - 与CNN一样快地训练RNN（https://arxiv.org/abs/1709.02755）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/asappresearch/sru) ⭐ 2,106 | 🐛 69 | 🌐 Python | 📅 2022-01-04 (👨‍💻 21 · 🔀 300 · 📦 18 · 📋 130 - 46% open · ⏱️ 19.05.2021):

  ```
  git clone https://github.com/asappresearch/sru
  ```
* [PyPi](https://pypi.org/project/sru) (📥 2.7K / month):
  ```
  pip install sru
  ```

</details>
<details><summary><b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈21 ·  ⭐ 7.1K · 💀) - EfficientNet等模型的PyTorch实现<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lukemelas/EfficientNet-PyTorch) ⭐ 8,221 | 🐛 167 | 🌐 Python | 📅 2022-04-08 (👨‍💻 24 · 🔀 1.4K · 📥 1.9M · 📋 280 - 50% open · ⏱️ 15.04.2021):

  ```
  git clone https://github.com/lukemelas/EfficientNet-PyTorch
  ```
* [PyPi](https://pypi.org/project/efficientnet-pytorch) (📥 100K / month):
  ```
  pip install efficientnet-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈21 ·  ⭐ 1.8K) - Efficient Neural Architecture Search的Pytorch实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/dreamquark-ai/tabnet) ⭐ 2,956 | 🐛 68 | 🌐 Python | 📅 2024-10-23 (👨‍💻 19 · 🔀 370 · 📋 230 - 7% open · ⏱️ 27.06.2022):

  ```
  git clone https://github.com/dreamquark-ai/tabnet
  ```
* [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 20K / month):
  ```
  pip install pytorch-tabnet
  ```

</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥈21 ·  ⭐ 1.5K · 💀) - 预训练的EfficientNet，EfficientNet-Lite，MixNet等<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) ⭐ 1,577 | 🐛 4 | 🌐 Python | 📅 2024-06-13 (👨‍💻 5 · 🔀 200 · 📦 120 · 📋 54 - 5% open · ⏱️ 08.07.2021):

  ```
  git clone https://github.com/rwightman/gen-efficientnet-pytorch
  ```
* [PyPi](https://pypi.org/project/geffnet) (📥 15K / month):
  ```
  pip install geffnet
  ```

</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈21 ·  ⭐ 1.3K) - PyTorch扩展用于快速研发原型和Kaggle实验。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) ⭐ 1,574 | 🐛 6 | 🌐 Python | 📅 2025-10-09 (👨‍💻 7 · 🔀 100 · 📋 24 - 8% open · ⏱️ 20.08.2022):

  ```
  git clone https://github.com/BloodAxe/pytorch-toolbelt
  ```
* [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 15K / month):
  ```
  pip install pytorch_toolbelt
  ```

</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥈21 ·  ⭐ 710) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rusty1s/pytorch_sparse) ⭐ 1,104 | 🐛 20 | 🌐 Python | 📅 2026-06-03 (👨‍💻 32 · 🔀 100 · 📋 200 - 13% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/rusty1s/pytorch_sparse
  ```
* [PyPi](https://pypi.org/project/torch-sparse) (📥 27K / month):
  ```
  pip install torch-sparse
  ```

</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥉20 ·  ⭐ 1.8K) - Reformer，Pytorch中高效的transformer实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lucidrains/reformer-pytorch) ⭐ 2,191 | 🐛 17 | 🌐 Python | 📅 2023-06-21 (👨‍💻 11 · 🔀 240 · 📋 120 - 11% open · ⏱️ 24.06.2022):

  ```
  git clone https://github.com/lucidrains/reformer-pytorch
  ```
* [PyPi](https://pypi.org/project/reformer-pytorch) (📥 1.9K / month):
  ```
  pip install reformer-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥉20 ·  ⭐ 1.7K · 💤) - 少量学习的扩展程序和数据加载器的集合。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/tristandeleu/pytorch-meta) ⭐ 2,060 | 🐛 61 | 🌐 Python | 📅 2023-07-17 (👨‍💻 12 · 🔀 220 · 📦 97 · 📋 130 - 32% open · ⏱️ 20.09.2021):

  ```
  git clone https://github.com/tristandeleu/pytorch-meta
  ```
* [PyPi](https://pypi.org/project/torchmeta) (📥 1.4K / month):
  ```
  pip install torchmeta
  ```

</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥉20 ·  ⭐ 1.1K) - 优化图聚类的PyTorch扩展库<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rusty1s/pytorch_scatter) ⭐ 1,745 | 🐛 11 | 🌐 Python | 📅 2026-06-03 (👨‍💻 22 · 🔀 120 · 📋 270 - 6% open · ⏱️ 18.08.2022):

  ```
  git clone https://github.com/rusty1s/pytorch_scatter
  ```
* [PyPi](https://pypi.org/project/torch-scatter) (📥 30K / month):
  ```
  pip install torch-scatter
  ```

</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉20 ·  ⭐ 860) - Performer的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lucidrains/performer-pytorch) ⭐ 1,181 | 🐛 44 | 🌐 Python | 📅 2022-02-02 (👨‍💻 6 · 🔀 120 · 📦 49 · 📋 78 - 44% open · ⏱️ 02.02.2022):

  ```
  git clone https://github.com/lucidrains/performer-pytorch
  ```
* [PyPi](https://pypi.org/project/performer-pytorch) (📥 75K / month):
  ```
  pip install performer-pytorch
  ```

</details>
<details><summary><b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥉20 ·  ⭐ 530) - PyTorch的简化框架和实用程序。<code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/GRAAL-Research/poutyne) ⭐ 578 | 🐛 9 | 🌐 Python | 📅 2026-06-07 (👨‍💻 18 · 🔀 62 · 📦 91 · 📋 53 - 15% open · ⏱️ 16.07.2022):

  ```
  git clone https://github.com/GRAAL-Research/poutyne
  ```
* [PyPi](https://pypi.org/project/poutyne) (📥 5.3K / month):
  ```
  pip install poutyne
  ```

</details>
<details><summary><b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉19 ·  ⭐ 2.9K · 💀) - 训练速度与Adam一样快且与SGD一样好的优化器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/Luolc/AdaBound) ⭐ 2,902 | 🐛 19 | 🌐 Python | 📅 2023-07-23 (👨‍💻 2 · 🔀 320 · 📦 140 · 📋 25 - 72% open · ⏱️ 06.03.2019):

  ```
  git clone https://github.com/Luolc/AdaBound
  ```
* [PyPi](https://pypi.org/project/adabound) (📥 1.4K / month):
  ```
  pip install adabound
  ```

</details>
<details><summary><b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉19 ·  ⭐ 1.6K · 💤) - pip安装antialiased-cnns以提高稳定性等。<code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/adobe/antialiased-cnns) ⭐ 1,683 | 🐛 16 | 🌐 Python | 📅 2024-04-08 (👨‍💻 6 · 🔀 200 · 📦 29 · 📋 44 - 29% open · ⏱️ 29.09.2021):

  ```
  git clone https://github.com/adobe/antialiased-cnns
  ```
* [PyPi](https://pypi.org/project/antialiased-cnns) (📥 1.5K / month):
  ```
  pip install antialiased-cnns
  ```

</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥉19 ·  ⭐ 1.4K · 💤) - Higher是一个pytorch库，允许用户在跨训练循环而不是单个训练步骤的损失上获得更高阶的梯度。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/facebookresearch/higher) ⚠️ Archived (👨‍💻 9 · 🔀 100 · 📦 160 · 📋 100 - 50% open · ⏱️ 26.10.2021):

  ```
  git clone https://github.com/facebookresearch/higher
  ```
* [PyPi](https://pypi.org/project/higher) (📥 110K / month):
  ```
  pip install higher
  ```

</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉17 ·  ⭐ 6.5K) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/geohot/tinygrad) ⭐ 33,491 | 🐛 178 | 🌐 Python | 📅 2026-08-23 (👨‍💻 62 · 🔀 650 · 📦 3 · 📋 110 - 14% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/geohot/tinygrad
  ```

</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉17 ·  ⭐ 650) - 该库的目标是为numpy/pytorch矩阵代数表达式生成更有用的异常消息。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/parrt/tensor-sensor) ⭐ 805 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2022-04-07 (👨‍💻 4 · 🔀 34 · 📦 7 · 📋 23 - 34% open · ⏱️ 07.04.2022):

  ```
  git clone https://github.com/parrt/tensor-sensor
  ```
* [PyPi](https://pypi.org/project/tensor-sensor) (📥 1.8K / month):
  ```
  pip install tensor-sensor
  ```

</details>
<details><summary><b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉16 ·  ⭐ 2.4K · 💀) - 一个微型的标量值autograd引擎和一个神经网络库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/karpathy/micrograd) ⭐ 17,241 | 🐛 79 | 🌐 Jupyter Notebook | 📅 2026-08-03 (👨‍💻 2 · 🔀 210 · 📦 7 · 📋 5 - 40% open · ⏱️ 18.04.2020):

  ```
  git clone https://github.com/karpathy/micrograd
  ```
* [PyPi](https://pypi.org/project/micrograd) (📥 360 / month):
  ```
  pip install micrograd
  ```

</details>
<details><summary><b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉16 ·  ⭐ 1.5K · 💀) - LambdaNetworks的实现。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/lucidrains/lambda-networks) ⭐ 1,528 | 🐛 13 | 🌐 Python | 📅 2020-11-18 (👨‍💻 3 · 🔀 160 · 📦 6 · 📋 28 - 46% open · ⏱️ 18.11.2020):

  ```
  git clone https://github.com/lucidrains/lambda-networks
  ```
* [PyPi](https://pypi.org/project/lambda-networks) (📥 45 / month):
  ```
  pip install lambda-networks
  ```

</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉16 ·  ⭐ 1.1K) - Tez是用于PyTorch的超级简单且轻巧的Trainer。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/abhishekkrthakur/tez) ⭐ 1,155 | 🐛 25 | 🌐 Python | 📅 2023-01-29 (👨‍💻 2 · 🔀 140 · 📦 33 · 📋 37 - 54% open · ⏱️ 10.08.2022):

  ```
  git clone https://github.com/abhishekkrthakur/tez
  ```
* [PyPi](https://pypi.org/project/tez) (📥 1.8K / month):
  ```
  pip install tez
  ```

</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉16 ·  ⭐ 1K · 💀) - 具有GPU支持且高效的可微分SDE求解器。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/google-research/torchsde) ⚠️ Archived (👨‍💻 5 · 🔀 110 · 📦 19 · 📋 50 - 18% open · ⏱️ 26.07.2021):

  ```
  git clone https://github.com/google-research/torchsde
  ```

</details>
<details><summary><b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉14 ·  ⭐ 370 · 💤) - 更高层次的pytorch神经网络训练库。<code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/achaiah/pywick) ⭐ 399 | 🐛 1 | 🌐 Python | 📅 2022-02-04 (👨‍💻 4 · 🔀 39 · 📦 7 · 📋 14 - 7% open · ⏱️ 22.10.2021):

  ```
  git clone https://github.com/achaiah/pywick
  ```
* [PyPi](https://pypi.org/project/pywick) (📥 36 / month):
  ```
  pip install pywick
  ```

</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉13 ·  ⭐ 1K · 💤) - 快速，通用和经过测试的微分结构化预测。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/harvardnlp/pytorch-struct) ⭐ 1,133 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2022-04-20 (👨‍💻 16 · 🔀 83 · 📋 54 - 44% open · ⏱️ 30.01.2022):

  ```
  git clone https://github.com/harvardnlp/pytorch-struct
  ```

</details>
<br>

## 数据库客户端

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

*用于连接，操作和查询数据库的库。*

🔗 <b><a href="https://github.com/HanXinzi2020/awesome-python-resources#数据库">Python DB Clients</a></b> ( ⭐ 7 · 💤)  - Collection of database clients for python.

<br>

## 中文自然语言处理

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/fxsjy/jieba">jieba</a></b> (🥇32 ·  ⭐ 29K · 💀) - Chinese Words Segementation Utilities. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/fxsjy/jieba) ⭐ 35,125 | 🐛 700 | 🌐 Python | 📅 2024-08-21 (👨‍💻 48 · 🔀 6.3K · 📦 14K · 📋 810 - 73% open · ⏱️ 15.02.2020):

  ```
  git clone https://github.com/fxsjy/jieba
  ```
* [PyPi](https://pypi.org/project/jieba) (📥 440K / month):
  ```
  pip install jieba
  ```
* [Conda](https://anaconda.org/conda-forge/jieba) (📥 120K · ⏱️ 30.05.2021):
  ```
  conda install -c conda-forge jieba
  ```

</details>
<details><summary><b><a href="https://github.com/isnowfy/snownlp">snownlp</a></b> (🥉22 ·  ⭐ 5.9K · 💀) - Python library for processing Chinese text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/isnowfy/snownlp) ⭐ 6,633 | 🐛 44 | 🌐 Python | 📅 2020-01-19 (👨‍💻 8 · 🔀 1.3K · 📦 930 · 📋 100 - 38% open · ⏱️ 19.01.2020):

  ```
  git clone https://github.com/isnowfy/snownlp
  ```
* [PyPi](https://pypi.org/project/snownlp) (📥 3.6K / month):
  ```
  pip install snownlp
  ```

</details>
<br>

## Others

<a href="#目录"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇38 ·  ⭐ 10K) - 用于数学，科学和工程的开源软件生态系统。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/scipy/scipy) ⭐ 14,948 | 🐛 1,846 | 🌐 Python | 📅 2026-08-23 (👨‍💻 1.3K · 🔀 4.3K · 📥 350K · 📦 560K · 📋 8.4K - 16% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/scipy/scipy
  ```
* [PyPi](https://pypi.org/project/scipy) (📥 43M / month):
  ```
  pip install scipy
  ```
* [Conda](https://anaconda.org/conda-forge/scipy) (📥 26M · ⏱️ 30.07.2022):
  ```
  conda install -c conda-forge scipy
  ```

</details>
<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇35 ·  ⭐ 9.5K) - 用纯Python编写的计算机代数系统。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/sympy/sympy) ⭐ 14,886 | 🐛 5,963 | 🌐 Python | 📅 2026-08-22 (👨‍💻 1.2K · 🔀 3.6K · 📥 460K · 📦 45K · 📋 12K - 32% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/sympy/sympy
  ```
* [PyPi](https://pypi.org/project/sympy) (📥 2.6M / month):
  ```
  pip install sympy
  ```
* [Conda](https://anaconda.org/conda-forge/sympy) (📥 2.3M · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge sympy
  ```

</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇31 ·  ⭐ 6.1K) - （JMLR'19）用于可扩展离群值检测的Python工具箱。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/yzhao062/pyod) ⭐ 9,976 | 🐛 232 | 🌐 Python | 📅 2026-08-19 (👨‍💻 41 · 🔀 1.1K · 📦 1.5K · 📋 260 - 47% open · ⏱️ 29.07.2022):

  ```
  git clone https://github.com/yzhao062/pyod
  ```
* [PyPi](https://pypi.org/project/pyod) (📥 370K / month):
  ```
  pip install pyod
  ```

</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥇30 ·  ⭐ 20K · 📈) - Streamlit用Python构建数据应用程序的最快方法。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/streamlit/streamlit) ⭐ 45,599 | 🐛 1,191 | 🌐 Python | 📅 2026-08-23 (👨‍💻 150 · 🔀 1.8K · 📦 380 · 📋 2.6K - 23% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/streamlit/streamlit
  ```
* [PyPi](https://pypi.org/project/streamlit) (📥 810K / month):
  ```
  pip install streamlit
  ```

</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥇30 ·  ⭐ 8.5K) - 对任何模型做UI封装并与他人共享。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/gradio-app/gradio) ⭐ 43,409 | 🐛 170 | 🌐 Python | 📅 2026-08-23 (👨‍💻 92 · 🔀 530 · 📦 1.1K · 📋 1K - 18% open · ⏱️ 25.08.2022):

  ```
  git clone https://github.com/gradio-app/gradio
  ```
* [PyPi](https://pypi.org/project/gradio) (📥 150K / month):
  ```
  pip install gradio
  ```

</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥈29 ·  ⭐ 5.9K) - 高效地计算导数的numpy代码。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/HIPS/autograd) ⭐ 7,522 | 🐛 181 | 🌐 Python | 📅 2026-08-17 (👨‍💻 52 · 🔀 800 · 📦 3.8K · 📋 370 - 39% open · ⏱️ 15.06.2022):

  ```
  git clone https://github.com/HIPS/autograd
  ```
* [PyPi](https://pypi.org/project/autograd) (📥 1.2M / month):
  ```
  pip install autograd
  ```
* [Conda](https://anaconda.org/conda-forge/autograd) (📥 230K · ⏱️ 29.06.2022):
  ```
  conda install -c conda-forge autograd
  ```

</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥈28 ·  ⭐ 6.4K) - 用于探索和发布数据的开源多功能工具。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/simonw/datasette) ⭐ 11,405 | 🐛 708 | 🌐 Python | 📅 2026-08-14 (👨‍💻 67 · 🔀 410 · 📥 39 · 📦 730 · 📋 1.4K - 27% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/simonw/datasette
  ```
* [PyPi](https://pypi.org/project/datasette) (📥 240K / month):
  ```
  pip install datasette
  ```

</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥈28 ·  ⭐ 3.8K) - 在药物发现，量子化学，材料科学和生物学方面普及深度学习。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/deepchem/deepchem) ⭐ 6,954 | 🐛 1,165 | 🌐 Python | 📅 2026-08-20 (👨‍💻 200 · 🔀 1.3K · 📦 120 · 📋 1.4K - 29% open · ⏱️ 26.08.2022):

  ```
  git clone https://github.com/deepchem/deepchem
  ```
* [PyPi](https://pypi.org/project/deepchem) (📥 8.9K / month):
  ```
  pip install deepchem
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈28 ·  ⭐ 2.2K) - HDBSCAN群集的高性能实现。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/hdbscan) ⭐ 3,136 | 🐛 385 | 🌐 Jupyter Notebook | 📅 2026-06-12 (👨‍💻 80 · 🔀 390 · 📦 1.5K · 📋 440 - 63% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/hdbscan
  ```
* [PyPi](https://pypi.org/project/hdbscan) (📥 450K / month):
  ```
  pip install hdbscan
  ```
* [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 1.2M · ⏱️ 11.02.2022):
  ```
  conda install -c conda-forge hdbscan
  ```

</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈28 ·  ⭐ 1.1K · 💀) - 为人而不是为机器优化的Python数据分析库。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/wireservice/agate) ⭐ 1,198 | 🐛 10 | 🌐 Python | 📅 2026-07-23 (👨‍💻 49 · 🔀 140 · 📦 1.1K · 📋 640 - 1% open · ⏱️ 15.07.2021):

  ```
  git clone https://github.com/wireservice/agate
  ```
* [PyPi](https://pypi.org/project/agate) (📥 1.6M / month):
  ```
  pip install agate
  ```
* [Conda](https://anaconda.org/conda-forge/agate) (📥 91K · ⏱️ 16.07.2021):
  ```
  conda install -c conda-forge agate
  ```

</details>
<details><summary><b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈28 ·  ⭐ 190) - 快速矩阵乘法库。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/explosion/cython-blis) ⭐ 238 | 🐛 8 | 🌐 C | 📅 2026-05-14 (👨‍💻 12 · 🔀 34 · 📦 20K · 📋 28 - 17% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/explosion/cython-blis
  ```
* [PyPi](https://pypi.org/project/blis) (📥 3.8M / month):
  ```
  pip install blis
  ```
* [Conda](https://anaconda.org/conda-forge/cython-blis) (📥 1.6M · ⏱️ 05.08.2022):
  ```
  conda install -c conda-forge cython-blis
  ```

</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥈27 ·  ⭐ 8.3K) - 基于PaddlePaddle的出色的预训练模型工具包。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/PaddlePaddle/PaddleHub) ⭐ 80 | 🐛 12 | 🌐 Python | 📅 2025-06-26 (👨‍💻 62 · 🔀 1.7K · 📥 580 · 📦 890 · 📋 1.1K - 41% open · ⏱️ 19.08.2022):

  ```
  git clone https://github.com/PaddlePaddle/PaddleHub
  ```
* [PyPi](https://pypi.org/project/paddlehub) (📥 14K / month):
  ```
  pip install paddlehub
  ```

</details>
<details><summary><b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈27 ·  ⭐ 8.2K · 💤) - 用于自动驾驶研究的开源模拟器。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/carla-simulator/carla) ⭐ 14,316 | 🐛 1,193 | 🌐 C++ | 📅 2026-08-21 (👨‍💻 140 · 🔀 2.4K · 📦 230 · 📋 4K - 16% open · ⏱️ 19.11.2021):

  ```
  git clone https://github.com/carla-simulator/carla
  ```
* [PyPi](https://pypi.org/project/carla) (📥 26K / month):
  ```
  pip install carla
  ```

</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈27 ·  ⭐ 1.8K) - 用于数字内核的时间编译器。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/serge-sans-paille/pythran) ⭐ 2,141 | 🐛 159 | 🌐 C++ | 📅 2026-08-22 (👨‍💻 66 · 🔀 170 · 📦 220 · 📋 760 - 14% open · ⏱️ 19.07.2022):

  ```
  git clone https://github.com/serge-sans-paille/pythran
  ```
* [PyPi](https://pypi.org/project/pythran) (📥 370K / month):
  ```
  pip install pythran
  ```
* [Conda](https://anaconda.org/conda-forge/pythran) (📥 260K · ⏱️ 31.07.2022):
  ```
  conda install -c conda-forge pythran
  ```

</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈27 ·  ⭐ 960) - 用于数据清理的API。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/pyjanitor-devs/pyjanitor) ⭐ 1,499 | 🐛 143 | 🌐 Python | 📅 2026-08-22 (👨‍💻 100 · 🔀 150 · 📦 220 · 📋 490 - 20% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/ericmjl/pyjanitor
  ```
* [PyPi](https://pypi.org/project/pyjanitor) (📥 29K / month):
  ```
  pip install pyjanitor
  ```
* [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 130K · ⏱️ 22.11.2021):
  ```
  conda install -c conda-forge pyjanitor
  ```

</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥉26 ·  ⭐ 1.3K) - Python中的度量学习算法。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/scikit-learn-contrib/metric-learn) ⭐ 1,438 | 🐛 51 | 🌐 Python | 📅 2026-03-19 (👨‍💻 22 · 🔀 220 · 📦 230 · 📋 160 - 26% open · ⏱️ 21.06.2022):

  ```
  git clone https://github.com/scikit-learn-contrib/metric-learn
  ```
* [PyPi](https://pypi.org/project/metric-learn) (📥 44K / month):
  ```
  pip install metric-learn
  ```

</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥉25 ·  ⭐ 7.1K) - 借助清晰的代码和速度来进行深度学习。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/google/trax) ⚠️ Archived (👨‍💻 78 · 🔀 720 · 📦 75 · 📋 210 - 41% open · ⏱️ 08.08.2022):

  ```
  git clone https://github.com/google/trax
  ```
* [PyPi](https://pypi.org/project/trax) (📥 4K / month):
  ```
  pip install trax
  ```

</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥉25 ·  ⭐ 1.3K) - 快速执行Python代码，并在Tableau可视化文件中显示结果。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/tableau/TabPy) ⭐ 1,654 | 🐛 22 | 🌐 Python | 📅 2026-08-21 (👨‍💻 47 · 🔀 480 · 📦 93 · 📋 290 - 1% open · ⏱️ 10.06.2022):

  ```
  git clone https://github.com/tableau/TabPy
  ```
* [PyPi](https://pypi.org/project/tabpy) (📥 19K / month):
  ```
  pip install tabpy
  ```

</details>
<details><summary><b><a href="https://github.com/uber/causalml">causalml</a></b> (🥉24 ·  ⭐ 3.2K) - 利用机器学习提升建模和因果推理。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/uber/causalml) ⭐ 5,968 | 🐛 9 | 🌐 Python | 📅 2026-08-20 (👨‍💻 44 · 🔀 520 · 📦 52 · 📋 280 - 21% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/uber/causalml
  ```
* [PyPi](https://pypi.org/project/causalml) (📥 48K / month):
  ```
  pip install causalml
  ```

</details>
<details><summary><b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥉24 ·  ⭐ 990 · 💀) - pyclustring是Python，C++数据挖掘库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/annoviko/pyclustering) ⭐ 1,215 | 🐛 80 | 🌐 Python | 📅 2024-02-25 (👨‍💻 26 · 🔀 220 · 📥 410 · 📦 350 · 📋 650 - 9% open · ⏱️ 12.02.2021):

  ```
  git clone https://github.com/annoviko/pyclustering
  ```
* [PyPi](https://pypi.org/project/pyclustering) (📥 50K / month):
  ```
  pip install pyclustering
  ```
* [Conda](https://anaconda.org/conda-forge/pyclustering) (📥 41K · ⏱️ 13.09.2021):
  ```
  conda install -c conda-forge pyclustering
  ```

</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉23 ·  ⭐ 960) - 用于Python中粒子群优化的研究工具包。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/ljvmiranda921/pyswarms) ⭐ 1,393 | 🐛 42 | 🌐 Python | 📅 2024-08-06 (👨‍💻 44 · 🔀 300 · 📦 180 · 📋 210 - 3% open · ⏱️ 03.07.2022):

  ```
  git clone https://github.com/ljvmiranda921/pyswarms
  ```
* [PyPi](https://pypi.org/project/pyswarms) (📥 18K / month):
  ```
  pip install pyswarms
  ```

</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥉22 ·  ⭐ 1.2K) - 使用scikit-learn启发式API进行Python遗传编程。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/trevorstephens/gplearn) ⭐ 1,878 | 🐛 17 | 🌐 Python | 📅 2026-08-14 (👨‍💻 10 · 🔀 200 · 📦 280 · 📋 190 - 7% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/trevorstephens/gplearn
  ```
* [PyPi](https://pypi.org/project/gplearn) (📥 5.3K / month):
  ```
  pip install gplearn
  ```

</details>
<details><summary><b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥉22 ·  ⭐ 910) - 适用于Python的OpenCL集成。<code>❗Unlicensed</code></summary>

* [GitHub](https://github.com/inducer/pyopencl) ⭐ 1,148 | 🐛 82 | 🌐 Python | 📅 2026-08-23 (👨‍💻 92 · 🔀 220 · 📦 800 · 📋 300 - 20% open · ⏱️ 23.08.2022):

  ```
  git clone https://github.com/inducer/pyopencl
  ```
* [PyPi](https://pypi.org/project/pyopencl) (📥 34K / month):
  ```
  pip install pyopencl
  ```
* [Conda](https://anaconda.org/conda-forge/pyopencl) (📥 670K · ⏱️ 22.06.2022):
  ```
  conda install -c conda-forge pyopencl
  ```

</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉22 ·  ⭐ 850 · 💤) - Python因子分析库（PCA，CA，MCA，MFA，FAMD）。<code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/MaxHalford/prince) ⭐ 1,480 | 🐛 10 | 🌐 Python | 📅 2026-07-21 (👨‍💻 12 · 🔀 150 · 📦 240 · 📋 110 - 35% open · ⏱️ 28.12.2021):

  ```
  git clone https://github.com/MaxHalford/prince
  ```
* [PyPi](https://pypi.org/project/prince) (📥 45K / month):
  ```
  pip install prince
  ```

</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉22 ·  ⭐ 440) - 查找pyspark并导入的工具库。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/minrk/findspark) ⭐ 525 | 🐛 13 | 🌐 Python | 📅 2026-03-01 (👨‍💻 15 · 🔀 68 · 📦 2.7K · 📋 22 - 50% open · ⏱️ 11.02.2022):

  ```
  git clone https://github.com/minrk/findspark
  ```
* [PyPi](https://pypi.org/project/findspark) (📥 2.1M / month):
  ```
  pip install findspark
  ```
* [Conda](https://anaconda.org/conda-forge/findspark) (📥 690K · ⏱️ 11.02.2022):
  ```
  conda install -c conda-forge findspark
  ```

</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥉20 ·  ⭐ 3.6K) - Python中的在线机器学习。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/online-ml/river) ⭐ 5,922 | 🐛 70 | 🌐 Python | 📅 2026-08-21 (👨‍💻 81 · 🔀 380 · 📦 160 · 📋 370 - 1% open · ⏱️ 24.08.2022):

  ```
  git clone https://github.com/online-ml/river
  ```

</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉20 ·  ⭐ 500) - 在pandas DataFrames中处理分子结构。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/rasbt/biopandas) ⭐ 756 | 🐛 28 | 🌐 Python | 📅 2026-05-22 (👨‍💻 10 · 🔀 100 · 📦 120 · 📋 47 - 42% open · ⏱️ 06.08.2022):

  ```
  git clone https://github.com/rasbt/biopandas
  ```
* [PyPi](https://pypi.org/project/biopandas) (📥 5.3K / month):
  ```
  pip install biopandas
  ```
* [Conda](https://anaconda.org/conda-forge/biopandas) (📥 120K · ⏱️ 13.05.2022):
  ```
  conda install -c conda-forge biopandas
  ```

</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉19 ·  ⭐ 2.7K) - StreamAlert是无服务器的实时数据分析框架。<code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

* [GitHub](https://github.com/airbnb/streamalert) ⭐ 2,889 | 🐛 90 | 🌐 Python | 📅 2023-10-23 (👨‍💻 33 · 🔀 320 · 📋 340 - 24% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/airbnb/streamalert
  ```

</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉19 ·  ⭐ 330) - （MLSys' 21）大型无人驾驶加速系统。<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

* [GitHub](https://github.com/yzhao062/SUOD) ⭐ 393 | 🐛 12 | 🌐 Python | 📅 2025-03-24 (👨‍💻 2 · 🔀 41 · 📦 430 · 📋 9 - 66% open · ⏱️ 07.07.2022):

  ```
  git clone https://github.com/yzhao062/SUOD
  ```
* [PyPi](https://pypi.org/project/suod) (📥 29K / month):
  ```
  pip install suod
  ```

</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉19 ·  ⭐ 320 · 💤) - 数据插补库可对缺少数据的数据集进行预处理。<code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

* [GitHub](https://github.com/eltonlaw/impyute) ⭐ 361 | 🐛 30 | 🌐 Python | 📅 2021-11-06 (👨‍💻 11 · 🔀 46 · 📦 140 · 📋 64 - 42% open · ⏱️ 06.11.2021):

  ```
  git clone https://github.com/eltonlaw/impyute
  ```
* [PyPi](https://pypi.org/project/impyute) (📥 8.2K / month):
  ```
  pip install impyute
  ```

</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉17 ·  ⭐ 840) - 天文学和天体物理学的机器学习，统计和数据挖掘.<code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

* [GitHub](https://github.com/astroML/astroML) ⭐ 1,199 | 🐛 71 | 🌐 Python | 📅 2024-05-25 (👨‍💻 30 · 🔀 270 · 📋 150 - 37% open · ⏱️ 17.08.2022):

  ```
  git clone https://github.com/astroML/astroML
  ```
* [PyPi](https://pypi.org/project/astroML) (📥 1.3K / month):
  ```
  pip install astroML
  ```
* [Conda](https://anaconda.org/conda-forge/astroml) (📥 31K · ⏱️ 02.03.2022):
  ```
  conda install -c conda-forge astroml
  ```

</details>
<details><summary><b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉16 ·  ⭐ 22) - 具有sklearn类功能的功能工程包。<code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

* [GitHub](https://github.com/solegalli/feature_engine) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2024-09-04 (👨‍💻 36 · 🔀 8 · ⏱️ 05.07.2022):

  ```
  git clone https://github.com/solegalli/feature_engine
  ```
* [PyPi](https://pypi.org/project/feature_engine) (📥 93K / month):
  ```
  pip install feature_engine
  ```
* [Conda](https://anaconda.org/conda-forge/feature_engine) (📥 14K · ⏱️ 14.06.2022):
  ```
  conda install -c conda-forge feature_engine
  ```

</details>
<details><summary><b><a href="https://github.com/cgnorthcutt/cleanlab">cleanlab</a></b> (🥉13 ·  ⭐ 49 · 🐣) - 机器学习的标准软件包。<code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

* [GitHub](https://github.com/cgnorthcutt/cleanlab) ⭐ 57 | 🐛 0 | 📅 2023-02-01 (👨‍💻 10 · 🔀 9 · ⏱️ 21.08.2022):

  ```
  git clone https://github.com/cgnorthcutt/cleanlab
  ```
* [PyPi](https://pypi.org/project/cleanlab) (📥 7.2K / month):
  ```
  pip install cleanlab
  ```

</details>

***

## 相关资源

* [**Python资源汇集列表**](https://github.com/HanXinzi-AI/awesome-python-resources) ⭐ 181 | 🐛 112 | 📅 2024-06-06: 周更新的各种应用方向与主题的资源汇集列表
* \[\*\*p

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
