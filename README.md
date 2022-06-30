#  Medical Symptom Checker

## To do: 
- Optimize the data dictionary / mapping file currently provided so it contains ICD-10/11 codes
- Look at `UMLS Metathesaurus Browser` API/browser to expand on and auto-generated the list of conditions-mappings file // https://uts.nlm.nih.gov/uts/umls/home // currently waiting on lisence approval for hXXX.wXXXX AT stonybrook DOT EdU
- Other ideas for data sources/examples to include: 
    - https://github.com/leanderme/sytora 
        - it has its own proprietary dataset -> `disease-symptom.csv`: Manually created by hand. Freely available under CC 4.0. 
        - and also uses a columbia dataset (150 diseases from 2004 from NYP) -> `http://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html` --> published paper --> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2656103/
    - NHANES dataset - shows symptoms and conditions of those that have responded 
    - JAMA paper/nice approach outlined -> https://www.nature.com/articles/ncomms5212 // suplemental data provided: 
        - Supplementary Data 3: Term co-occurrences between symptoms and diseases measured by TF-IDF weighted values. This table includes 147,978 records of symptom and disease relationships. (TXT 7797 kb)
        - Supplementary Data 4: List of disease links in the disease network with both significant shared symptoms and shared genes/PPIs. In total there are 133,106 such connections between 1,596 distinct diseases. (TXT 7801 kb)
        - Supplementary Data 5 1,000 randomly selected PubMed bibliographic records used for manual evaluation. The records contain PubMed identifier, title, abstract, MeSH indexing, author list, journal and publication date, etc. Each record was annotated by medical experts according to three criteria: (i) The symptom negation column indicates whether the extracted symptom-disease relationships contain negations (1/0 for yes/no) (ii) The column multiple diseases indicates whether the extracted multiple diseases in PubMed records have medical meaningful relationships (0) or not (1) (iii)The possible cofounders column indicates whether intermediate or otherwise cofounding factors were found in the extracted symptom-disease relationships, such as drug effects and drug side effects. (XLS 1625 kb)
        - Supplementary Data 6: This data file includes 33,977 records of the map from HPO phenotypes to UMLS semantic types (from UMLS 2012AA). (XLS 5014 kb)
        - Supplementary Data 7 SNOMED-CT symptom-disease relationships. The data file has six components: disease-symptom relationships, disease list, disease terms, symptom list, symptom terms and SNOMED semantic types. There are 2,340 records of disease-symptom relationships, which include 1,623 diseases and 817 symptoms. The SNOMED semantic type component lists the semantic types of concepts and their numbers in SNOMED. (XLS 636 kb)



## Information from orginal repo: 
### Description

This is FORK of: `DHILab Medical Symptom Checker` : The DHILab Medical Symptom Checker is designed to help you understand the possible causes of symptoms in children and adults.

### Live Demo

- Live demo on DHILab.com: https://dhilab.com/medical-symptom-checker-live/
- Live demo on GitHub.io: https://labinatorsolutions.github.io/medical-symptom-checker/

### Existing Data Sources

You can find the data sources of the symptoms and diseases at:

- **src/data/SymptomName.jsx**
- **src/data/DiseaseSymptoms.jsx**

### Build Instructions

1. Navigate to the **src/** directory using your terminal.
2. Run the following commands:

```
npm install
npm run build
```


