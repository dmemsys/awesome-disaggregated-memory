# Awesome Disaggregated Memory
A list of awesome researchers and papers about disaggregated memory.

- [Awesome Disaggregated Memory](#awesome-disaggregated-memory)
- [Researchers](#researchers)
- [Papers](#papers)
  - [Survey/Vision Papers](#surveyvision-papers)
  - [OS](#os)
  - [Software/Language Runtime](#softwarelanguage-runtime)
  - [Data structures](#data-structures)
  - [Storage Systems](#storage-systems)
  - [Databases](#databases)
  - [Hardware](#hardware)
  - [Applications](#applications)
- [Industrial Practices](#industrial-practices)

# Researchers
- [Harry Xu](http://web.cs.ucla.edu/~harryxu/)
- [Kimberly Keeton](https://scholar.google.com/citations?hl=en&user=wR_tv-kAAAAJ&view_op=list_works&sortby=pubdate)
- [Marcos Aguilera](http://mkaguilera.kawazoe.org/)
- [Mosharaf Chowdhury](https://www.mosharaf.com/)
- [Anurag Khandelwal](https://www.anuragkhandelwal.com/)
- [Yiying Zhang](https://cseweb.ucsd.edu/~yiying/)
- [Pengfei Zuo](http://pfzuo.github.io/homepage/)
- [Yizhou Shan](http://lastweek.io/)
- [Chenxi Wang](http://web.cs.ucla.edu/~wangchenxi/)
- [Qizhen Zhang](https://qizhenzhang.me/)
- [Huaicheng Li](https://huaicheng.github.io/)

# Papers
## Survey/Vision Papers
| Conference      | Paper                                                                                                                                  | Code |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| WORD 2019       | [Exploring the Disaggregated Memory Interface Design Space](http://word19.ece.cornell.edu/word19-paper8-camera.pdf)                    |      |
| ICDCS 2019      | [Memmory Disaggregation: Research Problems and Opportunities](https://ieeexplore.ieee.org/iel7/8867821/8884790/08885074.pdf)           |      |
| APSys 2022      | [Towards a Fully Disaggregated and Programmable Data Center](https://dl.acm.org/doi/abs/10.1145/3546591.3547527)                       |      |
| HotOS 2023      | [Skadi: Building a Distributed Runtime for Data Systems in Disaggregated Data Centers](https://dl.acm.org/doi/10.1145/3593856.3595897) |      |
| SIGOPS OSR 2023 | [Memory disaggregation: why now and what are the challenges](https://dl.acm.org/doi/abs/10.1145/3606557.3606563)                       |      |

## OS
| Conference   | Paper                                                                                                                                                              | Code                                               |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- |
| HPCA 2012    | [System-Level Implications of Disaggregated Memory](http://ieeexplore.ieee.org/document/6168955/)                                                                  |                                                    |
| NSDI 2017    | [Efficient Memory Disaggregation with INFINISWAP](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/gu)                                     | [link](https://github.com/SymbioticLab/Infiniswap) |
| ATC 2018     | [Remote regions: a simple abstraction for remote memory](https://www.usenix.org/system/files/conference/atc18/atc18-aguilera.pdf)                                  |                                                    |
| EuroSys 2018 | [Welcome to Zombieland: Practical and Energy-Efficient Memory Disaggregation in a Datacenter](https://dl.acm.org/doi/10.1145/3190508.3190537)                      |                                                    |
| OSDI 2018    | [LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation](https://www.usenix.org/conference/osdi18/presentation/shan)                          | [link](https://github.com/WukLab/LegoOS)           |
| EuroSys 2019 | [Can Far Memory Improve Job Throughput?](https://dl.acm.org/doi/abs/10.1145/3342195.3387522)                                                                       |                                                    |
| ATC 2020     | [Effectively Prefetching Remote Memory with Leap](https://www.usenix.org/conference/atc20/presentation/al-maruf)                                                   |                                                    |
| SIGMOD 2022  | [Optimizing Data-Intensive Systems in Disaggregated Data Centers with TELEPORT](https://dl.acm.org/doi/abs/10.1145/3514221.3517856)                                | [link](https://github.com/eniac/TELEPORT)          |
| EuroSys 2022 | [Slashing the Disaggregation Tax in Heterogeneous Data Centers with FractOS](https://dl.acm.org/doi/abs/10.1145/3492321.3519569)                                   |                                                    |
| FAST 2022    | [Hydra: Resilient and Highly Available Remote Memory](https://www.usenix.org/conference/fast22/presentation/lee)                                                   | [link](https://github.com/SymbioticLab/hydra)      |
| OSDI 2023    | [Karma: Resource Allocation for Dynamic Demands](https://www.usenix.org/conference/osdi23/presentation/vuppalapati)                                                |                                                    |
| ASPLOS 2023  | [TPP: Transparent Page Placement for CXL-Enabled Tiered Memory](https://dl.acm.org/doi/10.1145/3582016.3582063)                                                    |                                                    |
| EuroSys 2023 | [DiLOS: Do Not Trade Compatibility for Performance Memory Disaggregation](https://dl.acm.org/doi/abs/10.1145/3552326.3567488)                                      |                                                    |
| NSDI 2023    | [Canvas: Isolated and Adaptive Swapping for Multi-Applications on Remote Memory](https://www.usenix.org/conference/nsdi23/presentation/wang-chenxi)                | [link](https://github.com/uclasystem/canvas)       |
| NSDI 2023    | [Hermit: Low-Latency, High-Throughput, and Transparent Remote Memory via Feedback-Directed Asynchrony](https://www.usenix.org/conference/nsdi23/presentation/qiao) | [link](https://github.com/uclasystem/hermit)       |
| SOSP 2023    | [Mira: A Program-Behavior-Guided Far Memory System]()                                                                                                              |                                                    |
| HotOS 2023   | [Prefetching Using Principles of Hippocampal-Neocortical Interaction](https://www.anuragkhandelwal.com/papers/cls.pdf)                                             |                                                    |

## Software/Language Runtime
| Conference   | Paper                                                                                                                                              | Code                                           |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| OSDI 2020    | [AIFM: High-Performance, Application-Integrated Far Memory](https://www.usenix.org/conference/osdi20/presentation/ruan)                            | [link](https://github.com/AIFM-sys/AIFM)       |
| OSDI 2020    | [Semeru: A Memory-Disaggregated Managed Runtime](https://www.usenix.org/conference/osdi20/presentation/wang)                                       | [link](https://github.com/uclasystem/Semeru)   |
| OSDI 2022    | [MemLiner: Lining up Tracing and Application for a Far-Memory-Friendly Runtime](https://www.usenix.org/conference/osdi22/presentation/wang)        | [link](https://github.com/uclasystem/MemLiner) |
| OSDI 2022    | [Carbink: Fault-Tolerant Far Memory](https://www.usenix.org/conference/osdi22/presentation/zhou-yang)                                              |                                                |
| PLDI 2022    | [Mako: a low-pause, high-throughput evacuating collector for memory-disaggregated datacenters](https://dl.acm.org/doi/abs/10.1145/3519939.3523441) | [link](https://github.com/uclasystem/Mako)     |
| SIGCOMM 2023 | [Cowbird: Freeing CPUs to Compute by Offloading the Disaggregation of Memory]()                                                                    |                                                |

## Data structures
| Conference  | Paper                                                                                                                                                        | Code                                          |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------- |
| HotOS 2019  | [Designing far memory data structures: Think outside the box](https://dl.acm.org/doi/10.1145/3317550.3321433)                                                |                                               |
| ATC 2021    | [One-Sided RDMA-Conscious Extendible Hashing for Disaggregated Memory](https://www.usenix.org/conference/atc21/presentation/zuo)                             |                                               |
| SIGMOD 2022 | [Sherman: A Write-Optimized Distributed B+Tree Index on Disaggregated Memory](https://github.com/thustorage/Sherman)                                         | [link](https://github.com/thustorage/Sherman) |
| OSDI 2023   | [SMART: A High-Performance Adaptive Radix Tree for Disaggregated Memory](https://www.usenix.org/conference/osdi23/presentation/luo)                          | [link](https://github.com/dmemsys/SMART)      |
| FAST 2023   | [ROLEX: A Scalable RDMA-Oriented Learned Key-Value Store for Disaggregated Memory Systems](https://www.usenix.org/conference/fast23/presentation/li-pengfei) | [link](https://github.com/iotlpf/ROLEX)       |

## Storage Systems
| Conference      | Paper                                                                                                                                                                                | Code                                       |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------ |
| SYSTOR 2019     | [Storm: a fast transactional dataplane for remote data structures](https://dl.acm.org/doi/10.1145/3319647.3325827)                                                                   |                                            |
| ATC 2020        | [Disaggregating Persistent Memory and Controlling Them Remotely: An Exploration of Passive Disaggregated Key-Value Store](https://www.usenix.org/conference/atc20/presentation/tsai) | [link](https://github.com/WukLab/pDPM)     |
| FAST 2022       | [FORD: Fast One-Sided RDMA-based Distributed Transactions for Disaggregated Persistent Memory](https://www.usenix.org/conference/fast22/presentation/zhang-ming)                     | [link](https://github.com/minghust/ford)   |
| HotStorage 2022 | [Hello Bytes, Bye Blocks: PCIe Storage Meets Compute Express Link for Memory Expansion (CXL-SSD)](https://dl.acm.org/doi/abs/10.1145/3538643.3539745)                                |                                            |
| VLDB 2022       | [Redy: Remote Dynamic Memory Cache](https://dl.acm.org/doi/10.14778/3503585.3503587)                                                                                                 |                                            |
| TACO 2023       | [Fast One-Sided RDMA-Based State Machine Replication for Disaggregated Memory](https://dl.acm.org/doi/full/10.1145/3587096)                                                          |                                            |
| VLDB 2023       | [DINOMO: An Elastic, Scalable, High-Performance Key-Value Store for Disaggregated Persistent Memory](https://arxiv.org/pdf/2209.08743)                                               | [link](https://github.com/utsaslab/dinomo) |
| ASPLOS 2023     | [Ubft: Microsecond-scale bft using disaggregated memory](https://dl.acm.org/doi/10.1145/3575693.3575732)                                                                             |
| FAST 2023       | [FUSEE: A Fully Memory-Disaggregated Key-Value Store](https://www.usenix.org/conference/fast23/presentation/shen)                                                                    | [link](https://github.com/dmemsys/FUSEE)   |
| FAST 2023       | [Patronus: High-Performance and Protective Remote Memory](https://www.usenix.org/conference/fast23/presentation/yan)                                                                 |                                            |
| SOSP 2023       | [Ditto: An Elastic and Adaptive Memory-Disaggregated Caching System]()                                                                                                               | [link](https://github.com/dmemsys/Ditto)   |

## Databases
| Conference  | Paper                                                                                                                                  | Code |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| VLDB 2020   | [Understanding the Effect of Data Center Resource Disaggregation on Production DBMSs](https://dl.acm.org/doi/10.14778/3397230.3397249) |      |
| CIDR 2020   | [Rethinking Data Management Systems for Disaggregated Data Centers](https://www.cis.upenn.edu/~sga001/papers/ddc-cidr20.pdf)           |      |
| SIGMOD 2021 | [PolarDB Serverless: A Cloud Native Database for Disaggregate Data Centers](https://dl.acm.org/doi/10.1145/3448016.3457560)            |      |
| CIDR 2022   | [Farview: Disaggregated Memory with Operator Offloading for Database Engines](https://www.cidrdb.org/cidr2022/papers/p11-korolija.pdf) |      |

## Hardware
| Conference      | Paper                                                                                                                                                        | Code                                   |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------- |
| ISCA 2009       | [Disaggregated Memory for Expansion and Sharing in Blade Servers](https://dl.acm.org/doi/10.1145/1555754.1555789)                                            |                                        |
| OSDI 2016       | [Network Requirements for Resource Disaggregation](https://www.usenix.org/conference/osdi16/technical-sessions/presentation/gao)                             |                                        |
| ASAP 2018       | [REMAP: Remote Memory Manager for Disaggregated Platforms](https://ieeexplore.ieee.org/iel7/8424123/8445082/08445095.pdf)                                    |                                        |
| NSDI 2019       | [Shoal: A Network Architecture for Disaggregated Racks](https://www.usenix.org/conference/nsdi19/presentation/shrivastav)                                    |                                        |
| FAST 2021       | [Concordia: Distributed Shared Memory with In-Network Cache Coherence](https://www.usenix.org/conference/fast21/presentation/wang)                           |                                        |
| ATC 2021        | [Characterizing and Optimizing Remote Persistent Memory with RDMA and NVM](https://www.usenix.org/conference/atc21/presentation/wei)                         |                                        |
| ASPLOS 2021     | [Rethinking Software Runtimes for Disaggregated Memory](https://dl.acm.org/doi/10.1145/3445814.3446713)                                                      |                                        |
| SOSP 2021       | [MIND: In-Network Memory Management for Disaggregated Data Centers](https://dl.acm.org/doi/10.1145/3477132.3483561)                                          |                                        |
| ATC 2022        | [Direct Access, High-Performance Memory Disaggregation with DirectCXL](https://www.usenix.org/conference/atc22/presentation/gouk)                            |                                        |
| ASPLOS 2022     | [Clio: A Hardware-Software Co-Designed Disaggregated Memory System](https://dl.acm.org/doi/10.1145/3503222.3507762)                                          | [link](https://github.com/WukLab/Clio) |
| ASPLOS 2023     | [Pond: CXL-Based Memory Pooling Systems for Cloud Platforms](https://dl.acm.org/doi/10.1145/3575693.3578835)                                                 | [link](https://github.com/vtess/Pond)  |
| SIGOPS OSR 2023 | [Make It Real: An End-to-End Implementation of A Physically Disaggregated Data Center](https://cseweb.ucsd.edu/~yiying/SIGOPS-OSR-Yiying-Disaggregation.pdf) |                                        |


## Applications
| Conference    | Paper                                                                                                                                                                                                   | Code                                                           |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| HotNets 2017  | [Tolerating Faults in Disaggregated Datacenters](https://dl.acm.org/doi/10.1145/3152434.3152447)                                                                                                        |                                                                |
| WORD 2019     | [The Serverless Data Center: Hardware Disaggregation Meets Serverless Computing](https://adept.eecs.berkeley.edu/papers/the-serverless-data-center-hardware-disaggregation-meets-serverless-computing/) |                                                                |
| HotCloud 2020 | [Disaggregation and the Application](https://www.usenix.org/conference/hotcloud20/presentation/angel)                                                                                                   |                                                                |
| EuroSys 2022  | [Jiffy: Elastic Far-Memory for Stateful Serverless Analytics](https://dl.acm.org/doi/abs/10.1145/3492321.3527539)                                                                                       |                                                                |
| ATC 2022      | [JITServer: Disaggregated Caching JIT Compiler for JVM in the Cloud](https://www.usenix.org/conference/atc22/presentation/khrabrov)                                                                     | [link](https://github.com/AlexeyKhrabrov/jitserver-benchmarks) |
| POMACS 2023   | [Memtrade: Marketplace for Disaggregated Memory Clouds](https://dl.acm.org/doi/abs/10.1145/3589985?af=R)                                                                                                | [link](https://github.com/SymbioticLab/Memtrade)               |
| VLDB 2023     | [FlexChain: An Elastic Disaggregated Blockchain](https://www.vldb.org/pvldb/vol16/p23-wu.pdf)                                                                                                           |                                                                |

# Industrial Practices
- [The Machine](https://www.hpl.hp.com/research/systems-research/themachine/)
- [Disaggregated Memory - In Pursuit of Scale and Efficiency](https://pmem.io/blog/2022/01/disaggregated-memory-in-pursuit-of-scale-and-efficiency/)
- [Compute Express Link: The Breakthrough CPU-to-Device Interconnect](https://www.computeexpresslink.org/)
- [Microsoft Azure Blazes the Disaggregated Memory Trail with ZNUMA](https://www.nextplatform.com/2022/07/11/microsoft-azure-blazes-the-disaggregated-memory-trail-with-znuma/)