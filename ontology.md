# Awesome Ontology

[← Profile](./README.md)

A curated collection on **ontology engineering, multilingual knowledge representation, and knowledge graphs**.

Resources are collected for exploration; inclusion does not imply a completed implementation or reproduction. The notes below describe why each resource is worth investigating. Initial collection: **23 October 2026**.

## My practice

**[Bilingual ontology modeling](./research/knowledge-modeling.md)** — A personal exploration of Chinese–Japanese terminology, Python-based collection, RDF relations, and an ontology prototype using Protégé and OntoGraf.

## Start here

- **Design a vocabulary:** Ontology Development 101 → SKOS → Protégé.
- **Represent bilingual terminology:** SKOS labels and mappings → OntoLex-Lemon.
- **Build a repeatable workflow:** RDFLib → SHACL / pySHACL → ROBOT.
- **Explore the wider field:** Knowledge Graphs → Unifying Large Language Models and Knowledge Graphs.

## Projects & tools

| Resource | What it offers | Exploration angle |
| --- | --- | --- |
| [Protégé](https://protege.stanford.edu/) | Open-source OWL ontology editing, with desktop and collaborative web editions. | Define concepts and relations; inspect an ontology through its editor and reasoning tools. |
| [RDFLib](https://github.com/RDFLib/rdflib) | Python tooling for working with RDF. | Move between structured terminology data and RDF graphs in a reproducible Python workflow. |
| [pySHACL](https://github.com/RDFLib/pySHACL) | A Python validator for SHACL. | Check whether a graph meets explicit requirements, such as required labels or property types. |
| [ROBOT](https://github.com/ontodev/robot) · [Documentation](https://robot.obolibrary.org/) | Command-line and library tools for ontology workflows, including querying, reasoning, reports, and templates. | Study how ontology checks and releases can be automated. Developed in the OBO ecosystem. |
| [OBO Foundry](https://obofoundry.org/) | A community and collection of interoperable biological and biomedical ontologies. | Learn from real examples of definitions, identifiers, versioning, and collaborative maintenance. |

## Papers & guides

### Ontology Development 101: A Guide to Creating Your First Ontology

Natalya F. Noy and Deborah L. McGuinness · Stanford technical guide<br>
[Read the guide](https://protege.stanford.edu/publications/ontology_development/ontology101.pdf)

A practical introduction to defining scope, reusing existing knowledge, and organizing classes and properties. A useful starting point before choosing tools.

**Reading question:** what distinctions belong in the conceptual model, and which belong in language-specific labels?

### Knowledge Graphs

Aidan Hogan et al. · *ACM Computing Surveys*, 2021<br>
[Paper](https://arxiv.org/abs/2003.02320) · [DOI](https://doi.org/10.1145/3447772)

A broad survey spanning graph data models, schemas, identity, knowledge representation, construction, and quality assessment.

**Reading question:** which parts of a knowledge graph describe its schema, its instances, and the context of its claims?

### Unifying Large Language Models and Knowledge Graphs: A Roadmap

Shirui Pan et al. · *IEEE Transactions on Knowledge and Data Engineering*, 2024<br>
[Paper](https://arxiv.org/abs/2306.08302) · [DOI](https://doi.org/10.1109/TKDE.2024.3352100)

A roadmap covering knowledge-graph-enhanced language models, language-model-assisted graph work, and joint approaches.

**Reading question:** where can an explicit schema improve consistency, and where does model-generated knowledge still require validation?

## Standards & specifications

| Reference | Use it for |
| --- | --- |
| [SKOS Reference](https://www.w3.org/TR/skos-reference/) · W3C Recommendation | Concept schemes, multilingual labels, broader/narrower relations, and mappings between vocabularies. |
| [OWL 2 Primer](https://www.w3.org/TR/owl2-primer/) · W3C Recommendation | Formal classes, properties, individuals, and logical modeling. |
| [OntoLex-Lemon](https://www.w3.org/2016/05/ontolex/) · Community Group Report | Linking lexical entries, forms, and senses to ontology entities. This is a community specification, not a W3C Recommendation. |
| [SHACL](https://www.w3.org/TR/shacl/) · W3C Recommendation | Expressing constraints and validating RDF graphs against them. |

## Questions for future notes

- How should a bilingual vocabulary distinguish translation equivalents from merely related concepts?
- When is a lightweight SKOS concept scheme sufficient, and when are OWL axioms useful?
- How can changes in definitions and relations be tracked without losing their provenance?
- Which checks can be automated, and which require domain judgment?

## Adding a resource

Keep each entry short: **title and primary-source link → problem addressed → reason to explore → notes after reading or trying it**. Prefer original papers, official documentation, and source repositories. Add implementation notes only after running an example, with the version and observed limitations.
