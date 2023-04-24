CLOUD COMPUTING - UE20CS351

# Project: Implementing Raft Logic in Go

Name: Ananya Nigam
SRN:  PES1UG20CS044 


# Team Members
1. Ananya Nigam   (PES1UG20CS044)
2. Ananya Prakash  (PES1UG20CS045)
3. Anindita H.K    (PES1UG20CS054)



Raft is a consensus algorithm that is used to ensure that a group of distributed systems agree on a common state. It was designed as an alternative to the more complex Paxos algorithm, with the goal of being easier to understand, implement, and reason about.

The Raft algorithm divides the systems into two categories: leaders and followers. The leader is responsible for managing the replication of the log entries to all the followers and ensuring that they are up to date with the latest state. The followers listen to the leader and respond to its requests. In case the leader fails, a new leader is elected through a voting process, which ensures that only one leader is active at a time.Raft guarantees safety and consistency in the face of network failures, message loss, duplication, and delays, as long as a majority of the systems are available and can communicate with each other. It is widely used in distributed systems such as databases, storage systems, and cloud computing platforms.


