# Using-tools-like-John-the-Ripper-for-password-cracking
### NAME : SUSINDHAR K M
### REGISTER NUMBER : 212223040218
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
![image](https://github.com/user-attachments/assets/bcf9e0e3-fd79-4c34-8354-1b8418964c5e)


-  Create a Password-Protected ZIP File 
![image](https://github.com/user-attachments/assets/10b470c4-f66b-4852-9a7f-92f32acb201a)


### OR
```
zip -e secret.zip file.txt
```

- Open John-The-Ripper Tool
- 
![image](https://github.com/user-attachments/assets/4238d521-b03c-42d8-a03e-52aec44898fa)


![image](https://github.com/user-attachments/assets/386c4cbc-adec-4c46-8080-c8755bc2d13b)


- Generate Hash Using zip2john
 
![image](https://github.com/user-attachments/assets/a14ed527-079e-455b-9a65-25562a084405)


- cat hash.txt

![image](https://github.com/user-attachments/assets/9bbb3820-279a-4604-ab82-bf757336c30e)


![image](https://github.com/user-attachments/assets/10c4fe4f-e04d-4d44-829d-036cf0d7f34f)


## RESULT:
The password hashes were successfully cracked using John the Ripper.
