# FairytaleQA_Baseline

Papers about this dataset and Machine Learning models trained on this dataset have been submitted for publication. Progress on those papers will be updated here.

We have a separate Repository for the FairytaleQA Dataset here: https://github.com/uci-soe/FairytaleQAData

### Todo List
- [x] Provide model checkpoints used in the paper
- [x] Provide code to predict/evaluate QA (Question Answering) Baseline
- [x] Provide code to predict/evaluate QG (Question Generation) Baseline

This repo contains all the dependencies for the baseline QA/QG experiments, except for the model checkpoint because of size limit.
You may find the model checkpoints for the baseline results below:
1. QA Models
  * BART fine-tuned on NarrativeQA: https://drive.google.com/file/d/13d6_MlXj_gvNUliDneEkm3TO_P4uuTyR/view?usp=sharing 
  * BART fine-tuned on FairytaleQA: https://drive.google.com/file/d/1jEVAAJy-R-Gb1a4I5C66m7xq2vg02akV/view?usp=sharing
2. QG Models
  * BART fine-tuned on NarrativeQA: https://drive.google.com/file/d/1CEtKT1-t1qKTvDXAmdXoZl52MtZRO6b4/view?usp=sharing
  * BART fine-tuned on FairytaleQA: https://drive.google.com/file/d/1KA39dLn1GgxpEiPQ0IXiV2F6MJwPMs8L/view?usp=sharing
  * BART fine-tuned on NarrativeQA & FairytaleQA: https://drive.google.com/file/d/1TtVGTT42a_UNhU9HBY27h2Gf_KTCCek2/view?usp=sharing

```Github_QA&QG_generate_answers_on_test_val.ipynb``` is the notebook used for the QA/QG generation. After cloning this repo in the first cell, you need to put the model checkpoint in ```./models```. If you are using Google Colab, also remember to restart the runtime after installing the dependencies (Colab will have an automatic prompt as well).



