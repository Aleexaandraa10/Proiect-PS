# Shiny Application for Random Variable Distributions and Custom Functions

## 🔹 Description  
This interactive application, developed in **R Shiny**, allows users to explore probability distributions and custom functions through dynamic visualizations and direct user interaction.  
The project integrates fundamental concepts of **statistics and probability**, providing an educational platform where users can **simulate distributions, apply transformations, and analyze empirical distributions**.

---

## 🚀 Features  
- **Generation and representation of distributions**: Normal, Exponential, Poisson, Binomial  
- **Transformation of random variables**: For example, `3 - 2X`, `X²`, `∑X`, `∑X²`  
- **Displaying the empirical cumulative distribution function (ECDF)** for distributions and transformations  
- **Implementation and visualization of custom functions**  
- **Interactive interface** for adjusting parameters and graphical exploration  

---

## 📌 Application Architecture  
The project is structured into two main modules:

###  1. **Random Variable Distributions**  
- Generating samples from selected distributions  
- Applying transformations to the random variable  
- Graphical representation of the **empirical cumulative distribution function (ECDF)**  

###  2. **Custom Functions**  
- Visualizing analytically defined functions  
- Adjusting parameters and definition intervals  
- The ability to compare different functions  

---

## 🛠️ **Technologies Used**  
- **R Shiny** → for the reactive interface  
- **ggplot2** → for graphical representations  
- **dplyr & tidyr** → for data manipulation  

---

## 📌 **How to Run the Application?**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Aleexaandraa10/proiect-ps.git
   ```
2. Open RStudio and load the `App.R` file.  
3. Run the application with:  
   ```bash   
   shiny::runApp()
   ```
