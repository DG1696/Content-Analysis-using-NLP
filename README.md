Master's Thesis in Data Science and Business Analytics

Project Title: Unravelling User Insights through Topic Modeling 

Report Link -(https://github.com/DG1696/Content-Analysis-using-NLP/blob/07654a901e6196408145fd048ab85f17589ffa94/Topic_Modeling_on_the_application_of_British_Telecommunication_Data(Msc%20Thesis)%20pdf.pdf)

Project Overview:
This project involves the use of Natural Language Processing (NLP) techniques and Topic Modeling to analyze user-generated content from the BT Community Forum. The aim of this project is to extract actionable insights and identify underlying patterns in user discussions, using advanced topic modeling algorithms. By automating the process of data analysis, the project reduces the manual effort of analyzing large datasets and provides a more efficient way to extract meaningful information.

Through this project, I was able to transform noisy, unstructured data into clear insights, resulting in the identification of key discussion topics and trends. This approach helped stakeholders understand user concerns and preferences, enabling data-driven decision-making.

The project scored "Distinction" in my Master’s research, demonstrating the value and significance of the insights generated.

Objective:
The primary objective of this research project was to implement and apply Topic Modeling (specifically Latent Dirichlet Allocation (LDA)) on unstructured user data from the BT Community Forum. 
The goal was to,
- Identify key topics discussed by users.
- Track trends in user discussions over time.
- Automate data analysis to improve efficiency and reduce manual effort.
- Generate actionable insights that could inform decision-making.
- Tools & Technologies Used

Data Visualization snapshots.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bed8ddb0-aa05-48ee-9d93-f48b60e683c3" width="300" />
  <img src="https://github.com/user-attachments/assets/a6b039d8-d376-4612-871a-c87c3c8e5baf" width="300" />
  <img src="https://github.com/user-attachments/assets/2888da8f-dd6f-4b47-ab50-6a4c1b3a0481" width="300" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/036f2f84-5238-4a18-9a9b-95198abfbd69" width="300" />
  <img src="https://github.com/user-attachments/assets/03fa99ea-d5fe-4dd0-ab01-dd326debf9ba" width="300" />
  <img src="https://github.com/user-attachments/assets/db4b018e-0971-41ec-9a2d-09309c5027fd" width="300" />
  <img src="https://github.com/user-attachments/assets/32784a7a-95d9-4c20-a06e-52dae610981c" width="300" />
</p>


Tools used throughout the project to clean, preprocess, analyze, and visualize the data:
Python Libraries:Pandas, NumPy for data manipulation and handling large datasets.
NLTK, SpaCy for text preprocessing (tokenization, stopword removal, lemmatization).
Gensim for topic modeling using Latent Dirichlet Allocation (LDA).
Scikit-learn for feature extraction (TF-IDF, vectorization).
Matplotlib, Seaborn for data visualization, including word clouds and topic visualizations.
Other Tools: Jupyter Notebooks for running experiments and performing exploratory data analysis.

Data Description:
The dataset consists of user comments and posts from the BT Community Forum, a popular online platform where users discuss issues related to BT services.
The dataset contains over 1 million rows of text data, including comments, reviews, and forum discussions.
Data preprocessing was crucial, with steps like noise removal, tokenization, lemmatization, and stop-word removal, reducing the noisy data by 96.77%, which significantly improved model performance.

Methodology:
Data Preprocessing:

Text Cleaning: Noise in the data was reduced by 96.77% through techniques like removing HTML tags, special characters, stopwords, and non-alphanumeric tokens.
Tokenization and Lemmatization: Split text into tokens and reduced words to their root form for uniformity.
Vectorization: Used TF-IDF to transform text data into numerical features suitable for modeling.
Topic Modeling:

Applied Latent Dirichlet Allocation (LDA) for identifying hidden topics within the data.
The model was trained with X topics (based on coherence score and manual validation), each of which represents a set of words frequently discussed together in the forum.
Each topic was analyzed and manually labeled based on the most frequent words associated with it.
Data Visualization:

Used Matplotlib and Seaborn to visualize the topics, providing stakeholders with easy-to-understand insights.
Visualized the frequency of words per topic and the overall distribution of topics over time, helping to identify trends and hot spots in user discussions.
Exporting Insights:

Generated reports and summaries of the top topics, enabling stakeholders to access the findings in a structured format.
Created interactive visuals that allowed stakeholders to filter data and examine trends over time.

Conclusion :

In conclusion, the analysis of the BT community forum dataset using various topic modeling techniques, including LDA, NMF, and LSA, has provided valuable insights into the discussions and themes prevalent within the forum. While all three models have their strengths and advantages, the NMF (Non-Negative Matrix Factorization) model, particularly in its 10-topic configuration, has demonstrated its ability to provide comprehensive and specialized insights based on the BT community data.
