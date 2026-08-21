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

One Year of network node operation for improvement on Transaction Propagation, Network Diversification and Redundancy as well as initiating the establishment of community bootnodes.
- Project Category:

Network technology, hardware operations

2. Team Profile
- Core Members:

knmo, Entire Project -/Planning, Implementation, Further Development
- Technical Background

Two-year vocational training program, consisting of one year of theoretical study in IT (application development/network technology) and a second year of practical training in systems electronics.
Contact Information:
@NNCBN - E-Mail - Discord - https://github.com/NNCBN

3. Project Background
- Background Description:

Boot nodes are required for the Nervos Network to operate. These nodes maintain connections to other reachable network nodes. When a new node initiates synchronization for the first time, it would not know where to find full nodes for synchronization without specified boot nodes. These very boot nodes are currently operated in data centers belonging to large corporations. Those lack diversity and are subject to legal and economic influences.  
- Ecosystem Relevance:

The widespread adoption of community boot nodes mitigates the consequences of potential problems with existing boot nodes. Individuals interested should have the opportunity to become boot node operators themselves. However, they must meet minimum requirements, particularly with regard to uninterrupted long-term operation and performance.

4. Solution
- Core Solution: How does the project address the above issues? 

Creation of a new boot node that is operated not by a company and not hosted in a data center, but regionally diverse by an individual. Support for interested parties who wish to improve the decentralization of the NervosNetwork by operating a boot node themselves. The first community bootnode is operated by me, the initiator of this NNCBN (Nervos Network Community Boot Node). The fact that it will operate in that region contributes to greater diversity among the existing bootnodes and will have a significant impact on transaction propagation: It will be operated on a West-African island in the Atlantic, connected to a undersea cable between Brazil and Portugal. Historically, South-American connections have been routed through North America to Europe or Asia. Here is a point in Africa that connects the user-heavy Central European region with South America. 
- User Perspective: How do end users and developers use it? What are the results?

Transactions will be forwarded at high speed. Additionally, the first NNCBN network node serves than as an hub for connections from South America and West Africa. Pings to both South Africa and Central Europe show a latency of only ~80 ms, and ~200 ms to Australia and Brazil. Fast transaction routing between South America and Europe. Positive impact on transaction routing speed.
- Differentiation: How does this differ from existing solutions?

The first NNCBN network node represents a well-positioned diversification of full nodes. This presents an opportunity for valuable network diversification without being a customer of cloud giants like Amazon, Google, Microsoft, etc. as its the case with current Boot Nodes. The provider-side tunneling over vast distances is remarkable: ~80ms to Cape Town and ~80ms to Frankfurt are good examples. Adverse conditions or even outages at cloud giants (negative undertone, as centralization is not beneficial for various reasons) like Amazon are indeed rare, but they do occur, often with significant consequences. A large portion of the current infrastructure most likely runs on Ubuntu or Debian. Diversity creates reliability through redundancy: less common alternatives such as BSD or Qubes-OS should also exist. Even if not currently necessary, there may be system-wide vulnerabilities that do not exist in other systems. I have chosen Qubes-OS as the operating system because it is using "qubes", securely-isolated compartments and templates. Thereby offering flexibility and security. Also Hardware has been affected by vulnerabilities in the past. A prominent example of this was processors whose SRSO "INCEPTION" and "Spectre" vulnerabilities were mitigated through software updates. Newer processors starting with Zen 5 feature built-in native mitigation. Such a newer CPU will be used to operate the first NNCBN. The latest BIOS update will be applied after hardware deployment and before OS installation. Operating-System Software Updates are performed regularly, and weekly reports are provided on details such as data usage and other optimization settings.

5. Technical Approach
- Technology Stack:

AMD Zen5 processor, 16GB DDR5-RAM, 1024 GB SSD-HDD; 

- Architecture Overview: Core Modules and Their Relationships (Architecture Diagram or Flowchart May Be Included)

Qubes OS, template to run latest CKB linux-gnu (>=0.209.0). Installation without Docker. In future, there may also be other templates, such as those for system monitoring.

- Key Technical Points: The Most Technically Challenging Aspects of the Project and Their Solutions

Hardware Procurement, System Installation, Ongoing operarion, Software updates; Regular reporting on operations, ideally on social media, thereby sparking interest among others who also want to take on the operation of an NNCBN. And support by answering relevant questions there.

- Language: English

6. To-Do List
- Break down by week: Week 1, Week 2, … (Recommended: 4–8 weeks, no more than 12 weeks)

