# Graph-Computing-Papers
This is a project to collect and share related papers on graph processing by the iDC-NEU team. Papers can be systematic or algorithmic. As long as you feel fruitful, you can share them with us! Please add papers in the order of paper name, published conference/journal, paper link and code link(if open source).
# Content
- [Disk-based Graph Processing Systems](#Disk-based-Graph-Processing-System)
- [Graph Processing System Paper](#Graph-Processing-System-Paper)
  
  - [Static Graph Processing System](#Static-Graph-Processing-System)
  - [Dynamic Graph Processing System](#Dynamic-Graph-Processing-System)
  
- [GPU/FPGA-Graph Processing System Paper](#GPU/FPGA-Graph-Processing-System-Paper)

  - [Static Graph Processing System](#GPU/FPGA-Static-Graph-Processing-System)
  - [Dynamic Graph Processing System](#GPU/FPGA-Dynamic-Graph-Processing-System)

- [Graph Processing  Algorithmic Paper](#GNN-Algorithmic-Paper)

# <span id = "Disk-based-Graph-Processing-System">Disk-based Graph Processing System</span>

GraphChi:Large-Scale Graph Computation on Just a PC. Kyrola, Aapo, Guy Blelloch, and Carlos Guestrin. 10th USENIX Symposium on Operating Systems Design and Implementation (OSDI 12). 2012.

X-stream: Edge-centric graph processing using streaming partitions. Roy, Amitabha, Ivo Mihailovic, and Willy Zwaenepoel. Proceedings of the Twenty-Fourth ACM Symposium on Operating Systems Principles. 2013.

GridGraph: Large-Scale Graph Processing on a Single Machine Using 2-Level Hierarchical Partitioning. Zhu, Xiaowei, Wentao Han, and Wenguang Chen. 2015 USENIX Annual Technical Conference. 2015.

TurboGraph: a fast parallel graph engine handling billion-scale graphs in a single PC. Han, Wook-Shin, et al.  Proceedings of the 19th ACM SIGKDD international conference on Knowledge discovery and data mining. 2013.

FlashGraph: Processing {Billion-Node} Graphs on an Array of Commodity SSDs. Zheng, Da, Disa Mhembere, Randal Burns, Joshua Vogelstein, Carey E. Priebe, and Alexander S. Szalay. In 13th USENIX Conference on File and Storage Technologies, 2015.

Chaos: Scale-out graph processing from secondary storage. Roy, Amitabha, Laurent Bindschaedler, Jasmina Malicevic, and Willy Zwaenepoel. In Proceedings of the 25th Symposium on Operating Systems Principles, pp. 410-424. 2015.

# <span id = "Graph-Processing-System-Paper">Graph Processing System Paper</span>
## <span id = "Static-Graph-Processing-System">Static Graph Processing System</span>
**2012**

1. PowerGraph: Distributed Graph-Parallel Computation on Natural Graphs. [[OSDI 2012](https://dl.acm.org/doi/proceedings/10.5555/2387880)] [[paper]](https://dl.acm.org/doi/10.5555/2387880.2387883)

**2016**

1. Gemini: A Computation-Centric Distributed Graph Processing System. [OSDI 2016] [[paper](https://dl.acm.org/doi/10.5555/3026877.3026901)] [[code](https://github.com/thu-pacman/GeminiGraph)] [[slides](https://www.usenix.org/sites/default/files/conference/protected-files/osdi16_slides_zhu.pdf)]
2. GRAPE: parallelizing sequential graph computations.  [OSDI 2016] [[paper](https://dl.acm.org/doi/10.14778/3137765.3137801)] [[code](https://github.com/alibaba/libgrape-lite)]



## <span id = "Dynamic-Graph-Processing-System">Dynamic Graph Processing System</span>

**2012**

1. GraphInc: Facilitating real-time graph mining.  [CloudDB 2012] [[paper](https://dl.acm.org/doi/10.1145/2390021.2390023)] [code]

**2016**

1. GraphIn: An Online High Performance Incremental Graph Processing Framework.  [2016] [[paper](https://dl.acm.org/doi/10.1007/978-3-319-43659-3_24)] [code]
2. Tornado: A System For Real-Time Iterative Analysis Over Evolving Data.  [SIGMOD 2016] [[paper](https://dl.acm.org/doi/epdf/10.1145/2882903.2882950)] [code]

**2017**

1. KickStarter: Fast and Accurate Computations on Streaming Graphs via Trimmed Approximations.  [ASPLOS  2017] [[paper](https://dl.acm.org/doi/10.1145/3037697.3037748)] [[code](https://github.com/pdclab/graphbolt)]

**2019**

1. GraphBolt: Dependency-Driven Synchronous Processing of Streaming Graphs.  [EuroSys 2019] [[paper](https://dl.acm.org/doi/10.1145/3302424.3303974)] [[code](https://github.com/pdclab/graphbolt)]

**2021**

1. Ingress: Automating incremental graph processing with flexible memoization.  [VLDB 2021] [[paper](https://dl.acm.org/doi/10.14778/3461535.3461550)] [code]
2.  RisGraph: A Real-Time Streaming System for Evolving Graphs to Support Sub-millisecond Per-update Analysis at Millions Ops/s.  [SIGMOD 2021] [[paper](https://dl.acm.org/doi/10.1145/3448016.3457263)] [[code](https://github.com/thu-pacman/RisGraph)]
3. Tripoline: generalized incremental graph processing via graph triangle inequality.  [EuroSys 2021] [[paper](https://dl.acm.org/doi/10.1145/3447786.3456226)] [code]

**2022**
1. TDGraph: a topology-driven accelerator for high-performance streaming graph processing. [ISCA 2022] [[paper](https://dl.acm.org/doi/abs/10.1145/3470496.3527409)] [code]
2. GraphFly: Efficient Asynchronous Streaming Graphs Processing via Dependency-Flow. [SC 2022] [[paper](https://www.computer.org/csdl/proceedings-article/sc/2022/544400a632/1I0bT0fhTqM)] [[code](https://github.com/GFLY-PAPER/GraphFly)] [[slides](./slides/SC20-graphfly.pptx)]



# <span id = "GPU/FPGA-Graph-Processing-System-Paper">GPU/FPGA-Graph Processing System Paper</span>

## <span id = "GPU/FPGA-Static-Graph-Processing-System">Static Graph Processing System</span>
**2017**

1.A Distributed Multi-GPU System for Fast Graph Processing. [VLDB 2017] [[paper](http://www.vldb.org/pvldb/vol11/p297-jia.pdf)]

**2019**

1. GPU-based Graph Traversal on Compressed Graphs. [SIGMOD 2019] [[paper](https://dl.acm.org/doi/pdf/10.1145/3299869.3319871)]
2. SEP-Graph: Finding Shortest Execution Paths for Graph Processing under a Hybrid Framework on GPU. [PPOPP 2019] [[paper](https://dl.acm.org/doi/pdf/10.1145/3293883.3295733)] [[code](https://github.com/SEP-Graph/sep-graph.git)]

**2020**

1. Scaph: Scalable GPU-Accelerated Graph Processing with Value-Driven Differential Scheduling. [ATC 2020] [[paper](https://www.usenix.org/system/files/atc20-zheng.pdf)] [[code](https://github.com/ftxj/Scaph.git)]
2. Subway: Minimizing Data Transfer during Out-of-GPU-Memory Graph Processing. [EuroSys 2020] [[paper](https://dl.acm.org/doi/pdf/10.1145/3342195.3387537)] [[code](https://github.com/AutomataLab/Subway.git)]

**2021**

1. Ascetic: Enhancing Cross-Iterations Data Efficiency in Out-of-Memory Graph Processing on GPUs. [ICPP 2021] [[paper](https://dl.acm.org/doi/pdf/10.1145/3472456.3472457)] [[code](https://github.com/NKU-EmbeddedSystem/Ascetic.git)]
2. EMOGI: Efficient Memory-access for Out-of-memory Graph-traversal in GPUs.  [VLDB 2021] [[paper](http://www.vldb.org/pvldb/vol14/p114-min.pdf)] [[code](https://github.com/illinois-impact/EMOGI.git)]
3. Self-adaptive Graph Traversal on GPUs. [SIGMOD 2021] [[paper](https://dl.acm.org/doi/pdf/10.1145/3448016.3457279)]
## <span id = "GPU/FPGA-Dynamic-Graph-Processing-System">Dynamic Graph Processing System</span>

**2020**

1. GraphPulse: An Event-Driven Hardware Accelerator for Asynchronous Graph Processing. [MICRO 2020] [[paper](https://ieeexplore.ieee.org/document/9251946)] [code]

**2021**


  1.  JetStream: Graph Analytics on Streaming Data with Event-Driven Hardware Accelerator. [MICRO 2021] [[paper](https://dl.acm.org/doi/abs/10.1145/3466752.3480126)] [code] [[slides](./slides/JetStream.pptx)]
  2.  DepGraph: A Dependency-Driven Accelerator for Efficient Iterative Graph Processing. [HPCA 2021] [[paper](https://ieeexplore.ieee.org/abstract/document/9407071)] [code]
  3.  Improving Streaming Graph Processing Performance using Input Knowledge. [MICRO 2021] [[paper](https://dl.acm.org/doi/10.1145/3466752.3480096)] [code] [[slides](./slides/micro21-ABR.pptx)]



# <span id = "Graph-Processing-Algorithmic-Paper">Graph Processing  Algorithmic Paper</span>

**2022**


  1.  On Scalable Computation of Graph Eccentricities. [SIGMOD 2022] [[paper](https://dl.acm.org/doi/10.1145/3514221.3517874)] [code] [[slides](./slides/IFECC.pptx)]
  2.  LOTUS: locality optimizing triangle counting. [PP0PP 2022] [[paper](https://dl.acm.org/doi/10.1145/3503221.3508402)] [code] [[slides](./slides/LOTUS.pptx)]
  **2022**
  3. Sortledton: a Universal, Transactional Graph Data Structure. [VLDB 2022] [[paper](https://www.vldb.org/pvldb/vol15/p1173-fuchs.pdf)] [[code](https://gitlab.db.in.tum.de/per.fuchs/sortledton/)]



