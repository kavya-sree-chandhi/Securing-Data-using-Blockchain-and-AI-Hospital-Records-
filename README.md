# AI Blockchain Electronic Health Records Management System


## Introduction

Data is the input for various artificial intelligence (AI) algorithms to mine valuable features, yet data in Internet is scattered everywhere and controlled by different stakeholders who cannot believe in each other, and usage of the data in complex cyberspace is difficult to authorize or to validate. As a result, it is very difficult to enable data sharing in cyberspace for the real big data, as well as a real powerful AI

## Purpose of the Project

Now a days all service providers such as online social networks or cloud storage will store some type of users data and they can sale that data to other organization for their own benefits and user has no control on his data as that data is saved on third party servers. To overcome from above issue I have described a concept called Private Data Centres (PDC) with Blockchain and AI technique to provide security to user’s data. 

## Scope :

In this technique 3 functions will work which describe below:
### Blockchain: 

Blockchain-based data sharing with ownership guarantee, which enables trusted data sharing in the large-scale environment to form real big data. In this technique users can define access control which means which user has permission to access data and which user cannot access data and Blockchain object will be generate on that access data and allow only those users to access data which has permissions.

### Artificial Intelligence: 

AI-based secure computing platform to produce more intelligent security rules, which helps to construct a more trusted cyberspace. AI work similar to human brain and responsible to execute logic to check whether requesting user has permission to access shared data.

### Rewards: 

In this technique all users who is sharing the data will earn rewards point upon any user access his data. trusted value-exchange mechanism for purchasing security service, providing a way for participants to gain economic rewards when giving out their data or service, which promotes the data sharing and thus achieves better performance of AI.

## Existing System vs Proposed System

### Existing System

In existing systems, lack of ability to effectively manage data makes it very difficult for an individual to control the potential risks associated with the collected data. For example, once the data has been collected by a third party, the insufficiency of access to this data hinders an individual to understand or manage the risks related to the collected data from him. Meanwhile, the absence of immutable recording for the usage of data increases the risks to abuse them.

### Proposed System

In this project, we propose the SecNet, which is a new networking paradigm focusing on secure data storing, sharing and computing instead of communicating. SecNet provides data ownership guaranteeing with the help of blockchain technologies, and AI-based secure computing platform as well as blockchain-based incentive mechanism, offering paradigm and incentives for data merging and more powerful AI to nally achieve better network security. 

## Software Requirement

 The software requirements are description of features and functionalities of the target system. Requirements convey the expectations of users from the software product. The requirements can be obvious or hidden, known or unknown, expected or unexpected from client’s point of view.
• Operating system : Windows 7 or above
• Coding Language : Python 3.7.2
• Front-End : Django
• Data Base : MySQL 5.6 

## Hardware Requirement

To be used efficiently, all computer software needs certain hardware components or other software resources to be present on a computer. These prerequisites are known as system requirements and are often used as a guideline as opposed to an absolute rule.
• Processor : Pentium –IV 1.1 GHz.
• Hard Disk : 40 GB.
• RAM : 4GB

## System Architecture

A system architecture is the conceptual model that defines the structure, behavior, and more views of a system. An architecture description is a formal description and representation of a system, organized in a way that supports reasoning about the structures and behaviors of the system. SecNet is build as an architecture for a more secure cyberspace, by integrating three key components:
1) Blockchain-based data sharing with ownership guarantee.
2) AI-based secure computing platform based on big data to produce intelligent and dynamic security rules.
3) Trust value exchange mechanism for purchasing security services.

<img width="730" height="289" alt="image" src="https://github.com/user-attachments/assets/8e0314e1-e0bf-4f53-ad55-08fa20fafc86" />

## Conclusion
In order to leverage AI and blockchain to fit the problem of abusing data, as well as empower AI with the help of blockchain for trusted data management in trust-less environment, we propose the SecNet, which is a new networking paradigm focusing on secure data storing, sharing and computing instead of communicating. SecNet provides data ownership guaranteeing with the help of blockchain technologies, and AI-based secure computing platform as well as blockchain-based incentive mechanism, offering paradigm and incentives for data merging and more powerful AI to finally achieve better network security. 

## How to run

### Tools required:
* VS Code Editor <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi8qoOwh67qAhX9xjgGHU1BCs4QjBAwAXoECAUQAg&url=https%3A%2F%2Fcode.visualstudio.com%2Fdownload&usg=AOvVaw11fc5fOXYIyxQh75jYLjXg">(Refer this for installation)</a>
* IBM Blockchain Platform extension on VS code <a href="https://marketplace.visualstudio.com/items?itemName=IBMBlockchain.ibm-blockchain-platform">(Refer this for installation)</a>

* Docker Desktop <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjvrbKEh67qAhUzzTgGHXwuB_sQFjACegQIDBAG&url=https%3A%2F%2Fdocs.docker.com%2Fdocker-for-windows%2Finstall%2F&usg=AOvVaw2zo9suoRfAYuT_3irhySPG">(Refer this for installation)</a>


### Installation of used Libraries
~~~
apt-get install python-software-properties
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash –
apt-get install nodejs

