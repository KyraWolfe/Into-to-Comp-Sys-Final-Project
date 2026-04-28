# Into-to-Comp-Sys-Final-Project

# group members:
- Kyra Wolfe 
# project on: 
- phishing
# goal: 
- to detect a phishing scam from a safe email
# database: 
- phishing email dataset from kaggle
- https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset
- focusing on the CEAS_08 file specifically
# Articles to be Cited:
- *Al-Subaiey, A., Al-Thani, M., Alam, N. A., Antora, K. F., Khandakar, A., & Zaman, S. A. U. (2024, May 19). Novel Interpretable and Robust Web-based AI Platform for Phishing Email Detection. ArXiv.org. https://arxiv.org/abs/2405.11619*
# YouTube Videos and Notebooks Referenced
- https://www.youtube.com/watch?v=NzvnWflWk64
- https://www.youtube.com/watch?v=xqPW4NA2KI8
- https://www.kaggle.com/code/mubarakalamiri/phishing-email-detection-using-bert-project 
# details 
- dataset has roughly 39,154 emails
- confidence = 0.5
- error = 0.5
- features = 4 (sender, subject, body, url)
- VC = 5
- can change numbers as needed, have plenty of data
- 1 means scam, 0 means safe in database
# updates 
- dataset loaded using google colab
- downloaded directly as a zip files, file was unzipped and the specific file CEAS_08.csv was chosen and added to a variable
- planning on using a decision tree
- decision tree only works with numbers, my data uses strings and none of the strings are consistent enough to assign a number to
- switched to using BERT from transformers
- referencing code using YouTube and any notebooks I can find in the Kaggle for my dataset that also use BERT
- going to use the train test split from sklearn to break up the dataset and train on part and test accuracy on the rest
- as of Monday the 27th, I am not too sure if I will have time to fully train the model but am hoping to have all the necessary code present in the Colab
- ideally would like to measure the prediction ability and accuracy if there is time
- the notebook has errors in lines and I am not too sure exactly why
- May end the project at this point since I feel I do not have time to keep writing code without directly copying everything from previous notebooks and will really not have time to even get to training or training code
# additional details
- don't really know how push works
- might not be push feature in google colab
- will post active link here and hope for the best
- will update the push when done with project
- update: figured out how to add updated colab code without created a whole new thing each time in Github
# conclusion
- underestimated how much time it would take to create code for strings
- did not realize there was so much more prep to run strings
- would have probably chosen a database that had numbers attached to certain strings or just numbers data
- was happy to learn about the existence of google colab as I do not think my laptop could have run on my laptop
