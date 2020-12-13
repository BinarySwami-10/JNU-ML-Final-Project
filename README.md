
# Summary
### Highlights
- Our model is perhaps the most versatile and sophisticated 
- Highest model Accuracy is 85% and may go up, original model was trained for 2hrs or 10 epochs. 
- Use of AWS services [S3] in Program to fully automate ML Pipeline and Save/load Of checkpoints, security increased by clearing output whenever we enter sensitive password or access keys.

All Model Links Can Be found Here : [PETRAINED MODELS](https://huggingface.co/transformers/pretrained_models.html)

# *Individual Model Summary* 
outputs and details each model tested has been put below in form of brief summary. 

## Model:  RoBERTa-base [A Robustly Optimized BERT Pretraining Approach]

  -Accuracy
  
    85.07109004739336%

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

