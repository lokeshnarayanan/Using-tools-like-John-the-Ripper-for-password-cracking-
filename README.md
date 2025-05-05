# Using-tools-like-John-the-Ripper-for-password-cracking

## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
- Create an txt file
  
![image](https://github.com/user-attachments/assets/20d62626-eeb4-4fe5-b2bd-6653e7ceabae)


-  Create a Password-Protected ZIP File
  
![image](https://github.com/user-attachments/assets/b52fe600-7e6b-47ba-a13e-ffc61f653efc)



### OR

zip -e secret.zip file.txt


- Open John-The-Ripper Tool

  ![image](https://github.com/user-attachments/assets/dd06fe5f-9b70-4c0e-8f3f-6d49f96f6dec)


![image](https://github.com/user-attachments/assets/192981b3-83c8-40bf-96b5-7259b09b6098)


- Generate Hash Using zip2john
  
 
![image](https://github.com/user-attachments/assets/76778504-7f2f-412e-abad-408c8049a3bb)



- cat hash.txt

![image](https://github.com/user-attachments/assets/1b2f4aa8-b010-4c32-9077-8bbdd5e25f9d)


![image](https://github.com/user-attachments/assets/b62cabd3-90ac-4806-beb7-1d6a3aa676ce)


## RESULT:
The password hashes were successfully cracked using John the Ripper.
