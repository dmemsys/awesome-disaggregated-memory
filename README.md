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
- [Contribute](#contribute)

# Researchers
- [Harry Xu](http://web.cs.ucla.edu/~harryxu/)
- [Kimberly Keeton](https://scholar.google.com/citations?hl=en&user=wR_tv-kAAAAJ&view_op=list_works&sortby=pubdate)
- [Marcos Aguilera](http://mkaguilera.kawazoe.org/)
- [Asaf Cidon](https://www.asafcidon.com/)
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
| Year | Conf.      | Paper                                                                                                                                                        | Code |
| ---- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---- |
| 2019 | WORD       | [Exploring the Disaggregated Memory Interface Design Space](http://word19.ece.cornell.edu/word19-paper8-camera.pdf)                                          |      |
| 2019 | ICDCS      | [Memmory Disaggregation: Research Problems and Opportunities](https://ieeexplore.ieee.org/iel7/8867821/8884790/08885074.pdf)                                 |      |
| 2022 | APSys      | [Towards a Fully Disaggregated and Programmable Data Center](https://dl.acm.org/doi/abs/10.1145/3546591.3547527)                                             |      |
| 2023 | HotOS      | [Skadi: Building a Distributed Runtime for Data Systems in Disaggregated Data Centers](https://dl.acm.org/doi/10.1145/3593856.3595897)                       |      |
| 2023 | SIGOPS OSR | [Memory Disaggregation: Why Now and What are the Challenges](https://dl.acm.org/doi/abs/10.1145/3606557.3606563)                                             |      |
| 2023 | SIGOPS OSR | [Make It Real: An End-to-End Implementation of A Physically Disaggregated Data Center](https://cseweb.ucsd.edu/~yiying/SIGOPS-OSR-Yiying-Disaggregation.pdf) |      |

## OS
| Year | Conf.   | Paper                                                                                                                                                              | Code                                               |
| ---- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------- |
| 2012 | HPCA    | [System-Level Implications of Disaggregated Memory](http://ieeexplore.ieee.org/document/6168955/)                                                                  |                                                    |
| 2017 | NSDI    | [Efficient Memory Disaggregation with INFINISWAP](https://www.usenix.org/conference/nsdi17/technical-sessions/presentation/gu)                                     | [link](https://github.com/SymbioticLab/Infiniswap) |
| 2018 | ATC     | [Remote regions: a simple abstraction for remote memory](https://www.usenix.org/system/files/conference/atc18/atc18-aguilera.pdf)                                  |                                                    |
| 2018 | EuroSys | [Welcome to Zombieland: Practical and Energy-Efficient Memory Disaggregation in a Datacenter](https://dl.acm.org/doi/10.1145/3190508.3190537)                      |                                                    |
| 2018 | OSDI    | [LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation](https://www.usenix.org/conference/osdi18/presentation/shan)                          | [link](https://github.com/WukLab/LegoOS)           |
| 2019 | EuroSys | [Can Far Memory Improve Job Throughput?](https://dl.acm.org/doi/abs/10.1145/3342195.3387522)                                                                       |                                                    |
| 2020 | ATC     | [Effectively Prefetching Remote Memory with Leap](https://www.usenix.org/conference/atc20/presentation/al-maruf)                                                   |                                                    |
| 2022 | SIGMOD  | [Optimizing Data-Intensive Systems in Disaggregated Data Centers with TELEPORT](https://dl.acm.org/doi/abs/10.1145/3514221.3517856)                                | [link](https://github.com/eniac/TELEPORT)          |
| 2022 | EuroSys | [Slashing the Disaggregation Tax in Heterogeneous Data Centers with FractOS](https://dl.acm.org/doi/abs/10.1145/3492321.3519569)                                   |                                                    |
| 2022 | FAST    | [Hydra: Resilient and Highly Available Remote Memory](https://www.usenix.org/conference/fast22/presentation/lee)                                                   | [link](https://github.com/SymbioticLab/hydra)      |
| 2023 | OSDI    | [Karma: Resource Allocation for Dynamic Demands](https://www.usenix.org/conference/osdi23/presentation/vuppalapati)                                                |                                                    |
| 2023 | ASPLOS  | [TPP: Transparent Page Placement for CXL-Enabled Tiered Memory](https://dl.acm.org/doi/10.1145/3582016.3582063)                                                    |                                                    |
| 2023 | EuroSys | [DiLOS: Do Not Trade Compatibility for Performance Memory Disaggregation](https://dl.acm.org/doi/abs/10.1145/3552326.3567488)                                      |                                                    |
| 2023 | NSDI    | [Canvas: Isolated and Adaptive Swapping for Multi-Applications on Remote Memory](https://www.usenix.org/conference/nsdi23/presentation/wang-chenxi)                | [link](https://github.com/uclasystem/canvas)       |
| 2023 | NSDI    | [Hermit: Low-Latency, High-Throughput, and Transparent Remote Memory via Feedback-Directed Asynchrony](https://www.usenix.org/conference/nsdi23/presentation/qiao) | [link](https://github.com/uclasystem/hermit)       |
| 2023 | SOSP    | [Mira: A Program-Behavior-Guided Far Memory System](https://cseweb.ucsd.edu/~yiying/Mira-SOSP23.pdf)                                                                                                              |                                                    |
| 2023 | HotOS   | [Prefetching Using Principles of Hippocampal-Neocortical Interaction](https://www.anuragkhandelwal.com/papers/cls.pdf)                                             |                                                    |
| 2023 | HPCA    | [HoPP: Hardware-Software Co-Designed Page Prefetching for Disaggregated Memory](https://ieeexplore.ieee.org/document/10070986)                                     |                                                    |
| 2023 | DATE    | [MARB: Bridge the Semantic Gap between Operating System and Application Memory Access Behavior](https://ieeexplore.ieee.org/abstract/document/10137018)            |                                                    |
| 2024 | FAST    | [TeRM: Extending RDMA-Attached Memory with SSD](https://www.usenix.org/conference/fast24/presentation/yang-zhe)                                                    | [link](https://github.com/thustorage/TeRM)         |
| 2024 | OSDI    | [Nomad: Non-Exclusive Memory Tiering via Transactional Page Migration](https://www.usenix.org/conference/osdi24/presentation/xiang)                                |                                                    |
| 2024 | OSDI    | [Managing Memory Tiers with CXL in Virtualized Environments](https://www.usenix.org/conference/osdi24/presentation/zhong-yuhong)                                   |                                                    |
| 2024 | ATC     | [UniMem: Redesigning Disaggregated Memory within A Unified Local-Remote Memory Hierarchy](https://www.usenix.org/conference/atc24/presentation/zhong)              | [link](https://github.com/yijieZ/UniMem)           |
| 2024 | ATC     | [FlexMem: Adaptive Page Profiling and Migration for Tiered Memory](https://www.usenix.org/conference/atc24/presentation/xu-dong)                                   | [link](https://github.com/PASAUCMerced/FlexMem)    |

## Software/Language Runtime
| Year | Conf.   | Paper                                                                                                                                                                              | Code                                               |
| ---- | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| 2020 | OSDI    | [AIFM: High-Performance, Application-Integrated Far Memory](https://www.usenix.org/conference/osdi20/presentation/ruan)                                                            | [link](https://github.com/AIFM-sys/AIFM)           |
| 2020 | OSDI    | [Semeru: A Memory-Disaggregated Managed Runtime](https://www.usenix.org/conference/osdi20/presentation/wang)                                                                       | [link](https://github.com/uclasystem/Semeru)       |
| 2022 | OSDI    | [MemLiner: Lining up Tracing and Application for a Far-Memory-Friendly Runtime](https://www.usenix.org/conference/osdi22/presentation/wang)                                        | [link](https://github.com/uclasystem/MemLiner)     |
| 2022 | OSDI    | [Carbink: Fault-Tolerant Far Memory](https://www.usenix.org/conference/osdi22/presentation/zhou-yang)                                                                              |                                                    |
| 2022 | PLDI    | [Mako: a low-pause, high-throughput evacuating collector for memory-disaggregated datacenters](https://dl.acm.org/doi/abs/10.1145/3519939.3523441)                                 | [link](https://github.com/uclasystem/Mako)         |
| 2023 | SIGCOMM | [Cowbird: Freeing CPUs to Compute by Offloading the Disaggregation of Memory](https://vincen.tl/files/chen23cowbird.pdf)                                                                                                    |                                                    |
| 2024 | ASPLOS  | [Scaling Up Memory Disaggregated Applications with Smart](https://dl.acm.org/doi/pdf/10.1145/3617232.3624857)                                                                                                                        | [link](https://github.com/madsys-dev/smart)        |
| 2024 | NSDI    | [Harvesting Idle Memory for Application-Managed Soft State with Midas](https://web.cs.ucla.edu/~harryxu/papers/midas-nsdi24.pdf)                                                   | [link](https://github.com/uclasystem/midas)        |
| 2024 | ASPLOS  | [TrackFM: Far-out Compiler Support for a Far Memory World](https://dl.acm.org/doi/pdf/10.1145/3617232.3624856)                                                                     | [link](https://github.com/compiler-disagg/TrackFM) |
| 2024 | OSDI    | [A Tale of Two Paths: Toward a Hybrid Data Plane for Efficient Far-Memory Applications](https://www.usenix.org/conference/osdi24/presentation/chen-lei)                            |                                                    |
| 2024 | OSDI    | [DRust: Language-Guided Distributed Shared Memory with Fine Granularity, Full Transparency, and Ultra Efficiency](https://www.usenix.org/conference/osdi24/presentation/ma-haoran) |                                                    |

## Data structures
| Year | Conf.  | Paper                                                                                                                                                        | Code                                          |
| ---- | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------- |
| 2019 | HotOS  | [Designing far memory data structures: Think outside the box](https://dl.acm.org/doi/10.1145/3317550.3321433)                                                |                                               |
| 2021 | ATC    | [One-Sided RDMA-Conscious Extendible Hashing for Disaggregated Memory](https://www.usenix.org/conference/atc21/presentation/zuo)                             |                                               |
| 2022 | SIGMOD | [Sherman: A Write-Optimized Distributed B+Tree Index on Disaggregated Memory](https://github.com/thustorage/Sherman)                                         | [link](https://github.com/thustorage/Sherman) |
| 2023 | OSDI   | [SMART: A High-Performance Adaptive Radix Tree for Disaggregated Memory](https://www.usenix.org/conference/osdi23/presentation/luo)                          | [link](https://github.com/dmemsys/SMART)      |
| 2023 | FAST   | [ROLEX: A Scalable RDMA-Oriented Learned Key-Value Store for Disaggregated Memory Systems](https://www.usenix.org/conference/fast23/presentation/li-pengfei) | [link](https://github.com/iotlpf/ROLEX)       |


## Storage Systems
| Year | Conf.      | Paper                                                                                                                                                                                | Code                                           |
| ---- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------- |
| 2017 | SoCC       | [Distributed Shared Persistent Memory](http://lastweek.io/pubs/SoCC17-Hotpot.pdf)                                                                                                    | [code](https://github.com/WukLab/Hotpot)       |
| 2019 | SYSTOR     | [Storm: A Fast Transactional Dataplane for Remote Data Structures](https://dl.acm.org/doi/10.1145/3319647.3325827)                                                                   |                                                |
| 2020 | ATC        | [Disaggregating Persistent Memory and Controlling Them Remotely: An Exploration of Passive Disaggregated Key-Value Store](https://www.usenix.org/conference/atc20/presentation/tsai) | [link](https://github.com/WukLab/pDPM)         |
| 2022 | FAST       | [FORD: Fast One-Sided RDMA-based Distributed Transactions for Disaggregated Persistent Memory](https://www.usenix.org/conference/fast22/presentation/zhang-ming)                     | [link](https://github.com/minghust/ford)       |
| 2022 | HotStorage | [Hello Bytes, Bye Blocks: PCIe Storage Meets Compute Express Link for Memory Expansion (CXL-SSD)](https://dl.acm.org/doi/abs/10.1145/3538643.3539745)                                |                                                |
| 2022 | VLDB       | [Redy: Remote Dynamic Memory Cache](https://dl.acm.org/doi/10.14778/3503585.3503587)                                                                                                 |                                                |
| 2023 | TACO       | [Fast One-Sided RDMA-Based State Machine Replication for Disaggregated Memory](https://dl.acm.org/doi/full/10.1145/3587096)                                                          |                                                |
| 2023 | VLDB       | [DINOMO: An Elastic, Scalable, High-Performance Key-Value Store for Disaggregated Persistent Memory](https://arxiv.org/pdf/2209.08743)                                               | [link](https://github.com/utsaslab/dinomo)     |
| 2023 | ASPLOS     | [Ubft: Microsecond-scale bft using disaggregated memory](https://dl.acm.org/doi/10.1145/3575693.3575732)                                                                             |
| 2023 | FAST       | [FUSEE: A Fully Memory-Disaggregated Key-Value Store](https://www.usenix.org/conference/fast23/presentation/shen)                                                                    | [link](https://github.com/dmemsys/FUSEE)       |
| 2023 | FAST       | [Patronus: High-Performance and Protective Remote Memory](https://www.usenix.org/conference/fast23/presentation/yan)                                                                 |                                                |
| 2023 | SOSP       | [Ditto: An Elastic and Adaptive Memory-Disaggregated Caching System](https://dl.acm.org/doi/10.1145/3600006.3613144)                                                                 | [link](https://github.com/dmemsys/Ditto)       |
| 2024 | OSDI       | [Motor: Enabling Multi-Versioning for Distributed Transactions on Disaggregated Memory](https://www.usenix.org/conference/osdi24/presentation/zhang-ming)                            |                                                |
| 2024 | ATC        | [Ethane: An Asymmetric File System for Disaggregated Persistent Memory](https://www.usenix.org/conference/atc24/presentation/cai)                                                    | [link](https://github.com/miaogecm/Ethane.git) |

## Databases
| Year | Conf.  | Paper                                                                                                                                  | Code |
| ---- | ------ | -------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| 2020 | VLDB   | [Understanding the Effect of Data Center Resource Disaggregation on Production DBMSs](https://dl.acm.org/doi/10.14778/3397230.3397249) |      |
| 2020 | CIDR   | [Rethinking Data Management Systems for Disaggregated Data Centers](https://www.cis.upenn.edu/~sga001/papers/ddc-cidr20.pdf)           |      |
| 2021 | SIGMOD | [PolarDB Serverless: A Cloud Native Database for Disaggregate Data Centers](https://dl.acm.org/doi/10.1145/3448016.3457560)            |      |
| 2021 | VLDB   | [TowardsCost-Effectiveand elasticCloudDatabaseDeploymentviaMemoryDisaggregation](http://www.vldb.org/pvldb/vol14/p1900-zhang.pdf)      |      |
| 2022 | CIDR   | [Farview: Disaggregated Memory with Operator Offloading for Database Engines](https://www.cidrdb.org/cidr2022/papers/p11-korolija.pdf) |      |
| 2023 | ASPLOS | [Persistent Memory Disaggregation for Cloud-Native Relational Databases](https://dl.acm.org/doi/10.1145/3582016.3582055)               |      |

## Hardware
| Year | Conf.  | Paper                                                                                                                                | Code                                   |
| ---- | ------ | ------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------- |
| 2009 | ISCA   | [Disaggregated Memory for Expansion and Sharing in Blade Servers](https://dl.acm.org/doi/10.1145/1555754.1555789)                    |                                        |
| 2016 | OSDI   | [Network Requirements for Resource Disaggregation](https://www.usenix.org/conference/osdi16/technical-sessions/presentation/gao)     |                                        |
| 2018 | ASAP   | [REMAP: Remote Memory Manager for Disaggregated Platforms](https://ieeexplore.ieee.org/iel7/8424123/8445082/08445095.pdf)            |                                        |
| 2019 | NSDI   | [Shoal: A Network Architecture for Disaggregated Racks](https://www.usenix.org/conference/nsdi19/presentation/shrivastav)            |                                        |
| 2021 | FAST   | [Concordia: Distributed Shared Memory with In-Network Cache Coherence](https://www.usenix.org/conference/fast21/presentation/wang)   |                                        |
| 2021 | ATC    | [Characterizing and Optimizing Remote Persistent Memory with RDMA and NVM](https://www.usenix.org/conference/atc21/presentation/wei) |                                        |
| 2021 | ASPLOS | [Rethinking Software Runtimes for Disaggregated Memory](https://dl.acm.org/doi/10.1145/3445814.3446713)                              |                                        |
| 2021 | SOSP   | [MIND: In-Network Memory Management for Disaggregated Data Centers](https://dl.acm.org/doi/10.1145/3477132.3483561)                  |                                        |
| 2022 | ATC    | [Direct Access, High-Performance Memory Disaggregation with DirectCXL](https://www.usenix.org/conference/atc22/presentation/gouk)    |                                        |
| 2022 | ASPLOS | [Clio: A Hardware-Software Co-Designed Disaggregated Memory System](https://dl.acm.org/doi/10.1145/3503222.3507762)                  | [link](https://github.com/WukLab/Clio) |
| 2023 | ASPLOS | [Pond: CXL-Based Memory Pooling Systems for Cloud Platforms](https://dl.acm.org/doi/10.1145/3575693.3578835)                         | [link](https://github.com/vtess/Pond)  |


## Applications
| Year | Conf.    | Paper                                                                                                                                                                                                   | Code                                                           |
| ---- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| 2017 | HotNets  | [Tolerating Faults in Disaggregated Datacenters](https://dl.acm.org/doi/10.1145/3152434.3152447)                                                                                                        |                                                                |
| 2019 | WORD     | [The Serverless Data Center: Hardware Disaggregation Meets Serverless Computing](https://adept.eecs.berkeley.edu/papers/the-serverless-data-center-hardware-disaggregation-meets-serverless-computing/) |                                                                |
| 2020 | HotCloud | [Disaggregation and the Application](https://www.usenix.org/conference/hotcloud20/presentation/angel)                                                                                                   |                                                                |
| 2022 | EuroSys  | [Jiffy: Elastic Far-Memory for Stateful Serverless Analytics](https://dl.acm.org/doi/abs/10.1145/3492321.3527539)                                                                                       |                                                                |
| 2022 | ATC      | [JITServer: Disaggregated Caching JIT Compiler for JVM in the Cloud](https://www.usenix.org/conference/atc22/presentation/khrabrov)                                                                     | [link](https://github.com/AlexeyKhrabrov/jitserver-benchmarks) |
| 2023 | POMACS   | [Memtrade: Marketplace for Disaggregated Memory Clouds](https://dl.acm.org/doi/abs/10.1145/3589985?af=R)                                                                                                | [link](https://github.com/SymbioticLab/Memtrade)               |
| 2023 | VLDB     | [FlexChain: An Elastic Disaggregated Blockchain](https://www.vldb.org/pvldb/vol16/p23-wu.pdf)                                                                                                           |                                                                |
| 2023 | ATC      | [CXL-ANNS: Software-Hardware Collaborative Memory Disaggregation and Computation for Billion-Scale Approximate Nearest Neighbor Search](https://www.usenix.org/conference/atc23/presentation/jang)      |                                                                |
| 2023 | ATC      | [Overcoming the Memory Wall with CXL-Enabled SSDs](https://www.usenix.org/conference/atc23/presentation/yang-shao-peng)                                                                                 |                                                                |
| 2024 | ASPLOS   | [FaaSMem: Improving Memory Efficiency of Serverless Computing with Memory Pool Architecture](https://dl.acm.org/doi/pdf/10.1145/3620666.3651355)                                                        | [link](https://github.com/BarrinXu/FaaSMem)                    |
| 2024 | ATC      | [HydraRPC: RPC in the CXL Era](https://www.usenix.org/conference/atc24/presentation/ma)                                                                                                                 |                                                                |

# Industrial Practices
- [The Machine](https://www.hpl.hp.com/research/systems-research/themachine/)
- [Disaggregated Memory - In Pursuit of Scale and Efficiency](https://pmem.io/blog/2022/01/disaggregated-memory-in-pursuit-of-scale-and-efficiency/)
- [Compute Express Link: The Breakthrough CPU-to-Device Interconnect](https://www.computeexpresslink.org/)
- [Microsoft Azure Blazes the Disaggregated Memory Trail with ZNUMA](https://www.nextplatform.com/2022/07/11/microsoft-azure-blazes-the-disaggregated-memory-trail-with-znuma/)


---
# Contribute
This is an active repository and your contributions are always welcome! Do not hesitate to create pull requests.
