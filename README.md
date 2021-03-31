# Literature topics
Literature ressource for relevant topics

## WIlsON

WIlsON is an interactive workbench for analysis and visualization of multi-omics data developed at the MPI in Mario Looso's group. It is primarily intended to empower screening platforms to offer access to pre-calculated HT screen results to the non-computational scientist. Facilitated by an open file format, WIlsON supports all types of omics screens, serves results via a web-based dashboard, and enables end users to perform analyses and generate publication-ready plots.

Paper: https://academic.oup.com/bioinformatics/article/35/6/1055/5078467

Docker: https://hub.docker.com/r/loosolab/wilson

## Nf-Core

The nf-core framework has been developed as a means for the development of collaborative, peer-reviewed, best-practice analysis pipelines. All nf-core pipelines are written in Nextflow and so inherit the ability to be executed on most computational infrastructures, as well as having native support for container technologies such as Docker and Singularity.

Paper: https://www.nature.com/articles/s41587-020-0439-x

Project homepage: https://nf-co.re/


## Mutect2

Calls somatic short mutations via local assembly of haplotypes. Short mutations include single nucleotide (SNA) and insertion and deletion (indel) alterations. The caller uses a Bayesian somatic genotyping model that differs from the original MuTect by Cibulskis et al., 2013 and uses the assembly-based machinery of HaplotypeCaller. Of note, Mutect2 v4.1.0.0 onwards enables joint analysis of multiple samples.

Paper: https://www.biorxiv.org/content/10.1101/861054v1

Project-Homepage as part of GATK: https://gatk.broadinstitute.org/hc/en-us/articles/360037593851-Mutect2


## An Atlas of Gene Regulatory Elements in Adult Mouse Cerebrum

The mammalian cerebrum performs high level sensory, motor control and cognitive functions through highly specialized cortical networks and subcortical nuclei. Recent surveys of mouse and human brains with single cell transcriptomics1–3 and high-throughput imaging technologies4,5 have uncovered hundreds of neuronal cell types and a variety of non-neuronal cell types distributed in different brain regions, but the cell-type-specific transcriptional regulatory programs responsible for the unique identity and function of each brain cell type have yet to be elucidated. Here, we probe the accessible chromatin in >800,000 individual nuclei from 45 regions spanning the adult mouse isocortex, olfactory bulb, hippocampus and cerebral nuclei, and use the resulting data to define 491,818 candidate cis regulatory DNA elements in 160 distinct sub-types. We link a significant fraction of them to putative target genes expressed in diverse cerebral cell types and uncover transcriptional regulators involved in a broad spectrum of molecular and cellular pathways in different neuronal and glial cell populations. Our results provide a foundation for comprehensive analysis of gene regulatory programs of the mammalian brain and assist in the interpretation of non-coding risk variants associated with various neurological disease and traits in humans. To facilitate the dissemination of information, we have set up a web portal (http://catlas.org/mousebrain).

Nice extension to the paper recently presented by Tobias mapping Drosophila larval regulatory elements.

Paper preprint: https://www.biorxiv.org/content/10.1101/2020.05.10.087585v1.full
