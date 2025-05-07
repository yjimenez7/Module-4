# Module-4
Team assignment
# Process user's choice
# Get user input
# Display menu options
def main():
 choice = input("Please select an option:")
        print("1. set alarm")
        print("2. Check account balance")
        print("3. update media information ")
        print("4. check weather")
        print("5. Make a bed")

  if choice == '1':
            print(f"You selected option {choice}:set alarm")
        elif choice == '2':
            print(f"You selected option {choice}: Check account balance, Your current account balance is $80,000.00")
        elif choice == '3':
            print(f"You selected option {choice}: update media information")
        elif choice == '4':
            print(f"You selected option {choice}:check weather")
        elif choice == '5':
            print(f"You selected option {choice}: making the bed ")
        else:
         input("Press Enter the number to continue")
            print("Invalid choice. Please select a number between 1 and 5.")
  
