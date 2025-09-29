# EDA_project

# Netflix Exploratory Data Analysis (EDA)

This project presents an exploratory analysis of Netflix movies and TV shows.
A cleaned dataset of 5,328 records and 12 features was used.
The cleaning process was performed using a custom-built [Streamlit WebApp](https://edaapp-udphbqqqjkth4gtaibbjfh.streamlit.app/).

---

##  Dataset Information

* **Rows:** 5,328
* **Columns:** 12
* **Features:**

  * `show_id`, `type`, `title`, `director`, `cast`, `country`,
  * `date_added`, `release_year`, `rating`, `duration`,
  * `listed_in`, `description`

---

##  Visual Analysis

### 1. Content Types

**Chart:** Bar chart of count(`show_id`) by `type`

* Movies dominate the catalog, highlighting Netflix’s stronger focus on films.
* TV Shows form a significant portion, but less than movies.


---

### 2. Ratings Distribution

**Chart:** Bar chart of count(`show_id`) by `rating`

* Most frequent ratings: **TV-MA**, **TV-14**, and **R**.
* Indicates Netflix’s emphasis on mature and young adult audiences.


---

### 3. Release Year Trends

**Chart:** Line chart of count(`show_id`) by `release_year`

* Clear growth trend after **2010**.
* Rapid expansion aligns with Netflix’s global production strategy.


---

### 4. Date Added to Netflix

**Chart:** Line chart of count(`show_id`) by `date_added`

* Spikes around **2018–2020** confirm rapid content acquisition.
* Reflects Netflix’s aggressive library expansion.



---

### 5. Country-wise Content

**Chart:** Bar chart of count(`title`) by `country`

* **United States** leads in content production.
* **India** and **United Kingdom** follow, showing regional strengths.

---

### 6. Movie Duration Distribution

**Chart:** Histogram of `duration` (Movies)

* Most movies range between **80–120 minutes**.
* Matches standard film runtimes.



---

### 7. TV Show Duration Distribution

**Chart:** Histogram of `duration` (TV Shows)

* Majority of series run for **1–3 seasons**.
* Limited-series and short-format shows are common.



---

### 8. Audience Ratings Share

**Chart:** Pie chart of `title` by `rating`

* Mature ratings (**TV-MA**, **TV-14**) dominate.
* Confirms Netflix’s focus on adult and teen audiences.



---

##  Key Insights

* Netflix prioritizes **movies** but has a strong presence in **TV shows**.
* Majority of content is rated for **mature and young adult audiences**.
* Content production surged significantly after **2010**.
* **U.S., India, and the UK** are leading contributors to the catalog.
* Most movies are around **2 hours**, while most TV shows last **1–3 seasons**.

---

##  WebApp

Data cleaning was done using a custom-built Streamlit application:
[EDA WebApp](https://edaapp-udphbqqqjkth4gtaibbjfh.streamlit.app/)

---

Author Name[Prateek Kudari]
