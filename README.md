# reverse-string
Still a n00b; here is my successful attempt to reverse a string!

#print a prompt for user
print("Hey, type in a word so we can reverse it!")
#use a while loop to cycle through an 'input' prompt
while True:
    #create the variable 'user_word' to store user input
    user_word = input("go ahead and type a word here: ")
    #if statement with 'isalpha()' method that tests if a variable is characterized by letters y/n
    if user_word.isalpha():
        #create variable where the str(user_word) is stored
        #use the [::-1] slicer method to reverse user input
        reversed_result = str(user_word[::-1])
        print(reversed_result)
    elif:
        print("Yikes, try typing in letters...no numbers!!!")
        continue
    else:
        user_word = input("or just type 'quit' if you don't want to play")
        if user_word == "quit":
            else:
                continue
        break
