# Momentum Data Rheumatoid Arthritis and Venous Thromboembolism codelists
Codelists from Momentum Data, utilised for the study titled: *"Exploring temporal trends in the incidence and prevalence of rheumatoid arthritis and VTE risk factors in women with rheumatoid arthritis in England"*

## Quality control 
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

### Rhuematoid arthritis
1. Any individual with a [rheumatoid arthritis diagnosis code](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Rheumatoid%20Arthritis).
2. No diagnosis code for [ankylosing spondylitis](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Ankylosing%20Spondylitis) **OR** [psoriatic arthritis](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Psoriatic%20Arthritis).

### Pulmonary embolism
- Any individual with a code for [pulmonary embolism](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Pulmonary%20Embolism).

### Deep vein thrombosis
- Any individual with a code for [deep vein thrombosis](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Deep%20Vein%20Thrombosis).

### Venous thromboembolism
- Any individual with a code for [pulmonary embolism](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Pulmonary%20Embolism) **AND/OR** [deep vein thrombosis](https://github.com/MomentumData/Rheumatoid-Arthritis-and-VTE-Codelists/tree/e8e40909d595c81c0a33041f3f19f5a5bfd5cc9f/Deep%20Vein%20Thrombosis).
