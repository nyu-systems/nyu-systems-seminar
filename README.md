
# NYU Systems Reading Group

- [Topics](#topics)
- [Schedule](#schedule)
  * [Spring 2023](#spring-2023-cloud-scale-databases)
  * [Spring 2021](#spring-2021)
  * [Fall 2020](#fall-2020)
  * [Spring 2020](#spring-2020)

This term the seminar takes place every Wednesday from **12:30AM to 1:30PM**. The meeting takes place in person.

## Topics
The seminar discusses a broad range of recent systems papers. Papers are selected from typical systems related conferences, including, but not limited to, the following:

General Systems: [OSDI](https://dblp.uni-trier.de/db/conf/osdi), [SOSP](https://dblp.uni-trier.de/db/conf/sosp), [NSDI](https://dblp.uni-trier.de/db/conf/nsdi/), [ATC](https://dblp.uni-trier.de/db/conf/usenix), [EuroSys](https://dblp.uni-trier.de/db/conf/eurosys/)

Security: [USENIX Security](https://dblp.uni-trier.de/db/conf/uss/), [CCS](https://dblp.uni-trier.de/db/conf/ccs/), [Oakland](https://dblp.uni-trier.de/db/conf/sp/), [NDSS](https://dblp.uni-trier.de/db/conf/ndss/)

Networking: [SIGCOMM](https://dblp.uni-trier.de/db/conf/sigcomm/), [INFOCOM](https://dblp.uni-trier.de/db/conf/infocom/), [IMC](https://dblp.uni-trier.de/db/conf/imc/)

Architecture: [ASPLOS](https://dblp.uni-trier.de/db/conf/asplos/), [ISCA](https://dblp.uni-trier.de/db/conf/isca/), [MICRO](https://dblp.uni-trier.de/db/conf/micro/)

Distributed Systems: [PODC](https://dblp.uni-trier.de/db/conf/podc/), [ICDCS]( https://dblp.uni-trier.de/db/conf/icdcs/)

Storage: [FAST](https://dblp.uni-trier.de/db/conf/fast/)

Some academic terms may have a specfic theme. All the chosen papers are related to that theme.

## Schedule

Each reading group presenter should:
- Send an email reminder to the nyu-systems-reading-group@nyu.edu with paper details and update the URL in the repository a few days prior to the group meeting (at least two days before).

### Spring 2023 (Cloud Scale Databases)

Design and implementation of cloud scale database has an impact on how many of us build and optimize our systems: for those working in the lower-layers (e.g., on offloads, etc.) this is a common application that might influence designs; for those working on tracing, these systems are often what is used to store and query things, and has an impact on what is stored and why; and in general many of these have intricate algorithms (since they are inherently distributed). Reasoning about what properties they provide, and why, is a fun puzzle.

| Date | Discussion Lead | Paper Title and Link | Conference |
| ------------ | ------------ | ------------ | ------------ |
| Feb 22, 2023 | Panda | [Bigtable: A Distributed Storage System for Structured Data](https://research.google/pubs/pub27898/) | [OSDI'10](https://www.usenix.org/conference/osdi10) |
| Mar 1, 2023 | Jinyang | | |
| Mar 8, 2023 | - | | |
| Mar 15, 2023 | - | | |
| Mar 22, 2023 | - | | |
| Mar 29, 2023 | - | | |
| Apr 5, 2023 | -  | | |
| Apr 12, 2023 | - | | |
| Apr 19, 2023 | - | | |
| Apr 26, 2023 | - | | |
| May 03, 2023 | - | | |
| May 10, 2023 | - | | |
| May 17, 2023 | - | | |
| May 24, 2023 | - | | |

### Spring 2021

| Date | Discussion Lead | Paper Title and Link | Conference |
| ------------ | ------------ | ------------ | ------------ |
| March 9, 2021 |  John | [HovercRaft: achieving scalability and fault-tolerance for microsecond-scale datacenter services](https://dl.acm.org/doi/10.1145/3342195.3387545) |  [EuroSys'20](https://www.eurosys2020.org/) |
| March 16, 2021 |  Tao | [Architectural Considerations for a New Generation of Protocols ](https://groups.csail.mit.edu/ana/Publications/PubPDFs/Architectural%20Considerations%20for%20a%20New%20Generation%20of%20Protocols.pdf) | [CCR'90](https://www.sigcomm.org/publications/computer-communication-review) |
| March 23, 2021 |  Lingfan | [Cortex: A Compiler for Recursive Deep Learning Models](https://arxiv.org/abs/2011.01383) |  [MLSys'21](https://mlsys.org/) |
| March 30, 2021 |  Fabian | [Noria: dynamic, partially-stateful data-flow for high-performance web applications](https://www.usenix.org/conference/osdi18/presentation/gjengset) |  [OSDI'18](https://www.usenix.org/conference/osdi18) |
| April 6, 2021 |  Jinkun | [Eris: Coordination-Free Consistent Transactions Using In-Network Concurrency Control](https://syslab.cs.washington.edu/papers/eris-sosp17.pdf) |  [SOSP'17](https://www.sigops.org/s/conferences/sosp/2017/) |
| April 13, 2021 |  Changgeng | [TAO: Facebook’s Distributed Data Store for the Social Graph](https://www.usenix.org/conference/atc13/technical-sessions/presentation/bronson) |  [ATC'13](https://www.usenix.org/conference/atc13) |
| April 20, 2021 |  Eric  | [On the Use of ML for Blackbox System Performance Prediction](https://www.usenix.org/conference/nsdi21/presentation/fu) | [NSDI'21](https://www.usenix.org/conference/nsdi21) |
| April 27, 2021 |  Jessica | [Tesseract: Distributed, General Graph Pattern Mining on Evolving Graphs](https://binds.ch/wp-content/uploads/2021/04/tesseract2021.pdf) |  [EuroSys'21](https://2021.eurosys.org/) |
| May 4, 2021 |  Xiangyu | [Lyra: A Cross-Platform Language and Compiler for Data Plane Programming on Heterogeneous ASICs](https://dl.acm.org/doi/pdf/10.1145/3387514.3405879) | [SIGCOMM'20](https://conferences.sigcomm.org/sigcomm/2020/) |
| May 11, 2021 |  Anqi | [sensAI: ConvNets Decomposition via Class Parallelism for Fast Inference on Live Data](https://proceedings.mlsys.org/paper/2021/file/c4ca4238a0b923820dcc509a6f75849b-Paper.pdf) |  [MLSys'21](https://mlsys.org/) |
| May 18, 2021 |  Taegyun | [Ethanos: Efficient Bootstrapping for Full Nodes on Account-based Blockchain](https://dl.acm.org/doi/pdf/10.1145/3447786.3456231) |  [EuroSys'21](https://2021.eurosys.org/) |


### Fall 2020

| Date | Discussion Lead | Paper Title and Link | Conference |
| ------------ | ------------ | ------------ | ------------ |
| October 27, 2020 |  John | [RedLeaf: Isolation and Communication in a Safe Operating System](https://www.ics.uci.edu/~aburtsev/doc/redleaf-osdi20.pdf "RedLeaf: Isolation and Communication in a Safe Operating System") |  [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |
| November 3, 2020| Xiangyu  | [Swift: Delay is Simple and Effective for Congestion Control in the Datacenter](https://dl.acm.org/doi/pdf/10.1145/3387514.3406591) | [SIGCOMM'20](https://conferences.sigcomm.org/sigcomm/2020/) |
| November 10, 2020| Jessica  | [Come as You Are: Helping Unmodified Clients Bypass Censorship with Server-side Evasion](https://geneva.cs.umd.edu/papers/come-as-you-are.pdf) | [SIGCOMM'20](https://conferences.sigcomm.org/sigcomm/2020/) |
| November 17, 2020| Ding Ding |  [Microsecond Consensus for Microsecond Applications](https://www.usenix.org/system/files/osdi20-aguilera.pdf) |  [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |
| November 24, 2020| Thanksgiving |  - |  - |
| December 1, 2020| Taegyun | [Blockene: A High-throughput Blockchain Over Mobile Device](https://www.usenix.org/system/files/osdi20-satija.pdf) | [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |
| December 8, 2020| Eric | [A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters](https://www.usenix.org/system/files/osdi20-jiang.pdf) | [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |
| December 15, 2020| Changgeng |  [Tolerating Slowdowns in Replicated State Machines using Copilots](https://www.usenix.org/conference/osdi20/presentation/ngo) |  [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |
| December 22, 2020| Anqi | [Retiarii: A Deep Learning Exploratory-Training Framework](https://www.usenix.org/conference/osdi20/presentation/zhang-quanlu) |  [OSDI'20](https://www.usenix.org/conference/osdi20 "OSDI20") |



### Spring 2020

| Date | Discussion Lead | Paper Title and Link | Conference |
| ------------ | ------------ | ------------ | ------------ |
| February 10, 2020 |  Kickoff |  - |  - |
| February 17, 2020 | Fabian  |  [SplitFS: Reducing Software Overhead in File Systems for Persistent Memory](https://dl.acm.org/doi/10.1145/3341301.3359631)   | [SOSP'19](https://sosp19.rcs.uwaterloo.ca/program.html)  |
| February 24, 2020 | Panda  |  [Helen: Maliciously Secure Coopetitive Learning for LinearModels](https://arxiv.org/pdf/1907.07212.pdf) | [S&P'19](https://www.ieee-security.org/TC/SP2019/)  |
| March 2, 2020 |  John | [Learning to Reconstruct: Statistical Learning Theory and Encrypted Database Attacks](https://eprint.iacr.org/2019/011.pdf)  | [S&P'19](https://www.ieee-security.org/TC/SP2019/)  |
| March 9, 2020 | Jinkun | [Pretend Synchrony - Synchronous Verification of Asynchronous Distributed Programs](https://goto.ucsd.edu/~gleissen/papers/pretend-synchrony.pdf)  | [POPL'19](https://popl19.sigplan.org/) |
| March 16, 2020 | Spring Break |  Corona | Virus  |
| March 23, 2020 | Xiangyu  |  Corona |  Virus |
| March 30, 2020 |  Anirudh |  Corona | Virus  |
| April 6, 2020 |  Project Review |  Corona | Virus  |
| April 13, 2020 | Jinyang  |  Corona | Virus  |
| April 20, 2020 |  Taegyun |  Corona | Virus  |
| April 27, 2020 |  Eric |  Corona | Virus  |
| May 4, 2020 |  Changgeng |  Corona | Virus  |
| May 11, 2020 | Anqi  |  Corona | Virus  |
| May 18, 2020 | Tao |  Corona | Virus  |
