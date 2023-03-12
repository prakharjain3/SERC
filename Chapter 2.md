# Chapter 2

## Background

### 2.1 Self-adaptive systems

#### 2.1.1 Definition

* Self-adaptive software can evaluate and change its own behavior whenever the evaluation shows that the software is not accomplishing what it was intended to do, or when better functionality or performance may be possible [33].

#### 2.1.2 Conceptual Model of a Self-Adaptive System

It basically consists of 4 Components:

* Environment - anything which is not in control of the system (generally represents the external world with which the system interacts) and the outcome of which affects the system.
* Managed System - It refers to the application code that implements the system's functionality.
* Adaptation Goals - The goals essentially focus on the software quality of the managed system.
* Managing System - It is responsible for the adaptation of the managed system.

#### 2.1.3 Engineering Self-Adaptive Systems

The approach used in this thesis is based on the MAPE-K framework.

#### 2.1.4 MAPE-K

The MAPE-K framework is a conceptual model for self-adaptive systems. It is a cycle that consists of 4 key phases:

* Monitor (M) - The monitor activity is responsible for monitoring the managing system by collecting different types of data(of the managing system).
* Adapt (A) - Analyzes the data obtained from the monitor activity and identify if there is a need for adaptation.
* Plan (P) - to generate an adaption strategy to apply to the system to meet the overall goals.
* Execute (E) - the plan which is forwaded from the Plan activity is to execute the adaption plan.
* Knowledge (K) - shared space that consists of data that can be shared by the MAPE activities.

Different approaches to Self-Adaptive Systems

<table>
<tbody>
<th>Waves</th>
<th>Framework</th>
<tr><td>Automating Tasks</td><td>MAPE - K</td></tr>
<tr><td>Architecture-
Based
Adaptation</td><td>3-Layer Architectural
Model</td></tr>
<tr><td>Models at
Runtime</td><td>Model-Oriented
Architecture</td></tr>
<tr><td>Goal
Driven
Adaptation</td><td>Goal Model</td></tr>
<tr><td>Guarantees
Under Uncertainties</td><td>QoSMOS Architecture</td></tr>
<tr><td>Control-
Based
Approaches</td><td>PBM</td></tr>
</tbody>
</table>

#### 2.1.5 Architectural Patterns for Self-adaptation in IoT

Can be categorized into two main categories:

* Behavioral Adaptation - results in reconfigurations on the system behavior.
* Structural Adaptation - when a change in the structure of the underlying system.
  
Three different Architectural patterns for self-adaptation IoT were proposed by Musil.

* Synthesize-Utilize (SU) - decentralized, consists of autonomous entities on the application layer. This layer receives data from physical resources and autonomous entities.
* Syntesize-Command (SC) - centralized, consists of autonomous entities on the service middleware layer. All the sensor nodes and other components communicate to a central server which will then perform decision-making process.
* Collect-Organize (CO) - semi-decentralized, mulit-agent systems on the application layer which handles the physical resources and MAPE-K based adaption mechanism in the service middleware layer.

Continue from page 16
