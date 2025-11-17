# Networks-Final

Instructions
Final Course Project
Task: Complete an implementation of a project involving computer networks. You may complete one from my short list of suggestions, but I am also new to a lot of things that can be done here and may be fun, so feel free to search around and suggest if you find something that can be completed in a couple of weeks! You can team up (up to 2 people per team) for this one!

Submission: Short report that includes the following --

Explanation of the Project:

Begin with a brief overview of the project. Explain what the project aims to achieve and its relevance in the context of computer networks.
Discuss the motivations behind the project. Why would someone want to build or implement this particular network solution? Highlight real-world scenarios where such a system would be valuable (e.g., improving network security, enhancing communication efficiency, it's awesome, etc.).
Breakdown of Your Implementation:

Provide detailed information about how the project was implemented. If it’s a virtual network using VMs, include information like the following:
Network Topology: Describe the layout of the network. How many VMs were used? What roles did they play (e.g., routers, switches, servers)?
Configuration Details: Explain any specific configurations made (IP addresses, subnetting, routing protocols, etc.).
Communication Flow: Illustrate how data flows within the network. Use diagrams (virtual or physical) to visualize the connections.
Tools and Technologies: Mention the tools, software, and platforms used (e.g., VirtualBox, TrueNAS, openVPN).
If it’s a physical setup, include images or diagrams showing the physical connections between devices (if available).
Demonstration:

Showcase the project in action. This can be done through:
Screenshots: Capture relevant screens from your VMs (e.g., terminal windows, network configuration screens).
Videos: Record a short video demonstrating how the network functions. Highlight key features.
GitHub Repository: If applicable, provide a link to a GitHub repository where the code/configuration files are stored. Include a README with instructions for setting up and running the project.
Sample Data: If your project involves data transfer (e.g., file sharing, communication), demonstrate it with sample data.
Make sure the demonstration aligns with the project’s objectives.
Citation:

Acknowledge any external sources you used during the project. This includes tutorials, documentation, research papers, or any other references.
Properly cite these sources using a consistent citation style (e.g., APA, MLA, IEEE). You can use a citation generator to make your life easier here! Something like this is pretty accessible for my students.
Project Suggestions
Here are some projects I think are cool. These should be achievable on VMs:

Setup a Network Attached Storage (NAS). You can search around for different solutions, here is one example tutorial for TrueNAS on VM.
**Better on a raspberry pi!
After this is done, think of an application that will utilize this. One that I like is to do something like setting up a Plex (or alternative) server on the NAS. This tutorial goes through the steps as well, and is pretty fun overall.
Setup a VPN Gateway - 
Deploy VMs as VPN servers and clients.
Configure VPN protocols (e.g., OpenVPN, IPsec).
Set up encryption, authentication, and key management.
Test secure communication between client and server.
**Also better on a pi!
For a physical implementation like a raspberry pi, you can use this as your home network vpn, and you can demostrate with access from an outside network
After this is done, demonstrate local network access from remote (or virtually remote) machine
I personally think this pairs nicely with the NAS project as well, but maybe too much for a 2-week project...
Leverage Connection for Distributed Computing - 
Use your virtual machines as workers and develop/demonstrate a script that will distribute tasks and complete in parallel across machines.
Use your favorite language to do this (Python has a great package called Ray that makes this accessible, C++ you can use something like MPI, but search around based on your task!)
This is a secret intro to Cluster computing and HPC, which we have deployed here at UTRGV for our supercomputing cluster CRADLE. If you enjoy this project, there is a lot of exciting work to do here!
PS: If you would like to try a physical version of one of these projects that would be excellent! (and personally I think more fun and fulfilling). I have some jetson nano devices available, so just let me know if you would like to try it out.

