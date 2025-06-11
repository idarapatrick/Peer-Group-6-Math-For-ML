# Peer-Group-6-Math-For-ML
Peer group 6 input on the formative assessment in the course, Mathematics for Machine Learning. 

## Task 1
This task was done in collaboration. The dataset used is a malaria dataset about different African countries, pulled from Kaggle. The dataset contains informtaion about country name, dataset, country code, malaria occurences per 1000 people, total cases of malria reported, year, urban population, rural population, etc. 

- To begin this task, we had to clean our dataset, by dropping columns we didn't find relevant to our tasks.
- We proceeded to fill the null values with 0 as we found this step more effective than calling .dropna() to drop rows with null values.
- With our modified data, we created a new column called "malaria intensity" by using logic.
  - The logic involved finding the mean of the column for the occurence of malria, and ensuring that for each row, any value equals to or greater than the mean must be 1 in the "malaria intensity" colum, and any value below the average must be 0.
- With this we proceeded to complete the remaining tasks in the notebook. 

The repository link to the python package for the matrix multiplication can be found here: [Link to repository](https://github.com/idarapatrick/matrix-multiplication-package.git)
