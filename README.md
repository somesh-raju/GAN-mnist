# GAN-mnist
ML GAN model that generates images that look like hand-written digit images from MNIST database.

Below is an example of what the model generates after training 100 epochs.
![MNIST_GAN_100](https://user-images.githubusercontent.com/27999651/179366717-369030ee-58ae-4f98-a332-54ba413cf9a6.png)

The model performs better after adding dropout to Generator and Discriminator network.
Below is the loss plot generated after training with Dropout. We can see the generator loss is lower than Discriminator's, which is what we normally try to achieve.
![MNIST_GAN_train_hist_w_dropout](https://user-images.githubusercontent.com/27999651/179367214-84bcb301-3ba8-4d65-97d5-4823eb3dc30c.png)


And, here's the plot without dropout.


![MNIST_GAN_train_hist](https://user-images.githubusercontent.com/27999651/179367225-1ce33d1c-ddae-474b-aa2e-4b05510a0668.png)
