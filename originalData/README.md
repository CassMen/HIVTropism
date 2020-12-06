[English](#dataset-description)

[Português](#descrição-dos-dados)

---


# Dataset description

*hiv1-subtype-c-tropism*

Subtype C consensus used for V3-loop (extracted from Los Alamos): CTRPNNNTRKSIRIGPGQTFYATGDIIGDIRQAHC

For genotypic algorithms, all 'X4' results were coded as 'NR5'.

Variables:
- **accession**: Los Alamos sequence accession number.
- **country**: Los Alamos sequence country.
- **year**: Los Alamos sequence year of extraction.
- **coreceptor**: Los Alamos tropism result.
- **coreceptor-reduced**: Los Alamos tropism result aggregated, with R5 as 'R5' and X4 and R5X4 as 'NR5'.
- **dna**: Virus V3-loop DNA strand.
- **aa-sub-consensus**: Virus V3-loop aminoacid strand (NCBI codon translation) aligned with consensus. Gaps were replaced by consensus aminoacid.
- **geno2pheno-fpr**: Result from Geno2Pheno.
- **tcup**: Result from T-Cup 2.0.
- **hivcopred-svm-score**: Result from HIVcoPred.
- **automute-svm-pr5**: Result from AUTO-MUTE Support Vector Machine.
- **automute-rf-pr5**: Result from AUTO-MUTE Random Forest.
- **automute-nn-pr5**: Result from AUTO-MUTE Neural Network.
- **automute-bdt-pr5**: Result from AUTO-MUTE Boosted Decision Tree.
- **phenoseq**: Result from PhenoSeq.
- **web-pssm**: Result from Web PSSM.
- **rule-1125**: Result from 11/25 Rule.
- **rule-112425**: Result from 11/24/25 Rule.
- **net-charge-rule**: Result from Net Charge Rule.
- **raymonds-rule**: Result from Raymond's Rule. 

*hiv1-subtype-c-tropism-for-stacking*

Variables with the same name as in hiv1-subtype-c-tropism.csv mean the same.

Others:
- **g2p-5.75**: Result from Geno2Pheno with 5.75 cut-off.
- **g2p-10**: Result from Geno2Pheno with 10.0 cut-off.
- **tcup-0.5**: Result from T-Cup 2.0 with 0.5 cut-off.
- **hivcopred-0.3**: Result from HIVcoPred with 0.3 cut-off.
- **automute-svm-0.5**: Result from AUTO-MUTE Support Vector Machine with 0.5 cut-off.
- **automute-rf-0.5**: Result from AUTO-MUTE Random Forest with 0.5 cut-off.
- **automute-nn-0.5**: Result from AUTO-MUTE Neural Network with 0.5 cut-off.
- **automute-bdt-0.5**: Result from AUTO-MUTE Boosted Decision Tree with 0.5 cut-off.


---


# Descrição dos dados

*hiv1-subtype-c-tropism*

Consenso para o loop V3, subtipo C (extraído de Los Alamos): CTRPNNNTRKSIRIGPGQTFYATGDIIGDIRQAHC

Para os algoritmos genotípicos, todos os resultados 'X4' foram codificados como 'NR5'.

Variáveis:
- **accession**: Código da sequência, extraído de Los Alamos.
- **country**: País da sequência, extraído de Los Alamos.
- **year**: Ano da sequência, extraído de Los Alamos.
- **coreceptor**: Tropismo obtido de Los Alamos.
- **coreceptor-reduced**: Tropismo de Los Alamos representado como 'R5' (para vírus R5) e 'NR5' (para vírus X4 e R5X4).
- **dna**: DNA viral do loop V3.
- **aa-sub-consensus**: Aminoácidos do loop V3 (tradução por códons padrão NCBI) alinhados com o consenso. Gaps receberam o aminoácido do consenso para a posição.
- **geno2pheno-fpr**: Resultado do Geno2Pheno.
- **tcup**: Resultado do T-Cup 2.0.
- **hivcopred-svm-score**: Resultado do HIVcoPred.
- **automute-svm-pr5**: Resultado do AUTO-MUTE Support Vector Machine.
- **automute-rf-pr5**: Resultado do AUTO-MUTE Random Forest.
- **automute-nn-pr5**: Resultado do AUTO-MUTE Neural Network.
- **automute-bdt-pr5**: Resultado do AUTO-MUTE Boosted Decision Tree.
- **phenoseq**: Resultado do PhenoSeq.
- **web-pssm**: Resultado do Web PSSM.
- **rule-1125**: Resultado da Regra 11/25.
- **rule-112425**: Resultado da Regra 11/24/25.
- **net-charge-rule**: Resultado da Regra da Carga Total.
- **raymonds-rule**: Resultado da Regra de Raymond. 

*hiv1-subtype-c-tropism-for-stacking*

Variáveis com o mesmo nome em hiv1-subtype-c-tropism.csv têm o mesmo significado.

Outras:
- **g2p-5.75**: Resultado do Geno2Pheno com ponto de corte 5,75.
- **g2p-10**: Resultado do Geno2Pheno com ponto de corte 10,0.
- **tcup-0.5**: Resultado do T-Cup 2.0 com ponto de corte 0,5.
- **hivcopred-0.3**: Resultado do HIVcoPred com ponto de corte 0,3.
- **automute-svm-0.5**: Resultado do AUTO-MUTE Support Vector Machine com ponto de corte 0,5.
- **automute-rf-0.5**: Resultado do AUTO-MUTE Random Forest with 0.5 com ponto de corte 0,5.
- **automute-nn-0.5**: Resultado do AUTO-MUTE Neural Network with 0.5 com ponto de corte 0,5.
- **automute-bdt-0.5**: Resultado do AUTO-MUTE Boosted Decision Tree com ponto de corte 0,5.


