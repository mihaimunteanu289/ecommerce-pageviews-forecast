<h1>E-commerce Offer Pageviews Forecast</h1>

<p>This repository contains the source code for predicting daily pageviews for offers in an e-commerce environment.</p>

<h2>Project Overview</h2>

<p>The goal of this project is to forecast the number of daily pageviews for each offer on an e-commerce site using historical data. The project follows a series of analytical and predictive modeling steps.</p>

<h2>Repository Structure</h2>

<p>Here is a brief explanation of what each part of this repository covers:</p>

<ol>
<li><code>data</code>: Contains the dataset used for training and evaluation.</li>
<li><code>1. eda.ipynb</code>: This notebook includes the exploratory data analysis of the e-commerce offers dataset.</li>
<li><code>2. data_preprocessing.ipynb</code>: In this notebook, the raw data is cleaned and preprocessed for modeling.</li>
<li><code>3. feature_engineering.ipynb</code>: This notebook covers the creation and selection of features that will be used in the prediction model.</li>
<li><code>4.1. model_selection_ensembles.ipynb</code>: This notebook explores various predictive ensemble models to forecast pageviews.</li>
<li><code>4.2. model_selection_linears.ipynb</code>: This notebook explores various predictive linear models to forecast pageviews.</li>
<li><code>5. model_tuning.ipynb</code>: This notebook is dedicated to the tuning of the chosen model(s) to improve forecast accuracy.</li>
<li><code>6. ltr_listwise_poc.ipynb</code>: This notebook focuses on a proof of concept for listwise learning to rank (LTR) using LightGBM.</li>
<li><code>tpot_model_selection</code>: A directory containing optimization scripts or results for model selection.</li>
<li><code>hypertuning</code>: A directory dedicated to the hyperparameter tuning process of the predictive models.</li>
<li><code>requirements.txt</code>: A file listing all the dependencies necessary to run the project.</li>
<li><code>README.md</code>: The file that provides an overview of the project and the repository.</li>
</ol>

<h2>Getting Started</h2>

<p>To get started with the project:</p>

<ol>
<li>Clone the repository using Git: <code>git clone https://github.com/mihaimunteanu289/ecommerce-pageviews-forecast.git</code>.</li>
<li>Install the necessary dependencies by running <code>pip install -r requirements.txt</code>. This project requires Python 3.10 and other specific libraries.</li>
<li>Run the notebooks in the specified order to reproduce the analysis and predictions.</li>
</ol>

<h2>Author</h2>

<ul>
<li><strong>Mihai Munteanu</strong> - <a href="https://github.com/mihaimunteanu289">mihaimunteanu289</a></li>
</ul>
