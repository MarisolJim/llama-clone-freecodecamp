# LLMs
AI designed to work with text
input is text, it is analyzed and predicts the next word
probabilities (based on context) are assigned to possible words
multiple ways to select a word (some examples):
-Greedy sampling -select the most common word (good for one right answer but repetitve when creativity is wanted)
-random sampling- choose word based on prob assigned to it (if "blue" has a 35% prob, it is selected 35% of the time)
Top-k sampling - select from k most probable words, then use wither of the two methods above
Temperature modifies probablities
-high temp = more random ("creative")
-low temp = more deterministic (math appropriate)

LLMs are predicting the next token, not word
model will learn associations to the word (semantic meanings)
Don't actually know how the model learns the semantic meaning
Tokens can be words, sents, characters, emojis...