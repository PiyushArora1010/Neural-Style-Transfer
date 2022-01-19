# Neural-Style-Transfer
Neural style transfer is a computer vision technique that allows us to recompose the content of an image in the style of another. If you’ve ever imagined what a photo might look like if it were painted by a famous artist, then style transfer is the computer vision technique that turns this into a reality. This is the implementation of the famous research paper on Neural Style Transfer. 

# Use of Gram Matrix
Gram Matrix is used to calculate the style loss function which is to be applied on the content image.

# Use of Adam optimizer instead of L-BFGS
Adam optimizer with a learning rate of 0.01 was used instead of conventional L-BFGS optimizer which was used in the research paper.

# VGG19 architecture
Block4_Conv2d_2 layer was used for content output.
Block1_Conv2D_1, Block2_Conv2D_1, Block3_Conv2D_1, Block4_Conv2D_1, Block5_Conv2D_1 were used for style output.
