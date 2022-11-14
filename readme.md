This repository contains artifacts related to the submission "A Pattern Catalogue for Extending Digital Twin
Platforms with Behavioral Models". Therein we point out the current lack of support for modeling concepts for explicating behavioral aspects in Digital Twin Platforms. Related Digital Twin Modeling Languages (DTML) mostly support structural modeling of systems like Cyber-Physical Production Systems, but neglect the behavior of an object. Therefore we proposed several patterns to enhance DTML models to support explicit behavior modeling, and a snapshot-based approach to trace object states over time in histories, without requiring an extension of the DTML itself. Moreover, we debate the advantages and limitations while demonstrating them on the Azure Digital Twin Definition Language (DTDL). The patterns have been applied to our running example and the corresponding models are located as follows:

- EMF models (open + closed behavior pattern)
  - Using temporal annotations -> **BehaviouralDTP/3_layer_modeling_TS**
  - Using the snapshot-based pattern -> **BehaviouralDTP/3_layer_modeling_Snapshot**
- DTDL models (interfaces for open + closed behavior pattern) -> **BehaviouralDTP/DTDL_interfaces**
