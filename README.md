# Real-or-Fake-News-Claasifacation
## Fake dataset 

<img width="420" alt="image" src="https://user-images.githubusercontent.com/65066845/209506233-e0584278-f9d6-49ae-8771-db5854fc31ea.png">

## Real Dataset 

<img width="422" alt="image" src="https://user-images.githubusercontent.com/65066845/209506087-7774730b-cfb0-4805-9c91-75c764b2e418.png">

## Data visuataion:

### Fake news based on subject:
<img width="482" alt="image" src="https://user-images.githubusercontent.com/65066845/209462166-4c08bd08-ecce-4dc0-9c97-692308ed62a4.png">

### Word cloud for fake news:
<img width="539" alt="image" src="https://user-images.githubusercontent.com/65066845/209462182-b7c50569-8147-4584-99a5-6bb4548cf18c.png">

### Real news accurancy based on subject 
<img width="497" alt="image" src="https://user-images.githubusercontent.com/65066845/209462218-0ad240ae-b577-4169-952b-cd9969637596.png">

### Word cloud for real news:
<img width="539" alt="image" src="https://user-images.githubusercontent.com/65066845/209462234-94fd6a7d-e510-4b07-be9e-a787b00302cb.png">

## Creating Deep Learning Model:

<img width="825" alt="image" src="https://user-images.githubusercontent.com/65066845/209462817-666a0d60-1146-42d9-a68d-8120e8de14ab.png">

## Pre-Processing: 


### 1- Splitting the text data to a publisher, unknow publisher, and text 

### 1.a- Creating a list of index that don't have the publiction part 

<img width="794" alt="image" src="https://user-images.githubusercontent.com/65066845/209468683-23fa21d8-87f3-4d5d-945e-f8df3a3dcaa1.png">
### 1.b- create an array with all the publishers names 

<img width="455" alt="image" src="https://user-images.githubusercontent.com/65066845/209468838-d1764250-f15a-45b7-b42b-8e78f76b3a4f.png">
### 2- Converting all text to lower case:

<img width="451" alt="image" src="https://user-images.githubusercontent.com/65066845/209468333-3a2f101c-512e-4214-85f0-653dcf80e0e1.png">

### Append real and fake news together 
<img width="503" alt="image" src="https://user-images.githubusercontent.com/65066845/209469795-4148e31f-4289-444c-b837-2040d6f354a6.png">

### Vectorization -- word2vec
<img width="434" alt="image" src="https://user-images.githubusercontent.com/65066845/209469883-a8946609-aedb-478b-a7f5-52744cbe4c49.png">

### Training word2vec model using gensim library 

<img width="626" alt="image" src="https://user-images.githubusercontent.com/65066845/209471126-454d1ab1-293a-4ef3-9282-36dd97b55b29.png">

* sg: The training algorithm, either CBOW(0) or skip gram(1). The default training algorithm is CBOW. 

### Model Evalutation 
<img width="439" alt="image" src="https://user-images.githubusercontent.com/65066845/209507444-c5786613-1126-423f-8a34-abce58929cf6.png">

### Testing 
<img width="401" alt="image" src="https://user-images.githubusercontent.com/65066845/209507529-15a6f8bc-c902-48c5-8690-c9b7b7e3f425.png">

## Tools used:
* Pandas and Numpy for data manipulation
* Plotly for data visualizations
* Tensorflow/Keras for Recurrent Neural Networks
* Scikit-learn library for splitting the data into train-test samples, for data scaling (MinMaxScaler), and for additional model evaluation (mean_squared_error)
* <img width="953" alt="image" src="https://user-images.githubusercontent.com/65066845/209663589-231e6f1b-c7ff-4d95-be1f-7cc5fbe9ccfc.png">
<img width="734" alt="image" src="https://user-images.githubusercontent.com/65066845/209664377-23339678-70c0-4646-ad50-e9fe526efad8.png">


