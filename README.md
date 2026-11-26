# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT


<img width="945" height="905" alt="image" src="https://github.com/user-attachments/assets/b7ba9340-da40-414a-b087-d8ff261e5c6b" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="600" height="245" alt="image" src="https://github.com/user-attachments/assets/517ebb67-dd6d-4708-ae1e-d358da4f44e6" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="870" height="721" alt="image" src="https://github.com/user-attachments/assets/2b0a6b15-1630-47a1-8cfe-1078c7244562" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="776" height="265" alt="image" src="https://github.com/user-attachments/assets/dec824cb-612f-44c7-8934-5eb577d20bd9" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="777" height="466" alt="image" src="https://github.com/user-attachments/assets/c219018c-251f-4cda-b38f-cab2a7fafd79" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="770" height="481" alt="image" src="https://github.com/user-attachments/assets/4a16c721-dc9b-4610-8c07-da7b1283cae8" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="778" height="122" alt="image" src="https://github.com/user-attachments/assets/7f7952e6-6dd2-45e8-8e96-c7f09b1b4efe" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="775" height="457" alt="image" src="https://github.com/user-attachments/assets/a0919e9d-2910-40bf-b71f-3361d8fce056" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="773" height="342" alt="image" src="https://github.com/user-attachments/assets/d7a3983c-ab07-452f-8de4-9e35ab84254d" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="835" height="363" alt="image" src="https://github.com/user-attachments/assets/999179cd-6c7d-4def-85c5-13499f7cae3a" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
