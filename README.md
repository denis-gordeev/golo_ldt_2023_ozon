# golo_ldt_2023_ozon

Our solution for the https://lk.leaders2023.innoagency.ru/ hackathon

We first generate folds using `generate_folds.ipynb`

Then we train Deberta-v3 models using `train_deberta-kfold.ipynb`

Then we combine Deberta-predictions with other features aand train Catboost on the same folds using `baseline-denis-kfold-2.ipynb`
