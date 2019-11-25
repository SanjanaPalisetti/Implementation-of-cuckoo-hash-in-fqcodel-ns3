# Implementation-of-cuckoo-hash-in-fqcodel-ns3

__Brief__: _Flow Queue Controlled Delay_ (FQ-CoDel) is a hybrid packet scheduler and _Active Queue Management_ (AQM) algorithm, a powerful tool for fighting _bufferbloat_, a commonly occurring problem among networks,  and reducing latency. It is implemented in ns-3 to simulate the scheduling and hashing of flows. However, the ns-3 implementation of FQ-CoDel uses the common modulus hashing algorithm which does not handle collisions. We aim to provide a method to handle collisions in FQ-CoDel by implementing an alternative hash function called _Cuckoo hash_

# Cuckoo Hash


# References:
- [The Flow Queue CoDel Packet Scheduler and Active Queue Management Algorithm](https://tools.ietf.org/html/rfc8290)

This memo presents the FQ-CoDel hybrid packet scheduler and Active Queue Management (AQM) algorithm, a powerful tool for fighting bufferbloat and reducing latency.
- [Cuckoo hashing](https://www.cs.tau.ac.il/~shanir/advanced-seminar-data-structures-2009/bib/pagh01cuckoo.pdf)

This PDF presents the Cuckoo hashing algorithm - analysis, setup, implementation and results.
- [ns-3 code of FQ-CoDel](https://gitlab.com/nsnam/ns-3-dev/blob/master/src/traffic-control/model/fq-codel-queue-disc.h)

A flow queue used by the FqCoDel queue disc in ns3-dev

# Contributors:
__Guide__: Dr. Mohit P. Tahiliani

__Members__: Sanjana Palisetti, Meghna Savit, Mishal Ahmed 
