# palindrome

    import os
    os.system("cls")
    while True : 
        a = input("Enter the number or word you want to check : ")
        b = a[::-1]
        if b == a :
            os.system("cls")
            print("The entered number or word is a palindrome!\n")
        else :
            os.system("cls")
            print("The entered number or word is not a palindrome !\n")
