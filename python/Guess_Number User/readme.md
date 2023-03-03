: Function:Block of code which only runs when it is called EX: print(f"Yay! The computer guessed your number, {guess}, correctly!")

parameter: Names listed in the the function definition EX:if feedback == "h":
        high = guess - 1
    elif feedback == "l":
         high = guess - 1 

arguments:Imformation passed into functions:("Sorry, guess again. Too low")  
while loops: while guess != random_number:
          guess = int(input(f"Guess a number between 1 and {x}"))
          if guess < random_number:     
               print("Sorry, guess again. Too low") 
          elif guess > random_number:   
               print("Sorry, guess again. Too high") 

    print(f"Yay, congrats. You have guess the number {random_number} correctly")

 conditionals (if/else if/ else):if guess < random_number:  
 Scope:A variable created inside a function belongs to the local scope of that function, and can only be used inside that function.Ex: low = 1
    high = x

 
 random library: Set of methods for random Ex:random_number = random.randint
 Optimization:to find the best solution to a problem out of a large set of possible solutions.I had trouble with indenting which infected most of the code I needed to indent more and move some stuff around to make the code work.