## Directory structure

### January 2024
**919_prev_incorrect_response_repeat_gpt4_response_Jan28_2024.csv** : GPT-4 responses again taken on January 28, 2024 to initial USMLE questions that it answered incorrectly on August 30, 2023

### August 2023
**GPT4_responses_full_data_5072_points.csv** : GPT-4 responses containing both correct and incorrect responses
	
**IncorrectGPT4_Responses_919_points.csv** : Subset of 5072 points, where GPT-4 predicts the wrong option.
	
**final_annotated_multilabel_191_points_strict.csv**: Out of 300 points annotated, we finalize the labels using the "strict" criteria, where we retain labels that are selected by at least two annotators for each data point
	
**final_annotated_multilabel_300_points_relaxed.csv**: Out of 300 points annotated, we finalize the labels using the "relaxed" criteria, where we retain labels that are selected by any annotator for each data point
	
**raw_annotator_level_annotation_data.csv**: For the 300 annotated points, the raw annotator-level output obtained from the Potato annotation platform. This file is process to compute the "strict" and "relaxed" multi-label dataset
