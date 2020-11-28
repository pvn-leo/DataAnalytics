
# DataAnalytics


### Dataset
[Kaggle - US Accidents](https://www.kaggle.com/sobhanmoosavi/us-accidents)
### Instructions for execution
It is advised to run the whole project under Colab.  
This [final folder](https://drive.google.com/drive/folders/1pk7Eo-0JsE5PYBjy-YqhMyJAGfZ5vIrL?usp=sharing) contains all notebooks, models, data placed in their rightful directories. `Add it to your drive and ensure paths are changed in the third cell if, in case it doesn't work`
1. ReproduceRun.ipynb - uses sampled dataset, saved Random forest and Decision tree models. (plug and play)
2. Final_Model_Dataset_Extraction - used to save the sampled dataset along with Random Forest and Decision Tree models.
3. EndToEnd.ipynb - has all the necessary code for data cleaning and model training + testing + evaluation phases. A complete `Runtime -> Restart and run all` will produce all the necessary results in about 10-15 minutes. 

Working tree of **final/** folder.
Ensure you add a complete copy to your drive and start executing, since the final/ dir has only Viewer permissions.
```sh
final
├── data
│   ├── sampled_US_accidents.csv
│   └── US_Accidents_June20.csv
├── EndToEnd.ipynb
├── Final_Model_Dataset_Extraction.ipynb
├── models
│   ├── dtc_entropy.model
│   ├── dtc_gini.model
│   └── rfc.model
└── ReproduceRun.ipynb
```