# Curs introductiv de vedere computerizata


## Sesiunea 1 Ce este vederea computerizată?
1. Introducere în vederea computerizată (CV)
2. Aplicațiile vederii computerizate
3. Istoria vederii computerizate
4. Bazele limbajului Python (tipuri de date, operatori, comenzi de control)
5. Librării pentru vedere computerizată: OpenCV, Seaborn/Matplotlib, PyTorch,
Tensorflow/Keras
6. Exemple practice: Deschiderea și afișarea imaginilor, procese fundamentale de
prelucrare. Exemplu de segmentare și detecția obiectelor.


## Sesiunea 2 Procesarea, îmbunătățirea și filtrarea imaginilor
1. Ce sunt imaginile? Cum sunt achiziționate imaginile?
2. Noțiuni fundamentale: nivel de expunere, nivel de amplificare, timp de expunere,
lungime focală, focus, câmp de vizualizare, proiecție 3D-2D
3. Tehnici de procesare: matrice Bayer, straturi, măști, histograme
4. Tehnici de îmbunătățire: funcții elementare, funcții globale și locale, funcții nucleu,
filtre liniare, filtre non-liniare
5. Exemplu practic: Exemplu de procesare și îmbunătățire cu OpenCV, Kornia,
Torchvision


## Sesiunea 3 Segmentarea imaginilor și detectarea obiectelor
1. Prag de delimitare, segmentare pe regiuni sau margini
2. Detecția obiectelor, recunoașterea și urmărirea obiectelor
3. Histograma Gradienților Orientați (HOG)
4. Transformata Fourier și cascade Wavelet (Haar, Daubechies, Coiflet, Morlet, Meyer) 5. Exemplu practic: Detecție margini, cascade Haar, funcții nucleu (eșantionare, blur)


## Sesiunea 4 Extragerea și potrivirea caracteristicilor imaginilor
1. Transformarea caracteristicilor invariantă la scară (Scale invariant feature transform
SIFT)
2. Funcție robustă accelerată (Speeded up robust feature SURF)
3. Histograma locației și orientării gradienților (GLOH), Histograma locală bazată pe
energie (LESH)
4. Exemplu practic: Detecție de colțuri, exemplu SIFT pentru detecție de puncte cheie,
exemplu SURF


## Sesiunea 5 Introducere în rețele neuronale artificiale
1. Introducere: Perceptron/Neuron, funcții de activare, straturi și structuri
2. Straturi conectate complet, perceptron multi-strat și aproximatori de funcții
generale.
3. Rețele cu propagare înainte, propagarea înainte a semnalului.
4. Propagarea înapoi a erorii și reducerea gradientului. Diferențiabilitate. Bucla de
învățare-validare, epocă.
5. Introducere în librăria de rețele neuronale: PyTorch sau Tensorflow/Keras (preferabil
PyTorch)
6. Tensori, eșantioane lot, reducerea stohastică a gradientului.
7. Metrici specifice evaluării problemelor de clasificare
8. Exemplu practic: Implementarea unul perceptron multi-strat (MLP),
învățare/antrenare și evaluarea rețelei. Introducere Pytorch-Lightning.


## Sesiunea 6 Rețele neuronale convoluționale
1. Introducere în rețele convoluționale: Avantaje, funcționare, straturi necesare 2. Operații de convoluție, sub-eșantionare, supra-eșantionare; Concepte, intuiții,
implementări (PyTorch, Tensorflow/Keras)
3. Învățarea rețelelor convoluționale: procesarea datelor și augmentări, regularizare 4. Estimarea învățării: supra adaptare, sub adaptare, generalizare
5. Structuri micro și macro. Piramide de caracteristici
6. Istoria rețelelor convoluționale: Cognitron (1988), LeNet, AlexNet (2012), VGG,
ResNet
7. Rețele convoluționale moderne: FocalNet și ConvNext v1 și v2
8. Exemplu practic: Vizualizare comparativă a caracteristicilor piramidale între rețele
pre-antrenate mai vechi VGG/ResNet și mai recente FocalNet/ConvNext v2 (folosind librăria Timm)


## Sesiunea 7 Rețele auto-codificatoare (AutoEncoders) și rețele generativ-adversare (GANs) 
1. Modele deterministe și generative.
2. Auto-codificatoare, structuri codificator-decodificator (U-Net, HRNet, ConvNextv2,
etc)
3. Atac adversar.
4. Rețele Generativ-Adversare (GANs)
5. Auto-codificatoare variaționale (VAEs)
6. Difuzie stabilă, difuzie rece.
7. Funcții cost specifice învățării modelelor generative: Divergență Kulback-Leibler,
distanță Wasserstein, Perceptual Loss etc
8. Metrici specifice evaluarii calității imaginilor: L1,L2, PSNR, SSIM/MS-SSIM, etc


## Sesiunea 8 Rețele transformatoare, mecanismul de auto atenție, rețele vedere și limbaj
1. Google Transformer (Vaswani, 2017). Explicarea transformatorului standard cu
articolul științific prin care a fost introdus (Attention is all you need
https://paperswithcode.com/paper/attention-is-all-you-need).
2. Mecanismul de auto-atenție. Alte tipuri de atenție (local/global, încrucișată,
internă/externă, etc)
3. Transformatoare pentru vedere (ViT) și derivate MLP, spectrale.
4. Exemple practice: Transformator pentru vedere (ViT), rețele hibride pentru vedere
(LeVit)


## Sesiunea 9 Detectarea obiectelor cu rețele neuronale
1. Structura generală a detectoarelor de obiecte neuronale: corp, capete. Detectoare
cu 1 stagiu (SSD) și 2 stagii. Principii de funcționare: piramide de caracteristici etc.
2. Detectoare de obiecte pe bază de rețele convoluționale (R-CNN, Faster R-CNN, YOLO,
etc)
3. Detectoare de obiecte pe bază de rețele transformatoare (Swin, FocalNet, etc)
4. Detectoare de obiecte pe bază de rețele hibride (DETR și derivate)
5. Metrici specifice detectării obiectelor.
6. Exemplu practic: Exemple cu detectoare de obiecte (pre-antrenate)


## Sesiunea 10 Segmentarea Semantică
1. Ce este segmentarea semantică? Concepte, metrici și definiții
2. Rețele complet convoluționale
3. Studiu de caz: Arhitectura U-Net și derivatele sale (Attention U-Net, U-Net++, Swin
U-Net, TransU-Net).
4. Arhitectura HR-Net
5. Exemplu practic: Segmentare semantică cu rețele complet convoluționale (U-Net)


## Sesiunea 11 Segmentarea Instanțelor
1. Ce este segmentarea instanțelor? Concepte și definiții
2. Mask R-CNN
3. Mask DINO (https://paperswithcode.com/paper/mask-dino-towards-a-unified-
transformer-based-1 )
4. Segmentare modernă Segment Anything (SAM), Recognize Anything (RAM)
5. Exemple practice: Exemple de segmentare folosind rețeaua Segment Anything (SAM)


6. 
