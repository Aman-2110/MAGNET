Onedrive link : https://iiitaphyd-my.sharepoint.com/:f:/g/personal/santanu_biswas_students_iiit_ac_in/EjUi8SEjFjlJnvx7vd8N7tgBhtb2jONOYnyJOex8Nd1a0A?e=kQOBWg
(contains training code, datasets, model checkpoints, inference code)


File Directory Structure -> Team_32 -> 1. MLP -> contains models and train code for different datasets
                                       2. LSTM -> contains models and train code for different datasets
                                       3. BERT -> contains models and train code for different datasets
                                       4. MAGNET -> contains saved checkpoints and train code
                                       5. Dataset -> contains 3 datasets (Toxic comments, Reuters, RCV1-V2)
                                       6. EDA -> contains source code for EDA
                                       7. Experiments -> contains source code and saved checkpoints for the conducted experiments
                                       8. README.md
                                       9. requirements.txt -> contains dependencies

# For training : 
For running particular ipynb files, pretrained embedding files and the dataset files must have similar structure as defined above.

# For Inference : 
After training of model is successfully done, user can input sentence which will be classified over the labels defined in particular dataset using the best model.