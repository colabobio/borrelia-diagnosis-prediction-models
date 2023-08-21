# Borrelia prediction models

These repository includes the Jupyter notebooks to derive logistic regression models that predict Borrelia diagnosis using clinical and laboratory data of patients.

* 2018-2019-Clinical-Malaria-Cleaned.ipynb: This notebook constructs a clinical-only prediction model using data from 2018 and 2019, including patients who were currently diagnosed positive with malaria 

* 2018-2019-Clinical-No-Malaria-Cleaned.ipynb: This notebook constructs a clinical-only prediction model using data from 2018 and 2019, removing all patients who were currently diagnosed positive with malaria.

* 2019-Clinical-Cleaned.ipynb: This notebook constructs a clinical-only prediction model using data from 2019, for all patients (malaria negative and postive)

* 2019-Clinical+Lab-Cleaned.ipynb: This notebook constructs a clinical + lab prediction model using data from 2019, for all patients (malaria negative and postive)

* BestModel_2018train_2019test.ipynb: This notebook constructs a clinical-only model from 2018 data and validates it on 2019 data, for all patients (malaria negative and postive)