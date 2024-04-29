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

## OUTPUT:
![326443843-1a8c3de4-fc7f-4033-8e42-94d0d130354b](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/59b05b0a-6a36-4f24-b75f-36a4b60205b3)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![326443928-6c846b27-4ac2-40df-b48f-80a3b9eafac0](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/bd2039d2-1d10-4fce-acd5-fdb1e0272938)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![326444101-1263bf77-8da2-4a97-b88b-0f0d0e768e0c](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/ae61ed1f-a7f3-46c5-ac7d-353a17f58dc4)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![326444174-131510f9-fc3e-4480-bc6b-36c56551ad5b](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/f335056b-b266-4c83-a80f-5a0476b8ac1b)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![326444262-25a53d1f-f056-42a2-8899-2b315ab258f4](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/c22ef630-2e77-48a0-a186-82677e235c3c)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![326444379-7ffe4da3-78b5-4927-a34b-e25fcc8406e5](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/19c5e5ae-e7c6-487d-b006-e9f61f460a6c)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![326444458-5cff32e6-230c-48a9-891c-1a9d7c9e41ee](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/7fa5fe13-30b6-4f2e-8273-ee7b31df24da)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![326444522-29260581-702c-4dcb-83f0-e4dbb94deea1](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/7050c75c-f156-4b13-aede-489c3f901ab7)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![326444641-8db86ae6-4c70-4e45-a112-fd74b85c03cd](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/098ac012-0e93-4397-a242-7d2351eecc01)

SET logs the information regarding the Google credentials:

## OUTPUT:
![326444716-de35890b-2c51-47bb-bece-a1b880043632](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/27f9e3a9-d8db-4190-b179-b1487f963245)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![326444828-d6937c16-0595-45e7-ba0e-08b63e0f533a](https://github.com/Gopikakarthik/creating-a-backdoor-with-SET/assets/121235427/3f78ba7d-cea2-4402-929e-d6cc84421e41)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

