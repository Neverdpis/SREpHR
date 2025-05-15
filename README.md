# Systém rozpoznávania emócii pre humanoidného robota NICO  
Tento projekt sa zameriava na automatickú klasifikáciu emócií z obrázkov ľudskej tváre pomocou hlbokého učenia.  
Model je postavený na ResNet-50 architektúre predtrénovanej na ImageNetV1 a je ďalej fine-tunovaný na datasete AffectNet.  
  
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
Research GAN modelov pre augmentáciu datasetu Affectnet - WORK IN PROGRESS  
Augmentácia datasetu s pomocou GANmut - WORK IN PROGRESS  
Zvýšenie presnosti modelu - WORK IN PROGRESS  
Analýza feature vektorov pomocou SOM - TODO  
...  
Integrácia s robotom NICO - TODO  
  
Použité knižnice:  
PyTorch, torch, torchvision, scikit-learn, matplotlib, seaborn, pandas, numpy, tqdm  
  
