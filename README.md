# Python-import-turtle-Advance-Art-112
Create python use import turtle graphics code
from turtle import*
from colorsys import*
title("Satyam Shorrf")
setup(width=50, height=650)
tracer(2)
bgcolor('black')
pensize(3)
h=0.5


for i in range(250):
    c = hsv_to_rgb(h,1,1)
    h+=0.003
    pencolor(c)
    left(30)
    right(120)
    circle(100-i,60)
    forward(10)
    left(140)
    right(120)
    goto(0,0)
    fd(70)
    circle(30,80)
    fd(70)
    left(30)
    right(20)
    forward(10)
    h+=1/3
done() 

