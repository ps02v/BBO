# Biomedical Burden Ontology
The BBO repository holds the latest version of the Biomedical Burden Ontology (BBO). The BBO provides support for a number of burden-related entities. These include the various types of burden that are studied in a medical literature (e.g., treatment burden, symptom burden, disease burden, and so on). 

## Imported Ontologies
The BBO builds on the following ontologies:

| **Ontology** | **Acronym** | **Ontology IRI** |
|:-------:|:------:|:-------------:|
| [Basic Formal Ontology](https://github.com/bfo-ontology/BFO-2020) | BFO | [http://purl.obolibrary.org/obo/bfo.owl](http://purl.obolibrary.org/obo/bfo.owl) |
| [Common Core Ontologies](https://github.com/CommonCoreOntology/CommonCoreOntologies) | CCO | [http://www.ontologyrepository.com/CommonCoreOntologies/Mid/AllCoreOntology](http://www.ontologyrepository.com/CommonCoreOntologies/Mid/AllCoreOntology) |
| [Ontology for General Medical Science](https://github.com/OGMS/ogms) | OGMS | [http://purl.obolibrary.org/obo/ogms.owl](http://purl.obolibrary.org/obo/ogms.owl) |
| [Mental Functioning Ontology](https://github.com/jannahastings/mental-functioning-ontology) | MFO | [http://purl.obolibrary.org/obo/MF.owl](http://purl.obolibrary.org/obo/MF.owl) |
| [Emotion Ontology](https://github.com/jannahastings/emotion-ontology) | MFOEM | [http://purl.obolibrary.org/obo/MFOEM.owl](http://purl.obolibrary.org/obo/MFOEM.owl) |

A merged version of the BBO (containing all imported ontologies) is available [here](bbo-merged/).

# Directory Structure

## Files
* [`BBO.owl`](BBO.owl): The latest version of the BBO in Web Ontology Language (OWL) format.
* [`BBO.ttl`](BBO.ttl): The latest version of the BBO in Terse RDF Triple Language (Turtle) format.

## Directories
* `documentation/`: Contains documentation related to the BBO.
  * [`BBO Ontology Documentation.pdf`](documentation/BBO%20Ontology%20Documentation.pdf): Documentation for the classes/properties contained in the BBO, as well as a subset of the classes/properties in imported ontologies.
* `archive/`: Contains archived versions of the BBO for historical reference.
* `bbo-merged/`: Contains merged versions of the BBO.
    * [`BBO_Merged.owl`](bbo-merged/BBO_Merged.owl): A merged version of the BBO, including all imported ontologies (OWL format).
    * [`BBO_Merged.ttl`](bbo-merged/BBO_Merged.ttl): A merged version of the BBO, including all imported ontologies (Turtle format).

# BBO Entities
Some of the entities contained in the BBO are as follows:

* **Burden Process:** An affective process that represents the subjective experience of burden or the state of being burdened. 
* **Treatment Burden:** A burden process that arises as a result of one's participation in treatment processes.
* **Appraisal of Burden:** A cognitive representation that is produced by an appraisal process that occurs as part of a burden process.
* **Appraisal of Treatment Burden:** An appraisal of burden that refers to (is about) one's participation in a treatment process.
* **Conative Representation:** A mental representation that has a world-to-mind direction of fit. [This contrasts with cognitive representations that have a mind-to-world direction of fit.]
* **Expectation:** A conative representation that refers to future situations or states-of-affairs.
* **Positive Expectation:** An expectation that refers to situations an individual optimistically expects to occur.
* **Negative Expectation:** An expectation that refers to situations an individual optimistically expects _not_ to occur.
* **Negative Effect:** An effect that 1) decreases the subjective likelihood associated with a positive expectation or 2) increases the subjective likelihood associated with a negative expectation.
* **Appraisal of Burdensomeness:** An appraisal that refers to the impact of (or effect) of one's participation in a process. 

As suggested by this list, the BBO adopts a subjective or phenomenological approach, modelling burden as a particular sort of affective process. Such processes comprise appraisal processes that relate to one's 'obligatory' participation in certain sorts of processes (e.g., treatment processes). It is then one's appraisal of the effects (or impacts) of this participation that underwrite the experience of burden. According to the BBO, treatment processes become burdensome when one's participation in such processes yield negative effects, where the notion of a negative effect is understood in relation to individual expectations (see above).  

# More Information

Queries relating to the BBO should be directed to [Dr Paul Smart](mailto:ps02v@ecs.soton.ac.uk?subject=Biomedical%20Burden%20Ontology).

# Acknowledgements
The BBO was developed in the context of the [MELD-B](https://www.southampton.ac.uk/publicpolicy/support-for-policymakers/policy-projects/Current%20projects/meld-b.page) project, which is funded by the UK [National Institute of Health Research](https://www.nihr.ac.uk/) under grant agreement NIHR203988. 





