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
Creation of a new boot node that is operated not by a company and not hosted in a data center, but regionally by an individual. Support for interested parties who wish to promote the decentralization of the NervosNetwork by operating a boot node themselves. The first community bootnode is operated by me, the initiator of this NNCBN project, on a West African island. The fact that it will operate in that region contributes to greater diversity among the existing bootnodes and will have a significant impact on transaction propagation: The island in the Atlantic is connected to the undersea cable between Brazil and Portugal. Historically, many South American connections have routed through North America to Europe or Asia. Here is a point in Africa that connects the user-heavy Central European region with South America. 
- User Perspective: How do end users and developers use it? What are the results?
Transactions will be forwarded at high speed. Additionally, the first NNCBN network node serves than as an hub for connections from South America and West Africa. Pings to both South Africa and Central Europe show a latency of only ~80 ms, and ~200 ms to Australia and Brazil.
- Differentiation: How does this differ from existing solutions?
The first NNCBN network node represents a well-positioned diversification of full nodes. This presents an opportunity for valuable network diversification without being a customer of cloud giants like Amazon, Google, Microsoft, etc. The provider-side tunneling over vast distances is remarkable: ~80ms to Cape Town and ~80ms to Frankfurt are good examples. Adverse conditions or even outages at cloud giants (negative undertone, as centralization is not beneficial for various reasons) like Amazon are indeed rare, but they do occur—often with significant consequences. A large portion of the current infrastructure most likely runs on Ubuntu or Debian. Diversity creates reliability through redundancy: less common alternatives such as BSD should also exist. Even if not currently necessary, there may be system-wide vulnerabilities that do not exist in other systems. I have chosen Qubes-OS as the operating system because it is using "qubes", securely-isolated compartments and templates. Thereby offering flexibility and security. Hardware has been affected by vulnerabilities in the past. A prominent example of this was processors whose SRSO "INCEPTION" and "Spectre" vulnerabilities were mitigated through software updates. Newer processors starting with Zen 5 feature built-in native mitigation. Such a newer CPU will be used to operate the first NNCBN.

5. Technical Approach
- Technology Stack:
AMD Zen5 processor, 16GB DDR5-RAM, 1024 GB SSD-HDD; 

- Architecture Overview: Core Modules and Their Relationships (Architecture Diagram or Flowchart May Be Included)
Qubes OS, template to run latest CKB linux-gnu (=>0.209.0), In future, there may also be other templates, such as those for system monitoring.

- Key Technical Points: The Most Technically Challenging Aspects of the Project and Their Solutions
Hardware Procurement, System Installation, Ongoing operarion, Software updates; Regular reporting on operations, ideally on social media, thereby sparking interest among others who also want to take on the operation of an NNCBN. And support by answering relevant questions.

- Language: English

6. To-Do List
- Break down by week: Week 1, Week 2, … (Recommended: 4–8 weeks, no more than 12 weeks)
Week 1: Hardware Procurement, System Installation
Week 2: Contract with the Internet service provider, node synchronisation


- Weekly Goals: Specific tasks to be completed this week (not "continue development")

- Milestone Labels: Key milestones (e.g., MVP completion, start of testing, demo launch)

7. Required Funding & Funding Breakdown
A. Funding Requirements
- Total Amount Requested: Specific amount (USD)

- Single-Category Projects: (Purely technical development or purely user testing) If there is sufficient justification, you may apply for funding exceeding $1,000; however, the total cap for all project types remains at $2,000 and will not be adjusted. ** For applications exceeding $1,000, please provide a detailed explanation of why the project is structurally more complex than a standard single-category project and why the standard budget is insufficient to support delivery. The committee will evaluate each application on a case-by-case basis.

B. Funding Breakdown
- Break it down item by item: List the use of funds by week or by category, clearly distinguishing between the technical and community components.

- Description of Use: What exactly is each fund used for?

- Reasonableness: Aligned with the project scope and workload

8. Deliverables + How to Verify
A. Deliverables
- Deliverables List: List, item by item, the deliverables to be provided upon project completion

- Acceptance Criteria: What are the "completion criteria" for each deliverable? (Reproducible and verifiable)

- Format Guidelines: Code repositories, npm packages, documentation, demo URLs, videos, etc.

B. How to Verify
- Acceptance Process: How can the committee/community independently verify each deliverable?

- Non-code review verification: Can verification be completed without reviewing the code? (e.g., running tests, viewing demos, checking transaction hashes, reading documentation, etc.). This is a very critical point—if verification must rely on code review, it will be difficult for the committee, with its limited manpower, to cover everything.

- Expected Output: What results should be seen when the validation passes? (e.g., command output, page display, test report)

- Environment Requirements: What environment is required? (e.g., operating system, dependencies, Node.js)

- Cost Control: Is the cost of validation manageable? (The committee/community will not spend a significant amount of time on validation.)

9. Current State vs. Funded Work













