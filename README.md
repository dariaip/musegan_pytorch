# Musegan implementation using pytorch 
The depository includes an implementation of MuseGAN, originally presented at https://salu133445.github.io/musegan/
At the project Github repository there is a link to Pytorch implementation of the model, but the implementation is rather different from the approach described at "MuseGAN: Multi-track Sequential Generative Adversarial Networks for Symbolic Music Generation and Accompaniment" (https://arxiv.org/abs/1709.06298) and could be used in Google Colab because of shortage of resources there. 

So, my solution is based on the repository, but get closer to the original approach and can work at Google Colab (the process takes approximately 3.5 hours).

How to use it:
1. Open the provided jupyter notebook at Google Colab (environment with GPU)
2. Put "requirements.txt" at the same folder
3. Launch the code.

During training it saves intermediate results at ".mid" files, so you can easily download it and listen to generated music.

I also uploaded an example of generated music that I've got using the trained model.
