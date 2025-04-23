## LINEAR DISCRIMINANT ANALYSIS
---
- *Supervised machine learning technique*
- Used for
    - Classification
    - Dimesnionality reduction
- **IDEA:** LDA projects the data into lower dimensions space such that it maximises dit between multiple classes
    - Maximise the dist btwn diff class means
    - Minimise the spread of variance within class
> **KEY**:It uses both axes (X and Y) to generate a new axis in such a way that it maximizes the distance between the means of the two classes while minimizing the variation within each class. This transforms the dataset into a space where the classes are better separated.
---
#### Works better when?
- Linearly seperable
- Data follows normal distribution
- Simila covaraince
--- 
### Why scaling matters in LDA?
- LDA works by Covaraice matrix and distance-based calculations
- `standardScaler` it tranforms each feature to hhave a ***mean=0*** and ***SD=***
-  `fit_transform()` on the ***training set*** to learn its mean and std, then scale it.

- `transform()` on the **test set** using the same mean and std from the training set.
---
### CODE
- `n_components` in LDA stands for how many linear discriminants (features) you want to reduce your data to.