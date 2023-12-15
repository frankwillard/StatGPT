# StatGPT

## Few-Shot Prompting

590_prompting.ipynb runs all the few-shot prompting experiments with Flan-T5-XXL

## Zero-Shot Prompting

590ChatGPTprompting.ipynb rules all the chatGPT zero-shot prompting experiments.

## Fine-Tuning

GPT_2_Champion.ipynb includes the code for fine-tuning GPT-2 for the NBA Champion prediction task.

GPT_2_Champion_Weighted_Loss.ipynb includes the code for fine-tuning GPT-2 with loss rescaling for the NBA Champion prediction task.

GPT_2_HOF.ipynb includes the code for fine-tuning GPT-2 for the NBA Hall of Fame prediction task.

GPT_2_VORP.ipynb includes the code for fine-tuning GPT-2 for the VORP prediction task.

## Baselines

NBA_Champion_Baseline.ipynb includes all of our baseline experiments (Logistic Regression, Decision Tree, Random Forest, XGBoost) for the NBA Champion prediction task.

HOF_Baseline.ipynb includes all of our baseline experiments (Logistic Regression, Decision Tree, Random Forest, XGBoost) for the NBA Hall of Fame prediction task.

VORP_Binary_Baseline.ipynb includes all of our baseline experiments (Logistic Regression, Decision Tree, Random Forest, XGBoost) for the VORP prediction task.

## Additional Experiments

GPT_2_Champion_Ranking_Weighted_loss.ipynb includes the code for fine-tuning GPT-2 with loss rescaling for the NBA Champion prediction task, but looks into how well the model ranks the teams in a year. 

GPT_2_Champion_Ranking_without_won_last.ipynb includes the code for fine-tuning GPT-2 with loss rescaling for the NBA Champion prediction task, but looks into how well the model ranks the teams in a year (while excluding the won_last variable to induce better overall performance by not relying too heavily on one variable). 
