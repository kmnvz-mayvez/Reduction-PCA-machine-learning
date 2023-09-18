# machineLearning_reduction-with-PCA
prediction heart disease with pca machine-learning 

# guide-start python code 

- Install miniconda
- Intall jupyter notebook
- Intall Instalasi Environment python env_jcopml.yml
- check_installation.py

# sample dataset preview
| HeartDiseaseorAttack | HighBP | HighChol | CholCheck | BMI  | Smoker | Stroke | Diabetes | PhysActivity | Fruits | ... | AnyHealthcare | NoDocbcCost | GenHlth | MentHlth | PhysHlth | DiffWalk | Sex | Age | Education | Income |
|----------------------|--------|----------|-----------|------|--------|--------|----------|--------------|--------|-----|---------------|------------|---------|----------|----------|----------|-----|-----|-----------|--------|
| 0.0                  | 1.0    | 1.0      | 1.0       | 40.0 | 1.0    | 0.0    | 0.0      | 0.0          | 0.0    | ... | 1.0           | 0.0        | 5.0     | 18.0     | 15.0     | 1.0      | 0.0 | 9.0 | 4.0       | 3.0    |
| 0.0                  | 0.0    | 0.0      | 0.0       | 25.0 | 1.0    | 0.0    | 0.0      | 1.0          | 0.0    | ... | 0.0           | 1.0        | 3.0     | 0.0      | 0.0      | 0.0      | 0.0 | 7.0 | 6.0       | 1.0    |
| 0.0                  | 1.0    | 1.0      | 1.0       | 28.0 | 0.0    | 0.0    | 0.0      | 0.0          | 1.0    | ... | 1.0           | 1.0        | 5.0     | 30.0     | 30.0     | 1.0      | 0.0 | 9.0 | 4.0       | 8.0    |
| 0.0                  | 1.0    | 0.0      | 1.0       | 27.0 | 0.0    | 0.0    | 0.0      | 1.0          | 1.0    | ... | 1.0           | 0.0        | 2.0     | 0.0      | 0.0      | 0.0      | 0.0 | 11.0 | 3.0       | 6.0    |
| 0.0                  | 1.0    | 1.0      | 1.0       | 24.0 | 0.0    | 0.0    | 0.0      | 1.0          | 1.0    | ... | 1.0           | 0.0        | 2.0     | 3.0      | 0.0      | 0.0      | 0.0 | 11.0 | 5.0       | 4.0    |


# summary 

reduction feature form n_components = 15 

result: 
{'algo__C': 0.05660670699258889, 'algo__gamma': 0.157823278107956, 'pca__n_components': 15, 'pca__whiten': False} 0.5400652396720278 0.5655008278145696 0.5410950804162725

after pca form n_components = 10 

result: 
{'algo__C': 0.05660670699258889, 'algo__gamma': 0.157823278107956} 0.5407550851466414 0.5746560627562283 0.5424550614947966
