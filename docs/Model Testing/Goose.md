# GPT-Neo 125m
- Enkel voor continue text generation, niet conversation? 

## Voor student asks feedback full:

- Token indices sequence length is longer than the specified maximum sequence length for this model (3539 > 2048). Running this sequence through the model will result in indexing errors
Truncation was not explicitly activated but `max_length` is provided a specific value, please use `truncation=True` to explicitly truncate examples to max length. Defaulting to 'longest_first' truncation strategy. If you encode pairs of sequences (GLUE-style) with the tokenizer you can select this strategy more precisely by providing a specific strategy to `truncation`.
Setting `pad_token_id` to `eos_token_id`:50256 for open-end generation.


## Voor teacher create template, result is:

the world's resources.

The world's resources are the resources of the earth.

The world's resources are the resources of the earth.

The world's resources are the resources of the earth.

The world's
## Settings
- check hier settings: 1130
https://happytransformer.com/text-generation/settings/
- sommige zijn beter voor creativity, enz ok 1132
	
## Met args nrepeat 2: 1129
	
  - Introduction
 - Body
 + Introduction

- sommige zijn beter voor creativity, enz 
## Met top k sampling:
I want you to give me a solution one by one, and each time I'll give feedback to that solution. I'll say wether the solution is good or bad. After that, please send your next solution.
## Kan ook ding trainen...
https://happytransformer.com/learning-parameters/
Enige dat nodig is is een file met de tekst, niks anders... 
`happy_gen.train("train.txt")`
`from happytransformer import GENTrainArgs`

# GPT Neo 1.5B
Google collab met T4 GPU
## Voor student asks feedback full:
Same:
Token indices sequence length is longer than the specified maximum sequence length for this model (3539 > 2048). Running this sequence through the model will result in indexing errors
Truncation was not explicitly activated but `max_length` is provided a specific value, please use `truncation=True` to explicitly truncate examples to max length. Defaulting to 'longest_first' truncation strategy. If you encode pairs of sequences (GLUE-style) with the tokenizer you can select this strategy more precisely by providing a specific strategy to `truncation`.
Setting `pad_token_id` to `eos_token_id`:50256 for open-end generation.


## Voor teacher create template, result is:

I hope this helps you. Please feel free to ask me any questions you may have.



Thank you for your time.



Best regards,

Dr.

Dr.

Dr.

Dr


## Settings
## Met args nrepeat 2: 
If you have any questions, feel free to ask me. 
## Met top k sampling:
How to write a paper:

1. Choose an organism/species of your choice. This could be a species you're familiar with or one that interests you.

2. Research: Conduct research on your chosen organism, focusing


# GPT Neo 2.7B
Google collab met T4 GPU
## Voor student asks feedback full:
Same:
Token indices sequence length is longer than the specified maximum sequence length for this model (3539 > 2048). Running this sequence through the model will result in indexing errors
Truncation was not explicitly activated but `max_length` is provided a specific value, please use `truncation=True` to explicitly truncate examples to max length. Defaulting to 'longest_first' truncation strategy. If you encode pairs of sequences (GLUE-style) with the tokenizer you can select this strategy more precisely by providing a specific strategy to `truncation`.
Setting `pad_token_id` to `eos_token_id`:50256 for open-end generation.


## Voor teacher create template, result is:

I hope this helps you. Please feel free to ask me any questions you may have.



Thank you for your time.



Best regards,

Dr.

Dr.

Dr.

Dr


## Settings
## Met args nrepeat 2: 
If you have any questions, feel free to ask me. 
## Met top k sampling:
How to write a paper:

1. Choose an organism/species of your choice. This could be a species you're familiar with or one that interests you.

2. Research: Conduct research on your chosen organism, focusing


