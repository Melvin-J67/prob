# prob
## Joint Events in Probability

A joint event in probability happens when we are interested in the probability of two or more events occurring together.

In simple terms, it means finding the probability that Event A AND Event B happen at the same time.

The word AND is very important when dealing with joint events.

### 1. Understanding joint events with an example

Imagine you toss a coin and roll a die.

Let:

- Event A = Getting a Head when tossing the coin.
- Event B = Getting an even number when rolling the die.

The possible outcomes of the die are 1, 2, 3, 4, 5, and 6.

The even numbers are 2, 4, and 6.

We want to find the probability of getting a Head AND an even number.

We know:

$$
P(A)=\frac{1}{2}
$$

$$
P(B)=\frac{3}{6}=\frac{1}{2}
$$

Since tossing a coin and rolling a die are independent events, we multiply:

$$
P(A\cap B)=P(A)\times P(B)
$$

$$
=\frac{1}{2}\times\frac{1}{2}
$$

Answer$$
\boxed{P(A\cap B)=\frac{1}{4}}
$$

This means the probability of getting a Head and an even number is 1/4 or 25%.

### 2. The formula for joint events

There are two important situations to understand.

A. Independent events

Two events are independent if the occurrence of one does not affect the occurrence of the other.

Formula:

$$
P(A\cap B)=P(A)\times P(B)
$$

Example: Tossing a coin and rolling a die.

B. Dependent events

Two events are dependent if the occurrence of one affects the probability of the other.

Formula:

$$
P(A\cap B)=P(A)\times P(B|A)
$$

Where:

- $P(A)$ = Probability that event A happens.
- $P(B|A)$ = Probability that event B happens given that A has already happened.

Example:

A bag contains 3 red balls and 2 blue balls. You pick two balls without replacement.

What is the probability of picking a red ball first AND a red ball second?

First pick:

$$
P(A)=\frac{3}{5}
$$

Second pick (only 2 red balls remain out of 4):

$$
P(B|A)=\frac{2}{4}
$$

Therefore:

$$
P(A\cap B)=\frac{3}{5}\times\frac{2}{4}
$$

$$
=\frac{6}{20}=\frac{3}{10}
$$

### 3. Difference between joint events and individual events

| Type | Meaning | Symbol |
| --- | --- | --- |
| Individual event | A happens | $P(A)$ |
| Joint event | A and B happen | $P(A\cap B)$ |
| Conditional event | B happens given A | $P(B\\|A)$ |

Remember:

- AND (∩) means both events happen.
- OR (∪) means at least one of the events happens.
- GIVEN (|) means one event has already occurred.
4. If dependent, multiply the first probability by the conditional probability of the second event.

Would you like me to also explain joint probability tables and how to solve questions using them?
