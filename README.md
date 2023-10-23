# Master-Thesis
Containing Python and codes for 2D and 3D rock image segmentation

# Development of artificial neural algorithms in 3D segmentation of digital rock physic images to estimate pore space parameters

Accurate segmentation of micro-CT scan images of rocks, as the most crucial step in the path of
digital analysis of rock physics, has always been challenging and vital. As a result, the incomplete
segmentation leads to a significant error in estimating the flow and petrophysical properties of the
rock, such as permeability and porosity. Typically, an expert spends most of his time finding the
proper segmentation parameters to achieve the best possible results. This process is an extremely
exhausting and time-consuming process that causes even the most experienced professionals to
make mistakes. Therefore, it is necessary to present an automated method for image segmentation
to increase the speed and accuracy of two- and three-dimensional image segmentation and prevent
experts' errors. Methods based on convolutional algorithms, especially U-Net encoder-decoder
structure, will be one of the best-proposed methods. Based on this, in this research, a novel
structure named ARU-Net has been introduced to overcome the limitations of the usual U-Net
structure and improve the segmentation operations of 2D and 3D rock images. We modified the
proposed network by applying the residual and attention structures to the basic architecture of UNet to increase the final network's efficiency and accuracy. The residual structure, due to its
specific features and performance, prevents the network from being saturated during the learning
process. This function increases the accuracy of the model and its better learning. Also, using the
attention structure helps the network to use less computational resources and achieve higher
accuracy by focusing more on specific and main areas of the input images. The database used in
this research consists of two-dimensional images of four well-known sandstone samples (Parker,
Berea, Buff Berea, and Leopard), which we prepared by applying the necessary pre-processing
methods to train and evaluate the proposed network to ensure the richness and generalizability of
the database and model. During the model training process, the U-Net network estimated the
porosity equivalent to segmentation images with an error percentage of 10%. In comparison, the
proposed ARU-Net network reduced this error percentage to 4.10%. In addition to evaluating
models through porosity estimation, other common evaluation criteria have also been used, and in
all cases, the proposed network is preferable to the conventional U-Net network. The remarkable
performance of the presented model is related to its high ability to segment different and complex
porous and solid areas from each other.
