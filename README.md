# NT-Spark
Nervos Talk Forum - Spark Program

This is where user NNCBN’s NT-Spark submission is created in the https://talk.Nervos.org/ forum and edited before being published there. This creates clarity in the forum, since repeated edits and improvements take place on GitHub rather than in the forum itself. A committee must decide on the Spark proposals, a process that is complicated by changes made to the proposals within the forum. This reduces unnecessary extra work for the decision-makers there.

Proposal Template:
https://talk.nervos.org/t/spark-program-mini-grant-initiative/8752/7

0. Spark Program | NNCBN - Nervos Network Community Boot Nodes

1. Project Overview
- Project Name:

NNCBN - Nervos Network Community Boot Nodes
- One-Sentence Overview:

One Year of Network Node Operation: Improving Transaction Propagation, Network Diversity, and Redundancy While Establishing Community Bootnodes
- Project Category:

Network technology, hardware operations

2. Team Profile
- Core Members:

knmo, Entire Project -/Planning, Implementation, Further Development
- Technical Background

Two-year vocational training program consisting of one year of theoretical IT study (application development and network technology), followed by a second year of practical training in systems electronics.
Contact Information:
@NNCBN - E-Mail - Discord - https://github.com/NNCBN

3. Project Background
- Background Description:

Bootnodes are required for the Nervos Network to operate. They maintain connections with other reachable nodes on the network. When a new node synchronizes for the first time, it needs bootnodes to discover full nodes from which it can obtain the blockchain data. These bootnodes are currently operated in data centers owned by large corporations. This arrangement lacks operator diversity and makes the network vulnerable to legal and economic pressures.
- Ecosystem Relevance:

Widespread adoption of community bootnodes would mitigate the impact of potential problems affecting existing bootnodes. Interested individuals should have the opportunity to operate bootnodes themselves, provided they meet minimum requirements, particularly regarding long-term uninterrupted operation and performance.

4. Solution
- Core Solution: How does the project address the above issues? 

The project will create a new bootnode operated by an individual rather than a company and hosted outside a traditional data center. It will also support interested parties who wish to improve the decentralization of the Nervos Network by operating bootnodes themselves.

The first community bootnode is operated by me, the initiator of the Nervos Network Community Bootnode (NNCBN). Its geographic location will increase the diversity of the existing bootnodes and may significantly improve transaction propagation. It will operate on a West African island in the Atlantic, connected to an undersea cable linking Brazil and Portugal. Historically, connections between South America and Europe or Asia have often been routed through North America. This bootnode will provide a connection point in Africa between the heavily used Central European region and South America.

The project will also create and publish a curated list of selected bootnodes that will get tested through initial synchronization tests at randomly selected intervals. Bootnodes must remain continuously accessible so that new nodes can synchronize and establish connections through them. Preference will be given to bootnodes located in geographically underrepresented countries and operated on diverse operating-system platforms. Bootnodes hosted in data centers or operated through VPN providers are outside the scope of this project.
- User Perspective: How do end users and developers use it? What are the results?

Transactions will be forwarded at high speed. Additionally, the first NNCBN network node serves than as an hub for connections from South America and West Africa. Pings to both South Africa and Central Europe show a latency of only ~80 ms, and ~200 ms to Australia and Brazil. Fast transaction routing between South America and Europe. Positive impact on transaction routing speed.
- Differentiation: How does this differ from existing solutions?

The first NNCBN node represents a strategically positioned diversification of the full-node network. It provides an opportunity to improve network diversity without relying on major cloud providers such as Amazon and Google, as is currently the case for many bootnodes.

The provider-side routing over vast distances is notable: latency of approximately 80 ms to both Cape Town and Frankfurt provides a good example. Adverse conditions and outages at major cloud providers such as Amazon are rare, but they do occur, often with significant consequences.

Centralization is undesirable for several reasons, including dependence on the U.S. economy and jurisdiction, as well as hardware and software monocultures. A large proportion of the current infrastructure likely runs on Ubuntu or Debian. Diversity creates reliability through redundancy; less common alternatives, such as BSD or Qubes OS, should also be represented. Although this may not currently be necessary, system-wide vulnerabilities may arise that do not affect other operating systems.

I have chosen Qubes OS because it uses “qubes”—securely isolated compartments—and templates, providing both flexibility and security. Hardware has also been affected by vulnerabilities in the past. Prominent examples include the SRSO, “Inception,” and “Spectre” vulnerabilities, which were mitigated through software updates. A newer processor, beginning with the Zen 5 generation, will be used to operate the first NNCBN node. The latest BIOS update will be applied after the hardware is deployed and before the operating system is installed. Operating-system updates will be performed regularly, and weekly reports will provide details such as data usage and other optimization settings.

5. Technical Approach
- Technology Stack:

AMD Zen5 processor, 16GB DDR5-RAM, 1024 GB SSD-HDD; 

- Architecture Overview: Core Modules and Their Relationships (Architecture Diagram or Flowchart May Be Included)

Qubes OS, template to run latest CKB linux-gnu (>=0.209.0). Installation without Docker. In future, there may also be other templates, such as those for system monitoring.

- Key Technical Points: The Most Technically Challenging Aspects of the Project and Their Solutions

Hardware procurement, system installation, ongoing operation, software updates, and regular operational reporting—ideally on social media—to generate interest among others who may wish to operate an NNCBN. Relevant questions will also be answered through these channels.

