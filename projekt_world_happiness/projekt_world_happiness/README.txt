PROJEKT: Predikcija sreće pojedinih zemalja (World Happiness Report)
Kolegij: Uvod u podatkovnu znanost — Tim 13
===================================================================

SADRŽAJ PAKETA
  analiza_world_happiness.ipynb   <- glavni kod (Jupyter bilježnica)
  data/                           <- podaci (2015.csv ... 2019.csv)
  README.txt                      <- ove upute

VAŽNO: bilježnica i mapa "data" moraju ostati zajedno (bilježnica čita
podatke iz podmape "data"). Ne premještaj ih odvojeno.

-------------------------------------------------------------------
KAKO POKRENUTI — NAJLAKŠI NAČIN (Anaconda + Jupyter)
-------------------------------------------------------------------
1) Instaliraj Anacondu (besplatno): https://www.anaconda.com/download
   Anaconda već sadrži Python, pandas, scikit-learn, matplotlib i Jupyter.
2) Otvori "Anaconda Navigator" pa pokreni "Jupyter Notebook"
   (ili u "Anaconda Prompt" upiši:  jupyter notebook ).
3) U pregledniku koji se otvori dođi do ove mape i otvori
   analiza_world_happiness.ipynb
4) Pokreni sve ćelije redom:  izbornik  Cell -> Run All
   (ili klikni na ćeliju i pritisni  Shift + Enter  za jednu po jednu).

-------------------------------------------------------------------
ALTERNATIVA — VS Code
-------------------------------------------------------------------
1) Instaliraj Python (https://www.python.org/downloads/) i VS Code.
2) U VS Code dodaj ekstenzije "Python" i "Jupyter".
3) Otvori ovu mapu, otvori .ipynb i klikni "Run All".

-------------------------------------------------------------------
AKO NEMAŠ ANACONDU (čisti Python) — instaliraj biblioteke ručno
-------------------------------------------------------------------
U terminalu / command prompt:
   pip install pandas numpy scikit-learn matplotlib notebook
Zatim:
   jupyter notebook

-------------------------------------------------------------------
NAPOMENE
-------------------------------------------------------------------
- random_state = 42 osigurava da su rezultati uvijek isti
  (i jednaki onima u projektnoj dokumentaciji).
- Izvor podataka: World Happiness Report, Kaggle
  https://www.kaggle.com/datasets/unsdsn/world-happiness
