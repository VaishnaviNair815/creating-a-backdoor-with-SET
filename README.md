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
<img width="1114" height="757" alt="Screenshot 2025-11-13 082434" src="https://github.com/user-attachments/assets/2b5698ed-113f-4944-b38e-8accd398949b" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="733" height="262" alt="image" src="https://github.com/user-attachments/assets/1fffab95-87a2-48e6-a0e7-2c6f25554ef6" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="964" height="287" alt="Screenshot 2025-11-13 082600" src="https://github.com/user-attachments/assets/4ce03864-15a3-42db-92b3-c4fa96f6cf88" />

<img width="1113" height="210" alt="Screenshot 2025-11-13 082725" src="https://github.com/user-attachments/assets/6f469a3b-cb98-4078-bc43-5b5834ea82fc" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1099" height="205" alt="Screenshot 2025-11-13 082926" src="https://github.com/user-attachments/assets/7f1f9848-3273-442c-a38c-2fb8fb302ef1" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="870" height="400" alt="Screenshot 2025-11-13 083013" src="https://github.com/user-attachments/assets/84101910-647d-4afe-b3c5-e58d151a33ca" />




It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="592" height="241" alt="Screenshot 2025-11-17 000403" src="https://github.com/user-attachments/assets/8dab75f9-0cbe-4487-9329-3b6ba6058c4b" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="1263" height="177" alt="image" src="https://github.com/user-attachments/assets/4b7bee17-bc78-4026-a815-8e5081381d9f" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="969" height="522" alt="Screenshot 2025-11-13 083710" src="https://github.com/user-attachments/assets/488c6375-722f-4b6b-9a6c-67070d8aac57" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1250" height="438" alt="Screenshot 2025-11-13 090229" src="https://github.com/user-attachments/assets/89c244b1-b33d-47a0-84e4-4e75a9b86de3" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