- Language: English

6. To-Do List
- Break down by week: Week 1, Week 2, … (Recommended: 4–8 weeks, no more than 12 weeks)

**Week 1:** Procure the hardware, install the system, and document each step and practical experience for interested parties.

**Week 2:** Set up the contract with the internet service provider and synchronize the node.

**Week 3:** Create a social media account and share practical experiences from the installation and setup process. Share insights into network connections, data usage, and hardware utilization.
- Weekly Goals: Specific tasks to be completed this week (not "continue development")

Week 1: Hardware: check the configuration, apply the initial BIOS update, and install Qubes OS.

Week 2: Set up a contract with the internet service provider. Monthly prepaid payments are standard; if possible, set up automatic monthly payments.

Week 3: Share information about the hardware and software decisions made and their implementation.
- Milestone Labels: Key milestones (e.g., MVP completion, start of testing, demo launch)

End of September: The operating system is installed and up to date.

Early October: The CKB node is installed and begins synchronizing. It connects primarily to a node in Santiago, South America (Google), and uses a node in Cape Town, Africa (Amazon) as a fallback.

7. Required Funding & Funding Breakdown
A. Funding Requirements
- Total Amount Requested: Specific amount (USD)

1620$
- Single-Category Projects: (Purely technical development or purely user testing) If there is sufficient justification, you may apply for funding exceeding $1,000; however, the total cap for all project types remains at $2,000 and will not be adjusted. ** For applications exceeding $1,000, please provide a detailed explanation of why the project is structurally more complex than a standard single-category project and why the standard budget is insufficient to support delivery. The committee will evaluate each application on a case-by-case basis.

Hardware: one-time initial payment of $900 in September 2026.

I propose quarterly payments for electricity and internet: $10 per month for electricity plus $50 per month for internet, totaling $60 per month, or $180 per quarter, converted from CKB at the exchange rate in effect at the time.

The first quarterly payment, made in October 2026, will cover October, November, and December 2026. The second payment, made in January 2027, will cover January, February, and March 2027. The third payment, made in April 2027, will cover April, May, and June 2027. The fourth payment, made in July 2027, will cover July, August, and September 2027.


B. Funding Breakdown
- Break it down item by item: List the use of funds by week or by category, clearly distinguishing between the technical and community components.

Hardware, One-time initial payment $900

Monthly Electricity $10

Monthly Internet $50

$60/month × 12 months = $720
- Description of Use: What exactly is each fund used for?

Hardware: AMD Zen5 processor, 16GB DDR5-RAM, 1024 GB SSD-HDD;

Electricity consumption. Internet, Unlimited Data Usage.
- Reasonableness: Aligned with the project scope and workload

The selected location for the first NNCBN provides exceptionally good intercontinental connectivity for the Nervos Network, enabling transactions to be routed quickly.

Internet and electricity prices are comparable to international rates.

The hardware is state-of-the-art and was selected to provide sufficient performance while maintaining low power consumption.

8. Deliverables + How to Verify
A. Deliverables
- Deliverables List: List, item by item, the deliverables to be provided upon project completion

**Hardware purchase**

The internet connection has been established.

The hardware is running the latest BIOS version and Qubes OS. If unexpected complications arise with Qubes OS, a different operating system will be selected.

Node Software Settings, Become Discoverable by CKB Node Probe: https://nodes.ckb.dev/getConnectedInstruction

Full Node Synchronization

A record of all settings for interested bootnode operators who wish to launch a similar system.
- Acceptance Criteria: What are the "completion criteria" for each deliverable? (Reproducible and verifiable)

The network node is fully synchronized and continues to operate. Other nodes can discover this NNCBN among the available network connections and use it to synchronize newly configured nodes.
- Format Guidelines: Code repositories, npm packages, documentation, demo URLs, videos, etc.

B. How to Verify
- Acceptance Process: How can the committee/community independently verify each deliverable?

All steps will be documented, including instructions for future bootnode operators. This information will be made publicly available, and progress updates and details of actions taken will be shared on social media.
- Non-code review verification: Can verification be completed without reviewing the code? (e.g., running tests, viewing demos, checking transaction hashes, reading documentation, etc.). This is a very critical point—if verification must rely on code review, it will be difficult for the committee, with its limited manpower, to cover everything.

The nodes.ckb.dev website lists permanently operational nodes. This node will appear as a dot in the Atlantic Ocean, west of Senegal. Its performance monitoring data will also be documented and published.
- Expected Output: What results should be seen when the validation passes? (e.g., command output, page display, test report)

Fast transaction propagation between South America and Europe, while providing a point of connectivity for West Africa.
- Environment Requirements: What environment is required? (e.g., operating system, dependencies, Node.js)

A less commonly used, security-focused Linux distribution was selected to promote greater diversity within the ecosystem.

Resource-Efficient Logging Settings: toml [logger] filter = "error"

Remove [rpc] modules like "Debug" and "Miner": https://website-sooty-chi-72.vercel.app/lessons/19-full-node-setup
- Cost Control: Is the cost of validation manageable? (The committee/community will not spend a significant amount of time on validation.)

Every node operator will be able to see this new community bootnode among their network connections.

9. Current State vs. Funded Work

I’m already on site and have researched the best hardware to purchase. Internet service will be set up in early October, with monthly fees. Electricity is billed monthly and is already available. If fiber-optic service becomes available, the connection will be upgraded.











