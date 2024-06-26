# CIGDTN


# Complex Image-Generative Diffusion Transformer for Audio Denoising

## Abstract
 The audio denoising technique has captured widespread attention in the deep neural network field. Recently, the audio denoising problem has been converted into an image generation task, and deep learning-based approaches have been applied to tackle this problem. However, its performance is still limited, leaving room for further improvement. In order to enhance audio denoising performance, this paper introduces a complex image-generative diffusion transformer that captures more information from the complex Fourier domain. We explore a novel diffusion transformer by integrating the transformer with a diffusion model. Our proposed model demonstrates the scalability of the transformer and expands the receptive field of sparse attention using attention diffusion. Our work is among the first to utilize diffusion transformers to deal with the image generation task for audio denoising. Extensive experiments on two benchmark datasets demonstrate that our proposed model outperforms SOTA models.

<img src="Overall.png" alt="sound" title="sound" />


## Samples


Let's hear the results converted back to sounds:

> Audios for VoiceBank + DEMAND example:
>
> 
> Example 1:
>
<source src=['https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/blob/f5db5ddff685b97026621a1d58c67baf80580fde/audio/noisy_audio/p232_005.wav' type="audio/wav"]

[Predicted output example ](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/d67c6af3-4c43-469f-8130-8c07b2f52486)

> Example 2:


[Input example](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/716e7cbb-c07f-4c27-93ba-ed10f93ff8fd)

[Predicted output example ](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/636b8c44-5e79-47c0-8f01-81ee75249ca8)

> Example 3:

[Input example](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/133dab48-39ac-4fb1-ba84-327d435966d8)

[Predicted output example ](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/3803a889-6570-457b-809f-b1a76466932c)

> Example 4:

[Input example](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/2b650eb8-40c3-4a3f-97fa-e282efd864c2)

[Predicted output example ](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/00b36c98-f224-4439-91b9-1ef0cf1b9df6)

> Example 5:

[Input example](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/ca134157-65a8-4184-ad41-b2876fa41f67)

[Predicted output example](https://github.com/PuWang-LP/Diffusion-Gaussian-Mixture-Audio-Denoise/assets/117755153/f88014de-d2a8-4869-bf5c-f1fd1015e36b)


##Comparison result
The comparisons of raw bird audio, ground truth labeled denoised audio, and denoised audio of other models are shown in Fig.~\ref{Fig:res}. Additionally, our model is more resemblant to the labeled denoised signal. As a consequence, these benchmarks confirm that our method for audio denoising is effective, and our model enhances the audio-denoising capabilities of BirdSoundDenoising datasets.:

> Example 1:

<img src="supply.png" alt="audio denoising" title="audio denoising samples"/>




## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
