# FineTuning_of_LLMs

[Hugging Face Hub](https://huggingface.co/docs/hub/index)
The Hugging Face Hub is a platform with over `350k models`, `75k datasets`, and `150k demo apps (Spaces)`, all open source and publicly available, in an online platform where people can easily collaborate and build ML together. The Hub works as a central place where anyone can explore, experiment, collaborate, and build technology with Machine Learning.

The idea in this project is to take a pre-trained model (base model) from Hugging Face, and then fine-tune it with an augmented source dataset which contain medical terms so the final chat model to be able to answer specific medical questions.

**Pre-trained model:**
[aboonaji/llama2finetune-v2](https://huggingface.co/aboonaji/llama2finetune-v2)


**Source(Instruction) dataset:**
[(gamino/wiki_medical_terms)](https://huggingface.co/datasets/gamino/wiki_medical_terms)
This dataset contains over 6,000 medical terms and their wikipedia text. It is intended to be used on a downstream task that requires medical terms and their wikipedia explanation.


**Formated datasets:**

[aboonaji/wiki_medical_terms_llam2_format](https://huggingface.co/datasets/aboonaji/wiki_medical_terms_llam2_format)

[mlabonne/guanaco-llama2](https://huggingface.co/datasets/mlabonne/guanaco-llama2)

[emre/llama-2-instruct-121k-code](https://huggingface.co/datasets/emre/llama-2-instruct-121k-code)
