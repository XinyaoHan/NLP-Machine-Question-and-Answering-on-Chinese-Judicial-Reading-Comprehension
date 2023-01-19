# NLP-Machine-Question-and-Answering-on-Chinese-Judicial-Reading-Comprehension

This is a project conducted by Liancheng Gong & Xinyao Han & Qiaowei Li for NYU course CSCI-SHU 376.  
We performed Span-Extraction Machine Reading Comprehension (MRC) in the field of Chinese legal judgment documents. We use a Chinese Bert based binary classification model and a question answering model are applied on Chinese judicial Reading Comprehension (CJRC) data set.

### Demo
<img width="608" alt="1674088931(1)" src="https://user-images.githubusercontent.com/49512811/213328947-ffaf10cb-d468-4e5a-a499-e1d3da498ba5.png">



### The Dataset
<img width="550" alt="1674088661(1)" src="https://user-images.githubusercontent.com/49512811/213328426-0dfa68b4-1fa8-4688-8eff-ba1ec2f7c8d1.png">  
<img width="548" alt="1674088690(1)" src="https://user-images.githubusercontent.com/49512811/213328507-8e38afd5-b986-44b1-9561-8c31964b8af3.png">  

### Modeling
#### Classification Model  
Embedding  
<img width="445" alt="1674088738(1)" src="https://user-images.githubusercontent.com/49512811/213328606-2f23368b-f6db-4f76-bf4d-498a8b0940e9.png">  
Bert Classifier  
<img width="548" alt="1674088772(1)" src="https://user-images.githubusercontent.com/49512811/213328679-e66b2c41-e2b5-4567-8cb3-c58c9763e586.png">  

#### Question & Answering Model  
Embedding  
<img width="455" alt="1674088847(1)" src="https://user-images.githubusercontent.com/49512811/213328798-5ceea8ba-3d93-49df-b9bf-3131bb2550a1.png">  
BertForQuestionAnswering  
<img width="547" alt="1674088867(1)" src="https://user-images.githubusercontent.com/49512811/213328846-b44642d3-d986-410e-a59b-11ccaacb8716.png">  

### Results  
<img width="551" alt="1674088798(1)" src="https://user-images.githubusercontent.com/49512811/213328724-c586b073-f4fe-4e12-9c29-13e0d9823da6.png">  
<img width="548" alt="1674088903(1)" src="https://user-images.githubusercontent.com/49512811/213328898-70d9a5fa-21f9-4373-ad1d-131fdfac2519.png">
