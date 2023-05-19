# ISC23 AHUG Workshop 

to be held in conjunction with ISC High Performance 2023 (https://www.isc-hpc.com/) in Hamburg, Germany. The AHUG workshop is scheduled on 25th May, 2:00pm-6:00pm. 

![Alt text](hamburg1.JPG "Optional title")

### Date and Time
25th May 2023<br>
2:00PM-6:00PM


### Place
Congress Center Hamburg (CCH), Germany<br>
Meeting room will be announced later

### Timetable and agenda 

<table>
<thead>
<td><b>Start</b></td>
<td><b>Duration</b></td>
<td><b>Speaker</b></td>
<td><b>Institution</b></td>
<td><b>Title</b></td>
</thead>
<tbody>
<tr>
<td> 2:00pm</td>
<td> -</td>
<td> </td>
<td> Filippo Spiga (AHUG) </td>
<td> Welcome and Housekeeping </td>
</tr>

<tr>
<td> 2:00pm</td>
<td> 20</td>
<td> Simon McIntosh-Smith</td>
<td> University of Bristol	</td>
<td> An update on the GW4 Isambard 3 Arm-based supercomputer
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
  The GW4 Isambard supercomputer was the first production Arm-based system when it went live in the spring of 2018. Having already gone through two generations of Arm technology, Isambard 3, due to launch at the end of 2023, will be based on NVIDIA's new Grace CPUs. Isambard 3 will deliver 5-6 times the performance of Isambard 2, while using only 20% more power. In this talk we will describe the new system, as well as giving an update on the progress of Isambard's multi-year mission to port and optimise codes to the Arm architecture.
  </details-menu>
</details>

</td>
</tr>

<tr>
<td> 2:20pm</td>
<td> 20</td>
<td> Nam Ho</td>	
<td> Julich	</td>
<td> Memory Prefetching Evaluation using gem5 Simulations
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　Significantly increased memory bandwidth is increasingly difficult to exploit in standard multicore CPU architectures. Memory prefetchers play an important role in hiding memory access latencies and ensuring sufficiently high memory-level parallelism. In this talk, we report on ongoing efforts for exploring their impact on various HPC benchmarks and mini-apps that implement performance-critical kernels of Lattice Boltzmann Method, finite element, and reverse time migration methods. Using modern Arm core cores we explore the performance impact of different memory prefetchers solutions and configurations that have been implemented in the gem5 simulator.
  </details-menu>
</details>
</td>
</tr>


<tr>
<td> 2:40pm</td>
<td> 20</td>
<td> Carlos Falquez</td>		
<td> Julich</td>
<td> Studying different BFS algorithm implementations with gem5
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　To leverage different CPU features, different implementations of the breadth-first search (BFS) algorithm have been proposed. The gem5 simulator provides the opportunity to investigate how these implementations exploit different CPU configurations. For our study, we assume a modern Arm processor core like Neoverse V1 and report on the impact of different SVE pipelines, cache, network-on-chip, and memory configurations.
  </details-menu>
</details>
</td>
</tr>

<tr>
<td> 3:00pm</td>
<td> 20</td>
<td> Chen Liu</td>		
<td> Clarkson</td>
<td> High Frequency Performance Monitoring via Architectural Event Measurement
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　Obtaining detailed software execution information via performance monitoring counters is a powerful analysis technique. Performance counters provide an effective method to monitor program behaviors; hence performance bottlenecks due to hardware architecture or software design and implementation can be identified, isolated and improved on. The granularity and overhead of the monitoring mechanism, however, are paramount to proper analysis. Many prior designs have been able to provide performance counter monitoring with inherited drawbacks such as intrusive code changes, a slow timer system, or the need for a kernel patch. In this session, we introduce K-LEB (Kernel - Lineage of Event Behavior), a new monitoring mechanism that can produce precise, non-intrusive, low-overhead, periodic performance counter data, and support ARM processors. In this talk, we will discuss the performance counter profiling tools design choice and implementation and how to utilize the performance monitoring counter for the low-cost software analysis and its applications.
  </details-menu>
</details>
</td>
</tr>

<tr>
<td> 3:20pm</td>
<td> 20</td>
<td> Luka Stanisic</td>		
<td> Huawei</td>
<td> Performance Evaluation of the Ginkgo Sparse Linear Solver Framework on Arm
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　The Ginkgo linear algebra library provides a set of preconditioners and iterative solvers for sparse systems. Ginkgo receives attention for supporting accelerators, but also targets CPUs with OpenMP kernels that we focus on. We characterize the behavior of Ginkgo’s benchmarks (SpMV with 5 formats, matrix conversions, 7 solvers, 9 preconditioners) wrt. hot kernels, top-down analysis, roofline model and working set, along with OpenMP imbalance, pragma use and thread placement on one AArch64 Huawei Kunpeng920 system using GNU GCC and 10 matrices from SuiteSparse. Selected results are complemented with evaluations on AWS Graviton3, 3rd-gen Intel Xeon and AMD EPYC. We offer guidance for optimizing the OpenMP executor by identifying tuning opportunities and pitfalls. The solvers are in the memory-bound region of the roofline model with arithmetic intensity from 0.1 to 3, leading to a FLOPS efficiency below 1%. Scalability is limited by OpenMP imbalance of up to 43% for selected usecases.cThe Ginkgo linear algebra library provides a set of preconditioners and iterative solvers for sparse systems. Ginkgo receives attention for supporting accelerators, but also targets CPUs with OpenMP kernels that we focus on. We characterize the behavior of Ginkgo’s benchmarks (SpMV with 5 formats, matrix conversions, 7 solvers, 9 preconditioners) wrt. hot kernels, top-down analysis, roofline model and working set, along with OpenMP imbalance, pragma use and thread placement on one AArch64 Huawei Kunpeng920 system using GNU GCC and 10 matrices from SuiteSparse. Selected results are complemented with evaluations on AWS Graviton3, 3rd-gen Intel Xeon and AMD EPYC. We offer guidance for optimizing the OpenMP executor by identifying tuning opportunities and pitfalls. The solvers are in the memory-bound region of the roofline model with arithmetic intensity from 0.1 to 3, leading to a FLOPS efficiency below 1%. Scalability is limited by OpenMP imbalance of up to 43% for selected usecases.
  </details-menu>
</details>
</td>
</tr>

<tr>
<td> 3:40pm</td>
<td> 20</td>
<td>Gilles Tourpe </td>		
<td> AWS</td>
<td> Hackathon with TERATEC - Feedback
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　AWS, ARM, UCit and TERATEC organized a Hackathon for HPC masters universities. 10 teams competed on porting a stencil code (contributed by CGG) and code_saturne (contributed by EDF R&D) on AWS graviton3 instances. The talk proposal is to report on the learnings. This talk will be supported by AWS and ARM.
  </details-menu>
</details>
</td>
</tr>

<tr>
<td> 4:00pm</td>
<td> 30</td>
<td colspan=4> Coffee Break</td>
</tr>

<tr>
<td> 4:30pm</td>
<td> 20</td>
<td> Brendan Bouffler</td>
<td> AWS</td>
<td> Updates from the field on Graviton 3E for HPC
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　Graviton 3E was engineered specifically for HPC customers and we've also launched an Hpc7g instance family, based on this processor, coupled with 200 Gb/s of Elastic Fabric Adapter. We'll explain how this works, how to get access to these using HPC tooling, and show the performance results we're seeing - contributed by customers.
  </details-menu>
</details>
</td>
</tr>


<tr>
<td> 4:50pm</td>
<td> 20</td>
<td> Etienne Renault</td>		
<td> SiPearl</td>
<td> Evaluation and performance projections for ARM chips
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　The variety of ARM chips (and SOC) that are used in the HPC realm make it difficult to anticipate performances on other ARM based architectures. This talk compares the relatives performances of ARM chips on different HPC benchmarks and shows some strategies to anticipate results with a variety of different configurations.
  </details-menu>
</details>
</td>
</tr>


<tr>
<td> 5:10pm</td>
<td> 20</td>
<td> Filippo Spiga</td>		
<td> NVIDIA</td>
<td>Accelerating time-to-science with the NVIDIA Superchip platform 
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
The present talk will highlight how the NVIDIA Superchip platform (Grace Superchip and Grace Hopper Superchip), enabled by Arm Neoverse IP, is enabling HPC users and developers to achieve a better time-to-solution and energy-to-solution in their scientific workflows. Performance numbers will be disclosed and discussed, as well as the latest updates on the product go-to-market options.
  </details-menu>
</details>
</td>
</tr>


<tr>
<td> 5:30pm</td>
<td> 20</td>
<td> Beau Paisley</td>		
<td> Linaro</td>
<td> An Analysis of Arm Graviton systems Using Linaro Performance Reports
<details>
  <summary>
    Abstract
  </summary>
  <details-menu>
　In this presentation we will give an overview of Linaro Performance Reports, an application profiler for HPC applications.  We will use the tool to create a case study for analyzing various configurations of the WRF weather code on various configurations of AWS Graviton systems. 
  </details-menu>
</details>
</td>
</tr>

<tr>
<td> 5:50pm</td>
<td> 10</td>
<td> </td>
<td> Miwako Tsuji (AHUG) </td>
<td> Wrap-up session and announcements </td>
</tr>


</tbody>
</table>


### Organizers
- Filippo Spiga (NVIDIA) 
- Simon McIntosh-Smith (University of Bristol)
- Eva Siegmann (Stony Brook University)
- Miwako Tsuji (RIKEN)
