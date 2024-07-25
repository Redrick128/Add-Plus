# Add-Plus

### To set up Add Plus Copy the code put first grab the variable paste it on top of the loop second Grab the if statement and put it below inside the loop
## Python is used withvisual studio

## Variable > AddPlus = input()

## If/Elif
    elif AddPlus == "Add Plus":
      print("Welcome To Add Plus Ver 1.0 ")
      AddPlusN1 = input("N1 Here > ")
      AddPlusN2 = input("N2 Over her > ")

      AddPlusN1 = int(AddPlusN1)
      AddPlusN2 = int(AddPlusN2)

      ConfirmPLus = input("Comfirm Operation Y/N > ")

      if ConfirmPLus == "Y":
        print(AddPlusN1+AddPlusN2)
      elif ConfirmPLus == "N":
        print("Canceling Add Plus")
