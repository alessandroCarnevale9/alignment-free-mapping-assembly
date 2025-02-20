# Metodi Efficienti per il Trattamento di Sequenze Genomiche: Un'Analisi di Kallisto, Minimap e Miniasm

## 📌 Descrizione
Questa repository contiene il materiale relativo alla tesi "Metodi Efficienti per il Trattamento di Sequenze Genomiche: Un'Analisi di Kallisto, Minimap e Miniasm". Lo studio analizza tre strumenti bioinformatici utilizzati per il trattamento di sequenze genomiche:

- **Kallisto**: un tool alignment-free per la quantificazione dell'espressione genica da dati RNA-seq.
- **Minimap**: un mapper di letture lunghe basato su minimizer per identificare regioni omologhe nel genoma.
- **Miniasm**: un assembler de novo ottimizzato per la velocità, che evita la fase di correzione degli errori.

## 🔗 Link ai tool esaminati e alla piattaforma Galaxy
- [Kallisto](https://github.com/pachterlab/kallisto)
- [Minimap](https://github.com/lh3/minimap2)
- [Miniasm](https://github.com/lh3/miniasm)
- [Galaxy](https://usegalaxy.org/)

## 🔬 Dataset
È possibile riprodurre i test effettuati scaricando i file ai seguenti link:
- **Kallisto**:
  - [short reads Escherichia coli](https://www.ebi.ac.uk/ena/browser/view/ERR2686027)
  - [trascritti di Escherichia coli](https://ftp.ensemblgenomes.ebi.ac.uk/pub/bacteria/release-60/fasta/bacteria_0_collection/escherichia_coli_str_k_12_substr_mg1655_gca_000005845/cdna/)
- **Minimap**:
  - [long reads Escherichia coli](https://ftp.sra.ebi.ac.uk/vol1/fastq/SRR320/083/SRR32026183/)
  - [genoma di riferimento di Escherichia coli](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000005845.2/)
- **Miniasm**:
  - [long reads PacBio](http://www.cbcb.umd.edu/software/PBcR/data/selfSampleData.tar.gz) 

## 📊 Risultati
- **Kallisto** dimostra un'alta efficienza computazionale rispetto ai metodi tradizionali di quantificazione dell'espressione genica.
- **Minimap** permette un rapido allineamento delle letture lunghe, con un consumo di memoria ridotto rispetto agli approcci tradizionali.
- **Miniasm** ha prodotto velocemente un assemblaggio preliminare, ma richiede strumenti aggiuntivi per la correzione degli errori.

Autore: **Alessandro Carnevale**  
Università degli Studi di Salerno  

---
