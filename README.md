# Report generation for chest Xray

## Data Source :
[Data Source](https://csciitd-my.sharepoint.com/:u:/g/personal/anz197518_iitd_ac_in/Eb9zDGmQzPZJhXcGzB_XZuYBv-Ra9DKj3kK6RkBoCKM0Ag?e=3o7WqG)


## DataSet Structure

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)




#### Here is a general code flow for generating a report for chest X-ray using machine learning:
### 1. Collect Data: 
Collect chest X-ray images along with their associated diagnostic reports. This dataset should be annotated with relevant labels, such as the presence of pneumonia or other lung diseases.Data Collection of Frontal and Lateral DataFrame.

### 2. Data Pre-processing (Image Augmentation): 
Pre-process the data by cleaning, resizing, and normalizing the images. Additionally, text pre-processing should be done to clean and preprocess the diagnostic reports.

### 3. Defining Model Architecture: 
By Concatening fronatal and lateral view of and use Efficient Net and Embedding Net them and Use LSTM to obtain result and report from the Xray images.

### 4. Train a Machine Learning Model Using Tensorflow FrameWork: 
Train a machine learning model on the pre-processed data using algorithms like LSTM and Efficient Net (type of Neural Network).

### 5. Beam Search: 
Step 1: Set Beam Width & Decode. ‍ Passing a sentence into the Encoder to translate.

Step 2: Pass Tokens and Predict. ‍ Lets set our beam width to 3 and grab the top three predicted words at each position in a given sequence.

Step 3: Beam Search Final Output. ‍

### 6.Extracting Image Having Higher Bleu Score: 
Use the trained model to predict the classification of new chest X-ray images and generate an initial report.


### 7.Defining Conclusion: 
#### Best Predictions :

Have clear images with right amount of brightness and lateral views.

Words also occur in several times and model could be able to predict.

#### Worst Predictions :

Has Duplication of frontal and lateral views in data.
Words occurs in rare.

Has too less brightness or more brightness


### 8.Report Generation: 
Generating the final report, including any relevant images or graphs, and deliver it to the medical professional or patient.
## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-kumar-7534111ab/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/rahulkr54678274/)

