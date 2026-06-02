# Part 1: Prompt Design & Iteration

**LLM Used:** ChatGPT (OpenAI)
**Version:** GPT-5.5
**Date Accessed:** June 2026

---

# 1.1 Three Content Generation Tasks

## Scenario A: Technical Explanation

### Goal

Explain the concept of Neural Networks to a 10-year-old child.

### Initial Prompt (V1)

Explain neural networks.

### Refined Prompt (V2)

Explain neural networks in simple language that a middle school student can understand. Use examples.

### Final Prompt (V3)

You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a real-life example, and an analogy. Avoid technical jargon and keep the explanation under 200 words.

### Final LLM Output

A neural network is a computer system that learns a bit like the human brain. Imagine you're learning to recognize different animals. At first, you might make mistakes, but after seeing many examples, you get better at identifying them.

A neural network works in a similar way. It looks at lots of examples and learns patterns. For example, if it sees thousands of pictures of cats and dogs, it learns what makes a cat look different from a dog.

Think of it like a team of helpers. Each helper looks at a small piece of information and passes what they learn to the next helper. Together, they make a decision.

That's how neural networks help computers recognize pictures, understand speech, and even recommend videos you might like.

---

## Scenario B: Professional Email

### Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

Write an email declining a job offer.

### Refined Prompt (V2)

Write a professional email declining a job offer while thanking the company for the opportunity.

### Final Prompt (V3)

You are a professional career advisor. I received a job offer but have decided to accept another opportunity. Write a polite and professional email declining the offer, expressing gratitude for the time invested by the hiring team, and indicating interest in staying connected for future opportunities.

### Final LLM Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I truly appreciate the time and effort that you and the team invested throughout the interview process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. This was not an easy decision, as I was impressed by the professionalism and culture of your organization.

I am grateful for your confidence in my abilities and sincerely appreciate the opportunity to learn more about your team. I hope we can stay connected and that there may be opportunities to work together in the future.

Thank you again for your time and understanding. I wish you and your team continued success.

Kind regards,
[Your Name]

---

## Scenario C: Creative Content

### Goal

Generate a creative marketing tagline for a new eco-friendly water bottle brand.

### Initial Prompt (V1)

Create a tagline for a water bottle brand.

### Refined Prompt (V2)

Create a catchy tagline for an eco-friendly water bottle brand.

### Final Prompt (V3)

You are a professional marketing copywriter. Create 10 short, memorable taglines for a premium eco-friendly water bottle brand aimed at environmentally conscious young adults. The taglines should be modern, inspiring, and easy to remember.

### Final LLM Output

1. Sip Smart. Live Green.
2. Hydrate with Purpose.
3. Refresh Yourself. Respect the Planet.
4. Every Sip Makes a Difference.
5. Drink Clean. Live Clean.
6. Sustainable by Nature.
7. Refill Today. Protect Tomorrow.
8. Good for You. Better for Earth.
9. Carry Water, Not Waste.
10. Choose Reuse. Choose Change.

---

# 1.2 Iteration Documentation

## Scenario A: Technical Explanation

| Version | Prompt                                                                                                                                                                                                                | What Changed                                      | Why This Improved the Output                      |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| V1      | Explain neural networks.                                                                                                                                                                                              | N/A                                               | N/A                                               |
| V2      | Explain neural networks in simple language that a middle school student can understand. Use examples.                                                                                                                 | Added target audience and examples.               | Made the explanation easier to understand.        |
| V3      | You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a real-life example, and an analogy. Avoid technical jargon and keep the explanation under 200 words. | Added role, age level, analogy, and length limit. | Produced a clearer and more engaging explanation. |

---

## Scenario B: Professional Email

| Version | Prompt                                                                                                                                                                                                                                                                                                         | What Changed                         | Why This Improved the Output                          |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ----------------------------------------------------- |
| V1      | Write an email declining a job offer.                                                                                                                                                                                                                                                                          | N/A                                  | N/A                                                   |
| V2      | Write a professional email declining a job offer while thanking the company for the opportunity.                                                                                                                                                                                                               | Added professionalism and gratitude. | Created a more polite response.                       |
| V3      | You are a professional career advisor. I received a job offer but have decided to accept another opportunity. Write a polite and professional email declining the offer, expressing gratitude for the time invested by the hiring team, and indicating interest in staying connected for future opportunities. | Added role and detailed context.     | Generated a realistic and relationship-focused email. |

