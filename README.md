
# Peergen

![*Promising Genomics* by Mike Fortun](images/promising_genomics.jpg)

Working for a decade on projects collecting genomic data from Finnish citizens, such as [Kardiokompassi](https://kardiokompassi.fi/) and [Digital Health Revolution](http://www.digitalhealthrevolution.fi/), and working adjacent to the Finnish national genome project, i experienced the many problems and challenges faced by genomic health research and translation. Working with personal data projects over the same years, i saw multiple ways in which personal data vaults cut through these obstacles. Peergen is a project to translate these learnings into open source and social enterprise.

Peergen:
    <ul>
    <li> develops personal datastores for healthdata, including genomic data </li>
    <li> develops privacy-maximising methods of cultivating both personal and population prevention, resilience, health, and wellness, via a new method of *N-of-1 personal -omics at scale* </li>
    </ul>

### Peergen Method 1: A complete commitment to re-centering data on the participant via continual N-of-1 studies 

_Invert, always invert ('man muss immer umkehren')._  
- Carl Jacobi, 19th. c. mathematician

Given this partial characterisation (1) of large-scale genomics visualisation and analysis: 

1. Bottom-up -omic data science & visualisation stack 
    - population- centric
    - using e.g. IGV, GATK, Hail, Python, Anaconda, scikit-learn, Tensorflow, Keras, Apache Spark, Kubernetes
    - producing systematic reviews, RCTs
    - starting genome-first from an associated locus  
    - seeking networked, ML-enhanced predictions from genotype to phenotype, to render descriptive data predictable about functions

Consider its inversion (2):

2. Top-down post-genomic data science & visualisation stack
    - participant-centric  
    - using distributed databases, Linked Data (LD), and machine-learning (ML) 
    - producing N-of-1 studies
    - starting phenotype-first, from any other layer 
    - seeking to explore the *terra incognita* of top-down causal links unique to the person, and connect these to bottom-up functional links

The core solution to multi-omic data science at scale implemented here is to differentiate *two* ML stacks, corresponding to (1) & (2) above, running over the same data. 

The same data that research organises into RCTs and systematic reviews in (1), is organised into N-of-1 studies in (2). The ML stack (2) generates a systematically 'inverted' N-of-1 health research practise, and explores linking it to the current best-practises in large-scale health research in (1) above. 

Linked Data over personal data provides a continuously updating knowledge graph of phenotypic info, over personal omic data. This LD interface cumulatively affords participants to act as primary investigators of their genotype-to-phenotype spectrum. This way, the owner of -omic data is not only its core user, but develops progressive, emergent levels of causal insight over their development.  This deep ownership of personal data over time progressively deepens the interfaces over personal health data available for bottom-up research (1). The compounding of semantic links across personal genotype-to-phenotype databases reveals new levels of emergent structure, filling in terra-incognita.

\(1) above is already organised, in the practises of biomedical genetics, and only lacks the standardised Linked Data developed in Peergen.

The rapid development of -omics technologies, alongside advances in LD and ML, has now made it financially and technically feasible for each participant to be trained and equipped to perform single omics experiments as in (2), and to produce and improve multiple omics datasets over a lifetime. The tools here enable each participant to own and responsibly operate a large number of high-quality datasets; and to add to analysis gradually, continually, serendipitously, and en-passant, uncovering insights across many domains, biomedical and otherwise, resulting in reflexive loops of learning.

In linking (1) and (2) above via LD as implemented here, discovery of new levels and emergent forms of G2P causality is enabled at the N-of-1 locus. The N-of-1 locus becomes a personal read-write interface over a personal read-write genome, which in turn opens new vistas for research and translation.

![Denis Noble - Downward causation](images/causation1.jpg)

The software described above is in functional beta, ready for initial trials.

### Peergen Method 2: P2P Health Data Ownership via Distributed Database

While arguments for claiming and ownership of personal health and omic data began appearing regularly in public a decade ago, no solution has yet emerged. Here, drawing on the work of many teams of web- and semantic- scientists over the last decade, we present a working solution in which each user holds the keys to their genomic, -omic, and healthdata:

1. Personal samples and health data of participants are stored at biobanks and in insititutional databases, as planned and ethically permitted
2. A copy of the data is encrypted and stored via a distributed database, which is distributed across secured servers. The private key (PKI) is made sole property of the participant.
3. The participant can use their private key to authorise uses of their personal health data, via object capabilities.

This system is designed to fill a large gap in the sample data flow of PM and national genome projects. This gap is located between data authorisation flows, biobank-generated personal IDs, and research IDs. This gap is here filled by personal private keys to encrypted views over personal -omics and health data.

The chief innovation implemented here is new tooling committed to starting over after the EHR and its recent successor, the CHR (Combined Health Record). This new tooling is a distributed database, integrating semantic and ML classification *at the participant*, to enable personal multi-omic healthdata ownership. Each participant functions as a top-down semantic data hub: a natural data quality and ontological engineering agent over their data.

The need for decentralisation of personal health data is now acknowledged by a critical mass of authorities across critical domains and infrastructures. E.g: Eric Topol[]. I argued for a decentralised approach to the storage of personal data in the Digital Health Revolution project in 2014. At the time a valid counterargument was made that the technology for decentralisation was not ready. Thanks to breakthroughs by many teams in semantic web science occurring alongside breakthroughs in ML, no such counterargument can be made now. 

This implementation of medical data ownership places the data owner in the role of performing follow-up analyses on all their data and events. This approach seeks eventual comprehensivity along unlimited combinations of lines of research, with the owner able to provide follow-up across a lifetime. This approach should over time should lead to very rich models of genotype-to-phenotype causality. 

![Eric Topol](images/topol1.jpg)

The software described above is in functional beta, ready for initial trials.

### Peergen Method 3: ML-centric Visualisation Engine  
https://github.com/P2PSci/alethiometer

ML is now 'unreasonably effective' at classifying images. A rational redesign of interface focusing on combining user and ML views is an obvious next step in data visualisation and exploration.

Here we present a novel integration of Circos with ML, into a genotype-to-phenotype visualisation engine, based on the Circos genome visualisation library. Circos plots here extend from omics views, to personal health & wellness categories (already coded and working separately). Linked Data allows the circos plot to 'zoom' or scale 'up' across -omes, and 'down; across personal healthdata.

[Kardiokompassi](https://kardiokompassi.fi) uses the metaphor of the compass. Alethiometer takes the next step, and uses the circular compass itself as a UI for ML over personal healthdata visualised using Circos. Circos is powerful, e.g. able to visualize linkages and genetic maps between pairs of genes, but needs abstraction layers over its complexity, which are developed within Peergen. 

Circos here has an added compelling data-entry interface, which shifts it from a tool for reading bottom-up data, to a tool for writing top-down data.

![Zooming-out from tables ..](images/pheno1.gif)


![to Circos plots ...](images/circos1.png)


![... to hGraphs](images/hgraph1.gif)

The software described above is in semi-functional alpha, not yet ready for initial trials. The functions described are all working, but still need to be functionally integrated.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a> <br />

