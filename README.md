
<img src="https://github.com/nayantaramohan/DATA-591-Team-Virufy/blob/main/images/virufy-logo.png" width="180" align="right">    
<img src="https://github.com/nayantaramohan/DATA-591-Team-Virufy/blob/main/images/uw-logo.png" width="170" align="right">  
 
# DATA 591 Wi 2023: Capstone Project
#### COVID-19 detection on cough audio samples using HUBERT 

## Goal
Virufy aims to build a free smartphone app to detect COVID-19 from cough recordings through machine learning analysis of audio signals, which would allow for mass-scale testing of COVID-19 and could effectively stop the spread of the virus. We are building an end-to-end system that preprocesses cough (audio signals) data and gives a binary output of whether COVID-19 is present or not. This model involves audio engineering and extracting relevant features which shall be hosted on Amazon infrastructure and can be accessed through a REST API.

## Motivation
Over 800,000 people have died as a result of COVID-19 in the US and 5 million worldwide as of this writing. A record number of hospital beds have been occupied due to COVID-19's high infectiousness, exceeding hospital capacity and placing a tremendous burden on global healthcare systems. Despite ongoing global immunization campaigns, distribution attempts in low- and middle-income nations have been limited. Additionally, the efficacy of the current vaccinations in stopping the spread of COVID-19 has been reduced due to the emergence of new viral variations such as Omicron.    
  
Emerging Artificial Intelligence (AI) technologies have demonstrated the capacity to develop quick, inexpensive, and available solutions. There is growing evidence that using machine learning and deep learning techniques, one may predict COVID-19 by listening to infected individuals' coughs. This study advances the development of an audio-based COVID-19 diagnostic tool by demonstrating adequate performance on a sizable and varied dataset. Future work should aim at gathering large numbers of PCR-validated samples and determining the model's generalizability to additional datasets, in addition to enhancing model performance.    
  
The approach to data is different in this study as this is a novel approach where the data is a sound sample. For COVID-19 patients of all ages, in various environments, symptomatic and asymptomatic, and at various times relative to symptom onset, numerous research groups have been collecting sound recordings.
There is a significant impact on the industry: a prospective, entirely digital COVID-19 detection approach would enable a smartphone-based quick, fair COVID-19 test with no danger of infection, financial burden, and supply chain problems—all features that are beneficial for reducing COVID-19 spread. Given the significance, it is necessary to investigate and create digital COVID-19 exams that are based on machine learning.

## Repository tree
```
├── data
│   ├── virufy-cdf-coswara
│   ├── virufy-cdf-coughvid
│   ├── virufy-cdf-india-clinical-1
│   ├── model_train_data_set_1_public.csv
│   └── model_val_data_set_1_public.csv
├── documentation
│   ├── virufy-data-exploration.pdf
│   ├── virufy-project-proposal.pdf
│   ├── virufy-poster.pdf
│   └── virufy-team-bios.pdf
├── images
│   ├── img-tentative.png
│   ├── uw-logo.png
│   └── virufy-logo.png
├── model
│   ├── config.json
│   └── pytorch_model.bin
├── hubert_test.ipynb
├── hubert_train.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```

## Input Data & Sources
1. **virufy-cdf-coswara**: [description to be added - high level]
2. **virufy-cdf-coughvuid**: [description to be added - high level]
3. **virufy-cdf-india-clinical-1**: [description to be added - high level]

Total number of samples:
Number of training samples:
Number of validation samples:

## Special Considerations
- [Explain the limitation of number of positive samples being less...lala... final number of samples taken for our analysis is....]

## Data Licenses
All the data sets are a property of Virufy and is not to be accessed by public.   
[Link to the privacy policy](https://drive.google.com/file/d/1EB_9q8nSxvJXWMtCfxCWmisM-n03TJYz/view)


## Snapshot of Analysis Output
[Add image of the pipeline]
[Add image of the confusion matrix]
[high level explanation]

## Risks and benefits of the proposed solution
The use of AI for predicting if someone has COVID-19 could potentially have several benefits. For example, it could help healthcare providers more quickly and accurately diagnose patients, potentially leading to earlier treatment and better outcomes. It could also help healthcare systems prioritize the allocation of resources, such as testing and personal protective equipment, to those who are most in need.

However, there are also potential risks and limitations to using AI for COVID-19 prediction. One major concern is the accuracy of the predictions. AI algorithms are only as good as the data they are trained on, and the accuracy of their predictions can be affected by a variety of factors, such as the quality and diversity of the training data. There is also the potential for bias in the data or the algorithm, which could lead to unfair or inaccurate predictions.

Another potential risk is the ethical concerns around using AI for medical diagnosis. Some people may be uncomfortable with the idea of relying on a machine to make important medical decisions, and there are valid concerns about the potential for errors or misdiagnoses.

Overall, the use of AI for predicting COVID-19 infections could have potential benefits, but it is important to carefully consider the risks and limitations and ensure that any AI systems are developed and used responsibly.

## References
[1] Haritaoglu, E. D., Rasmussen, N., Tan, D. C. H., J., J. R., Xiao, J., Chaudhari, G., Rajput, A., Govindan, P., Canham, C., Chen, W., Yamaura, M., Gomezjurado, L., Broukhim, A., Khanzada, A., & Pilanci, M. (2022, March 30). Using deep learning with large aggregated datasets for covid-19 classification from cough. arXiv.org. Retrieved November 22, 2022, from [https://arxiv.org/abs/2201.01669](https://arxiv.org/abs/2201.01669).   
  
[2] Nemati, E., Rahman, M. M., Nathan, V., Vatanparvar, K., & Kuang, J.
(2020, July). A comprehensive approach for classification of the cough type. In 2020 42nd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC) (pp. 208-212). IEEE.    

[3] Mouawad, P., Dubnov, T., & Dubnov, S. (2021). Robust detection of COVID-19 in cough sounds. SN Computer Science, 2(1), 1-13.    

[4] Chaudhari, G., Jiang, X., Fakhry, A., Han, A., Xiao, J., Shen, S., & Khanzada, A. (2020). Virufy: Global applicability of crowdsourced and clinical datasets for AI detection of COVID-19 from cough. arXiv preprint arXiv:2011.13320.    

[5] Fakhry, A., Jiang, X., Xiao, J., Chaudhari, G., Han, A., & Khanzada, A. (2021). Virufy: A multi-branch deep learning network for automated detection of COVID-19. arXiv preprint arXiv:2103.01806.    

[6] Feng, K., He, F., Steinmann, J., & Demirkiran, I. (2021, March). Deep-learning based approach to identify covid-19. In SoutheastCon 2021 (pp. 1-4). IEEE.


## Best practices for documentation
- PEP 8 – Style Guide for Python Code ([Reference link](https://peps.python.org/pep-0008/))
- Use of relative path addresses to help in reproducibility
- Use of intuitive variable and function names to ease in understanding
- Appropriate comments and documentation provided for the data aquisition, data processing and data analysis steps
- Description of all data files present in the repository mentioned


## Authors
[Charles Reinertson](https://github.com/charles-reinertson)  
[Nayantara Mohan](https://github.com/nayantaramohan)  
[Urmika Kasi](https://github.com/urmikakasi)

