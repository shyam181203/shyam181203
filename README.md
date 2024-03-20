import turtle as t

# Set up the canvas
t.setup(600, 600)
t.setpos(0, -250)
t.pensize(8)
t.fillcolor('yellow')
t.begin_fill()
t.pencolor('blue')
t.circle(250)
t.end_fill()

# Draw the letters 'CSK'
t.pensize(12)
t.pencolor('blue')

# Letter 'C'
t.up()
t.setpos(-100, 0)
t.down()
t.setheading(90)
t.forward(200)
t.right(90)
t.forward(100)
t.circle(-100, 180)
t.forward(100)

# Letter 'S'
t.up()
t.setpos(50, 0)
t.down()
t.setheading(90)
t.forward(200)
t.left(90)
t.forward(100)
t.circle(100, 180)
t.forward(100)

# Letter 'K'
t.up()
t.setpos(200, 0)
t.down()
t.setheading(90)
t.forward(200)
t.right(135)
t.forward(140)
t.backward(140)
t.right(90)
t.forward(140)

# Hide the turtle and end the program
t.hideturtle()
t.done()
