# Genomes

## Genome Data Overview

| Species | Group | File | Source | Project | PacBio HiFi Data | Hi-C Data | RNA Data | hifiasm | Hi-C scaffolding | RepeatMasking | Gene Annotation | Annotation Files | Comments | Edit Date |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| *Aglais urticae* | Butterfly | [GCA_905147175.2_ilAglUrti1.2_genomic.fna](#aglais-urticae-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_905147175.2/) | Museomics; Denmark | NA | NA | NA | NA | NA | NA | NA | genes.bed; gtf; integenic.bed | The annotation file has been downloaded from [DToL *Nymphalis urticae*](https://portal.darwintreeoflife.org/data/root/details/Nymphalis%20urticae). [Futher notes](#aglais-urticae-expanded-notes) | 16/01-2025 |
| *Apion fulvipes* | Beetle | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Apion virens* | Beetles | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Bathyphantes gracilis* | Spider | none | NA | PopGen; Genetic Load | Y | Y |  | N | N | N | N | none |  | 20/01-2025 |
| *Coenonympha arcania* | Butterfly | NA | NA | NA | NA | NA | NA | NA | NA | NA | NA | NA | /faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Coenonympha_arcania contains random assortment of annotation files; owner jilong | 16/01-2025 |
| *Coenonympha pamphilius* | Butterfly | none | NA | Museomics; Finland | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Coenonympha tullia* | Butterfly | [EG_CoeTul_15102024_genomic.fna](#coenonympha-tullia-genome-file) | EG; jepe | Museomics; Denmark | Y | Y | Y |  |  |  |  | gff3; genes.bed; intergenic.bed; repeats.bed | Annotation files are not named according to [convention](#genome-file-naming-convention); owner b960499 | 16/01-2025 |
| *Enchytraeus albidus* | Annelid | [EncAlb_19032024_genomic.fna](#enchytraeus-albidus-genome-file) | EG; jepe | Enchytraeus albidus | Y | N | Y | Y | N | Y | Y | genes.bed; gtf | The originally received data files are located here /faststorage/project/EcoGenetics/people/Jeppe_Bayer/enchytraeus_albidus/data; 8k_q20 purge-dupped thrice has been chosen as the best option for a reference genome. RNA files are just named 'Orme'. With the annotation files there is also 2 .fas files; owner b960499 | 20/01-2025 |
| *Enoplognatha ovata* | Spider | none | NA | PopGen | N | N | N | N | N | N | N | none |  | 20/01-2025 |
| *Entomobrya nicoleti* | Collembola | [EG_EntNic_05092024_genomic.fna](#entomobrya-nicoleti-genome-file) | EG; jepe | PopGen; Genetic Load | Y | Y | Y | Y | Y | Y | Y; BRAKER2 | bundle.bed; genes.bed; gtf; intergenic.bed; repeats.bed | Large number of BUSCO genes contained within debris; debris contatenated to single bundled super-scaffold. Insufficient RNA data for gene annotation instead gene annotation was done using the protein sequences of Orchesella cincta as reference; [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/) | 20/01-2025 |
| *Erigone atra* | Spider | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Eulampis jugularis* | Hummingbird | [D2212160079.fasta](#eulampis-jugularis-genome-file) |  | Hummingbird | N | N | N | NA | NA | NA | NA | none |  | 20/01-2025 |
| *Gonepteryx rhamni* | Butterfly | [EG_GonRha_22032024_genomic.fna](#gonepteryx-rhamni-genome-file) | EG; jepe | Museomics; Denmark | Y | Y | Y | Y | Y | Y | Y; BRAKER1 | genes.bed; gtf; intergenic.bed; repeats.bed | An index file Gonepteryx_rhamni/EG_GonRha_22032024_genomic.fna.fai and a neutral BED file EG_GonRha_22032024_genomic.neutral.bed have erroneously been added; owner anneaa. RNA data file have been named using the species Danish name 'citronsommerfugl', though it is misspelled as 'citronsommerfug', this naming is an inconsistency | 16/01-2025 |
| *Heliconia bihai* | Hummingbird | [H_bihai.fasta](#heliconia-bihai-genome-file) |  | Hummingbird | Y | N | N | NA | NA | NA | NA | none |  | 20/01-2025 |
| *Heliconia caribea* | Hummingbird | [H_caribea.fasta](#heliconia-caribea-genome-file) |  | Hummingbird | Y | N | N | NA | NA | NA | NA | none |  | 20/01-2025 |
| *Hipparchia semele* | Butterfly | [GCA_933228805.2_ilHipSeme1.2_genomic.fna](#hipparchia-semele-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_933228805.2/) | Museomics; Finland | NA | NA | NA | NA | NA | NA | NA | gbff |  | 17/01-2025 |
| *Isotoma viridis* | Collembola | [EG_IsoVir_23082024_genomic.fna](#isotoma-viridis-genome-file) | EG; jepe | PopGen; Genetic Load | Y | Y | Y | Y | Y | Y | Y; BRAKER3 | bundle.bed; genes.bed; gtf; intergenic.bed; repeats.bed | Large number of BUSCO genes contained within debris; debris contatenated to single bundled super-scaffold. Gene annotation was supplemented using the protein sequences of Orchesella cincta as reference; [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/) | 20/01-2025 |
| *Lepidocyrtus lanuginosus* | Collembola | none | NA | PopGen; Genetic Load | N | N | Y | N | N | N | N | none | Possible species confusion with Lepidocyrtus lignorum | 20/01-2025 |
| *Lepidocyrtus lignorum* | Collembola | [EG_LepLig_16022023_genomic_nomask_noann.fna](#lepidocyrtus-lignorum-genome-file) | EG; jepe | PopGen; Genetic Load | Y | N | N | Y | N | N | none |  | Possible species confusion with Lepidocyrtus lanuginosus | 20/01-2025 |
| *Lycaena hippothoe* | Butterfly | [GCA_964264095.1.fasta](#lycaena-hippothoe-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_964264095.1/) | Museomics; Finland | NA | NA | NA | NA | NA | NA | NA | none | There seems to be an alternative confirmed reference genome available <https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_964264015.1/> | 17/01-2025 |
| *Lycaena phlaeas* | Butterfly | [GCA_905333005.2_ilLycPhla1.2_genomic.fna](#lycaena-phlaeas-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_905333005.2/) | Museomics; Finland | NA | NA | NA | NA | NA | NA | NA | gbff |  | 17/01-2025 |
| *Lycaena virgaureae* | Butterfly | [EG_LycVir_01052024_genomic_haplotype1.fna](#lycaena-virgaureae-genome-file); [EG_LycVir_01052024_genomic_haplotype2.fna](#lycaena-virgaureae-genome-file) | EG; jepe | Museomics; Denmark | Y | Y | Y | Y | Y | Y | Y; BRAKER1 | genes.bed; gtf; intergenic.bed; repeats.bed | For this species both haplotype assemblies have been moved for; decision b960499. All annotation files are available for both assemblies | 17/01-2025 |
| *Maniola jurtina* | Butterfly | [GCF_905333055.1_ilManJurt1.1_genomic.fna](#maniola-jurtina-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_905333055.1/) | Museomics; Denmark | NA | NA | NA | NA | NA | NA | NA | gbff; genes.bed; gff; gtf; intergenic.bed |  | 17/01-2025 |
| *Microlinyphia pusilla* | Spider | none | NA | PopGen | N | N | Y | N | N | N | N | none |  | 20/01-2025 |
| *Neottiura bimaculata* | Spider | none | NA | PopGen; Genetic Load | N | Y | N | N | N | N | N | none |  | 20/01-2025 |
| *Oedothorac fuscus* | Spider | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Orchesella cincta* | Collembola | [GCA_001718145.1_ASM171814v1_genomic.fna](#orchesella-cincta-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/) | NA | NA | NA | NA | NA | NA | NA | NA | gbff; genes.bed; gff; gtf; intergenic.bed; neutral.bed | neutral.bed should not bed here; owner b960499 | 20/01-2025 |
| *Orchesella flavescens* | Collembola | [GCA_964034955.1_qeOrcFlav1.1_genomic.fna](#orchesella-flavescens-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_964034955.1/) | PopGen | NA | NA | NA | NA | NA | NA | NA | none | Don't know which specific project this is used for; owner b960499 | 20/01-2025 |
| *Orchesella villosa* | Collembola | [EG_OrcVil_23072024_genomic.fna](#orchesella-villosa-genome-file) | EG; jepe | PopGen; jepe | Y | Y | Y | Y | Y | Y | Y; BRAKER3 | genes.bed; gtf; intergenic.bed; neutral.bed; repeats.bed | Gene annotation was supplemented using the protein sequences of Orchesella cincta as reference; [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/). There shouldn't be a neutral.bed; owner anneaa | 20/01-2025 |
| *Pachygnatha degeeri* | Spider | none | NA | PopGen; Genetic Load | N | N | N | N | N | N | N | none |  | 20/01-2025 |
| *Parnassius mnemosyne* | Butterfly | [GCA_963668995.1_Parnassius_mnemosyne_n_2023_11_genomic.fna](#parnassius-mnemosyne-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_963668995.1/) | Museomics; Denmark | NA | NA | NA | NA | NA | NA | NA | genes.bed; gff; gtf; intergenic.bed |  | 17/01-2025 |
| *Pieris napi* | Butterfly | [GCF_905475465.1_ilPieNapi1.2_genomic.fna](#pieris-napi-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_905475465.1/) | Museomics; Denmark | NA | NA | NA | NA | NA | NA | NA | gbff; genes.bed; gff; gtf; intergenic.bed |  | 17/01-2025 |
| *Pisauria mirabilis* | Spider | none | NA | PopGen; Genetic Load | N | N | N | N | N | N | N | none |  | 20/01-2025 |
| *Pogonognathellus flavescens* | Collembola | [EG_PogFla_23072024_genomic.fna](#pogonognathellus-flavescens-genome-file) | EG; jepe | PopGen; Genetic Load | Y | Y | Y | Y | Y | Y | Y; BRAKER3 | genes.bed; gtf; intergenic.bed; neutral.bed; repeats.bed | Gene annotation was supplemented using the protein sequences of Orchesella cincta as reference; [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_001718145.1/). There shouldn't be a neutral.bed; owner anneaa | 20/01-2025 |
| *Sitona lineatus* | Beetle | [GCA_964263205.1.fasta](#sitona-lineatus-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_964263205.1/) | PopGen; Genetic Load | NA | NA | NA | NA | NA | NA | NA | none | Seems odd that there are currently no related annotation files; owner b960499 | 20/01-2025 |
| *Stegodyphus africanus* | Spider |  |  | Faster X | Y | Y | N | N | N | N | N | gff3 |  | 20/01-2025 |
| *Stenus fulviconis* | Beetle | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Stenus impressus* | Beetle | none | NA | PopGen; Genetic Load | N | N | N | N | N | N | N | none |  | 20/01-2025 |
| *Syntomus truncatellus* | Beetle | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Tachyporus hypnorum* | Beetle | none | NA | PopGen; Genetic Load | N | N | N | N | N | N | N | none |  | 20/01-2025 |
| *Tenuiphantes tenuis* | Spider | none | NA | PopGen; Genetic Load | Y | Y | Y | N | N | N | N | none |  | 20/01-2025 |
| *Thymelicus acteon* | Butterfly | [Thymelicus_acteon-GCA_951805285.1-softmasked.fa.gz](#thymelicus-acteon-genome-file) | [NCBI](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_951805285.1/) | Museomics; Denmark | NA | NA | NA | NA | NA | NA | NA | gtf | It's gene annotation has been used as a reference database for the annotation of *Thymelicus lineola*. Annotation folder also contains a protein sequence file | 17/01-2025 |
| *Thymelicus lineola* | Butterfly | [EG_ThyLin_01052024_genomic.fna](#thymelicus-lineola-genome-file) | EG; jepe | Museomics; Denmark | Y | Y | N | Y | Y | Y | Y | genes.bed; gtf; intergenic.bed; repeats.bed | Not sure whether current annotation has been made based on Thymelicus sylvetris or Thymelicus acteon protein sequences. PacBio Hifi data and Hi-C data is available from [DToL](https://portal.darwintreeoflife.org/data/root/details/Thymelicus%20lineola) | 17/01-2025 |
| *Trichosirocalus troglodytes* | Beetle | none | NA | PopGen | N | N | N | N | N | N | N | none |  | 20/01-2025 |

## Genome File Naming Convention

All genomes made within the EcoGenetics Centre should follow the same naming convention, eg.:

```txt
EG_[speciesCode]_[date]_genomic.fna
```

- `EG` denotes that the genomes has been created within the `E`co`G`enetics Centre.
- A 6 letter species code is made using the first 3 letters of the genus name combined with the first 3 letter of the species name, ex.:  
  *Entomobrya nicoleti* -> EntNic  
  Note that the first letter of both words is capitalised.
- The date is the date for the completion of the genome, written as: `ddmmyyyy`.
- `genomic` indicates that the file covers an entire genome and isn't a subsequence.

Arbitrary example:

```txt
EG_EntNic_22012024_genomic.fna
```

Annotation files also follow a convention. Genome annotation files (eg. GFF, GBFF, GTF) have the same file name as the genome but with the file extension matching the genome annotation format:

```txt
EG_[speciesCode]_[date]_genomic.gtf
```

BED files additionally indicate what type of genome region they specifiy:

- Gene coding regions: genes.bed
- Intergenic regions: intergenic.bed
- Repetitive regions: repeats.bed

Ex:

```txt
EG_[speciesCode]_[date]_genomic.intergenic.bed
```

## Genome Folder Structure

Folders containing reference genomes ideally all follow the same structure, which should be:

```txt
[species]/
	|__annotation/
	|		|__EG_[speciesCode]_[date]_genomic.genes.bed
	|		|__EG_[speciesCode]_[date]_genomic.gtf
	|		|__EG_[speciesCode]_[date]_genomic.intergenic.bed
	|		|__EG_[speciesCode]_[date]_genomic.repeats.bed
	|
	|___EG_[speciesCode]_[date]_genomic.fna
```

This means no index files as these can become outdated or you can drown in the sheer number of different indexing format files. All BED files serve single purposes and are broadly applicable. There are no BED files for regions which can be debatable such as 'neutral' regions as neutral regions can be defined by varying criteria

## Genome File Paths

### Aglais urticae genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Aglais_urticae/GCA_905147175.2_ilAglUrti1.2_genomic.fna
```

### Coenonympha tullia genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Coenonympha_tullia/EG_CoeTul_15102024_genomic.fna
```

### Enchytraeus albidus genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/Enchytraeus_albidus/reference_genome/Enchytraeus_albidus/EncAlb_19032024_genomic.fna
```

### Entomobrya nicoleti genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Entomobrya_nicoleti/EG_EntNic_05092024_genomic.fna
```

### Eulampis jugularis genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/heliconia_hummingbird/reference_genomes/Eulampis_jugularis/D2212160079.fasta
```

### Gonepteryx rhamni genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Gonepteryx_rhamni/EG_GonRha_22032024_genomic.fna
```

### Heliconia bihai genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/heliconia_hummingbird/reference_genomes/Heliconia_bihai/H_bihai.fasta
```

### Heliconia caribea genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/heliconia_hummingbird/reference_genomes/Heliconia_caribea/H_caribea.fasta
```

### Hipparchia semele genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Hipparchia_semele/GCA_933228805.2_ilHipSeme1.2_genomic.fna
```

### Isotoma viridis genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Isotoma_viridis/EG_IsoVir_23082024_genomic.fna
```

### Lepidocyrtus lignorum genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Lepidocyrtus_lignorum/EG_LepLig_16022023_genomic_nomask_noann.fna
```

### Lycaena hippothoe genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Lycaena_hippothoe/GCA_964264095.1.fasta
```

### Lycaena phlaeas genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Lycaena_phlaeas/GCA_905333005.2_ilLycPhla1.2_genomic.fna
```

### Lycaena virgaureae genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Lycaena_virgaureae/EG_LycVir_01052024_genomic_haplotype1.fna
```

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Lycaena_virgaureae/EG_LycVir_01052024_genomic_haplotype2.fna
```

### Maniola jurtina genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Maniola_jurtina/GCF_905333055.1_ilManJurt1.1_genomic.fna
```

### Orchesella cincta genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Orchesella_cincta/GCA_001718145.1_ASM171814v1_genomic.fna
```

### Orchesella flavescens genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Orchesella_flavescens/GCA_964034955.1_qeOrcFlav1.1_genomic.fna
```

### Orchesella villosa genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Orchesella_villosa/EG_OrcVil_23072024_genomic.fna
```

### Parnassius mnemosyne genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Parnassius_mnemosyne/GCA_963668995.1_Parnassius_mnemosyne_n_2023_11_genomic.fna
```

### Pieris napi genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Pieris_napi/GCF_905475465.1_ilPieNapi1.2_genomic.fna
```

### Pogonognathellus flavescens genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/collembola/Pogonognathellus_flavescens/EG_PogFla_23072024_genomic.fna
```

### Sitona lineatus genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/population_genetics/reference_genomes/beetles/Sitona_lineatus/GCA_964263205.1.fasta
```

### Thymelicus acteon genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Thymelicus_acteon/Thymelicus_acteon-GCA_951805285.1-softmasked.fa.gz
```

### Thymelicus lineola genome file

```sh
/faststorage/project/EcoGenetics/BACKUP/museomics/reference_genomes/Thymelicus_lineola/EG_ThyLin_01052024_genomic.fna
```

## Expanded Notes

### Aglais urticae Expanded Notes

The following awk script has been used to create 'GCA_905147175.2_ilAglUrti1.2_genomic.gtf' which is an altered version of 'Nymphalis_urticae-GCA_905147175.2-2022_03-genes.gtf' with the chromosome names altered to match those appearing in 'GCA_905147175.2_ilAglUrti1.2_genomic.fna'

```awk
awk \
	'BEGIN{
		FS = "\t"
		OFS = "\t"
	}
	{
		if ($0 ~ /^>/)
		{
			n = split($1, namearray, " ")
			chromname[namearray[n]]=substr(namearray[1], 2, length(namearray[1]))
		}
		if (FNR == NR)
		{
			next
		}
		if ($0 ~ /^#/)
		{
			print $0; next
		}
		$1 = chromname[$1]
		print $0
	}' \
	GCA_905147175.2_ilAglUrti1.2_genomic.fna \
	Nymphalis_urticae-GCA_905147175.2-2022_03-genes.gtf \
	> GCA_905147175.2_ilAglUrti1.2_genomic.gtf
```

Though this GTF annotation should be compatible with the FNA sequence file, do note that there is no annotation matching the chromosomes 'CAJHUP020000001.1' and 'CAJHUP020000002.1'.
