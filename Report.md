![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Report | Text Summarizing with ChatGPT



# Introduction

This exercise aimed to explore different prompt variations for summarizing product reviews using OpenAI’s GPT-3.5-Turbo. Three distinct prompts were tested, each with unique constraints and focus areas. The goal was to analyze their effectiveness, identify cases where GPT provided incorrect or misleading responses, and extract key learnings.

Prompt Variations and Results

**1. Standard Summarization with Word Limit**

Prompt: Summarize the review in at most 25 words.

Results: The model effectively condensed the review while maintaining the core message. However, at times, it omitted minor details that might be useful for nuanced understanding.

Strengths:

Efficient and to the point.

Preserved key aspects of the review.

Weaknesses:

Some summaries lacked minor but potentially relevant details.

**2. Extracting Emotional Sentiment**

Prompt: Identify the emotional sentiment (Positive/Neutral/Negative) and provide a brief explanation.

Results: The model mostly classified sentiment correctly but sometimes leaned towards a more positive tone, even when criticisms were present in the review.

Strengths:

Successfully identified sentiment in most cases.

Provided explanations based on textual clues.

Weaknesses:

Occasionally ignored negative sentiments embedded within positive statements.

Some explanations were too generic.

**3. Bias-Free Summarization**

Prompt: Summarize the review without subjective language (e.g., "cute," "amazing") unless explicitly present.

Results: The summaries were generally neutral, but sometimes the model struggled to distinguish between factual statements and implicit opinions within the review.

Strengths:

Reduced unintended bias.

Maintained factual accuracy.

Weaknesses:

Occasionally removed important descriptive details.

Some summaries felt too mechanical and lacked readability.

**Key Learnings**

Prompt specificity significantly impacts output. Minor tweaks in phrasing can lead to substantial differences in summarization quality.

GPT tends to favor positive sentiment. Even when a review contained mixed opinions, the model often emphasized the positive aspects.

Balancing factual accuracy and readability is challenging. A completely neutral summary can sometimes strip away useful context, making it feel less natural.

Using "extract" instead of "summarize" can improve precision. This is particularly useful for targeted information retrieval.

**Conclusion**

Overall, this experiment demonstrated that prompt engineering plays a crucial role in guiding the behavior of AI models. Different approaches can yield varying degrees of accuracy and relevance, and refining prompts based on the desired outcome is key to achieving high-quality responses.



<br>


