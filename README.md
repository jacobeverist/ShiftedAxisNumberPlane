# Demo of Manim NumberPlane with yaxis shifted to border

Demonstration of shifting the y-axis to the left-side border of NumberPlane.

We cannot move yaxis directly without screwing up the internal NumberPlane class calculations

Instead, we use a yaxis_shift variable in all calculations and relabel the x-axis ticks

## Prerequisites

Must have manim community installed, at least 0.17.3

```shell
pip install manim
```

## Running demo

Demonstrates creating NumberPlane, plotting a function, and plotting points.

```shell
manim -p shifted_axis_numberplane.py
```

