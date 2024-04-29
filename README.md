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

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/28decd55-dcf3-49ed-893d-647aa8245ff4)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/29caf0ca-ba7c-4c2b-ac99-3839862bf617)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/a8a5ba1b-04de-4cdc-894f-935be3be4c37)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/83abdad9-6c83-4bdc-b64a-040680915caa)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/b997b5b4-0a7a-496f-8116-2c3046faaeec)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/762bf0c2-824e-4f4a-8143-8cc97706cc58)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/d58eebc6-573a-409e-9259-81205fe30204)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/9d9c46bf-10f1-4011-b565-2981c006bbc8)

SET logs the information regarding the Google credentials:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/6524eab4-2740-4665-ad0b-1c5f2b311e3d)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Hariharan-061102/creating-a-backdoor-with-SET/assets/93427270/ef268bf7-2823-4ee7-8642-5226695d9af9)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
