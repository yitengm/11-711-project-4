# 11-711-project-4
This is 11-711 Adv NLP Project 4 Team 11

We aim at using RoBERTa Model to classify emotions in Chinese Dataset (CPED).


Dataset Description:
cn-data-original: Original CPED Dataset.
cn-data-revised: Re-labeled CPED Dataset, using combination of GPT-4 and Manual Mapping.
cn-data-translated: English version of CPED Dataset, translated using Google Translate API.
cn-data-translated-combined: Combine adjacent text with same speaker & same emotion label, in order to generate longer sentence with more context.
data-for-gpt: CPED data labeled with "positive-other" and "negative other".
go-emotion-data: GoEmotions Dataset, used for Project 3.

Jupyter Notebook Description:
cn-visual.ipynb: Visualize CPED dataset (after relabeling, using data in cn-data-revised folder)
en-visual.ipynb: Visualize GoEmotions dataset