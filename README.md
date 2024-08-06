# CARTESI VOTE TRACKING SYSTEM

Overview
This code manages a voting system and communicates with a server to handle different types of requests.

**Key Functions
Set Up:**

The code connects to a server using a URL from its settings.
**Vote Tracking:**

It keeps track of votes and who has voted.
**Handling Requests:**

**Advance Requests: **Logs the request and always accepts it.
**Inspect Requests:** Logs the request and always accepts it.
**Vote Requests:**
Checks if a person has already voted. If they have, it rejects their vote.
If they haven’t, it counts their vote for the chosen candidate.
**Get Votes Requests:**
Returns the number of votes a candidate has received.
**Continuous Checking:
**
The code repeatedly asks the server if there are any new requests to handle.
It processes any new requests it receives based on their type.
**Summary**
The code continuously interacts with a server to manage votes and respond to requests. It keeps track of who has voted and handles different types of requests related to voting.