Week 1: Hardware Procurement, System Installation, Documenting each step and practical experiences for those interested.

Week 2: Contract with the Internet service provider, node synchronisation.

Week 3: Create a socialmedia account and share practical experiences from the installation and setup process there, Share insights on connections, data usage, and hardware utilization.
- Weekly Goals: Specific tasks to be completed this week (not "continue development")

Week 1: Hardware: Check Configuration, initial BIOS update, Qubes OS installation

Week 2: Contract with the Internet service provider, Monthly prepaid payments are the norm; If possible, set up automatic monthly payments.

Week 3: Sharing information regarding the hardware and software decisions made and their implementation. 
- Milestone Labels: Key milestones (e.g., MVP completion, start of testing, demo launch)

End of September: The operating system is installed and up to date. 

Early October: The CKB node is installed and synchronizing: It connects primarily to Santiago, South America (Google), and uses Cape Town, Africa (Amazon) as a fallback.

7. Required Funding & Funding Breakdown
A. Funding Requirements
- Total Amount Requested: Specific amount (USD)

1620$
- Single-Category Projects: (Purely technical development or purely user testing) If there is sufficient justification, you may apply for funding exceeding $1,000; however, the total cap for all project types remains at $2,000 and will not be adjusted. ** For applications exceeding $1,000, please provide a detailed explanation of why the project is structurally more complex than a standard single-category project and why the standard budget is insufficient to support delivery. The committee will evaluate each application on a case-by-case basis.

Hardware, One-time initial payment $900 September 2026.

I propose a quarterly payment for electricity and internet: $10 for electricity + $50 for internet = $60 × 3 months = $180 at the CKB-to-dollar exchange rate in effect at that time. The first quarterly payment starting in October, covers the three months of October, November, and December. The second quarterly payment in January 2027 is for January, February, and March 2027. The third quarterly payment in April 2027 is for April, May, and June 2027, and the fourth quarterly payment in July 2027 is for July, August, and September.


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

The chosen location where the first NNCBN will operate provides exceptionally good intercontinental connectivity for the Nervos network. Transactions are routed very quickly.

Internet and electricity prices are comparable to international rates. 

The hardware is state-of-the-art but was selected to ensure sufficient performance with low power consumption. 

8. Deliverables + How to Verify
A. Deliverables
- Deliverables List: List, item by item, the deliverables to be provided upon project completion

Hardware Purchase

The Internet connection has been set up

The hardware is running the latest BIOS version and Qubes OS. In the event of unexpected complications with Qubes OS, choosing a different operating system.


Node Software Settings

Full Node Synchronization

A record of all settings for interested Bootnode operators who also want to launch such a system.
- Acceptance Criteria: What are the "completion criteria" for each deliverable? (Reproducible and verifiable)

The network node is fully synchronized and continues to operate. Other nodes can see this NNCBN in the network connections and use it to initially synchronize newly configured nodes.
- Format Guidelines: Code repositories, npm packages, documentation, demo URLs, videos, etc.

B. How to Verify
- Acceptance Process: How can the committee/community independently verify each deliverable?

All steps will be documented, including instructions for future Bootnode operators to follow. This information will be publicly available, and I will post updates on progress and actions taken on social media.
- Non-code review verification: Can verification be completed without reviewing the code? (e.g., running tests, viewing demos, checking transaction hashes, reading documentation, etc.). This is a very critical point—if verification must rely on code review, it will be difficult for the committee, with its limited manpower, to cover everything.

https://nodes.ckb.dev lists all permanently operational nodes. This one will appear as a dot in the Atlantic Ocean west of Senegal. Performance monitoring is also documented and published.
- Expected Output: What results should be seen when the validation passes? (e.g., command output, page display, test report)

Fast transaction processing between South America and Europe. Point of contact for West Africa.
- Environment Requirements: What environment is required? (e.g., operating system, dependencies, Node.js)

A less commonly used Linux distribution with a focus on security was selected to create and promote diversity within the ecosystem.
- Cost Control: Is the cost of validation manageable? (The committee/community will not spend a significant amount of time on validation.)

Every node operator will be able to see this new community boot node in their network connections.

9. Current State vs. Funded Work

I'm already on site. I've done some research on the best hardware to purchase. The internet service will be set up in early October, with monthly fees. Electricity is billed monthly and is already available for use. If fiber-optic service becomes available, the switch will be initiated and implemented. 











