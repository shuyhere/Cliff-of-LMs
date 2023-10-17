# cliff-of-LLMs


### Existing attempts to address local optimia 
#### [SELF-TAUGHT OPTIMIZER (STOP): RECURSIVELY SELF-IMPROVING CODE GENERATION](https://arxiv.org/pdf/2310.02304.pdf)



### Large Language Models as Evaluator

#### [Style Over Substance: Evaluation Biases for Large Language Models](https://arxiv.org/abs/2307.03025)
The extent to which humans and LLMs are capable evaluators remains uncertain. This study investigates the behavior of crowd-sourced and expert annotators, as well as LLMs, when comparing outputs from different models.
Curate a dataset of <span style="background:rgba(205, 244, 105, 0.55)">intentionally flawed</span> machine-generated answers. Our findings reveal a concerning bias in the evaluation process, as <span style="background:#ff4d4f">answers with factual errors are rated more favorably than answers that are too short or contained grammatical errors.</span>

Independently evaluating machine-generated text across multiple dimensions, rather than merging all the evaluation aspects into a single score --<span style="background:#d3f8b6"> Multi-Elo Rating System</span>
<span style="background:#d4b106">Significantly enhances the quality of LLM-based evaluations</span>
<span style="background:#ff4d4f">No significant improvement in crowd sourced-based evaluations</span>


<span style="background:#d4b106">All the judges exhibit a bias toward longer texts.</span>
GPT-4 demonstrates the most bias and the expert annotators demonstrate the least bias

Human and LLMs: <span style="background:#ff4d4f">The response of “Several Major Factual Errors” as superior to that of “Correct + Short”</span>

<span style="background:#d4b106">Crowd-sourced annotators lack fact-checking, while experts and LLM judges can fact-check, albeit imperfectly.</span>
<span style="background:#ff4d4f">LLM fails to detect inaccuracies, it often favors flawed outputs over shorter or grammatically imprecise responses.</span>

<span style="background:#d4b106">The order of answers affects the judges’ decisions.</span>

<span style="background:#ff4d4f">Stop Using Crowd-Sourced Annotators!</span>

#### [Benchmarking Cognitive Biases in Large Language Models as Evaluators](https://arxiv.org/abs/2309.17012)
<span style="background:#affad1">COBBLER pipeline</span>
<span style="background:#ff4d4f">LLMs are biased text quality evaluators</span>
<span style="background:#ff4d4f">Machine preferences are misaligned with humans</span>
EGOCENTRIC bias

 Automatic evaluation leaderboards（with LLMs） have a number of limitations, including a preference for long outputs or outputs that are more similar to the evaluators’ generation qualities.
 
Test six different biases to benchmark their evaluation quality and categorize the model biases into two groups:
1. Implicit Biases
2. Induced Biases
![image.png](https://cdn.jsdelivr.net/gh/babytreemi/picgo/img/2023%2F10%2F16%2F20231016144706_14-47-06.png)
