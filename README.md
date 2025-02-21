# Aplicație Shiny pentru Distribuții de Variabile Aleatoare și Funcții Personalizate  

## 🔹 Descriere  
Această aplicație interactivă, dezvoltată în **R Shiny**, permite explorarea distribuțiilor de probabilitate și a unor funcții personalizate prin vizualizări dinamice și interacțiune directă cu utilizatorul.  
Proiectul integrează concepte fundamentale de **statistică și probabilități**, oferind o platformă educațională unde utilizatorii pot **simula distribuții, aplica transformări și analiza repartiții empirice**.  

---

## 🚀 Funcționalități  
- **Generarea și reprezentarea distribuțiilor**: Normală, Exponențială, Poisson, Binomială  
- **Transformarea variabilelor aleatoare**: Ex. `3 - 2X`, `X²`, `∑X`, `∑X²`  
- **Afișarea funcției de repartiție empirică (ECDF)** pentru distribuții și transformări  
- **Implementarea și vizualizarea funcțiilor personalizate**  
- **Interfață interactivă** pentru ajustarea parametrilor și explorarea grafică  

---

## 📌 Arhitectura Aplicației  
Proiectul este structurat în două module principale:  

###  1. **Distribuții variabile aleatoare**  
- Generare de eșantioane din distribuțiile alese  
- Transformări aplicate variabilei aleatoare  
- Reprezentare grafică a **funcției de repartiție empirică (ECDF)**  

###  2. **Funcții personalizate**  
- Vizualizarea unor funcții definite analitic  
- Ajustarea parametrilor și intervalelor de definiție  
- Posibilitatea de a compara diverse funcții  

---

## 🛠️ **Tehnologii Utilizate**  
- **R Shiny** → pentru interfață reactivă  
- **ggplot2** → pentru reprezentările grafice  
- **dplyr & tidyr** → pentru manipularea datelor  

---

## 📌 **Cum rulezi aplicația?**  
1. Clonează repository-ul:  
   ```bash
   git clone https://github.com/Aleexaandraa10/proiect-ps.git
2. Deschide RStudio și încarcă fișierul App.R
3. Rulează aplicația cu:
   ```bash   
   shiny::runApp()
