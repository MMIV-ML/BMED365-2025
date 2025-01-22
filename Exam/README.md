# Exam Information (BMED365-2025)

This document provides important information about the upcoming exam for the BMED365 course.

## Date and Time
The digital home exam will take place on **Monday March 3rd 2025 09:00-12:00**.

## Location and Preparation
The digital home exam will take place in [Inspera](https://www.inspera.com). Please make sure you are able to login to [UiB/Inspera](https://vurdering.uib.no) at least 15 minutes before the scheduled start time (more details at https://www.uib.no/en/student/125772/preparing-exams). Note: In addition to preparing yourself academically, you must also remember to check that your computer and login are ready to use at the examination. This is your responsibility as a student.

## Exam Format

- The **two hours** digital home exam in BMED365 on Inspera consists of **eight multiple-choice questions**, each with five answer options, where there are two answers being "the most correct". 

- This is followed by **two free-text essay questions**. 

- The eight MCQ questions and the two essay questions are given in both **English** and **Norsk bokmål**. 

- **All aids are allowed** but specify precisely which aids you have had access to and how you used these sources (look-up, search, prompt) in your submitted answers. The exam allows the use of AI to understand and explain medical AI.

- The **topics covered** from the course syllabus (lectures, readings, and assignments) in the MCQ-section and in the two essay questions are among the following: 


  - The equation $y \approx f(\mathbf{X}, \theta)$
  - Image classification, object detection, and image segmentation (semantic segmentation, instance segmentation)
  - Supervised learning, unsupervised learning, semi-supervised learning, self-supervised learning, and reinforcement learning
  - Patient similarity networks (PSNs)
  - Large language models (LLMs), multimodal foundation models; tokens, embeddings, transformers, the concept of prompt engineering and the use of AI-accelerated coding in Python
  - Imaging modalities e.g., MRI, CT, PET, and live cell imaging, imaging mass cytometry (IMC)
  - The role of Python in AI and computational modeling
  - Performance measures of predictive models (e.g., accuracy, precision, recall, F1-score, ROC-AUC, Dice score)
  - The role of AI in experimental biomedicine (wet lab, dry lab, moist lab) and in clinical science (precision medicine, personalized medicine, P4 medicine)
  - Computational modeling of biological systems (e.g., compartment models, ODEs, PDEs, networks, and graphs)
  - Imaging-derived biomarkers and imaging-based parameter estimation
  - Explainable AI, ethical AI, regulations in AI, human-in-the-loop AI
  - Future perspectives and challenges using AI in biomedicine and health (drug discovery, self-driving labs, prompting proteins, patient similarity networks, diagnostic reasoning, and problem-solving)
  


## Grading (Pass or Fail)

- For the 8 **MCQ questions** with 5 answer options each, you will get 3 points for exactly 1 correct answer, 5 points for 2 correct answers, 0 points otherwise.

- For each of the two **essay questions**, a particularly good answer is given 10 points; a particularly bad answer, or no answer, is given 0 points; each essay question counts for 1/6 of the exam.

- The highest possible score on the complete exam is 60 points, the lowest possible score is 0 points.

- We will use the binary grading system with a **tentative threshold** of 30 points for passing the exam: 0-29 points is a fail, 30-60 is a pass (e.g. you will pass if you score at least 5 points on each of the essay questions and has at least one correct answer on each of the 8 MCQ questions; note that this is just an example, **the actual grading and threshold will be set by the course responsible**).<br>

======================================================


### _Side note_ : 

The probability of getting at least 10 points on the MCQ questions **by chance** is non-negligible, i.e. try to solve:

>_In an exam, there are 8 MCQ questions with 5 options each, of which precisely 2 are correct.  You will get 3 points for exactly 1 correct answer, 5 points for 2 correct answers, and 0 points otherwise. What is the probability of getting at least 10 points on the MCQ questions by chance on the exam?_

----

<!--

#### A few MCQ examples and short essay questions from previous **ELMED219** (6 ECTS, targeted at medical students) exams:

<img src=./assets/example_01.png width=500>

-----

<img src=./assets/example_02.png width=500>

-----

<img src=./assets/example_07.png width=500>

-----

<img src=./assets/example_06.png width=500>

-----

<img src=./assets/example_05.png width=500>

-----

<img src=./assets/example_04.png width=500>

---

<img src=./assets/example_03.png width=500>

---

and remember ....

> All aids are permitted during this home exam. However, please specify precisely which aids you have utilized, and how you used these sources (look-up, search, prompt) in your submitted answers. The exam allows the use of AI to understand and explain medical AI. Be sure to get time to answer the essay questions, as points here will help you to pass the exam. 


**Good luck with your preparation!**

---------

## BMED365 v2024 (Norsk)

_For English, see [here](./SENSOR-GUIDANCE.md)_

<img src=./assets/all.png width=500>

<img src=./assets/mcq_01.png width=500>

<img src=./assets/mcq_02.png width=500>

<img src=./assets/mcq_03.png width=500>

<img src=./assets/mcq_04.png width=500>

<img src=./assets/mcq_05.png width=500>

<img src=./assets/mcq_06.png width=500>

<img src=./assets/mcq_07.png width=500>

<img src=./assets/mcq_08.png width=500>

<img src=./assets/txt_01.png width=500>

<img src=./assets/txt_02.png width=500>

<img src=./assets/aid_01.png width=500>

-----

-->

**ChatGPT-o1: Thought about probability of scoring 10 points for 2m 55s**

Imagine that for each of the eight questions you randomly select any subset of the five options (including possibly none or all). Since there are 5 options, each of which can be either chosen or not, there are 2⁵ = 32 equally likely ways of marking each question. Exactly two of the five options are correct.

Let X be the number of correct options you select on a single question. Under random marking (each of the 32 subsets equally likely), one can count:

• P(X = 0) = 1/4  
• P(X = 1) = 1/2  
• P(X = 2) = 1/4  

(This follows from noting there are 2 correct options and 3 incorrect options. Choosing r out of 2 correct and any subset of the 3 incorrect yields 2^3 = 8 subsets for each r, giving 8, 16, and 8 out of the total 32 subsets.)

Scoring rules:
• 3 points if exactly one correct option is selected (X = 1).  
• 5 points if exactly two correct options are selected (X = 2).  
• 0 points otherwise (X = 0).  

Hence, for a single question S (the score from that question) takes values:
S = 0 with probability 1/4, S = 3 with probability 1/2, S = 5 with probability 1/4.

Over eight independent questions, let N₀ be the number of questions scoring 0, N₁ the number scoring 3, and N₂ the number scoring 5. Then N₀ + N₁ + N₂ = 8 and the total score is 3N₁ + 5N₂. We want the probability that the total score is at least 10.

A quicker way is to find the probability that the total score is under 10 and subtract from 1. The only ways for 3N₁ + 5N₂ < 10 are:

1) N₂ = 0 and 3N₁ ≤ 9 ⇒ N₁ ≤ 3.  
2) N₂ = 1 and 3N₁ + 5 ≤ 9 ⇒ 3N₁ ≤ 4 ⇒ N₁ ≤ 1.  
3) N₂ ≥ 2 automatically gives 3N₁ + 5N₂ ≥ 10.

