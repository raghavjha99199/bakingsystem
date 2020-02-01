# bankingsystem
banking system through 
class Bank_Account:
def__init__(self):
self.balance=0
print("hello!! welecome deposit and withdrawing machine")
            #function to deposit amount
def deposit(self):
amount=float(input("neter amount want to deposit :"))
self.balance+=amount
print("\n amount want to deposit",amount)
            #function to withdraw the amount
def withdraw(self):
amount=foat(input("enter amount to be draw"))
if self.balance>=amount
self.balance-=amount
                print("\n you withdraw:",amount)
                else:
                    print("\n insuuficient balance")
                    #fuction to dispaly amount
def display(self):
print("\n Net avilable balance=",self.balance)
s=Bank_Account()
s.deposit()
s.withdraw()
                        #calling function with class object
s.display()
