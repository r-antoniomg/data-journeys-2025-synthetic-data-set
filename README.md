# README
This README file is based on the template created by Anneliese Eber, University of Waterloo Library, and licensed under CC-BY 4.0 (https://creativecommons.org/licenses/by/4.0/).

---
This README file was generated on 2025-10-21 by R. Antonio Muñoz Gómez
---
## 1.0 GENERAL INFORMATION 

1.1 Title of dataset: Synthetic co-op salaries data

1.2. Author information: R. Antonio Muñoz Gómez; Anneliese Eber

1.2.1 Author/Principal Investigator Information  
 Name: R. Antonio Muñoz Gómez  
 Institution: University of Waterloo  
 Unit: Libraries  
 Email: ra2munoz@uwaterloo.ca  
 ORCID ID: https://orcid.org/0009-0009-0319-035X  

1.2.2. Author/Principal Investigator Information  
 Name: Anneliese Eber  
 Institution: University of Waterloo  
 Unit: Libraries  
 Email: aeber@uwaterloo.ca  
 ORCID ID: https://orcid.org/0009-0000-8922-8877

1.4 Data collection date(s): 2025-10-10 

## 2.0 DATA AND FILE OVERVIEW

2.1 Software Used: GPT-5 on Microsoft Copilot (University of Waterloo instance)

2.2 File Naming Convention:
- `synthetic-co-op-salaries-data-v.[#.#].csv` : Where #.# indicates the version number, with decimal increments for minor changes and integer increments for major changes
- `synthetic-co-op-salaries-data-prompts.txt`

2.3 Organization of Files and Folders: All files are kept in a flat structure with no directories or sub-directories   

## 3.0 ACCESS, USAGE, SHARING, AND INTELLECTUAL PROPERTY INFORMATION 

3.1 Data licenses and restrictions:
CC-BY 4.0 (https://creativecommons.org/licenses/by/4.0/) 

3.2 Related publications, outputs, and datasets:
The data set was created for instructional purposes as part of the 2025 Data Journeys workshop series at the University of Waterloo. Materials from Data Journeys workshops are available from: (https://osf.io/z8mbc/files)

3.3 Ancillary datasets: This synthetic data set was inspired by the Salaries + Blacklist spreadsheet (https://docs.google.com/spreadsheets/d/1OEDRTAalRsyD1iAO5fkp_8HUJUxbYTavotHhwX0AwBU/edit?usp=sharing) published on Reddit's WaterlooWorks Megathread (Fall 2025) (https://www.reddit.com/r/uwaterloo/comments/1klrdth/waterlooworks_megathread_fall_2025/)

## 4.0 METHODOLOGY  

4.1 Methods for collecting/creating data:
- This data set was created using GPT-5 on Microsoft Copilot (University of Waterloo instance)
- The prompts aimed to replicate the patterns of the text strings found in each column
- No attempt was made to accurately replicate the distribution of values
- The list of prompts is available as synthetic-co-op-salaries-data-prompts.txt

## 5.0 DATA-SPECIFIC INFORMATION 

5.1 Variable list:

- `Company / Role` : text string. fictional company name
- `Salary Information (CAD unless otherwise specified)` : text string. salary amount
- `Benefits` : text string. additional monetary or in-kind benefits
- `Year` : numeric. year for which the data is being reported
- `Position` : text string. the position for which the co-op student was hired

NOTE: Cells in the data set may contain extraneous data following similar patterns to the original Salaries + Blacklist spreadsheet data set

## 6.0 Artificial Intelligence Disclosure [(AID) Statement](https://doi.org/10.48550/arXiv.2408.01904)

_Artificial Intelligence Tool_: GPT-5 on Copilot (University of Waterloo institutional instance); _Execution_: The data set was created artificially using prompts available in the `synthetic-co-op-salaries-data-prompts.txt` file.
