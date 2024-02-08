# ML-Project-PREDICTION-OF-THE-PRODUCTION-OF-SOLAR-ENERGY

## Summary:

 The purpose of this project is to apply different methods of machine learning and hyperparameter automatic learning and hyperparameter tuning / optimisation (HPO). In addition, the aim is to determine the best method for a dataset (model selection, including hyperparameter fitting, estimating the future performance of the best method including hyperparameter fitting), estimate the future performance of the best method (model evaluation) and (model evaluation) and build the final model and use it to make new predictions on new data (model use) to predict the production of solar energy.

## Content:

- disp_st12ns1.txt: available data (for training, HPO, evaluation and final model building). The available data contains the 75 attributes and the response variable ("output"). Contains 12 years of data, one instance per day (365-day years).
- comp_st12ns1.txt: competition data, on which to use the final model to make predictions. This is 2 years of data (one instance per day) with the 75 input variables, but without the response variable.
- Busqueda_modelo_disp.ipynb: EDA, hyperparameter setting, model selection... The notebook has explanations of the processes, analysis of the results, justifications of the decisions using tables and graphs.
- Prediccion_final_comp.ipynb: loads the final model and use it to make predictions on the competition data.
- modelo_final.pkl: is the file that contains the final model.
- predicciones: is the file that contains the predictions.

## Technologies:

  - Python: data collection, data exploration and preprocessing, data visualization anda data partitioning.
  - Scikit-learn: model selection, model training, model evaluation, model tuning and model deployment.

## Team:
  
  - Arianna Potente Vázquez: https://github.com/Ari-Potente
  
  - Ernesto Gracia Cancho: https://github.com/Ernesto-Gracia-Cancho

## Report

In the "Busqueda_modelo_disp" and "Prediccion_final_comp" files you can find in detail the process of what is being done and the conclusions reached.
