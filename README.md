# A brief introduction of cross-status-lsm

This project provides data of "Cross-status Communication and Project Outcomes in OSS Development".
+ The file *Data* contains two files *RQ1* and *RQ2*.
 - In *RQ1*, the data of **Section 6.1** are provided.
   * *6-1-1-LanguageStyleMatching(LSM)-values.cs*v shows 13 LSM scores (12 LIWC categories and the average) of 166 projects.
   * *6-1-2-Friedman-Test.csv* shows the Friedman-Test results of 166 projects' LSM scores.
   * *6-1-3-project-features.csv* shows the results of non-parametric Spearman rank-order correlation test and results of the Kruskal-Wallis rank sum test. 
     + Column 1: Project Repo Name 
     + Column 2-14: LSM variables 
     + Column 15: Ratio of the elite to the non-elite 
     + Column 16: project team size 
     + Column 17: average experiences 
     + Column 18: Sponsorship 1: With sponsorship 0: Without sponsorship 
     + Column 19: Main programming language 1: JavaScript-like 2: C++ 3: Ruby 4: Python 5: Go 6: C 7: Java 0: Others 
     + Column 20: Application domain 1: Development Environment & Tools 2: System 3: Cloud & Networking 4: Security & Privacy 5: AI 6: Data Science 7: Enterprise-General  8: Mobile 0: Others
   * *Figures of projects' LSM values* contains 12 figures that each depicts one selected LSM values' distribution of all 166 projects.
     + LSM-1.eps depicts the LSM values' distribution of Personal Pronouns category.
     + LSM-2.eps depicts the LSM values' distribution of Impersonal Pronouns category.
     + LSM-3.eps depicts the LSM values' distribution of Articles category.
     + LSM-4.eps depicts the LSM values' distribution of Prepositions category.
     + LSM-5.eps depicts the LSM values' distribution of Auxiliary Verbs category.
     + LSM-6.eps depicts the LSM values' distribution of Common Adverbs category.
     + LSM-7.eps depicts the LSM values' distribution of Conjunctions category.
     + LSM-8.eps depicts the LSM values' distribution of Negations category.
     + LSM-9.eps depicts the LSM values' distribution of Analytic Thinking category.
     + LSM-10.eps depicts the LSM values' distribution of Clout category.
     + LSM-11.eps depicts the LSM values' distribution of Authentic category.
     + LSM-12.eps depicts the LSM values' distribution of Tone category.
 - In *RQ2*, the data of **Section 6.2** are provided.
   + *6-2-regression.csv* shows the values of regression model.
     * Column 1: Project Repo Name
     * Column 2-5: Project outcome variables
     * Column 6-18: LSM variables
     * Column 19-25: Main programming language
     * Column 26-33: Application domain
     * Column 34: Ratio of the elite to the non-elite
     * Column 35: Project team size Column 36: Average experiences
     * Column 37: Sponsorship

