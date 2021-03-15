# seurat_on_AWS
sagemaker notebook for scRNA analysis


The notebook runs a slightly modified/abbreviated version of this tutorial: https://satijalab.org/seurat/articles/pbmc3k_tutorial.html. There is actually a great series of vignettes that you can plug in to this notebook, including one for multimodal analysis. 
 
To experiment with the notebook: create a SageMaker notebook instance. Detailed instructions are here, simple instructions are: go to SageMaker in the console and click on “Notebook instances”
 
Two notes when creating your notebook instance:
Expand “Additional configuration” under Notebook Instance settings. You will need to increase the size of the root volume. This gives you some space to hold test data while playing around. You can always stop the instance and increase the size of the volume as needed, but I started with 20Gb.
When creating your instance, expand “Git repositories” and select “Clone a repository to use for this notebook instance only. Paste this git repository URL: https://github.com/jennomics/seurat_on_AWS.git
