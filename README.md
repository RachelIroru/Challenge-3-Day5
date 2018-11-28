# Challenge-3-Day5
Creating a bank account
import sysconfig
class Rachel_account(object): 
    
    def __init__(self):
        self.balance=()
        self.active = True
        
    def open_account(self,Surname,Firstname):
        self.name=Surname,Firstname
        return self.name   
    
    def deposit(self,amount):
        self.balance += amount
        return self.balance

    def withdraw(self,amount):
        if amount > self.balance:
            raise RuntimeError('Check your account balance.')
        self.balance -= amount
        return self.balance
    def close_account(self):
        result=self.active
        return result

