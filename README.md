<h1 align="center" >Cognitive Emotion</h1>

<h2 align="" >About the Project</h2>
The project uses the EEG Brainwave Dataset from Kaggle to create 
machine learning models that allow the user to predict the emotion of a person 
given his EEG Brainwave Data.The dataset was downloaded from Kaggle. 
Here is the  <a href="https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions" >link</a> to the dataset.

<h2 align="" >Setup</h2>

To run the notebook one can either prefer using Google Colab the better method or run the notebook locally. To run using Colab just use the link at the end of the ReadMe file.

For running the notebook locally, follow the steps [Windows]:

1. Clone the repository using `git clone https://github.com/Namratha2301/CognitiveEmotion.git`
2. Set directory to cloned repo `cd CognitiveEmotion`
3. Create a python virtual environment for the project using `python -m venv env`
4. Activate the environment using `env\Scripts\activate`
5. Install the dependencies using `pip install -r requirements.txt`
6. Open the Jupyter Notebook IDE using `jupyter notebook`
7. The Jupyter Notebook IDE should open up allowing you to run the file

<h2 align="" >Machine Learning Models and Scores</h2>
<table align="center" >
<thead>
<th>S.No</th>
<th>Model</th>
<th>Package</th>
<th>Score</th>
</thead>

<tr>
<td>
1
</td>
<td>
Random Forest Classifier
</td>
<td>
SciKit-Learn
</td>
<td>
98.7%
</td>
</tr>

<tr>
<td>
2
</td>
<td>
Logistic Regression Classifier
</td>
<td>
SciKit-Learn
</td>
<td>
93.2%
</td>
</tr>

<tr>
<td>
3
</td>
<td>
Logistic Regression Classifier With 2 PC
</td>
<td>
SciKit-Learn
</td>
<td>
77.5%
</td>
</tr>

<tr>
<td>
4
</td>
<td>
Logistic Regression Classifier with 10 PC
</td>
<td>
SciKit-Learn
</td>
<td>
86.6%
</td>
</tr>

<tr>
<td>
5
</td>
<td>
Linear Support Vector Machine Classifier (SVM)
</td>
<td>
SciKit-Learn
</td>
<td>
96.57%
</td>
</tr>

<tr>
<td>
6
</td>
<td>
Extreme Gradient Boosting Classifier
</td>
<td>
XGBoost
</td>
<td>
99.39%
</td>
</tr>

<tr>
<td>
7
</td>
<td>
GRU
</td>
<td>
TensorFlow
</td>
<td>
95.46%
</td>
</tr>
</table>


<h2>Link to Colab File</h2>
<a href="https://colab.research.google.com/drive/1kN7CFoHXXKD8FWbcWiLgs3R7y30u4Dma?usp=sharing">CognitiveEmotionColab</a>
