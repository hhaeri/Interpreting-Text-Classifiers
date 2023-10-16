# Interpreting Text Classifiers and Benchmarking Explainers

Interpretable AI for text classification is pivotal for establishing transparency and trust in AI systems, especially in fields like healthcare and law where accurate, accountable decisions are critical. Challenges arise due to the complexity of text data and the black-box nature of deep learning models. Techniques such as LIME, SHAP, attention mechanisms, and rule-based models aim to provide explanations for model predictions.

The objective of this study is to use interpretable AI to analyze movie reviews and understand the sentiment behind them. For this project I start with a NLP model developed by Hugging Face🤗 for sentiment analysis. Specifically, I will use twitter-XLM-roBERTa-base pre-trained model which is trained on over 190M tweets and is tuned for sentiment analysis. This NLP model that is trained on millions of tweets that are not necessarily movie reviews. The models extract features such as the presence of certain words or phrases that might indicate a positive or negative opinion and gives you a sentiment of a review based on these features. Using [Ferret XAI](https://pypi.org/project/ferret-xai/), I benchmark the pre-trained model from huggingface and create exaplanators for the text classifier that classifies movie reviews. I use interpretable AI techniques like LIME and SHAP to get an understanding of the most important factors that drive a positive or negative opinion. Besides the conventional methods of analyzing the given prompt, I also tried open ended language models to analyze why the reviews have particular sentiment. I furher benchmarked the different explainers by evaluating their faithfulness and plausibility. 
With this information in hand, the goal is to create a visualization that clearly illustrates the key factors that drive positive or negative opinions about a movie. By using interpretable AI to understand movie reviews, one can make better movie recommendations. 







