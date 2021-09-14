# RECEIPT-GENERATOR
This is a basic application whih can be used in stores to calculate and generate bill. This application will keep store the numbers user has put and will add them until the user presses "q" on their keyboard. Then the application will print the result as a bill.

print("NAME OF THE SHOP\n")
sum = 0
while(True):
    
    userInput = input("Enter the item name:")
    userInput = input("Enter the item rate:")
    
    if(userInput!='q'):
        sum = sum + int(userInput)
        print(f"Your Order Total so far: {sum}")
        print("___________________________________\n")

    else:
        print(f"Your Bill Total is {sum}.")
        print("*****************************")
        print("Thanks For Shopping with us.")
        print("------------------------------")
        break
        
