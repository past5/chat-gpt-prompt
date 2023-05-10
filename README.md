# chat-gpt-prompt
This repository contains Python scripts of prompt examples taken from Isa Fulford and Andrew Ng fantastic [ChatGPT Prompt Engineering Course](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/).  The course is a must for everyone to effectively work with AI prompt engineering.  The course is free for a limited time.  All credit for these scripts goes to Deeplearning.ai.

## Guidelines for Prompting
### Prompt Principle 1 - Write Clear and Specific Instructions
1. Use delimiters to differentiate different parts of the input (ticks, quotes, tags)
2. Ask for structured output (HTML, JSON)
3. Ask the model to check whether the conditions are satisfied.  Check assumptions required to do the tasks.
4. Few shot prompting - give successful examples of completing tasks, then ask model to perform the task

### Prompt Principle 2 - Give the model time to think
“If a model given a task that’s too complex to do in a short amount of time and small amount of words, it will likely make a guess that is incorrect”

1. Specify the steps required to complete the tasks
2. Instruct the model to work out its own solution before rushing to a conclusion

### Hallucinations
Models can make statements that sound plausible but are not true

To reduce hallucinations, first find relevant information, then answer the question based on the relevant information

