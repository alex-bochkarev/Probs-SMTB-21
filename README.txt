             ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                A PRACTICAL INTRO TO PROBABILITY THEORY.

              Alexey Bochkarev (www.bochkarev.io/contact)
             ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


/SMTB-2021. Based on the [course] for ZPSH-2021 (in Russian)/

*Status:*
• _English_ track is over (comments / questions / feedback are still
  very welcome!)
• _Russian_ track starts 2021-07-28.


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

  📔 *Notebook:* [(ipynb)] [(nbviewer)] [(colab)]


[(ipynb)] <./1-probability.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/1-probability.ipynb>

[(colab)]
<https://colab.research.google.com/github/alex-bochkarev/Probs-SMTB-21/blob/main/1-probability.ipynb>


Topic 2: Independence, Tests, and Co.
─────────────────────────────────────

  • Crocodiles and rabbits revised (aka black and white balls).
  • Dependent and Independent events.
  • Conditional probability.
  • COVID test as a random variable. Characterizing tests.

  📔 *Notebook:* [(ipynb)] [(nbviewer)] [(colab)]


[(ipynb)] <./2-independence.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/2-independence.ipynb>

[(colab)]
<https://colab.research.google.com/github/alex-bochkarev/Probs-SMTB-21/blob/main/2-independence.ipynb>


Topic 3: Random Variables: definition, characteristics, and the Bernoulli scheme.
─────────────────────────────────────────────────────────────────────────────────

  • Definition of the random variable.
  • Quick examples: score on dice; an RV with countably many values
    (Poisson)
  • Bernoulli scheme (a "biased" coin) and Binomial distribution
    (counting the number of "Heads").
  • PMF, CDF.

  📔 *Notebook:* [(ipynb)] [(nbviewer)] [(colab)]


[(ipynb)] <./3-random-vars.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/3-random-vars.ipynb>

[(colab)]
<https://colab.research.google.com/github/alex-bochkarev/Probs-SMTB-21/blob/main/3-random-vars.ipynb>


Topic 4: Random Variables: continuous case.
───────────────────────────────────────────

  • Motivation: a random variable that "can be anything"
  • A histogram.
  • PDF, CDF.
  • Examples: uniform, normal random variables. (*)
  • A numerical illustration for Central Limit Theorem. (*)

  (*) which we may or may not cover – didn't work for English track.

  📔 *Notebook:* [(ipynb)] [(nbviewer)] [(colab)]


[(ipynb)] <./4-random-vars-cont.ipynb>

[(nbviewer)]
<https://nbviewer.jupyter.org/github/alex-bochkarev/Probs-SMTB-21/blob/main/4-random-vars-cont.ipynb>

[(colab)]
<https://colab.research.google.com/github/alex-bochkarev/Probs-SMTB-21/blob/main/4-random-vars-cont.ipynb>


Further reading / learning
══════════════════════════

  I am having hard times recommending good literature in English, but:
  • 🌍 *Online:*
    ⁃ there are hardcore (but exciting!) university courses. E.g.,
      [Probability - The Science of Uncertainty and Data] by MiTx
      (edx.org). I think it overlaps to an extent with the [OCW].
    ⁃ Usually, there are surprisingly good wiki articles on specific
      distributions (e.g., [binomial])
  • 📖 *book:* There is a classical book by Sheldon M. Ross
    *"Introduction to Probability Models"*. Pretty long, but
    comprehensive, and definitely might be useful if you want to look up
    something specific.

    Note that a couple of things came up in a discussion during the
    class: [Rosalind] (bioinf + programming) and [CrashCourse] videos.

    Of course, there is also [KhanAcademy] and other numerous online
    courses, videos, and other resources on probability theory, of which
    I am not sure what's really good. If you have a suggestion here –
    please drop me a message!


[Probability - The Science of Uncertainty and Data]
<https://www.edx.org/course/probability-the-science-of-uncertainty-and-data>

[OCW]
<https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/>

[binomial] <https://en.wikipedia.org/wiki/Binomial_distribution>

[Rosalind] <http://rosalind.info>

[CrashCourse] <https://www.youtube.com/channel/UCX6b17PVsYBQ0ip5gyeme-Q>

[KhanAcademy] <https://www.khanacademy.org/math/statistics-probability>
