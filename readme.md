## MNIST with first model
Create a folder called "data"<br />
Download the MNIST dataset following this (https://github.com/explainingai-code/Pytorch-VAE#data-preparation)<br />
Extract the MNIST data into the "data" folder<br />
Run '''python extract_mnist_images.py'''<br />
Run the Main '''diffusion.ipynb'''<br />
If you just want to generate samples, you can just run the part under Sampling Section<br />\
You can then check the results under the result file


## MNIST with second model
'''pip install -r requirements.txt'''<br />
'''python -m tools.train_ddpm''' for training ddpm<br />
'''python -m tools.sample_ddpm''' for generating images<br />
You can then check the results under the result file