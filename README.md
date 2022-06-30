#  Medical Symptom Checker

## To do: 
- Optimize the data dictionary / mapping file currently provided so it contains ICD-10/11 codes
- Look at `UMLS Metathesaurus Browser` API/browser to expand on and auto-generated the list of conditions-mappings file // https://uts.nlm.nih.gov/uts/umls/home // currently waiting on lisence approval for hXXX.wXXXX AT stonybrook DOT EdU
- Other ideas for data sources/examples to include: 
    - https://github.com/leanderme/sytora 
        - it has its own proprietary dataset -> `disease-symptom.csv`: Manually created by hand. Freely available under CC 4.0. 
        - and also uses a columbia dataset (150 diseases from 2004 from NYP) -> `http://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html` --> published paper --> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2656103/
    - NHANES dataset - shows symptoms and conditions of those that have responded 



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


