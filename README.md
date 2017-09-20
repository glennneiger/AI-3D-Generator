# AI-3D-Generator
The point of this repo is to keep all my code for a GAN that generates voxel files based on training in specific 3D models of some category. The purpose of this is to use this as a design aid for 3d printing products.

The project will contain a scraper to allow the user to create new datasets based on a category of 3D models. For example, if I want to train my GAN to generate home and kitchen models, then I will use this scraper to capture all possible models in the chosen category. The files will be stl files, that are not easy to work with using convolutional neural networks, so we will voxelize them and then bundle them in batches.

The next part is a GAN Model based on the DCGAN paper. But the main difference is that rather than working with 2D Convolutional layers, we will work with 3D convolutional layers, since our desired output is a 3D voxel model.
