# Linux Rootkit IOCs
This repository contains a collection of "Indicators of Compromise" for 24 rootkits targeting the Linux operating system.\
They have been acquired during the detailed analysis of each rootkit and should aid forensic investigators in the examination of potentially infected systems.

---

The IOCs have been divided into three main categories:

#### File paths:
Paths of different files belonging to the rootkit. 
These are either absolute or, in some cases, just filenames, which may be located in arbitrary locations on the system. 
Some file paths include randomized values to make automated searches more challenging.

#### Strings:
Unique strings collected from files and memory dumps belonging to the rootkit.

#### Network traffic:
Rootkit-specific payloads as well as general information (e.g. ports, protocols) about the rootkits network traffic.\
Note, that many of the listed values are defaults, which may be modified by the attacker before deploying the rootkit.

---

The analysis and acquisition of these IOCs have been conducted as part of a research project exploring the current state of Linux rootkits and evaluating different "real-world" approaches for their detection. For more information about how they may be utilized during forensic investigations, please see the accompanying research paper: www.awesome-paper.com
