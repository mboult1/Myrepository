import math

def circle_area(radius):
    return math.pi * radius ** 2

def square_area(side_length):
    return side_length ** 2


circle_radius = 2
square_side_length = 3

circle_area_value = circle_area(circle_radius)
square_area_value = square_area(square_side_length)


if circle_area_value > square_area_value:
    result = "The circle has more area."
elif circle_area_value < square_area_value:
    result = "The square has more area."
else:
    result = "The circle and the square have the same area."

circle_area_value, square_area_value, result
