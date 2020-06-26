# awesome-tlaplus

TLA+ is a formal specification and verification language to help engineers design, specify, reason about, and verify complex software and hardware systems. It is widely used to verify the algorithms in distributed systems.

## WebSites

* Homepage: https://lamport.azurewebsites.net/tla/tla.html
* TLA+ Tools: https://github.com/tlaplus
* TLA Proof System: https://tla.msr-inria.inria.fr/tlaps/content/Home.html
* TLA+ example: https://github.com/tlaplus/Examples
* Learn TLA+: https://learntla.com/introduction/
* News Aggregator: https://wall.tlapl.us

## Discussions

* google groups: https://groups.google.com/forum/#!forum/tlaplus
* reddit: https://www.reddit.com/r/tlaplus/
* twitter: https://twitter.com/tlaplus

## Tools

* Toolbox & TLC: https://github.com/tlaplus/tlaplus
* TLAPM: https://github.com/tlaplus/tlapm
* Apalache: https://github.com/konnov/apalache
* VSCode-extension: https://github.com/alygin/vscode-tlaplus
* Jupyter notebook: https://github.com/kelvich/tlaplus_jupyter
* TLC command-line wrapper: https://github.com/pmer/tla-bin

## Books

* [Specifying Systems](https://lamport.azurewebsites.net/tla/book.html) (freely available)
* [Hyperbook](https://lamport.azurewebsites.net/tla/hyperbook.html) (freely available)
* [Practical TLA+](https://www.apress.com/gp/book/9781484238288)
* [TLA+ in Practice and Theory](https://pron.github.io/posts/tlaplus_part1) (freely available)

## TLA+ blog posts and articles


| name | description |  
| --- | --- | 
| [AWS and TLA+](http://lamport.azurewebsites.net/tla/amazon.html) | Use of Formal Methods at Amazon Web Services |
| [Batch Installer](https://medium.com/espark-engineering-blog/formal-methods-in-practice-8f20d72bce4f) | Sending async batches of commands. |
| [Redux](https://www.hillelwayne.com/post/tla-redux/) | Redux reducers with verifying a temporal property. |
| [Zero Downtime Deployments](https://www.hillelwayne.com/post/modeling-deployments/) | A simple model of a deploying new code to servers where at least one server is always available to clients, and all available servers show the same code version. |
| [Trading Algorithm](https://www.linkedin.com/pulse/lamports-tla-spec-testing-why-youre-using-nira-amit/) | Trading boths executing trades in a simulated market, showing how it’s susceptible to flash crashes. |
| [Detecting Linked-List Cycles](https://lorinhochstein.wordpress.com/2017/10/16/the-tortoise-and-the-hare-in-tla/) | Finding cycles in linked lists. |
| [Replicated Storage](http://muratbuffalo.blogspot.com/2016/11/modeling-replicated-storage-system-in.html) | Replicated storage system with a quorum. |
| [Rate Limiter](https://learntla.com/concurrency/example/) | Independent workers hitting a rate-limited API. |
| [Thread Pool](http://www.cs.unh.edu/~charpov/programming-tlabuffer.html) | Multiple reader and writer threads sharing a bounded queue, discovering deadlocks. |
| [Bank Transfer](https://learntla.com/introduction/example/) | Specifying a bank transfer with overdraft protection. |
| [Finding bugs in systems through formalization](https://andy.hammerhartes.de/finding-bugs-in-systems-through-formalization.html) | Ensuring distributed jobs go from “pending” to “completed”. |
| [Building A "Simple" Distributed System](https://jack-vanlightly.com/blog/2019/1/27/building-a-simple-distributed-system-formal-verification) | Rebalanser - distributed resource allocation library. |
| [Train Sidings – A TLA+ Example](https://www.heinbockel.eu/2019/12/08/train-sidings-a-tla-example/) | Railroad line where two trains can pass each other. |
| [Azure Cosmos TLA+ specifications](https://github.com/Azure/azure-cosmos-tla) | The consistency levels offered by Azure Cosmos DB (also see [Murat Demirbas' talk](https://www.microsoft.com/en-us/research/video/tla-specifications-of-the-consistency-guarantees-provided-by-cosmos-db/)). |


## Real-world specs (not part of [TLA+ Examples](https://github.com/tlaplus/examples))

| name | description |  
| --- | --- | 
| [TLA+ in TIDB](https://github.com/pingcap/tla-plus) | verify the distributed consensus algorithm : Raft & the implementation of distributed transaction. |
| [Generating All Combinations and Partitions](https://github.com/tlaplus/tlaplus/blob/master/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla) | Spec of an [algorithm](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.tla#L28-L33) in Knuth's TAOCP. It's [Java implemenation](https://github.com/tlaplus/tlaplus/blob/f8f057f3e019026e478369c2b82e20677c920335/tlatools/org.lamport.tlatools/src/tlc2/value/impl/SubsetValue.java#L513-L588) is used by TLC. |

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

### (University) courses teaching (with) TLA+

* [SUNY Buffalo: CSE 4/586 Distributed Systems](https://cse.buffalo.edu/~demirbas/course.pdf)  ([Notes](http://muratbuffalo.blogspot.com/2015/01/my-experience-with-using-tla-in.html))
* [Portland State: CS410/510 Practical Specification and Verification](https://web.cecs.pdx.edu/~apt/cs510spec/)
* [University of Wellington: SWEN421 - Formal Software Engineering](https://ecs.wgtn.ac.nz/Courses/SWEN421_2020T1/CourseOutline)
