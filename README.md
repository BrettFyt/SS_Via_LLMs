# SS_Via_LLMs
The files are the source of paper "Sentence Simplification via Large Language Models"(https://arxiv.org/pdf/2302.11957)，which used LLMs for sentences simplification task.

The ChatGPT and GPT3.5 folder stores the outputs for the sentence simplification task using ChatGPT and text-davinci-003 respectively, and the examples for few-shot is also available there. For Portuguese and Spanish, the file naming format is MODEL-NAME_LANGUAGE_ZERO-/FEW-SHOT_REFS_PROMPTS-ID. For English, the file naming format is MODEL-NAME_ZERO-/FEW-SHOT_REFS_PROMPTS-ID.

For the metrics, you can get SARI and FKGL scripts from https://github.com/feralvam/easse. The FRES scripts and SIMPLEXT test sentences are available from the paper "An Unsupervised Method for Building Sentence Simplification Corpora in Multiple Languages" (https://aclanthology.org/2021.findings-emnlp.22/). In addition, you can get the whole Portuguese ASSET set from https://github.com/facebookresearch/muss/tree/main/muss_system_outputs/pt/asset.
