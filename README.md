Download Link: https://assignmentchef.com/product/solved-cs212-lab-18-create-a-wallet-a-linked-list-of-money
<br>
<span class="kksr-muted">Rate this product</span>

Create a Wallet: a linked list of Money.This lab will form the basis for project 3.Create a new project in Eclipse called Lab18.Import the class WalletMain from Z:Lab18, and look at the code.

For this lab we will need a linked list capable of storing objects of type Money. The easiest way to get this MoneyList class is to import the linked list classes from the Z:Lab16 folder (classes LinkedList and ListNode), then rename them MoneyList and MoneyNode. You can do this manually, or use the refactor as shown in lecture.

You will need to import the Money, Bill, Coin, etc. classes from Lab 17 into your project.

Create a class called Wallet (a skeleton for this class is available in the Z:Lab18 folder.) The Wallet class will use a MoneyList to store all the bills and coins in the wallet. It should also have the following methods:

<ul>

 <li>addToWallet(Money m) which will append a new Money to the contents of the wallet.</li>

 <li>print() which prints the values of all the bills and coins in the wallet (see MoneyMain in Lab 16)</li>

 <li>getValue() which returns a String show the value of what’s in the wallet in “dddd.cc” format.Once these methods are written, run class WalletMain.You may want to save your files on a jump drive or email them to yourself, as they will be part of project 3.</li>