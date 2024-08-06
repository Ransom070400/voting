# CARTESI VOTE TRACKING SYSTEM
Nigeria's challenges with corruption are well-documented and have significant implications for its governance and economic development. Addressing corruption is crucial for improving the country’s economic prospects. Here’s how a cartesi based blockchain voting system specifically could address some of these challenges:

Enhancing Electoral Integrity: Blockchain’s transparency and immutability make it difficult to alter voting results. By ensuring that election outcomes are secure and verifiable, a blockchain system can reduce the potential for vote tampering and fraudulent activities, which are significant issues in Nigeria’s elections.

Increasing Public Trust: Corruption erodes public trust in government institutions. Implementing a transparent and tamper-proof voting system could rebuild trust in the electoral process, encouraging more citizen engagement and participation. This increased engagement can lead to better governance and more effective policy-making.

Encouraging Accountability: Blockchain’s ability to provide an immutable record of transactions means that any attempt to manipulate the system can be traced. This can create a deterrent for corrupt practices, as the risk of being caught increases.

Reducing Election Costs: Traditional voting systems can be costly and prone to mismanagement. Blockchain can streamline the voting process, reduce administrative costs, and minimize the resources required to manage and secure the election process.

Promoting Legal Reforms: The adoption of blockchain voting might push for broader reforms in other areas of governance. As the technology demands strict adherence to transparency and accountability, it could encourage similar standards in other government functions.

Driving Technological Adoption: By adopting blockchain for voting, Nigeria could set a precedent for the use of technology to tackle corruption and inefficiency. This move could attract tech-savvy investors and innovators interested in applying similar solutions in other areas of governance and public services.

Overview
This code manages a voting system and communicates with a server to handle different types of requests.

Key Functions
Set Up:

The code connects to a server using a URL from its settings.
Vote Tracking:

It keeps track of votes and who has voted.
Handling Requests:

Advance Requests: Logs the request and always accepts it.
Inspect Requests: Logs the request and always accepts it.
Vote Requests:
Checks if a person has already voted. If they have, it rejects their vote.
If they haven’t, it counts their vote for the chosen candidate.
Get Votes Requests:
Returns the number of votes a candidate has received.
Continuous Checking:

The code repeatedly asks the server if there are any new requests to handle.
It processes any new requests it receives based on their type.
Summary
The code continuously interacts with a server to manage votes and respond to requests. It keeps track of who has voted and handles different types of requests related to voting.
