<img src='https://github.com/lewagon/data-images/blob/master/ML/kaggle-batch-challenge.png?raw=true' width=600>

Objective is to submit my attempt at the challenge to the leaderboard - I finished in the top 13%

```bash
cd ~/code/<user.github_nickname>/<program.challenges_repo_name>/05-ML/07-Ensemble-Methods/Houses-Kaggle-Competition
curl https://wagon-public-datasets.s3.amazonaws.com/houses_train_raw.csv > data/train.csv
curl https://wagon-public-datasets.s3.amazonaws.com/houses_test_raw.csv > data/test.csv
curl https://wagon-public-datasets.s3.amazonaws.com/houses_sample_submission.csv > data/sample_submission.csv
pip install --upgrade pip
pip install --upgrade scikit-learn
```

Open `houses_kaggle_competition.ipynb` and follow instruction
