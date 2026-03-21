# Secure-and-Private-Agentic-AI
A secure, private agentic AI interface. Your data and AI are sandboxed from the internet, and your traffic is either encrypted or off the public internet entirely.

### Goals
Enables individuals, enterprises, friends, community groups etc, to have a private and secure AI environment that they share and build together. The interface and all data reside on a server, which is sandboxed from the internet. The AI can only see the data you have uploaded to your Knowledge Collections. The setup requires many steps, however once completed, you and your users can connect from most types of devices by simply installing one security app and opening a browser. Fully scalable setup - your AWS servers can be upgraded to accomodate more users and bigger LLMs when required.

### Introduction
A lightweight, private and secure agentic AI console  
A client-side (local) browser application using a 70 KB html file  
The instance of Open WebUI on an AWS server requires only 2 vCPUs and 2GB RAM  
Open WebUI and LLM(s) are each located on AWS servers, no local hardware required  
Traffic between your device and AWS server with Open WebUI is via Tailscale (encrypted tunnel)  
The AWS server hosting your Open WebUI has no public ports open  
Traffic between your server and your private LLM on your Endpoint is encrypted or via AWS PrivateLink  
Choose from thousands of different models on Hugging Face and host private LLMs  
Once setup, other users can share your network - add users in Open WebUI and Tailscale  
Use the LLM network and SPAA console across your enterprise - scales easily  
Your LLM costs are managed in your Hugging Face account  
The code is simple, 100% transparent, and is easy to adapt to your personal or professional needs  

### Setup
The setup instructions and the text for the config.file are embedded in the Readme section of the html file. You can read them on the code page, or download and open the html file in a browser and read there. Resources required:  
Hugging Face provides access to free, open source LLMs.  
Open WebUI is an open source, self-hosted AI platform that you setup on an AWS server, and which manages LLM deployment for you (and your users).  
Tailscale is an identity-based connectivity platform that securely connects user devices with the AWS server.  
