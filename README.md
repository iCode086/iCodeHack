# iCodeHack
SaddaHack

Firstly, hack.html provides an interface to give us a choice to choose between the Transaction function and Upload function. 

The transaction function when deployed, the account currently active becomes the admin. Only the admin can mint money from the system. It would show the account name of the admin account as Minter as well as the current account.
Now, other accounts can send any amount from one account to another and check the balance as well.
The smart contract in this function consists of the mint and transfer functions which allow the transactions to take place along with the event sent to show the transaction details of the transaction made.

Link: https://drive.google.com/file/d/1RCpEo1uqmKU7CtXiV2XodUjW9Ek6gKOv/view?usp=sharing

The upload function if purely built on blockchain and hosted on IPFS. When a person uploads any files into the system, it generates a hash code and on click of submit button converts and posts it onto the browser. The set and get methods are written in the smart contract to enable the write and read functions respectively.
When we see the transactions on ganache we will observe that the set method is repetively used to write because it controls the uploads into the browser and also helps in providing the hash of the file.

Link: https://drive.google.com/file/d/15bEZCwjq4pbm-sB3ytlL_9j3lhDk9559/view?usp=sharing


