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

* Homepage: http://www.tlapl.us  (https://lamport.azurewebsites.net/tla/tla.html)
* TLA+ Project: https://project.tlapl.us  (https://github.com/tlaplus)
* TLA+ Community Modules: https://modules.tlapl.us/ (https://github.com/tlaplus/CommunityModules)
* TLA+ Examples: https://examples.tlapl.us  (https://github.com/tlaplus/Examples)
* Learn TLA+ (PlusCal): https://learntla.com/ (https://learntla.com/)
* News Aggregator: https://wall.tlapl.us

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

* Toolbox: https://tools.tlapl.us (https://github.com/tlaplus/tlaplus)
* VSCode-extension: https://github.com/alygin/vscode-tlaplus
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
| [Using TLA+ in the Real World to Understand a Glibc Bug](https://probablydance.com/2020/10/31/using-tla-in-the-real-world-to-understand-a-glibc-bug/) | Lifting code to the specification level to study a complex concurrency bug. |
| [tla-specs](https://github.com/Alexander-N/tla-specs) | Collection of documented TLA+ explorations. |

## Real-world specs (not part of [TLA+ Examples](https://github.com/tlaplus/examples))

| name | description |  
| --- | --- | 
| [Distributed Lock](https://github.com/kuujo/onos-tlaplus/blob/master/DistributedLock/DistributedLock.tla) | TLA+ specification of a replicated state machine for distributed locking |
| [Generating All Combinations and Partitions](https://github.com/tlaplus/tlaplus/blob/master/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla) | Spec of an [algorithm](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla#L28-L33) in Knuth's TAOCP. It's [Java implemenation](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.java#L513-L588) is used by TLC. |
| [Just-in-Time Paxos](https://github.com/kuujo/just-in-time-paxos) | TLA+ specification of an experimental consensus protocol that relies on high-precision clock synchronization to order proposals |
| [Multi-primary Replication Protocol](https://github.com/kuujo/onos-tlaplus/blob/master/FlowRuleStore/FlowRuleStore.tla) | TLA+ specification of a multi-primary replication protocol created for [ONOS](https://opennetworking.org/onos/) |
| [P4Runtime Protocol Specification](https://github.com/kuujo/onos-tlaplus/tree/master/P4RuntimeElection) | TLA+ specification of the [P4Runtime](https://github.com/p4lang/p4runtime) API that was used to demonstrate and fix safety violations in the protocol |
| [Raft Consensus Algorithm](https://github.com/ongardie/raft.tla) | TLA+ specification of the Raft consensus algorithm |
| [Raft Consensus Algorithm w/ Client](https://github.com/atomix/atomix-tlaplus/tree/master/Raft) | TLA+ specification of the Raft consensus algorithm and linearizable client |
| [Sequentially Consistent Raft Streams](https://github.com/atomix/atomix-tlaplus/blob/master/ClientSequencer/ClientSequencer.tla) | TLA+ specification of an algorithm for sequentially consistent streaming responses from a Raft cluster |
| [SWIM Membership Protocol](https://github.com/atomix/atomix-tlaplus/blob/master/SWIM/SWIM.tla) | TLA+ specification of the Scalable Weakly-consistent Infection-style Membership (SWIM) protocol |
| [TendermintAcc](https://github.com/tendermint/spec/blob/master/spec/light-client/accountability/TendermintAcc_004_draft.tla) | TLA+ specification of Tendermint consensus tuned for safety and fork accountability properties, including an inductive invariant | 
| [Tendermint Light Client](https://github.com/tendermint/spec/blob/master/spec/light-client/verification/Lightclient_003_draft.tla) | TLA+ specification of the Tendermint light client | 
| [TLA+ in TIDB](https://github.com/pingcap/tla-plus) | verify the distributed consensus algorithm : Raft & the implementation of distributed transaction. |

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
