This artifact contains the dataset used in the paper **Understanding the Role of External Pull Requests in the NPM Ecosystem**.

# Script
We provide 3 script files
1. `preliminary_A1_2.ipynb` for the preliminary A1 and A2
2. `preliminary_A3.ipynb` for the preliminary A3
3. `rq1.ipynb` for RQ1
Note that RQ2, we used seperated spreed among three authors and count the result.

# Dataset
The appendix contains our quantitative and qualitative datasets, shown in Figure 1 in the paper.
The dataset are provided via this repository and [zenodo](https://doi.org/10.5281/zenodo.6366986) for the large dataset (file size more than 100MB).

There are seven data files as described below:
1. `filtered_dataset_with_label.csv` - A filtered dataset contains 945,291 PR.
2. `external_PR_dataset.csv` - List of the External PR used in preliminary study, RQ1, and RQ2.
3. `internal_PR_dataset.csv`  - List of the Internal PR used in preliminary study, RQ1, and RQ2.
4. `bot_PR_dataset.csv` - List of the Bot PR used in preliminary study, RQ1, and RQ2.
5. `attention_label_ranking.json` - The attention labels of each PR type with count using in RQ1.
6. `ranking_label_bot.csv` - The labels appearing in the Bot PR are already ranked and be used in RQ1.
7. `ranking_label_external.csv` - The labels appearing in the External PR are already ranked and be used in RQ1.
8. `ranking_label_internal.csv` - The labels appearing in the Internal PR are already ranked and be used in RQ1.
9. `sampled_dataset_external_PR.csv` - Result of manual classification of the External PRs used in RQ2.
10. `sampled_dataset_inside_PR.csv` - Result of manual classification of the Internal PRs used in RQ2.
11. `sampled_dataset_bot_PR.csv` - Result of manual classification of the Bot PRs used in RQ2.
