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


![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/87c84446-db8b-4dca-8b63-587ed5259566)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/21ec8810-fa57-4c3d-8741-ca2edecd53e1)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/2493ee9e-f8ab-41ea-8f6b-fac65b135f1e)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/08751118-063d-4f5a-b3cd-16528f586783)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/571e91b2-9ee8-4c4e-ac57-98996835c164)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/5d23ee60-06bf-43bc-9ade-8cd190cde66b)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/a3af39be-c471-4ace-9453-ec4a2bb5087e)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/2c4b05f5-c73d-4feb-9b78-6524be5f7241)

SET logs the information regarding the Google credentials:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/a01f479f-d3b8-4612-8f18-02968d037fd1)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Subhikshaa13/creating-a-backdoor-with-SET/assets/118787344/5fa83046-a2ec-4edf-abc6-253b0003f3e1)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
