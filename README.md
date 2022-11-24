Creating smart contracts in solidity

Build a smart contract of the marketplace in which we have two roles.
The client (role 1) needs to get some home service done, and the tasker (role 2) who completes a task
and gets paid for it. You are to add the following functionalities in smart contact.
• Introducing two parties to an Ethereum smart contract.
• Enabling a client to transfer money to a smart contract.
• Allowing a smart contract to transfer money to a tasker.
Task2
In this task, you are going to design a smart contract for HR by which he can send employees' salaries.
• There are four employees to whom we need to send the profit
• Employee1, Employee2, Employee3, and Employee4 receive 50, 25, 15, and 10 percent profit,
respectively
• You need to define the three functions: constructor, balance, deposit and a modifier:
o Constructor: It will take the employee's address so that we can deposit salary to each
employee i.e Constructor (adrs1, adrs2, adrs3,adrs4)
o Balance: This function will return the employee's balance
o Deposit: Calculate the profit for each employee according to their percentage, send the
profit
o Modifier: This function will ensure that the deposit is called from the HR
• You will need to use a different address for each employee, and you can do that under remix VM
(London). Copy three different addresses and when you deploy this contract, pass those addresses
into the constructor