Hence the combinations that fail to reach 10 points are:
• (N₂ = 0, N₁ = 0..3).  
• (N₂ = 1, N₁ = 0..1).

Compute each probability:

(a) N₂ = 0, N₁ = 0..3.  
This means all eight questions were either scored 0 or 3. The probability that exactly N₁ of them yield 3 points is

∑ (from N₁=0 to 3)  (8 choose N₁) (1/2)^(N₁) (1/4)^(8 - N₁).

(b) N₂ = 1, N₁ = 0..1.  
Here one question yields 5 points and N₁ of the remaining seven yield 3 points. The probability is

∑ (from N₁=0 to 1)  [8! / (1!⋅N₁!⋅(7−N₁)!)] (1/4)^1 (1/2)^(N₁) (1/4)^(7 − N₁).

Summing these gives approximately 0.010635..., so the probability that the total score is at least 10 is about

1 − 0.010635... = 0.989364... ≈ 98.94%.

In words, even with completely blind guessing (checking or not checking each option uniformly at random), the chance of scoring at least 10 points on these eight multiple-select questions is roughly **98.94%**. 

Key takeaway: Because the expected score per question is relatively high (E[S] = 0×(1/4) + 3×(1/2) + 5×(1/4) = 2.75), the chance of surpassing 10 points in total (over eight questions) ends up very close to 99%.

----

**Gemini Advanced 2.0 Experimental Advanced**:

Therefore, the probability of getting at least 10 points on the exam by purely guessing is 
approximately **3.873%**.


-----

