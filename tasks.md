# Tasks

**Contents**
- [Tasks](#tasks)
	- [Population Genomics](#population-genomics)
		- [Genome Assenbly and Annotation](#genome-assenbly-and-annotation)
			- [Collembola](#collembola)
				- [*Entomobrya nicoleti*](#entomobrya-nicoleti)
				- [*Isotoma viridis*](#isotoma-viridis)
				- [*Lepidocyrtus lignorum*](#lepidocyrtus-lignorum)
				- [*Orchesella villosa*](#orchesella-villosa)
				- [*Pogonognathellus flavescens*](#pogonognathellus-flavescens)
			- [Beetles](#beetles)
				- [*Apion fulvipes*0](#apion-fulvipes0)
				- [*Apion virens*](#apion-virens)
				- [*Stenus fulvicornis*](#stenus-fulvicornis)
				- [*Stenus impressus*](#stenus-impressus)
				- [*Syntomus truncatellus*](#syntomus-truncatellus)
				- [*Tachyporus hypnorum*](#tachyporus-hypnorum)
			- [Spiders](#spiders)
				- [*Bathyphantes gracilis*](#bathyphantes-gracilis)
				- [*Erigone atra*](#erigone-atra)
				- [*Neottiura bimaculata*](#neottiura-bimaculata)
				- [*Oedethorax fuscus*](#oedethorax-fuscus)
				- [*Pachygnatha degeeri*](#pachygnatha-degeeri)
				- [*Pisaura mirabilis*](#pisaura-mirabilis)
				- [*Tenuiphantes tenuis*](#tenuiphantes-tenuis)
		- [Alignment of Re-sequencing Data](#alignment-of-re-sequencing-data)
		- [Variant Call Files](#variant-call-files)
		- [Genetic Load Measures](#genetic-load-measures)
	- [Museomics](#museomics)
		- [Genome Assenbly and Annotation](#genome-assenbly-and-annotation-1)
			- [*Coenonympha tullia*](#coenonympha-tullia)
			- [*Gonepteryx rhamni*](#gonepteryx-rhamni)
			- [*Lycaena virgaureae*](#lycaena-virgaureae)
			- [*Thymelicus lineola*](#thymelicus-lineola)
	- [Faster X](#faster-x)
	- [*Enchytraeus albidus*](#enchytraeus-albidus)
		- [Genome Assenbly and Annotation](#genome-assenbly-and-annotation-2)
			- [*Enchytraeus albidus*](#enchytraeus-albidus-1)

## Population Genomics

### Genome Assenbly and Annotation

#### Collembola

##### *Entomobrya nicoleti*

- [x] Draft assembly
- [x] Hi-C scaffolding
- [x] Repeat masking
- [x] Gene annotation
  - BRAKER2
- [ ] Genome assembly statistics table
- [x] Genome placed in reference genome folder
- [x] GTF file
- [x] Gene coding region BED file
- [x] Intergenic region BED file
- [x] Repetitive region BED file
- [x] (Additional) Bundled debris super-scaffold BED file

[Genome assembly statistics](./assemblyStatistics/entomobryaNicoleti.md)

Protein reference sequences were obtained from *Orchesella cincta*, downloaded from [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/).
Initial run with BRAKER3, using both RNA data and protein reference sequences, indicated an insufficient amount of RNA hints for gene annotation.
Subsequently, the genome was annotated using only protein reference sequences.

##### *Isotoma viridis*

- [x] Draft assembly
- [x] Hi-C scaffolding
- [x] Repeat masking
- [x] Gene annotation
  - BRAKER3
- [ ] Genome assembly statistics table
- [x] Genome placed in reference genome folder
- [x] GTF file
- [x] Gene coding region BED file
- [x] Intergenic region BED file
- [x] Repetitive region BED file
- [x] (Additional) Bundled debris super-scaffold BED file

[Genome assembly statistics](./assemblyStatistics/isotomaViridis.md)

Protein reference sequences were obtained from *Orchesella cincta*, downloaded from [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/).
Gene annotation was supplemented using the protein sequences from *Orchesella cincta* as reference.

##### *Lepidocyrtus lignorum*

- [x] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

[Genome assembly statistics](./assemblyStatistics/lepidocyrtusLignorum.md)

##### *Orchesella villosa*

- [x] Draft assembly
- [x] Hi-C scaffolding
- [x] Repeat masking
- [x] Gene annotation
  - BRAKER3
- [ ] Genome assembly statistics table
- [x] Genome placed in reference genome folder
- [x] GTF file
- [x] Gene coding region BED file
- [x] Intergenic region BED file
- [x] Repetitive region BED file

[Genome assembly statistics](./assemblyStatistics/orchesellaVillosa.md)

Protein reference sequences were obtained from *Orchesella cincta*, downloaded from [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/).
Gene annotation was supplemented using the protein sequences from *Orchesella cincta* as reference.

##### *Pogonognathellus flavescens*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

#### Beetles

##### *Apion fulvipes*0

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Apion virens*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Stenus fulvicornis*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Stenus impressus*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Syntomus truncatellus*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Tachyporus hypnorum*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

#### Spiders

##### *Bathyphantes gracilis*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Erigone atra*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Neottiura bimaculata*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Oedethorax fuscus*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Pachygnatha degeeri*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Pisaura mirabilis*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

##### *Tenuiphantes tenuis*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

### Alignment of Re-sequencing Data

### Variant Call Files

### Genetic Load Measures

## Museomics

### Genome Assenbly and Annotation

#### *Coenonympha tullia*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

#### *Gonepteryx rhamni*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

#### *Lycaena virgaureae*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

#### *Thymelicus lineola*

- [ ] Draft assembly
- [ ] Hi-C scaffolding
- [ ] Repeat masking
- [ ] Gene annotation
- [ ] Genome assembly statistics table
- [ ] Genome placed in reference genome folder
- [ ] GTF file
- [ ] Gene coding region BED file
- [ ] Intergenic region BED file
- [ ] Repetitive region BED file

## Faster X

## *Enchytraeus albidus*

### Genome Assenbly and Annotation

#### *Enchytraeus albidus*