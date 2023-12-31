# 11-711-project-4
This is 11-711 Adv NLP Project 4 Team 11

We aim at using RoBERTa Model to classify emotions in Chinese Dataset (CPED).

## Report
11-711-project-4-report.pdf  

## Dataset Description (./data):
**cn-data-translated-combined**: Final Dataset that we used. Combine adjacent text with same speaker & same emotion label, in order to generate longer sentence with more context.  
**cn-data-original**: Original CPED Dataset.  
**cn-data-revised**: Re-labeled CPED Dataset, using combination of GPT-4 and Manual Mapping.  
**cn-data-translated**: English version of CPED Dataset, translated using Google Translate API.  
**data-for-gpt**: CPED data labeled with "positive-other" and "negative other".  
**go-emotion-data**: GoEmotions Dataset, used for Project 3.  

## Code Description (./code):
- Model 1: **Advanced_Model_Chinese_Roberta.ipynb** Advanced model (Chinese RoBERTa), including training and evaluation process
- Model 2: **Baseline_Model_Emotion_Detection.ipynb** Baseline model (RoBERTa model in assignment 3), fine tuned for translated Chinese dataset.
  
**cn-visual.ipynb**: Visualize CPED dataset (after relabeling, using data in cn-data-revised folder)  
**en-visual.ipynb**: Visualize GoEmotions dataset  
