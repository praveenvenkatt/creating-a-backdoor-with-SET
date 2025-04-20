# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212222040121
Name: Praveen V
```
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

![Screenshot 2025-04-20 191957](https://github.com/user-attachments/assets/bb9086b6-6850-413f-ac45-5d416dff2d67)


sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-20 192023](https://github.com/user-attachments/assets/72394cf5-e03c-4b08-8137-ce0e5ad67c3e)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2025-04-20 192046](https://github.com/user-attachments/assets/7f4c074c-f909-47c5-963f-2b007fe3b84c)



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2025-04-20 192133](https://github.com/user-attachments/assets/0566b0fc-dce5-47a8-9c79-c90584f84b3b)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2025-04-20 192154](https://github.com/user-attachments/assets/8ec74a23-89b9-4ebe-a05c-32400a85c437)


It shows the following screen in which the option Google can be selected:

![Screenshot 2025-04-20 192223](https://github.com/user-attachments/assets/4afff78b-2e87-42a2-be96-7e71769ca2a0)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-11-02 114905](https://github.com/user-attachments/assets/3a43d288-3254-4b26-8ea5-e3ed0a035a21)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![Screenshot 2025-04-20 192446](https://github.com/user-attachments/assets/5030f9a6-11c8-4574-9857-d26c01c0b9ed)


SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/6bc122bd-7651-437a-be18-a06b790eb797)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
