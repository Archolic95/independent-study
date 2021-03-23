# independent-study
 
**3D Neural Procedural Modeling**

_Spring 2021 | Runjia Tian | Advisor: Prof. Andrew Witt_

In late 2020, Autodesk Research published Fusion360 Reconstruction, a dataset that includes the construction sequence for more than 5,000 objects created by designers.

The independent study investigates the idea that shape creation could be formulized as sequential and relational language, and whether the shape creation process could be generalized to a probabilistic distribution that could be learnt by deep Neural Networks.

**Description**

Based upon previous work in imitating 3D geometric modeling as sequential CAD commands, the independent study project will further explore and investigate the following questions:

- Does the previous approach of using Recurrent Neural Network suggests a strong relationship between the type of object and its design construction sequence?
- Instead of using implicit representation of construction graph such as using all topological sort ordering for construction sequence, is there an alternative approach that could perform the CAD command suggestion through explicit graphs? One such approach is to formulate each design construction graph as a Directed Acyclic Graph (DAG)
- In the case of using DAG for the representation of construction graph, could similar command suggestion inference be learnt by other forms of Neural Networks, such as using Reinforcement Learning and Q-Learning (DQN) for generating DAGs.
- The previous work using RNN has already deploy such model to Fusion 360 as user interface. Can we deploy the DAG-based model to Fusion 360 as well?
- Once the model is deployed, can we carry out a user research for testing whether such interface is really helpful for geometric modeling? (IRB might be required)
- Based on the above research, are there commonalities between the modeling graph of various objects? What other conclusions could we draw/interpret through this project?

**Deliverables**

_Research precedents in the fields of Neural Procedural Modeling_

Success Criteria:

Develop an in-depth literature review in neural procedural modeling across multiple domains.

_Learning Algorithm for procedural modeling_

Success Criteria: Develops a learning algorithm that makes neural command prediction or inference to a certain level of accuracy. Hacker level: learning algorithm create random imporisation

_Suggestive User Interface_

Success Criteria: Integrating learning algorithm into interactive user interface that suggests current modeling target as well as immediate subsequent commands.

_(Advanced) Execute BIM Dataset with neural procedural modeling_

Success Criteria: Use similar methodology to experiment with executing 3D shapes for architecture designs.

**Scheduling**

| **Week** | **Date** | **Research Scope** |
| --- | --- | --- |
| **Week 3 - 4** | 2.8 - 2.23 | Recap procedural modeling as sequential commands, precedents study on neural procedural modeling |
| **Week 5 - 6** | 2.24 - 3.9 | Procedural modeling as Directed Acyclic Graphs (DAGs) |
| **Week 7 - 8** | 3.10 - 3.23 | Procedural modeling as policy in Reinforcement Learning |
| **Week 9 - 10** | 3.24 - 4.6 | Enactive procedural modeling user interface |
| **Week 11 - 12** | 4.7 - 4.20 | Procedural modeling for architecture |
| **Week 13 - 14** | 4.21 - 5.3 | Prepare for final report |

**Bibliography**

1. Chaudhuri, Siddhartha, and Koltun, Vladlen. &quot;Data-Driven Suggestions for Creativity Support in 3D Modeling.&quot; ACM Transactions on Graphics, vol. 29, no. 6, 2010, pp. 1–10.
2. Chen, Mia, et al. &quot;Gmail Smart Compose.&quot; Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery &amp; Data Mining, 2019, pp. 2287–2295.
3. Davis, Nicholas, et al. &quot;Empirically Studying Participatory Sense-Making in Abstract Drawing with a Co-Creative Cognitive Agent.&quot; Proceedings of the 21st International Conference on Intelligent User Interfaces, 2016, pp. 196–207.
4. Igarashi, Takeo, and Hughes, John. &quot;A Suggestive Interface for 3D Drawing.&quot; ACM SIGGRAPH 2007 Courses, 2007, 20-Es.
5. Matejka, Justin, et al. &quot;CommunityCommands: command recommendations for software applications.&quot; Proceedings of the 22nd annual ACM symposium on User interface software and technology. 2009.
6. Shardanand, Upendra, and Pattie Maes. &quot;Social information filtering: algorithms for automating &quot;word of mouth&quot;.&quot; Proceedings of the SIGCHI conference on Human factors in computing systems. 1995.
7. Sutherland, Ivan E. &quot;Sketchpad a man-machine graphical communication system.&quot; Simulation 2.5 (1964): R-3.
8. Willis, Karl D. D, et al. &quot;Fusion 360 Gallery: A Dataset and Environment for Programmatic CAD Reconstruction.&quot; 2020.