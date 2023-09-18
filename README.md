# machineLearning_reduction-with-PCA
prediction heart disease with pca machine-learning 

# guide-start python code 

- Install miniconda
- Install jupyter notebook
- Install Instalasi Environment python env_jcopml.yml
- check_installation.py

# sample dataset preview
| HeartDiseaseorAttack | HighBP | HighChol | CholCheck | BMI  | Smoker | Stroke | Diabetes | PhysActivity | Fruits | ... | AnyHealthcare | NoDocbcCost | GenHlth | MentHlth | PhysHlth | DiffWalk | Sex | Age | Education | Income |
|----------------------|--------|----------|-----------|------|--------|--------|----------|--------------|--------|-----|---------------|------------|---------|----------|----------|----------|-----|-----|-----------|--------|
| 0.0                  | 1.0    | 1.0      | 1.0       | 40.0 | 1.0    | 0.0    | 0.0      | 0.0          | 0.0    | ... | 1.0           | 0.0        | 5.0     | 18.0     | 15.0     | 1.0      | 0.0 | 9.0 | 4.0       | 3.0    |
| 0.0                  | 0.0    | 0.0      | 0.0       | 25.0 | 1.0    | 0.0    | 0.0      | 1.0          | 0.0    | ... | 0.0           | 1.0        | 3.0     | 0.0      | 0.0      | 0.0      | 0.0 | 7.0 | 6.0       | 1.0    |
| 0.0                  | 1.0    | 1.0      | 1.0       | 28.0 | 0.0    | 0.0    | 0.0      | 0.0          | 1.0    | ... | 1.0           | 1.0        | 5.0     | 30.0     | 30.0     | 1.0      | 0.0 | 9.0 | 4.0       | 8.0    |
| 0.0                  | 1.0    | 0.0      | 1.0       | 27.0 | 0.0    | 0.0    | 0.0      | 1.0          | 1.0    | ... | 1.0           | 0.0        | 2.0     | 0.0      | 0.0      | 0.0      | 0.0 | 11.0 | 3.0       | 6.0    |
| 0.0                  | 1.0    | 1.0      | 1.0       | 24.0 | 0.0    | 0.0    | 0.0      | 1.0          | 1.0    | ... | 1.0           | 0.0        | 2.0     | 3.0      | 0.0      | 0.0      | 0.0 | 11.0 | 5.0       | 4.0    |

# visualiasai scatterplot 

![image](https://github.com/kmnvz-mayvez/machineLearning_reduction-with-PCA/assets/55338832/e5103f5b-c181-47f4-a9aa-af7bb4f0f139)

- 1.0 heart diseaseor attack true
- 0.0 heart diseaseor attack false

# Cumulative Explained Variance

![image](https://github.com/kmnvz-mayvez/machineLearning_reduction-with-PCA/assets/55338832/3cb8dd1e-63ca-49cb-9c20-460ba9599acd)

- untuk n_components 

# summary
# Reduction Feature form n_components = 10
# Result:

- algo__C: 0.05589524205217925
- algo__gamma: 4.689400963537697
- pca__n_components: 10
- pca__whiten: False
- Accuracy: 0.9061071034374014
- Precision: 0.905151174708294
- F1 Score: 0.9052546515294859

# After PCA form n_components = 5
# Result:

- algo__C: 0.5450293694558256
- algo__gamma: 51.41096648805754
- Accuracy: 0.9065801403342794
- Precision: 0.9052103043204037
- F1 Score: 0.9053532008830022
