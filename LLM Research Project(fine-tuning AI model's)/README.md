# LLM-Conversational-Acuity

You should be able to find and add results through this [link](https://docs.google.com/spreadsheets/d/1iiRd8d2JwryC6t5yJ4FuXY50Q8X_rvqHH0dDc2m2ZuQ/edit?usp=sharing).

## Dataset

 <i> This can be found in the ```/DatasetFiles``` <i>
 
```PromptDataset.csv``` is the dataset we will be using for fine-tuning the LLM. Download the CSV and save it to the main Google Drive.

```PromptDataset_yourgpt.jsonl``` is the JSONl file version of PromptDataset.csv.

```csvjson.json``` is the JSON file version of PromptDataset.csv.

## Models
 <i> Each model will have a folder with the name of the model <i>
 
### GPT-3.5 Turbo Files
```GPT3_5FineTuned_with_parameters.ipynb``` contains all the fine-tuning with adjusted parameters.

### GPT-4o mini Files and GPT-4o Files
You will have to replace the ```gpt-3.5-turbo``` in the folder of gpt3.5 turbo with ```gpt-4o-mini``` for **GPT-4o mini** and ```gpt-4o-2024-08-06``` for **GPT-4o**. This should replace the 3.5 Turbo model with the model that you need.

### Llama 2
```llama_2.ipynb``` contains all the fine-tuning with adjusted parameters. 

## Model Comparison
```Text_Comparison.ipynb``` contains the quantitative metrics (cosine similarity, Jaccard similarity, Levenshtein distance) for determining text similarity.

## Not Used 
 <i> We will not be using Gemini model for our experiment <i>
 
### Gemini model -- We will not be using these files for our experiment
```Gemini.ipynb``` is the Gemini API key applied to a Colab notebook.

```Gemini_w_RL_and_FT (1).ipynb``` is the edited notebook with implementations for RLHF and fine-tuning. We will have to adjust to keep up with our dataset.

```Gemini_w_RL_and_FT (2).ipynb``` is the mopst recent. It contains dataset implementation, as long as the PromptDataset.csv is saved in the main Google Drive. Otherwise, path information will need to be adjusted accordingly.
