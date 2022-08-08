# SANITIVISE
### Under development PoC of a medical data-sharing solution with a customisable incentive scheme

<h2>INTRODUCTION</h2>
This repository contains an initial base for the aforementioned project.
The goal of this project is to develop an Ethereum based medical data sharing platform with a customisable incentive scheme, making it more profitable for patients that are willing to participate.
The architecture would consist of two parts : one on-chain running on Ethereum (for its reliability and usability), and one off-chain using the IPFS protocol.
By providing data on the platform, a practitionner or research can buy the said data, and the patient remuneration would increase by a dynamically calculated incentive based on the rarity of the data, and provided by a ETH pool filled little by little with fees coming from the transactions.

<h3>1. Current state of the project</h3>
The current project contains a Ethereum implementation of a file sharing. 
Even though it doesn't contain any form of our customisable incentive solution yet, it allows for a base to work on and to take inspiration from.
The <a href="https://github.com/saren-io/ethereum-data-share">base work</a> was made by user jaykch, with the licences conditions available <a href="https://github.com/jaykch/ethereum-file-share/blob/master/LICENSE">here</a>.

<h3>2. Upcoming work</h3>
Based on the current implementation, we want to incrementially improve it by changing the core logic and adding our desired fonctionalities. 
This project being part of a research, the possibility of adding the said functionalities will depend on criteria such as time, the capacity of the team, etc.
They are listed as follows : 

<h4>2.1 Creation of the patient incentive model</h4>
Based on the research that will be done in the third work package of our proposal, we will adapt the current implementation to support the selected technologies.
This is the most important part of the project in terms of the innovation we are bringing to the field and the one that is going to take the most time during the project.

<h4>2.2 Creation of the validator incentive model</h4>
The patient incentive model serves as a way to motivate patient to share their data by increasing the remuneration they get. 
This particular model is made to make sure the data has a proper format, by allowing a concurrent bot-free reviewing system of the data with another incentive for doing so.

<h4>2.3 Calibration and details</h4>
The two models being done at this point, we want to properly calibrate them and tweak the implementation before going further. As such, that step will mostly consists of modifications on files from the 2.1 and 2.2 chapters (which corresponds to work packages 2 and 3 in our project).

<h4>2.4 Modification and finalisation of the frontend</h4>
As we'll have a base frontend fairly quickly that's probably utilising HTML + JS (with a Truffle box), we want to update it to accomodate for the new functionalities and models that will be created in the meantime. This will serve as the base for some final testing.
