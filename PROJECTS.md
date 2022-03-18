<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

import turtle
        turt = turtle.Turtle()
        turt.pencolor("cyan")
        shapes = 60
        angle1 = 6
        sides = 8
        length = 50
        angle2 = 360.0 / sides
        turt.speed(0)
        for x in range(shapes):
            for y in range(sides):
                turt.forward(length)
                turt.right(angle2)
            turt.left(angle1)
        turt.done()

</script>
</head>
</body>
</html>