npm install -g @vue/cli
npm install axios
npm install formidable

sudo apt install python3
pip install glob
pip install docx2txt
pip install networkx
pip install sklearn
pip install re
pip install nltk
pip install unicodedata
pip install pattern3
~~~

### Steps to run

1. Git Clone this repository to your system
```
git clone https://github.com/yashverma9/AI-Blockchain-Electronic-Health-Records-Management-System
```

2. Start Docker Desktop on your system

3. In the terminal navigate to the repository directory
```
cd AI-Blockchain-Electronic-Health-Records-Management-System
```
4. Open VS Code in the same directory
```
code .
```

5. Open the IBM Blockchain Platform extension. Start a new fabric runtime using default template of 2 ORG, 2CA. Package the contract folder using the 'PACKAGE OPEN PROJECT' option. Now install and instantiate the smart contract on the peers. Export the connection profile to server folder and the wallets as well. <a href="https://developer.ibm.com/tutorials/ibm-blockchain-platform-vscode-smart-contract/">(Refer this for more detailed steps)</a>

6. Open two terminals simultaneously in VS Code.

7. In the 1st terminal start the server side
```
cd web-app/server
npm install
npm start
```

8. In the 2nd terminal start the client side
```
cd web-app/client
npm install
npm run serve
```

9. Your application is running, go to the link specified to open it!


## Implementation Demo : 

### 1. Home Page
<br>
<p align="center">
  <img width="829" height="427" alt="image" src="https://github.com/user-attachments/assets/523cb847-e504-4db2-bd96-e86d83f0629e" />
</p>
<br>
In above screen click on ‘New Patient Register Here’ link to get below screen.

### 2. Patient Home
<br>
<p align="center">
  <img width="821" height="323" alt="image" src="https://github.com/user-attachments/assets/03dd02f8-5f99-4ee0-abd4-a9c0e7d506c6" />
</p>
<br>
In above screen I am adding patient disease details and selecting ‘Hospital1’ to share my data and if you want to share with two hospitals then hold ‘CTRL’ key and select both hospitals to give permission. Now press ‘Create’ button to create profile.

<br>
<p align="center">
  <img width="787" height="484" alt="image" src="https://github.com/user-attachments/assets/d0076e29-094d-4879-bd26-a4b12846a838" />
</p>
<br>
In above screen one patient is created with patient ID 1 and now Hospital 1 can login and search and access this patient data as patient has given permission to Hospital1.


### 3. Hospital Login
<br>
<p align="center">
  <img width="788" height="400" alt="image" src="https://github.com/user-attachments/assets/318bfb9c-96ac-4506-846c-2364d2951164" />
</p>
<br>
In above screen to login as Hospital1 click on ‘Hospital’ link to get above screen. Use ‘Hospital1’ as username and ‘Hospital1’ as password to login as Hospital1 and use Hospital2 to login as Hospital2. After login will get below screen.

<br>
<p align="center">
  <img width="789" height="483" alt="image" src="https://github.com/user-attachments/assets/018a73ae-315f-4e36-9fdc-788528124af1" />
</p>
<br>
In above screen click on ‘Access Patient Share Data’ link to search for patient details.

### 4. Patient grants permission to the Hospital 1 
<br>
<p align="center">
  <img width="778" height="449" alt="image" src="https://github.com/user-attachments/assets/4fa74fa6-3942-43a2-aea3-8d850adb79c2" />
</p>
<br>
In above screen I want to search for all patients who are suffering from ‘pain’ and then click on ‘Access data’ button to get below screen.

<br>
<p align="center">
  <img width="806" height="489" alt="image" src="https://github.com/user-attachments/assets/b621827c-49cb-4f54-a038-0c4210695298" />
</p>
<br>
In above screen Hospital1 getting details of patient and Hospital2 not having permission so it will not get details. To see this logout and login as ‘Hospital2’

### 5. Hospital 2 cannot view reports
<br>
<p align="center">
  <img width="782" height="492" alt="image" src="https://github.com/user-attachments/assets/3c602907-639e-48f9-a25d-e87d45e62e7a" />
</p>
<br>
In above screen ‘Hospital2’ is login, after login will get below screen

<br>
<p align="center">
  <img width="796" height="506" alt="image" src="https://github.com/user-attachments/assets/0cc14d7b-2860-40b0-a160-f5dcbd21cd5f" />
</p>
<br>
Now click on ‘Access Patient Share Data’ link and search for same pain disease

<br>
<p align="center">
  <img width="807" height="510" alt="image" src="https://github.com/user-attachments/assets/272e1b20-b41b-4357-816f-f26e6af6a695" />
</p>
<br>
For above query will get below result

<br>
<p align="center">
  <img width="802" height="427" alt="image" src="https://github.com/user-attachments/assets/21001149-2a32-43bb-a4d5-61ff06a92631" />
</p>
<br>
In above screen no patient details are showing as Hospital2 not having permission. So block chain allow only those users to access data who has permission. Now logout and login as patient by entering patient id in below screen.

<br>
<p align="center">
  <img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/388a6fb4-59db-41b1-99c8-26670d3fdac9" />
</p>
<br>
