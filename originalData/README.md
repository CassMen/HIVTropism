[English](#dataset-description)

[Português](#descrição-dos-dados)

---


# Dataset description

*hiv1-subtype-c-tropism*

Subtype C consensus used for V3-loop (extracted from Los Alamos): CTRPNNNTRKSIRIGPGQTFYATGDIIGDIRQAHC

For genotypic tests, all 'X4' results were coded as 'NR5'.

Variables:
- **id**: Case id extracted from the Los Alamos database.
- **dna**: Virus V3-loop DNA strand. 
- **aa**: Virus V3-loop aminoacid strand (NCBI codon translation) aligned with consensus. Gaps are represented by 'X'.
- **aa-consenso**: Virus V3-loop aminoacid strand (NCBI codon translation) aligned with consensus. Gaps were replaced by consensus aminoacid.
- **desfecho-real**: Los Alamos tropism result.
- **desfecho-reduzido**: Los Alamos tropism result aggregated, with R5 as 'R5' and X4 and R5X4 as 'NR5'.
- **web-pssm-c-sinsi**: Result from Web PSSM.
- **phenoseq-c**: Result from PhenoSeq.		
- **tcup2-c-020**: Result from T-CUP 2.0 with 0.20 cut-off.
- **g2p-020**: Result from Geno2Pheno with 0.20 cut-off.
- **g2p-010**: Result from Geno2Pheno with 0.10 cut-off.
- **automute-BDT**: Result from AUTO-MUTE Boosted Decision Tree.
- **automute-RF**: Result from AUTO-MUTE Random Forest.
- **automute-NN**: Result from AUTO-MUTE Neural Network.
- **automute-SVM**: Result from AUTO-MUTE Support Vector Machine.
- **raymond**: Result from Raymond's Rule.

---


# Descrição dos dados

*hiv1-subtype-c-tropism*

Consenso para o loop V3, subtipo C (extraído de Los Alamos): CTRPNNNTRKSIRIGPGQTFYATGDIIGDIRQAHC

Para os testes genotípicos, todos os resultados 'X4' foram codificados como 'NR5'.

Variáveis:
- **id**: Id do caso extraído do Los Alamos.
- **dna**: DNA viral do loop V3.
- **aa**: Aminoácidos do loop V3 (tradução por códons padrão NCBI) alinhados com o consenso. Gaps estão representados como 'X'.
- **aa-consenso**: Aminoácidos do loop V3 (tradução por códons padrão NCBI) alinhados com o consenso. Gaps receberam o aminoácido do consenso para a posição.
- **desfecho-real**: Tropismo obtido do Los Alamos.
- **desfecho-reduzido**: Tropismo do Los Alamos representado como 'R5' (para vírus R5) e 'NR5' (para vírus X4 e R5X4).
- **web-pssm-c-sinsi**: Resultado do Web PSSM.
- **phenoseq-c**: Resultado do PhenoSeq.
- **tcup2-c-020**: Resultado do T-CUP 2.0 com ponto de corte 0,20.
- **g2p-020**: Resultado do Geno2Pheno com ponto de corte 0,20.
- **g2p-010**: Resultado do Geno2Pheno com ponto de corte 0,10.
- **automute-BDT**: Resultado do AUTO-MUTE Boosted Decision Tree.
- **automute-RF**: Resultado do AUTO-MUTE Random Forest.
- **automute-NN**: Resultado do AUTO-MUTE Neural Network.
- **automute-SVM**: Resultado do AUTO-MUTE Support Vector Machine.
- **raymond**: Resultado da Regra de Raymond.


