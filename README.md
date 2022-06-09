# Graph-Computing-Papers
This is a project to collect and share related papers on graph processing by the iDC-NEU team. Papers can be systematic or algorithmic. As long as you feel fruitful, you can share them with us! Please add papers in the order of paper name, published conference/journal, paper link and code link(if open source).
# Content
- [Graph Processing System Paper](#Graph-Processing-System-Paper)
  
  - [Static Graph Processing System](#Static-Graph-Processing-System)
  - [Dynamic Graph Processing System](#Dynamic-Graph-Processing-System)
  
- [GPU/FPGA-Graph Processing System Paper](#GPU/FPGA-Graph-Processing-System-Paper)

  - [Static Graph Processing System](#GPU/FPGA-Static-Graph-Processing-System)
  - [Dynamic Graph Processing System](#GPU/FPGA-Dynamic-Graph-Processing-System)

- [Graph Processing  Algorithmic Paper](#GNN-Algorithmic-Paper)

  

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



# <span id = "Graph-Processing-Algorithmic-Paper">Graph Processing  Algorithmic Paper</span>



