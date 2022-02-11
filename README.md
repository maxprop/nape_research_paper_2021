### nape_research_paper_2021

ABSTRACT
Delineation and classification of distinct geologic facies from 3D seismic volumes constitute an important part of seismic data interpretation during geophysical exploration for hydrocarbons. Seismic volumes are created from reflected or refracted seismic waves from the earth’s interior reflecting geological formations and structures. During prospecting, field development, and reservoir characterization, it is important to interpret the different units of depositional facies as it helps to provide insights into the geology of the hydrocarbon systems present in a field. Interpretations are usually carried out by experienced geologists and specialists manually on workstations to quickly show and highlight important features of the 3D images. Detailed classification of large images representing a wider environment of deposition will often require hundreds of work hours by experts. A machine learning approach to automatically produce the pixel-by-pixel classification with better results implementing a data augmentation process is proposed. This problem is majorly approached as an image segmentation process where each voxel in the image is classified into its respective facies class. Convolutional Neural Networks (CNNs) are popular methods for solving such problems along with a U-Net segmentation workflow. Random 2D slices extracted from the X, Y, and Z axes representing different inline, crossline, and time-depth portions of the seismic volume were utilized to train the deep learning network. The data augmentation process implemented helped to introduce unique data samples to the model. This process involves slicing the 3D seismic volume diagonally all through the three dimensions thereby producing 2D images that are inclined and represent tilted pieces of the seismic volume. These images also helped contribute special signal inputs not found in the training data to the network since these images were seen differently as new samples by the model.
