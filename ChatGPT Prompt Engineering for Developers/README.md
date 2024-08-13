# ChatGPT Prompt Engineering for Developers

## Introduction

#### Two Types of Large Language Models (LLM)
1. Base LLM
2. Instruction tuned LLM

`Base LLM` - Predicts next word based on text training data

`Instruction tuned LLM` - Tries to follow instructions

Fine-tune on instructions and good attempts at following those instructions.

RLHF: Reinforcement Learning with Human Feedback
Helpful, Honest and Harmless

## Guidelines

#### Principles and Tactics to interact with ChatGPT model.

Principles

1. To write clean and specific instructions. 
    Clear != Short

    Tactic 1. Use delimiters
    
    ```
    Triple quotes: ''' ''',
    Triple backticks: ``` ```,
    Tripal dashes: ---,
    Angel brackets: < >,
    XML tags: <tag></tag>
    ```

    Tactic 2. Ask for structured output
    HTML, JSON

    Tactic 3. Check weather conditions are satisfied
    Check assumptions required to do the task.

    Tactic 4. Few-shot prompting
    Give successful exaxmples of completing tasks
    Then ask model to perform the task.

2. Give the model to think.

    Tactic 1. Specify the steps to complete the task.
     
     ```
     Step 1: ...
     Step 2: ...
     ...
     Step N: ...
     ```
    
    Tactic 2. Instruct the model to work out it's own solution before rushing to a conclusion.

#### Model Limitations

Hallucination
Makes statements that sound plausible
but are not true

Reducing Hallucination:
First find relevant information,
then answer the question based on the relevant information.

## Iterative

#### Iterative Prompt Development

```
Idea --> Implementation(Code/Data) Prompt --> Experimental Results --> Error Analysis --> Idea (Repeat)
```

#### Prompt Guidelines
- Be clear and specific
- Analyze why result does not give desired output
- Refine the idea and the prompt
- Repeat

#### Iterative Processing
- Try something
- Analyze where the result does not give what you want
- Clarify instructions, give more time to think
- Refine prompts with a batch of examples

## Summarizing

Add the statement or condition to summarize the response.

## Inferring

## Transforming

## Exxpanding

## Chatbot

## Conclusion