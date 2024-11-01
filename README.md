# Project structure
# 
# /streamlit_app.py - main python file
# /requirements.txt - includes all required libs
# /NBA Shot Locations 1997 - 2020.csv - contains dataset (IMPORTANT: original file you can download from here: https://www.kaggle.com/datasets/jonathangmwl/nba-shot-locations)
#
# /sources - includes streamlit python files for each pages
#   - introduction_page.py - Introduction to the project
#   - preprocessing_page.py - Preprocessing and feature engineering
#   - visualisation_page.py - Visualizations and Statistics
#   - preprocessing_for_modelling_page.py - Preprocessing for modeling purposes
#   - modelling_page.py - Base Models
#   - deep_learning_page.py - Deep Learning
#   - conclusion.py - Conclusion
# 
# /models - includes trained models and their appropriate parameters(accuracies, classification_reports, shap_plots)
#   - model_best_lr.joblib - Logistic Regression best model
#   - model_dt.joblib - DecisionTree model
#   - model_boosting.joblib - AdaBoosting model
#   - model_best_bagging.joblib - Bagging best model
#   - model_best_rf.joblib - Random Forest best model
#   - model_lenet.keras - CNN LeNet model
#   - model_lenet_training_history_leaky_relu.pkl - CNN LeNet model's history dictionary
#   - model_pytorch_state_dict.pth - PyTorch model's state dictionary
# 
# /models/accuracies - includes models' accuracies
#   - accuracy_cnn_test - CNN LeNet test accuracy result
#   - accuracy_cnn_train - CNN LeNet train accuracy result
#   - accuracy_pytorch_test - PyTorch test accuracy result
#   - accuracy_pytorch_train - PyTorch train accuracy result
# 
# /models/classification_reports - includes models' classification reports
#   - classification_report_model_cnn.txt - CNN LeNet classification report
#
# /models/shap_plots - includes model's SHAP plots
#   - Boosting_shap_plot.png - Boosing SHAP plot
#   - Random Forest_shap_plot.png - Random Forest SHAP plot

# How to run the app?
# 1. Open terminal app
# 2. change directory to 'streamlit' folder 
# 3. This step is optional: you can replace 'NBA Shot Locations 1997 - 2020.csv' dataset file from here: https://www.kaggle.com/datasets/jonathangmwl/nba-shot-locations
# 4. run this command:
#   streamlit run streamlit_app.py
# 5. Select 'Preprocessing for modeling purposes' page for generating joblib file for train_test_split
# 6. All pages will work without any problem
