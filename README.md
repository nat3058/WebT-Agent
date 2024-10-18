# WebT-Agent
Using Vision and Large Language Models to reason about and intelligently traverse websites

TODO:
- Include memory in chat (need to modify the request json to accumulate prev request data)
- Create a state machine and encode the states as prompts
     - then code up this state machine
- decompose problems into smaller chunks that can be acted upon
- figure out how to utilize Vision and LLMs together, using diff models for prompts that the model is best suited for
     - Vision: check and maintain state, convert visual info into understandable language
     - LLM: do the logical thinking and reasoning
