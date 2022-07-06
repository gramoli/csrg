## Projects

### Reducing Blockchain Bottlenecks
The number of cryptographic verifications used in blockchains leads to performance bottlenecks. By reducing 
the number of verifications needed in the blockchain protocols, either by sharding the verification or 
by reducing the propagation of transactions in the network, is key to accelerate the processing of transactions.

- [Dynamic Blockchain Sharding](../pubs/FAB22-Sharding.pdf).
D. Tennakoon, V. Gramoli. 
5th International Symposium on Foundations and Applications of Blockchain (FAB), 2022.

- [Leaderless Consensus](../pubs/ICDCS2021-leaderless.pdf)
K. Antoniadis, A. Desjardins, V. Gramoli, R. Guerraoui, I. Zablotchi.
IEEE 41st International Conference on Distributed Computing Systems (ICDCS), 392-402, 2021, **Best Paper Award**. [video](https://youtu.be/gPrdhebjTM0)

- [Red Belly: A secure, fair and scalable open blockchain](../pubs/redbellyblockchain-oakland21.pdf).
T Crain, C Natoli, V Gramoli.
IEEE Symposium on Security and Privacy (S&P), 466-483, 2021. [video](https://www.youtube.com/watch?v=IlIXrqSie9A)


### Decentralized Governance
A recent area of research is computational social choice that lies at the border of computer science and social choice theory.
As election protocols are often designed assuming synchrony, it makes it hard to adapt them to an open network like the Internet 
where delays can be due to network congestion, misconfiguration or natural disasters. This projects aims at designing 
protocols that tolerate delays and malicious participants to cope with the elect a decentralized governance in a fair manner.

- [Red Belly: A secure, fair and scalable open blockchain](../pubs/redbellyblockchain-oakland21.pdf).
T Crain, C Natoli, V Gramoli.
IEEE Symposium on Security and Privacy (S&P), 466-483, 2021. [video](https://www.youtube.com/watch?v=IlIXrqSie9A)


### Consensus Accountability
Accountability is missing from classic blockchains as the user that manages to double spends usually go undetected. This 
project aims at building an undeniable proof-of-fraud identifying a node that has attempted a double spending attack.
The key idea is to require that the key messages that can influence the block decision to be cryptographically signed 
by their senders. The proof-of-fraud is derived from the combination of conflicting messages.

- [Crime and Punishment in Distributed Byzantine
Decision Tasks](../pubs/ICDCS2022.pdf).
P. Civit, S. Gilbert, V. Gramoli, R. Guerraoui, J. Komatovic, Z. Milosevic, A. Seredinschi. 
42nd IEEE International Conference on Distributed Computing Systems (ICDCS), 2022.

- [As easy as ABC: Optimal (A)ccountable
(B)yzantine (C)onsensus is easy!](../pubs/ABC-IPDPS2022.pdf)
P. Civit, S. Gilbert, V. Gramoli, R. Guerraoui, J. Komatovic.
36th IEEE International Parallel & Distributed Processing Symposium (IPDPS), 2022, **Best Paper Award**.

- [TRAP: The Bait of Rational Players to Solve Byzantine Consensus](../pubs/TRAP-AsiaCCS2022.pdf).
A. Ranchal Pedrosa, V. Gramoli.
17th ACM ASIA Conference on Computer and Communications Security (AsiaCCS), 2022.

- [Polygraph: Accountable byzantine agreement](https://eprint.iacr.org/2019/587.pdf).
P Civit, S Gilbert, V Gramoli. 
IEEE 41st International Conference on Distributed Computing Systems (ICDCS), 2021. [video](https://www.youtube.com/watch?v=OUPWY9SPV6Q)
(BA in proceedings of 34th International Symposium on Distributed Computing (DISC), 2020)


### Ordered Consensus
To avoid the reordering of transactions in blockchain systems that allows hackers to front-run other users, 
it is important to impose an ordering on the transactions being committed in the blockchain. This project
consists of minimizing the time it takes to order transactions to avoid slowing down significantly the system.

- [BA: Ordered Reliable Broadcast and Fast Ordered Byzantine Consensus for Cryptocurrency](https://drops.dagstuhl.de/opus/volltexte/2021/14865/pdf/LIPIcs-DISC-2021-63.pdf).
P. Zarbafian, V. Gramoli:
35th International Symposium on Distributed Computing (DISC), 2021. [video](https://youtu.be/DYN1jifeWGY)

- [The Blockchain Anomaly](../../pubs/Blockchain_Anomaly.pdf).
C Natoli, V Gramoli.
15th IEEE International Symposium on Network Computing and Applications (NCA), 2016.

