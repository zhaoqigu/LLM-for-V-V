# LLM-for-V-V
Artificts for paper "LLMs for Formal Verification & Validation".

# ------------------------------------

few_shot_example foler provide examples of a structured process to train ChatGPT using a few-shot method, enabling it to reliably generate NuSMV code from Umple models. By providing training templates, ChatGPT learns to map Umple syntax to NuSMV code format, allowing consistent code generation for new models.

Related Experinment

prompt.txt -- provided to chatgpt as prompt.

training_data.json -- file contains examples which are mapping of source model (Umple) to target model (SMV: input language to NuSMV2).

respond.txt -- chatgpt generated SMV model.

# ------------------------------------

This repository also showcases a process for incremental development using ChatGPT to iteratively generate more advanced NuSMV code. By leveraging previously generated NuSMV results as additional few-shot templates, users can incrementally define new behaviors and progressively refine their system.

prompt.txt -- provided to chatgpt as prompt.

training_data.txt -- contains mapping of source (original Umple model) to target model (previously generated SMV code).

output.txt -- chatgpt generated SMV model with incrementally added new behaviors and constrains correctly.

