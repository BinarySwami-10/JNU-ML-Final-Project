### Problem Statement : Covid-19 tweet sentiment Analysis

#### Best model is 0.best_model.ipynb first file in github repo. Notebook, [please see here](https://colab.research.google.com/drive/1Gq3_w9l2kPWKP_CQJjnnHB1mr7XiW9-M?usp=sharing) to evaluate in colab

#### Summary File :0z_bestmodel_summary.ipynb, probably second file in repo.

# How to use
- open in colab and run instance 
- download and extract this model ,only works for roberta [MODEL LINK outputs.zip](https://nikhil-colab-bucket.s3-us-west-2.amazonaws.com/outputs.zip) in ./outputs folder as it is.
- run as usual and comment out any ! commands using aws (amazon web services)
- do not train the model in! we are using trained weights. to avoid training comment out section 'START TRAINING'

![IMAGE](https://www.codemotion.com/magazine/wp-content/uploads/2020/05/bert-google-896x504.png)
# Summary
### Highlights
- Our model is perhaps the most versatile and sophisticated in our batch.
- Highest model Accuracy is 90% and may go up, original model was trained for 2hrs or 10 epochs. 
- Use of AWS services [S3] in Program to fully automate ML Pipeline and Save/load Of checkpoints, security increased by clearing output whenever we enter sensitive password or access keys.
- We can dray conclusions faster by parallely running models on cloud, and saving checkpoints in AWS instead of colab which refreshes and loses data.


# *Individual Model Summary* 
outputs and details each model tested has been put below in form of brief summary. 
All Model Links in the API available for use Can Be found Here : [PETRAINED MODELS](https://huggingface.co/transformers/pretrained_models.html)

## Model:  RoBERTa-base [A Robustly Optimized BERT Pretraining Approach]

  -Accuracy
  
    91%

  -Notebook
  
   https://github.com/BinarySwami-10/JNU-ML-Final-Project/blob/main/Mod_Roberta_Acc_85_Param_120M.ipynb

  -Details
  
    12-layer, 768-hidden, 12-heads, 125M parameters RoBERTa using the BERT-base architecture

## Model: DistilRoBERTa [Remove Insignificant Parameters from RoBERTa]

  -Accuracy
  
    82.91205897840969 %
  
  -Notebook
  
   https://github.com/BinarySwami-10/JNU-ML-Final-Project/blob/main/Mod_distilroberta_Acc_82_Param_80M.ipynb
    
  -Details
       	
    6-layer, 768-hidden, 12-heads, 82M parameters, The DistilRoBERTa model distilled from the RoBERTa model roberta-base checkpoint.


## Model: XLNet-base [Generalized Autoregressive Pretraining for Language Understanding]

  -Accuracy
  
    79%

  -Notebook
  
   https://github.com/BinarySwami-10/JNU-ML-Final-Project/blob/main/Mod_XLnet_Acc_79_Param_110M.ipynb
    
  -Details
    
    12-layer, 768-hidden, 12-heads, 110M parameters. XLNet English model

## Model: XLNet-Large [Generalized Autoregressive Pretraining for Language Understanding]

  -Accuracy
    
    75.92550265792721 %
  
  -Notebook
    
   https://github.com/BinarySwami-10/JNU-ML-Final-Project/blob/main/Mod_XLnet_large_Acc_75.ipynb
  
  -Details
    
    24-layer, 1024-hidden, 16-heads, 340M parameters. XLNet Large English model

