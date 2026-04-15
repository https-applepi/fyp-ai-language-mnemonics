# Multi-Media Language Learning with AI

## Project overview
This repository contains the artefacts for my final year project, **Multi-Media Language Learning with AI**.

The project investigates whether AI-generated mnemonic materials can support beginner foreign-language vocabulary learning, with a particular focus on **visual keyword mnemonics**. The core idea is that a learner may remember a new foreign word more effectively when it is linked to a familiar English sound cue and a clear visual scene that reinforces the true meaning. The final mnemonics produced and used in the experiment was produced by ChatGPT-5 with DALL·E 3.

The project began with exploratory work on mnemonic theory, keyword-method literature, and prompt-based generation across multiple languages and models. Following this exploration, the final controlled experiment focused on **Polish vocabulary** in order to produce a more interpretable and controlled study.

## Research question
Can AI-generated mnemonic materials help learners remember and retain beginner foreign-language vocabulary more effectively than simpler study formats such as explanation-only support or word-translation exposure alone?

## Project summary
This project explored whether large language models and image-generation systems can be used to create useful mnemonic aids for vocabulary learning.

Early work focused on:
- reviewing prior literature on the keyword mnemonic method
- identifying common features of successful mnemonic strategies
- testing prompt-based mnemonic generation across Polish, Spanish, and Mandarin
- comparing the usefulness and clarity of outputs from different AI systems

The final experiment narrowed the scope to **Polish** and tested 10 beginner-friendly vocabulary items under three learning conditions:
1. image + mnemonic explanation
2. explanation only
3. word-translation only

Participants were assigned to counterbalanced groups so that each word appeared in each condition across the study design. The study included an immediate recall test, a delayed recall test, and qualitative feedback on the generated materials.

## Repository structure

### `report/`
Contains the final dissertation and report-related materials.

### `prompts/`
Contains the main prompts used to generate and refine mnemonic materials.

### `final-experiment/stimuli/`
Contains the 10 final Polish mnemonic images used in the evaluated experiment, along with a list of the associated vocabulary items and mnemonic explanations.

### `final-experiment/data/`
Contains anonymised participant response data, cleaned data files, and any supporting scoring sheets used in the analysis.

### `final-experiment/results/`
Contains summaries of the immediate and delayed results, along with short interpretations of the findings.

### `criteria/`
Contains the quality criteria used to judge whether an AI-generated mnemonic image was acceptable, clear, and educationally useful.

### `exploratory-generation/`
Contains the non-chosen mnemonics generated during the exploratory stage.

## Final vocabulary set
The final experiment used the following Polish words:

- dom — house
- kot — cat
- okno — window
- pies — dog
- ser — cheese
- zima — winter
- sklep — shop/store
- stary — old
- torba — bag
- ptak — bird

## Main finding
The project found that AI can generate mnemonic materials that are educationally promising, but quality control is essential. Weak mnemonic images can confuse the learner or make the sound cue more memorable than the true meaning. In the final study, the strongest support appeared in the **image + explanation** condition, especially when compared against weaker support conditions, although the results were not strong enough to claim a definitive advantage in every case. The project therefore argues that AI-generated mnemonic learning materials can be useful, but only when they are carefully filtered and evaluated against clear criteria.

## Data and privacy
All participant data included in this repository has been anonymised. No personally identifying participant information is included.

## Author
Jenny Song  
Final Year Project  
University College Dublin

## Supervisor
Professor Tony Veale