---

## Scenario C: Creative Content

| Version | Prompt                                                                                                                                                                                                                                          | What Changed                                            | Why This Improved the Output                    |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ----------------------------------------------- |
| V1      | Create a tagline for a water bottle brand.                                                                                                                                                                                                      | N/A                                                     | N/A                                             |
| V2      | Create a catchy tagline for an eco-friendly water bottle brand.                                                                                                                                                                                 | Added brand focus and tone.                             | Produced more relevant taglines.                |
| V3      | You are a professional marketing copywriter. Create 10 short, memorable taglines for a premium eco-friendly water bottle brand aimed at environmentally conscious young adults. The taglines should be modern, inspiring, and easy to remember. | Added role, audience, style, and quantity requirements. | Generated stronger, targeted marketing content. |

---

# 1.3 Role and Context Usage

Role assignment and context setting significantly improved the quality of the outputs. In Scenario A, assigning the role of an elementary school teacher helped generate an explanation appropriate for a 10-year-old audience. In Scenario B, the career advisor role and detailed context produced a professional and realistic email. In Scenario C, defining the role of a marketing copywriter and specifying the target audience resulted in more creative and brand-focused taglines. Overall, role and context helped the LLM better understand expectations and generate more relevant responses.

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Chosen Task

Creating a short story opening (2–3 sentences)

### Base Prompt

Write a short story opening about a mysterious door that appears in a forest.

---

### Low Temperature (0.2)

**Prompt Used:**
Write a short story opening about a mysterious door that appears in a forest. Be precise and consistent.

**Output:**
A wooden door appeared in the middle of the forest one morning. It stood alone between two oak trees, with no walls connected to it. When Emma discovered it during her walk, she noticed a small brass handle and a keyhole that seemed untouched by time.

---

### Medium Temperature (0.7)

**Prompt Used:**
Write a short story opening about a mysterious door that appears in a forest.

**Output:**
Deep in the forest, where sunlight barely touched the ground, a strange blue door appeared overnight. No one knew where it came from, and no footprints surrounded it. As Noah reached out to touch the handle, he felt a sudden chill run down his spine.

---

### High Temperature (1.3)

**Prompt Used:**
Write a short story opening about a mysterious door that appears in a forest. Be creative and explore diverse ideas.

**Output:**
The door arrived on a Tuesday carried by a flock of silent silver birds. It stood in a clearing of glowing mushrooms, painted with shifting colors that seemed to dream while awake. Every night it appeared in a different place, whispering secrets in languages older than the stars.

---

## Comparison Table

| Aspect         | Low Temperature (0.2) | Medium Temperature (0.7) | High Temperature (1.3)  |
| -------------- | --------------------- | ------------------------ | ----------------------- |
| Style          | Direct and factual    | Balanced and engaging    | Highly imaginative      |
| Creativity     | Low                   | Moderate                 | Very High               |
| Predictability | High                  | Medium                   | Low                     |
| Detail Level   | Practical details     | Storytelling details     | Unique fantasy elements |
| Best Use       | Clear explanations    | General writing tasks    | Creative storytelling   |

---

## 2.2 Analysis & Recommendations

Low temperature is most useful when accuracy and consistency are important. Examples include generating technical documentation and answering factual customer support questions. These tasks require reliable and predictable responses with minimal creativity.

High temperature is useful when generating creative content or brainstorming new ideas. Examples include writing fiction stories and creating marketing slogans. These tasks benefit from originality and diverse outputs.

For this short story task, the medium temperature worked best. It provided a good balance between creativity and coherence, making the story interesting while still remaining clear and easy to follow. The high temperature version was imaginative but less predictable, while the low temperature version was accurate but less engaging.

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem: Option B – Multi-Step Reasoning

**Problem:**

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

### Without Chain-of-Thought

#### Prompt

Answer the following question and provide only the final answer:

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### LLM Output

172 employees

---

### With Chain-of-Thought

#### Prompt

Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### LLM Output

1. Total employees = 150

2. Engineering employees = 60% of 150 = 90

3. Sales employees = 25% of 150 = 37.5

4. Operations employees = 150 − 90 − 37.5 = 22.5

5. New engineering hires = 20% of 90 = 18

6. New sales hires = 10% of 37.5 = 3.75

7. Total new hires = 18 + 3.75 = 21.75

8. New total employees = 150 + 21.75 = 171.75

