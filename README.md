# Clinical NER  in the lung cancer domain
This repository contains a deep learning-based implementation to extract lung cancer named-entities from clinical notes Written in Spanish.

Clinical named entity recognition (CNER) is performed using two deep learning models: BiLSTM and BERT. 

To train these models, we annotated a lung cancer corpus that contains 19,000 annotated sentences using nineteen entity types. 

<br> 
<strong>1. BiLSTM-CRF:</strong> This model is combined con clinical emebeddins pre-trained for Spanish. The directory BiLSTM contains the code for trining this model.<br> <br>

<strong>2. BERT</strong>: We used multilingual BERT fine-tuned with a classitication layer on top. The directory BERT contains the code for trining this model.<br>

<strong>3. The lung cancer corpus </strong> is governed by the General Data Protection Regulation (GDPR) (EU) 2016/679 of the European Parliament. This corpus is available "upon request". This corpus can be accessible after an evaluation by the hospital's ethics committee. To request access to the anonymized data, please contact Dr. Maria Torrente at the following email: maria.torrente@salud.madrid.org 

<strong>4. Tained-models: </strong> We provide trained models on the lung cancer corpus. These models can be used to evaluate or exploit them by performing real-life study cases with clinical notes written in Spanish. Trained models can also be used to integrate them into medical text mining applications. The directory "trained_models" contains instructions for using these models.

<strong>Contact:</strong><br>

If you have any question or suggestion, please contact us at the following email address: oswaldo.solartep@alumnos.upm.es


