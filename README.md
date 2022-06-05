# cursed-poodles
The styleGAN that nobody asked for! I had a lot of fun learning about GANs and decided to train one of my own.
- The model was designed by NVIDIA: https://github.com/NVlabs/stylegan2-ada-pytorch
- I used flicker to scrape images of poodles and barely filtered the data, mostly for my own curiosity.
- The final model took 14 hours to train using my RTX 2060 NVIDIA gpu.

# Set-up Instructions using Pip Virtual Enviroments
1. Make sure you are using Python version 3.9.13 (I did this using a pyenv shell)
2. Create a new pip enviroment
3. git clone https://github.com/NVlabs/stylegan2-ada-pytorch to replace the empty folder named "stylegan2-ada-pytorch" in the repository
4. Activate the enviroment and pip install requirements.txt
5. Run demo.ipynb and have fun! You can change the seed values to generate new images of poodles.

## Results
![This is an image](./fakes.png)
