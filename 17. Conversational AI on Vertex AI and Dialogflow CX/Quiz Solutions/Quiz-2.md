>Read the text prompt below and answer the following question. What information would the highlighted $conversation placeholder parse into the prompt? Your goal is to summarize a given conversation between a Human and an AI. Conversation: $conversation{USER:"Human:" AGENT:"AI:"}Human: $last-user-utterance A concise summary of the conversation in 1 or 2 sentences is:
```
The conversation between the agent and the user, excluding the very last user utterance.
```
>When configuring a Generator there are some controls that can be used to customize the behavior of the generative responses. What are the controls available to you to customize the generative AI responses? (Select two options)
```
Text Prompt
```
```
LLM parameters, such as Temperature, Top P and Top K
```
>What is the correct syntax for a Generator’s output parameter?
```
$request.generative
```
>Which two language models can a Generator use to generate code? (Select two options)
```
code-bison
```
```
text-bison
```
>Generators have a particular set of capabilities that can be utilized by a Dialogflow CX virtual agent in a customer conversation. What are two capabilities of Generators? (Select two options)
```
Sentiment analysis of customer responses
```
```
Conversation Summarization
```
>With generators, you can make a prompt contextual by marking words as placeholders by adding a $ before the word. These placeholders usually hold a position in the prompt that will be substituted for user input data at runtime. What session parameter can you associate with the $text prompt placeholder?
```
Any of the session parameters identified in the Intents
```