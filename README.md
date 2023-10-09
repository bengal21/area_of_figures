# AreaCalculationSergey 0.0

## What is this?

The module allows you to calculate areas of different figures.

## Installing
```
pip install AreaCalculationSergey
```
## Quick Guide

```
from AreaCalculationSergey import area


instance = area.AreaCalc
instance.area_of_circle(radius)
```

There are three functions:

## area_of_circle(radius, round_result=2) - allows you to calculate area of a circle, using only radius.

## area_of_triangle(side1, side2, side3, round_result=2) - allows you to calculate area of a triangle, using three sides of triangle.

Also you can add additional argument to round the result, by default is 2.

## right_triangle(side1, side2, side3) - allows you to know whether triangle is right or not.

## How to add new metod

```
def area_rectangle(side1, side2, round_result=2):
    return side1 * side2


instance = AreaCalc()
instance.area_rectangle = area_rectangle
instance.area_rectangle(5, 4)
```

---


