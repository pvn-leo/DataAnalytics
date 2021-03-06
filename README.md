
# Analysis on the Impact of Weather and Road Conditions on traffic accidents in USA


### Dataset
[Kaggle - US Accidents](https://www.kaggle.com/sobhanmoosavi/us-accidents)  

### Instructions for execution
It is advised to run the whole project under Colab.  
This drive folder link shared through google form contains all notebooks, models and data placed in their rightful directories. `Add it to your drive and ensure paths are changed in the third cell if, in case it doesn't work`
1. **plug_and_play.ipynb** - uses sampled dataset, saved Random forest and Decision tree models. (plug and play)
2. **Final_Model_Dataset_Extraction** - used to save the sampled dataset along with Random Forest and Decision Tree models.
3. **EndToEnd.ipynb** - has all the necessary code for data cleaning and model training + testing + evaluation phases. A complete `Runtime -> Restart and run all` will produce all the necessary results in about 10-15 minutes. 

Working tree of **final/** folder.
Ensure you add a complete copy to your drive and start executing, since the final/ dir has only Viewer permissions.
```sh
final
├── Copy_of_EDA.ipynb
├── data
│   ├── sampled_US_accidents.csv
│   ├── US_accidents1.csv
│   └── US_Accidents_June20.csv
├── EDA+Plots_after_cleaning.ipynb
├── EndToEnd.ipynb
├── Final_Model_Dataset_Extraction.ipynb
├── models
│   ├── dtc_entropy.model
│   ├── dtc_gini.model
│   └── rfc.model
├── plug_and_play.ipynb
└── reports
    ├── Copy_of_general_report
    └── stage1-48_Goal_Diggers_PES1201802018_PES1201800157_PES1201802000
```
