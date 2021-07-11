# IM-ML
A machine learning workflow to predict I-Modulons( top-down regulons derived from the ICA result of RNAseq) with DNA sequence features.<br>
<br>
1. Generate SigmaFactor PSSMs<br>
2. Feature Matrix Generation<br>
3. Feature Engineering<br>
4. Machine learing: model training and hyperparameter optimization<br>
5. ArcA Direct Repeats motifs to improve model performance<br>

The workflow depends on:<br>
        1. bitome: https://github.com/SBRG/bitome<br>
        2. pymodulon: https://github.com/SBRG/pymodulon<br>
        3. DNAshapeR:https://github.com/TsuPeiChiu/DNAshapeR<br>