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

### Supplementary file S6: microscopy data for all cells used in figure 7. 
<details>
  <summary>for more details about the columns:</summary>
this CSV file contains all data for all cells used in microscopy analysis of figure 7. Each row contains the data of one cell. 
- First few columns indicate the strain, the biological replicate and the field of view used. 
  
- Area is the area (in phase contrast) of the bacterial cell in pixels,
- Circularity describes how round a cell is, with 1 being a perfect circle. Dividing cells tend to have a lower circularity
- columns named 1-100 are the strechted to 100 points and normalized value to the maxima (per cell) of fluorescence around the perimeter
- raw_fluo is the raw fluorescence value for each pixel in the perimeter in a continuous order.
- intersections indicate values corresponding to the two "poles" where the perimeter interacts with the cell long axis. 

</details>

### Supplementary file S7:  average microscopy values used in figure 7. 
<details>
  <summary>for more details about the columns:</summary>
this excel file contains all data for all cells used in microscopy analysis of figure 7. Each row contains the data of one field of view. 
- First few columns indicate the strain, the biological replicate and the field of view (image) used. 
- raw_fluo is the average raw fluorescence values for each image 
- ratio poles septum is the average value for each image calculated using the formula described in figure 7. 

</details>


  