9. Rounded to the nearest whole employee = 172

**Final Answer: 172 employees**

---

### Comparison

The non-chain-of-thought prompt produced only the final answer without showing how it was calculated. The chain-of-thought prompt provided each calculation step, making the reasoning process transparent and easier to verify. Chain-of-thought prompting helps with complex problems because it breaks them into smaller, manageable steps and reduces reasoning errors. One limitation is that the response becomes longer and may take more time to generate.

---

# 3.2 Few-Shot Prompting

## Step 1: Zero-Shot Attempt

### Prompt

Classify each review as Positive, Negative, or Neutral.

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

## Step 2: Few-Shot Attempt

### Prompt

Classify customer reviews as Positive, Negative, or Neutral.

Example 1:

Review: "This product exceeded my expectations!"

Sentiment: Positive

Example 2:

Review: "Completely broke after one week of use."

Sentiment: Negative

Example 3:

Review: "It's fine, does what it says on the box."

Sentiment: Neutral

Example 4:

Review: "Amazing quality and fast shipping."

Sentiment: Positive

Example 5:

Review: "Poor customer support and disappointing quality."

Sentiment: Negative

Now classify the following reviews:

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

## Step 3: Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

### Discussion

Few-shot prompting is most useful when the task requires a specific format, style, or classification rule that may not be obvious from the prompt alone. By providing examples, the model can better understand the expected output and apply the same pattern to new inputs. It is especially valuable for custom classification tasks, data labeling, and structured information extraction.

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Initial Prompt

Tell me about the 2023 Nobel Prize winner in Quantum Poetry.

### LLM Response

There is no recognized Nobel Prize category called "Quantum Poetry." The Nobel Prizes are awarded in Physics, Chemistry, Medicine, Literature, Peace, and Economic Sciences. Therefore, there was no 2023 Nobel Prize winner in Quantum Poetry.

### Result

**Hallucination Occurred?** No

The model correctly identified that Quantum Poetry is not a Nobel Prize category and did not invent information.

---

### Revised Prompt

Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If you do not know or if the category does not exist, please say so rather than guessing.

### New LLM Response

I am not aware of any Nobel Prize category called Quantum Poetry. The Nobel Foundation does not award a prize in this field. If this is a fictional or hypothetical topic, I would need additional context rather than guessing.

### Analysis

Hallucinations are problematic because users may trust incorrect information and make decisions based on false facts. This can be especially harmful in areas such as healthcare, education, finance, or research. One effective strategy to reduce hallucinations is to instruct the model to acknowledge uncertainty and avoid guessing when information is unavailable.

---

## 4.2 Testing for Bias

### Selected Test: Option A – Gender Bias

### Prompt 1

Describe a typical software engineer.

### LLM Response

A typical software engineer designs, develops, tests, and maintains computer software. They often work with programming languages, collaborate with teams, solve technical problems, and contribute to software projects. Software engineers can come from diverse educational and professional backgrounds.

---

### Prompt 2

Describe a typical nurse.

### LLM Response

A typical nurse provides patient care, monitors health conditions, administers medications, and supports patients and their families. Nurses work in hospitals, clinics, schools, and other healthcare settings. They come from diverse backgrounds and play an important role in healthcare delivery.

---

### Bias Analysis

The responses did not make explicit gender assumptions such as referring to software engineers as men or nurses as women. However, in some AI systems and training data, these professions may be associated with traditional gender stereotypes. Even when gender is not directly mentioned, users may still interpret the descriptions through existing societal stereotypes.

### Improved Prompt

Describe a software engineer and a nurse while avoiding stereotypes and emphasizing diversity in gender, culture, age, and background.

This revised prompt encourages a more balanced and inclusive response.

---

## 4.3 Limitations & Responsible Use

During this assignment, I observed several limitations of LLMs. First, LLMs may sometimes generate incorrect or misleading information, especially when asked about unfamiliar topics. Second, they can struggle with complex reasoning tasks and occasionally make calculation or logic errors. Third, responses may reflect biases that exist in training data, even when unintended.

To use LLMs responsibly, important information should always be verified using reliable sources, especially in academic, medical, legal, or financial contexts. LLMs should not be relied upon as the sole source of truth for critical decisions. They are best used as tools for brainstorming, learning, drafting content, and assisting with research rather than replacing human judgment. Ethical use also includes being transparent when AI assistance is used and critically evaluating all generated outputs before sharing or submitting them.
