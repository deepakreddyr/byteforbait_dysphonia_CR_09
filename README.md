DATASET - The Saarbrucken voice disorder database ~ https://stimmdb.coli.uni-saarland.de/

STEPS:
1. PRE PROCESSING - Feature Extraction using Mel-frequency cepstral coefficients (MFCC).
2. MODEL BUILDING
3. INTERACTIVE WEB PAGE
4. INTEGRATION OF MODEL WITH WEBPAGE

FILES:
1. DYSO.ipynb - A JupyterNotebook that contains the steps for data prepocessing and model building
2. dysphonia.csv - A CSV file that consists of the file path and the classes it belongs
3. dysphonia.h5 - A model that is loaded into a h5 file that is used to make predictions when loaded into a vraiable in the webapp which has an accuracy of 78%
4. dysphoniacvv.h5 - A CVV implemented model that is loaded into a h5 file that is used to make predictions when loaded into a vraiable in the webapp which has an accuracy of 93%

