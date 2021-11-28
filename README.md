# CREDIT-CARD-BANKING-SYSTEM-GUI
THIS PROJECT IS BASICALLY A BANK MANAGMENT SYSTEM WHICH IS DIFFERENT FROM OTHER BANK MANAGMENT SYSTEMS. HERE, WE ARE DOING SEVERAL THINGS. IN THIS A MAIN MENU WILL BE THERE WHICH CONSIST OF

1.NEW ACCOUNT 

2.SEARCH ACCOUNT 
    
3.DISPLAY ALL ACCOUNTS(SORTED BY LAST CREATED)  
    
4.DISPLAY ALL ACCOUNTS(SORTED BY ACCOUNT CREATED  
    
5.VALIDATE A CREDIT CARD NUMBER .
   
FOR VALIDATING A CREDIT CARD NUMBER, WE ARE USING LUHN ALGORITHM. FOR EACH AND EVERY MENU WE DID CODING USING DIFFERENT ALGORITHMS SUCH AS MERGE SORT ,QUICK SORT,LUHN ALGORITHM.

INTRODUCTION:
Credit cards are the most frequently used payment method, accounting for about 95% of all online transactions

With increasing credit card use on the Internet comes a dramatic increase in credit card fraud. Typing errors are one of the most common errors that occur when a user attempts to retype his/her credit card number.

An example is when the “8” key is hit instead of “7.” A general credit card number consists of an industry ID or major industry identifier (MII) (one digit), issuer ID (5 digits), account number (9 digits), and checksum (one digit).

MasterCard has 16 digits and its IIN starts with 5,
 
Visa card has 16 digits with an IIN that starts with 4, 

American express cards has 16 digits with an IIN starts with 37
![image](https://user-images.githubusercontent.com/84842286/143763614-cd37cc7d-e177-4f53-9567-3aa01fb8b91d.png)

SOFTWARE REQUIREMENTS:
1.     Install Qt Framework
2.     Install MinGW C++ Compiler
How to run:
•For Windows OS:
O Click on the build button to build the application
O Click on the run button to run the application.
Libraries Used:Various Qt Libraries are used: 
<QApplication> : The QApplication class manages the GUI application's control flow and main settings
<QSplashScreen> : The QSplashScreen widget provides a splash screen that can be shown during application startup.
<QMovie> : The QMovie class is a convenience class for playing movies.
<QLayout> : The QLayout class is the base class of geometry managers.
 <QStyle> : The QStyle class is an abstract base class that encapsulates the look and feel of a GUI.
<QFile> : The QFile class provides an interface for reading from and writing to files.
Minimum Hardware Requirments:
4GB Disk Space
Windows OS
4GB RAM
![image](https://user-images.githubusercontent.com/84842286/143763637-ef96a2e0-bde3-4d48-8d2c-dc63acc4adb7.png)

LUHN ALGORITHM:  
  
  1.The Luhn algorithm (MOD 10) is the first line of defense in many e-commerce sites.

 2.It is used to validate a variety of identification numbers, such as MasterCard and Visa card numbers.
 
3.It was designed to protect companies and consumers against accidental errors and typing errors
![image](https://user-images.githubusercontent.com/84842286/143763658-c4f8c35b-d8a6-476e-b6b1-250f73acd801.png)
  
  
  PSUEDO-CODE:
  
  
Function checkLuhn(string CC) {
int nDigits := length(CC)
  int sum := integer(CC[nDigits-1])
  int parity := nDigits modulus 2
  for i from 0 to nDigits – 2 {
  int digit := integer(CC[i])
  if i modulus 2 = parity
  digit := digit × 2
  if digit > 9
  digit := digit – 9
  sum := sum + digit
  }
  return (sum modulus 10) = 0}
![image](https://user-images.githubusercontent.com/84842286/143763673-70d3e237-d2cd-4907-8156-bf6904875129.png)
  
  
  
  

