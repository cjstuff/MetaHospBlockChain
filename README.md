# Medic@Chain

### A blockchain-based Medical Records Management System

### Group no-11
Members:
1. Aman Saxena(2021H1030120H)
2. Chirag Jain(2021H1030072H)
3. Manas Srivastava(2021H1030078H)
4. Sahitya Ratan(2021H1030100H)

Folder: BITSF452_A3_11.zip
> Module: 
* app -> app.js

Today, doctors & health professionals are limited in the level of care they can provide because due to inability to view your complete, accurate health records. The proposed solution is a blockchain network created by the Health Department, who registers the doctors in this network. The doctors can publish patients medical records safely on blockchain network.


## System Requirements

1. Operating System : Ubuntu 16.04
2. System RAM : 4GB or Above

## Step by step instructions for installing / setting up the application for use

**Step 1:** Download the repostory using the command:  
```
 Git Clone "https://gitlab.com/ced_b3_projects/ced-b3-g10.git"
 ```
**Step 2:** Install the dependecies using the command: 
```
 npm Install  
 ```
**Step 3:** Use the following command to compile smart contract:  
```
 truffle compile  
 ```
**Step 4:** Do the following steps to connect to the Ganache Ethereum Workspace chain:  
```
 open Ganache
 Create New Workspace
 Enter port no: 7545
 Network Id: 5177
 Start the workspace
```
**Step 5:** Use the following command to deploy the smart contract to the connected chain: 
```
 truffle migrate  
 ```
**Step 6:** Run the dapp using the command  
```
 npm start  
```
## Execution Flow:

**Step 7:** Login as admin to register the doctors. Admin has the privilege to register or delist the doctors.

**Step 8:** Only registered doctors can add health records of patients. The patient registration will be done at this point of time.

**Step 9:** Only registered patients can access the patient login portal. The registered patients can view their health records history. Also the patients can view the health records w.r.t respective doctors.

**Step 10:** Only patients has the privilege to grant access to doctor, so that the doctor can view the respective patients health records for a particular period. The patients can revoke the access given to doctor at any point of time.

**Step 11:** Registered doctors can view patient health records only when access to doctor is given by patient.

END
