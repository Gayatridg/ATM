# ATM
Application
class Bank:
#creating a constructor
   def __init__(self,name,account_number,balance=0:
      self.__name=name
      self.__account_number=account_number
      self.__balance=balance
  #for depositing amount
   def deposit(self,amount):
       self.__balance+=amount
       print("Amount is deposited")
  #for withdrawl
  def withdraw(self,amount):
      if amount<=self.__balance
         self.__balance-=amount
         print("Amount is debited")
      else:
         print(""Insufficient funds")
  def get_balance(self):
       return self.__balanace
  def get__account_info(self):
      if amount<=self.__balance:
         self.withdraw(amount)
         other_account.deposit(amount)
      else:
          print("Insufficient funds")
  
  def get_balance_info(self):
      return f"Account holder:{self.__name}\nAccount number is :{self.account_number}\nBalance:{self.__balance}"
  def get_balance(self):
      return f"Balance is:{self.__balance}"
  
  def get_account_number(self):
      return self.__account_number

class ATM:
    def __init__(self,account):
        self.account=accont

    def show_menu(self):
        print("\n---ATM---")
        print("1. Check Balance")
        print("2. Deposit Money")
        print("3. Withdraw Money")
        print("4. Transfer Monay")
        print("5. View Account Info")
        print("6. Exit")

    def run(self):
       while True:
            self.show_menu()
            choice=input("choose an option:")

            if choice=='1':
                print(f"Your balance is:{self.account.get_balance()})
            elif choice=='2':
                amount=float(input("Enter amount to deposit:"))
                self.account.deposit(amounut)
                print(f"Deposited {amount}.New balance is {self.account.get_balance()}.")
            elif choice=='3':
                amount=float(input("enter amount to withdraw"))
                self.account.withdraw(amount)
                print("f"Withdraw {amount}.New balance is {self.account.get_balance()}.")
            elif choice=='4':
                account_number=input("Enter account number to transfer to:")
                amount=float(input("Enter amount to transfer:"))
                #Simulate finding the other account
                other_account=BankAccouunt("Recipient",account_number)
                self.account.transfer(amount,other_account.transfer(amount,other_account)
                print(f"Transferred {amount} to account {account_number}.New balance is {self.account.get_balance()}.")
            elif choice=='5':
                 print(self.account.get_account_info())
            elif choice=='6':
                 print("Exiting ATM.Have a great day!")
                 break
            else:
                 print("Invalid choice.Please try again.")

        account=BankAccount("Alice","123456",1000)
        atm=ATM(account)
        atm.run()

    
    

    
       
