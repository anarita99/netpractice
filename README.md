*This project has been created as part of the 42 curriculum by adores.*
 
# NetPractice
 
## Description
 
NetPractice is a practical networking exercise from the 42 curriculum. The goal is to configure small-scale networks by solving 10 progressive levels, each presenting a non-functioning network diagram that must be fixed by adjusting IP addresses, subnet masks, and routing tables.
 
Through this project, you gain hands-on experience with how TCP/IP addressing works, how routers forward traffic between networks, and how gateways connect devices to the outside world. Each level introduces new challenges that require a solid understanding of subnetting and network topology.
 
## Instructions
 
### Running the Training Interface
 
1. Download the project files from the 42 project page.
2. Extract the files into a folder of your choice.
3. Inside that folder, run the launch script:
```bash
bash run.sh
```
 
This will start a local web server and open the NetPractice interface in your browser automatically.
 
> **If `run.sh` does not work**, you can start the server manually:
> ```bash
> python3 -m http.server 49242
> ```
> Then open your browser and navigate to `http://localhost:49242`.
 
### Using the Interface
 
- Enter your **intranet login** in the field on the main page to load your personal configuration.
- Alternatively, use the **Evaluation** tab to generate a random configuration for practice.
- For each level, adjust the unshaded fields until the network configuration is correct.
- Use the **[Check again]** button to verify your configuration.
- Use the **[Get my config]** button to export and download your configuration file.
- Once a level is successfully completed, click **[Next level]** to continue.
> Always export your configuration before moving to the next level — you will need these files for submission.
 
### Submission Requirements
 
- Complete all **10 levels** in the training interface.
- Export one configuration file per level using the **[Get my config]** button.
- Place all **10 configuration files** at the **root of your Git repository**.
- Make sure your intranet login was entered in the interface before exporting, as it is used to identify your configuration.
 
## Resources
 
### Networking Concepts Studied
 
- **TCP/IP Addressing** — how IP addresses are structured and assigned across a network
- **Subnet Masks** — how masks divide an IP address into network and host portions
- **Subnetting (CIDR)** — calculating network ranges, usable hosts, and broadcast addresses
- **Default Gateways** — the role of a gateway in routing traffic outside a local network
- **Routers and Switches** — how routers forward packets between networks vs. how switches operate within a LAN
- **Routing Tables** — how devices determine where to send packets based on destination addresses
- **OSI Model Layers** — understanding where IP addressing (Layer 3) and switching (Layer 2) operate
### References
 
- [Networking Fundamentals – Full YouTube Playlist](https://youtube.com/playlist?list=PLIhvC56v63IJVXv0GJcl9vO5Z6znCVb1P) — the primary video resource used to learn and reinforce networking concepts throughout this project
- [Cloudflare – What is subnetting?](https://www.cloudflare.com/learning/network-layer/what-is-subnetting/)
- **Peer collaboration** was the main resource for working through the levels.

### Use of AI
 
AI was used in a limited and supporting role during this project:
 
- **Clarifying doubts** about networking concepts such as subnet mask calculations and routing table logic, when documentation was unclear.
- **Helping draft this README**, following the structure and requirements outlined in the project subject.
All solutions to the 10 levels were worked out independently and with the help of peers. AI was not used to solve any network configuration directly.
 

