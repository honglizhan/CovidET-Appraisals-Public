# CovidET-Appraisals (EMNLP 2023)

This repo contains the dataset for our EMNLP 2023 findings paper. If you use this dataset, please cite our paper.

Title: <a href="https://arxiv.org/abs/2310.14389">Evaluating Subjective Cognitive Appraisals of Emotions from Large Language Models</a>

Authors: <a href="https://honglizhan.github.io/">Hongli Zhan</a>, <a href="https://cascoglab.psy.utexas.edu/desmond/">Desmond C. Ong</a>, <a href="https://jessyli.com/">Junyi Jessy Li</a>

## 1. Dataset
The CovidET-Appraisals dataset can be found under the "data" folder. CovidET-Appraisals contains a total 241 unique Reddit posts, each annotated with judgments on 24 emotion appraisal dimensions pertaining to how the narrator feels about and views the situation that they are going through (e.g., whether the narrator feels the situation they are in is something they could control), as well as rationales for the judgments in the form of natural language explanations. Among them, 40 of the posts were annotated by 2 annotators for inter-annotator measurements.

## 2. Responses from LLMs
The prompts we used to elicit the responses from LLMs are provided under the folder "./LLM_responses/prompts". We provide the raw responses recorded from LLMs (GPT-3.5-turbo, Alpaca, Dolly, Flan-T5) under the "./LLM_responses/Responses-Raw" folder. To enable a fair comparison of models, we sample from the LLMs five times with different model initializations. We additionally clean the responses elicited from the LLMs using regular expressions (under the folder "./LLM_responses/Responses-Cleaned").

## 3. Human Evaluation
As rationalizing emotional appraisals with natural language is a novel task, we perform extensive human evaluation on both human-annotated and LLM-generated rationales. We recruit evaluators from the Amazon Mechanical Turk (MTurk) to work on our human evaluation task, and their evaluation is recorded under the "Human_EVAL" folder.

```bibtex
@inproceedings{zhan-etal-2023-appraisals,
    title = "Evaluating Subjective Cognitive Appraisals of Emotions from Large Language Models",
    author = "Zhan, Hongli  and
      Ong, Desmond  and
      Li, Junyi Jessy",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
}
```


[![ClustrMaps Tracker](https://www.clustrmaps.com/map_v2.png?d=hscvcJEH3ZC7uj3MYaSB93PHb_T-Uw_QGE88O-cQIq4&cl=ffffff)](https://clustrmaps.com/site/1bwuc)

(Traffic since Oct 7th, 2023)
