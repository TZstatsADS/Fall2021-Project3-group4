# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2021

+ Team #4
+ Team members
	+ Hui Xiang
	+ Meghna Venkatesh
	+ Spark Li
	+ Emily Jennings-Dobbs
	+ Dipesh Patel

+ Project summary: In this project, we built two models to experiment and deal with the noisy label issues. For the first model, we built a deep neural network and trained it on the noisy labels. Our algorithm includes batch normaizalition, Relu activation function and Adam optimizer and it was able to achiave a better training result compared to the baseline model. For the second model, we first used the deep neural network and trained it on the clean labels. Then we used the trained neural network to correct the noisy labels. After label correction, we added several weakly supervised features that augmented images by normalizing the features and fill the newly shifted pixel by nearest ones. These techniques helps our second model to be more robust.
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md))
	+ Hui Xiang: Initialized group connection with Emily, provided suggestions for model 1 neural network, built and tuned model 2 in Python including label correction                         and add weakly supervised features, write project summary.
	+ Meghna Venkatesh：
	+ Spark Li：Testing and tuning model 1.
	+ Emily Jennings-Dobbs: Helped initiate and maintain communication within the group. Built and tuned the first model in python. Helped tune parameters and added early stopping feature to second model.
	+ Dipesh Patel：Testing model 1. Provided suggestions for model 2. Helped with debugging model 2. Helped with explanantions for model selection and construction.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
