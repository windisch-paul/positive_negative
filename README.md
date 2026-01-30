# Introduction
Data and code associated with the manuscript "Large Language Models for Supporting Clear Writing and Detecting Spin in Randomized Controlled Trials in Oncology".

# Data
Each trial is a row in the csv file. For each trial there are the follwing columns:
- __Unnamed: 0__: Index column
- __doi__: DOI of the publication
- __journal__: Journal that the publication was published in 
- __date__: Date of the publication
- __title__: Title of the publication
- __abstract__: Full abstract of the publication
- __abstract_introduction__: Introduction of the abstract
- __abstract_methods__: Methods of the abstract
 __abstract_results__: Results of the abstract
- __abstract_conclusions__: Conclusion of the abstract
- __Annotation_accept__: The final annotation by the human annotators
- __Annotation_disagreement__: 1 if there was agreement that had to be resolved between the annotators, 0 if there was no disagreement
- __Disagreement_reason__: Reason for the disagreement if there was one
- __gpt35turbo_temp100_conclusion_response_raw__: Response by GPT 3.5 Turbo when provided only with the conclusion of the abstract
- __gpt4o_temp100_conclusion_response_raw__: Response by GPT 4o when provided only with the conclusion of the abstract
- __o1_temp100_conclusion_response_raw__: Response by o1 when provided only with the conclusion of the abstract
- __gpt35turbo_temp100_methods_conclusion_response_raw__: Response by GPT 3.5 Turbo when provided only with the methods and conclusion of the abstract
- __gpt4o_temp100_methods_conclusion_response_raw__: Response by GPT 4o when provided only with the methods and conclusion of the abstract
- __o1_temp100_methods_conclusion_response_raw__: Response by o1 when provided only with the methods and conclusion of the abstract
- __gpt35turbo_temp100_methods_results_conclusion_response_raw__: Response by GPT 3.5 Turbo when provided only with the results, methods, and conclusion of the abstract
- __gpt4o_temp100_methods_results_conclusion_response_raw__: Response by GPT 4o when provided only with the results, methods, and conclusion of the abstract
- __o1_temp100_methods_results_conclusion_response_raw__: Response by o1 when provided only with the results, methods, and conclusion of the abstract
- __gpt35turbo_temp100_title_abstract_response_raw__: Response by GPT 3.5 Turbo when provided with the title and abstract
- __gpt4o_temp100_title_abstract_response_raw__: Response by GPT 4o when provided with the title and abstract
- __o1_temp100_title_abstract_response_raw__: Response by o1 when provided with the title and abstract
