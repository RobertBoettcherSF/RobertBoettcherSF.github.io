# ⭐ Sternenfisch ⭐

**Implementing Algorithms in Ada** · [Wikipedia: List of Algorithms](https://en.wikipedia.org/wiki/List_of_algorithms)

*Building reliable, verifiable implementations of classic and modern algorithms in Ada and Ada SPARK*

**LLM usage disclosure:** AI assistance was used for these projects.

---

## 🚀 Featured (2026-09-20)


| Project | Repository | Description |
| --- | --- | --- |
| **Connected-Component Labeling (SPARK L2)** | [Ada-SPARK-Connected-Component-Labeling](https://github.com/RobertBoettcherSF/Ada-SPARK-Connected-Component-Labeling) | ICEYE-adjacent CCL on binary masks; 4-connectivity; L2 cvc5 **18/18**. |
| **Median Filtering (SPARK L2)** | [Ada-SPARK-Median-Filtering](https://github.com/RobertBoettcherSF/Ada-SPARK-Median-Filtering) | Fixed $3\times3$ median pre-filter sheet; L2 **34/34**. |
| **Cooley–Tukey FFT (SPARK L2)** | [Ada-SPARK-Cooley-Tukey-FFT](https://github.com/RobertBoettcherSF/Ada-SPARK-Cooley-Tukey-FFT) | Fixed-point radix-2 FFT ($N=8$); SAR-formation building block; L2 **45/45**. |
| **PN-Counter CRDT (SPARK L2)** | [Ada-SPARK-PN-Counter](https://github.com/RobertBoettcherSF/Ada-SPARK-PN-Counter) | Clean-room PN-Counter sheet; merge = componentwise $\max$; L2 **23/23**. |
| **Ada Logistics Module** | [Ada-Logistics-Module](https://github.com/RobertBoettcherSF/Ada-Logistics-Module) | Clean-room logistics/Spedition sim (EU classes, Space_Haul/Tunnel, ATC, evolutionary fleet, sim_run.csv). MIT. |
| **rogue_engine** | [rogue_engine](https://github.com/RobertBoettcherSF/rogue_engine) | Ada 2023 survival ops / bunker–strider engine (suit, Story_Arc, messages, SI strip). MIT. |


## ✅ Verification (measured)

Educational SPARK sheets with figures from our last successful `make prove` / `gnatprove.out`. **Not** a third-party compliance audit (no DO-178C / ISO / AdaCore Covex Platinum claim unless `adacovex` artifacts exist).


| Package | Level | Proved | Notes |
| --- | --- | --- | --- |
| [Ada-SPARK-Connected-Component-Labeling](https://github.com/RobertBoettcherSF/Ada-SPARK-Connected-Component-Labeling) | L2 cvc5 | 18/18 | ICEYE-adjacent CCL sheet |
| [Ada-SPARK-Median-Filtering](https://github.com/RobertBoettcherSF/Ada-SPARK-Median-Filtering) | L2 | 34/34 | $3\times3$ median pre-filter |
| [Ada-SPARK-Cooley-Tukey-FFT](https://github.com/RobertBoettcherSF/Ada-SPARK-Cooley-Tukey-FFT) | L2 | 45/45 | Fixed-point radix-2 FFT |
| [Ada-SPARK-PN-Counter](https://github.com/RobertBoettcherSF/Ada-SPARK-PN-Counter) | L2 cvc5 | 23/23 | Clean-room PN-Counter CRDT |
| [Ada-SPARK-CRC32](https://github.com/RobertBoettcherSF/Ada-SPARK-CRC32) | L2 | (per README) | `make prove` L2 cvc5 |
| [Ada-SPARK-Huffman-Coding](https://github.com/RobertBoettcherSF/Ada-SPARK-Huffman-Coding) | L3 Pareto | 16/16 | Default `make prove` L3 |
| [Ada-SPARK-Flood-Fill](https://github.com/RobertBoettcherSF/Ada-SPARK-Flood-Fill) | L2 | (per README) | CVC5 Level 2 |

## 📚 Algorithm Implementations

---

### 🔗 Distributed &amp; Concurrent Algorithms


| Algorithm                      | Repository                                                                                                                              | Description                                 |
| ------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **Bully**                      | [Ada-Bully-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bully-Algorithm)                                                         | Leader election in distributed systems      |
| **Chandra-Toueg**              | [Ada-Chandra-Toueg](https://github.com/RobertBoettcherSF/Ada-Chandra-Toueg)                                                             | Consensus algorithm for distributed systems |
| **Chandy-Lamport**             | [Ada-Chandy-Lamport-Algorithm](https://github.com/RobertBoettcherSF/Ada-Chandy-Lamport-Algorithm)                                       | Distributed snapshot algorithm              |
| **Dekker's**                   | [Ada-Dekker](https://github.com/RobertBoettcherSF/Ada-Dekker)                                                                           | Mutual exclusion algorithm with variants    |
| **Dijkstra-Scholten**          | [Ada-Dijkstra-Scholten-Algorithm](https://github.com/RobertBoettcherSF/Ada-Dijkstra-Scholten-Algorithm)                                 | Distributed termination detection           |
| **Huang's**                    | [Ada-Huangs-Algorithm](https://github.com/RobertBoettcherSF/Ada-Huangs-Algorithm)                                                       | Distributed termination detection           |
| **Lamport Ordering**           | [Ada-Lamport-Ordering](https://github.com/RobertBoettcherSF/Ada-Lamport-Ordering)                                                       | Causal message ordering                     |
| **Lamport's Bakery**           | [Ada-lamport](https://github.com/RobertBoettcherSF/Ada-lamport)                                                                         | Mutual exclusion algorithm                  |
| **Lamport's Mutual Exclusion** | [Lamports-Distributed-Mutual-Exclusion-Algorithm](https://github.com/RobertBoettcherSF/Lamports-Distributed-Mutual-Exclusion-Algorihtm) | Distributed mutual exclusion                |
| **Maekawa's**                  | [Ada-Maekawas-Algorithm](https://github.com/RobertBoettcherSF/Ada-Maekawas-Algorithm)                                                   | Distributed mutual exclusion                |
| **Nagle's**                    | [Ada-Nagles-Algorithm](https://github.com/RobertBoettcherSF/Ada-Nagles-Algorithm)                                                       | Network congestion control                  |
| **Naimi-Trehel**               | [Ada-Naimi-Trehel](https://github.com/RobertBoettcherSF/Ada-Naimi-Trehel)                                                               | Distributed mutual exclusion                |
| **PN-Counter (CRDT)**           | [Ada-SPARK-PN-Counter](https://github.com/RobertBoettcherSF/Ada-SPARK-PN-Counter)                                                       | Positive-Negative Counter CRDT (SPARK L2)   |
| **Paxos**                      | [Ada-Paxos-Algorithm](https://github.com/RobertBoettcherSF/Ada-Paxos-Algorithm)                                                         | Consensus algorithm                         |
| **Peterson's**                 | [Ada-peterson](https://github.com/RobertBoettcherSF/Ada-peterson)                                                                       | Two-process mutual exclusion                |
| **Raft**                       | [Ada-Raft](https://github.com/RobertBoettcherSF/Ada-Raft)                                                                               | Consensus algorithm                         |
| **Raymond's**                  | [Ada-Raymonds-Algorithm](https://github.com/RobertBoettcherSF/Ada-Raymonds-Algorithm)                                                   | Tree-based mutual exclusion                 |
| **Ricart-Agrawala**            | [Ada-Ricart-Agrawala-Algorithm](https://github.com/RobertBoettcherSF/Ada-Ricart-Agrawala-Algorithm)                                     | Distributed mutual exclusion                |
| **Vector Clocks**              | [Ada-Vector-Clocks](https://github.com/RobertBoettcherSF/Ada-Vector-Clocks)                                                             | Logical clock synchronization               |
| **XOR Swap**                   | [Ada-Xor-Swap-Algorithm](https://github.com/RobertBoettcherSF/Ada-Xor-Swap-Algorithm)                                                   | Value swapping without temporary variable   |


---

### 💾 Memory Management &amp; Garbage Collection


| Algorithm                   | Repository                                                                                                    | Description                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| **Banker's**                | [Ada-Bankers-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bankers-Algorithm)                           | Deadlock avoidance algorithm           |
| **Buddy Memory Allocation** | [Ada-Buddy-Memory-Allocation](https://github.com/RobertBoettcherSF/Ada-Buddy-Memory-Allocation)               | Memory allocation strategy             |
| **Cheney's**                | [Ada-Cheneys-Algorithm](https://github.com/RobertBoettcherSF/Ada-Cheneys-Algorithm)                           | Copying garbage collection             |
| **Clock Page Replacement**  | [Ada-clock-replacement](https://github.com/RobertBoettcherSF/Ada-clock-replacement)                           | Page replacement for virtual memory    |
| **Generational GC**         | [Ada-Generational-Garbage-Collector](https://github.com/RobertBoettcherSF/Ada-Generational-Garbage-Collector) | Generational garbage collection        |
| **Mark and Sweep**          | [Ada-Mark-and-Sweep](https://github.com/RobertBoettcherSF/Ada-Mark-and-Sweep)                                 | Garbage collection algorithm           |
| **Mark-Compact**            | [Ada-Mark-Compact-Algorithm](https://github.com/RobertBoettcherSF/Ada-Mark-Compact-Algorithm)                 | Memory compaction algorithm            |
| **Reference Counting**      | [Ada-Reference-Counting](https://github.com/RobertBoettcherSF/Ada-Reference-Counting)                         | Memory management via reference counts |
| **Semi-Space Collectors**   | [Ada-Semi-Space-Collectors](https://github.com/RobertBoettcherSF/Ada-Semi-Space-Collectors)                   | Stop-the-world garbage collection      |


---

### 🔍 Graph Algorithms


| Algorithm                        | Repository                                                                                                | Description                     |
| -------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------- |
| **Connected Component Labeling** | [Ada-Connected-Component-Labeling](https://github.com/RobertBoettcherSF/Ada-Connected-Component-Labeling) | Image processing algorithm      |
| **Grafalgo**                     | [Grafalgo-Ada-Implementation](https://github.com/RobertBoettcherSF/Grafalgo-Ada-Implementation)           | Graph algorithms library        |
| **Push-Relabel**                 | [Ada-Push-Relabel-Algorithm](https://github.com/RobertBoettcherSF/Ada-Push-Relabel-Algorithm)             | Maximum flow algorithm          |
| **Spectral Layout**              | [Ada-Spectral-Layout](https://github.com/RobertBoettcherSF/Ada-Spectral-Layout)                           | Graph layout via eigenvalues    |
| **Subgraph Isomorphism**         | [Ada-subgraph-isomorphism](https://github.com/RobertBoettcherSF/Ada-subgraph-isomorphism)                 | Subgraph matching               |
| **Top Nodes**                    | [Ada-Top-Nodes-Algorithm](https://github.com/RobertBoettcherSF/Ada-Top-Nodes-Algorithm)                   | Graph node ranking              |
| **Topological Sort**             | [Ada-Topological-Sort](https://github.com/RobertBoettcherSF/Ada-Topological-Sort)                         | DAG vertex ordering             |
| **Uniform-Cost Search**          | [Ada-Uniform-Cost-Search](https://github.com/RobertBoettcherSF/Ada-Uniform-Cost-Search)                   | Weighted graph search           |
| **Warnsdorff's Rule**            | [Ada-Warnsdorffs-Rule](https://github.com/RobertBoettcherSF/Ada-Warnsdorffs-Rule)                         | Heuristic for the Knight's Tour |
| **Bellman–Ford** | [Ada-Bellman-Ford-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bellman-Ford-Algorithm) | Single-source shortest paths with negatives |
| **Blossom** | [Ada-Blossom-Algorithm](https://github.com/RobertBoettcherSF/Ada-Blossom-Algorithm) | Maximum matching in general graphs |
| **Borůvka** | [Ada-Boruvkas-Algorithm](https://github.com/RobertBoettcherSF/Ada-Boruvkas-Algorithm) | Minimum spanning tree |
| **Christofides** | [Ada-Christofides-Algorithm](https://github.com/RobertBoettcherSF/Ada-Christofides-Algorithm) | TSP approximation |
| **Coin Graph** | [Ada-Coin-Graph](https://github.com/RobertBoettcherSF/Ada-Coin-Graph) | Coin-graph constructions |
| **Coloring** | [Ada-Coloring-Algorithm](https://github.com/RobertBoettcherSF/Ada-Coloring-Algorithm) | Graph coloring heuristics |
| **Dinic** | [Ada-Dinics-Algorithm](https://github.com/RobertBoettcherSF/Ada-Dinics-Algorithm) | Maximum flow (blocking flows) |
| **Edmonds (Arborescence)** | [Ada-Edmonds-Algorithm](https://github.com/RobertBoettcherSF/Ada-Edmonds-Algorithm) | Minimum branching / arborescence |
| **Edmonds–Karp** | [Ada-Edmonds-Karp-Algorithm](https://github.com/RobertBoettcherSF/Ada-Edmonds-Karp-Algorithm) | Maximum flow (BFS augmenting paths) |
| **Euclidean MST** | [Ada-Euclidean-Minimum-Spanning-Tree](https://github.com/RobertBoettcherSF/Ada-Euclidean-Minimum-Spanning-Tree) | MST in the plane |
| **Flow Networks** | [Ada-Flow-Networks](https://github.com/RobertBoettcherSF/Ada-Flow-Networks) | Flow network survey / utilities |
| **Floyd–Warshall** | [Ada-Floyd-Warshall-Algorithm](https://github.com/RobertBoettcherSF/Ada-Floyd-Warshall-Algorithm) | All-pairs shortest paths |
| **Force-Based Layout** | [Ada-Force-Based-Algorithms](https://github.com/RobertBoettcherSF/Ada-Force-Based-Algorithms) | Force-directed graph drawing |
| **Ford–Fulkerson** | [Ada-Ford-Fulkerson-Algorithm](https://github.com/RobertBoettcherSF/Ada-Ford-Fulkerson-Algorithm) | Maximum flow (augmenting paths) |
| **Hopcroft–Karp** | [Ada-Hopcroft-Karp-Algorithm](https://github.com/RobertBoettcherSF/Ada-Hopcroft-Karp-Algorithm) | Maximum bipartite matching |
| **Hungarian** | [Ada-Hungarian-Algorithm](https://github.com/RobertBoettcherSF/Ada-Hungarian-Algorithm) | Assignment problem |
| **HITS** | [Ada-Hyperlink-Induced-Topic-Search](https://github.com/RobertBoettcherSF/Ada-Hyperlink-Induced-Topic-Search) | Hubs and authorities |
| **Johnson** | [Ada-Johnsons-Algorithm](https://github.com/RobertBoettcherSF/Ada-Johnsons-Algorithm) | All-pairs shortest paths |
| **Karger** | [Ada-Kargers-Algorithm](https://github.com/RobertBoettcherSF/Ada-Kargers-Algorithm) | Randomized min-cut |
| **Kruskal** | [Ada-Kruskals-Algorithm](https://github.com/RobertBoettcherSF/Ada-Kruskals-Algorithm) | Minimum spanning tree |
| **Longest Path** | [Ada-Longest-Path-Problem](https://github.com/RobertBoettcherSF/Ada-Longest-Path-Problem) | Longest paths in graphs |
| **Minimum Spanning Tree** | [Ada-Minimum-Spanning-Tree](https://github.com/RobertBoettcherSF/Ada-Minimum-Spanning-Tree) | MST survey |
| **Nearest Neighbor (TSP)** | [Ada-Nearest-Neighbor-Algorithm](https://github.com/RobertBoettcherSF/Ada-Nearest-Neighbor-Algorithm) | TSP heuristic |
| **Nonblocking Switch** | [Ada-Nonblocking-Minimal-Spanning-Switch](https://github.com/RobertBoettcherSF/Ada-Nonblocking-Minimal-Spanning-Switch) | Nonblocking spanning switch |
| **PageRank** | [Ada-PageRank](https://github.com/RobertBoettcherSF/Ada-PageRank) | Link analysis ranking |
| **Prim** | [Ada-Prims-Algorithm](https://github.com/RobertBoettcherSF/Ada-Prims-Algorithm) | Minimum spanning tree |
| **Prüfer Coding** | [Ada-Prufer-Coding](https://github.com/RobertBoettcherSF/Ada-Prufer-Coding) | Tree ↔ Prüfer sequence |
| **Reverse-Delete** | [Ada-Reverse-Delete-Algorithm](https://github.com/RobertBoettcherSF/Ada-Reverse-Delete-Algorithm) | Minimum spanning tree |
| **Shortest Path Problem** | [Ada-Shortest-Path-Problem](https://github.com/RobertBoettcherSF/Ada-Shortest-Path-Problem) | Shortest-path survey |
| **Tarjan Offline LCA** | [Ada-Tarjans-Off-Line-Lowest-Common-Ancestors](https://github.com/RobertBoettcherSF/Ada-Tarjans-Off-Line-Lowest-Common-Ancestors) | Offline lowest common ancestors |
| **Transitive Closure** | [Ada-Transitive-Closure](https://github.com/RobertBoettcherSF/Ada-Transitive-Closure) | Reachability / closure |
| **Travelling Salesman** | [Ada-Travelling-Salesman-Problem](https://github.com/RobertBoettcherSF/Ada-Travelling-Salesman-Problem) | TSP algorithms survey |
| **TrustRank** | [Ada-TrustRank](https://github.com/RobertBoettcherSF/Ada-TrustRank) | Trust-based ranking |
| **Vehicle Routing** | [Ada-Vehicle-Routing-Problem](https://github.com/RobertBoettcherSF/Ada-Vehicle-Routing-Problem) | VRP heuristics |
| **A*** | [Ada-A-Star](https://github.com/RobertBoettcherSF/Ada-A-Star) | Heuristic pathfinding |
| **B*** | [Ada-B-Star](https://github.com/RobertBoettcherSF/Ada-B-Star) | Heuristic search |


---

### 🎯 Scheduling Algorithms


| Algorithm                   | Repository                                                                                          | Description                      |
| --------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------- |
| **Cyclic Executive**        | [cyclic\_executive\_scheduler](https://github.com/RobertBoettcherSF/cyclic_executive_scheduler)     | RTOS-style cyclic task scheduler |
| **Earliest Deadline First** | [Ada-earliest-deadline](https://github.com/RobertBoettcherSF/Ada-earliest-deadline)                 | Real-time scheduling (EDF)       |
| **Elevator Algorithm**      | [Ada-Elevator-Algorithm](https://github.com/RobertBoettcherSF/Ada-Elevator-Algorithm)               | Disk scheduling (SCAN)           |
| **Fair-Share**              | [Ada-fair-share](https://github.com/RobertBoettcherSF/Ada-fair-share)                               | Fair-share scheduling            |
| **Least Slack Time**        | [Ada-lds-scheduler](https://github.com/RobertBoettcherSF/Ada-lds-scheduler)                         | Real-time scheduling (LST)       |
| **List Scheduling**         | [Ada-List-Scheduling](https://github.com/RobertBoettcherSF/Ada-List-Scheduling)                     | Instruction/task scheduling      |
| **MLFQ**                    | [Ada-mlfq](https://github.com/RobertBoettcherSF/Ada-mlfq)                                           | Multilevel Feedback Queue        |
| **Rate-Monotonic**          | [Ada-rate-monotonic](https://github.com/RobertBoettcherSF/Ada-rate-monotonic)                       | Real-time scheduling (RMS)       |
| **Round-Robin**             | [Ada-round-robin](https://github.com/RobertBoettcherSF/Ada-round-robin)                             | Time-sliced scheduling           |
| **Shortest Job Next**       | [Ada-sjn](https://github.com/RobertBoettcherSF/Ada-sjn)                                             | SJN/SJF scheduling               |
| **Shortest Remaining Time** | [Ada-srt-simulation](https://github.com/RobertBoettcherSF/Ada-srt-simulation)                       | SRT scheduling simulation        |
| **Shortest Seek First**     | [Ada-SPARK-Shortest-Seek-First](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Seek-First) | Disk scheduling (SSTF)           |


---

### 📊 Computer Vision &amp; Image Processing


| Algorithm                           | Repository                                                                                                          | Description                              |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| **Adaptive Histogram Equalization** | [Ada-Adaptive-Histogram-Equalization](https://github.com/RobertBoettcherSF/Ada-Adaptive-Histogram-Equalization)     | Contrast enhancement (CLAHE)             |
| **Blind Deconvolution**             | [Ada-Blind-Deconvolution](https://github.com/RobertBoettcherSF/Ada-Blind-Deconvolution)                             | Image deblurring                         |
| **Canny Edge Detector**             | [Ada-Canny-Edge-Detector](https://github.com/RobertBoettcherSF/Ada-Canny-Edge-Detector)                             | Edge detection algorithm                 |
| **Feature Detection**               | [Ada-Feature-Detection](https://github.com/RobertBoettcherSF/Ada-Feature-Detection)                                 | Feature point detection                  |
| **Generalised Hough Transform**     | [Ada-Generalised-Hough-Transform](https://github.com/RobertBoettcherSF/Ada-Generalised-Hough-Transform)             | Object recognition                       |
| **GrowCut**                         | [Ada-GrowCut](https://github.com/RobertBoettcherSF/Ada-GrowCut)                                                     | Image segmentation                       |
| **Histogram Equalization**          | [Ada-Histogram-Equalization](https://github.com/RobertBoettcherSF/Ada-Histogram-Equalization)                       | Contrast enhancement                     |
| **Hough Transform**                 | [Ada-Hough-Transform](https://github.com/RobertBoettcherSF/Ada-Hough-Transform)                                     | Line detection                           |
| **Marr-Hildreth**                   | [Ada-Marr-Hildreth-Algorithm](https://github.com/RobertBoettcherSF/Ada-Marr-Hildreth-Algorithm)                     | Edge detection via Laplacian of Gaussian |
| **Median Filtering**                | [Ada-Median-Filtering](https://github.com/RobertBoettcherSF/Ada-Median-Filtering)                                   | Noise reduction filtering                |
| **Random Walker**                   | [Ada-Random-Walker](https://github.com/RobertBoettcherSF/Ada-Random-Walker)                                         | Image segmentation                       |
| **Region Growing**                  | [Ada-Region-Growing](https://github.com/RobertBoettcherSF/Ada-Region-Growing)                                       | Image segmentation                       |
| **Richardson-Lucy Deconvolution**   | [Ada-Richardson-Lucy-Deconvolution](https://github.com/RobertBoettcherSF/Ada-Richardson-Lucy-Deconvolution)         | Image deblurring                         |
| **Seam Carving**                    | [Ada-Seam-Carving](https://github.com/RobertBoettcherSF/Ada-Seam-Carving)                                           | Content-aware image resizing             |
| **Segmentation**                    | [Ada-Segmentation](https://github.com/RobertBoettcherSF/Ada-Segmentation)                                           | Image segmentation                       |
| **SIFT**                            | [Ada-Scale-Invariant-Feature-Transform](https://github.com/RobertBoettcherSF/Ada-Scale-Invariant-Feature-Transform) | Feature detection                        |
| **Summed-Area Table**               | [Ada-Summed-Area-Table](https://github.com/RobertBoettcherSF/Ada-Summed-Area-Table)                                 | Integral image computation               |
| **SURF**                            | [Ada-Speeded-Up-Robust-Features](https://github.com/RobertBoettcherSF/Ada-Speeded-Up-Robust-Features)               | Feature detection and matching           |
| **Watershed Transformation**        | [Ada-Watershed-Transformation](https://github.com/RobertBoettcherSF/Ada-Watershed-Transformation)                   | Image segmentation                       |


---

### 🎨 Dithering &amp; Halftoning


| Algorithm                     | Repository                                                                                          | Description               |
| ----------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------- |
| **Dithering**                 | [Ada-Dithering](https://github.com/RobertBoettcherSF/Ada-Dithering)                                 | Dithering framework       |
| **Error Diffusion**           | [Ada-Error-Diffusion](https://github.com/RobertBoettcherSF/Ada-Error-Diffusion)                     | Error-diffusion dithering |
| **Floyd-Steinberg Dithering** | [Ada-Floyd-Steinberg-Dithering](https://github.com/RobertBoettcherSF/Ada-Floyd-Steinberg-Dithering) | Image dithering           |
| **Half-Toning**               | [Ada-Half-Toning](https://github.com/RobertBoettcherSF/Ada-Half-Toning)                             | Halftoning                |
| **Ordered Dithering**         | [Ada-Ordered-Dithering](https://github.com/RobertBoettcherSF/Ada-Ordered-Dithering)                 | Ordered dithering         |
| **Riemersma Dithering**       | [Ada-Riemersma-Dithering](https://github.com/RobertBoettcherSF/Ada-Riemersma-Dithering)             | Riemersma dithering       |


---

### 🌊 Signal Processing &amp; Fourier Transforms


| Algorithm                       | Repository                                                                                                      | Description                  |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| **Adaptive-Additive Algorithm** | [Ada-Adaptive-Additive-Algorithm](https://github.com/RobertBoettcherSF/Ada-Adaptive-Additive-Algorithm)         | Adaptive additive algorithm  |
| **Bluestein's FFT**             | [Ada-Bluesteins-FFT-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bluesteins-FFT-Algorithm)               | Chirp z-transform FFT        |
| **Bruun's FFT**                 | [Ada-Bruuns-FFT-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bruuns-FFT-Algorithm)                       | FFT algorithm                |
| **Cooley-Tukey FFT**            | [Ada-Cooley-Tukey-FFT-Algorithm](https://github.com/RobertBoettcherSF/Ada-Cooley-Tukey-FFT-Algorithm)           | FFT algorithm                |
| **Discrete Fourier Transform**  | [Ada-Discrete-Fourier-Transformation](https://github.com/RobertBoettcherSF/Ada-Discrete-Fourier-Transformation) | DFT computation              |
| **Fast Folding Algorithm**      | [Ada-Fast-Folding-Algorithm](https://github.com/RobertBoettcherSF/Ada-Fast-Folding-Algorithm)                   | Folding for periodic signals |
| **Fast Fourier Transform**      | [Ada-Fast-Fourier-Transform](https://github.com/RobertBoettcherSF/Ada-Fast-Fourier-Transform)                   | FFT computation              |
| **Gerchberg-Saxton**            | [Ada-Gerchberg-Saxton-Algorithm](https://github.com/RobertBoettcherSF/Ada-Gerchberg-Saxton-Algorithm)           | Phase retrieval              |
| **Goertzel Algorithm**          | [Ada-Goertzel-Algorithm](https://github.com/RobertBoettcherSF/Ada-Goertzel-Algorithm)                           | Single-tone DFT evaluation   |
| **Karplus-Strong**              | [Ada-Karplus-Strong-String-Synthesis](https://github.com/RobertBoettcherSF/Ada-Karplus-Strong-String-Synthesis) | String sound synthesis       |
| **Prime-Factor FFT**            | [Ada-Prime-Factor-FFT-Algorithm](https://github.com/RobertBoettcherSF/Ada-Prime-Factor-FFT-Algorithm)           | FFT algorithm                |
| **Rader's FFT**                 | [Ada-Raders-FFT-Algorithm](https://github.com/RobertBoettcherSF/Ada-Raders-FFT-Algorithm)                       | FFT for prime sizes          |


---

### 🗜️ Lossless Compression


| Algorithm                                  | Repository                                                                                                                                          | Description                |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| **Adaptive Huffman Coding**                | [Ada-Adaptive-Huffman-Coding](https://github.com/RobertBoettcherSF/Ada-Adaptive-Huffman-Coding)                                                     | Adaptive entropy coding    |
| **Arithmetic Coding**                      | [Ada-Arithmetic-Coding](https://github.com/RobertBoettcherSF/Ada-Arithmetic-Coding)                                                                 | Entropy coding             |
| **Burrows-Wheeler Transform**              | [Ada-Burrows-Wheeler-Transform](https://github.com/RobertBoettcherSF/Ada-Burrows-Wheeler-Transform)                                                 | Reversible block transform |
| **Context-Tree Weighting**                 | [Ada-Context-Tree-Weighting](https://github.com/RobertBoettcherSF/Ada-Context-Tree-Weighting)                                                       | Lossless compression       |
| **Deflate**                                | [Ada-Deflate](https://github.com/RobertBoettcherSF/Ada-Deflate)                                                                                     | Lossless data compression  |
| **Delta Encoding**                         | [Ada-Delta-Encoding](https://github.com/RobertBoettcherSF/Ada-Delta-Encoding)                                                                       | Numeric delta encoding     |
| **Dictionary Coder**                       | [Ada-Dictionary-Coder](https://github.com/RobertBoettcherSF/Ada-Dictionary-Coder)                                                                   | Dictionary-based coding    |
| **Dynamic Markov Compression**             | [Ada-Dynamic-Markov-Compression](https://github.com/RobertBoettcherSF/Ada-Dynamic-Markov-Compression)                                               | Statistical compression    |
| **Elias Delta Coding**                     | [Ada-Elias-Delta-Coding](https://github.com/RobertBoettcherSF/Ada-Elias-Delta-Coding)                                                               | Universal coding           |
| **Elias Gamma Coding**                     | [Ada-Elias-Gamma-Coding](https://github.com/RobertBoettcherSF/Ada-Elias-Gamma-Coding)                                                               | Universal coding           |
| **Elias Omega Coding**                     | [Ada-Elias-Omega-Coding](https://github.com/RobertBoettcherSF/Ada-Elias-Omega-Coding)                                                               | Universal coding           |
| **Entropy Coding**                         | [Ada-Entropy-Coding](https://github.com/RobertBoettcherSF/Ada-Entropy-Coding)                                                                       | Entropy coding             |
| **Entropy Coding (Known Characteristics)** | [Ada-Entropy-Coding-With-Known-Entropy-Characteristics](https://github.com/RobertBoettcherSF/Ada-Entropy-Coding-With-Known-Entropy-Characteristics) | Entropy coding             |
| **Exponential-Golomb Coding**              | [Ada-Exponential-Golomb-Coding](https://github.com/RobertBoettcherSF/Ada-Exponential-Golomb-Coding)                                                 | Universal coding           |
| **Fibonacci Coding**                       | [Ada-Fibonacci-Coding](https://github.com/RobertBoettcherSF/Ada-Fibonacci-Coding)                                                                   | Universal coding           |
| **Golomb Coding**                          | [Ada-Golomb-Coding](https://github.com/RobertBoettcherSF/Ada-Golomb-Coding)                                                                         | Entropy coding             |
| **Huffman Coding**                         | [Ada-Huffmann-Coding](https://github.com/RobertBoettcherSF/Ada-Huffmann-Coding)                                                                     | Entropy coding             |
| **Incremental Encoding**                   | [Ada-Incremental-Encoding](https://github.com/RobertBoettcherSF/Ada-Incremental-Encoding)                                                           | Incremental encoding       |
| **Lempel-Ziv-Jeff-Bonwick**                | [Ada-Lempel-Ziv-Jeff-Bonwick](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Jeff-Bonwick)                                                     | LZJB compression           |
| **Lempel-Ziv-Markov Chain**                | [Ada-Lempel-Ziv-Markov-Chain-Algorithm](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Markov-Chain-Algorithm)                                 | LZMA compression           |
| **Lempel-Ziv-Oberhumer**                   | [Ada-Lempel-Ziv-Oberhurmer](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Oberhurmer)                                                         | LZO compression            |
| **Lempel-Ziv-Ross-Williams**               | [Ada-Lempel-Ziv-Ross-Williams](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Ross-Williams)                                                   | LZR compression            |
| **Lempel-Ziv-Stac**                        | [Ada-Lempel-Ziv-Stac](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Stac)                                                                     | LZS compression            |
| **Lempel-Ziv-Storer-Szymanski**            | [Ada-Lempel-Ziv-Storer-Szymanski](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Storer-Szymanski)                                             | LZSS compression           |
| **Lempel-Ziv-Welch**                       | [Ada-Lempel-Ziv-Welch](https://github.com/RobertBoettcherSF/Ada-Lempel-Ziv-Welch)                                                                   | LZW compression            |
| **Levenshtein Coding**                     | [Ada-Levenshtein-Coding](https://github.com/RobertBoettcherSF/Ada-Levenshtein-Coding)                                                               | Universal coding           |
| **LZ77 &amp; LZ78**                        | [Ada-LZ77-LZ78](https://github.com/RobertBoettcherSF/Ada-LZ77-LZ78)                                                                                 | LZ77/LZ78 compression      |
| **LZWL**                                   | [Ada-LZWL](https://github.com/RobertBoettcherSF/Ada-LZWL)                                                                                           | LZWL compression           |
| **LZX**                                    | [Ada-LZX](https://github.com/RobertBoettcherSF/Ada-LZX)                                                                                             | LZX compression            |
| **Package-Merge Algorithm**                | [Ada-Package-Merge-Algorithm](https://github.com/RobertBoettcherSF/Ada-Package-Merge-Algorithm)                                                     | Optimal prefix codes       |
| **Prediction by Partial Matching**         | [Ada-Prediction-By-Partial-Matching](https://github.com/RobertBoettcherSF/Ada-Prediction-By-Partial-Matching)                                       | PPM compression            |
| **Range Encoding**                         | [Ada-Range-Encoding](https://github.com/RobertBoettcherSF/Ada-Range-Encoding)                                                                       | Entropy coding             |
| **Rice Coding**                            | [Ada-Rice-Coding](https://github.com/RobertBoettcherSF/Ada-Rice-Coding)                                                                             | Entropy coding             |
| **Run-Length Encoding**                    | [Ada-Run-Length-Encoding](https://github.com/RobertBoettcherSF/Ada-Run-Length-Encoding)                                                             | RLE compression            |
| **SEQUITUR**                               | [Ada-SEQUITUR-Algorithm](https://github.com/RobertBoettcherSF/Ada-SEQUITUR-Algorithm)                                                               | Grammar-based compression  |
| **Shannon-Fano Coding**                    | [Ada-Shannon-Fano-Coding](https://github.com/RobertBoettcherSF/Ada-Shannon-Fano-Coding)                                                             | Prefix coding              |
| **Shannon-Fano-Elias Coding**              | [Ada-Shannon-Fano-Elias-Coding](https://github.com/RobertBoettcherSF/Ada-Shannon-Fano-Elias-Coding)                                                 | Entropy coding             |
| **Truncated Binary Encoding**              | [Ada-Truncated-Binary-Encoding](https://github.com/RobertBoettcherSF/Ada-Truncated-Binary-Encoding)                                                 | Entropy coding             |
| **Unary Coding**                           | [Ada-Unary-Coding](https://github.com/RobertBoettcherSF/Ada-Unary-Coding)                                                                           | Entropy coding             |
| **Universal Coding**                       | [Ada-Universal-Coding](https://github.com/RobertBoettcherSF/Ada-Universal-Coding)                                                                   | Universal coding           |


---

### 🎞️ Lossy &amp; Media Compression


| Algorithm                                     | Repository                                                                                                                                        | Description                |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------- |
| **3Dc**                                       | [Ada-3Dc](https://github.com/RobertBoettcherSF/Ada-3Dc)                                                                                           | Normal map compression     |
| **A-law Algorithm**                           | [Ada-A-Law-Algorithm](https://github.com/RobertBoettcherSF/Ada-A-Law-Algorithm)                                                                   | Audio companding           |
| **Audio Compression**                         | [Ada-Audio-Compression](https://github.com/RobertBoettcherSF/Ada-Audio-Compression)                                                               | Audio compression          |
| **Block Truncation Coding**                   | [Ada-Block-Truncation-Coding](https://github.com/RobertBoettcherSF/Ada-Block-Truncation-Coding)                                                   | Image compression          |
| **Code-Excited Linear Prediction**            | [Ada-Code-Excited-Linear-Prediction](https://github.com/RobertBoettcherSF/Ada-Code-Excited-Linear-Prediction)                                     | Speech coding              |
| **Embedded Zerotree Wavelet**                 | [Ada-Embedded-Zerotree-Wavelet](https://github.com/RobertBoettcherSF/Ada-Embedded-Zerotree-Wavelet)                                               | Image compression          |
| **Fast Cosine Transform**                     | [Ada-Fast-Cosine-Transform-Algorithms](https://github.com/RobertBoettcherSF/Ada-Fast-Cosine-Transform-Algorithms)                                 | Transform coding           |
| **Fast Efficient Lossless Image Compression** | [Ada-Fast-Efficient-Lossless-Image-Compression-System](https://github.com/RobertBoettcherSF/Ada-Fast-Efficient-Lossless-Image-Compression-System) | Lossless image compression |
| **Fractal Compression**                       | [Ada-Fractal-Compression](https://github.com/RobertBoettcherSF/Ada-Fractal-Compression)                                                           | Image compression          |
| **Image Compression**                         | [Ada-Image-Compression](https://github.com/RobertBoettcherSF/Ada-Image-Compression)                                                               | Image compression          |
| **Linear Predictive Coding**                  | [Ada-Linear-Predictive-Coding](https://github.com/RobertBoettcherSF/Ada-Linear-Predictive-Coding)                                                 | Speech coding              |
| **Mu-law Algorithm**                          | [Ada-Mu-Law-Algorithm](https://github.com/RobertBoettcherSF/Ada-Mu-Law-Algorithm)                                                                 | Audio companding           |
| **Set Partitioning in Hierarchical Trees**    | [Ada-Set-Partitioning-In-Hierarchical-Trees](https://github.com/RobertBoettcherSF/Ada-Set-Partitioning-In-Hierarchical-Trees)                     | Image compression (SPIHT)  |
| **Speech Compression**                        | [Ada-Speech-Compression](https://github.com/RobertBoettcherSF/Ada-Speech-Compression)                                                             | Speech compression         |
| **Transform Coding**                          | [Ada-Transform-Coding](https://github.com/RobertBoettcherSF/Ada-Transform-Coding)                                                                 | Transform coding           |
| **TurboQuant**                                | [Ada-TurboQuant](https://github.com/RobertBoettcherSF/Ada-TurboQuant)                                                                             | Quantization               |
| **Vector Quantization**                       | [Ada-Vector-Quantization](https://github.com/RobertBoettcherSF/Ada-Vector-Quantization)                                                           | Quantization               |
| **Video Compression**                         | [Ada-Video-Compression](https://github.com/RobertBoettcherSF/Ada-Video-Compression)                                                               | Video compression          |
| **Warped Linear Predictive Coding**           | [Ada-Warped-Linear-Predictive-Coding](https://github.com/RobertBoettcherSF/Ada-Warped-Linear-Predictive-Coding)                                   | Speech coding              |
| **Wavelet Compression**                       | [Ada-Wavelet-Compression](https://github.com/RobertBoettcherSF/Ada-Wavelet-Compression)                                                           | Wavelet-based compression  |


---

### 🔐 Checksums, Hashing &amp; Error Detection


| Algorithm                         | Repository                                                                                                | Description             |
| --------------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------- |
| **Adler-32**                      | [Ada-Adler-32](https://github.com/RobertBoettcherSF/Ada-Adler-32)                                         | Checksum algorithm      |
| **Cyclic Redundancy Check**       | [Ada-Cyclic-Redundancy-Check](https://github.com/RobertBoettcherSF/Ada-Cyclic-Redundancy-Check)           | Error-detecting code    |
| **Damm Algorithm**                | [Ada-Damm-Algorithm](https://github.com/RobertBoettcherSF/Ada-Damm-Algorithm)                             | Check digit algorithm   |
| **Fletcher's Checksum**           | [Ada-Fletchers-Checksum](https://github.com/RobertBoettcherSF/Ada-Fletchers-Checksum)                     | Checksum algorithm      |
| **Fowler-Noll-Vo**                | [Ada-Fowler-Noll-Vo](https://github.com/RobertBoettcherSF/Ada-Fowler-Noll-Vo)                             | Hash function           |
| **Hash Functions**                | [Ada-Hash-Functions](https://github.com/RobertBoettcherSF/Ada-Hash-Functions)                             | Hash functions          |
| **Longitudinal Redundancy Check** | [Ada-Longitudinal-Redundacy-Check](https://github.com/RobertBoettcherSF/Ada-Longitudinal-Redundacy-Check) | Error-detecting code    |
| **Luhn Algorithm**                | [Ada-Luhn-Algorithm](https://github.com/RobertBoettcherSF/Ada-Luhn-Algorithm)                             | Check digit algorithm   |
| **Luhn Mod N**                    | [Ada-Luhn-Mod-N-Algorithm](https://github.com/RobertBoettcherSF/Ada-Luhn-Mod-N-Algorithm)                 | Check digit algorithm   |
| **Parity Bit**                    | [Ada-Parity-Bit](https://github.com/RobertBoettcherSF/Ada-Parity-Bit)                                     | Error-detecting bit     |
| **Redundancy Checks**             | [Ada-Redundancy-Checks](https://github.com/RobertBoettcherSF/Ada-Redundancy-Checks)                       | Error-detection schemes |
| **Verhoeff Algorithm**            | [Ada-Verhoeff-Algorithm](https://github.com/RobertBoettcherSF/Ada-Verhoeff-Algorithm)                     | Check digit algorithm   |


---

### 🗄️ Database Algorithms


| Algorithm                         | Repository                                                                                                  | Description                 |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------- | --------------------------- |
| **Block Nested Loop Join**        | [Ada-Block-Nested-Loop](https://github.com/RobertBoettcherSF/Ada-Block-Nested-Loop)                         | Database join algorithm     |
| **Chase Algorithm**               | [Ada-Chase](https://github.com/RobertBoettcherSF/Ada-Chase)                                                 | Data-dependency reasoning   |
| **Hash Join**                     | [Ada-Hash-Join](https://github.com/RobertBoettcherSF/Ada-Hash-Join)                                         | Database join algorithm     |
| **Intersection Algorithm**        | [Ada-Intersection-Algorithm](https://github.com/RobertBoettcherSF/Ada-Intersection-Algorithm)               | Set/relational intersection |
| **Nested Loop Join**              | [Ada-Nested-Loop-Join](https://github.com/RobertBoettcherSF/Ada-Nested-Loop-Join)                           | Database join algorithm     |
| **Recovery Exploiting Semantics** | [Ada-Recovery-Exploiting-Semantics](https://github.com/RobertBoettcherSF/Ada-Recovery-Exploiting-Semantics) | ARIES recovery algorithm    |
| **Sort-Merge Join**               | [Ada-Sort-Merge-Join](https://github.com/RobertBoettcherSF/Ada-Sort-Merge-Join)                             | Database join algorithm     |


---

### 🎲 Game Theory Algorithms


| Algorithm               | Repository                                                                              | Description                  |
| ----------------------- | --------------------------------------------------------------------------------------- | ---------------------------- |
| **Fictitious Play**     | [Ada-Fictitious-Play](https://github.com/RobertBoettcherSF/Ada-Fictitious-Play)         | Learning in games            |
| **Lemke-Howson**        | [Ada-Lemke-Howson](https://github.com/RobertBoettcherSF/Ada-Lemke-Howson)               | Nash equilibrium computation |
| **Regret Minimization** | [Ada-Regret-Minimization](https://github.com/RobertBoettcherSF/Ada-Regret-Minimization) | Strategy learning            |
| **Replicator Equation** | [Ada-Replicator-Equation](https://github.com/RobertBoettcherSF/Ada-Replicator-Equation) | Evolutionary game dynamics   |
| **Gale–Shapley** | [Ada-Gale-Shapley-Algorithm](https://github.com/RobertBoettcherSF/Ada-Gale-Shapley-Algorithm) | Stable matching / deferred acceptance |
| **Shapley Value** | [Ada-Shapley-Value](https://github.com/RobertBoettcherSF/Ada-Shapley-Value) | Cooperative game fair allocation |
| **Core** | [Ada-Core](https://github.com/RobertBoettcherSF/Ada-Core) | Core of a cooperative game |
| **Nucleolus** | [Ada-Nucleolus](https://github.com/RobertBoettcherSF/Ada-Nucleolus) | Leximin excess solution concept |
| **Banzhaf Power Index** | [Ada-Banzhaf-Power-Index](https://github.com/RobertBoettcherSF/Ada-Banzhaf-Power-Index) | Voting power / swing coalitions |
| **Correlated Equilibrium** | [Ada-Correlated-Equilibrium](https://github.com/RobertBoettcherSF/Ada-Correlated-Equilibrium) | Aumann correlated equilibrium |
| **Bayesian Nash Equilibrium** | [Ada-Bayesian-Nash-Equilibrium](https://github.com/RobertBoettcherSF/Ada-Bayesian-Nash-Equilibrium) | Incomplete-information Nash |
| **Backward Induction** | [Ada-Backward-Induction](https://github.com/RobertBoettcherSF/Ada-Backward-Induction) | Extensive-form perfect-information solve |
| **Monte Carlo Tree Search** | [Ada-Monte-Carlo-Tree-Search](https://github.com/RobertBoettcherSF/Ada-Monte-Carlo-Tree-Search) | UCT tree search for games |
| **Multiplicative Weight Update** | [Ada-Multiplicative-Weight-Update-Method](https://github.com/RobertBoettcherSF/Ada-Multiplicative-Weight-Update-Method) | Online learning / Hedge |
| **Mirror Descent** | [Ada-Mirror-Descent](https://github.com/RobertBoettcherSF/Ada-Mirror-Descent) | First-order optimization / online learning |
| **Mean-Field Game** | [Ada-Mean-Field-Game](https://github.com/RobertBoettcherSF/Ada-Mean-Field-Game) | Continuum limit of large games |
| **Potential Game** | [Ada-Potential-Game](https://github.com/RobertBoettcherSF/Ada-Potential-Game) | Exact/ordinal potential games |
| **Vickrey–Clarke–Groves** | [Ada-Vickrey-Clarke-Groves-Mechanism](https://github.com/RobertBoettcherSF/Ada-Vickrey-Clarke-Groves-Mechanism) | Truthful mechanism design (VCG) |
| **Combinatorial Auction** | [Ada-Combinatorial-Auction](https://github.com/RobertBoettcherSF/Ada-Combinatorial-Auction) | Bundle bids / winner determination |
| **Top Trading Cycle** | [Ada-Top-Trading-Cycle](https://github.com/RobertBoettcherSF/Ada-Top-Trading-Cycle) | Housing-market allocation (TTC) |


---

### ⚙️ Compiler, Hardware &amp; Logic Algorithms


| Algorithm           | Repository                                                                                          | Description                |
| ------------------- | --------------------------------------------------------------------------------------------------- | -------------------------- |
| **Quine-McCluskey** | [Ada-Quine-McCluskey-Algorithm](https://github.com/RobertBoettcherSF/Ada-Quine-McCluskey-Algorithm) | Boolean logic minimization |
| **Sethi-Ullman**    | [Ada-Sethi-Ullman-Algorithm](https://github.com/RobertBoettcherSF/Ada-Sethi-Ullman-Algorithm)       | Compiler code generation   |
| **Tomasulo**        | [Ada-Tomasulo-Algorithm](https://github.com/RobertBoettcherSF/Ada-Tomasulo-Algorithm)               | Out-of-order execution     |


---

### ✅ Satisfiability &amp; Term Rewriting


| Algorithm | Repository | Description |
| --- | --- | --- |
| **DPLL** | [Ada-DPLL](https://github.com/RobertBoettcherSF/Ada-DPLL) | Davis–Putnam–Logemann–Loveland SAT |
| **Knuth–Bendix** | [Ada-Knuth-Bendix-Completion](https://github.com/RobertBoettcherSF/Ada-Knuth-Bendix-Completion) | Term-rewriting completion |


---

### 🔢 Mathematical &amp; Data Processing Algorithms


| Algorithm                           | Repository                                                                                                                  | Description                       |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| **Apriori**                         | [Apriori-Hadoop-Data-Structures-Ada](https://github.com/RobertBoettcherSF/Apriori-Hadoop-Data-Structures-Ada)               | Association rule learning         |
| **Double Dabble**                   | [Ada-Double-Dabble](https://github.com/RobertBoettcherSF/Ada-Double-Dabble)                                                 | BCD to binary conversion          |
| **Elser Difference Map**            | [Ada-Elser-Difference-Map-Algorithm](https://github.com/RobertBoettcherSF/Ada-Elser-Difference-Map-Algorithm)               | Phase retrieval algorithm         |
| **Exponential Backoff**             | [Ada-Exponential-Backoff](https://github.com/RobertBoettcherSF/Ada-Exponential-Backoff)                                     | Network retry strategy            |
| **Fast Sequential Summation**       | [FastSequentialSummationAda](https://github.com/RobertBoettcherSF/FastSequentialSummationAda)                               | Efficient summation algorithms    |
| **Fortune's Algorithm**             | [Ada-Fortunes-Algorithm](https://github.com/RobertBoettcherSF/Ada-Fortunes-Algorithm)                                       | Voronoi diagram construction      |
| **Hamming Distance**                | [Ada-Hamming-Distance](https://github.com/RobertBoettcherSF/Ada-Hamming-Distance)                                           | Symbol difference count           |
| **Hamming Weight**                  | [Ada-Hamming-Weight](https://github.com/RobertBoettcherSF/Ada-Hamming-Weight)                                               | Population count                  |
| **Karn's**                          | [Ada-Karn-Algorithm](https://github.com/RobertBoettcherSF/Ada-Karn-Algorithm)                                               | Random number generation          |
| **Level Set Method**                | [Ada-Level-Set-Method](https://github.com/RobertBoettcherSF/Ada-Level-Set-Method)                                           | PDE/level-set numerics            |
| **Marzullo's**                      | [Ada-Marzullos-Algorithm](https://github.com/RobertBoettcherSF/Ada-Marzullos-Algorithm)                                     | Distributed clock synchronization |
| **Mersenne Twister**                | [Ada-Mersenne-Twister](https://github.com/RobertBoettcherSF/Ada-Mersenne-Twister)                                           | Pseudorandom number generation    |
| **Pearson Hashing**                 | [Ada-Pearson-Hashing](https://github.com/RobertBoettcherSF/Ada-Pearson-Hashing)                                             | Hash function                     |
| **Risch Algorithm**                 | [Ada-Risch-Algorithm](https://github.com/RobertBoettcherSF/Ada-Risch-Algorithm)                                             | Symbolic integration              |
| **Samplesort**                      | [Ada-Samplesort](https://github.com/RobertBoettcherSF/Ada-Samplesort)                                                       | Sorting algorithm                 |
| **Secant Method**                   | [Ada-Secant-Method](https://github.com/RobertBoettcherSF/Ada-Secant-Method)                                                 | Root-finding                      |
| **Shortest Common Supersequence**   | [Ada-Shortest-Common-Supersequence-Problem](https://github.com/RobertBoettcherSF/Ada-Shortest-Common-Supersequence-Problem) | Sequence problem                  |
| **Sieve of Sundaram**               | [Ada-Sieve-Of-Sundaram](https://github.com/RobertBoettcherSF/Ada-Sieve-Of-Sundaram)                                         | Prime sieve                       |
| **Subset Sum**                      | [Ada-Subset-Sum-Algorithm](https://github.com/RobertBoettcherSF/Ada-Subset-Sum-Algorithm)                                   | NP-complete problem               |
| **Symbolic Cholesky Decomposition** | [Ada-Symbolic-Cholesky-Decomposition](https://github.com/RobertBoettcherSF/Ada-Symbolic-Cholesky-Decomposition)             | Sparse matrix decomposition       |
| **Tarski-Kuratowski**               | [Ada-Tarski-Kuratowski-Algorithm](https://github.com/RobertBoettcherSF/Ada-Tarski-Kuratowski-Algorithm)                     | Computability theory              |
| **Trigonometric Interpolation**     | [Ada-Trigonometric-Interpolation](https://github.com/RobertBoettcherSF/Ada-Trigonometric-Interpolation)                     | Interpolation                     |
| **Ukkonen's Algorithm**             | [Ada-Ukkonens-Algorithm](https://github.com/RobertBoettcherSF/Ada-Ukkonens-Algorithm)                                       | Suffix tree construction          |
| **Unicode Collation**               | [Ada-Unicode-Collation-Algorithm](https://github.com/RobertBoettcherSF/Ada-Unicode-Collation-Algorithm)                     | String comparison                 |
| **Unrestricted Algorithm**          | [Ada-Unrestricted-Algorithm](https://github.com/RobertBoettcherSF/Ada-Unrestricted-Algorithm)                               | General algorithm                 |
| **VEGAS Algorithm**                 | [Ada-VEGAS-Algorithm](https://github.com/RobertBoettcherSF/Ada-VEGAS-Algorithm)                                             | Monte Carlo integration           |
| **Verlet Integration**              | [Ada-Verlet-Integration](https://github.com/RobertBoettcherSF/Ada-Verlet-Integration)                                       | Numerical integration             |
| **Zeller's Congruence**             | [Ada-Zellers-Congruence-Algorithm](https://github.com/RobertBoettcherSF/Ada-Zellers-Congruence-Algorithm)                   | Day-of-week calculation           |
| **Ziggurat Algorithm**              | [Ada-Ziggurat-Algorithm](https://github.com/RobertBoettcherSF/Ada-Ziggurat-Algorithm)                                       | Random sampling                   |
| **Zobrist Hashing**                 | [Ada-Zobrist-Hashing](https://github.com/RobertBoettcherSF/Ada-Zobrist-Hashing)                                             | Hashing for game states           |


---

### 🏗️ System &amp; Network Algorithms


| Algorithm                                | Repository                                                                                                                | Description                               |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **Berkeley**                             | [Ada-Berkeley-Algorithm](https://github.com/RobertBoettcherSF/Ada-Berkeley-Algorithm)                                     | Clock synchronization                     |
| **cFS Rewrite**                          | [Ada-cFS](https://github.com/RobertBoettcherSF/Ada-cFS)                                                                   | NASA Core Flight System rewrite           |
| **Christians' Algorithm**                | [Ada-Cristians-Algorithm](https://github.com/RobertBoettcherSF/Ada-Cristians-Algorithm)                                   | Clock synchronization                     |
| **CHS Conversion**                       | [Ada-CHS-Conversion](https://github.com/RobertBoettcherSF/Ada-CHS-Conversion)                                             | Disk geometry conversion                  |
| **DASH PGAS**                            | [AdaPGAS](https://github.com/RobertBoettcherSF/AdaPGAS)                                                                   | Partitioned Global Address Space          |
| **FM-Index**                             | [fm\_index](https://github.com/RobertBoettcherSF/fm_index)                                                                | String matching with BWT                  |
| **Lulea's**                              | [Ada-Luleas-Algorithm](https://github.com/RobertBoettcherSF/Ada-Luleas-Algorithm)                                         | Distributed algorithm                     |
| **Page Replacement Algorithms**          | [Ada-page-replacement-algorithms](https://github.com/RobertBoettcherSF/Ada-page-replacement-algorithms)                   | Collection of page replacement strategies |
| **Proof-of-Work Algorithms**             | [Ada-Proof-Of-Work-Algorithms](https://github.com/RobertBoettcherSF/Ada-Proof-Of-Work-Algorithms)                         | Blockchain consensus                      |
| **Rate Limiter**                         | [rate\_limiter](https://github.com/RobertBoettcherSF/rate_limiter)                                                        | Operation throttling                      |
| **Truncated Binary Exponential Backoff** | [Ada-Truncated-Binary-Exponential-Backoff](https://github.com/RobertBoettcherSF/Ada-Truncated-Binary-Exponential-Backoff) | Network retry strategy                    |
| **Watchdog Timer**                       | [watchdog\_timer](https://github.com/RobertBoettcherSF/watchdog_timer)                                                    | Safety-critical heartbeat monitor         |


---

### 🎓 Research &amp; Specialized Algorithms


| Algorithm                                      | Repository                                                                                                            | Description                                   |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| **Bayesian Network Learning**                  | [ada-spark-bayesian-network-learning](https://github.com/RobertBoettcherSF/ada-spark-bayesian-network-learning)       | Structure learning algorithms                 |
| **External Memory Graphs**                     | [spark-external-memory-graphs](https://github.com/RobertBoettcherSF/spark-external-memory-graphs)                     | Graph algorithms for massive datasets         |
| **FMM Data Structures**                        | [spark-fmm-data-structures](https://github.com/RobertBoettcherSF/spark-fmm-data-structures)                           | Fast Multipole Method data structures         |
| **Imaginary Sliding Window**                   | [isw-spark](https://github.com/RobertBoettcherSF/isw-spark)                                                           | Memory-efficient sliding window (SPARK)       |
| **Latin Squares**                              | [spark-latin-squares](https://github.com/RobertBoettcherSF/spark-latin-squares)                                       | Partial Latin square modeling (SPARK)         |
| **Mission Clock**                              | [mission-clock](https://github.com/RobertBoettcherSF/mission-clock)                                                   | High-resolution time tracking                 |
| **Peer Grading Algorithms**                    | [Ada\_Peer\_Grading\_Algorithms](https://github.com/RobertBoettcherSF/Ada_Peer_Grading_Algorithms)                    | Educational peer grading                      |
| **Permutation Groups**                         | [perm\_groups](https://github.com/RobertBoettcherSF/perm_groups)                                                      | Knuth's algorithms for permutation groups     |
| **Resilient Algorithms &amp; Data Structures** | [Resilient-Algorithms-Data-Structures](https://github.com/RobertBoettcherSF/Resilient-Algorithms-Data-Structures)     | Fault-resilient sorting &amp; priority queues |
| **Texas Medication Algorithm**                 | [Ada-Texas-Medication-Algorithm-Project](https://github.com/RobertBoettcherSF/Ada-Texas-Medication-Algorithm-Project) | Clinical decision algorithms                  |
| **Variational Quantum Eigensolver**            | [Ada-Variational-Quantum-Eigensolver](https://github.com/RobertBoettcherSF/Ada-Variational-Quantum-Eigensolver)       | Quantum eigenvalue computation                |
| **Winnow Algorithm**                           | [Ada-Winnow-Algorithm](https://github.com/RobertBoettcherSF/Ada-Winnow-Algorithm)                                     | Machine learning classification               |


---

### 🧮 Parsing &amp; Compilation Algorithms


| Algorithm                         | Repository                                                                                                                      | Description                                    |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Simple LR Parser**              | [Ada-Simple-LR-Parser](https://github.com/RobertBoettcherSF/Ada-Simple-LR-Parser)                                               | Simple LR parser in Ada                        |
| **Simple Precedence Parser**      | [Ada-Simple-Precdence-Parser](https://github.com/RobertBoettcherSF/Ada-Simple-Precdence-Parser)                                 | Simple precedence parser in Ada                |
| **Packrat Parser**                | [Ada-Packrat-Parser](https://github.com/RobertBoettcherSF/Ada-Packrat-Parser)                                                   | Packrat parser in Ada                          |
| **Pratt Parser**                  | [Ada-Pratt-Parser](https://github.com/RobertBoettcherSF/Ada-Pratt-Parser)                                                       | Pratt parser in Ada                            |
| **Recursive Descent Parser**      | [Ada-Recursive-Descent-Parser](https://github.com/RobertBoettcherSF/Ada-Recursive-Descent-Parser)                               | Recursive descent parser in Ada                |
| **Shunting-Yard Algorithm**       | [Ada-Shunting-Yard-Algorithm](https://github.com/RobertBoettcherSF/Ada-Shunting-Yard-Algorithm)                                 | Shunting-yard algorithm in Ada                 |
| **Hindley-Milner Type Inference** | [Ada-Hindley-Milner-Type-Inference-Algorithm](https://github.com/RobertBoettcherSF/Ada-Hindley-Milner-Type-Inference-Algorithm) | Hindley-Milner type inference algorithm in Ada |


---

### ⚛️ Quantum Algorithms


| Algorithm                           | Repository                                                                                                            | Description                               |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| **Aharonov-Jones-Landau**           | [Ada-Aharonov-Jones-Landau-Algorithm](https://github.com/RobertBoettcherSF/Ada-Aharonov-Jones-Landau-Algorithm)       | Aharonov-Jones-Landau algorithm in Ada    |
| **Amplitude Amplification**         | [Ada-Amplitude-Amplification](https://github.com/RobertBoettcherSF/Ada-Amplitude-Amplification)                       | Amplitude amplification in Ada            |
| **Bernstein-Varizani**              | [Ada-Bernstein-Varizani-Algorithm](https://github.com/RobertBoettcherSF/Ada-Bernstein-Varizani-Algorithm)             | Bernstein-Varizani algorithm in Ada       |
| **BHT Algorithm**                   | [Ada-BHT-Algorithm](https://github.com/RobertBoettcherSF/Ada-BHT-Algorithm)                                           | BHT algorithm in Ada                      |
| **Boson Sampling**                  | [Ada-Boson-Sampling](https://github.com/RobertBoettcherSF/Ada-Boson-Sampling)                                         | Boson sampling in Ada                     |
| **Chaitin's Algorithm**             | [Ada-Chaitins-Algorithm](https://github.com/RobertBoettcherSF/Ada-Chaitins-Algorithm)                                 | Chaitin's algorithm in Ada                |
| **Deutsch-Josza**                   | [Ada-Deutsch-Josza-Algorithm](https://github.com/RobertBoettcherSF/Ada-Deutsch-Josza-Algorithm)                       | Deutsch-Josza algorithm in Ada            |
| **Grover's Algorithm**              | [Ada-Grovers-Algorithm](https://github.com/RobertBoettcherSF/Ada-Grovers-Algorithm)                                   | Grover's algorithm in Ada                 |
| **Hadamard Test**                   | [Ada-Hadamard-Test](https://github.com/RobertBoettcherSF/Ada-Hadamard-Test)                                           | Hadamard test in Ada                      |
| **Hadamard Transform**              | [Ada-Hadamard-Transform](https://github.com/RobertBoettcherSF/Ada-Hadamard-Transform)                                 | Hadamard transform in Ada                 |
| **Hamiltonian Simulation**          | [Ada-Hamiltonian-Simulation](https://github.com/RobertBoettcherSF/Ada-Hamiltonian-Simulation)                         | Hamiltonian simulation in Ada             |
| **HHL Algorithm**                   | [Ada-HHL-Algorithm](https://github.com/RobertBoettcherSF/Ada-HHL-Algorithm)                                           | HHL algorithm in Ada                      |
| **Hidden Linear Function Problem**  | [Ada-Hidden-Linear-Function-Problem](https://github.com/RobertBoettcherSF/Ada-Hidden-Linear-Function-Problem)         | Hidden linear function problem in Ada     |
| **Hidden Shift Problem**            | [Ada-Hidden-Shift-Problem](https://github.com/RobertBoettcherSF/Ada-Hidden-Shift-Problem)                             | Hidden shift problem in Ada               |
| **Hidden Subgroup Problem**         | [Ada-Hidden-Subgroup-Problem](https://github.com/RobertBoettcherSF/Ada-Hidden-Subgroup-Problem)                       | Hidden subgroup problem in Ada            |
| **Non-Local Quantum Computation**   | [Ada-Non-Local-Quantum-Computation](https://github.com/RobertBoettcherSF/Ada-Non-Local-Quantum-Computation)           | Non-local quantum computation in Ada      |
| **Quantum Annealing**               | [Ada-Quantum-Annealing](https://github.com/RobertBoettcherSF/Ada-Quantum-Annealing)                                   | Quantum annealing in Ada                  |
| **Quantum Artificial Life**         | [Ada-Quantum-Artificial-Life](https://github.com/RobertBoettcherSF/Ada-Quantum-Artificial-Life)                       | Quantum artificial life in Ada            |
| **Quantum Counting**                | [Ada-Quantum-Counting-Algorithm](https://github.com/RobertBoettcherSF/Ada-Quantum-Counting-Algorithm)                 | Quantum counting algorithm in Ada         |
| **Quantum Fourier Transform**       | [Ada-Quantum-Fourier-Transform](https://github.com/RobertBoettcherSF/Ada-Quantum-Fourier-Transform)                   | Quantum Fourier transform in Ada          |
| **Quantum Optimization Algorithms** | [Ada-Quantum-Optimization-Algorithms](https://github.com/RobertBoettcherSF/Ada-Quantum-Optimization-Algorithms)       | Quantum optimization algorithms in Ada    |
| **Quantum Phase Estimation**        | [Ada-Quantum-Phase-Estimation-Algorithm](https://github.com/RobertBoettcherSF/Ada-Quantum-Phase-Estimation-Algorithm) | Quantum phase estimation algorithm in Ada |


---


### 🎰 Pseudorandom Number Generators


| Algorithm | Repository | Description |
| --- | --- | --- |
| **Linear Congruential Generator** | [Ada-Linear-Congruential-Generator](https://github.com/RobertBoettcherSF/Ada-Linear-Congruential-Generator) | Classic LCG family |
| **Lagged Fibonacci Generator** | [Ada-Lagged-Fibonacci-Generator](https://github.com/RobertBoettcherSF/Ada-Lagged-Fibonacci-Generator) | Lagged Fibonacci PRNG |
| **ACORN Generator** | [Ada-ACORN-Generator](https://github.com/RobertBoettcherSF/Ada-ACORN-Generator) | Additive congruential PRNG (Wikramaratna) |
| **Blum Blum Shub** | [Ada-Blum-Blum-Shub](https://github.com/RobertBoettcherSF/Ada-Blum-Blum-Shub) | Cryptographic PRNG |
| **Pseudorandom Number Generator** | [Ada-Pseudorandom-Number-Generator](https://github.com/RobertBoettcherSF/Ada-Pseudorandom-Number-Generator) | PRNG survey (LCG / LFG / xorshift) |
| **Floyd’s Cycle-Finding** | [Ada-Floyds-Cycle-Finding-Algorithm](https://github.com/RobertBoettcherSF/Ada-Floyds-Cycle-Finding-Algorithm) | Tortoise-and-hare cycle detection |
| **Brent’s Algorithm** | [Ada-Brents-Algorithm](https://github.com/RobertBoettcherSF/Ada-Brents-Algorithm) | Cycle detection (power-of-two teleports) |


### 🧠 Markov Decision Processes & Reinforcement Learning


| Algorithm | Repository | Description |
| --- | --- | --- |
| **Value Iteration** | [Ada-Value-Iteration](https://github.com/RobertBoettcherSF/Ada-Value-Iteration) | MDP Bellman optimality iteration |
| **Policy Iteration** | [Ada-Policy-Iteration](https://github.com/RobertBoettcherSF/Ada-Policy-Iteration) | Howard policy evaluation / improvement |


### 📐 Convex Optimization & Matrix Scaling


| Algorithm | Repository | Description |
| --- | --- | --- |
| **Ellipsoid Method** | [Ada-Ellipsoid-Method](https://github.com/RobertBoettcherSF/Ada-Ellipsoid-Method) | Convex optimization via shrinking ellipsoids |
| **Birkhoff–von Neumann** | [Ada-Birkhoff-von-Neumann](https://github.com/RobertBoettcherSF/Ada-Birkhoff-von-Neumann) | Doubly stochastic → permutation decomposition |
| **Sinkhorn–Knopp** | [Ada-Sinkhorn-Knopp-Algorithm](https://github.com/RobertBoettcherSF/Ada-Sinkhorn-Knopp-Algorithm) | Matrix scaling to doubly stochastic form |


### 🧠 Machine Learning &amp; Optimization


| Algorithm | Repository | Description |
| --- | --- | --- |
| **Backpropagation** | [Ada-Backpropagation](https://github.com/RobertBoettcherSF/Ada-Backpropagation) | Neural-net backprop training |
| **Gradient Descent** | [Ada-Gradient-Descent](https://github.com/RobertBoettcherSF/Ada-Gradient-Descent) | Educational GD; SPARK L2 via `Gradient_Descent_Spark` |
| **Softmax** | [Ada-SPARK-Softmax](https://github.com/RobertBoettcherSF/Ada-SPARK-Softmax) | Softmax activation (SPARK) |


---

### 📦 Collections &amp; Frameworks


| Repository                                                                    | Description                                             |
| ----------------------------------------------------------------------------- | ------------------------------------------------------- |
| [ada-code-examples](https://github.com/RobertBoettcherSF/ada-code-examples)   | Collection of working Ada code                          |
| [ada-language-guide](https://github.com/RobertBoettcherSF/ada-language-guide) | Guide to the Ada programming language                   |
| [skip\_list](https://github.com/RobertBoettcherSF/skip_list)                  | Skip List — probabilistic alternative to balanced trees |
| [Sternenfisch-Diary](https://github.com/RobertBoettcherSF/Sternenfisch-Diary) | A diary by Sternenfisch                                 |


---

## 🎯 Project Status

**Active Development**: Continuously implementing algorithms from the [Wikipedia List of Algorithms](https://en.wikipedia.org/wiki/List_of_algorithms) in Ada and Ada SPARK for formal verification and safety-critical applications.

**2026-09-20**: ICEYE-adjacent SPARK L2 tranche (Connected-Component-Labeling 18/18, Median-Filtering 34/34, Cooley-Tukey-FFT 45/45) plus clean-room **Ada-SPARK-PN-Counter** CRDT sheet (23/23). Featured also keeps **Ada Logistics Module** and **rogue_engine**. SPARK L2 ports on DPLL / Knuth–Bendix / Backpropagation / Gradient Descent. Ada-SPARK catalog continues (~926+ public `Ada-SPARK-*` repos).

**Year**: 2026

---

*"The only way to make software reliable is to make it verifiable."* — [Tony Hoare](https://en.wikipedia.org/wiki/Tony_Hoare)


<!-- ADA-CATALOG:SPARK-BEGIN -->
## ✅ Ada SPARK Level 4 Ports

Formally verified educational packages (`gnatprove` Level 4). Companion plain-Ada repos often exist without the `SPARK` infix.


---

### All Ada-SPARK repositories


| Package | Repository |
| --- | --- |
| **01 Matrix** | [Ada-SPARK-01-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-01-Matrix) |
| **132 Pattern** | [Ada-SPARK-132-Pattern](https://github.com/RobertBoettcherSF/Ada-SPARK-132-Pattern) |
| **3Sum Closest** | [Ada-SPARK-3Sum-Closest](https://github.com/RobertBoettcherSF/Ada-SPARK-3Sum-Closest) |
| **4Sum II** | [Ada-SPARK-4Sum-II](https://github.com/RobertBoettcherSF/Ada-SPARK-4Sum-II) |
| **A Star** | [Ada-SPARK-A-Star](https://github.com/RobertBoettcherSF/Ada-SPARK-A-Star) |
| **ACORN Generator** | [Ada-SPARK-ACORN-Generator](https://github.com/RobertBoettcherSF/Ada-SPARK-ACORN-Generator) |
| **Accounts Merge Lite** | [Ada-SPARK-Accounts-Merge-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Accounts-Merge-Lite) |
| **Accounts Merge Stub** | [Ada-SPARK-Accounts-Merge-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Accounts-Merge-Stub) |
| **Accumulator** | [Ada-SPARK-Accumulator](https://github.com/RobertBoettcherSF/Ada-SPARK-Accumulator) |
| **Add Binary** | [Ada-SPARK-Add-Binary](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Binary) |
| **Add Digits** | [Ada-SPARK-Add-Digits](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Digits) |
| **Add Strings** | [Ada-SPARK-Add-Strings](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Strings) |
| **Add Two Numbers** | [Ada-SPARK-Add-Two-Numbers](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Two-Numbers) |
| **Add Two Numbers II** | [Ada-SPARK-Add-Two-Numbers-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Two-Numbers-II) |
| **Add Without Plus** | [Ada-SPARK-Add-Without-Plus](https://github.com/RobertBoettcherSF/Ada-SPARK-Add-Without-Plus) |
| **Adler32** | [Ada-SPARK-Adler32](https://github.com/RobertBoettcherSF/Ada-SPARK-Adler32) |
| **Alert Using Same Key Card Stub** | [Ada-SPARK-Alert-Using-Same-Key-Card-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Alert-Using-Same-Key-Card-Stub) |
| **Alien Dictionary Lite** | [Ada-SPARK-Alien-Dictionary-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Alien-Dictionary-Lite) |
| **Alien Dictionary Stub** | [Ada-SPARK-Alien-Dictionary-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Alien-Dictionary-Stub) |
| **All Paths From Source To Target** | [Ada-SPARK-All-Paths-From-Source-To-Target](https://github.com/RobertBoettcherSF/Ada-SPARK-All-Paths-From-Source-To-Target) |
| **Argmax** | [Ada-SPARK-Argmax](https://github.com/RobertBoettcherSF/Ada-SPARK-Argmax) |
| **Arranging Coins** | [Ada-SPARK-Arranging-Coins](https://github.com/RobertBoettcherSF/Ada-SPARK-Arranging-Coins) |
| **Array Partition I** | [Ada-SPARK-Array-Partition-I](https://github.com/RobertBoettcherSF/Ada-SPARK-Array-Partition-I) |
| **As Far From Land As Possible** | [Ada-SPARK-As-Far-From-Land-As-Possible](https://github.com/RobertBoettcherSF/Ada-SPARK-As-Far-From-Land-As-Possible) |
| **Assign Cookies** | [Ada-SPARK-Assign-Cookies](https://github.com/RobertBoettcherSF/Ada-SPARK-Assign-Cookies) |
| **Asteroid Collision** | [Ada-SPARK-Asteroid-Collision](https://github.com/RobertBoettcherSF/Ada-SPARK-Asteroid-Collision) |
| **Authentication Manager Stub** | [Ada-SPARK-Authentication-Manager-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Authentication-Manager-Stub) |
| **Available Captures For Rook** | [Ada-SPARK-Available-Captures-For-Rook](https://github.com/RobertBoettcherSF/Ada-SPARK-Available-Captures-For-Rook) |
| **Average Of Levels In Binary Tree** | [Ada-SPARK-Average-Of-Levels-In-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Average-Of-Levels-In-Binary-Tree) |
| **BST Insert Search** | [Ada-SPARK-BST-Insert-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-BST-Insert-Search) |
| **BST Iterator Stub** | [Ada-SPARK-BST-Iterator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-BST-Iterator-Stub) |
| **Babylonian Sqrt** | [Ada-SPARK-Babylonian-Sqrt](https://github.com/RobertBoettcherSF/Ada-SPARK-Babylonian-Sqrt) |
| **Balanced Binary Tree** | [Ada-SPARK-Balanced-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Balanced-Binary-Tree) |
| **Bankers Algorithm** | [Ada-SPARK-Bankers-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Bankers-Algorithm) |
| **Base64 Decode** | [Ada-SPARK-Base64-Decode](https://github.com/RobertBoettcherSF/Ada-SPARK-Base64-Decode) |
| **Base64 Encode** | [Ada-SPARK-Base64-Encode](https://github.com/RobertBoettcherSF/Ada-SPARK-Base64-Encode) |
| **Baseball Game** | [Ada-SPARK-Baseball-Game](https://github.com/RobertBoettcherSF/Ada-SPARK-Baseball-Game) |
| **Basic Calculator** | [Ada-SPARK-Basic-Calculator](https://github.com/RobertBoettcherSF/Ada-SPARK-Basic-Calculator) |
| **Basic Calculator II** | [Ada-SPARK-Basic-Calculator-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Basic-Calculator-II) |
| **Basic Calculator Stub** | [Ada-SPARK-Basic-Calculator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Basic-Calculator-Stub) |
| **Bead Sort** | [Ada-SPARK-Bead-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Bead-Sort) |
| **Beautiful Arrangement** | [Ada-SPARK-Beautiful-Arrangement](https://github.com/RobertBoettcherSF/Ada-SPARK-Beautiful-Arrangement) |
| **Beautiful Array Lite** | [Ada-SPARK-Beautiful-Array-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Beautiful-Array-Lite) |
| **Bellman Ford Algorithm** | [Ada-SPARK-Bellman-Ford-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Bellman-Ford-Algorithm) |
| **Bellman Ford Lite** | [Ada-SPARK-Bellman-Ford-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Bellman-Ford-Lite) |
| **Best First Search** | [Ada-SPARK-Best-First-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Best-First-Search) |
| **Best Time To Buy And Sell Stock** | [Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock](https://github.com/RobertBoettcherSF/Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock) |
| **Best Time To Buy And Sell Stock II** | [Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock-II) |
| **Best Time To Buy And Sell Stock With Cooldownoldown** | [Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock-With-Cooldownoldown](https://github.com/RobertBoettcherSF/Ada-SPARK-Best-Time-To-Buy-And-Sell-Stock-With-Cooldownoldown) |
| **Binary GCD** | [Ada-SPARK-Binary-GCD](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-GCD) |
| **Binary Insertion Sort** | [Ada-SPARK-Binary-Insertion-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Insertion-Sort) |
| **Binary Number With Alternating Bits** | [Ada-SPARK-Binary-Number-With-Alternating-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Number-With-Alternating-Bits) |
| **Binary Search** | [Ada-SPARK-Binary-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Search) |
| **Binary Search Lower Bound** | [Ada-SPARK-Binary-Search-Lower-Bound](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Search-Lower-Bound) |
| **Binary Search Upper Bound** | [Ada-SPARK-Binary-Search-Upper-Bound](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Search-Upper-Bound) |
| **Binary To Integer** | [Ada-SPARK-Binary-To-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-To-Integer) |
| **Binary Tree Inorder** | [Ada-SPARK-Binary-Tree-Inorder](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Inorder) |
| **Binary Tree Level Order** | [Ada-SPARK-Binary-Tree-Level-Order](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Level-Order) |
| **Binary Tree Max Depth** | [Ada-SPARK-Binary-Tree-Max-Depth](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Max-Depth) |
| **Binary Tree Min Depth** | [Ada-SPARK-Binary-Tree-Min-Depth](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Min-Depth) |
| **Binary Tree Paths** | [Ada-SPARK-Binary-Tree-Paths](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Paths) |
| **Binary Tree Postorder** | [Ada-SPARK-Binary-Tree-Postorder](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Postorder) |
| **Binary Tree Preorder** | [Ada-SPARK-Binary-Tree-Preorder](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Preorder) |
| **Binary Tree Right Side View** | [Ada-SPARK-Binary-Tree-Right-Side-View](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Tree-Right-Side-View) |
| **Binary Watch** | [Ada-SPARK-Binary-Watch](https://github.com/RobertBoettcherSF/Ada-SPARK-Binary-Watch) |
| **Binomial Coefficient** | [Ada-SPARK-Binomial-Coefficient](https://github.com/RobertBoettcherSF/Ada-SPARK-Binomial-Coefficient) |
| **Bisection Method** | [Ada-SPARK-Bisection-Method](https://github.com/RobertBoettcherSF/Ada-SPARK-Bisection-Method) |
| **Bit Reversal** | [Ada-SPARK-Bit-Reversal](https://github.com/RobertBoettcherSF/Ada-SPARK-Bit-Reversal) |
| **Bitonic Sort** | [Ada-SPARK-Bitonic-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitonic-Sort) |
| **Bitonic Sorter** | [Ada-SPARK-Bitonic-Sorter](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitonic-Sorter) |
| **Bitset** | [Ada-SPARK-Bitset](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitset) |
| **Bitwise AND Of Numbers Range** | [Ada-SPARK-Bitwise-AND-Of-Numbers-Range](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitwise-AND-Of-Numbers-Range) |
| **Bitwise OR Of Numbers Range** | [Ada-SPARK-Bitwise-OR-Of-Numbers-Range](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitwise-OR-Of-Numbers-Range) |
| **Bitwise ORs Of Subarrays Lite** | [Ada-SPARK-Bitwise-ORs-Of-Subarrays-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitwise-ORs-Of-Subarrays-Lite) |
| **Bitwise XOR Of All Pairings** | [Ada-SPARK-Bitwise-XOR-Of-All-Pairings](https://github.com/RobertBoettcherSF/Ada-SPARK-Bitwise-XOR-Of-All-Pairings) |
| **Block Sort** | [Ada-SPARK-Block-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Block-Sort) |
| **Bloom Filter** | [Ada-SPARK-Bloom-Filter](https://github.com/RobertBoettcherSF/Ada-SPARK-Bloom-Filter) |
| **Blum Blum Shub** | [Ada-SPARK-Blum-Blum-Shub](https://github.com/RobertBoettcherSF/Ada-SPARK-Blum-Blum-Shub) |
| **Boats To Save People** | [Ada-SPARK-Boats-To-Save-People](https://github.com/RobertBoettcherSF/Ada-SPARK-Boats-To-Save-People) |
| **Bogosort** | [Ada-SPARK-Bogosort](https://github.com/RobertBoettcherSF/Ada-SPARK-Bogosort) |
| **Bounding Box** | [Ada-SPARK-Bounding-Box](https://github.com/RobertBoettcherSF/Ada-SPARK-Bounding-Box) |
| **Boyer Moore** | [Ada-SPARK-Boyer-Moore](https://github.com/RobertBoettcherSF/Ada-SPARK-Boyer-Moore) |
| **Bray Curtis** | [Ada-SPARK-Bray-Curtis](https://github.com/RobertBoettcherSF/Ada-SPARK-Bray-Curtis) |
| **Breadth First Search** | [Ada-SPARK-Breadth-First-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Breadth-First-Search) |
| **Brents Algorithm** | [Ada-SPARK-Brents-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Brents-Algorithm) |
| **Broken Calculator** | [Ada-SPARK-Broken-Calculator](https://github.com/RobertBoettcherSF/Ada-SPARK-Broken-Calculator) |
| **Browser History Stub** | [Ada-SPARK-Browser-History-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Browser-History-Stub) |
| **Bubble Sort** | [Ada-SPARK-Bubble-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Bubble-Sort) |
| **Bucket Sort** | [Ada-SPARK-Bucket-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Bucket-Sort) |
| **Buddy Memory Allocation** | [Ada-SPARK-Buddy-Memory-Allocation](https://github.com/RobertBoettcherSF/Ada-SPARK-Buddy-Memory-Allocation) |
| **Bulb Switcher** | [Ada-SPARK-Bulb-Switcher](https://github.com/RobertBoettcherSF/Ada-SPARK-Bulb-Switcher) |
| **Bulb Switcher Stub** | [Ada-SPARK-Bulb-Switcher-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Bulb-Switcher-Stub) |
| **Burrows Wheeler Transform** | [Ada-SPARK-Burrows-Wheeler-Transform](https://github.com/RobertBoettcherSF/Ada-SPARK-Burrows-Wheeler-Transform) |
| **Burstsort** | [Ada-SPARK-Burstsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Burstsort) |
| **Cooley Tukey FFT** | [Ada-SPARK-Cooley-Tukey-FFT](https://github.com/RobertBoettcherSF/Ada-SPARK-Cooley-Tukey-FFT) |
| **CRC32** | [Ada-SPARK-CRC32](https://github.com/RobertBoettcherSF/Ada-SPARK-CRC32) |
| **CSR Row Sum** | [Ada-SPARK-CSR-Row-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-CSR-Row-Sum) |
| **Can Place Flowers** | [Ada-SPARK-Can-Place-Flowers](https://github.com/RobertBoettcherSF/Ada-SPARK-Can-Place-Flowers) |
| **Canberra Distance** | [Ada-SPARK-Canberra-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Canberra-Distance) |
| **Candy** | [Ada-SPARK-Candy](https://github.com/RobertBoettcherSF/Ada-SPARK-Candy) |
| **Capacity To Ship Packages** | [Ada-SPARK-Capacity-To-Ship-Packages](https://github.com/RobertBoettcherSF/Ada-SPARK-Capacity-To-Ship-Packages) |
| **Car Pooling** | [Ada-SPARK-Car-Pooling](https://github.com/RobertBoettcherSF/Ada-SPARK-Car-Pooling) |
| **Cheapest Flights** | [Ada-SPARK-Cheapest-Flights](https://github.com/RobertBoettcherSF/Ada-SPARK-Cheapest-Flights) |
| **Cheapest Flights Stub** | [Ada-SPARK-Cheapest-Flights-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Cheapest-Flights-Stub) |
| **Cheapest Flights Within K Stops** | [Ada-SPARK-Cheapest-Flights-Within-K-Stops](https://github.com/RobertBoettcherSF/Ada-SPARK-Cheapest-Flights-Within-K-Stops) |
| **Chebyshev Distance** | [Ada-SPARK-Chebyshev-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Chebyshev-Distance) |
| **Check If Matrix Is X Matrix** | [Ada-SPARK-Check-If-Matrix-Is-X-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Check-If-Matrix-Is-X-Matrix) |
| **Check If Number Is A Sum Of Powers Of Three** | [Ada-SPARK-Check-If-Number-Is-A-Sum-Of-Powers-Of-Three](https://github.com/RobertBoettcherSF/Ada-SPARK-Check-If-Number-Is-A-Sum-Of-Powers-Of-Three) |
| **Check If The Sentence Is Pangram** | [Ada-SPARK-Check-If-The-Sentence-Is-Pangram](https://github.com/RobertBoettcherSF/Ada-SPARK-Check-If-The-Sentence-Is-Pangram) |
| **Check If Two String Arrays Are Equivalent** | [Ada-SPARK-Check-If-Two-String-Arrays-Are-Equivalent](https://github.com/RobertBoettcherSF/Ada-SPARK-Check-If-Two-String-Arrays-Are-Equivalent) |
| **Checksum Ones Complement** | [Ada-SPARK-Checksum-Ones-Complement](https://github.com/RobertBoettcherSF/Ada-SPARK-Checksum-Ones-Complement) |
| **Cherry Pickup Lite** | [Ada-SPARK-Cherry-Pickup-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Cherry-Pickup-Lite) |
| **Circle Sort** | [Ada-SPARK-Circle-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Circle-Sort) |
| **Circular Deque Stub** | [Ada-SPARK-Circular-Deque-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Circular-Deque-Stub) |
| **Circular Queue** | [Ada-SPARK-Circular-Queue](https://github.com/RobertBoettcherSF/Ada-SPARK-Circular-Queue) |
| **Clamp** | [Ada-SPARK-Clamp](https://github.com/RobertBoettcherSF/Ada-SPARK-Clamp) |
| **Climbing Stairs** | [Ada-SPARK-Climbing-Stairs](https://github.com/RobertBoettcherSF/Ada-SPARK-Climbing-Stairs) |
| **Clock Page Replacement** | [Ada-SPARK-Clock-Page-Replacement](https://github.com/RobertBoettcherSF/Ada-SPARK-Clock-Page-Replacement) |
| **Clone Graph** | [Ada-SPARK-Clone-Graph](https://github.com/RobertBoettcherSF/Ada-SPARK-Clone-Graph) |
| **Clone Graph Stub** | [Ada-SPARK-Clone-Graph-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Clone-Graph-Stub) |
| **Closest Pair Brute** | [Ada-SPARK-Closest-Pair-Brute](https://github.com/RobertBoettcherSF/Ada-SPARK-Closest-Pair-Brute) |
| **Cocktail Shaker Sort** | [Ada-SPARK-Cocktail-Shaker-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Cocktail-Shaker-Sort) |
| **Cocktail Sort** | [Ada-SPARK-Cocktail-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Cocktail-Sort) |
| **Coin Change** | [Ada-SPARK-Coin-Change](https://github.com/RobertBoettcherSF/Ada-SPARK-Coin-Change) |
| **Coin Change II** | [Ada-SPARK-Coin-Change-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Coin-Change-II) |
| **Comb Sort** | [Ada-SPARK-Comb-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Comb-Sort) |
| **Combination Iterator Stub** | [Ada-SPARK-Combination-Iterator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Combination-Iterator-Stub) |
| **Combination Sum** | [Ada-SPARK-Combination-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Combination-Sum) |
| **Combination Sum II** | [Ada-SPARK-Combination-Sum-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Combination-Sum-II) |
| **Combination Sum III** | [Ada-SPARK-Combination-Sum-III](https://github.com/RobertBoettcherSF/Ada-SPARK-Combination-Sum-III) |
| **Combination Sum IV** | [Ada-SPARK-Combination-Sum-IV](https://github.com/RobertBoettcherSF/Ada-SPARK-Combination-Sum-IV) |
| **Complement Of Base 10** | [Ada-SPARK-Complement-Of-Base-10](https://github.com/RobertBoettcherSF/Ada-SPARK-Complement-Of-Base-10) |
| **Complement Of Base 10 Integer** | [Ada-SPARK-Complement-Of-Base-10-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Complement-Of-Base-10-Integer) |
| **Compress String** | [Ada-SPARK-Compress-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Compress-String) |
| **Connected Component Labeling** | [Ada-SPARK-Connected-Component-Labeling](https://github.com/RobertBoettcherSF/Ada-SPARK-Connected-Component-Labeling) |
| **Construct Binary Tree From Inorder And Postorder Lite** | [Ada-SPARK-Construct-Binary-Tree-From-Inorder-And-Postorder-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Construct-Binary-Tree-From-Inorder-And-Postorder-Lite) |
| **Construct Binary Tree From Preorder And Inorder Lite** | [Ada-SPARK-Construct-Binary-Tree-From-Preorder-And-Inorder-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Construct-Binary-Tree-From-Preorder-And-Inorder-Lite) |
| **Container With Most Water** | [Ada-SPARK-Container-With-Most-Water](https://github.com/RobertBoettcherSF/Ada-SPARK-Container-With-Most-Water) |
| **Contains Duplicate** | [Ada-SPARK-Contains-Duplicate](https://github.com/RobertBoettcherSF/Ada-SPARK-Contains-Duplicate) |
| **Contains Duplicate II** | [Ada-SPARK-Contains-Duplicate-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Contains-Duplicate-II) |
| **Contiguous Array** | [Ada-SPARK-Contiguous-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Contiguous-Array) |
| **Continuous Subarray Sum** | [Ada-SPARK-Continuous-Subarray-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Continuous-Subarray-Sum) |
| **Convert 1D Array Into 2D Array** | [Ada-SPARK-Convert-1D-Array-Into-2D-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Convert-1D-Array-Into-2D-Array) |
| **Convert A Number To Hexadecimal** | [Ada-SPARK-Convert-A-Number-To-Hexadecimal](https://github.com/RobertBoettcherSF/Ada-SPARK-Convert-A-Number-To-Hexadecimal) |
| **Convert BST To Greater Tree** | [Ada-SPARK-Convert-BST-To-Greater-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Convert-BST-To-Greater-Tree) |
| **Convert Binary Number In A Linked List To Integer** | [Ada-SPARK-Convert-Binary-Number-In-A-Linked-List-To-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Convert-Binary-Number-In-A-Linked-List-To-Integer) |
| **Convert Sorted Array To BST** | [Ada-SPARK-Convert-Sorted-Array-To-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Convert-Sorted-Array-To-BST) |
| **Convex Hull Graham** | [Ada-SPARK-Convex-Hull-Graham](https://github.com/RobertBoettcherSF/Ada-SPARK-Convex-Hull-Graham) |
| **Copy List With Random Pointer Lite** | [Ada-SPARK-Copy-List-With-Random-Pointer-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Copy-List-With-Random-Pointer-Lite) |
| **Corporate Flight Bookings** | [Ada-SPARK-Corporate-Flight-Bookings](https://github.com/RobertBoettcherSF/Ada-SPARK-Corporate-Flight-Bookings) |
| **Cosine Distance** | [Ada-SPARK-Cosine-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Cosine-Distance) |
| **Cosine Similarity** | [Ada-SPARK-Cosine-Similarity](https://github.com/RobertBoettcherSF/Ada-SPARK-Cosine-Similarity) |
| **Count And Say** | [Ada-SPARK-Count-And-Say](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-And-Say) |
| **Count And Say Stub** | [Ada-SPARK-Count-And-Say-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-And-Say-Stub) |
| **Count Binary Substrings** | [Ada-SPARK-Count-Binary-Substrings](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Binary-Substrings) |
| **Count Complete Tree Nodes** | [Ada-SPARK-Count-Complete-Tree-Nodes](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Complete-Tree-Nodes) |
| **Count Negative Numbers In A Sorted Matrix** | [Ada-SPARK-Count-Negative-Numbers-In-A-Sorted-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Negative-Numbers-In-A-Sorted-Matrix) |
| **Count Odd Numbers In An Interval** | [Ada-SPARK-Count-Odd-Numbers-In-An-Interval](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Odd-Numbers-In-An-Interval) |
| **Count Of Smaller Numbers After Self Lite** | [Ada-SPARK-Count-Of-Smaller-Numbers-After-Self-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Of-Smaller-Numbers-After-Self-Lite) |
| **Count Operations To Obtain Zero** | [Ada-SPARK-Count-Operations-To-Obtain-Zero](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Operations-To-Obtain-Zero) |
| **Count Primes** | [Ada-SPARK-Count-Primes](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Primes) |
| **Count Primes Stub** | [Ada-SPARK-Count-Primes-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Primes-Stub) |
| **Count Sorted Vowel Strings** | [Ada-SPARK-Count-Sorted-Vowel-Strings](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Sorted-Vowel-Strings) |
| **Count Square Submatrices With All Ones** | [Ada-SPARK-Count-Square-Submatrices-With-All-Ones](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Square-Submatrices-With-All-Ones) |
| **Count Sub Islands** | [Ada-SPARK-Count-Sub-Islands](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Sub-Islands) |
| **Count The Number Of Consistent Strings** | [Ada-SPARK-Count-The-Number-Of-Consistent-Strings](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-The-Number-Of-Consistent-Strings) |
| **Count Triplets That Can Form Two Arrays Of Equal XOR** | [Ada-SPARK-Count-Triplets-That-Can-Form-Two-Arrays-Of-Equal-XOR](https://github.com/RobertBoettcherSF/Ada-SPARK-Count-Triplets-That-Can-Form-Two-Arrays-Of-Equal-XOR) |
| **Counting Bits** | [Ada-SPARK-Counting-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Counting-Bits) |
| **Counting Sort** | [Ada-SPARK-Counting-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Counting-Sort) |
| **Course Schedule** | [Ada-SPARK-Course-Schedule](https://github.com/RobertBoettcherSF/Ada-SPARK-Course-Schedule) |
| **Course Schedule II** | [Ada-SPARK-Course-Schedule-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Course-Schedule-II) |
| **Course Schedule II Stub** | [Ada-SPARK-Course-Schedule-II-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Course-Schedule-II-Stub) |
| **Covariance** | [Ada-SPARK-Covariance](https://github.com/RobertBoettcherSF/Ada-SPARK-Covariance) |
| **Crawler Log Folder** | [Ada-SPARK-Crawler-Log-Folder](https://github.com/RobertBoettcherSF/Ada-SPARK-Crawler-Log-Folder) |
| **Create Maximum Number Lite** | [Ada-SPARK-Create-Maximum-Number-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Create-Maximum-Number-Lite) |
| **Critical Connections In A Network Lite** | [Ada-SPARK-Critical-Connections-In-A-Network-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Critical-Connections-In-A-Network-Lite) |
| **Cycle Sort** | [Ada-SPARK-Cycle-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Cycle-Sort) |
| **Daily Temperatures** | [Ada-SPARK-Daily-Temperatures](https://github.com/RobertBoettcherSF/Ada-SPARK-Daily-Temperatures) |
| **Damerau Levenshtein Distance** | [Ada-SPARK-Damerau-Levenshtein-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Damerau-Levenshtein-Distance) |
| **Decode String** | [Ada-SPARK-Decode-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Decode-String) |
| **Decode String Stub** | [Ada-SPARK-Decode-String-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Decode-String-Stub) |
| **Decode Ways** | [Ada-SPARK-Decode-Ways](https://github.com/RobertBoettcherSF/Ada-SPARK-Decode-Ways) |
| **Decode Ways Stub** | [Ada-SPARK-Decode-Ways-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Decode-Ways-Stub) |
| **Decode XORed Array** | [Ada-SPARK-Decode-XORed-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Decode-XORed-Array) |
| **Defanging An IP Address** | [Ada-SPARK-Defanging-An-IP-Address](https://github.com/RobertBoettcherSF/Ada-SPARK-Defanging-An-IP-Address) |
| **Degree Of An Array** | [Ada-SPARK-Degree-Of-An-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Degree-Of-An-Array) |
| **Dekkers Algorithm** | [Ada-SPARK-Dekkers-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Dekkers-Algorithm) |
| **Delete And Earn** | [Ada-SPARK-Delete-And-Earn](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-And-Earn) |
| **Delete And Earn Stub** | [Ada-SPARK-Delete-And-Earn-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-And-Earn-Stub) |
| **Delete Node BST Stub** | [Ada-SPARK-Delete-Node-BST-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-Node-BST-Stub) |
| **Delete Node In A BST Lite** | [Ada-SPARK-Delete-Node-In-A-BST-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-Node-In-A-BST-Lite) |
| **Delete Node In A Linked List** | [Ada-SPARK-Delete-Node-In-A-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-Node-In-A-Linked-List) |
| **Delete Operation For Two Strings** | [Ada-SPARK-Delete-Operation-For-Two-Strings](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-Operation-For-Two-Strings) |
| **Delete The Middle Node** | [Ada-SPARK-Delete-The-Middle-Node](https://github.com/RobertBoettcherSF/Ada-SPARK-Delete-The-Middle-Node) |
| **Delta Encoding** | [Ada-SPARK-Delta-Encoding](https://github.com/RobertBoettcherSF/Ada-SPARK-Delta-Encoding) |
| **Deque Bounded** | [Ada-SPARK-Deque-Bounded](https://github.com/RobertBoettcherSF/Ada-SPARK-Deque-Bounded) |
| **Design A Leaderboard** | [Ada-SPARK-Design-A-Leaderboard](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-A-Leaderboard) |
| **Design A Stack With Increment** | [Ada-SPARK-Design-A-Stack-With-Increment](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-A-Stack-With-Increment) |
| **Design A Stack With Increment Operation** | [Ada-SPARK-Design-A-Stack-With-Increment-Operation](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-A-Stack-With-Increment-Operation) |
| **Design Add And Search Words** | [Ada-SPARK-Design-Add-And-Search-Words](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Add-And-Search-Words) |
| **Design An Ordered Stream** | [Ada-SPARK-Design-An-Ordered-Stream](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-An-Ordered-Stream) |
| **Design Bitset** | [Ada-SPARK-Design-Bitset](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Bitset) |
| **Design Browser History** | [Ada-SPARK-Design-Browser-History](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Browser-History) |
| **Design Circular Deque** | [Ada-SPARK-Design-Circular-Deque](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Circular-Deque) |
| **Design Circular Queue** | [Ada-SPARK-Design-Circular-Queue](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Circular-Queue) |
| **Design Circular Queue Stub** | [Ada-SPARK-Design-Circular-Queue-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Circular-Queue-Stub) |
| **Design Food Rating System** | [Ada-SPARK-Design-Food-Rating-System](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Food-Rating-System) |
| **Design Front Middle Back Queue** | [Ada-SPARK-Design-Front-Middle-Back-Queue](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Front-Middle-Back-Queue) |
| **Design Front Middle Back Queue Stub** | [Ada-SPARK-Design-Front-Middle-Back-Queue-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Front-Middle-Back-Queue-Stub) |
| **Design HashMap** | [Ada-SPARK-Design-HashMap](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-HashMap) |
| **Design HashMap Stub** | [Ada-SPARK-Design-HashMap-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-HashMap-Stub) |
| **Design HashSet** | [Ada-SPARK-Design-HashSet](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-HashSet) |
| **Design HashSet Stub** | [Ada-SPARK-Design-HashSet-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-HashSet-Stub) |
| **Design Hit Counter Lite** | [Ada-SPARK-Design-Hit-Counter-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Hit-Counter-Lite) |
| **Design Linked List** | [Ada-SPARK-Design-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Linked-List) |
| **Design Number Container System** | [Ada-SPARK-Design-Number-Container-System](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Number-Container-System) |
| **Design Ordered Stream** | [Ada-SPARK-Design-Ordered-Stream](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Ordered-Stream) |
| **Design Parking System II** | [Ada-SPARK-Design-Parking-System-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Parking-System-II) |
| **Design Skiplist Lite** | [Ada-SPARK-Design-Skiplist-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Skiplist-Lite) |
| **Design Twitter Lite** | [Ada-SPARK-Design-Twitter-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Twitter-Lite) |
| **Design Underground System Lite** | [Ada-SPARK-Design-Underground-System-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Design-Underground-System-Lite) |
| **Detect Capital** | [Ada-SPARK-Detect-Capital](https://github.com/RobertBoettcherSF/Ada-SPARK-Detect-Capital) |
| **Diagonal Traverse** | [Ada-SPARK-Diagonal-Traverse](https://github.com/RobertBoettcherSF/Ada-SPARK-Diagonal-Traverse) |
| **Diameter Of Binary Tree** | [Ada-SPARK-Diameter-Of-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Diameter-Of-Binary-Tree) |
| **Dice Coefficient** | [Ada-SPARK-Dice-Coefficient](https://github.com/RobertBoettcherSF/Ada-SPARK-Dice-Coefficient) |
| **Difference Array** | [Ada-SPARK-Difference-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Difference-Array) |
| **Different Ways To Add Parentheses Lite** | [Ada-SPARK-Different-Ways-To-Add-Parentheses-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Different-Ways-To-Add-Parentheses-Lite) |
| **Dijkstra Lite** | [Ada-SPARK-Dijkstra-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Dijkstra-Lite) |
| **Dijkstras Algorithm** | [Ada-SPARK-Dijkstras-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Dijkstras-Algorithm) |
| **Disjoint Set Forest** | [Ada-SPARK-Disjoint-Set-Forest](https://github.com/RobertBoettcherSF/Ada-SPARK-Disjoint-Set-Forest) |
| **Distinct Subsequences** | [Ada-SPARK-Distinct-Subsequences](https://github.com/RobertBoettcherSF/Ada-SPARK-Distinct-Subsequences) |
| **Divisor Game** | [Ada-SPARK-Divisor-Game](https://github.com/RobertBoettcherSF/Ada-SPARK-Divisor-Game) |
| **Domino And Tromino Tiling Lite** | [Ada-SPARK-Domino-And-Tromino-Tiling-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Domino-And-Tromino-Tiling-Lite) |
| **Dot Product** | [Ada-SPARK-Dot-Product](https://github.com/RobertBoettcherSF/Ada-SPARK-Dot-Product) |
| **Dungeon Game Lite** | [Ada-SPARK-Dungeon-Game-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Dungeon-Game-Lite) |
| **Duplicate Zeros** | [Ada-SPARK-Duplicate-Zeros](https://github.com/RobertBoettcherSF/Ada-SPARK-Duplicate-Zeros) |
| **Dutch National Flag** | [Ada-SPARK-Dutch-National-Flag](https://github.com/RobertBoettcherSF/Ada-SPARK-Dutch-National-Flag) |
| **Earliest Deadline First Scheduling** | [Ada-SPARK-Earliest-Deadline-First-Scheduling](https://github.com/RobertBoettcherSF/Ada-SPARK-Earliest-Deadline-First-Scheduling) |
| **Edit Distance** | [Ada-SPARK-Edit-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Edit-Distance) |
| **Elevator Algorithm** | [Ada-SPARK-Elevator-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Elevator-Algorithm) |
| **Eliminate Maximum Number Of Monsters** | [Ada-SPARK-Eliminate-Maximum-Number-Of-Monsters](https://github.com/RobertBoettcherSF/Ada-SPARK-Eliminate-Maximum-Number-Of-Monsters) |
| **Encode And Decode Strings Lite** | [Ada-SPARK-Encode-And-Decode-Strings-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Encode-And-Decode-Strings-Lite) |
| **Encode And Decode TinyURL Stub** | [Ada-SPARK-Encode-And-Decode-TinyURL-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Encode-And-Decode-TinyURL-Stub) |
| **Euclidean Algorithm** | [Ada-SPARK-Euclidean-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Euclidean-Algorithm) |
| **Euclidean Distance** | [Ada-SPARK-Euclidean-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Euclidean-Distance) |
| **Eval RPN** | [Ada-SPARK-Eval-RPN](https://github.com/RobertBoettcherSF/Ada-SPARK-Eval-RPN) |
| **Evaluate Division Lite** | [Ada-SPARK-Evaluate-Division-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Evaluate-Division-Lite) |
| **Evaluate Division Stub** | [Ada-SPARK-Evaluate-Division-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Evaluate-Division-Stub) |
| **Evaluate Reverse Polish Notation** | [Ada-SPARK-Evaluate-Reverse-Polish-Notation](https://github.com/RobertBoettcherSF/Ada-SPARK-Evaluate-Reverse-Polish-Notation) |
| **Excel Sheet Column** | [Ada-SPARK-Excel-Sheet-Column](https://github.com/RobertBoettcherSF/Ada-SPARK-Excel-Sheet-Column) |
| **Excel Sheet Column Number** | [Ada-SPARK-Excel-Sheet-Column-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Excel-Sheet-Column-Number) |
| **Excel Sheet Column Title** | [Ada-SPARK-Excel-Sheet-Column-Title](https://github.com/RobertBoettcherSF/Ada-SPARK-Excel-Sheet-Column-Title) |
| **Exchange Sort** | [Ada-SPARK-Exchange-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Exchange-Sort) |
| **Exclusive Time Of Functions Lite** | [Ada-SPARK-Exclusive-Time-Of-Functions-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Exclusive-Time-Of-Functions-Lite) |
| **Exponential Search** | [Ada-SPARK-Exponential-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Exponential-Search) |
| **Extended Euclidean** | [Ada-SPARK-Extended-Euclidean](https://github.com/RobertBoettcherSF/Ada-SPARK-Extended-Euclidean) |
| **Extended Euclidean Algorithm** | [Ada-SPARK-Extended-Euclidean-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Extended-Euclidean-Algorithm) |
| **FNV Hash** | [Ada-SPARK-FNV-Hash](https://github.com/RobertBoettcherSF/Ada-SPARK-FNV-Hash) |
| **Factorial** | [Ada-SPARK-Factorial](https://github.com/RobertBoettcherSF/Ada-SPARK-Factorial) |
| **Factorial Trailing Zeroes** | [Ada-SPARK-Factorial-Trailing-Zeroes](https://github.com/RobertBoettcherSF/Ada-SPARK-Factorial-Trailing-Zeroes) |
| **Fair Candy Swap** | [Ada-SPARK-Fair-Candy-Swap](https://github.com/RobertBoettcherSF/Ada-SPARK-Fair-Candy-Swap) |
| **Fast Pow** | [Ada-SPARK-Fast-Pow](https://github.com/RobertBoettcherSF/Ada-SPARK-Fast-Pow) |
| **Fibonacci DP** | [Ada-SPARK-Fibonacci-DP](https://github.com/RobertBoettcherSF/Ada-SPARK-Fibonacci-DP) |
| **Fibonacci Number** | [Ada-SPARK-Fibonacci-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Fibonacci-Number) |
| **Fibonacci Search** | [Ada-SPARK-Fibonacci-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Fibonacci-Search) |
| **Final Prices With A Special Discount** | [Ada-SPARK-Final-Prices-With-A-Special-Discount](https://github.com/RobertBoettcherSF/Ada-SPARK-Final-Prices-With-A-Special-Discount) |
| **Find All Anagrams In A String** | [Ada-SPARK-Find-All-Anagrams-In-A-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-All-Anagrams-In-A-String) |
| **Find All Duplicates In An Array** | [Ada-SPARK-Find-All-Duplicates-In-An-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-All-Duplicates-In-An-Array) |
| **Find All Numbers Disappeared** | [Ada-SPARK-Find-All-Numbers-Disappeared](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-All-Numbers-Disappeared) |
| **Find Center Of Star Graph** | [Ada-SPARK-Find-Center-Of-Star-Graph](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Center-Of-Star-Graph) |
| **Find Common Characters** | [Ada-SPARK-Find-Common-Characters](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Common-Characters) |
| **Find First And Last Position** | [Ada-SPARK-Find-First-And-Last-Position](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-First-And-Last-Position) |
| **Find If Path Exists In Graph** | [Ada-SPARK-Find-If-Path-Exists-In-Graph](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-If-Path-Exists-In-Graph) |
| **Find K Closest Elements** | [Ada-SPARK-Find-K-Closest-Elements](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-K-Closest-Elements) |
| **Find Median Data Stream Stub** | [Ada-SPARK-Find-Median-Data-Stream-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Median-Data-Stream-Stub) |
| **Find Median From Data Stream** | [Ada-SPARK-Find-Median-From-Data-Stream](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Median-From-Data-Stream) |
| **Find Median Sorted Arrays Lite** | [Ada-SPARK-Find-Median-Sorted-Arrays-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Median-Sorted-Arrays-Lite) |
| **Find Minimum In Rotated Sorted Array** | [Ada-SPARK-Find-Minimum-In-Rotated-Sorted-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Minimum-In-Rotated-Sorted-Array) |
| **Find Minimum In Rotated Sorted Array II** | [Ada-SPARK-Find-Minimum-In-Rotated-Sorted-Array-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Minimum-In-Rotated-Sorted-Array-II) |
| **Find Mode In BST** | [Ada-SPARK-Find-Mode-In-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Mode-In-BST) |
| **Find Peak Element** | [Ada-SPARK-Find-Peak-Element](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Peak-Element) |
| **Find The City** | [Ada-SPARK-Find-The-City](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-City) |
| **Find The City With Smallest Number Of Neighbors** | [Ada-SPARK-Find-The-City-With-Smallest-Number-Of-Neighbors](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-City-With-Smallest-Number-Of-Neighbors) |
| **Find The Difference** | [Ada-SPARK-Find-The-Difference](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-Difference) |
| **Find The Duplicate Number** | [Ada-SPARK-Find-The-Duplicate-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-Duplicate-Number) |
| **Find The Original Array Of Prefix XOR** | [Ada-SPARK-Find-The-Original-Array-Of-Prefix-XOR](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-Original-Array-Of-Prefix-XOR) |
| **Find The Smallest Divisor** | [Ada-SPARK-Find-The-Smallest-Divisor](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-Smallest-Divisor) |
| **Find The Town Judge** | [Ada-SPARK-Find-The-Town-Judge](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-The-Town-Judge) |
| **Find Words That Can Be Formed** | [Ada-SPARK-Find-Words-That-Can-Be-Formed](https://github.com/RobertBoettcherSF/Ada-SPARK-Find-Words-That-Can-Be-Formed) |
| **First Bad Version** | [Ada-SPARK-First-Bad-Version](https://github.com/RobertBoettcherSF/Ada-SPARK-First-Bad-Version) |
| **First Unique Char** | [Ada-SPARK-First-Unique-Char](https://github.com/RobertBoettcherSF/Ada-SPARK-First-Unique-Char) |
| **First Unique Character** | [Ada-SPARK-First-Unique-Character](https://github.com/RobertBoettcherSF/Ada-SPARK-First-Unique-Character) |
| **First Unique Character In A String** | [Ada-SPARK-First-Unique-Character-In-A-String](https://github.com/RobertBoettcherSF/Ada-SPARK-First-Unique-Character-In-A-String) |
| **Fisher Yates Shuffle** | [Ada-SPARK-Fisher-Yates-Shuffle](https://github.com/RobertBoettcherSF/Ada-SPARK-Fisher-Yates-Shuffle) |
| **Fixed Point Iteration** | [Ada-SPARK-Fixed-Point-Iteration](https://github.com/RobertBoettcherSF/Ada-SPARK-Fixed-Point-Iteration) |
| **Fizz Buzz** | [Ada-SPARK-Fizz-Buzz](https://github.com/RobertBoettcherSF/Ada-SPARK-Fizz-Buzz) |
| **Flash Sort** | [Ada-SPARK-Flash-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Flash-Sort) |
| **Flashsort** | [Ada-SPARK-Flashsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Flashsort) |
| **Flatten Binary Tree To Linked List Lite** | [Ada-SPARK-Flatten-Binary-Tree-To-Linked-List-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Flatten-Binary-Tree-To-Linked-List-Lite) |
| **Flatten Nested List Stub** | [Ada-SPARK-Flatten-Nested-List-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Flatten-Nested-List-Stub) |
| **Flipping An Image** | [Ada-SPARK-Flipping-An-Image](https://github.com/RobertBoettcherSF/Ada-SPARK-Flipping-An-Image) |
| **Flood Fill** | [Ada-SPARK-Flood-Fill](https://github.com/RobertBoettcherSF/Ada-SPARK-Flood-Fill) |
| **Floyd Warshall** | [Ada-SPARK-Floyd-Warshall](https://github.com/RobertBoettcherSF/Ada-SPARK-Floyd-Warshall) |
| **Floyd Warshall Lite** | [Ada-SPARK-Floyd-Warshall-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Floyd-Warshall-Lite) |
| **Floyds Cycle Finding Algorithm** | [Ada-SPARK-Floyds-Cycle-Finding-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Floyds-Cycle-Finding-Algorithm) |
| **Four Sum** | [Ada-SPARK-Four-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Four-Sum) |
| **Fruit Into Baskets** | [Ada-SPARK-Fruit-Into-Baskets](https://github.com/RobertBoettcherSF/Ada-SPARK-Fruit-Into-Baskets) |
| **Game Of Life Step** | [Ada-SPARK-Game-Of-Life-Step](https://github.com/RobertBoettcherSF/Ada-SPARK-Game-Of-Life-Step) |
| **Gas Station** | [Ada-SPARK-Gas-Station](https://github.com/RobertBoettcherSF/Ada-SPARK-Gas-Station) |
| **Gaussian Elimination** | [Ada-SPARK-Gaussian-Elimination](https://github.com/RobertBoettcherSF/Ada-SPARK-Gaussian-Elimination) |
| **Generate Parentheses** | [Ada-SPARK-Generate-Parentheses](https://github.com/RobertBoettcherSF/Ada-SPARK-Generate-Parentheses) |
| **Get Equal Substrings Within Budget** | [Ada-SPARK-Get-Equal-Substrings-Within-Budget](https://github.com/RobertBoettcherSF/Ada-SPARK-Get-Equal-Substrings-Within-Budget) |
| **Get Maximum In Generated Array** | [Ada-SPARK-Get-Maximum-In-Generated-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Get-Maximum-In-Generated-Array) |
| **Gnome Sort** | [Ada-SPARK-Gnome-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Gnome-Sort) |
| **Goat Latin** | [Ada-SPARK-Goat-Latin](https://github.com/RobertBoettcherSF/Ada-SPARK-Goat-Latin) |
| **Gray Code** | [Ada-SPARK-Gray-Code](https://github.com/RobertBoettcherSF/Ada-SPARK-Gray-Code) |
| **Greatest Common Divisor** | [Ada-SPARK-Greatest-Common-Divisor](https://github.com/RobertBoettcherSF/Ada-SPARK-Greatest-Common-Divisor) |
| **Group Anagrams** | [Ada-SPARK-Group-Anagrams](https://github.com/RobertBoettcherSF/Ada-SPARK-Group-Anagrams) |
| **Group Anagrams Stub** | [Ada-SPARK-Group-Anagrams-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Group-Anagrams-Stub) |
| **Grumpy Bookstore Owner** | [Ada-SPARK-Grumpy-Bookstore-Owner](https://github.com/RobertBoettcherSF/Ada-SPARK-Grumpy-Bookstore-Owner) |
| **Guess Number Higher Or Lower** | [Ada-SPARK-Guess-Number-Higher-Or-Lower](https://github.com/RobertBoettcherSF/Ada-SPARK-Guess-Number-Higher-Or-Lower) |
| **Hamming Code** | [Ada-SPARK-Hamming-Code](https://github.com/RobertBoettcherSF/Ada-SPARK-Hamming-Code) |
| **Hamming Distance** | [Ada-SPARK-Hamming-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Hamming-Distance) |
| **Hamming Weight** | [Ada-SPARK-Hamming-Weight](https://github.com/RobertBoettcherSF/Ada-SPARK-Hamming-Weight) |
| **Hand Of Straights Stub** | [Ada-SPARK-Hand-Of-Straights-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Hand-Of-Straights-Stub) |
| **Happy Number** | [Ada-SPARK-Happy-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Happy-Number) |
| **Heap Push Pop** | [Ada-SPARK-Heap-Push-Pop](https://github.com/RobertBoettcherSF/Ada-SPARK-Heap-Push-Pop) |
| **Heap Sort** | [Ada-SPARK-Heap-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Heap-Sort) |
| **Heaps Algorithm** | [Ada-SPARK-Heaps-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Heaps-Algorithm) |
| **Heapsort** | [Ada-SPARK-Heapsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Heapsort) |
| **Heaters** | [Ada-SPARK-Heaters](https://github.com/RobertBoettcherSF/Ada-SPARK-Heaters) |
| **Height Checker** | [Ada-SPARK-Height-Checker](https://github.com/RobertBoettcherSF/Ada-SPARK-Height-Checker) |
| **Histogram Bin** | [Ada-SPARK-Histogram-Bin](https://github.com/RobertBoettcherSF/Ada-SPARK-Histogram-Bin) |
| **Hit Counter Stub** | [Ada-SPARK-Hit-Counter-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Hit-Counter-Stub) |
| **Horner Scheme** | [Ada-SPARK-Horner-Scheme](https://github.com/RobertBoettcherSF/Ada-SPARK-Horner-Scheme) |
| **House Robber** | [Ada-SPARK-House-Robber](https://github.com/RobertBoettcherSF/Ada-SPARK-House-Robber) |
| **House Robber II** | [Ada-SPARK-House-Robber-II](https://github.com/RobertBoettcherSF/Ada-SPARK-House-Robber-II) |
| **House Robber III Lite** | [Ada-SPARK-House-Robber-III-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-House-Robber-III-Lite) |
| **House Robber III Stub** | [Ada-SPARK-House-Robber-III-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-House-Robber-III-Stub) |
| **How Many Numbers Are Smaller** | [Ada-SPARK-How-Many-Numbers-Are-Smaller](https://github.com/RobertBoettcherSF/Ada-SPARK-How-Many-Numbers-Are-Smaller) |
| **Huffman Coding** | [Ada-SPARK-Huffman-Coding](https://github.com/RobertBoettcherSF/Ada-SPARK-Huffman-Coding) |
| **IPO Lite** | [Ada-SPARK-IPO-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-IPO-Lite) |
| **Image Smoother** | [Ada-SPARK-Image-Smoother](https://github.com/RobertBoettcherSF/Ada-SPARK-Image-Smoother) |
| **Implement Queue Using Stacks** | [Ada-SPARK-Implement-Queue-Using-Stacks](https://github.com/RobertBoettcherSF/Ada-SPARK-Implement-Queue-Using-Stacks) |
| **Implement Stack Using Queues** | [Ada-SPARK-Implement-Stack-Using-Queues](https://github.com/RobertBoettcherSF/Ada-SPARK-Implement-Stack-Using-Queues) |
| **Implement StrStr** | [Ada-SPARK-Implement-StrStr](https://github.com/RobertBoettcherSF/Ada-SPARK-Implement-StrStr) |
| **Implement Trie** | [Ada-SPARK-Implement-Trie](https://github.com/RobertBoettcherSF/Ada-SPARK-Implement-Trie) |
| **Increasing Order Search Tree** | [Ada-SPARK-Increasing-Order-Search-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Increasing-Order-Search-Tree) |
| **Insert Delete GetRandom O1** | [Ada-SPARK-Insert-Delete-GetRandom-O1](https://github.com/RobertBoettcherSF/Ada-SPARK-Insert-Delete-GetRandom-O1) |
| **Insert Interval** | [Ada-SPARK-Insert-Interval](https://github.com/RobertBoettcherSF/Ada-SPARK-Insert-Interval) |
| **Insert Into A Binary Search Tree** | [Ada-SPARK-Insert-Into-A-Binary-Search-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Insert-Into-A-Binary-Search-Tree) |
| **Insert Into BST** | [Ada-SPARK-Insert-Into-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Insert-Into-BST) |
| **Insertion Sort** | [Ada-SPARK-Insertion-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Insertion-Sort) |
| **Int To Roman Stub** | [Ada-SPARK-Int-To-Roman-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Int-To-Roman-Stub) |
| **Integer Break** | [Ada-SPARK-Integer-Break](https://github.com/RobertBoettcherSF/Ada-SPARK-Integer-Break) |
| **Integer To English Stub** | [Ada-SPARK-Integer-To-English-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Integer-To-English-Stub) |
| **Integer To Roman** | [Ada-SPARK-Integer-To-Roman](https://github.com/RobertBoettcherSF/Ada-SPARK-Integer-To-Roman) |
| **Interleaving String** | [Ada-SPARK-Interleaving-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Interleaving-String) |
| **Interpolation Search** | [Ada-SPARK-Interpolation-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Interpolation-Search) |
| **Intersection Of Two Arrays** | [Ada-SPARK-Intersection-Of-Two-Arrays](https://github.com/RobertBoettcherSF/Ada-SPARK-Intersection-Of-Two-Arrays) |
| **Intersection Of Two Arrays II** | [Ada-SPARK-Intersection-Of-Two-Arrays-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Intersection-Of-Two-Arrays-II) |
| **Intersection Of Two Linked Lists** | [Ada-SPARK-Intersection-Of-Two-Linked-Lists](https://github.com/RobertBoettcherSF/Ada-SPARK-Intersection-Of-Two-Linked-Lists) |
| **Intro Sort** | [Ada-SPARK-Intro-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Intro-Sort) |
| **Introselect** | [Ada-SPARK-Introselect](https://github.com/RobertBoettcherSF/Ada-SPARK-Introselect) |
| **Introsort** | [Ada-SPARK-Introsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Introsort) |
| **Invert Binary Tree** | [Ada-SPARK-Invert-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Invert-Binary-Tree) |
| **Is Graph Bipartite** | [Ada-SPARK-Is-Graph-Bipartite](https://github.com/RobertBoettcherSF/Ada-SPARK-Is-Graph-Bipartite) |
| **Is Palindrome** | [Ada-SPARK-Is-Palindrome](https://github.com/RobertBoettcherSF/Ada-SPARK-Is-Palindrome) |
| **Is Subsequence** | [Ada-SPARK-Is-Subsequence](https://github.com/RobertBoettcherSF/Ada-SPARK-Is-Subsequence) |
| **Island Perimeter** | [Ada-SPARK-Island-Perimeter](https://github.com/RobertBoettcherSF/Ada-SPARK-Island-Perimeter) |
| **Isomorphic Strings** | [Ada-SPARK-Isomorphic-Strings](https://github.com/RobertBoettcherSF/Ada-SPARK-Isomorphic-Strings) |
| **Jaccard Index** | [Ada-SPARK-Jaccard-Index](https://github.com/RobertBoettcherSF/Ada-SPARK-Jaccard-Index) |
| **Jump Game** | [Ada-SPARK-Jump-Game](https://github.com/RobertBoettcherSF/Ada-SPARK-Jump-Game) |
| **Jump Game II** | [Ada-SPARK-Jump-Game-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Jump-Game-II) |
| **Jump Search** | [Ada-SPARK-Jump-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Jump-Search) |
| **K Closest Points Stub** | [Ada-SPARK-K-Closest-Points-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-K-Closest-Points-Stub) |
| **K Closest Points To Origin** | [Ada-SPARK-K-Closest-Points-To-Origin](https://github.com/RobertBoettcherSF/Ada-SPARK-K-Closest-Points-To-Origin) |
| **K Means Step** | [Ada-SPARK-K-Means-Step](https://github.com/RobertBoettcherSF/Ada-SPARK-K-Means-Step) |
| **K Way Merge** | [Ada-SPARK-K-Way-Merge](https://github.com/RobertBoettcherSF/Ada-SPARK-K-Way-Merge) |
| **Kadanes Algorithm** | [Ada-SPARK-Kadanes-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Kadanes-Algorithm) |
| **Keyboard Row** | [Ada-SPARK-Keyboard-Row](https://github.com/RobertBoettcherSF/Ada-SPARK-Keyboard-Row) |
| **Keys And Rooms** | [Ada-SPARK-Keys-And-Rooms](https://github.com/RobertBoettcherSF/Ada-SPARK-Keys-And-Rooms) |
| **Knapsack 01** | [Ada-SPARK-Knapsack-01](https://github.com/RobertBoettcherSF/Ada-SPARK-Knapsack-01) |
| **Knight Probability In Chessboard Lite** | [Ada-SPARK-Knight-Probability-In-Chessboard-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Knight-Probability-In-Chessboard-Lite) |
| **Knuth Morris Pratt** | [Ada-SPARK-Knuth-Morris-Pratt](https://github.com/RobertBoettcherSF/Ada-SPARK-Knuth-Morris-Pratt) |
| **Koko Eating Bananas** | [Ada-SPARK-Koko-Eating-Bananas](https://github.com/RobertBoettcherSF/Ada-SPARK-Koko-Eating-Bananas) |
| **Kruskal MST Lite** | [Ada-SPARK-Kruskal-MST-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Kruskal-MST-Lite) |
| **Kruskals Algorithm** | [Ada-SPARK-Kruskals-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Kruskals-Algorithm) |
| **Kth Largest Array** | [Ada-SPARK-Kth-Largest-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Largest-Array) |
| **Kth Largest Element** | [Ada-SPARK-Kth-Largest-Element](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Largest-Element) |
| **Kth Largest Element In A Stream** | [Ada-SPARK-Kth-Largest-Element-In-A-Stream](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Largest-Element-In-A-Stream) |
| **Kth Largest Element In An Array** | [Ada-SPARK-Kth-Largest-Element-In-An-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Largest-Element-In-An-Array) |
| **Kth Largest In Stream Stub** | [Ada-SPARK-Kth-Largest-In-Stream-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Largest-In-Stream-Stub) |
| **Kth Smallest BST Stub** | [Ada-SPARK-Kth-Smallest-BST-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Smallest-BST-Stub) |
| **Kth Smallest Element In A Sorted Matrix** | [Ada-SPARK-Kth-Smallest-Element-In-A-Sorted-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Kth-Smallest-Element-In-A-Sorted-Matrix) |
| **L1 Norm** | [Ada-SPARK-L1-Norm](https://github.com/RobertBoettcherSF/Ada-SPARK-L1-Norm) |
| **L2 Norm Squared** | [Ada-SPARK-L2-Norm-Squared](https://github.com/RobertBoettcherSF/Ada-SPARK-L2-Norm-Squared) |
| **LFU Cache Lite** | [Ada-SPARK-LFU-Cache-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-LFU-Cache-Lite) |
| **LFU Cache Stub** | [Ada-SPARK-LFU-Cache-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-LFU-Cache-Stub) |
| **LRU Cache Lite** | [Ada-SPARK-LRU-Cache-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-LRU-Cache-Lite) |
| **LRU Cache Stub** | [Ada-SPARK-LRU-Cache-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-LRU-Cache-Stub) |
| **LZ77** | [Ada-SPARK-LZ77](https://github.com/RobertBoettcherSF/Ada-SPARK-LZ77) |
| **Lagged Fibonacci Generator** | [Ada-SPARK-Lagged-Fibonacci-Generator](https://github.com/RobertBoettcherSF/Ada-SPARK-Lagged-Fibonacci-Generator) |
| **Lagrange Interpolation** | [Ada-SPARK-Lagrange-Interpolation](https://github.com/RobertBoettcherSF/Ada-SPARK-Lagrange-Interpolation) |
| **Lamports Bakery Algorithm** | [Ada-SPARK-Lamports-Bakery-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Lamports-Bakery-Algorithm) |
| **Largest Number** | [Ada-SPARK-Largest-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Largest-Number) |
| **Largest Rectangle In Histogram** | [Ada-SPARK-Largest-Rectangle-In-Histogram](https://github.com/RobertBoettcherSF/Ada-SPARK-Largest-Rectangle-In-Histogram) |
| **Last Stone Weight** | [Ada-SPARK-Last-Stone-Weight](https://github.com/RobertBoettcherSF/Ada-SPARK-Last-Stone-Weight) |
| **Last Stone Weight II** | [Ada-SPARK-Last-Stone-Weight-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Last-Stone-Weight-II) |
| **Leaf Similar Trees** | [Ada-SPARK-Leaf-Similar-Trees](https://github.com/RobertBoettcherSF/Ada-SPARK-Leaf-Similar-Trees) |
| **Least Common Multiple** | [Ada-SPARK-Least-Common-Multiple](https://github.com/RobertBoettcherSF/Ada-SPARK-Least-Common-Multiple) |
| **Lemke Howson** | [Ada-SPARK-Lemke-Howson](https://github.com/RobertBoettcherSF/Ada-SPARK-Lemke-Howson) |
| **Lemonade Change** | [Ada-SPARK-Lemonade-Change](https://github.com/RobertBoettcherSF/Ada-SPARK-Lemonade-Change) |
| **Length Of Last Word** | [Ada-SPARK-Length-Of-Last-Word](https://github.com/RobertBoettcherSF/Ada-SPARK-Length-Of-Last-Word) |
| **Letter Case Permutation** | [Ada-SPARK-Letter-Case-Permutation](https://github.com/RobertBoettcherSF/Ada-SPARK-Letter-Case-Permutation) |
| **Letter Combinations Of A Phone Number** | [Ada-SPARK-Letter-Combinations-Of-A-Phone-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Letter-Combinations-Of-A-Phone-Number) |
| **Level Order Traversal Stub** | [Ada-SPARK-Level-Order-Traversal-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Level-Order-Traversal-Stub) |
| **Levenshtein Distance** | [Ada-SPARK-Levenshtein-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Levenshtein-Distance) |
| **Library Sort** | [Ada-SPARK-Library-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Library-Sort) |
| **License Key Formatting** | [Ada-SPARK-License-Key-Formatting](https://github.com/RobertBoettcherSF/Ada-SPARK-License-Key-Formatting) |
| **Line Intersection** | [Ada-SPARK-Line-Intersection](https://github.com/RobertBoettcherSF/Ada-SPARK-Line-Intersection) |
| **Line Reflection** | [Ada-SPARK-Line-Reflection](https://github.com/RobertBoettcherSF/Ada-SPARK-Line-Reflection) |
| **Linear Congruential Generator** | [Ada-SPARK-Linear-Congruential-Generator](https://github.com/RobertBoettcherSF/Ada-SPARK-Linear-Congruential-Generator) |
| **Linear Regression** | [Ada-SPARK-Linear-Regression](https://github.com/RobertBoettcherSF/Ada-SPARK-Linear-Regression) |
| **Linear Search** | [Ada-SPARK-Linear-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Linear-Search) |
| **Linked List Cycle** | [Ada-SPARK-Linked-List-Cycle](https://github.com/RobertBoettcherSF/Ada-SPARK-Linked-List-Cycle) |
| **Linked List Cycle II** | [Ada-SPARK-Linked-List-Cycle-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Linked-List-Cycle-II) |
| **Logger Rate Limiter Lite** | [Ada-SPARK-Logger-Rate-Limiter-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Logger-Rate-Limiter-Lite) |
| **Logger Rate Limiter Stub** | [Ada-SPARK-Logger-Rate-Limiter-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Logger-Rate-Limiter-Stub) |
| **Longest Common Prefix** | [Ada-SPARK-Longest-Common-Prefix](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Common-Prefix) |
| **Longest Common Subsequence** | [Ada-SPARK-Longest-Common-Subsequence](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Common-Subsequence) |
| **Longest Common Substring** | [Ada-SPARK-Longest-Common-Substring](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Common-Substring) |
| **Longest Increasing Subsequence** | [Ada-SPARK-Longest-Increasing-Subsequence](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Increasing-Subsequence) |
| **Longest Mountain In Array** | [Ada-SPARK-Longest-Mountain-In-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Mountain-In-Array) |
| **Longest Ones** | [Ada-SPARK-Longest-Ones](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Ones) |
| **Longest Palindromic Subsequence** | [Ada-SPARK-Longest-Palindromic-Subsequence](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Palindromic-Subsequence) |
| **Longest Palindromic Substring** | [Ada-SPARK-Longest-Palindromic-Substring](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Palindromic-Substring) |
| **Longest Repeating Character Replacement** | [Ada-SPARK-Longest-Repeating-Character-Replacement](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Repeating-Character-Replacement) |
| **Longest Substring Without Repeat** | [Ada-SPARK-Longest-Substring-Without-Repeat](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Substring-Without-Repeat) |
| **Longest Substring Without Repeating** | [Ada-SPARK-Longest-Substring-Without-Repeating](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Substring-Without-Repeating) |
| **Longest Word In Dictionary** | [Ada-SPARK-Longest-Word-In-Dictionary](https://github.com/RobertBoettcherSF/Ada-SPARK-Longest-Word-In-Dictionary) |
| **Lowest Common Ancestor BST** | [Ada-SPARK-Lowest-Common-Ancestor-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Lowest-Common-Ancestor-BST) |
| **Lowest Common Ancestor Of BST** | [Ada-SPARK-Lowest-Common-Ancestor-Of-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Lowest-Common-Ancestor-Of-BST) |
| **Lucky Numbers In A Matrix** | [Ada-SPARK-Lucky-Numbers-In-A-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Lucky-Numbers-In-A-Matrix) |
| **MD5** | [Ada-SPARK-MD5](https://github.com/RobertBoettcherSF/Ada-SPARK-MD5) |
| **Magnetic Force Between Two Balls** | [Ada-SPARK-Magnetic-Force-Between-Two-Balls](https://github.com/RobertBoettcherSF/Ada-SPARK-Magnetic-Force-Between-Two-Balls) |
| **Majority Element** | [Ada-SPARK-Majority-Element](https://github.com/RobertBoettcherSF/Ada-SPARK-Majority-Element) |
| **Majority Element II** | [Ada-SPARK-Majority-Element-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Majority-Element-II) |
| **Make The String Great** | [Ada-SPARK-Make-The-String-Great](https://github.com/RobertBoettcherSF/Ada-SPARK-Make-The-String-Great) |
| **Manacher** | [Ada-SPARK-Manacher](https://github.com/RobertBoettcherSF/Ada-SPARK-Manacher) |
| **Manhattan Distance** | [Ada-SPARK-Manhattan-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Manhattan-Distance) |
| **Map Sum Pairs** | [Ada-SPARK-Map-Sum-Pairs](https://github.com/RobertBoettcherSF/Ada-SPARK-Map-Sum-Pairs) |
| **Mark And Sweep** | [Ada-SPARK-Mark-And-Sweep](https://github.com/RobertBoettcherSF/Ada-SPARK-Mark-And-Sweep) |
| **Matchsticks To Square Lite** | [Ada-SPARK-Matchsticks-To-Square-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Matchsticks-To-Square-Lite) |
| **Matrix Cells In Distance Order** | [Ada-SPARK-Matrix-Cells-In-Distance-Order](https://github.com/RobertBoettcherSF/Ada-SPARK-Matrix-Cells-In-Distance-Order) |
| **Matrix Chain Multiplication** | [Ada-SPARK-Matrix-Chain-Multiplication](https://github.com/RobertBoettcherSF/Ada-SPARK-Matrix-Chain-Multiplication) |
| **Matrix Diagonal Sum** | [Ada-SPARK-Matrix-Diagonal-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Matrix-Diagonal-Sum) |
| **Matrix Multiply** | [Ada-SPARK-Matrix-Multiply](https://github.com/RobertBoettcherSF/Ada-SPARK-Matrix-Multiply) |
| **Max Area Of Island** | [Ada-SPARK-Max-Area-Of-Island](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Area-Of-Island) |
| **Max Consecutive Ones** | [Ada-SPARK-Max-Consecutive-Ones](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Consecutive-Ones) |
| **Max Consecutive Ones II** | [Ada-SPARK-Max-Consecutive-Ones-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Consecutive-Ones-II) |
| **Max Consecutive Ones III** | [Ada-SPARK-Max-Consecutive-Ones-III](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Consecutive-Ones-III) |
| **Max Heap** | [Ada-SPARK-Max-Heap](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Heap) |
| **Max Path Sum Stub** | [Ada-SPARK-Max-Path-Sum-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Path-Sum-Stub) |
| **Max Points On A Line Lite** | [Ada-SPARK-Max-Points-On-A-Line-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Points-On-A-Line-Lite) |
| **Max Product Subarray** | [Ada-SPARK-Max-Product-Subarray](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Product-Subarray) |
| **Max Stack** | [Ada-SPARK-Max-Stack](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Stack) |
| **Max Stack Stub** | [Ada-SPARK-Max-Stack-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Max-Stack-Stub) |
| **Maximal Rectangle** | [Ada-SPARK-Maximal-Rectangle](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximal-Rectangle) |
| **Maximal Square** | [Ada-SPARK-Maximal-Square](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximal-Square) |
| **Maximum Binary Tree** | [Ada-SPARK-Maximum-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Binary-Tree) |
| **Maximum Candies Allocated To K Children** | [Ada-SPARK-Maximum-Candies-Allocated-To-K-Children](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Candies-Allocated-To-K-Children) |
| **Maximum Depth Of Binary Tree** | [Ada-SPARK-Maximum-Depth-Of-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Depth-Of-Binary-Tree) |
| **Maximum Depth Of N Ary Tree** | [Ada-SPARK-Maximum-Depth-Of-N-Ary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Depth-Of-N-Ary-Tree) |
| **Maximum Ice Cream Bars** | [Ada-SPARK-Maximum-Ice-Cream-Bars](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Ice-Cream-Bars) |
| **Maximum Performance Of A Team Lite** | [Ada-SPARK-Maximum-Performance-Of-A-Team-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Performance-Of-A-Team-Lite) |
| **Maximum Points You Can Obtain From Cards** | [Ada-SPARK-Maximum-Points-You-Can-Obtain-From-Cards](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Points-You-Can-Obtain-From-Cards) |
| **Maximum Product Of Word Lengths** | [Ada-SPARK-Maximum-Product-Of-Word-Lengths](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Product-Of-Word-Lengths) |
| **Maximum Product Subarray** | [Ada-SPARK-Maximum-Product-Subarray](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Product-Subarray) |
| **Maximum Subarray** | [Ada-SPARK-Maximum-Subarray](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Subarray) |
| **Maximum Subarray Circular** | [Ada-SPARK-Maximum-Subarray-Circular](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Subarray-Circular) |
| **Maximum Twin Sum Of A Linked List** | [Ada-SPARK-Maximum-Twin-Sum-Of-A-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Twin-Sum-Of-A-Linked-List) |
| **Maximum Units On A Truck** | [Ada-SPARK-Maximum-Units-On-A-Truck](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-Units-On-A-Truck) |
| **Maximum XOR Of Two Numbers** | [Ada-SPARK-Maximum-XOR-Of-Two-Numbers](https://github.com/RobertBoettcherSF/Ada-SPARK-Maximum-XOR-Of-Two-Numbers) |
| **Mean Variance** | [Ada-SPARK-Mean-Variance](https://github.com/RobertBoettcherSF/Ada-SPARK-Mean-Variance) |
| **Median Filtering** | [Ada-SPARK-Median-Filtering](https://github.com/RobertBoettcherSF/Ada-SPARK-Median-Filtering) |
| **Median Of Three** | [Ada-SPARK-Median-Of-Three](https://github.com/RobertBoettcherSF/Ada-SPARK-Median-Of-Three) |
| **Median Of Two Sorted Arrays Lite** | [Ada-SPARK-Median-Of-Two-Sorted-Arrays-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Median-Of-Two-Sorted-Arrays-Lite) |
| **Meeting Rooms** | [Ada-SPARK-Meeting-Rooms](https://github.com/RobertBoettcherSF/Ada-SPARK-Meeting-Rooms) |
| **Meeting Rooms II** | [Ada-SPARK-Meeting-Rooms-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Meeting-Rooms-II) |
| **Merge In Between Linked Lists** | [Ada-SPARK-Merge-In-Between-Linked-Lists](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-In-Between-Linked-Lists) |
| **Merge Intervals** | [Ada-SPARK-Merge-Intervals](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Intervals) |
| **Merge K Sorted Lists Stub** | [Ada-SPARK-Merge-K-Sorted-Lists-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-K-Sorted-Lists-Stub) |
| **Merge Sort** | [Ada-SPARK-Merge-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Sort) |
| **Merge Sorted Array** | [Ada-SPARK-Merge-Sorted-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Sorted-Array) |
| **Merge Sorted Arrays** | [Ada-SPARK-Merge-Sorted-Arrays](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Sorted-Arrays) |
| **Merge Two Binary Trees** | [Ada-SPARK-Merge-Two-Binary-Trees](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Two-Binary-Trees) |
| **Merge Two Sorted Lists** | [Ada-SPARK-Merge-Two-Sorted-Lists](https://github.com/RobertBoettcherSF/Ada-SPARK-Merge-Two-Sorted-Lists) |
| **Mersenne Twister** | [Ada-SPARK-Mersenne-Twister](https://github.com/RobertBoettcherSF/Ada-SPARK-Mersenne-Twister) |
| **Middle Of The Linked List** | [Ada-SPARK-Middle-Of-The-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Middle-Of-The-Linked-List) |
| **Min Cost Climbing Stairs** | [Ada-SPARK-Min-Cost-Climbing-Stairs](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Cost-Climbing-Stairs) |
| **Min Cost Connect Cities Stub** | [Ada-SPARK-Min-Cost-Connect-Cities-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Cost-Connect-Cities-Stub) |
| **Min Cost To Connect All Points** | [Ada-SPARK-Min-Cost-To-Connect-All-Points](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Cost-To-Connect-All-Points) |
| **Min Heap** | [Ada-SPARK-Min-Heap](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Heap) |
| **Min Max Normalize** | [Ada-SPARK-Min-Max-Normalize](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Max-Normalize) |
| **Min Stack** | [Ada-SPARK-Min-Stack](https://github.com/RobertBoettcherSF/Ada-SPARK-Min-Stack) |
| **Minimum ASCII Delete Sum** | [Ada-SPARK-Minimum-ASCII-Delete-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-ASCII-Delete-Sum) |
| **Minimum Bit Flips To Convert Number** | [Ada-SPARK-Minimum-Bit-Flips-To-Convert-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Bit-Flips-To-Convert-Number) |
| **Minimum Cost To Move Chips** | [Ada-SPARK-Minimum-Cost-To-Move-Chips](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Cost-To-Move-Chips) |
| **Minimum Deletions To Make Character Frequencies Unique** | [Ada-SPARK-Minimum-Deletions-To-Make-Character-Frequencies-Unique](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Deletions-To-Make-Character-Frequencies-Unique) |
| **Minimum Depth Of Binary Tree** | [Ada-SPARK-Minimum-Depth-Of-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Depth-Of-Binary-Tree) |
| **Minimum Height Trees** | [Ada-SPARK-Minimum-Height-Trees](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Height-Trees) |
| **Minimum Limit Of Balls In A Bag** | [Ada-SPARK-Minimum-Limit-Of-Balls-In-A-Bag](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Limit-Of-Balls-In-A-Bag) |
| **Minimum Number Of Arrows** | [Ada-SPARK-Minimum-Number-Of-Arrows](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Number-Of-Arrows) |
| **Minimum Number Of Days To Make M Bouquets** | [Ada-SPARK-Minimum-Number-Of-Days-To-Make-M-Bouquets](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Number-Of-Days-To-Make-M-Bouquets) |
| **Minimum Number Of Moves To Seat** | [Ada-SPARK-Minimum-Number-Of-Moves-To-Seat](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Number-Of-Moves-To-Seat) |
| **Minimum Operations To Make The Array Increasing** | [Ada-SPARK-Minimum-Operations-To-Make-The-Array-Increasing](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Operations-To-Make-The-Array-Increasing) |
| **Minimum Path Sum** | [Ada-SPARK-Minimum-Path-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Path-Sum) |
| **Minimum Sum Of Four Digit Number** | [Ada-SPARK-Minimum-Sum-Of-Four-Digit-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Sum-Of-Four-Digit-Number) |
| **Minimum Window Substring** | [Ada-SPARK-Minimum-Window-Substring](https://github.com/RobertBoettcherSF/Ada-SPARK-Minimum-Window-Substring) |
| **Missing Number** | [Ada-SPARK-Missing-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Missing-Number) |
| **Missing Ranges Stub** | [Ada-SPARK-Missing-Ranges-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Missing-Ranges-Stub) |
| **Modular Exponentiation** | [Ada-SPARK-Modular-Exponentiation](https://github.com/RobertBoettcherSF/Ada-SPARK-Modular-Exponentiation) |
| **Monotonic Stack** | [Ada-SPARK-Monotonic-Stack](https://github.com/RobertBoettcherSF/Ada-SPARK-Monotonic-Stack) |
| **Most Common Word** | [Ada-SPARK-Most-Common-Word](https://github.com/RobertBoettcherSF/Ada-SPARK-Most-Common-Word) |
| **Move To Front** | [Ada-SPARK-Move-To-Front](https://github.com/RobertBoettcherSF/Ada-SPARK-Move-To-Front) |
| **Move Zeroes** | [Ada-SPARK-Move-Zeroes](https://github.com/RobertBoettcherSF/Ada-SPARK-Move-Zeroes) |
| **Moving Average** | [Ada-SPARK-Moving-Average](https://github.com/RobertBoettcherSF/Ada-SPARK-Moving-Average) |
| **Moving Average From Data Stream** | [Ada-SPARK-Moving-Average-From-Data-Stream](https://github.com/RobertBoettcherSF/Ada-SPARK-Moving-Average-From-Data-Stream) |
| **Multiply Strings Lite** | [Ada-SPARK-Multiply-Strings-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Multiply-Strings-Lite) |
| **Multiply Strings Stub** | [Ada-SPARK-Multiply-Strings-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Multiply-Strings-Stub) |
| **My Calendar Stub** | [Ada-SPARK-My-Calendar-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-My-Calendar-Stub) |
| **My Linked List Stub** | [Ada-SPARK-My-Linked-List-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-My-Linked-List-Stub) |
| **N Ary Tree Level Order Traversal** | [Ada-SPARK-N-Ary-Tree-Level-Order-Traversal](https://github.com/RobertBoettcherSF/Ada-SPARK-N-Ary-Tree-Level-Order-Traversal) |
| **N Ary Tree Postorder Traversal** | [Ada-SPARK-N-Ary-Tree-Postorder-Traversal](https://github.com/RobertBoettcherSF/Ada-SPARK-N-Ary-Tree-Postorder-Traversal) |
| **N Ary Tree Preorder Traversal** | [Ada-SPARK-N-Ary-Tree-Preorder-Traversal](https://github.com/RobertBoettcherSF/Ada-SPARK-N-Ary-Tree-Preorder-Traversal) |
| **N Queens Lite** | [Ada-SPARK-N-Queens-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-N-Queens-Lite) |
| **N Repeated Element In Size 2N Array** | [Ada-SPARK-N-Repeated-Element-In-Size-2N-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-N-Repeated-Element-In-Size-2N-Array) |
| **N th Tribonacci** | [Ada-SPARK-N-th-Tribonacci](https://github.com/RobertBoettcherSF/Ada-SPARK-N-th-Tribonacci) |
| **Naive String Search** | [Ada-SPARK-Naive-String-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Naive-String-Search) |
| **Nearest Exit From Entrance In Maze** | [Ada-SPARK-Nearest-Exit-From-Entrance-In-Maze](https://github.com/RobertBoettcherSF/Ada-SPARK-Nearest-Exit-From-Entrance-In-Maze) |
| **Neighboring Bitwise XOR** | [Ada-SPARK-Neighboring-Bitwise-XOR](https://github.com/RobertBoettcherSF/Ada-SPARK-Neighboring-Bitwise-XOR) |
| **Nested Iterator Stub** | [Ada-SPARK-Nested-Iterator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Nested-Iterator-Stub) |
| **Network Delay Time** | [Ada-SPARK-Network-Delay-Time](https://github.com/RobertBoettcherSF/Ada-SPARK-Network-Delay-Time) |
| **Network Delay Time Stub** | [Ada-SPARK-Network-Delay-Time-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Network-Delay-Time-Stub) |
| **New 21 Game Lite** | [Ada-SPARK-New-21-Game-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-New-21-Game-Lite) |
| **Newton Raphson** | [Ada-SPARK-Newton-Raphson](https://github.com/RobertBoettcherSF/Ada-SPARK-Newton-Raphson) |
| **Next Greater Element I** | [Ada-SPARK-Next-Greater-Element-I](https://github.com/RobertBoettcherSF/Ada-SPARK-Next-Greater-Element-I) |
| **Next Greater Element II** | [Ada-SPARK-Next-Greater-Element-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Next-Greater-Element-II) |
| **Next Greater Node In Linked List** | [Ada-SPARK-Next-Greater-Node-In-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Next-Greater-Node-In-Linked-List) |
| **Next Permutation Stub** | [Ada-SPARK-Next-Permutation-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Next-Permutation-Stub) |
| **Nim Game** | [Ada-SPARK-Nim-Game](https://github.com/RobertBoettcherSF/Ada-SPARK-Nim-Game) |
| **Non Decreasing Array** | [Ada-SPARK-Non-Decreasing-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Non-Decreasing-Array) |
| **Non Overlapping Intervals** | [Ada-SPARK-Non-Overlapping-Intervals](https://github.com/RobertBoettcherSF/Ada-SPARK-Non-Overlapping-Intervals) |
| **Nth Digit** | [Ada-SPARK-Nth-Digit](https://github.com/RobertBoettcherSF/Ada-SPARK-Nth-Digit) |
| **Nth Digit Stub** | [Ada-SPARK-Nth-Digit-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Nth-Digit-Stub) |
| **Nth Ugly Number** | [Ada-SPARK-Nth-Ugly-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Nth-Ugly-Number) |
| **Num Matrix Block Sum** | [Ada-SPARK-Num-Matrix-Block-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Num-Matrix-Block-Sum) |
| **Number Complement** | [Ada-SPARK-Number-Complement](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Complement) |
| **Number Of 1 Bits** | [Ada-SPARK-Number-Of-1-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-1-Bits) |
| **Number Of 1 Bits In Range** | [Ada-SPARK-Number-Of-1-Bits-In-Range](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-1-Bits-In-Range) |
| **Number Of Connected Components** | [Ada-SPARK-Number-Of-Connected-Components](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Connected-Components) |
| **Number Of Good Pairs** | [Ada-SPARK-Number-Of-Good-Pairs](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Good-Pairs) |
| **Number Of Islands** | [Ada-SPARK-Number-Of-Islands](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Islands) |
| **Number Of Islands DFS** | [Ada-SPARK-Number-Of-Islands-DFS](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Islands-DFS) |
| **Number Of Lines To Write String** | [Ada-SPARK-Number-Of-Lines-To-Write-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Lines-To-Write-String) |
| **Number Of Provinces** | [Ada-SPARK-Number-Of-Provinces](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Provinces) |
| **Number Of Recent Calls** | [Ada-SPARK-Number-Of-Recent-Calls](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Recent-Calls) |
| **Number Of Steps To Reduce A Number** | [Ada-SPARK-Number-Of-Steps-To-Reduce-A-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Steps-To-Reduce-A-Number) |
| **Number Of Steps To Reduce A Number In Binary Representation** | [Ada-SPARK-Number-Of-Steps-To-Reduce-A-Number-In-Binary-Representation](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Steps-To-Reduce-A-Number-In-Binary-Representation) |
| **Number Of Substrings Containing All Three Characters** | [Ada-SPARK-Number-Of-Substrings-Containing-All-Three-Characters](https://github.com/RobertBoettcherSF/Ada-SPARK-Number-Of-Substrings-Containing-All-Three-Characters) |
| **Odd Even Linked List** | [Ada-SPARK-Odd-Even-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Odd-Even-Linked-List) |
| **Odd Even Merge Sort** | [Ada-SPARK-Odd-Even-Merge-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Odd-Even-Merge-Sort) |
| **Odd Even Sort** | [Ada-SPARK-Odd-Even-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Odd-Even-Sort) |
| **One Edit Distance** | [Ada-SPARK-One-Edit-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-One-Edit-Distance) |
| **One Hot** | [Ada-SPARK-One-Hot](https://github.com/RobertBoettcherSF/Ada-SPARK-One-Hot) |
| **Ones And Zeroes** | [Ada-SPARK-Ones-And-Zeroes](https://github.com/RobertBoettcherSF/Ada-SPARK-Ones-And-Zeroes) |
| **Online Stock Span** | [Ada-SPARK-Online-Stock-Span](https://github.com/RobertBoettcherSF/Ada-SPARK-Online-Stock-Span) |
| **Online Stock Span Stub** | [Ada-SPARK-Online-Stock-Span-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Online-Stock-Span-Stub) |
| **Open The Lock** | [Ada-SPARK-Open-The-Lock](https://github.com/RobertBoettcherSF/Ada-SPARK-Open-The-Lock) |
| **Ordered Stream Stub** | [Ada-SPARK-Ordered-Stream-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Ordered-Stream-Stub) |
| **Out Of Boundary Paths Lite** | [Ada-SPARK-Out-Of-Boundary-Paths-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Out-Of-Boundary-Paths-Lite) |
| **Overlap Coefficient** | [Ada-SPARK-Overlap-Coefficient](https://github.com/RobertBoettcherSF/Ada-SPARK-Overlap-Coefficient) |
| **Pacific Atlantic Water Flow** | [Ada-SPARK-Pacific-Atlantic-Water-Flow](https://github.com/RobertBoettcherSF/Ada-SPARK-Pacific-Atlantic-Water-Flow) |
| **Pacific Atlantic Water Stub** | [Ada-SPARK-Pacific-Atlantic-Water-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Pacific-Atlantic-Water-Stub) |
| **Package Merge Algorithm** | [Ada-SPARK-Package-Merge-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Package-Merge-Algorithm) |
| **Paint Fence Lite** | [Ada-SPARK-Paint-Fence-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Paint-Fence-Lite) |
| **Paint House Lite** | [Ada-SPARK-Paint-House-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Paint-House-Lite) |
| **Paint House Stub** | [Ada-SPARK-Paint-House-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Paint-House-Stub) |
| **Palindrome Linked List** | [Ada-SPARK-Palindrome-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Palindrome-Linked-List) |
| **Palindrome Number** | [Ada-SPARK-Palindrome-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Palindrome-Number) |
| **Palindrome Pairs Lite** | [Ada-SPARK-Palindrome-Pairs-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Palindrome-Pairs-Lite) |
| **Palindrome Partitioning** | [Ada-SPARK-Palindrome-Partitioning](https://github.com/RobertBoettcherSF/Ada-SPARK-Palindrome-Partitioning) |
| **Palindrome Partitioning II** | [Ada-SPARK-Palindrome-Partitioning-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Palindrome-Partitioning-II) |
| **Pancake Sort** | [Ada-SPARK-Pancake-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Pancake-Sort) |
| **Pancake Sorting** | [Ada-SPARK-Pancake-Sorting](https://github.com/RobertBoettcherSF/Ada-SPARK-Pancake-Sorting) |
| **Parity Bits** | [Ada-SPARK-Parity-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Parity-Bits) |
| **Parking System Stub** | [Ada-SPARK-Parking-System-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Parking-System-Stub) |
| **Partition Around Pivot** | [Ada-SPARK-Partition-Around-Pivot](https://github.com/RobertBoettcherSF/Ada-SPARK-Partition-Around-Pivot) |
| **Partition Equal Subset Sum** | [Ada-SPARK-Partition-Equal-Subset-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Partition-Equal-Subset-Sum) |
| **Partition Labels** | [Ada-SPARK-Partition-Labels](https://github.com/RobertBoettcherSF/Ada-SPARK-Partition-Labels) |
| **Partition List** | [Ada-SPARK-Partition-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Partition-List) |
| **Pascal Triangle** | [Ada-SPARK-Pascal-Triangle](https://github.com/RobertBoettcherSF/Ada-SPARK-Pascal-Triangle) |
| **Pascal Triangle II** | [Ada-SPARK-Pascal-Triangle-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Pascal-Triangle-II) |
| **Path Sum** | [Ada-SPARK-Path-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Path-Sum) |
| **Path Sum III Lite** | [Ada-SPARK-Path-Sum-III-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Path-Sum-III-Lite) |
| **Path With Minimum Effort** | [Ada-SPARK-Path-With-Minimum-Effort](https://github.com/RobertBoettcherSF/Ada-SPARK-Path-With-Minimum-Effort) |
| **Patience Sort** | [Ada-SPARK-Patience-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Patience-Sort) |
| **Patience Sorting** | [Ada-SPARK-Patience-Sorting](https://github.com/RobertBoettcherSF/Ada-SPARK-Patience-Sorting) |
| **Peak Index In Mountain Array** | [Ada-SPARK-Peak-Index-In-Mountain-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Peak-Index-In-Mountain-Array) |
| **Pearson Correlation** | [Ada-SPARK-Pearson-Correlation](https://github.com/RobertBoettcherSF/Ada-SPARK-Pearson-Correlation) |
| **Pearson Hashing** | [Ada-SPARK-Pearson-Hashing](https://github.com/RobertBoettcherSF/Ada-SPARK-Pearson-Hashing) |
| **Peeking Iterator Stub** | [Ada-SPARK-Peeking-Iterator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Peeking-Iterator-Stub) |
| **Perfect Number** | [Ada-SPARK-Perfect-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Perfect-Number) |
| **Perfect Squares** | [Ada-SPARK-Perfect-Squares](https://github.com/RobertBoettcherSF/Ada-SPARK-Perfect-Squares) |
| **Permutation In String** | [Ada-SPARK-Permutation-In-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Permutation-In-String) |
| **Permutations** | [Ada-SPARK-Permutations](https://github.com/RobertBoettcherSF/Ada-SPARK-Permutations) |
| **Permutations II** | [Ada-SPARK-Permutations-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Permutations-II) |
| **Petersons Algorithm** | [Ada-SPARK-Petersons-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Petersons-Algorithm) |
| **Pigeonhole Sort** | [Ada-SPARK-Pigeonhole-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Pigeonhole-Sort) |
| **Plus One** | [Ada-SPARK-Plus-One](https://github.com/RobertBoettcherSF/Ada-SPARK-Plus-One) |
| **PN Counter** | [Ada-SPARK-PN-Counter](https://github.com/RobertBoettcherSF/Ada-SPARK-PN-Counter) |
| **Point In Polygon** | [Ada-SPARK-Point-In-Polygon](https://github.com/RobertBoettcherSF/Ada-SPARK-Point-In-Polygon) |
| **Population Count** | [Ada-SPARK-Population-Count](https://github.com/RobertBoettcherSF/Ada-SPARK-Population-Count) |
| **Postman Sort** | [Ada-SPARK-Postman-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Postman-Sort) |
| **Pow X N** | [Ada-SPARK-Pow-X-N](https://github.com/RobertBoettcherSF/Ada-SPARK-Pow-X-N) |
| **Pow X N Stub** | [Ada-SPARK-Pow-X-N-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Pow-X-N-Stub) |
| **Power Of Four** | [Ada-SPARK-Power-Of-Four](https://github.com/RobertBoettcherSF/Ada-SPARK-Power-Of-Four) |
| **Power Of Three** | [Ada-SPARK-Power-Of-Three](https://github.com/RobertBoettcherSF/Ada-SPARK-Power-Of-Three) |
| **Power Of Two** | [Ada-SPARK-Power-Of-Two](https://github.com/RobertBoettcherSF/Ada-SPARK-Power-Of-Two) |
| **Powx N** | [Ada-SPARK-Powx-N](https://github.com/RobertBoettcherSF/Ada-SPARK-Powx-N) |
| **Prefix Sums** | [Ada-SPARK-Prefix-Sums](https://github.com/RobertBoettcherSF/Ada-SPARK-Prefix-Sums) |
| **Prim MST Lite** | [Ada-SPARK-Prim-MST-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Prim-MST-Lite) |
| **Prime Check** | [Ada-SPARK-Prime-Check](https://github.com/RobertBoettcherSF/Ada-SPARK-Prime-Check) |
| **Prime Number Of Set Bits** | [Ada-SPARK-Prime-Number-Of-Set-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Prime-Number-Of-Set-Bits) |
| **Prime Number Of Set Bits In Binary Representation** | [Ada-SPARK-Prime-Number-Of-Set-Bits-In-Binary-Representation](https://github.com/RobertBoettcherSF/Ada-SPARK-Prime-Number-Of-Set-Bits-In-Binary-Representation) |
| **Prims Algorithm** | [Ada-SPARK-Prims-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Prims-Algorithm) |
| **Priority Queue Binary Heap** | [Ada-SPARK-Priority-Queue-Binary-Heap](https://github.com/RobertBoettcherSF/Ada-SPARK-Priority-Queue-Binary-Heap) |
| **Product Except Self** | [Ada-SPARK-Product-Except-Self](https://github.com/RobertBoettcherSF/Ada-SPARK-Product-Except-Self) |
| **Product Of Array Except Self** | [Ada-SPARK-Product-Of-Array-Except-Self](https://github.com/RobertBoettcherSF/Ada-SPARK-Product-Of-Array-Except-Self) |
| **Product Of Numbers Stub** | [Ada-SPARK-Product-Of-Numbers-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Product-Of-Numbers-Stub) |
| **Projection Area Of 3D Shapes** | [Ada-SPARK-Projection-Area-Of-3D-Shapes](https://github.com/RobertBoettcherSF/Ada-SPARK-Projection-Area-Of-3D-Shapes) |
| **Quantum Sort** | [Ada-SPARK-Quantum-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Quantum-Sort) |
| **Queue Reconstruction By Height** | [Ada-SPARK-Queue-Reconstruction-By-Height](https://github.com/RobertBoettcherSF/Ada-SPARK-Queue-Reconstruction-By-Height) |
| **Queue Using Stacks** | [Ada-SPARK-Queue-Using-Stacks](https://github.com/RobertBoettcherSF/Ada-SPARK-Queue-Using-Stacks) |
| **Quick Sort** | [Ada-SPARK-Quick-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Quick-Sort) |
| **Quickselect** | [Ada-SPARK-Quickselect](https://github.com/RobertBoettcherSF/Ada-SPARK-Quickselect) |
| **Quicksort** | [Ada-SPARK-Quicksort](https://github.com/RobertBoettcherSF/Ada-SPARK-Quicksort) |
| **Rabin Karp** | [Ada-SPARK-Rabin-Karp](https://github.com/RobertBoettcherSF/Ada-SPARK-Rabin-Karp) |
| **Radix Sort** | [Ada-SPARK-Radix-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Radix-Sort) |
| **Random Pick With Weight Lite** | [Ada-SPARK-Random-Pick-With-Weight-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Random-Pick-With-Weight-Lite) |
| **Randomized Collection** | [Ada-SPARK-Randomized-Collection](https://github.com/RobertBoettcherSF/Ada-SPARK-Randomized-Collection) |
| **Randomized Set** | [Ada-SPARK-Randomized-Set](https://github.com/RobertBoettcherSF/Ada-SPARK-Randomized-Set) |
| **Range Addition** | [Ada-SPARK-Range-Addition](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Addition) |
| **Range Module Stub** | [Ada-SPARK-Range-Module-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Module-Stub) |
| **Range Sum BST** | [Ada-SPARK-Range-Sum-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Sum-BST) |
| **Range Sum Of BST** | [Ada-SPARK-Range-Sum-Of-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Sum-Of-BST) |
| **Range Sum Query** | [Ada-SPARK-Range-Sum-Query](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Sum-Query) |
| **Range Sum Query 2D Immutable** | [Ada-SPARK-Range-Sum-Query-2D-Immutable](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Sum-Query-2D-Immutable) |
| **Range Sum Query Immutable** | [Ada-SPARK-Range-Sum-Query-Immutable](https://github.com/RobertBoettcherSF/Ada-SPARK-Range-Sum-Query-Immutable) |
| **Ransom Note** | [Ada-SPARK-Ransom-Note](https://github.com/RobertBoettcherSF/Ada-SPARK-Ransom-Note) |
| **Rate Monotonic Scheduling** | [Ada-SPARK-Rate-Monotonic-Scheduling](https://github.com/RobertBoettcherSF/Ada-SPARK-Rate-Monotonic-Scheduling) |
| **ReLU** | [Ada-SPARK-ReLU](https://github.com/RobertBoettcherSF/Ada-SPARK-ReLU) |
| **Reach A Number** | [Ada-SPARK-Reach-A-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Reach-A-Number) |
| **Recent Counter** | [Ada-SPARK-Recent-Counter](https://github.com/RobertBoettcherSF/Ada-SPARK-Recent-Counter) |
| **Rectangle Area** | [Ada-SPARK-Rectangle-Area](https://github.com/RobertBoettcherSF/Ada-SPARK-Rectangle-Area) |
| **Rectangle Overlap** | [Ada-SPARK-Rectangle-Overlap](https://github.com/RobertBoettcherSF/Ada-SPARK-Rectangle-Overlap) |
| **Red Black Tree** | [Ada-SPARK-Red-Black-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Red-Black-Tree) |
| **Reduce Array Size To The Half** | [Ada-SPARK-Reduce-Array-Size-To-The-Half](https://github.com/RobertBoettcherSF/Ada-SPARK-Reduce-Array-Size-To-The-Half) |
| **Redundant Connection** | [Ada-SPARK-Redundant-Connection](https://github.com/RobertBoettcherSF/Ada-SPARK-Redundant-Connection) |
| **Redundant Connection II** | [Ada-SPARK-Redundant-Connection-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Redundant-Connection-II) |
| **Redundant Connection II Lite** | [Ada-SPARK-Redundant-Connection-II-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Redundant-Connection-II-Lite) |
| **Reference Counting** | [Ada-SPARK-Reference-Counting](https://github.com/RobertBoettcherSF/Ada-SPARK-Reference-Counting) |
| **Regular Expression Matching Lite** | [Ada-SPARK-Regular-Expression-Matching-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Regular-Expression-Matching-Lite) |
| **Relative Sort Array** | [Ada-SPARK-Relative-Sort-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Relative-Sort-Array) |
| **Remove All Adjacent Duplicates** | [Ada-SPARK-Remove-All-Adjacent-Duplicates](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-All-Adjacent-Duplicates) |
| **Remove All Adjacent Duplicates II** | [Ada-SPARK-Remove-All-Adjacent-Duplicates-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-All-Adjacent-Duplicates-II) |
| **Remove All Adjacent Duplicates In String** | [Ada-SPARK-Remove-All-Adjacent-Duplicates-In-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-All-Adjacent-Duplicates-In-String) |
| **Remove Duplicate Letters** | [Ada-SPARK-Remove-Duplicate-Letters](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicate-Letters) |
| **Remove Duplicates From Sorted Array** | [Ada-SPARK-Remove-Duplicates-From-Sorted-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicates-From-Sorted-Array) |
| **Remove Duplicates From Sorted Array II** | [Ada-SPARK-Remove-Duplicates-From-Sorted-Array-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicates-From-Sorted-Array-II) |
| **Remove Duplicates From Sorted List** | [Ada-SPARK-Remove-Duplicates-From-Sorted-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicates-From-Sorted-List) |
| **Remove Duplicates From Sorted List II** | [Ada-SPARK-Remove-Duplicates-From-Sorted-List-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicates-From-Sorted-List-II) |
| **Remove Duplicates Sorted** | [Ada-SPARK-Remove-Duplicates-Sorted](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Duplicates-Sorted) |
| **Remove Element** | [Ada-SPARK-Remove-Element](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Element) |
| **Remove K Digits** | [Ada-SPARK-Remove-K-Digits](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-K-Digits) |
| **Remove Linked List Elements** | [Ada-SPARK-Remove-Linked-List-Elements](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Linked-List-Elements) |
| **Remove Nth Node From End** | [Ada-SPARK-Remove-Nth-Node-From-End](https://github.com/RobertBoettcherSF/Ada-SPARK-Remove-Nth-Node-From-End) |
| **Reorder List** | [Ada-SPARK-Reorder-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Reorder-List) |
| **Reorganize String** | [Ada-SPARK-Reorganize-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Reorganize-String) |
| **Reorganize String Stub** | [Ada-SPARK-Reorganize-String-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Reorganize-String-Stub) |
| **Repeated String Match** | [Ada-SPARK-Repeated-String-Match](https://github.com/RobertBoettcherSF/Ada-SPARK-Repeated-String-Match) |
| **Repeated Substring Pattern** | [Ada-SPARK-Repeated-Substring-Pattern](https://github.com/RobertBoettcherSF/Ada-SPARK-Repeated-Substring-Pattern) |
| **Replace Elements With Greatest On Right** | [Ada-SPARK-Replace-Elements-With-Greatest-On-Right](https://github.com/RobertBoettcherSF/Ada-SPARK-Replace-Elements-With-Greatest-On-Right) |
| **Replace Words** | [Ada-SPARK-Replace-Words](https://github.com/RobertBoettcherSF/Ada-SPARK-Replace-Words) |
| **Reservoir Sampling** | [Ada-SPARK-Reservoir-Sampling](https://github.com/RobertBoettcherSF/Ada-SPARK-Reservoir-Sampling) |
| **Reshape The Matrix** | [Ada-SPARK-Reshape-The-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Reshape-The-Matrix) |
| **Restore IP Addresses** | [Ada-SPARK-Restore-IP-Addresses](https://github.com/RobertBoettcherSF/Ada-SPARK-Restore-IP-Addresses) |
| **Reverse Bits** | [Ada-SPARK-Reverse-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Bits) |
| **Reverse Integer** | [Ada-SPARK-Reverse-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Integer) |
| **Reverse Linked List** | [Ada-SPARK-Reverse-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Linked-List) |
| **Reverse Linked List II** | [Ada-SPARK-Reverse-Linked-List-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Linked-List-II) |
| **Reverse Only Letters** | [Ada-SPARK-Reverse-Only-Letters](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Only-Letters) |
| **Reverse Pairs Lite** | [Ada-SPARK-Reverse-Pairs-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Pairs-Lite) |
| **Reverse String** | [Ada-SPARK-Reverse-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-String) |
| **Reverse String II** | [Ada-SPARK-Reverse-String-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-String-II) |
| **Reverse Vowels** | [Ada-SPARK-Reverse-Vowels](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Vowels) |
| **Reverse Vowels Of A String** | [Ada-SPARK-Reverse-Vowels-Of-A-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Vowels-Of-A-String) |
| **Reverse Words** | [Ada-SPARK-Reverse-Words](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Words) |
| **Reverse Words In A String** | [Ada-SPARK-Reverse-Words-In-A-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Words-In-A-String) |
| **Reverse Words In A String III** | [Ada-SPARK-Reverse-Words-In-A-String-III](https://github.com/RobertBoettcherSF/Ada-SPARK-Reverse-Words-In-A-String-III) |
| **Ring Buffer** | [Ada-SPARK-Ring-Buffer](https://github.com/RobertBoettcherSF/Ada-SPARK-Ring-Buffer) |
| **Robot Return To Origin** | [Ada-SPARK-Robot-Return-To-Origin](https://github.com/RobertBoettcherSF/Ada-SPARK-Robot-Return-To-Origin) |
| **Roman To Int** | [Ada-SPARK-Roman-To-Int](https://github.com/RobertBoettcherSF/Ada-SPARK-Roman-To-Int) |
| **Roman To Integer** | [Ada-SPARK-Roman-To-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Roman-To-Integer) |
| **Rotate Array** | [Ada-SPARK-Rotate-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Rotate-Array) |
| **Rotate Image** | [Ada-SPARK-Rotate-Image](https://github.com/RobertBoettcherSF/Ada-SPARK-Rotate-Image) |
| **Rotate List** | [Ada-SPARK-Rotate-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Rotate-List) |
| **Rotate String** | [Ada-SPARK-Rotate-String](https://github.com/RobertBoettcherSF/Ada-SPARK-Rotate-String) |
| **Rotting Oranges** | [Ada-SPARK-Rotting-Oranges](https://github.com/RobertBoettcherSF/Ada-SPARK-Rotting-Oranges) |
| **Round Robin Scheduling** | [Ada-SPARK-Round-Robin-Scheduling](https://github.com/RobertBoettcherSF/Ada-SPARK-Round-Robin-Scheduling) |
| **Run Length Encoding** | [Ada-SPARK-Run-Length-Encoding](https://github.com/RobertBoettcherSF/Ada-SPARK-Run-Length-Encoding) |
| **SHA 1** | [Ada-SPARK-SHA-1](https://github.com/RobertBoettcherSF/Ada-SPARK-SHA-1) |
| **Same Tree** | [Ada-SPARK-Same-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Same-Tree) |
| **Samplesort** | [Ada-SPARK-Samplesort](https://github.com/RobertBoettcherSF/Ada-SPARK-Samplesort) |
| **Search 2D Matrix** | [Ada-SPARK-Search-2D-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-2D-Matrix) |
| **Search A 2D Matrix** | [Ada-SPARK-Search-A-2D-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-A-2D-Matrix) |
| **Search A 2D Matrix II** | [Ada-SPARK-Search-A-2D-Matrix-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-A-2D-Matrix-II) |
| **Search In A Binary Search Tree** | [Ada-SPARK-Search-In-A-Binary-Search-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-In-A-Binary-Search-Tree) |
| **Search In Rotated Sorted Array** | [Ada-SPARK-Search-In-Rotated-Sorted-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-In-Rotated-Sorted-Array) |
| **Search In Rotated Sorted Array II** | [Ada-SPARK-Search-In-Rotated-Sorted-Array-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-In-Rotated-Sorted-Array-II) |
| **Search Insert Position** | [Ada-SPARK-Search-Insert-Position](https://github.com/RobertBoettcherSF/Ada-SPARK-Search-Insert-Position) |
| **Seat Manager Stub** | [Ada-SPARK-Seat-Manager-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Seat-Manager-Stub) |
| **Seat Reservation Manager** | [Ada-SPARK-Seat-Reservation-Manager](https://github.com/RobertBoettcherSF/Ada-SPARK-Seat-Reservation-Manager) |
| **Secant Method** | [Ada-SPARK-Secant-Method](https://github.com/RobertBoettcherSF/Ada-SPARK-Secant-Method) |
| **Selection Algorithm** | [Ada-SPARK-Selection-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Selection-Algorithm) |
| **Selection Sort** | [Ada-SPARK-Selection-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Selection-Sort) |
| **Self Dividing Numbers** | [Ada-SPARK-Self-Dividing-Numbers](https://github.com/RobertBoettcherSF/Ada-SPARK-Self-Dividing-Numbers) |
| **Sequence Reconstruction Lite** | [Ada-SPARK-Sequence-Reconstruction-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Sequence-Reconstruction-Lite) |
| **Set Matrix Zeroes** | [Ada-SPARK-Set-Matrix-Zeroes](https://github.com/RobertBoettcherSF/Ada-SPARK-Set-Matrix-Zeroes) |
| **Shaker Sort** | [Ada-SPARK-Shaker-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Shaker-Sort) |
| **Shell Sort** | [Ada-SPARK-Shell-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Shell-Sort) |
| **Shift 2D Grid** | [Ada-SPARK-Shift-2D-Grid](https://github.com/RobertBoettcherSF/Ada-SPARK-Shift-2D-Grid) |
| **Shortest Bridge** | [Ada-SPARK-Shortest-Bridge](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Bridge) |
| **Shortest Common Supersequence Lite** | [Ada-SPARK-Shortest-Common-Supersequence-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Common-Supersequence-Lite) |
| **Shortest Completing Word** | [Ada-SPARK-Shortest-Completing-Word](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Completing-Word) |
| **Shortest Job Next** | [Ada-SPARK-Shortest-Job-Next](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Job-Next) |
| **Shortest Path In Binary Matrix** | [Ada-SPARK-Shortest-Path-In-Binary-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Path-In-Binary-Matrix) |
| **Shortest Remaining Time** | [Ada-SPARK-Shortest-Remaining-Time](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Remaining-Time) |
| **Shortest Seek First** | [Ada-SPARK-Shortest-Seek-First](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Seek-First) |
| **Shortest Unsorted Continuous Subarray** | [Ada-SPARK-Shortest-Unsorted-Continuous-Subarray](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Unsorted-Continuous-Subarray) |
| **Shortest Word Distance** | [Ada-SPARK-Shortest-Word-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Shortest-Word-Distance) |
| **Sieve Of Eratosthenes** | [Ada-SPARK-Sieve-Of-Eratosthenes](https://github.com/RobertBoettcherSF/Ada-SPARK-Sieve-Of-Eratosthenes) |
| **Sigmoid** | [Ada-SPARK-Sigmoid](https://github.com/RobertBoettcherSF/Ada-SPARK-Sigmoid) |
| **Simplify Path Stub** | [Ada-SPARK-Simplify-Path-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Simplify-Path-Stub) |
| **Simpson Rule** | [Ada-SPARK-Simpson-Rule](https://github.com/RobertBoettcherSF/Ada-SPARK-Simpson-Rule) |
| **Single Number** | [Ada-SPARK-Single-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Single-Number) |
| **Single Number II** | [Ada-SPARK-Single-Number-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Single-Number-II) |
| **Single Number III** | [Ada-SPARK-Single-Number-III](https://github.com/RobertBoettcherSF/Ada-SPARK-Single-Number-III) |
| **Sliding Window Max** | [Ada-SPARK-Sliding-Window-Max](https://github.com/RobertBoettcherSF/Ada-SPARK-Sliding-Window-Max) |
| **Sliding Window Maximum** | [Ada-SPARK-Sliding-Window-Maximum](https://github.com/RobertBoettcherSF/Ada-SPARK-Sliding-Window-Maximum) |
| **Sliding Window Median** | [Ada-SPARK-Sliding-Window-Median](https://github.com/RobertBoettcherSF/Ada-SPARK-Sliding-Window-Median) |
| **Slowsort** | [Ada-SPARK-Slowsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Slowsort) |
| **Smallest Integer Divisible By K** | [Ada-SPARK-Smallest-Integer-Divisible-By-K](https://github.com/RobertBoettcherSF/Ada-SPARK-Smallest-Integer-Divisible-By-K) |
| **Smooth Sort** | [Ada-SPARK-Smooth-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Smooth-Sort) |
| **Smoothsort** | [Ada-SPARK-Smoothsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Smoothsort) |
| **Snapshot Array Stub** | [Ada-SPARK-Snapshot-Array-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Snapshot-Array-Stub) |
| **Softmax** | [Ada-SPARK-Softmax](https://github.com/RobertBoettcherSF/Ada-SPARK-Softmax) |
| **Softmin** | [Ada-SPARK-Softmin](https://github.com/RobertBoettcherSF/Ada-SPARK-Softmin) |
| **Sort An Array** | [Ada-SPARK-Sort-An-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-An-Array) |
| **Sort Array By Parity** | [Ada-SPARK-Sort-Array-By-Parity](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Array-By-Parity) |
| **Sort Array By Parity II** | [Ada-SPARK-Sort-Array-By-Parity-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Array-By-Parity-II) |
| **Sort Characters By Frequency** | [Ada-SPARK-Sort-Characters-By-Frequency](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Characters-By-Frequency) |
| **Sort Colors** | [Ada-SPARK-Sort-Colors](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Colors) |
| **Sort Integers By The Number Of 1 Bits** | [Ada-SPARK-Sort-Integers-By-The-Number-Of-1-Bits](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Integers-By-The-Number-Of-1-Bits) |
| **Sort List Lite** | [Ada-SPARK-Sort-List-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-List-Lite) |
| **Sort Merge Join** | [Ada-SPARK-Sort-Merge-Join](https://github.com/RobertBoettcherSF/Ada-SPARK-Sort-Merge-Join) |
| **Sorted Array To BST** | [Ada-SPARK-Sorted-Array-To-BST](https://github.com/RobertBoettcherSF/Ada-SPARK-Sorted-Array-To-BST) |
| **Sorted List** | [Ada-SPARK-Sorted-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Sorted-List) |
| **Soup Servings Lite** | [Ada-SPARK-Soup-Servings-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Soup-Servings-Lite) |
| **Spaghetti Sort** | [Ada-SPARK-Spaghetti-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Spaghetti-Sort) |
| **Sparse Dot** | [Ada-SPARK-Sparse-Dot](https://github.com/RobertBoettcherSF/Ada-SPARK-Sparse-Dot) |
| **Sparse Set** | [Ada-SPARK-Sparse-Set](https://github.com/RobertBoettcherSF/Ada-SPARK-Sparse-Set) |
| **Sparse Vector Dot Stub** | [Ada-SPARK-Sparse-Vector-Dot-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Sparse-Vector-Dot-Stub) |
| **Spearman Rank Stub** | [Ada-SPARK-Spearman-Rank-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Spearman-Rank-Stub) |
| **Special Array With X Elements** | [Ada-SPARK-Special-Array-With-X-Elements](https://github.com/RobertBoettcherSF/Ada-SPARK-Special-Array-With-X-Elements) |
| **Spiral Matrix** | [Ada-SPARK-Spiral-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Spiral-Matrix) |
| **Spiral Matrix II** | [Ada-SPARK-Spiral-Matrix-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Spiral-Matrix-II) |
| **Split Array Largest Sum** | [Ada-SPARK-Split-Array-Largest-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Split-Array-Largest-Sum) |
| **Sqrt Integer** | [Ada-SPARK-Sqrt-Integer](https://github.com/RobertBoettcherSF/Ada-SPARK-Sqrt-Integer) |
| **Sqrt X** | [Ada-SPARK-Sqrt-X](https://github.com/RobertBoettcherSF/Ada-SPARK-Sqrt-X) |
| **Sqrtx** | [Ada-SPARK-Sqrtx](https://github.com/RobertBoettcherSF/Ada-SPARK-Sqrtx) |
| **Squares Of A Sorted Array** | [Ada-SPARK-Squares-Of-A-Sorted-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-Squares-Of-A-Sorted-Array) |
| **Stack Bounded** | [Ada-SPARK-Stack-Bounded](https://github.com/RobertBoettcherSF/Ada-SPARK-Stack-Bounded) |
| **Stack Using Queues Stub** | [Ada-SPARK-Stack-Using-Queues-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Stack-Using-Queues-Stub) |
| **Standard Score** | [Ada-SPARK-Standard-Score](https://github.com/RobertBoettcherSF/Ada-SPARK-Standard-Score) |
| **Stock Spanner Stub** | [Ada-SPARK-Stock-Spanner-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Stock-Spanner-Stub) |
| **Stooge Sort** | [Ada-SPARK-Stooge-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Stooge-Sort) |
| **Strand Sort** | [Ada-SPARK-Strand-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Strand-Sort) |
| **Stream Of Characters Lite** | [Ada-SPARK-Stream-Of-Characters-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Stream-Of-Characters-Lite) |
| **String Compression** | [Ada-SPARK-String-Compression](https://github.com/RobertBoettcherSF/Ada-SPARK-String-Compression) |
| **String To Integer Atoi** | [Ada-SPARK-String-To-Integer-Atoi](https://github.com/RobertBoettcherSF/Ada-SPARK-String-To-Integer-Atoi) |
| **String To Integer Atoi Stub** | [Ada-SPARK-String-To-Integer-Atoi-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-String-To-Integer-Atoi-Stub) |
| **Strstr Naive** | [Ada-SPARK-Strstr-Naive](https://github.com/RobertBoettcherSF/Ada-SPARK-Strstr-Naive) |
| **Student Attendance Record I** | [Ada-SPARK-Student-Attendance-Record-I](https://github.com/RobertBoettcherSF/Ada-SPARK-Student-Attendance-Record-I) |
| **Subarray Sum Equals K** | [Ada-SPARK-Subarray-Sum-Equals-K](https://github.com/RobertBoettcherSF/Ada-SPARK-Subarray-Sum-Equals-K) |
| **Subarrays With K Different Integers** | [Ada-SPARK-Subarrays-With-K-Different-Integers](https://github.com/RobertBoettcherSF/Ada-SPARK-Subarrays-With-K-Different-Integers) |
| **Subsets** | [Ada-SPARK-Subsets](https://github.com/RobertBoettcherSF/Ada-SPARK-Subsets) |
| **Subsets Bitmask** | [Ada-SPARK-Subsets-Bitmask](https://github.com/RobertBoettcherSF/Ada-SPARK-Subsets-Bitmask) |
| **Subsets II** | [Ada-SPARK-Subsets-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Subsets-II) |
| **Subtract Product Sum Digits** | [Ada-SPARK-Subtract-Product-Sum-Digits](https://github.com/RobertBoettcherSF/Ada-SPARK-Subtract-Product-Sum-Digits) |
| **Subtract The Product And Sum** | [Ada-SPARK-Subtract-The-Product-And-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Subtract-The-Product-And-Sum) |
| **Subtree Of Another Tree** | [Ada-SPARK-Subtree-Of-Another-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Subtree-Of-Another-Tree) |
| **Successful Pairs Of Spells And Potions** | [Ada-SPARK-Successful-Pairs-Of-Spells-And-Potions](https://github.com/RobertBoettcherSF/Ada-SPARK-Successful-Pairs-Of-Spells-And-Potions) |
| **Sudoku Solver Lite** | [Ada-SPARK-Sudoku-Solver-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Sudoku-Solver-Lite) |
| **Sum Of Digits Of String After Convert** | [Ada-SPARK-Sum-Of-Digits-Of-String-After-Convert](https://github.com/RobertBoettcherSF/Ada-SPARK-Sum-Of-Digits-Of-String-After-Convert) |
| **Sum Of Left Leaves** | [Ada-SPARK-Sum-Of-Left-Leaves](https://github.com/RobertBoettcherSF/Ada-SPARK-Sum-Of-Left-Leaves) |
| **Sum Of Subarray Minimums** | [Ada-SPARK-Sum-Of-Subarray-Minimums](https://github.com/RobertBoettcherSF/Ada-SPARK-Sum-Of-Subarray-Minimums) |
| **Sum Of Two Integers** | [Ada-SPARK-Sum-Of-Two-Integers](https://github.com/RobertBoettcherSF/Ada-SPARK-Sum-Of-Two-Integers) |
| **Sum Root To Leaf Numbers** | [Ada-SPARK-Sum-Root-To-Leaf-Numbers](https://github.com/RobertBoettcherSF/Ada-SPARK-Sum-Root-To-Leaf-Numbers) |
| **Summary Ranges** | [Ada-SPARK-Summary-Ranges](https://github.com/RobertBoettcherSF/Ada-SPARK-Summary-Ranges) |
| **Super Ugly Number** | [Ada-SPARK-Super-Ugly-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Super-Ugly-Number) |
| **Super Ugly Number Stub** | [Ada-SPARK-Super-Ugly-Number-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Super-Ugly-Number-Stub) |
| **Surface Area Of 3D Shapes** | [Ada-SPARK-Surface-Area-Of-3D-Shapes](https://github.com/RobertBoettcherSF/Ada-SPARK-Surface-Area-Of-3D-Shapes) |
| **Surrounded Regions** | [Ada-SPARK-Surrounded-Regions](https://github.com/RobertBoettcherSF/Ada-SPARK-Surrounded-Regions) |
| **Swap Nodes In Pairs** | [Ada-SPARK-Swap-Nodes-In-Pairs](https://github.com/RobertBoettcherSF/Ada-SPARK-Swap-Nodes-In-Pairs) |
| **Swapping Nodes In A Linked List** | [Ada-SPARK-Swapping-Nodes-In-A-Linked-List](https://github.com/RobertBoettcherSF/Ada-SPARK-Swapping-Nodes-In-A-Linked-List) |
| **Swim In Rising Water** | [Ada-SPARK-Swim-In-Rising-Water](https://github.com/RobertBoettcherSF/Ada-SPARK-Swim-In-Rising-Water) |
| **Swim In Rising Water Stub** | [Ada-SPARK-Swim-In-Rising-Water-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Swim-In-Rising-Water-Stub) |
| **Symmetric Tree** | [Ada-SPARK-Symmetric-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Symmetric-Tree) |
| **Tanimoto** | [Ada-SPARK-Tanimoto](https://github.com/RobertBoettcherSF/Ada-SPARK-Tanimoto) |
| **Target Sum** | [Ada-SPARK-Target-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Target-Sum) |
| **Target Sum Stub** | [Ada-SPARK-Target-Sum-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Target-Sum-Stub) |
| **Task Scheduler** | [Ada-SPARK-Task-Scheduler](https://github.com/RobertBoettcherSF/Ada-SPARK-Task-Scheduler) |
| **Task Scheduler Stub** | [Ada-SPARK-Task-Scheduler-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Task-Scheduler-Stub) |
| **Ternary Search** | [Ada-SPARK-Ternary-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Ternary-Search) |
| **The K Weakest Rows In A Matrix** | [Ada-SPARK-The-K-Weakest-Rows-In-A-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-The-K-Weakest-Rows-In-A-Matrix) |
| **The Skyline Problem Lite** | [Ada-SPARK-The-Skyline-Problem-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-The-Skyline-Problem-Lite) |
| **Third Maximum Number** | [Ada-SPARK-Third-Maximum-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Third-Maximum-Number) |
| **Three Divisors** | [Ada-SPARK-Three-Divisors](https://github.com/RobertBoettcherSF/Ada-SPARK-Three-Divisors) |
| **Three Sum** | [Ada-SPARK-Three-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Three-Sum) |
| **Three Sum Closest Stub** | [Ada-SPARK-Three-Sum-Closest-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Three-Sum-Closest-Stub) |
| **Tic Tac Toe Stub** | [Ada-SPARK-Tic-Tac-Toe-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Tic-Tac-Toe-Stub) |
| **Tim Sort** | [Ada-SPARK-Tim-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Tim-Sort) |
| **Tim Sort Stub** | [Ada-SPARK-Tim-Sort-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Tim-Sort-Stub) |
| **Time Based Key Value Store** | [Ada-SPARK-Time-Based-Key-Value-Store](https://github.com/RobertBoettcherSF/Ada-SPARK-Time-Based-Key-Value-Store) |
| **Time Map Stub** | [Ada-SPARK-Time-Map-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Time-Map-Stub) |
| **Timsort** | [Ada-SPARK-Timsort](https://github.com/RobertBoettcherSF/Ada-SPARK-Timsort) |
| **Title To Number** | [Ada-SPARK-Title-To-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Title-To-Number) |
| **To Lower Case** | [Ada-SPARK-To-Lower-Case](https://github.com/RobertBoettcherSF/Ada-SPARK-To-Lower-Case) |
| **Toeplitz Matrix** | [Ada-SPARK-Toeplitz-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Toeplitz-Matrix) |
| **Top K Frequent Elements** | [Ada-SPARK-Top-K-Frequent-Elements](https://github.com/RobertBoettcherSF/Ada-SPARK-Top-K-Frequent-Elements) |
| **Top K Frequent Stub** | [Ada-SPARK-Top-K-Frequent-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Top-K-Frequent-Stub) |
| **Top K Frequent Words** | [Ada-SPARK-Top-K-Frequent-Words](https://github.com/RobertBoettcherSF/Ada-SPARK-Top-K-Frequent-Words) |
| **Top Nodes Algorithm** | [Ada-SPARK-Top-Nodes-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Top-Nodes-Algorithm) |
| **Topological Sort** | [Ada-SPARK-Topological-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Topological-Sort) |
| **Topological Sort Lite** | [Ada-SPARK-Topological-Sort-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Topological-Sort-Lite) |
| **Total Hamming Distance** | [Ada-SPARK-Total-Hamming-Distance](https://github.com/RobertBoettcherSF/Ada-SPARK-Total-Hamming-Distance) |
| **Tournament Sort** | [Ada-SPARK-Tournament-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Tournament-Sort) |
| **Transpose Matrix** | [Ada-SPARK-Transpose-Matrix](https://github.com/RobertBoettcherSF/Ada-SPARK-Transpose-Matrix) |
| **Trapezoidal Rule** | [Ada-SPARK-Trapezoidal-Rule](https://github.com/RobertBoettcherSF/Ada-SPARK-Trapezoidal-Rule) |
| **Trapping Rain Water** | [Ada-SPARK-Trapping-Rain-Water](https://github.com/RobertBoettcherSF/Ada-SPARK-Trapping-Rain-Water) |
| **Trapping Rain Water II Lite** | [Ada-SPARK-Trapping-Rain-Water-II-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Trapping-Rain-Water-II-Lite) |
| **Tree Sort** | [Ada-SPARK-Tree-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Tree-Sort) |
| **Triangle** | [Ada-SPARK-Triangle](https://github.com/RobertBoettcherSF/Ada-SPARK-Triangle) |
| **Triangle Min Path** | [Ada-SPARK-Triangle-Min-Path](https://github.com/RobertBoettcherSF/Ada-SPARK-Triangle-Min-Path) |
| **Tribonacci** | [Ada-SPARK-Tribonacci](https://github.com/RobertBoettcherSF/Ada-SPARK-Tribonacci) |
| **Tribonacci Number** | [Ada-SPARK-Tribonacci-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Tribonacci-Number) |
| **Trigram Search** | [Ada-SPARK-Trigram-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Trigram-Search) |
| **Trim A Binary Search Tree** | [Ada-SPARK-Trim-A-Binary-Search-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Trim-A-Binary-Search-Tree) |
| **Trim BST Stub** | [Ada-SPARK-Trim-BST-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Trim-BST-Stub) |
| **Tweet Counts Stub** | [Ada-SPARK-Tweet-Counts-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Tweet-Counts-Stub) |
| **Two City Scheduling** | [Ada-SPARK-Two-City-Scheduling](https://github.com/RobertBoettcherSF/Ada-SPARK-Two-City-Scheduling) |
| **Two Pointers Sum** | [Ada-SPARK-Two-Pointers-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Two-Pointers-Sum) |
| **Two Sum** | [Ada-SPARK-Two-Sum](https://github.com/RobertBoettcherSF/Ada-SPARK-Two-Sum) |
| **Two Sum BST Stub** | [Ada-SPARK-Two-Sum-BST-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Two-Sum-BST-Stub) |
| **Two Sum II Input Array Is Sorted** | [Ada-SPARK-Two-Sum-II-Input-Array-Is-Sorted](https://github.com/RobertBoettcherSF/Ada-SPARK-Two-Sum-II-Input-Array-Is-Sorted) |
| **UTF 8 Validation** | [Ada-SPARK-UTF-8-Validation](https://github.com/RobertBoettcherSF/Ada-SPARK-UTF-8-Validation) |
| **Ugly Number** | [Ada-SPARK-Ugly-Number](https://github.com/RobertBoettcherSF/Ada-SPARK-Ugly-Number) |
| **Ugly Number II** | [Ada-SPARK-Ugly-Number-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Ugly-Number-II) |
| **Uncommon Words From Two Sentences** | [Ada-SPARK-Uncommon-Words-From-Two-Sentences](https://github.com/RobertBoettcherSF/Ada-SPARK-Uncommon-Words-From-Two-Sentences) |
| **Underground System Stub** | [Ada-SPARK-Underground-System-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Underground-System-Stub) |
| **Uniform Cost Search** | [Ada-SPARK-Uniform-Cost-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Uniform-Cost-Search) |
| **Union Find** | [Ada-SPARK-Union-Find](https://github.com/RobertBoettcherSF/Ada-SPARK-Union-Find) |
| **Unique BSTs Stub** | [Ada-SPARK-Unique-BSTs-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-BSTs-Stub) |
| **Unique Binary Search Trees** | [Ada-SPARK-Unique-Binary-Search-Trees](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Binary-Search-Trees) |
| **Unique Binary Search Trees II Lite** | [Ada-SPARK-Unique-Binary-Search-Trees-II-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Binary-Search-Trees-II-Lite) |
| **Unique Email Addresses** | [Ada-SPARK-Unique-Email-Addresses](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Email-Addresses) |
| **Unique Morse Code Words** | [Ada-SPARK-Unique-Morse-Code-Words](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Morse-Code-Words) |
| **Unique Paths** | [Ada-SPARK-Unique-Paths](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Paths) |
| **Unique Paths II** | [Ada-SPARK-Unique-Paths-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Paths-II) |
| **Unique Paths With Obstacles** | [Ada-SPARK-Unique-Paths-With-Obstacles](https://github.com/RobertBoettcherSF/Ada-SPARK-Unique-Paths-With-Obstacles) |
| **Univalued Binary Tree** | [Ada-SPARK-Univalued-Binary-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Univalued-Binary-Tree) |
| **Valid Anagram** | [Ada-SPARK-Valid-Anagram](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Anagram) |
| **Valid IP Address Stub** | [Ada-SPARK-Valid-IP-Address-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-IP-Address-Stub) |
| **Valid Number Stub** | [Ada-SPARK-Valid-Number-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Number-Stub) |
| **Valid Palindrome** | [Ada-SPARK-Valid-Palindrome](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Palindrome) |
| **Valid Palindrome II** | [Ada-SPARK-Valid-Palindrome-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Palindrome-II) |
| **Valid Parentheses** | [Ada-SPARK-Valid-Parentheses](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Parentheses) |
| **Valid Perfect Square** | [Ada-SPARK-Valid-Perfect-Square](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Perfect-Square) |
| **Valid Square** | [Ada-SPARK-Valid-Square](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Square) |
| **Valid Sudoku Stub** | [Ada-SPARK-Valid-Sudoku-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Sudoku-Stub) |
| **Valid Word Abbreviation** | [Ada-SPARK-Valid-Word-Abbreviation](https://github.com/RobertBoettcherSF/Ada-SPARK-Valid-Word-Abbreviation) |
| **Validate BST Stub** | [Ada-SPARK-Validate-BST-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Validate-BST-Stub) |
| **Validate Binary Search Tree** | [Ada-SPARK-Validate-Binary-Search-Tree](https://github.com/RobertBoettcherSF/Ada-SPARK-Validate-Binary-Search-Tree) |
| **Validate Stack Sequences** | [Ada-SPARK-Validate-Stack-Sequences](https://github.com/RobertBoettcherSF/Ada-SPARK-Validate-Stack-Sequences) |
| **Vector 2D Stub** | [Ada-SPARK-Vector-2D-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Vector-2D-Stub) |
| **Vector Dot Cross** | [Ada-SPARK-Vector-Dot-Cross](https://github.com/RobertBoettcherSF/Ada-SPARK-Vector-Dot-Cross) |
| **Walls And Gates** | [Ada-SPARK-Walls-And-Gates](https://github.com/RobertBoettcherSF/Ada-SPARK-Walls-And-Gates) |
| **Water Bottles** | [Ada-SPARK-Water-Bottles](https://github.com/RobertBoettcherSF/Ada-SPARK-Water-Bottles) |
| **Wiggle Sort** | [Ada-SPARK-Wiggle-Sort](https://github.com/RobertBoettcherSF/Ada-SPARK-Wiggle-Sort) |
| **Wiggle Subsequence** | [Ada-SPARK-Wiggle-Subsequence](https://github.com/RobertBoettcherSF/Ada-SPARK-Wiggle-Subsequence) |
| **Wildcard Matching Lite** | [Ada-SPARK-Wildcard-Matching-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Wildcard-Matching-Lite) |
| **Word Break** | [Ada-SPARK-Word-Break](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Break) |
| **Word Break II** | [Ada-SPARK-Word-Break-II](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Break-II) |
| **Word Break Stub** | [Ada-SPARK-Word-Break-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Break-Stub) |
| **Word Ladder II Lite** | [Ada-SPARK-Word-Ladder-II-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Ladder-II-Lite) |
| **Word Ladder Lite** | [Ada-SPARK-Word-Ladder-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Ladder-Lite) |
| **Word Ladder Stub** | [Ada-SPARK-Word-Ladder-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Ladder-Stub) |
| **Word Pattern** | [Ada-SPARK-Word-Pattern](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Pattern) |
| **Word Search** | [Ada-SPARK-Word-Search](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Search) |
| **Word Search II Lite** | [Ada-SPARK-Word-Search-II-Lite](https://github.com/RobertBoettcherSF/Ada-SPARK-Word-Search-II-Lite) |
| **XOR Of Numbers Range** | [Ada-SPARK-XOR-Of-Numbers-Range](https://github.com/RobertBoettcherSF/Ada-SPARK-XOR-Of-Numbers-Range) |
| **XOR Operation In An Array** | [Ada-SPARK-XOR-Operation-In-An-Array](https://github.com/RobertBoettcherSF/Ada-SPARK-XOR-Operation-In-An-Array) |
| **Z Algorithm** | [Ada-SPARK-Z-Algorithm](https://github.com/RobertBoettcherSF/Ada-SPARK-Z-Algorithm) |
| **Zigzag Iterator Stub** | [Ada-SPARK-Zigzag-Iterator-Stub](https://github.com/RobertBoettcherSF/Ada-SPARK-Zigzag-Iterator-Stub) |
| **Zobrist Hashing** | [Ada-SPARK-Zobrist-Hashing](https://github.com/RobertBoettcherSF/Ada-SPARK-Zobrist-Hashing) |

<!-- ADA-CATALOG:SPARK-END -->

<!-- ADA-CATALOG:A2022-BEGIN -->
## 📘 Ada 2022 Teaching Sheets

Small Ada 2022 standard-library / language teaching packages (`make && make test`, no SPARK).


---

### All Ada-2022 teaching sheets


| Package | Repository |
| --- | --- |
| **Abort Statement** | [Ada-2022-Abort-Statement](https://github.com/RobertBoettcherSF/Ada-2022-Abort-Statement) |
| **Access Types** | [Ada-2022-Access-Types](https://github.com/RobertBoettcherSF/Ada-2022-Access-Types) |
| **Address To Access Conversions** | [Ada-2022-Address-To-Access-Conversions](https://github.com/RobertBoettcherSF/Ada-2022-Address-To-Access-Conversions) |
| **Aggregates** | [Ada-2022-Aggregates](https://github.com/RobertBoettcherSF/Ada-2022-Aggregates) |
| **Anonymous Access** | [Ada-2022-Anonymous-Access](https://github.com/RobertBoettcherSF/Ada-2022-Anonymous-Access) |
| **Arrays And Records** | [Ada-2022-Arrays-And-Records](https://github.com/RobertBoettcherSF/Ada-2022-Arrays-And-Records) |
| **Aspects** | [Ada-2022-Aspects](https://github.com/RobertBoettcherSF/Ada-2022-Aspects) |
| **Asynchronous Select** | [Ada-2022-Asynchronous-Select](https://github.com/RobertBoettcherSF/Ada-2022-Asynchronous-Select) |
| **Attributes** | [Ada-2022-Attributes](https://github.com/RobertBoettcherSF/Ada-2022-Attributes) |
| **Big Integers** | [Ada-2022-Big-Integers](https://github.com/RobertBoettcherSF/Ada-2022-Big-Integers) |
| **Big Numbers** | [Ada-2022-Big-Numbers](https://github.com/RobertBoettcherSF/Ada-2022-Big-Numbers) |
| **Big Reals** | [Ada-2022-Big-Reals](https://github.com/RobertBoettcherSF/Ada-2022-Big-Reals) |
| **Bounded Doubly Linked Lists** | [Ada-2022-Bounded-Doubly-Linked-Lists](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Doubly-Linked-Lists) |
| **Bounded Hashed Maps** | [Ada-2022-Bounded-Hashed-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Hashed-Maps) |
| **Bounded Hashed Sets** | [Ada-2022-Bounded-Hashed-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Hashed-Sets) |
| **Bounded Multiway Trees** | [Ada-2022-Bounded-Multiway-Trees](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Multiway-Trees) |
| **Bounded Ordered Maps** | [Ada-2022-Bounded-Ordered-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Ordered-Maps) |
| **Bounded Ordered Sets** | [Ada-2022-Bounded-Ordered-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Ordered-Sets) |
| **Bounded Priority Queues** | [Ada-2022-Bounded-Priority-Queues](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Priority-Queues) |
| **Bounded Strings** | [Ada-2022-Bounded-Strings](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Strings) |
| **Bounded Synchronized Queues** | [Ada-2022-Bounded-Synchronized-Queues](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Synchronized-Queues) |
| **Bounded Vectors** | [Ada-2022-Bounded-Vectors](https://github.com/RobertBoettcherSF/Ada-2022-Bounded-Vectors) |
| **Calendar Arithmetic** | [Ada-2022-Calendar-Arithmetic](https://github.com/RobertBoettcherSF/Ada-2022-Calendar-Arithmetic) |
| **Calendar Delays** | [Ada-2022-Calendar-Delays](https://github.com/RobertBoettcherSF/Ada-2022-Calendar-Delays) |
| **Calendar Formatting** | [Ada-2022-Calendar-Formatting](https://github.com/RobertBoettcherSF/Ada-2022-Calendar-Formatting) |
| **Calendar Time Zones** | [Ada-2022-Calendar-Time-Zones](https://github.com/RobertBoettcherSF/Ada-2022-Calendar-Time-Zones) |
| **Calendar Timing** | [Ada-2022-Calendar-Timing](https://github.com/RobertBoettcherSF/Ada-2022-Calendar-Timing) |
| **Case If Expressions** | [Ada-2022-Case-If-Expressions](https://github.com/RobertBoettcherSF/Ada-2022-Case-If-Expressions) |
| **Characters Conversions** | [Ada-2022-Characters-Conversions](https://github.com/RobertBoettcherSF/Ada-2022-Characters-Conversions) |
| **Characters Handling** | [Ada-2022-Characters-Handling](https://github.com/RobertBoettcherSF/Ada-2022-Characters-Handling) |
| **Characters Latin 1** | [Ada-2022-Characters-Latin-1](https://github.com/RobertBoettcherSF/Ada-2022-Characters-Latin-1) |
| **Characters Latin 9** | [Ada-2022-Characters-Latin-9](https://github.com/RobertBoettcherSF/Ada-2022-Characters-Latin-9) |
| **Command Line** | [Ada-2022-Command-Line](https://github.com/RobertBoettcherSF/Ada-2022-Command-Line) |
| **Command Line Environment** | [Ada-2022-Command-Line-Environment](https://github.com/RobertBoettcherSF/Ada-2022-Command-Line-Environment) |
| **Complex Elementary** | [Ada-2022-Complex-Elementary](https://github.com/RobertBoettcherSF/Ada-2022-Complex-Elementary) |
| **Complex Elementary Functions** | [Ada-2022-Complex-Elementary-Functions](https://github.com/RobertBoettcherSF/Ada-2022-Complex-Elementary-Functions) |
| **Complex Text IO** | [Ada-2022-Complex-Text-IO](https://github.com/RobertBoettcherSF/Ada-2022-Complex-Text-IO) |
| **Complex Types** | [Ada-2022-Complex-Types](https://github.com/RobertBoettcherSF/Ada-2022-Complex-Types) |
| **Conditional Case Expressions** | [Ada-2022-Conditional-Case-Expressions](https://github.com/RobertBoettcherSF/Ada-2022-Conditional-Case-Expressions) |
| **Containers** | [Ada-2022-Containers](https://github.com/RobertBoettcherSF/Ada-2022-Containers) |
| **Contracts** | [Ada-2022-Contracts](https://github.com/RobertBoettcherSF/Ada-2022-Contracts) |
| **Controlled Types** | [Ada-2022-Controlled-Types](https://github.com/RobertBoettcherSF/Ada-2022-Controlled-Types) |
| **Decimal** | [Ada-2022-Decimal](https://github.com/RobertBoettcherSF/Ada-2022-Decimal) |
| **Declare Expressions** | [Ada-2022-Declare-Expressions](https://github.com/RobertBoettcherSF/Ada-2022-Declare-Expressions) |
| **Declare Quantify Combos** | [Ada-2022-Declare-Quantify-Combos](https://github.com/RobertBoettcherSF/Ada-2022-Declare-Quantify-Combos) |
| **Delta Aggregates** | [Ada-2022-Delta-Aggregates](https://github.com/RobertBoettcherSF/Ada-2022-Delta-Aggregates) |
| **Direct IO** | [Ada-2022-Direct-IO](https://github.com/RobertBoettcherSF/Ada-2022-Direct-IO) |
| **Directories** | [Ada-2022-Directories](https://github.com/RobertBoettcherSF/Ada-2022-Directories) |
| **Directories Hierarchical File Names** | [Ada-2022-Directories-Hierarchical-File-Names](https://github.com/RobertBoettcherSF/Ada-2022-Directories-Hierarchical-File-Names) |
| **Discrete Random** | [Ada-2022-Discrete-Random](https://github.com/RobertBoettcherSF/Ada-2022-Discrete-Random) |
| **Discriminants** | [Ada-2022-Discriminants](https://github.com/RobertBoettcherSF/Ada-2022-Discriminants) |
| **Dispatching** | [Ada-2022-Dispatching](https://github.com/RobertBoettcherSF/Ada-2022-Dispatching) |
| **Dispatching Yield** | [Ada-2022-Dispatching-Yield](https://github.com/RobertBoettcherSF/Ada-2022-Dispatching-Yield) |
| **Doubly Linked Lists** | [Ada-2022-Doubly-Linked-Lists](https://github.com/RobertBoettcherSF/Ada-2022-Doubly-Linked-Lists) |
| **Dynamic Priorities** | [Ada-2022-Dynamic-Priorities](https://github.com/RobertBoettcherSF/Ada-2022-Dynamic-Priorities) |
| **Elementary Functions** | [Ada-2022-Elementary-Functions](https://github.com/RobertBoettcherSF/Ada-2022-Elementary-Functions) |
| **Entry Families** | [Ada-2022-Entry-Families](https://github.com/RobertBoettcherSF/Ada-2022-Entry-Families) |
| **Environment Variables** | [Ada-2022-Environment-Variables](https://github.com/RobertBoettcherSF/Ada-2022-Environment-Variables) |
| **Exception Information** | [Ada-2022-Exception-Information](https://github.com/RobertBoettcherSF/Ada-2022-Exception-Information) |
| **Exceptions** | [Ada-2022-Exceptions](https://github.com/RobertBoettcherSF/Ada-2022-Exceptions) |
| **Execution Time** | [Ada-2022-Execution-Time](https://github.com/RobertBoettcherSF/Ada-2022-Execution-Time) |
| **Expression Functions** | [Ada-2022-Expression-Functions](https://github.com/RobertBoettcherSF/Ada-2022-Expression-Functions) |
| **Finalization** | [Ada-2022-Finalization](https://github.com/RobertBoettcherSF/Ada-2022-Finalization) |
| **Finalization Controlled** | [Ada-2022-Finalization-Controlled](https://github.com/RobertBoettcherSF/Ada-2022-Finalization-Controlled) |
| **Fixed Point** | [Ada-2022-Fixed-Point](https://github.com/RobertBoettcherSF/Ada-2022-Fixed-Point) |
| **Float Random** | [Ada-2022-Float-Random](https://github.com/RobertBoettcherSF/Ada-2022-Float-Random) |
| **Float Text IO** | [Ada-2022-Float-Text-IO](https://github.com/RobertBoettcherSF/Ada-2022-Float-Text-IO) |
| **Formal Packages** | [Ada-2022-Formal-Packages](https://github.com/RobertBoettcherSF/Ada-2022-Formal-Packages) |
| **GPR Projects** | [Ada-2022-GPR-Projects](https://github.com/RobertBoettcherSF/Ada-2022-GPR-Projects) |
| **Generics** | [Ada-2022-Generics](https://github.com/RobertBoettcherSF/Ada-2022-Generics) |
| **Hashed Maps** | [Ada-2022-Hashed-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Hashed-Maps) |
| **Hashed Sets** | [Ada-2022-Hashed-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Hashed-Sets) |
| **IO** | [Ada-2022-IO](https://github.com/RobertBoettcherSF/Ada-2022-IO) |
| **Indefinite Containers** | [Ada-2022-Indefinite-Containers](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Containers) |
| **Indefinite Doubly Linked Lists** | [Ada-2022-Indefinite-Doubly-Linked-Lists](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Doubly-Linked-Lists) |
| **Indefinite Hashed Maps** | [Ada-2022-Indefinite-Hashed-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Hashed-Maps) |
| **Indefinite Hashed Sets** | [Ada-2022-Indefinite-Hashed-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Hashed-Sets) |
| **Indefinite Holders** | [Ada-2022-Indefinite-Holders](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Holders) |
| **Indefinite Multiway Trees** | [Ada-2022-Indefinite-Multiway-Trees](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Multiway-Trees) |
| **Indefinite Ordered Maps** | [Ada-2022-Indefinite-Ordered-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Ordered-Maps) |
| **Indefinite Ordered Sets** | [Ada-2022-Indefinite-Ordered-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Ordered-Sets) |
| **Indefinite Vectors** | [Ada-2022-Indefinite-Vectors](https://github.com/RobertBoettcherSF/Ada-2022-Indefinite-Vectors) |
| **Integer Text IO** | [Ada-2022-Integer-Text-IO](https://github.com/RobertBoettcherSF/Ada-2022-Integer-Text-IO) |
| **Interfaces** | [Ada-2022-Interfaces](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces) |
| **Interfaces C** | [Ada-2022-Interfaces-C](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces-C) |
| **Interfaces C Extensions** | [Ada-2022-Interfaces-C-Extensions](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces-C-Extensions) |
| **Interfaces C Pointers** | [Ada-2022-Interfaces-C-Pointers](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces-C-Pointers) |
| **Interfaces C Strings** | [Ada-2022-Interfaces-C-Strings](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces-C-Strings) |
| **Interfaces Fortran** | [Ada-2022-Interfaces-Fortran](https://github.com/RobertBoettcherSF/Ada-2022-Interfaces-Fortran) |
| **Interrupts** | [Ada-2022-Interrupts](https://github.com/RobertBoettcherSF/Ada-2022-Interrupts) |
| **Iterator Filters** | [Ada-2022-Iterator-Filters](https://github.com/RobertBoettcherSF/Ada-2022-Iterator-Filters) |
| **Iterator Interfaces** | [Ada-2022-Iterator-Interfaces](https://github.com/RobertBoettcherSF/Ada-2022-Iterator-Interfaces) |
| **Iterators** | [Ada-2022-Iterators](https://github.com/RobertBoettcherSF/Ada-2022-Iterators) |
| **Limited Types** | [Ada-2022-Limited-Types](https://github.com/RobertBoettcherSF/Ada-2022-Limited-Types) |
| **Limited With** | [Ada-2022-Limited-With](https://github.com/RobertBoettcherSF/Ada-2022-Limited-With) |
| **Lists Deep Dive** | [Ada-2022-Lists-Deep-Dive](https://github.com/RobertBoettcherSF/Ada-2022-Lists-Deep-Dive) |
| **Locales** | [Ada-2022-Locales](https://github.com/RobertBoettcherSF/Ada-2022-Locales) |
| **Multiway Trees** | [Ada-2022-Multiway-Trees](https://github.com/RobertBoettcherSF/Ada-2022-Multiway-Trees) |
| **Null Exclusions** | [Ada-2022-Null-Exclusions](https://github.com/RobertBoettcherSF/Ada-2022-Null-Exclusions) |
| **Numerics** | [Ada-2022-Numerics](https://github.com/RobertBoettcherSF/Ada-2022-Numerics) |
| **Ordered Maps** | [Ada-2022-Ordered-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Ordered-Maps) |
| **Ordered Sets** | [Ada-2022-Ordered-Sets](https://github.com/RobertBoettcherSF/Ada-2022-Ordered-Sets) |
| **Packages** | [Ada-2022-Packages](https://github.com/RobertBoettcherSF/Ada-2022-Packages) |
| **Parallel Reduce** | [Ada-2022-Parallel-Reduce](https://github.com/RobertBoettcherSF/Ada-2022-Parallel-Reduce) |
| **Prefixed Views** | [Ada-2022-Prefixed-Views](https://github.com/RobertBoettcherSF/Ada-2022-Prefixed-Views) |
| **Protected Entries** | [Ada-2022-Protected-Entries](https://github.com/RobertBoettcherSF/Ada-2022-Protected-Entries) |
| **Put Image** | [Ada-2022-Put-Image](https://github.com/RobertBoettcherSF/Ada-2022-Put-Image) |
| **Quantified Expressions** | [Ada-2022-Quantified-Expressions](https://github.com/RobertBoettcherSF/Ada-2022-Quantified-Expressions) |
| **Random Numbers** | [Ada-2022-Random-Numbers](https://github.com/RobertBoettcherSF/Ada-2022-Random-Numbers) |
| **Real Time** | [Ada-2022-Real-Time](https://github.com/RobertBoettcherSF/Ada-2022-Real-Time) |
| **Reduce** | [Ada-2022-Reduce](https://github.com/RobertBoettcherSF/Ada-2022-Reduce) |
| **Reference Types** | [Ada-2022-Reference-Types](https://github.com/RobertBoettcherSF/Ada-2022-Reference-Types) |
| **Representation Clauses** | [Ada-2022-Representation-Clauses](https://github.com/RobertBoettcherSF/Ada-2022-Representation-Clauses) |
| **Requeue** | [Ada-2022-Requeue](https://github.com/RobertBoettcherSF/Ada-2022-Requeue) |
| **Select Statements** | [Ada-2022-Select-Statements](https://github.com/RobertBoettcherSF/Ada-2022-Select-Statements) |
| **Sequential IO** | [Ada-2022-Sequential-IO](https://github.com/RobertBoettcherSF/Ada-2022-Sequential-IO) |
| **Storage Elements** | [Ada-2022-Storage-Elements](https://github.com/RobertBoettcherSF/Ada-2022-Storage-Elements) |
| **Storage IO** | [Ada-2022-Storage-IO](https://github.com/RobertBoettcherSF/Ada-2022-Storage-IO) |
| **Stream IO** | [Ada-2022-Stream-IO](https://github.com/RobertBoettcherSF/Ada-2022-Stream-IO) |
| **Streams** | [Ada-2022-Streams](https://github.com/RobertBoettcherSF/Ada-2022-Streams) |
| **String Processing** | [Ada-2022-String-Processing](https://github.com/RobertBoettcherSF/Ada-2022-String-Processing) |
| **Strings Bounded** | [Ada-2022-Strings-Bounded](https://github.com/RobertBoettcherSF/Ada-2022-Strings-Bounded) |
| **Strings Fixed** | [Ada-2022-Strings-Fixed](https://github.com/RobertBoettcherSF/Ada-2022-Strings-Fixed) |
| **Strings Maps** | [Ada-2022-Strings-Maps](https://github.com/RobertBoettcherSF/Ada-2022-Strings-Maps) |
| **Strings Maps Constants** | [Ada-2022-Strings-Maps-Constants](https://github.com/RobertBoettcherSF/Ada-2022-Strings-Maps-Constants) |
| **Strings Unbounded** | [Ada-2022-Strings-Unbounded](https://github.com/RobertBoettcherSF/Ada-2022-Strings-Unbounded) |
| **Synchronized Queue Interfaces** | [Ada-2022-Synchronized-Queue-Interfaces](https://github.com/RobertBoettcherSF/Ada-2022-Synchronized-Queue-Interfaces) |
| **Synchronous Barriers** | [Ada-2022-Synchronous-Barriers](https://github.com/RobertBoettcherSF/Ada-2022-Synchronous-Barriers) |
| **Synchronous Task Control** | [Ada-2022-Synchronous-Task-Control](https://github.com/RobertBoettcherSF/Ada-2022-Synchronous-Task-Control) |
| **Tagged Streams** | [Ada-2022-Tagged-Streams](https://github.com/RobertBoettcherSF/Ada-2022-Tagged-Streams) |
| **Tagged Types** | [Ada-2022-Tagged-Types](https://github.com/RobertBoettcherSF/Ada-2022-Tagged-Types) |
| **Tags** | [Ada-2022-Tags](https://github.com/RobertBoettcherSF/Ada-2022-Tags) |
| **Target Name** | [Ada-2022-Target-Name](https://github.com/RobertBoettcherSF/Ada-2022-Target-Name) |
| **Task Attributes** | [Ada-2022-Task-Attributes](https://github.com/RobertBoettcherSF/Ada-2022-Task-Attributes) |
| **Task Discriminants** | [Ada-2022-Task-Discriminants](https://github.com/RobertBoettcherSF/Ada-2022-Task-Discriminants) |
| **Task Identification** | [Ada-2022-Task-Identification](https://github.com/RobertBoettcherSF/Ada-2022-Task-Identification) |
| **Task Termination** | [Ada-2022-Task-Termination](https://github.com/RobertBoettcherSF/Ada-2022-Task-Termination) |
| **Tasking Basics** | [Ada-2022-Tasking-Basics](https://github.com/RobertBoettcherSF/Ada-2022-Tasking-Basics) |
| **Text IO Bounded IO** | [Ada-2022-Text-IO-Bounded-IO](https://github.com/RobertBoettcherSF/Ada-2022-Text-IO-Bounded-IO) |
| **Text IO Complex IO** | [Ada-2022-Text-IO-Complex-IO](https://github.com/RobertBoettcherSF/Ada-2022-Text-IO-Complex-IO) |
| **Text IO Editing** | [Ada-2022-Text-IO-Editing](https://github.com/RobertBoettcherSF/Ada-2022-Text-IO-Editing) |
| **Text IO Enumeration IO** | [Ada-2022-Text-IO-Enumeration-IO](https://github.com/RobertBoettcherSF/Ada-2022-Text-IO-Enumeration-IO) |
| **Text IO Unbounded IO** | [Ada-2022-Text-IO-Unbounded-IO](https://github.com/RobertBoettcherSF/Ada-2022-Text-IO-Unbounded-IO) |
| **Timing Events** | [Ada-2022-Timing-Events](https://github.com/RobertBoettcherSF/Ada-2022-Timing-Events) |
| **Types And Subtypes** | [Ada-2022-Types-And-Subtypes](https://github.com/RobertBoettcherSF/Ada-2022-Types-And-Subtypes) |
| **UTF Encoding** | [Ada-2022-UTF-Encoding](https://github.com/RobertBoettcherSF/Ada-2022-UTF-Encoding) |
| **UTF Encoding Conversions** | [Ada-2022-UTF-Encoding-Conversions](https://github.com/RobertBoettcherSF/Ada-2022-UTF-Encoding-Conversions) |
| **UTF Encoding Strings** | [Ada-2022-UTF-Encoding-Strings](https://github.com/RobertBoettcherSF/Ada-2022-UTF-Encoding-Strings) |
| **Unbounded Priority Queues** | [Ada-2022-Unbounded-Priority-Queues](https://github.com/RobertBoettcherSF/Ada-2022-Unbounded-Priority-Queues) |
| **Unbounded Synchronized Queues** | [Ada-2022-Unbounded-Synchronized-Queues](https://github.com/RobertBoettcherSF/Ada-2022-Unbounded-Synchronized-Queues) |
| **Unbounded Text IO** | [Ada-2022-Unbounded-Text-IO](https://github.com/RobertBoettcherSF/Ada-2022-Unbounded-Text-IO) |
| **Unchecked Conversion** | [Ada-2022-Unchecked-Conversion](https://github.com/RobertBoettcherSF/Ada-2022-Unchecked-Conversion) |
| **Unchecked Deallocation** | [Ada-2022-Unchecked-Deallocation](https://github.com/RobertBoettcherSF/Ada-2022-Unchecked-Deallocation) |
| **User Defined Indexing** | [Ada-2022-User-Defined-Indexing](https://github.com/RobertBoettcherSF/Ada-2022-User-Defined-Indexing) |
| **User Defined Literals** | [Ada-2022-User-Defined-Literals](https://github.com/RobertBoettcherSF/Ada-2022-User-Defined-Literals) |
| **Vectors** | [Ada-2022-Vectors](https://github.com/RobertBoettcherSF/Ada-2022-Vectors) |
| **Vectors Deep Dive** | [Ada-2022-Vectors-Deep-Dive](https://github.com/RobertBoettcherSF/Ada-2022-Vectors-Deep-Dive) |
| **Visibility Renames** | [Ada-2022-Visibility-Renames](https://github.com/RobertBoettcherSF/Ada-2022-Visibility-Renames) |
| **Wide Characters Unicode** | [Ada-2022-Wide-Characters-Unicode](https://github.com/RobertBoettcherSF/Ada-2022-Wide-Characters-Unicode) |

<!-- ADA-CATALOG:A2022-END -->
