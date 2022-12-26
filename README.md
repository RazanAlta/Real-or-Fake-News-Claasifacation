# Real-or-Fake-News-Claasifacation
## Fake dataset 
<img width="581" alt="image" src="https://user-images.githubusercontent.com/65066845/209502796-7e3f5335-1a91-44e2-ab63-8086b405fa87.png">
## Real Dataset 

<img width="584" alt="image" src="https://user-images.githubusercontent.com/65066845/209502712-0b4fd09e-2d5a-4017-86f8-b1361a7b03be.png">
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
