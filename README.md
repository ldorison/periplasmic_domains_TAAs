## this repository contains the files associated with the following article : Phylogenetically restricted atypical periplasmic domains in trimeric autotransporters bind peptidoglycan and are important for protein stability. 

### Supplementary file S1: list of TAAs found in the interpro database, with their associated sequence.  
<details>
  <summary>for more details about the columns:</summary>


- accession: the accession number in the UniProt Database 

- sequence: the sequence of the TAA

- Specie: species where it is found 

- prot_name: protein name

- start and end: start and end of the YadA anchor domain 

- full length: full length in residues of the protein 

- taxID: the corresponding NCBI taxonomic identifier

- diff: full length - end -> gives the size of the periplasmic domain 

- size nter: size of the extracellular fraction of the adhesin 

- size bbarrel: size of the YadA anchor domain (end - start) 

- beta_seq: beta barrel sequence 

- cter_seq: sequence of the periplasmic domain 

- long_beta_seq: beta barrel sequence + beginning of the passenger domain 

- full phylogeny associated to the taxID 

- espr: presence or not of an ESPR (detected by Interpro).

- prediction: information about the presence of the signal peptide, identified with signalP 6.0 in slow mode.
</details>

### Supplementary file S2: list of selected genomes.  
<details>
  <summary>for more details about the columns:</summary>


- assembly accession: NCBI assembly accession
  
- From / accession : Uniprot identifier of the adhesin used to select the genome
  
- To: other genome name
  
- biosample: corresponding NCBI biosample
  
- wgs: whole genome sequencing: true or false
  
- sequence: adhesin sequence
  
- Specie: species where it is found
  
- prot_name: protein name

- start and end: start and end of the YadA anchor domain 

- full length: full length in residues of the protein 

- taxID: the corresponding NCBI taxonomic identifier

- diff: full length - end -> gives the size of the periplasmic domain 

- size nter: size of the extracellular fraction of the adhesin 

- size bbarrel: size of the YadA anchor domain (end - start) 

- beta_seq: beta barrel sequence 

- cter_seq: sequence of the periplasmic domain 

- long_beta_seq: beta barrel sequence + beginning of the passenger domain

- the rest of the columns correspond to the additionnal genome informations provided by NCBI
</details>

### Supplementary file S3: CSV with the list of all neighbouring genes for the adhesins found in genomes.  
<details>
  <summary>for more details about the columns:</summary>


- next_to: which adhesin it is next to (Uniprot identifier)
  
- name: protein name
  
- locus_tag: genomic locus tag 
  
- position: relative position to the adhesin (0 being the adhesin itself) 
  
- from: genome file used 
  
- sequence: protein sequence 
  
- feature and qualifiers, additionnal info provided in the genome annotation 
  
- start end: localisation on the genome 
  
- Strand: strand orientation on the genome 

</details>


### Supplementary file S4: list of nodes from Silix.  

- the first column is the cluster number
  
- the second column is the protein locus tag (from file S3)

### Supplementary file S5: output of HMM search of all neighbours genes. 
- HMMER3 tabular output format 
