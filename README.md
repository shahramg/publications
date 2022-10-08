## Publications 

1. Shahram Ghandeharizadeh. [Display of 3D Illuminations using Flying Light Specks](https://arxiv.org/pdf/2207.08346).  USC [FLS Laboratory](https://www.flslab.org/) Technical Report Number 2022-02.  A shorter (8 page) version of this paper appeared in the Proceedings of the 30th ACM International Conference on Multimedia (MM '22), October 10--14, 2022, Lisboa, Portugal, DOI https://dl.acm.org/doi/10.1145/3503161.3548250, ISBN 978-1-4503-9203-7/22/10. See https://github.com/shahramg/FLS-Multimedia2022 for experimental software.
    - Abstract:  This paper presents techniques to display 3D illuminations using Flying Light Specks, FLSs. Each FLS is a miniature (hundreds of micrometers) sized drone with one or more light sources to generate different colors and textures with adjustable brightness. It is network enabled with a processor and local storage. Synchronized swarms of cooperating FLSs render illumination of virtual objects in a pre-specified 3D volume, an FLS display. We present techniques to display both static and motion illuminations. Our display techniques consider the limited flight time of an FLS on a fully charged battery and the duration of time to charge the FLS battery. Moreover, our techniques assume failure of FLSs is the norm rather than an exception. We present a hardware and a software architecture for an FLS-display along with a family of techniques to compute flight paths of FLSs for illuminations. With motion illuminations, one technique (ICF) minimizes the overall distance traveled by the FLSs significantly when compared with the other techniques.

1. Shahram Ghandeharizadeh and Luis Garcia. [Safety in the Emerging Holodeck Applications](https://arxiv.org/pdf/2208.08398).  USC [FLS Laboratory](https://www.flslab.org/) Technical Report Number 2022-01.  This paper appeared in CHI 2022 Workshop on Novel Challenges of Safety, Security and Privacy in Extended Reality, April 25, 2022.
    - Abstract:  Technological advances in holography, robotics, and 3D printing are starting to realize the vision of a holodeck. These immersive 3D displays must address user safety from the start to be viable. A holodeck's safety challenges are novel because its applications will involve explicit physical interactions between humans and synthesized 3D objects and experiences in real-time. This pioneering paper first proposes research directions for modeling safety in future holodeck applications from traditional physical human-robot interaction modeling. Subsequently, we propose a test-bed to enable safety validation of physical human-robot interaction based on existing augmented reality and virtual simulation technology.

1. Shahram Ghandeharizadeh. [Holodeck: Immersive 3D Displays Using Swarms of Flying Light Specks](https://arxiv.org/pdf/2111.03657).  USC [FLS Laboratory](https://www.flslab.org/) Technical Report Number 2021-02.  A shorter version of this paper appeared in ACM Multimedia Asia (Gold Coast, Australia). https://doi.org/10.1145/3469877.3493698
    - Abstract:  Unmanned Aerial Vehicles (UAVs) have moved beyond a platform for hobbyists to enable environmental monitoring, journalism, film industry, search and rescue, package delivery, and entertainment. This paper describes 3D displays using swarms of flying light specks, FLSs. An FLS is a small (hundreds of micrometers in size) UAV with one or more light sources to generate different colors and textures with adjustable brightness. A synchronized swarm of FLSs renders an illumination in a pre-specified 3D volume, an FLS display. An FLS display provides true depth, enabling a user to perceive a scene more completely by analyzing its illumination from different angles. An FLS display may either be non-immersive or immersive. Both will support 3D acoustics. Non-immersive FLS displays may be the size of a 1980's computer monitor, enabling a surgical team to observe and control micro robots performing heart surgery inside a patient's body. Immersive FLS displays may be the size of a room, enabling users to interact with objects, e.g., a rock, a teapot. An object with behavior will be constructed using FLS-matters. FLS-matter will enable a user to touch and manipulate an object, e.g., a user may pick up a teapot or throw a rock. An immersive and interactive FLS display will approximate Star Trek's Holodeck. A successful realization of the research ideas presented in this paper will provide fundamental insights into implementing a Holodeck using swarms of FLSs. A Holodeck will transform the future of human communication and perception, and how we interact with information and data. It will revolutionize the future of how we work, learn, play and entertain, receive medical care, and socialize.

1. Haoyu Huang and Shahram Ghandeharizadeh. [Nova-LSM: A Distributed, Component-based LSM-tree Key-value Store](https://arxiv.org/pdf/2104.01305).  USC Database Laboratory Technical Report Number 2021-01.  In ACM-SIGMOD, Xi’an, Shaanxi, China, June 20-25, 2021.
   - Abstract:   The cloud infrastructure motivates disaggregation of monolithic data stores into components that are assembled together based on an application's workload. This study investigates disaggregation of an LSM-tree key-value store into components that communicate using RDMA. These components separate storage from processing, enabling processing components to share storage bandwidth and space. The processing components scatter blocks of a file (SSTable) across an arbitrary number of storage components and balance load across them using power-of-d. They construct ranges dynamically at runtime to parallelize compaction and enhance performance. Each component has configuration knobs that control its scalability. The resulting component-based system, Nova-LSM, is elastic. It outperforms its monolithic counterparts, both LevelDB and RocksDB, by several orders of magnitude with workloads that exhibit a skewed pattern of access to data.
   
1. Shahram Ghandeharizadeh and Haoyu Huang. [Scaling Data Stores with Skewed Data Access:  Solutions and Opportunities](./skeda.pdf).  USC Database Laboratory Technical Report Number 2019-03.  In 8th Workshop on Scalable Cloud Data Management, co-located with
IEEE BigData, Los Angeles, CA, December 9-12, 2019.
   - Abstract:  With a multi-node data store, a skewed pattern of access to data results in formation of hot spots and bottleneck servers.  In its most extreme, one server out of many may dictate the overall processing capability of the system, reducing the throughput of a thousand node system to that of one node.  This paper presents alternative bottlenecks due to a skewed pattern of data access and a taxonomy of solutions to resolve them.  We identify use of the emerging RDMA as an opportunity to design and implement novel load balancing algorithms.

2. Haoyu Huang and Shahram Ghandeharizadeh. [An Evaluation of RDMA-based Message Passing Protocols](./rdma.pdf).  USC Database Laboratory Technical Report Number 2019-02.
   - Abstract:  An enumeration of RDMA messaging verbs READ, WRITE, SEND/RECEIVE and queue pair types creates a diverse set of message passing protocols.  This paper constructs three abstract communication paradigms to quantify the performance and scalability characteristics of five protocols.  With each abstraction, different protocols provide different results and the identity of the protocol that is superior to the others changes.  Factors such as the number of queue pairs per node, the size of messages, the number of pending requests per queue pair, and the abstract communication paradigm dictate the superiority of a protocol.  These results are important for design and implementation of algorithms and techniques that use the emerging RDMA.

3. Shahram Ghandeharizadeh, Haoyu Huang, and Hieu Nguyen.  [Nova: Diffused Database Processing using Clouds of Components, Vision Paper](./nova.pdf).  USC Database Laboratory Technical Report Number 2019-01.  In the 15th IEEE International Conference on Beyond Database Architectures and Structures (BDAS), Ustron, Poland, May 28-31, 2019.
    - Abstract:  Nova proposes a departure from today's complex monolithic database management systems (DBMSs) as a service using the cloud.  It advocates a server-less alternative consisting of a cloud of simple components that communicate using high speed networks.   Nova will monitor the workload of an application continuously, configuring the DBMS to use the appropriate implementation of a component most suitable for processing the workload.  In response to load fluctuations, it will adjust the knobs of a component to scale it to meet the performance requirements of the application.  The vision of Nova is compelling because it adjusts resource usage, preventing either over-provisioning of resources that sit idle or over-utilized resources that yield a low performance, optimizing total cost of ownership.  In addition to introducing Nova, this vision paper presents key research challenges that must be addressed to realize Nova.  We explore two challenges in detail.

4. Shahram Ghandeharizadeh and Haoyu Huang.  [Hoagie:  A Database and Workload Generator using Published Specifications](./BPOD_2018.pdf). USC Database Laboratory Technical Report Number 2018-10.  In the Second IEEE International Workshop on Benchmarking, Performance Tuning and Optimization for Big Data Applications, Seattle, WA, December 10, 2018.
    - Abstract:  Hoagie   is   a   plug-n-play   workload   and   database generator to evaluate novel system architectures, design decisions, protocols, and algorithms. It uses published specifications to create a database of data items and a workload that references these data  items.  Hoagie<92>s  modular  design  enables  an  experimentalist to use it either offline or online. In offline mode, Hoagie outputs a trace file that can be used to issue requests to a target system.  In  online  mode,  Hoagie  is  plugged  into  an  existing  benchmark that  invokes  it  to  generate  requests  one  at  a  time  to  its  target system.  We  have  made  Hoagie  open  source  to  foster  its  future development.

