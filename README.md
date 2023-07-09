# Deep Learning Final Project

Welcome to our deep-learning project focused on Pokémon classification! In this project, we have developed a classifier using deep learning techniques (Transfer-Learning and Self-Supervised Learning) to identify and categorize different Pokémon species accurately. We will provide a comprehensive explanation of how to utilize our trained model for Pokémon classification tasks, enabling you to easily leverage the power of deep learning in your own Pokémon-related projects. 
our collab file (i.e .ipynb) includes a detailed guide on using our Pokémon classifier effectively!

in our project you just need to run the cells, we provide all the work needed to download the Pokemon data set.

**we will sum up here :**
1. **section A** - Environment Building and Database Processing:
   
   1.1 **A.1** Building Environment
   
   1.2 **A.2** Downloading Data
   
   1.3 **A.3** Pre Processing Data (so it will be easier to run the model on the data)
   
2. **Section B** - Self Supervised Approach
   
   In this section we will offer 2 main approaches for the model architecture:
   Pre-training of - Self Supervised learning model and then transfer learning and training model.
   transfer learning using SOTA VGG pre trained model and training it on our data.
   
   2.1 **B.1** Building an environment for using Self Supervised Learning approach
   
   2.2 **B.2** using BYOL as the self-supervised model
   
   2.3 **B.3** using DINO as the self-supervised model
   
   2.4 **B.4** using SimCLR as the self-supervised model
   
   2.5 **B.5** using Sim Siam as the self-supervised model
   
3. **Section C** - Training Techniqe Functions
   
   *This section is mandatory for every approach you chose*
   
   3.1 **C.1** Functions need to be loaded before training the model
   
4. **Section D** - Self Supervised Training Phase
   
    *Run this section only if you chose the self supervised approach*
   
   4.1 in the train phase : *Note: pay attention that after you Fine-tuning and re-train the model (by running the next cell code), a checkpoint will be saved to the main directorty.*
   
15. **Section E** - Transfer Learning Approach
    
   *Run this section only if you chose the transfer learning using VGG approach*
   
   5.1 Transfering VGG model without self_supervised Pre-Training
   
   *Note: pay attention that after you Fine-tuning and re-train the model (by running the next cell code), a checkpoint will be saved to the main directorty.*
   
5. **Section F** - Results and Test
    
   *In this section we will show the model results and test the model on the test dataset*
    
   6.1 Best Model Loss and Accuracy curves
   
   6.2 Testing The Model
   
   6.3 results from our runs :) 
   
   
