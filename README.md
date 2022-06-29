# MSc Thesis Project

## Master Information Studies: Data Science track

### A user interface for communicating AI assisted diagnosis using atrophy progression timelines in all-cause dementia

#### This project was carried out as part of a Master’s Thesis project at the University of Amsterdam, in collaboration with UMC’s Alzheimer Center.

*Author: Julia Rzepka, University of Amsterdam, submitted in partial fulfillment for the degree of Master of Science*

*Internal Supervisor: Sara Mahdavi Hezavehi, UVA*

*External Supervisor: Vikram Venkatraghavan, Amsterdam UMC (VUmc Alzheimer Center)*

Various techniques have been examined to diagnose stages and types of dementia, including support vector machines, deep neural networks, or event-based modeling. These methods have been shown to outperform humans in the detection of certain patterns and anomalies. However, performance does not go hand in hand with transparency and explainability. Physicians often struggle to interpret the decisions of AI-driven systems, due to a lack of understanding on what basis the decisions are made. To address this issue, this project focused on developing an interactive user interface (UI) for disease course sequencing and disease subtyping. Created visualisations were integrated with an event-based model called Snowphlake (Staging NeurOdegeneration With PHenotype informed progression timeLine of biomarKErs), which is currently under development at University Medical Center (UMC) in Amsterdam. The results of the project were presented in the form of a dashboard and evaluated by conducting qualitative semi-structured interviews with medical professionals available at UMC. Overall, all participants in user testing agreed that the UI provides sufficient explanations, is visually attractive and intuitive to use. The results of the qualitative evaluation were confirmed by the system usability questionnaire, which was aimed at measuring the usability of the interface. Although the created UI was found to be useful for research purposes, at the current level of development, it is not yet sufficient to be implemented in clinical practice. 

<p align="center">
<img src="https://github.com/rzepkka/Master-Thesis-Project/blob/main/title_page.png" width="900" height="400">

- [UI](https://github.com/rzepkka/Master-Thesis-Project/tree/main/UI) - this folder contains all Python and R files used to create the User Interface (UI) for AD diagnosis. It  includes a *data* folder with the data that was used for group-based visualizations. The data necessary to generate patient-specific information is not included in the folder, for the security and privacy of UMC's patients.

- [notebooks](https://github.com/rzepkka/Master-Thesis-Project/tree/main/notebooks) - this folder contains Jupyter Notebooks files with examples of how the created visualization functions can be applied. 
  
- [Evaluation](https://github.com/rzepkka/Master-Thesis-Project/tree/main/Evaluation) - this folder contains the interview protocol, coding schema and individual responses to the usability questionnaire.

- [Master_Thesis]([https://github.com/rzepkka/Master-Thesis-Project/Master_Thesis.pdf](https://github.com/rzepkka/Master-Thesis-Project/blob/main/Master_Thesis.pdf)) - thesis report



