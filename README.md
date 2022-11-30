# DiffusionSync
Lip Sync using Spectrogram analysis linked with Diffusion models to generate realistic mouth pieces.

1. Diffusion model take up as much as one hour to generate realistic mouth piece at 480p resolution. 
2. Training on A100 locally would probably generate better results.
3. cache withdrawal could potentially generate better results.
4. Generate vids of 480p resolution, 20 seconds clips.

* a. Dated: 28th Nov: Upscaled video without audio added. Stable diffusion upscales to 720p.
* b. Dated: 28th Nov: https://youtu.be/DKaYazpKhJ0 , Upscaled video to 1080p. Diffusion activated
* c. Check **DFS_AK_covid.mp4** for results on quick based audio. Poor results. Model looks good for single person ads. 
* d. More examples enroute testing. **Positive about going beta access before Jan 1st, 2022 for ads and commericials** 
* e. Currently researching possible levels on upscaling incl. diffusion models, for super-resolution on limited resources.
* f. **Dated 29th Nov** Check DFS_BB2_hindi.mp4 for different AoV lip sync. Upscaling the video soon!
* g. **Dated 29th Nov** HD version of DF_BB2_hindi is available at **https://youtu.be/b51Fr-SBMJM** . Experimented using Diffusion models to generate mouth pieces, note the indifferent output of the people in the background. This happens due to the dataset bias that Diffusion model has. But, progress seems good!
* h. Next stop would be impose a mask layer and apply diffusion models. but still HD level lipsync is Goooood!!!!!
* i. Tried mini-Diffusion model for front facing lipsync. Results looks decent. Click https://youtu.be/Io3wQY0GSfc for result.
