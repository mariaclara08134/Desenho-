import turtle 

turtle.shape("turtle")
turtle.color("black")
turtle.speed(2)

quadrado1 = [(0,0),(16,0),(16,16),(0,16),(0,0)]
quadrado2 = [(32,0),(32,16),(16,16),(16,0)]
triangulo = [(0,0),(0,16),(16,24),(32,16),(0,16),(0,0)]
porta = [(6,0),(10,0),(10,13),(6,13),(6,0)]

def desenha_casa(x:int , y:int , zoom: float) :

    # Desenha os quadrados da casa
    turtle.fillcolor("red")
    turtle.begin_fill()
    turtle.penup()
    turtle.goto(zoom * x , zoom * y)
    turtle.pendown()
   
    for (x,y) in quadrado1:
        turtle.goto(zoom * x , zoom * y)

    turtle.end_fill()

    turtle.fillcolor("red")
    turtle.begin_fill()
    turtle.penup()
    turtle.goto(zoom * x , zoom * y)
    turtle.pendown()

    for (x,y) in quadrado2:
        turtle.goto(zoom * x , zoom * y)

    turtle.end_fill()

    # Desenha o triângulo
    
    turtle.fillcolor("blue")
    turtle.begin_fill()
    turtle.penup()
    turtle.goto(zoom * x , zoom * y)
    turtle.pendown()

    for (x,y) in triangulo:
        turtle.goto(zoom * x , zoom * y)

    turtle.end_fill()

    # Desenha a porta 

    turtle.fillcolor("yellow")
    turtle.begin_fill()
    turtle.penup()
    turtle.goto(zoom * x , zoom * y)
    turtle.pendown()

    for (x,y) in porta:
        turtle.goto(zoom * x , zoom * y)

    turtle.end_fill()

    turtle.fillcolor("yellow")
    turtle.begin_fill()
    turtle.penup()
    turtle.goto(x - 80, y + 140)
    turtle.pendown()
    turtle.circle(20)
    turtle.end_fill()


desenha_casa(x = 50, y = 60 , zoom = 8)
# Algumas linhas e o círculo não foram amplicados ou reduzidos com o zoom
desenha_casa(-50, -50, 5)

turtle.done()
