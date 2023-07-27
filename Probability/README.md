# Probability

## Learning Goals

- Describe set theory and its terminology
- Recognize combinatorics
- Describe the fundamentals of probability theory
- Define conditional probability

## Lecture Materials

* [Jupyter Notebook: Probability](Probability-Introduction.ipynb)

## Lesson Plan (1 hour 30 minutes)

### Introduction (5 minutes)

Discuss today's objectives, and situate them for their first Phase 2 lecture!

### Set Theory (5 minutes)

Very light intro about set theory and setting it up to relate to probability theory. Key is to highlight intersections and unions, which can help explain later concepts and formulas, and the notation, which will pop up later.

The python set functions are a nice bonus, but just that - do not need to focus on them, just to highlight that `set` objects in python have their own specific methods which can be useful.

### Combinatorics (10 minutes)

Quick intro to combinatorics. Key is that students should know to ask whether order matters, and whether something is done with or without replacement. There are a few examples for students to work through, but probably shouldn't spend too much time on this so would not break out into breakout rooms.

### Probability Theory (20 minutes)

Disucss random variables, probability in terms of sets, and how to calculate probabilities. Emphasize that students may find the formulas useful, but they should not worry about memorizing them or the names of these rules.

The knowledge check can be run in separate breakout rooms, giving small groups the time to answer these on their own (might want to remove the answers from the notebook if that's the plan) or as one big group.

### Explore in Python (10 minutes)

Introduce the mushrooms dataset, then walk through a few more exercises in python - building up to an example in which two traits are NOT independent, which leads naturally into a discussion of conditional probabilities.

### Conditional Probability (15 minutes)

Discuss conditional probabilities at a high level, including how this changes our calculations. Two more exercises, to showcase that P(A | B) is NOT the same as P(B | A). There's then more discussion on the intuition behind conditional probabilities, making the reduction in sample space more apparent and more visual.

### Total Probability (10 minutes)

Walk through the law of total probability and an example calculation.

### Partitioning Complex Events (10 minutes)

Walk through a further complication, when what's given is more complex than a single facet of information. There's a level up provided at the end of the notebook which allows for further practice with this. 

Likely in this section you as the instructor should run through the first part, proving that P(orange stalk) is not as simple as just adding P(orange stalk below ring) + P(orange stalk above ring) - that double counts the mushrooms which have orange stalks in both places. Then have students find P(edible | orange stalk) either in breakout rooms or in a big group (depending on time).

### Conclusion (5 minutes)

Congratulate them on laying the first block of their foundation of stats knowledge, remind them that it's OK to still be confused at this point.