**Google AI Studio: Gemini 2.0 Flash Thinking Experimental 01-21** (https://aistudio.google.com/prompts/1GWtE8KB4GXwzE4KWouh1mRkLmawdYALw)

Let $P_0 = P(X_i=0) = \frac{3}{10}$, $P_3 = P(X_i=3) = \frac{6}{10}$, $P_5 = P(X_i=5) = \frac{1}{10}$.
We want to find the probability of getting at least 10 points, i.e., $P(S \ge 10)$, where $S = \sum_{i=1}^8 X_i$.
It is easier to calculate $P(S < 10) = P(S=0) + P(S=3) + P(S=5) + P(S=6) + P(S=8) + P(S=9)$.
$P(S=0) = \binom{8}{8} P_0^8 = (\frac{3}{10})^8 \approx 0.00006561$.
$P(S=3) = \binom{8}{1} P_0^7 P_3^1 = 8 (\frac{3}{10})^7 (\frac{6}{10}) \approx 0.00104976$.
$P(S=5) = \binom{8}{1} P_0^7 P_5^1 = 8 (\frac{3}{10})^7 (\frac{1}{10}) \approx 0.00017496$.
$P(S=6) = \binom{8}{2} P_0^6 P_3^2 = 28 (\frac{3}{10})^6 (\frac{6}{10})^2 \approx 0.00734832$.
$P(S=8) = \binom{8}{1, 1, 6} P_0^6 P_3^1 P_5^1 = \frac{8!}{6!1!1!} P_0^6 P_3^1 P_5^1 = 56 (\frac{3}{10})^6 (\frac{6}{10}) (\frac{1}{10}) \approx 0.00244944$.
$P(S=9) = \binom{8}{3} P_0^5 P_3^3 = \binom{8}{5} P_0^5 P_3^3 = 56 (\frac{3}{10})^5 (\frac{6}{10})^3 \approx 0.02939328$.
$P(S < 10) = P(S=0) + P(S=3) + P(S=5) + P(S=6) + P(S=8) + P(S=9) \approx 0.00006561 + 0.00104976 + 0.00017496 + 0.00734832 + 0.00244944 + 0.02939328 = 0.04048137$.
$P(S \ge 10) = 1 - P(S < 10) = 1 - 0.04048137 \approx 0.95951863$.

Final Answer: The final answer is **$\boxed{0.9595}$** (after 80 sec)

-----

**Claude 3.5 Sonnet**:

Therefore, the probability of getting at least 10 points is approximately 0.0884 or about **8.84%**.

-----

**Bearly DeepSeek V3**:


To determine the probability of getting at least 10 points on the MCQ questions by chance, we need to analyze the scoring system and the possible outcomes. 

\### Scoring System: - **Exactly 1 correct answer:** 3 points - **Exactly 2 correct answers:** 5 points - **Otherwise:** 0 points 

\### Problem Breakdown: 1. **Total Questions:** 8 2. **Options per Question:** 5 3. **Correct Answers per Question:** 2 

\### Step 1: Calculate the Probability of Each Outcome per Question For each question, the possible outcomes are: - **Exactly 1 correct answer** - **Exactly 2 correct answers** - **Otherwise (0 or more than 2 correct answers)** 

\#### Probability of Exactly 1 Correct Answer: The number of ways to choose 1 correct answer out of 2 is $$ \binom{2}{1} $$. The number of ways to choose 1 incorrect answer out of 3 is $$ \binom{3}{1} $$. The total number of ways to choose 2 answers out of 5 is $$ \binom{5}{2} $$. So, the probability is: $$ P(\text{1 correct}) = \frac{\binom{2}{1} \cdot \binom{3}{1}}{\binom{5}{2}} = \frac{2 \cdot 3}{10} = \frac{6}{10} = 0.6 $$ 

\#### Probability of Exactly 2 Correct Answers: The number of ways to choose 2 correct answers out of 2 is $$ \binom{2}{2} $$. The number of ways to choose 0 incorrect answers out of 3 is $$ \binom{3}{0} $$. So, the probability is: $$ P(\text{2 correct}) = \frac{\binom{2}{2} \cdot \binom{3}{0}}{\binom{5}{2}} = \frac{1 \cdot 1}{10} = \frac{1}{10} = 0.1 $$ \#### Probability of Otherwise: $$ P(\text{otherwise}) = 1 - P(\text{1 correct}) - P(\text{2 correct}) = 1 - 0.6 - 0.1 = 0.3 $$ 

\### Step 2: Calculate the Total Points for Each Question - **Exactly 1 correct answer:** 3 points - **Exactly 2 correct answers:** 5 points - **Otherwise:** 0 points 

\### Step 3: Calculate the Probability of Getting at Least 10 Points We need to consider all possible combinations of outcomes across the 8 questions that result in a total score of at least 10 points. This is a complex combinatorial problem, but we can simplify it by considering the expected value and variance of the score per question and then using the Central Limit Theorem to approximate the probability. 

\#### Expected Value (Mean) per Question: $$ E = 3 \cdot P(\text{1 correct}) + 5 \cdot P(\text{2 correct}) + 0 \cdot P(\text{otherwise}) = 3 \cdot 0.6 + 5 \cdot 0.1 + 0 \cdot 0.3 = 1.8 + 0.5 + 0 = 2.3 $$ 

\#### Variance per Question: $$ Var = (3 - 2.3)^2 \cdot 0.6 + (5 - 2.3)^2 \cdot 0.1 + (0 - 2.3)^2 \cdot 0.3 = 0.49 \cdot 0.6 + 7.29 \cdot 0.1 + 5.29 \cdot 0.3 = 0.294 + 0.729 + 1.587 = 2.61 $$ 

\#### Total Expected Value and Variance for 8 Questions: $$ E_{\text{total}} = 8 \cdot 2.3 = 18.4 $$ $$ Var_{\text{total}} = 8 \cdot 2.61 = 20.88 $$ $$ \sigma_{\text{total}} = \sqrt{20.88} \approx 4.57 $$ 

\#### Probability of Getting at Least 10 Points: We want to find the probability that the total score is at least 10. Using the normal approximation: $$ P(\text{Score} \geq 10) = P\left(Z \geq \frac{10 - 18.4}{4.57}\right) = P\left(Z \geq -1.84\right) $$ Using standard normal tables or a calculator, we find: $$ P(Z \geq -1.84) \approx 0.9671 $$ 

**Final Answer**: The probability of getting at least 10 points on the MCQ questions by chance is 
approximately **96.71%**.


----

_If you get 5 points on each of the two essay questions, what is the chance you pass the exam at the threshold of 30 points (i.e. score at least 20 points on the MCQ section)?_

---

**ChatGPT-o1: Thought about probability of 20 points for 1m 44s**

To find the probability of scoring at least 20 points by pure chance, note that each of the 8 questions yields one of three possible scores:

• 0 points with probability 1/4,  
• 3 points with probability 1/2,  
• 5 points with probability 1/4.

Let N₂ be the number of questions that yield 5 points, N₁ the number that yield 3 points, and N₀ the number that yield 0 points, with N₂ + N₁ + N₀ = 8. The total score T is then

T = 5N₂ + 3N₁.

We want P(T ≥ 20). Because each question’s outcome is independent, the probability that exactly (N₂, N₁, N₀) occurs is

C(8, N₂) × (1/4)^(N₂) × C(8 − N₂, N₁) × (1/2)^(N₁) × (1/4)^(8 − N₂ − N₁),

where C(a, b) = “a choose b”.

Step 1: Identify all (N₂, N₁) combinations satisfying 5N₂ + 3N₁ ≥ 20.  
You systematically check N₂ = 0, 1, …, 8 and see which N₁ make 5N₂ + 3N₁ ≥ 20 possible (and also keep N₂ + N₁ ≤ 8). The valid pairs (N₂, N₁) turn out to be:

N₂ = 0,  N₁ = 7, 8  
N₂ = 1,  N₁ = 5, 6, 7  
N₂ = 2,  N₁ = 4, 5, 6  
N₂ = 3,  N₁ = 2, 3, 4, 5  
N₂ = 4,  N₁ = 0, 1, 2, 3, 4  
N₂ = 5,  N₁ = 0, 1, 2, 3  
N₂ = 6,  N₁ = 0, 1, 2  
N₂ = 7,  N₁ = 0, 1  
N₂ = 8,  N₁ = 0  

Step 2: Sum the probabilities of all valid (N₂, N₁) pairs.  
Using the fact that p(5 points) = 1/4, p(3 points) = 1/2, p(0 points) = 1/4, one can group the factors to see that each valid (N₂, N₁) term contributes

C(8, N₂) × C(8 − N₂, N₁) × (1/4)^(N₂) × (1/2)^(N₁) × (1/4)^(8 − N₂ − N₁).

A convenient way to handle the (1/4) factors is to note:

(1/4)^(N₂) × (1/4)^(8 − N₂ − N₁) = (1/4)^(8 − N₁)  
and multiply separately by (1/2)^(N₁).  

Summing across all (N₂, N₁) in the list above and simplifying numerically gives approximately **0.696**. In other words, the probability that the total score is at least 20 (when you pick each subset of answers entirely at random) is about **69.6%**.

Summary of key takeaway:  
When answers are chosen blindly, there is roughly a 70% chance of scoring 20 points or more on these eight questions, given that each question awards 0, 3, or 5 points with probabilities 1/4, 1/2, and 1/4, respectively.

----

**Bearly DeepSeek V3**:  Approximately **36.32 %**


----


_In an exam, there are 8 MCQ questions with 5 options each, of which precisely 2 are correct.  You will get 3 points for exactly 1 correct answer, 5 points for 2 correct answers, and 0 points otherwise. Make a python program that calculates and plotsthe probability of getting at least n points on the MCQ questions by chance on the exam, for n=0, 1, ..., 40._

See [mcq-probability-at-least.ipynb](./mcq-probability-at-least.ipynb) for the code.

