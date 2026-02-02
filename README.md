# 📖About LSM-MRCF
This repository contains the implementation of LSM-MRCF for accurate network traffic prediction. When reproducing, please make sure to modify the data format and the reference path.

## 🚀Running the model
First, the initial prediction values and the overall confidence levels are obtained by running the code of each predictor in the "Multi-predictor" folder separately. Subsequently, we prepare datasets for the decision-making by the LLM. The historical data, excluding the true values corresponding to the predictions is utilised as sheet1. Sheet2 and 3 contain the prediction values of two predictors, while sheet4 and 5 encompass the validation predictions，together with the comprehensive confidence as the fundamental data supporting LLM decision-making. Ultimately, the "finetuning" code is executed to obtain the final enhanced predictions.

## 🔒Important Notice
Due to commercial confidentiality and pending patent filings associated with this industry collaboration, only a partial implementation of our model is currently available. The full source code and data will be made publicly available upon patent filing and paper acceptance.
