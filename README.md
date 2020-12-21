# TL;DR
Collection of personal experiments around artificial life, lindenmayer systems, formal grammars, fractal generation, and evolutionary algorithms

---

## Setup

### 1) Installing dependencies:

If using venv, create a virtual environment named `venv_linden` using:
`python3 -m venv venv_linden`

Activate the environment: 
`source venv_linden/bin/activate`

Then, install the necessary packages: 
`pip install -r requirements.txt`

### 2) Troubleshooting:

---

## Sources:

* [See here](https://realpython.com/beginners-guide-python-turtle/) for a beginner's tutorial on how to use `Turtle` in Python.  I chose Turtle since it is a pre-installed Python library.

* [See here](https://hackaday.io/project/11721-python-l-system) for an alternative to the Turtle package called *PyGame*.  This should be more familiar to graphics/game programmers but is still low-level enough for beginners.  Note that if your examples aren't running and you are using a recent version of Mac OS X, it might be a problem with the interaction between *pygame* and *virtualenv*. More [details here](https://github.com/pygame/pygame/issues/203#issuecomment-365798598).

* [See here](http://algorithmicbotany.org/papers/abop/abop.pdf) for *The Algorithmic Beauty of Plants* by [Przemyslaw Prusinkiewicz](https://en.wikipedia.org/wiki/Przemys%C5%82aw_Prusinkiewicz) (director of the Computer Graphics group studying Fibonacci numbers and modeling using grammars) and [Aristid Lindenmayer](https://en.wikipedia.org/wiki/Aristid_Lindenmayer) (a theoretical biologist studying sequence generators). This textbook is based off Lindenmayer's original notes discusssing the theory and practice of Lindenmayer (L-)Systems for modeling plant growth.

* [See here] for my sequence of articles on Lindenmayer Systems from the perspectives of theoretical biology, artificial life, physics, mathematics, computation, linguistics, and philosophy.


