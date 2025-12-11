# Systém rozpoznávania emócii pre humanoidného robota NICO  
Tento projekt sa zameriava na automatickú klasifikáciu emócií z obrázkov ľudskej tváre pomocou hlbokého učenia.  
Model je postavený na ResNet-50 architektúre predtrénovanej na ImageNetV1 a je ďalej fine-tunovaný na datasete AffectNet.  

Plan checkpoints

2025

28.10. - Read 3 scientific papers for PS2, Write 4 pages of DP

S 4.11. - Get Unreal engine basic samples generation working - First deadline, Write 4 pages of DP

11.11. - Get Unreal engine basic samples generation working - Second deadline, Have dataset with generated samples we can do experiments on - First deadline, Write 4 pages of DP

S 18.11. - Have dataset with generated samples we can do experiments on - Second deadline, Write 4 pages of DP

25.11. - Model trained on dataset with generated samples - First deadline, Write 4 pages of DP

S 2.12. - Have dataset with samples from GAN - First deadline, Write 4 pages of DP, MAŤ 15 Strán na PS2 napísaných + prezentácia + atď - First deadline, TREBA POSLAŤ MAIN OD ŠKOLITEĽKY ŽE JE TO OK !

9.12. - Have dataset with samples from GAN - Second deadline, Model trained on dataset from GAN - First deadline, Write 4 pages of DP, MAŤ 15 Strán na PS2 napísaných + prezentácia + atď - Second deadline, TREBA POSLAŤ MAIN OD ŠKOLITEĽKY ŽE JE TO OK !

12.12. - PROJEKTOVY SEMINAR 2 - 15 Strán DP napísaných + Ďalšie ==> VIĎ STRÁNKA PREDMETU

16.12. - Model trained on dataset from GAN - Second deadline, Experiments with Unreal and GAN, Write 4 pages of DP

23.12. - Experiments with Unreal and GAN - DONE - First deadline, Write 4 pages of DP

30.12. - its beginning to look a lot like christmas

2026

6.1. - Experiments with Unreal and GAN - DONE - Second deadline, Write 4 pages of DP

13.1. - Refine Unreal + GAN - First deadline, Write 3 pages of DP

20.1. - Experiments 2 - First deadline, Write 3 pages of DP

27.1. - Refine Unreal + GAN - Second deadline, Write 3 pages of DP

3.2. - Concept analysis - First deadline, Write 3 pages of DP

10.2. - Experiments 2 - Second deadline, Write 3 pages of DP

17.2. - Concept analysis - Second deadline, Write 3 pages of DP

24.2. - Miscellaneous work on DP, Write 3 pages of DP

3.3. - , Have DP generally written - FIRST DEADLINE

10.3.- Miscellaneous work on DP

17.3. - , Have DP generally written - SECOND DEADLINE

24.3. - Miscellaneous work on DP

31.3. - Model on ROBOT experiments - First deadline, 

7.4. - Model on ROBOT experiments - Second deadline,

14.4. - , Have DP done - FIRST DEADLINE

21.4.- Miscellaneous work on DP

28.4. - , Have DP done - SECOND DEADLINE

5.5. - You should be done by now

7.5. ODOVZDANIE FINALNE DONE

  
Cieľe práce:  
-Preskúmať modely pre rozpoznávanie emócií z výrazu tváre  
-Využiť dataset AffectNet a analyzovať jeho slabé stránky  
-Zlepšiť klasifikáciu podreprezentovaných triedy pomocou augmentácie dát  
-Analyzovať a vizualizovať vnútorné reprezentácie modelu  
-Vytvorenie a kalibrácia systému pre robota NICO  
  
Kalendár:  
Reimplementácia pôvondého projektu z TensorFlow a Keras do Pytorch - DONE  
Natrénovanie Pytorch modelu a porovnanie presnosti s predošlou keras implementáciou - DONE  
Analýza feature vektorov - DONE (pokračovať ďalej s pokročilejšími metódami)  
Research GAN modelov pre augmentáciu datasetu Affectnet - DONE
Augmentácia datasetu s pomocou GANmut - WORK IN PROGRESS  
Zvýšenie presnosti modelu - WORK IN PROGRESS  
Analýza feature vektorov pomocou SOM - DONE

Integrácia s robotom NICO - TODO  
  
Použité knižnice:  
PyTorch, torch, torchvision, scikit-learn, matplotlib, seaborn, pandas, numpy, tqdm  

Použité prostredie:
Google Colab
  
