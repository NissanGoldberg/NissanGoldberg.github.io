---
name: Deep Learning Paper
tools: [Academia, Deep Learning]
image: https://techcrunch.com/wp-content/uploads/2016/06/shutterstock_330496148.png
description: Learning to Conceal&#58; A Method for Preserving Privacy and Avoiding Prejudice in Images.Learning to Conceal
---

### A Method for Preserving Privacy and Avoiding Prejudice in Images

Using **VAE** we introduce a learning model able to **conceal personal information** (e.g. gender, age, ethnicity, etc.) from an image while maintaining any additional information present in the image (e.g. smile, hair-style, brightness).

![](https://i.ibb.co/FggSw74/vae-paper.png)

We created a variational autoencoder (VAE) model that is trained on a dataset including labels of the information one would like to conceal (e.g. gender, ethnicity, age). These labels are directly added to the VAE's sampled latent vector. Due to the limited number of neurons in the latent vector and its appended noise, the VAE avoids learning any relation between the given images and the given labels, as those are given directly. Therefore, the encoded image lacks any of the information one wishes to conceal.

<p class="text-center">
{% include elements/button.html link="https://arxiv.org/abs/1909.09156" text="Learn More" %}
</p>