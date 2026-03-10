# Awesome TLA+ [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="tlaplus-logo.png" align="right" width="100" title="TLA+">](http://www.tlapl.us)


TLA+ is a formal specification and verification language to help engineers design, specify, reason about, and verify complex software and hardware systems. It is widely used to verify the algorithms in distributed systems.

## Contents

- [WebSites](#websites)
- [Discussions](#discussions)
- [Users](#users)
- [Tools](#tools)
- [Books](#books)
- [TLA+ blog posts and articles](#tla-blog-posts-and-articles)
- [Real-world specs](#real-world-specs-not-part-of-tla-examples)
- [TLA+ Video Resources](#tla-video-resources)
- [Scientific papers](#scientific-papers)
- [(University) courses teaching (with) TLA+](#university-courses-teaching-with-tla)

## WebSites

* Homepage: http://www.tlapl.us (https://lamport.azurewebsites.net/tla/tla.html)
* TLA+ Project: https://project.tlapl.us (https://github.com/tlaplus)
* TLA+ Community Modules: https://modules.tlapl.us/ (https://github.com/tlaplus/CommunityModules)
* TLA+ Examples: https://examples.tlapl.us  (https://github.com/tlaplus/Examples)
* Learn TLA+ (PlusCal): https://learntla.com/
* Writing Specs: https://writingspecs.com/ — Beginner-friendly intro to writing specs and TLA+ concepts; WIP, not comprehensive.

## Discussions

* google groups: https://groups.google.com/forum/#!forum/tlaplus
* reddit: https://www.reddit.com/r/tlaplus/
* twitter: https://twitter.com/tlaplus
* stackoverflow: https://stackoverflow.com/questions/tagged/tla%2b

## Users

* Microsoft
* [Atomix](https://github.com/atomix)
* [Informal Systems](https://informal.systems/): TLA+ for protocol specification, model checking, model-based testing, and security audits of blockchains
* [Open Networking Foundation](https://opennetworking.org)
* [Zilliqa Research](https://www.zilliqa.com)

## Tools

### Verification

* TLC: https://tools.tlapl.us (https://github.com/tlaplus/tlaplus)
* TLAPM: https://proofs.tlapl.us (https://github.com/tlaplus/tlapm)
* Apalache: https://apalache.informal.systems/

### IDEs

* VSCode-extension: https://github.com/tlaplus/vscode-tlaplus
* Toolbox (Eclipse based IDE): https://tools.tlapl.us (https://github.com/tlaplus/tlaplus) (no longer maintained)
* Jupyter notebook: https://github.com/kelvich/tlaplus_jupyter
* Emacs mode: https://github.com/ratish-punnoose/tla-mode
* Another Emacs mode: https://git.sdf.org/bch/tlamode/
* Intellij IDEA plugin: https://github.com/ocadaruma/tlaplus-intellij-plugin

### Misc

* Better-comments (VSCode): https://github.com/alygin/better-comments
* TLC command-line wrapper: https://github.com/pmer/tla-bin

### Parsers

* [SANY](https://github.com/tlaplus/tlaplus/tree/master/tlatools/org.lamport.tlatools/src/tla2sany) (Syntactic Analyzer): A parser and syntax checker for TLA+ specifications
* [TLAPS](https://github.com/tlaplus/tlapm): A system for mechanically checking proofs written in TLA+
* [tree-sitter-tlaplus](https://github.com/tlaplus-community/tree-sitter-tlaplus): A tree-sitter grammar for TLA⁺ and PlusCal 
* [tlapy](https://github.com/johnyf/tlapy): A collection of Python tools for working with TLA+ specifications

## Books

* [Specifying Systems](https://lamport.azurewebsites.net/tla/book.html) (freely available)
* [Hyperbook](https://lamport.azurewebsites.net/tla/hyperbook.html) (freely available)
* [Practical TLA+](https://www.apress.com/gp/book/9781484238288)
* [TLA+ in Practice and Theory](https://pron.github.io/posts/tlaplus_part1) (freely available)

## TLA+ blog posts and articles


| name | description |  
| --- | --- | 
| [AWS and TLA+](https://lamport.azurewebsites.net/tla/amazon-excerpt.html) | Use of Formal Methods at Amazon Web Services |
| [Batch Installer](https://medium.com/espark-engineering-blog/formal-methods-in-practice-8f20d72bce4f) | Sending async batches of commands. |
| [Redux](https://www.hillelwayne.com/tla-redux/) | Redux reducers with verifying a temporal property. |
| [Zero Downtime Deployments](https://www.hillelwayne.com/modeling-deployments/) | A simple model of a deploying new code to servers where at least one server is always available to clients, and all available servers show the same code version. |
| [Trading Algorithm](https://www.linkedin.com/pulse/lamports-tla-spec-testing-why-youre-using-nira-amit/) | Trading boths executing trades in a simulated market, showing how it’s susceptible to flash crashes. |
| [Detecting Linked-List Cycles](https://lorinhochstein.wordpress.com/2017/10/16/the-tortoise-and-the-hare-in-tla/) | Finding cycles in linked lists. |
| [Replicated Storage](http://muratbuffalo.blogspot.com/2016/11/modeling-replicated-storage-system-in.html) | Replicated storage system with a quorum. |
| [Rate Limiter](https://old.learntla.com/concurrency/example/) | Independent workers hitting a rate-limited API. |
| [Thread Pool](http://www.cs.unh.edu/~charpov/programming-tlabuffer.html) | Multiple reader and writer threads sharing a bounded queue, discovering deadlocks. |
| [Bank Transfer](https://learntla.com/introduction/example/) | Specifying a bank transfer with overdraft protection. |
| [Finding bugs in systems through formalization](https://andy.hammerhartes.de/finding-bugs-in-systems-through-formalization.html) | Ensuring distributed jobs go from “pending” to “completed”. |
| [Building A "Simple" Distributed System](https://jack-vanlightly.com/blog/2019/1/27/building-a-simple-distributed-system-formal-verification) | Rebalanser - distributed resource allocation library. |
| [Train Sidings – A TLA+ Example](https://www.heinbockel.eu/2019/12/08/train-sidings-a-tla-example/) | Railroad line where two trains can pass each other. |
| [Azure Cosmos TLA+ specifications](https://github.com/Azure/azure-cosmos-tla) | The consistency levels offered by Azure Cosmos DB (also see [Murat Demirbas' talk](https://www.microsoft.com/en-us/research/video/tla-specifications-of-the-consistency-guarantees-provided-by-cosmos-db/)). |
| [Modeling Streamlet in TLA+](http://muratbuffalo.blogspot.com/2020/07/modeling-streamlet-in-tla.html) | A PlusCal spec of a crash fault-tolerant variant of the Streamlet blockchain protocol. |
| [Understanding Apache Hudi's Consistency Model](https://hudi.apache.org/blog/2024/04/24/understanding-apache-hudi-consistency-model-part-3) | TLA+ specification and model checking of Hudi's consistency model |
| [Using TLA+ in the Real World to Understand a Glibc Bug](https://probablydance.com/2020/10/31/using-tla-in-the-real-world-to-understand-a-glibc-bug/) | Lifting code to the specification level to study a complex concurrency bug. |
| [tla-specs](https://github.com/Alexander-N/tla-specs) | Collection of documented TLA+ explorations. |

## Real-world specs (not part of [TLA+ Examples](https://github.com/tlaplus/examples))

| name | description | related resources |
| --- | --- | --- |
| [Linux kernel](https://kernel.googlesource.com/pub/scm/linux/kernel/git/cmarinas/kernel-tla) | TLA+ specs for kernel/arm64 work, including modeling qrwlock, qspinlock, and parts of arm64 | [Formal Methods for Kernel Hackers (LPC 2018)](https://lpc.events/event/2/contributions/60/) · [LPC 2018 slides (PDF)](https://lpc.events/event/2/contributions/60/attachments/18/42/FormalMethodsPlumbers2018.pdf) · [LPC 2018 video](https://www.youtube.com/watch?v=qeUHlXOBXmg) · [rs3lab/kernel-tla (rqspinlock)](https://github.com/rs3lab/kernel-tla) · [A new type of spinlock for BPF (LWN)](https://lwn.net/Articles/1016674/) |
| [glibc pthread_cond](https://sourceware.org/bugzilla/show_bug.cgi?id=25847) | TLA+ used for investigating and fixing the pthread condition-variable lost-wakeup bug | [skarupke/glibc_tla_plus](https://github.com/skarupke/glibc_tla_plus) · [Using TLA+ to Fix a Very Difficult glibc Bug (C++Now 2025 video)](https://www.youtube.com/watch?v=Brgfp7_OP2c) · [glibc patch series](https://sourceware.org/pipermail/libc-alpha/2023-May/147837.html) |
| [Elasticsearch Formal Models](https://github.com/elastic/elasticsearch-formal-models) | TLA+ models of core Elasticsearch algorithms, including replication and replica engine behavior | [Using TLA+ for fun and profit in the development of Elasticsearch (TLA+ Conf 2019)](https://conf.tlapl.us/2019/yannickwelsch/) · [Slides (PPTX)](https://conf.tlapl.us/06_-_TLAConf19_-_Yannick_Welsch_-_Using_TLA_for_fun_and_profit_in_the_development_of_Elasticsearch.pptx) |
| [etcd-io/raft](https://github.com/etcd-io/raft/issues/111) | TLA+ spec and trace-validation work for the Raft algorithm as implemented by etcd | [Runtime Protocol Refinement Checking for etcd-raft](https://medium.com/princeton-systems-course/runtime-protocol-refinement-checking-for-etcd-raft-a2cb4710c3b4) · [Validating System Executions with the TLA+ Tools (TLA+ Conf 2024 slides)](https://conf.tlapl.us/2024/MarkusAKuppe-ValidatingSystemExecutionsWithTheTLAPlusTools.pdf) · [Validating Traces of Distributed Programs Against TLA+ Specifications](https://arxiv.org/html/2404.16075v2) |
| [TLA+ in TIDB](https://github.com/pingcap/tla-plus) | verify the distributed consensus algorithm : Raft & the implementation of distributed transaction. | |
| [Servo web engine](https://github.com/servo/servo) | TLA+ used to find and fix concurrency bugs in Servo's event-loop | [Re-fixing Servo's event-loop (blog)](https://medium.com/@polyglot_factotum/re-fixing-servos-event-loop-e00bdf267385) · [GOSIM China 2024 talk (video)](https://www.youtube.com/watch?v=1c9sHaEXQak) · [Slides (PDF)](https://github.com/gterzian/taming-concurrency/blob/main/Greg%20Terzian%20-%20GOSIM_China_2024.pdf) |
| [Apache Kafka KRaft](https://issues.apache.org/jira/browse/KAFKA-17644) | TLA+ verification/spec work for KRaft features such as pre-vote and reconfiguration; TLA+ model also used to find bugs | [Vanlightly/kafka-tlaplus](https://github.com/Vanlightly/kafka-tlaplus) ·  [A Primer on Formal Verification and TLA+](https://jack-vanlightly.com/blog/2023/10/10/a-primer-on-formal-verification-and-tla) · [Detecting Bugs in Data Infrastructure using Formal Methods](https://medium.com/splunk-maas/detecting-bugs-in-data-infrastructure-using-formal-methods-704fde527c58) · [Verifying Kafka Transactions diary](https://jack-vanlightly.com/analyses) · [Distributed Systems Showdown: TLA+ vs Real Code (Hydra Conf slides)](https://assets.ctfassets.net/oxjq45e8ilak/KU9K9OecXlAig5n5cVnYQ/e05f158e22e2a34722918b01f8204472/Jack_Vanlightly_Distributed_systems_showdown__TLA_vs_real_code_2021_06_15_14_08_33.pdf) |
| [Apache Kafka Replication](https://github.com/hachikuji/kafka-specification) | TLA+ specification of the Kafka ISR-based replication protocol, including KIP-101, KIP-279, and KIP-320; model checking revealed weaknesses in proposed designs | [KIP-320 wiki (references TLA+ spec)](https://cwiki.apache.org/confluence/display/KAFKA/KIP-320%3A+Allow+fetchers+to+detect+and+handle+log+truncation) |
| [MongoDB Replication](https://github.com/visualzhou/mongo-repl-tla) | TLA+ specs and trace-checking for MongoDB replication behavior/protocols | [Fixing a MongoDB Replication Protocol Bug with TLA+ (TLA+ Conf 2019)](https://conf.tlapl.us/2019/williamschultz/) · [TLA+ Conf 2019 video](https://www.youtube.com/watch?v=x9zSynTfLDE) · [Rapid Prototyping a Logless Reconfiguration Protocol (MongoDB blog)](https://www.mongodb.com/company/blog/technical/rapid-prototyping-safe-logless-reconfiguration-protocol-mongodb-tla-plus) · [Modular Verification of MongoDB Transactions](https://muratbuffalo.blogspot.com/2025/05/modular-verification-of-mongodb.html) · [Logless Dynamic Reconfiguration (paper)](https://arxiv.org/pdf/2102.11960v1) · [eXtreme Modelling in Practice (paper)](https://arxiv.org/abs/2006.00915) · [eXtreme Modelling in Practice (video)](https://www.youtube.com/watch?v=IIGzXX72weQ) |
| [Signal SVR2](https://github.com/signalapp/SecureValueRecovery2/blob/main/docs/svr2.tla) | TLA+ specification of the Raft-based consensus and self-healing protocol for Signal's Secure Value Recovery service, which stores PIN-protected secrets across multi-replica SGX enclaves | |
| [Xen vchan](https://github.com/talex5/spec-vchan) | TLA+ specification of the Xen vchan inter-domain communication protocol | [Using TLA+ to Understand Xen Vchan (blog)](http://roscidus.com/blog/blog/2019/01/01/using-tla-plus-to-understand-xen-vchan/) |
| [Ceph Consensus](https://github.com/afonsonf/ceph-consensus-spec) | TLA+ specification of the Ceph consensus algorithm (based on Paxos), derived from the actual [Paxos.cc](https://github.com/ceph/ceph/blob/master/src/mon/Paxos.cc) source code | [Formal Verification of the Ceph Consensus Algorithm (thesis)](https://hdl.handle.net/10216/139563) · [Formal Verification and Visualization (paper)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4437917) |
| [Raft Consensus Algorithm](https://github.com/ongardie/raft.tla) | TLA+ specification of the Raft consensus algorithm | |
| [Raft Consensus Algorithm w/ Client](https://github.com/atomix/atomix-tlaplus/tree/master/Raft) | TLA+ specification of the Raft consensus algorithm and linearizable client | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) |
| [Sequentially Consistent Raft Streams](https://github.com/atomix/atomix-tlaplus/blob/master/ClientSequencer/ClientSequencer.tla) | TLA+ specification of an algorithm for sequentially consistent streaming responses from a Raft cluster | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) |
| [tendermint-rs](https://github.com/cometbft/tendermint-rs) | Rust Tendermint implementation with TLA+ specifications | [Verification Driven Development for Tendermint and IBC](https://informal.systems/blog/q1-tech-update) · [How TLA+ and Apalache Helped Us Design the Tendermint Light Client (video)](https://www.youtube.com/watch?v=K2o8znf384w) · [A Tendermint Light Client (paper)](https://arxiv.org/pdf/2010.07031) |
| [TendermintAcc](https://github.com/tendermint/spec/blob/master/spec/light-client/accountability/TendermintAcc_004_draft.tla) | TLA+ specification of Tendermint consensus tuned for safety and fork accountability properties, including an inductive invariant | [Verification Driven Development for Tendermint and IBC](https://informal.systems/blog/q1-tech-update) · [Model-based Testing with TLA+ and Apalache (TLA+ Conf 2020 slides)](https://conf.tlapl.us/2020/09-Kuprianov_and_Konnov-Model-based_testing_with_TLA_+_and_Apalache.pdf) |
| [Tendermint Light Client](https://github.com/tendermint/spec/blob/master/spec/light-client/verification/Lightclient_003_draft.tla) | TLA+ specification of the Tendermint light client | [How TLA+ and Apalache Helped Us Design the Tendermint Light Client (video)](https://www.youtube.com/watch?v=K2o8znf384w) · [Model-based Testing with TLA+ and Apalache (TLA+ Conf 2020 slides)](https://conf.tlapl.us/2020/09-Kuprianov_and_Konnov-Model-based_testing_with_TLA_+_and_Apalache.pdf) · [A Tendermint Light Client (paper)](https://arxiv.org/pdf/2010.07031) |
| [celestia-tendermint-rs](https://github.com/celestiaorg/celestia-tendermint-rs) | Celestia fork of tendermint-rs, a Tendermint client framework with TLA+ specifications | |
| [cometbft-rs](https://github.com/cometbft/cometbft-rs) | Rust CometBFT client framework with TLA+ specifications | |
| [DualTor SONiC Protocol](https://github.com/GerardoGran/dualtor-tla-verification) | TLA+ specification of the DualTor Standby/Active protocol for SONiC Top-of-Rack switches, verifying correctness of MUX failover and state machine coordination | |
| [Apache BookKeeper](https://github.com/Vanlightly/bookkeeper-tlaplus) | TLA+ specification of the BookKeeper replication protocol; found data-loss bugs in fencing and recovery | |
| [EPaxos](https://github.com/efficient/epaxos) | TLA+ specs for the Egalitarian Paxos protocol, including `EgalitarianPaxos.tla` | [EPaxos project page](https://efficient.github.io/epaxos/) · [EPaxos Revisited (NSDI'21)](https://www.usenix.org/conference/nsdi21/presentation/tollman) · [On the Correctness of Egalitarian Paxos](https://arxiv.org/pdf/1906.10917) · [Making Democracy Work: Fixing and Simplifying EPaxos (OPODIS'25)](https://software.imdea.org/~gotsman/papers/epaxos-opodis25.pdf) |
| [SWIM Membership Protocol](https://github.com/atomix/atomix-tlaplus/blob/master/SWIM/SWIM.tla) | TLA+ specification of the Scalable Weakly-consistent Infection-style Membership (SWIM) protocol | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) |
| [Distributed Lock](https://github.com/kuujo/onos-tlaplus/blob/master/DistributedLock/DistributedLock.tla) | TLA+ specification of a replicated state machine for distributed locking | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) · [Distributed Systems in ONOS with Atomix 3 (ONF Connect 2018 slides)](https://opennetworking.org/wp-content/uploads/2018/12/Distributed-Systems-in-ONOS-with-Atomix-3.pdf) · [ONF Connect 2018 video](https://www.youtube.com/watch?v=PwWe4rEN2Tk) |
| [Multi-primary Replication Protocol](https://github.com/kuujo/onos-tlaplus/blob/master/FlowRuleStore/FlowRuleStore.tla) | TLA+ specification of a multi-primary replication protocol created for [ONOS](https://opennetworking.org/onos/) | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) · [Distributed Systems in ONOS with Atomix 3 (ONF Connect 2018 slides)](https://opennetworking.org/wp-content/uploads/2018/12/Distributed-Systems-in-ONOS-with-Atomix-3.pdf) |
| [P4Runtime Protocol Specification](https://github.com/kuujo/onos-tlaplus/tree/master/P4RuntimeElection) | TLA+ specification of the [P4Runtime](https://github.com/p4lang/p4runtime) API that was used to demonstrate and fix safety violations in the protocol | [Bridging the Verifiability Gap (TLA+ Conf 2020 slides)](http://conf.tlapl.us/2020/13-Jordan_Halterman_Bridging_the_verifiability_gap-Slides.pdf) |
| [Flexible Paxos](https://github.com/fpaxos/fpaxos-tlaplus) | TLA+ specification of Flexible Paxos, which revisits quorum intersection requirements in Paxos | [Flexible Paxos paper](https://arxiv.org/pdf/1608.06696v1.pdf) · [Flexible Paxos (the morning paper)](https://blog.acolyer.org/2016/09/27/flexible-paxos-quorum-intersection-revisited/) · [Dr TLA+ Series: Flexible Paxos (video)](https://www.youtube.com/watch?v=LX-WK8EmoFE) |
| [Viewstamped Replication](https://github.com/Vanlightly/vsr-tlaplus) | TLA+ specifications of Viewstamped Replication; found a state transfer defect in the "VR Revisited" paper | [VR Revisited analysis series (Jack Vanlightly)](https://jack-vanlightly.com/analyses/2022/12/20/paper-vr-revisited-view-change-questions-part1) |
| [CBC Casper](https://github.com/crytic/whipstaff) | TLA+ and PlusCal specification of the CBC Casper consensus protocols (binary consensus) by Trail of Bits | [Formal Analysis of the CBC Casper Consensus Algorithm with TLA+ (Trail of Bits blog)](https://blog.trailofbits.com/2019/10/25/formal-analysis-of-the-cbc-casper-consensus-algorithm-with-tla/) · [CBC Casper paper](https://github.com/cbc-casper/cbc-casper-paper) |
| [Event Driven HotStuff](https://github.com/ausimnull/EDHotStuff) | PlusCal specification of the Event Driven HotStuff BFT consensus algorithm | [discuss.tlapl.us thread](https://discuss.tlapl.us/msg03461.html) · [HotStuff: BFT Consensus in the Lens of Blockchain (paper)](https://arxiv.org/abs/1803.05069) |
| [TezEdge](https://github.com/tezedge/tezedge-specification) | TLA+ specs and models for the TezEdge node's p2p overlay network, shell, and consensus layers (Tezos blockchain) | |
| [Succinct Atomic Swap](https://github.com/dgpv/SASwap_TLAplus_spec) | TLA+ specification of the Succinct Atomic Swap (SAS) Bitcoin smart contract protocol, verifying safety invariants and temporal properties | [SAS protocol description (Ruben Somsen)](https://gist.github.com/RubenSomsen/8853a66a64825716f51b409be528355f) · [SAS presentation (video)](https://youtu.be/TlCxpdNScCA) · [bitcoin-dev mailing list post](https://gnusha.org/pi/bitcoindev/CAPv7TjZGBbf6f1y49HLFD2eNiP5d4e+=dFGqiMFs6jaeYyH-NQ@mail.gmail.com/) |
| [Katzenpost](https://github.com/katzenpost/formal_specifications) | TLA+ and Promela specifications of protocols for the Katzenpost mixnet anonymous communication network, including the directory authority voting protocol | [discuss.tlapl.us thread](https://discuss.tlapl.us/msg05499.html) |
| [Generating All Combinations and Partitions](https://github.com/tlaplus/tlaplus/blob/master/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla) | Spec of an [algorithm](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla#L28-L33) in Knuth's TAOCP. It's [Java implemenation](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.java#L513-L588) is used by TLC. | |
| [TaskScheduler](https://github.com/ubisoft/task-scheduler/tree/main/tla) | TLA+ specifications by Ubisoft validating lock-free MPSC/MCSP queue algorithms in a concurrent task scheduler, ensuring absence of deadlocks, reordering, and task loss | |
| [lfest-rs](https://github.com/MathisWellmann/lfest-rs/blob/main/lfest.tla) | TLA+ specifications for a leveraged futures exchange simulator, verifying order execution and margin calculation logic | |
| [Just-in-Time Paxos](https://github.com/kuujo/just-in-time-paxos) | TLA+ specification of an experimental consensus protocol that relies on high-precision clock synchronization to order proposals | |
| [Spire Consensus](https://github.com/obsidiandynamics/spire-tla) | TLA+ specification and TLAPS machine-verifiable proof of the Spire single-value and Spanning Privilege (SP) multi-value consensus algorithms | [Spire pre-print (TechRxiv)](https://www.techrxiv.org/articles/preprint/Spire_A_Cooperative_Phase-Symmetric_Solution_to_Distributed_Consensus/13531136) |
| [zig-rcsp](https://github.com/yrashk/zig-rcsp/blob/master/rcsp.tla) | TLA+ specification of a reference-counted shared pointer algorithm for Zig, verifying correctness of concurrent acquire/release operations | |

## TLA+ Video Resources

* [The TLA+ Video Course](http://lamport.azurewebsites.net/video/videos.html)
* [Dr TLA+](https://github.com/tlaplus/DrTLAPlus)
* [TLA+ Community Meeting 2018](https://www.youtube.com/playlist?list=PLWLcqZLzY8u_3mDg2cHmduA5wl4J6hNX2)
* [TLA+ conf 2019](https://www.youtube.com/playlist?list=PLWLcqZLzY8u_Osnz-YPOVrptG1ys73OkR)
* [Debugging software designs using testable pseudo-code (TLA+)](https://www.youtube.com/watch?v=LAEXHua4MQQ)
* [The practice and Theory of TLA+](https://www.youtube.com/watch?v=15uy9Ga-14I)
* [Tackling Concurrency Bugs with TLA+](https://www.youtube.com/watch?v=_9B__0S21y8)
* [Formal verification applied](https://www.youtube.com/watch?v=l9XZYI3jta0)
* [Thinking Above the Code](https://www.youtube.com/watch?v=-4Yp3j_jk8Q)
* [Building confidence in concurrent code with a model checker (aka TLA+ for programmers)](https://youtu.be/tqwcz-Yt9gQ)

## Scientific papers

* Search [Arxiv](http://search.arxiv.org:8081/?query=tla&in=grp_cs), [DBLP](https://dblp.uni-trier.de/search?q=tla), ...

### Theory

* [Lamport's TLA+ publications](https://lamport.azurewebsites.net/tla/papers.html?back-link=more-stuff.html)
* [Stephan Merz's publications](https://members.loria.fr/SMerz/papers.html)

### Tools

* [Model Checking TLA+ Specifications](http://link.springer.com/10.1007/3-540-48153-2_6)
* [Verifying Safety Properties with the TLA+ Proof System](http://link.springer.com/10.1007/978-3-642-14203-1_12)
* [TLA+ model checking made symbolic](https://dl.acm.org/doi/10.1145/3360549)
* [The TLA+ Toolbox](https://arxiv.org/abs/1912.10633)

### Application

* [eXtreme Modelling in Practice](https://arxiv.org/abs/2006.00915)
* [Specifying and Model Checking Workflows of Single Page Applications with TLA+](https://arxiv.org/abs/2005.05627)

## (University) courses teaching (with) TLA+

* [EECS4315 Mission-Critical Systems (Winter 2023 - Section Z)](https://www.eecs.yorku.ca/~jackie/teaching/lectures/index.html#EECS4315_W23)
* [SUNY Buffalo: CSE 4/586 Distributed Systems](https://cse.buffalo.edu/~demirbas/course.pdf)  ([Notes](http://muratbuffalo.blogspot.com/2015/01/my-experience-with-using-tla-in.html))
* [Portland State: CS410/510 Practical Specification and Verification](https://web.cecs.pdx.edu/~apt/cs510spec/)
* [University of Wellington: SWEN421 - Formal Software Engineering](https://ecs.wgtn.ac.nz/Courses/SWEN421_2020T1/CourseOutline)
* [Bordeaux INP: IF311 Formal Software Design](http://herbrete.vvv.enseirb-matmeca.fr/IF311/)
* [TU Kaiserslautern: Programming Distributed Systems](https://pl.cs.uni-kl.de/homepage/de/teaching/ss19/progdist/)
* [University of Iowa: CS5620f15 Distributed Systems and Algorithms](https://weblog.cs.uiowa.edu/cs5620f15/)
* [University of Tartu: Systems Modelling](https://courses.cs.ut.ee/2019/SM/)
* [University of Colorado: Distributed Systems Verification](https://gowthamk.github.io/csci7000_s21/)
* [University of California, San Diego: CSE 128 Spring 2005 Concurrency](https://cseweb.ucsd.edu/classes/sp05/cse128/)
