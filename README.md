# Starburst Heart Art

A Python Turtle graphics script that generates a colorful, starburst-textured parametric heart using trigonometric equations.

## Overview

**Starburst Heart Art** (`starburst_heart_art.py`) is a generative art project built with Python's built-in `turtle`, `math`, and `random` modules. Using trigonometric heart equations, this script radiates 300 vibrant, starburst-tipped rays from the center to form a glowing heart against a dark canvas, finishing each endpoint with a multi-colored 8-point starburst pattern.

## Mathematical Formula

Each point $(x, y)$ on the heart boundary is calculated across $300$ evenly spaced angles $\theta \in [-\pi, \pi]$ using:

$$x = 16 \sin^3(\theta) \times 15$$

$$y = \left(13\cos(\theta) - 5\cos(2\theta) - 2\cos(3\theta) - \cos(4\theta)\right) \times 15$$

## How to Run

1. Make sure **Python 3** is installed on your system (`turtle` comes pre-installed with standard Python).
2. Open the `python.work` folder in VS Code or your terminal.
3. Run the script:

```bash
python main.py
