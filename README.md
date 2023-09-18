# machineLearning_reduction-with-PCA
prediction heart disease with pca machine-learning 

# guide-start python code 

- Install miniconda
- Intall jupyter notebook
- Intall Instalasi Environment python env_jcopml.yml
- check_installation.py

# sample dataset preview
	HeartDiseaseorAttack	HighBP	HighChol	CholCheck	BMI	 Smoker	Stroke	Diabetes	PhysActivity	Fruits	...	AnyHealthcare	NoDocbcCost	GenHlth	MentHlth	PhysHlth	DiffWalk	Sex	Age	Education	Income


# summary 

reduction feature form n_components = 15 
result: {'algo__C': 0.05660670699258889, 'algo__gamma': 0.157823278107956, 'pca__n_components': 15, 'pca__whiten': False} 0.5400652396720278 0.5655008278145696 0.5410950804162725

after pca form n_components = 10 

result: {'algo__C': 0.05660670699258889, 'algo__gamma': 0.157823278107956} 0.5407550851466414 0.5746560627562283 0.5424550614947966
