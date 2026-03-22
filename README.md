# Secure-and-Private-Agentic-AI
A secure, private agentic AI interface. Your data and AI are sandboxed from the internet, and your traffic is either encrypted or off the public internet entirely.

## Description
Enables individuals, enterprises, friends, community groups etc, to have a private and secure AI environment that they share and build together. The interface and all data reside on a server, which is sandboxed from the internet. The AI can only see the data you have uploaded to your Knowledge Collections. Once set up, you and your users can connect to your AIs from most types of devices by simply installing one security app (Tailscale) and opening a browser. A sample agent setup of 5 agents is demonstrated, however you can have as many or as few agents as you wish, using different specialised LLMs, Knowledge, skills and tools. Simply modify the 70 KB html file and the config.js file to create/edit/delete agents, or upload the html file to your coder agent and ask the LLM to modify it for you with any features you wish.

## Introduction
A lightweight, private and secure agentic AI console.  
A client-side (local) browser application using a 70 KB html file.  
The instance of Open WebUI on an AWS server requires only 2 vCPUs and 2GB RAM.  
Open WebUI and LLM(s) are each located on AWS servers, no local hardware required.  
Traffic between your device and AWS server with Open WebUI is via Tailscale (encrypted tunnel).  
The AWS server hosting your Open WebUI has no public ports open.  
Traffic between your server and your private LLM on your Endpoint is encrypted or via AWS PrivateLink.  
Choose from thousands of different models on Hugging Face and host private LLMs.  
Once setup, other users can share your network - add users in Open WebUI and Tailscale.  
Use the LLM network and SPAA console across your enterprise - scales easily.  
Your LLM costs are managed in your Hugging Face account.  
Minimise LLM costs by using different LLMs for different complexity tasks, and token management (counters and triggers).  
The code is simple, 100% transparent, and is easy to adapt to your personal or professional needs.  

## Setup
The setup instructions and the text for the config.file are embedded in the Readme section of the html file. You can read them on the html code page, or download and open the 70 KB html file in a browser and read there. For peace of mind, before you open the html file you can upload the html file to an AI and ask: do a security assessment of this AI agent interface, including data security and malicious content.  
Resources required:  
Hugging Face provides access to free, open source LLMs. You can get a free account to get started, and will need to upgrade to a paid account for the full setup.  
Open WebUI is an open source, self-hosted AI platform that you setup on an AWS server, and which manages LLM deployment for you (and your users).  
Tailscale is an identity-based connectivity platform that securely connects user devices with the AWS server.  
AWS Private Link sends traffic between your two AWS servers via private IP addresses on the AWS network, such that your traffic never traverses the public internet.  

## Screenshots  
You can simply download the 70 KB html file and open it in a browser to see it, however it wont function until you setup your config.js file (Setup Step 4).  
Below is a screenshot of the AI interface with 5 example agents, and the drop down box for the Coder agent.  
<br>
<img width="1239" height="719" alt="SPAA1" src="https://github.com/user-attachments/assets/77280684-d9c2-41d3-bb75-b721d0796356" />  
  
<img width="922" height="864" alt="SPAA2" src="https://github.com/user-attachments/assets/133e5adb-eff4-4d48-b504-ffe344461c60" />
