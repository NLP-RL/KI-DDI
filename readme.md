KI-DDI

Knowledge-Infused, Discourse-aware Disease Identification

To train the model please follow the instructions

1. Make sure you are connected to GPU (Our experiments were carried out in Nvidia A100 GPU)
2. For training model run the file linear_plus_knowledge_self_report_having_first_utterance_one_disease.ipynb and save the weights corresponding to the best accuracy. 
3. The code is for the case when each symptom has atmost one disease connected to them (one red node for each blue node in figure).
4. In one_disease_data you will find data that has 3 parts:
   (a) final_combined_all_dialog.p - It has entire dialog.
   
   (b) final_combined_all_self_report.p - It has only the very first utterance by patient i.e it has self report.
   
   (c) joint_graph - It has the joint graph formed by combined subgraph and dialog node relevant to each dialog.
5. Results reported are mean value of running experiments 3 times.
