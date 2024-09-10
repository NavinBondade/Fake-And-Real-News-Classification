# Distinguishing The Fake And Real News With EDA <br> Development Dataset Accuracy: 99 % | Extrinsic Dataset Accuracy: 85%
<p align="center">
<a href="https://nbviewer.jupyter.org/github/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Notebook/Fake_and_Real_News_notebook.ipynb" target="_blank">
  <img align="center"  src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/button_if-github-fails-to-load-the-notebook-click-here%20(4).png?raw=true"/>
</a>
</p> 
<img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/089D/production/_111750220_gettyimages-1215064495.jpg" alt="Fake_And_Real_News_Classification" width="1000" height="510">
<p>Fake news has become one of the most pervasive challenges in today's digital landscape, contributing to the spread of misinformation that can cause widespread harm. The dissemination of false and misleading information has, on numerous occasions, resulted in violent protests, public unrest, and significant damage to the reputation of individuals, organizations, and even entire communities. To address this growing issue, I have developed a state-of-the-art deep learning system that is designed to accurately and efficiently detect fake news.

This system, built using advanced neural network architectures, is capable of identifying fake news with an impressive accuracy of 99%, delivering results within just a few seconds. By analyzing the language, tone, and structure of the text, the model distinguishes between genuine and deceptive information with exceptional precision. This automated solution not only provides a rapid response to potential misinformation but also aids in mitigating its harmful impact by enabling organizations and individuals to respond swiftly and appropriately, ensuring a more informed and responsible flow of information.</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Wordcloud</li>
</ul>
<h2>Word Cloud Representation</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Word%20Cloud%20Representation.jpg" alt="wordcloud" >
</p>  
<h2>Target Class Distribution</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Real%20and%20Fake%20News%20Class%20Distribution.png" >
<p align="center">
<img src="https://github.com/NavinBondade/Distinguishing-Fake-And-Real-News-With-Deep-Learning/blob/main/Graphs/Real%20and%20Fake%20News%20Class%20Distribution%20In%20Percentage.png">
</p> 
<h2>Model Details</h2>
<p>For the conversion of text data to numeric, I have used Keras word to sequence function. The deep learning model at its core uses single one-dimensional convolution neural network layers followed by Max pooling and dropout layer,  it also uses three dense layers for decision making. All the layers use RELU as an activation function except the last dense layer that uses the sigmoid activation function.</p>
<br>
<p align="center">
  <img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/model.png" height="700">
</p>
<h2>Model Traning</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Model%20Training.jpg" alt="loss_accuracy">
<p>The model was trained for 2 epochs. During training, the model uses Adam as an optimizer and uses binary cross-entropy as the loss function to penalize the model more when it makes false predictions.</p>
<h2>Model Evaluation on Development Dataset</h2>
<ul>
  <li><b>Training Data Accuracy: 99%</b></li>
  <li><b>Test Data Accuracy: 99%</b></li>
  <li><b>Training Data Loss: 0.0201</b></li> 
  <li><b>Test Data Loss: 0.006</b></li> 
</ul>
<h3>Confusion Matrix</h3>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Confusion%20Matrix%20Development%20Data.png">
<h3>Classification Report on Development Dataset</h3>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Classification%20Report%20development%20data.png">   
<h2>Testing Model on Extrinsic Dataset</h2>
<p>After gaining amazing test and train accuracy by the model, I have further tested it on an extrinsic dataset which model never saw. The main objective behind this was to test whether the model has got overfitted to the data, whether the model has learned the noise and how well it performs on data it never saw before. To achieve this objective I tested the model on a dataset that contains only fake news and not real ones.</p>
<h2>Model Evaluation on Extrinsic Dataset</h2>
<ul>
  <li><b>Accuracy: 85%</b></li>
  <li><b>Loss: 0.49</b></li> 
</ul>
<h2>Confusion Matrix</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Confusion%20Matrix%20For%20Fake%20News%20Dataset.png">
<h2>Classification Report</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Classification%20Report%20For%20Fake%20News%20Dataset.png">   
<h2>Conclusion</h2>
<p>In this project, I have created a one dimension convolution-based deep learning model that distinguishes fake and real news with an accuracy of 99 percent on the development dataset and 85 percent on the extrince dataset.</p>







