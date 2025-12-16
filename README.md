## How to reproduce the analysis

1. Clone the repository:
   git clone https://github.com/juliajensine/Contesting_Gender_Equality.git
   cd project-name

2. Create the environment:
   conda env create -f environment.yml
   conda activate gender-sentiment

3. Prepare the data:
   Download data: https://zenodo.org/records/15480855
   Ajust path in Setup file

5. Prepare Data:
   Run 01_Notebook_SetUp.ipynb

7. Train Classifier:
   Run 02_Notebook_Classifier.ipynb

8. Run Sentiment Analysis:
   Run 03_Notebook_SentimentAnalysis
