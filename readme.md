# A Pattern Catalogue for Extending Digital Twin Platforms with Behavioral Models

This repository contains artifacts and evaluation data related to the submission "A Pattern Catalogue for Extending Digital Twin
Platforms with Behavioral Models" submitted to the Journal "Automatisierungstechnik". Therein we point out the current lack of support for modeling concepts for explicating behavioral aspects in Digital Twin Platforms (although such support is given in modeling frameworks such as the Eclipse Modeling Framework (EMF)). Related Digital Twin Modeling Languages (DTML) mostly support structural modeling of systems like Cyber-Physical Production Systems, but neglect the behavior of an object. Therefore we proposed several patterns to enhance DTML models to support explicit behavior modeling, and a snapshot-based approach to trace object states over time in histories, without requiring an extension of the DTML itself. Moreover, we debate the advantages and limitations while demonstrating them on the Azure Digital Twin Definition Language (DTDL). 

In this repository, we collected example models that apply these different patterns to a running example described in the paper.
- The models which show the application of the open and closed system behavior pattern within EMF are located in the following folders:
  - Using temporal annotations -> **[BehaviouralDTP/3_layer_modeling_TS](BehaviouralDTP/3_layer_modeling_TS)**
  - Using the snapshot-based pattern -> **[BehaviouralDTP/3_layer_modeling_Snapshot](BehaviouralDTP/3_layer_modeling_Snapshot)**
- The corresponding DTDL models that can be imported into the Azure Digital Twins Service for both the open and closed behavior pattern in combination with the temporal annotation based history patterns are located in the following folder: **[BehaviouralDTP/DTDL_interfaces](BehaviouralDTP/DTDL_interfaces)**
