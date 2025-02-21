# Proiect-PS

📊 Aplicație Shiny pentru Distribuții de Variabile Aleatoare și Funcții Personalizate
🔹 Descriere
Această aplicație interactivă, dezvoltată în R Shiny, permite explorarea distribuțiilor de probabilitate și a unor funcții personalizate prin vizualizări dinamice și interacțiune directă cu utilizatorul. Proiectul integrează concepte fundamentale de statistică și probabilități, oferind o platformă educațională unde utilizatorii pot simula distribuții, aplica transformări și analiza repartiții empirice.

🚀 Funcționalități
✅ Generarea și reprezentarea distribuțiilor: Normală, Exponențială, Poisson, Binomială
✅ Transformarea variabilelor aleatoare: Ex. 
3
−
2
𝑋
3−2X, 
𝑋
2
X 
2
 , 
∑
𝑋
∑X, 
∑
𝑋
2
∑X 
2
 
✅ Afișarea funcției de repartiție empirică (ECDF) pentru distribuții și transformări
✅ Implementarea și vizualizarea funcțiilor personalizate
✅ Interfață interactivă pentru ajustarea parametrilor și explorarea grafică

📌 Arhitectura Aplicației
Proiectul este structurat în două module principale:

📈 1. Distribuții variabile aleatoare
Generare de eșantioane din distribuțiile alese
Transformări aplicate variabilei aleatoare
Reprezentare grafică a funcției de repartiție empirică (ECDF)
🔢 2. Funcții personalizate
Vizualizarea unor funcții definite analitic
Ajustarea parametrilor și intervalelor de definiție
Posibilitatea de a compara diverse funcții
🛠️ Tehnologii Utilizate
R Shiny → pentru interfață reactivă
ggplot2 → pentru reprezentările grafice
dplyr & tidyr → pentru manipularea datelor
📌 Cum rulezi aplicația?
1️⃣ Clonează repository-ul:

bash
Copy
Edit
git clone https://github.com/Aleexaandraa10/proiect-ps.git
2️⃣ Deschide RStudio și încarcă fișierul App.R
3️⃣ Rulează aplicația cu:

r
Copy
Edit
shiny::runApp()
📈 Posibile Îmbunătățiri
🔹 Compararea ECDF-ului cu CDF-ul teoretic
🔹 Calculul automat al mediei și varianței pentru eșantioane
🔹 Implementarea unui buton de export pentru rezultate

📜 Concluzie
Această aplicație îmbină vizualizarea interactivă cu statistica teoretică, oferind un instrument educațional pentru explorarea distribuțiilor de probabilitate și transformarea variabilelor aleatoare. Prin interfața Shiny, utilizatorii pot ajusta parametrii în timp real și observa impactul acestora asupra datelor generate.
