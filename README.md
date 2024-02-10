## benchmark correlations

humans are the quintessential evaluator of llms. the chatbot arena is a great representation of this. but humans are slow and the arena leaderboards have a tough time keeping up with the current pace of this space. judging how well other, automated benchmarks, conform to the arena elo is a great indicator of a valuable benchmark. 

spearman correlation is an excellent choice when judging how well benchmarks conform to human judgment, or more specifically **arena elo**. spearman doesn't assume a linear relationship but rather a monotonic one, captures the relative relationship of the data and handles outliers well.


### eq-bench
eq-bench is a relatively new benchmark that i'm very bullish on. it's extremely cheap to run, doesn't require any strong llm models acting as a judge, and only has 170 questions.

![](/figures/result2.png)

