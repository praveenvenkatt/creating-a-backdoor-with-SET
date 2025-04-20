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

![Screenshot 2024-11-02 114302](https://github.com/user-attachments/assets/6818fcdc-ac12-4cb6-b5d3-bff31ddd8bc6)

sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2024-11-02 114509](https://github.com/user-attachments/assets/c765fde1-efbb-40cb-822d-97fe00f0c3c9)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2024-11-02 114636](https://github.com/user-attachments/assets/b839bbfb-4304-4b89-a24f-7e3c7b5f37a0)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2024-11-02 114659](https://github.com/user-attachments/assets/86dbb68b-49d9-4d2c-b604-f7109b26f5e4)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2024-11-02 114752](https://github.com/user-attachments/assets/ed293357-6151-4006-ba8a-3b6bea0a6fd8)

It shows the following screen in which the option Google can be selected:

![Screenshot 2024-11-02 114817](https://github.com/user-attachments/assets/02a15720-822d-4ca4-82b0-8026efb0a06e)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-11-02 114905](https://github.com/user-attachments/assets/3a43d288-3254-4b26-8ea5-e3ed0a035a21)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![WhatsApp Image 2024-11-02 at 13 42 12_0864af96](https://github.com/user-attachments/assets/12377443-0167-4960-b60a-b4a764dd010d)

SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/6bc122bd-7651-437a-be18-a06b790eb797)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
