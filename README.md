# Node-RED Watson Assistant Demo
The goal of this demo is to build a chatbot with IBM Watson Assistant and Node-RED. The script is based on the videos [How to setup the Node-RED Starter Kit on IBM Cloud?](https://www.youtube.com/watch?v=Tk0sHowF3I0) and [Node-RED and Watson Assistant for prototyping in hackathons](https://www.youtube.com/watch?v=SFXUxc4JvFY).
![image](architecture.jpg)
# Prereqs
You need an IBM Cloud account. Please [sign-up](https://cloud.ibm.com/) for the IBM Cloud if not done already. If you are attending a hackathon you might get a special registration URL.

# Install the Node-RED Starter Kit
- go to the [Catalog](https://cloud.ibm.com/catalog) and search for _Node-RED Starter_ or directly to [Create a Cloud Foundry App/Node-RED Starter](https://cloud.ibm.com/catalog/starters/node-red-starter)
- enter a unique App name, e.g. *myuniqueapp...*
- choose a region, organization, and a space or use the defaults
- click on *Create*, der app is now starting
 ![Node-RED runnung](noderedrunning.jpg)
- click on *Visit App URL*
- click *Next*
- enter a Node-RED *Username* and *Password* and click *Next* twice, then click *Finish*
- click on *Go to your Node-RED flow editor* and login
- import [this Node-RED flow](https://raw.githubusercontent.com/gitjps/hackathons_and_node-red/master/node-red-flows/node-flows-hackathon-hacknext-2019.json) via the clipboard 
![Node-RED import](importnoderedflow.jpg)
- there are some error messages because some required nodes are not installed yet, but we don't worry for for now
- 