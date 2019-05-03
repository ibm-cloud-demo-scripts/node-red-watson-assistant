![chatbot](Conversation_service_Blog1200x600.png)

# Node-RED Watson Assistant Demo (draft)

The goal of this demo is to build a chatbot with IBM Watson Assistant and Node-RED. Node-RED is a visual programming and intenet wiring tool which is quite useful for hackathons and prototypes. It connects all the devices with the cloud services, backend systems and external services.
The figure shows a sample architecture.

![image](architecture.jpg)

The script is based on [this tutorial](https://github.com/thomassuedbroecker/hackathons_and_node-red), which also contains some videos. 
# Prereqs
You need an IBM Cloud account. Please [sign-up](https://cloud.ibm.com/) for the IBM Cloud if not done already. If you are attending a hackathon you might get a special registration URL.

# Install the Node-RED Starter Kit
- go to the [Catalog](https://cloud.ibm.com/catalog) and search for _Node-RED Starter_ or directly to [Create a Cloud Foundry App/Node-RED Starter](https://cloud.ibm.com/catalog/starters/node-red-starter)
- enter a unique App name, e.g. *myuniqueapp...*
- choose a region, organization, and a space or use the defaults
- click on *Create*, der app is now starting

 ![Node-RED running](noderedrunning.jpg)
- click on *Visit App URL*
- click *Next*
- enter a Node-RED *Username* and *Password* and click *Next* twice, then click *Finish*
- click on *Go to your Node-RED flow editor* and login
- import [this Node-RED flow](https://raw.githubusercontent.com/gitjps/hackathons_and_node-red/master/node-red-flows/node-flows-hackathon-hacknext-2019.json) via the clipboard 

![Node-RED import](importnoderedflow.jpg)
- there are some error messages because some required nodes are not installed yet, but we don't worry for for now
- the sample code is now imported into several Node-RED flow which can be selected by clicking of the tabs
- click on the red *Deploy* button to deploy and run all flows
