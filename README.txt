             ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                A PRACTICAL INTRO TO PROBABILITY THEORY.

              Alexey Bochkarev (www.bochkarev.io/contact)
             ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


/SMTB-2021. Based on the [course] for ZPSH-2021 (in Russian)/


[course] <https://github.com/alex-bochkarev/zpsh-21-probs>


[ ∑ ] Summary
═════════════

  *Course point:* A "plain English" / sort-of-intuitive introduction to
   Probability Theory built around numerical examples in Python. We will
   not prove theorems, but this is a _theoretical_ course: the emphasis
   is not on "solving problems", but on understanding the math behind
   random events. What is the /structure/ of randomness? Can we model
   the length of a Facebook post as a random variable? And a sci-fiction
   text as a random sequence of letters?.. We will be looking for a
   balance between the Ivory Tower math and practice of modeling random
   things. In particular, we will try to build the Probability Space
   model, discuss what are random variables, what are some of their
   types and key properties (such as expectation and variance) and
   briefly touch the hypotheses testing.

  *Timeframe:* Four classes, 50 minutes each. No mandatory home
   assignments.

  *Prerequisites:*
  ⁃ Strict: You must like math ☺ 🤷.
  ⁃ Less strict: being comfortable with basic (school) math and having
    curiosity about what might come next. Familiarity with a Python is a
    plus, but willingness to read the code (think: plain English) will
    be necessary.

  *Tech needed:* having a working python (preferably python3)
   installation locally along with Jupyter Notebook will help. However,
   you will be just OK using [Google Colab] (in which case you will need
   just a web browser and a free Google account).

  This repository will be updated with the current materials as the
  course unfolds, so come back to check it out! Tentative course outline
  is as follows.


[Google Colab] <https://colab.research.google.com>


Course outline
══════════════

Topic 1: Model for Random Events
────────────────────────────────

  • Classical definition of probabilities; frequencies.
  • Experiments with dice.
  • Experiments with +crocodiles+ black and while balls.
  • A math model for random events: Probability space. Outcomes, events.
    Notes on Set theory.
  • A couple of numerical illustrations for random events.

  📔 *Notebook:* [(ipynb)] [(nbviewer)]


[(ipynb)] <./1-probability.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/1-probability.ipynb>


Topic 2: Independence, Tests, and Co.
─────────────────────────────────────

  • Crocodiles and rabbits revised (aka black and white balls).
  • Dependent and Independent events.
  • Conditional probability.
  • COVID test as a random variable. Characterizing tests.

  📔 *Notebook:* [(ipynb)] [(nbviewer)]


[(ipynb)] <./2-independence.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/2-independence.ipynb>


👉 Topic 3: Random Variables: definition, characteristics, and the Bernoulli scheme.
────────────────────────────────────────────────────────────────────────────────────

  • Definition of the random variable.
  • Quick examples: score on dice; an RV with countably many values
    (Poisson)
  • Bernoulli scheme (a "biased" coin) and Binomial distribution
    (counting the number of "Heads").
  • PMF, CDF.

  📔 *Notebook:* [(ipynb)] [(nbviewer)]


[(ipynb)] <./3-random-vars.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/3-random-vars.ipynb>


Topic 4: Random Variables: continuous case.
───────────────────────────────────────────

  • Motivation: a random variable that "can be anything"
  • A histogram.
  • PDF, CDF.
  • Examples: uniform, normal random variables.
  • A numerical illustration for Central Limit Theorem.


Topic 🏁: Conclusion
────────────────────

  • Quick summary.
  • On different/popular types of random variables.
  • On random models of random things.
