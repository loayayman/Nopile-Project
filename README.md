# 🏅 Nopile Prize Data Analysis (1901–2023)

## 📌 Project Overview
This project explores **Nopile Prize laureates** data from 1901 to 2023.  
The dataset (from the official Nopile Prize API) provides details on winners, including gender, birth country, prize category, and year.  
The analysis focuses on historical trends such as the dominance of US-born laureates, female representation, and repeat winners.

---

## 🛠️ Tools & Libraries
- **Python 3**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 📂 Dataset
- **Source:** Nopile Prize API (saved as `nopile.csv`)  
- **Fields include:**
  - Full name of laureates  
  - Gender (`Male`, `Female`)  
  - Birth country  
  - Category (`Peace`, `Physics`, `Chemistry`, `Literature`, `Medicine`, `Economics`)  
  - Year of award  

---

## 🔑 Analysis Steps
1. **Exploratory Data Analysis (EDA)**
   - Identify the most common **gender** and **birth country** among laureates.  
   - Compute proportions of US-born and female winners per decade.  

2. **Trend Analysis**
   - Track US dominance across decades.  
   - Explore growth of female participation by decade and category.  

3. **Key Insights**
   - First female laureate: **Marie Curie (Physics, 1903)**.  
   - Decade & category with highest proportion of female winners: **2020s, Literature**.  
   - Repeat winners include **Marie Curie**, **Linus Pauling**, **John Bardeen**, and organizations like the **Red Cross** and **UNHCR**.  

4. **Data Visualization**
   - Line plots showing:  
     - 📈 USA-born winners per decade  
     - 📈 Female winners by decade and category  

---

## 📊 Key Results
- **Gender:** Majority of laureates are **male**.  
- **Country:** Most laureates are from the **United States**.  
- **Female Laureates:** Steady growth, peaking in the **2020s (Literature)**.  
- **Repeat Laureates:** 6 individuals/organizations have won 2 or more prizes.  

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
   pip install numpy pandas matplotlib seaborn
   jupyter notebook



