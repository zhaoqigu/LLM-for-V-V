# LLM-for-V-V
Artificts for paper "Towards Integrating LLMs into Formal Verification and Validation Frameworks".

# ------------------------------------

This repository provide examples of a structured process to train ChatGPT using a few-shot method, enabling it to reliably generate NuSMV code from Umple models. By providing carefully crafted training templates, ChatGPT learns to map Umple syntax to NuSMV code format, allowing consistent code generation for new models.

Objectives
Bridge Syntax Gap: Automate the transformation of Umple models into NuSMV code.
Leverage Few-Shot Learning: Utilize ChatGPT’s ability to generalize patterns and generate reliable outputs using example-based learning.
Efficiency: Reduce manual translation effort and ensure correctness in mapping rules.

# ------------------------------------

This repository also showcases a process for incremental development using ChatGPT to iteratively generate more advanced NuSMV code. By leveraging previously generated NuSMV results as additional few-shot templates, users can incrementally define new behaviors and progressively refine their system.

Objectives
Iterative Refinement: Enable step-by-step enhancement of NuSMV code based on incremental requirements.
Leverage Prior Outputs: Use ChatGPT’s adaptability to incorporate earlier NuSMV results as templates for subsequent refinements.
Automate Behavior Extension: Simplify the process of adding new behaviors or constraints to an existing Umple modle for NuSMV code generation.
