import turtle
import random
import time

# Set up the screen
screen = turtle.Screen()
screen.bgcolor('black')
screen.title('Rock Paper Scissor Shoot!')
screen.setup(width=700, height=500)
screen.tracer(0)

# Add shapes for the game
screen.addshape('rock.gif')
screen.addshape('paper.gif')
screen.addshape('scissors.gif')
screen.addshape('rock_comp.gif')
screen.addshape('paper_comp.gif')
screen.addshape('scissors_comp.gif')

# Set up player choices
rock = turtle.Turtle()
rock.shape('rock.gif')
rock.shapesize(3)
rock.penup()
rock.goto(200, 200)

paper = turtle.Turtle()
paper.shape('paper.gif')
paper.shapesize(3)
paper.penup()
paper.goto(200, 0)

scissors = turtle.Turtle()
scissors.shape('scissors.gif')
scissors.shapesize(3)
scissors.penup()
scissors.goto(200, -200)

# Set up computer choices
rock_comp = turtle.Turtle()
rock_comp.shape('rock_comp.gif')
rock_comp.shapesize(3)
rock_comp.penup()
rock_comp.goto(-200, 200)

paper_comp = turtle.Turtle()
paper_comp.shape('paper_comp.gif')
paper_comp.shapesize(3)
paper_comp.penup()
paper_comp.goto(-200, 0)

scissors_comp = turtle.Turtle()
scissors_comp.shape('scissors_comp.gif')
scissors_comp.shapesize(3)
scissors_comp.penup()
scissors_comp.goto(-200, -200)

# Scores
comp_score = 0
player_score = 0

# Choices lists
computer_choices = ["rock_comp.gif", "paper_comp.gif", "scissors_comp.gif"]
player_choices = ["rock.gif", "paper.gif", "scissors.gif"]

# Decision turtle
dec = turtle.Turtle()
dec.hideturtle()
dec.color('yellow')
dec.penup()
dec.goto(0, 150)

# Display the initial instruction
dec.write('Click on an icon to play!', font=('Verdana', 20, 'bold'), align='center')

# Score display
score = turtle.Turtle()
score.hideturtle()
score.color('white')
score.penup()
score.goto(0, 220)
score.write(f"Player: {player_score} - Computer: {comp_score}", font=('Verdana', 16), align='center')

# Function to update the scores display
def update_scores():
    score.clear()
    score.write(f"Player: {player_score} - Computer: {comp_score}", font=('Verdana', 16), align='center')

# Function to handle the game logic
def gotcha(x, y):
    global comp_score
    global player_score
    
    # Determine player's choice based on the icon clicked
    if rock.distance(x, y) < 50:
        player_choice = 'rock'
    elif paper.distance(x, y) < 50:
        player_choice = 'paper'
    elif scissors.distance(x, y) < 50:
        player_choice = 'scissors'
    else:
        return  # Ignore clicks outside the icons

    # Randomly select computer's choice
    comp_choice = random.choice(computer_choices)
    if comp_choice == 'rock_comp.gif':
        comp_choice_text = 'rock'
    elif comp_choice == 'paper_comp.gif':
        comp_choice_text = 'paper'
    else:
        comp_choice_text = 'scissors'

    # Determine the result
    dec.clear()
    if player_choice == comp_choice_text:
        dec.write("It's a tie!", font=('Verdana', 24), align='center')
    elif (player_choice == 'rock' and comp_choice_text == 'scissors') or \
         (player_choice == 'paper' and comp_choice_text == 'rock') or \
         (player_choice == 'scissors' and comp_choice_text == 'paper'):
        dec.write("You win this round!", font=('Verdana', 24), align='center')
        player_score += 1
    else:
        dec.write("Computer wins this round!", font=('Verdana', 24), align='center')
        comp_score += 1

    # Update the scores display
    update_scores()
    
    # Pause for a second to display the decision
    time.sleep(1)
    
    # Clear decision and ask player to play again
    dec.clear()
    dec.write('Click on an icon to play!', font=('Verdana', 20, 'bold'), align='center')

# Bind the click event to the gotcha function
screen.onclick(gotcha)

# Start the main event loop
turtle.mainloop()
