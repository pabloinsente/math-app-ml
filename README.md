# Essential Mathematics for Applied Machine Learning and Data Science

## What is this?

A collection of interactive tutorials about essential mathematics for applied machine learning and data science.

## How are you doing this?

As a learning resource with the following characteristics:

- Open
- Free
- Interactive (Jupyter Notebooks and blogpost formats)
- Visual
- Python-based
- Math with code, i.e., exemplifying mathematical concepts with Python.

## Is this for me?

Maybe. I have no formal mathematical training beyond high school, so I'm writing this from that perspective. This entails the following:

1. I use a narrative style, like a conversation with myself or a dear friend who I'm trying to help to understand something.
2. I try to explain every bit of notation and to "translate" math expression into natural language. 
3. I use visual explanations and analogies as much as possible.
4. Almost zero proofs.

## What are the prerequisites?

This is a tricky question. I'd like to say "NONE! Only your enthusiasm!" but I would be lying. That being said, my best guess is: *solid high school math*. Now, from where I come from, math education is pretty bad, therefore is unclear what *solid* means for people from different parts of the world. From my experience writing this I'd say:

1. Algebra
2. Pre-calculus
3. A bit of trigonometry
4. Basic notions of probability and sets

## What contents do you cover?

1. Linear Algebra ![progress](https://progress-bar.dev/80/ "progress")
2. Calculus (Differential, Integral, and Vector Calculus) ![progress](https://progress-bar.dev/0/ "progress")
3. Probability and Statistics ![progress](https://progress-bar.dev/0/ "progress")
4. Information Theory (maybe)
5. Optimization (maybe)

Points (4) and (5) are maybes, not because they aren't important, but because my time availability.

## How do I use this?

You have three options:

### My blog

Read the tutorials in [my blog](https://pabloinsente.github.io/).

### Remotely

With mybinder, by clicking the icon -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pabloinsente/math-app-ml/master)

This will build a docker image of the repo that runs on the cloud. Beware that it may take 2-3 minutes to be ready. Note the mybinder link may be behind a few updates.

Then navigate to the `notebooks` directory and access to the tutorial.

### Locally

To obtain the files locally, run this in the command line:

```
git clone https://github.com/pabloinsente/math-app-ml.git
```

To set up your system, you need python 3.6.x. It is recommended to use a virtual environment before installing the dependencies. To do this, navigate into the cloned repository in the console by:

```
cd math-app-ml
```
Note that you may need to change the path to cd into the directory.

Then run this inside that directory to create the virtual environment:

```
python3 -m venv venv
```
And activate your environment by running:

```
source venv/bin/activate
```

Make sure to have the latest pip version:

```
pip install --upgrade pip
```

Install dependencies by running:

```
pip install -r requirements.txt
```

To run the notebooks, navigate to the `notebooks` directory and launch Jupyter Lab as:

```
jupyter lab 
```

## Who are you and why are you doing this?

I'm PhD student in Psychology at UW-Madison. I'm from Santiago, Chile. I'm doing this for a couple of reasons:

1. Because teaching (or creating educational content) is the best way to learn *for me*. I've TA multiple courses over the years, and as a result became convinced the person learns the most after each class is the instructor, not the students.
2. Because I like to do things that other people can use, even if is just a small number of individuals. Particularly if those individuals are people like me, that sometimes do not have the money to pay for books or courses.
3. Because is a way to show potential employees that I know "things", even math, which is something most people don't believe given my lack of formal training.
