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

If your examples aren't running and you are using a recent version of Mac OS X, it might be a problem with *pygame* and virtualenv. More [details here](https://github.com/pygame/pygame/issues/203#issuecomment-365798598).   

Try this line to install pygame instead: 
`python3 -m pip install -U pygame --user`

It does work if you create a venv with python -m venv however. Instructions if you want to use an virtualenv (some people have trouble with the window losing focus when inside a venv).

```
# create a virtualenv called 'anenv' and use it.
python3 -m virtualenv anenv
. ./anenv/bin/activate

# venvdotapp helps the python be a mac 'app'. So the pygame window can get focus.
python -m pip install venvdotapp
venvdotapp
python -m pip install pygame

# See if pygame works with the oo module, and the aliens example.
python -m pygame.examples.aliens
```

That's just needed on mac if you use virtualenv, not if you install it with --user, or if you use -m venv.

---

## Sources:

For instructions on how to use `Pygame` if you are a python programmer, [see here](https://www.pygame.org/docs/tut/PygameIntro.html).
