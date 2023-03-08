# Chapter 1

## Introduction

Hence, in this thesis, we scope our research area within the context of IoT systems and see how the results can be generalized to other modern software systems.

### 1.1 Architecting IoT Systems: The Challenges

* Heterogenity - IoT systems are heterogeneous in nature as they consist of a large number of devices, each with its own hardware and software components. `Majorly heteroginity arises due to devices and different backend services.`
* Interoperability - The devices in IoT systems are not only heterogeneous but also have `different communication protocols`, which makes it difficult to interconnect them. Each device may follow `their own data standards and formats`.
  EDA and MSA handle some of the challenges related to heterogenity and interoperability.
* Security - The communication between the devices should happen in a secure channel otherwise an attacker might be able to extract sensitive information.
  Blockchain handles some of the challenges to security

The IoT devices are deployed in uncertain and unpredictable environments.

These uncertainities coupled with the challenges mentioned above significantly affect the QoS.

And thereby self-adaptation techniques have been proposed as a solution. This is mainly due to their ability to handle the uncertainty as well as the dynamic nature of the environment.

### 1.2 Challenges in Self-adaptation

* Reactive nature of adaptation - Most of the self-adaptation techniques are reactive in nature. They adapt to the changes in the environment only after the changes have occurred. This is not suitable for IoT systems as the changes in the environment are unpredictable and may occur at any time. Hence, the self-adaptation techniques should be proactive (creating or controlling a situation rather than just responding to it after it has happened) in nature.
* Systems adapt, but they do not learn - literally the title.
Adaptation is a process of changing the system to suit the environment.
Learning is a process of acquiring knowledge or skill through experience.
`Solutions` - we can leverage ml techniques towards aiding adaptation
* Quality assurances to learning: using ml without any quality assurance is not a good idea as ml suffers from accuracy and bias issues.

### 1.3 Research Questions

* RQ1 How to perform effective and efficient proactive adaptation using machine learning techniques?
  Tackles challenge one Reactive nature of adaptation
* RQ2 How can machine learning be used to improve the adaptation process continuously?
  Tackles challenge two Systems adapt, but they do not learn
* RQ3 How to guarantee the quality of the adaptation performed by such a machine learning process, and how can such guarantees, in turn, help the machine learning process?
  Tackles Challenge three Quality assurances to learning
* RQ4 How can the approach be generalized to other class of software systems?
  Self Explanatory

### 1.4 Self-adaptation to Self-learning : Solution Overview

"Given a task T of solving an architectural problem, given the architecture A of the IoT system, and a set of quality attributes Q that models the QoS of the system, the architecture A of the system improves with Data D, such that the QoS Q of the system is not compromised"

Reading the section would be a good idea.

Continue from page no