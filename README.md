# password-validater
password= input("Enter your password:")
if len(password)>=8:
    print("strong")
elif len(password)<8:
        print('"Weak!". Try to include atleast 8 characters and containing numbers and symbols.')
