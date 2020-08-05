# DeepFakeMe :robot:

In this notebook, I deepfaked myself by adapting from a demonstration from the paper *First Order Motion Model for Image Animation*. You can find more information [here](https://aliaksandrsiarohin.github.io/first-order-model-website/) in their website.

A simple-to-understand video on the First Order Motion Model and what sets it apart from other contemporary deepfake techniques is discussed in this YouTube video *[Everybody Can Make Deepfakes Now!]*(https://www.youtube.com/watch?v=mUfJOQKdtAk).

I was inspired from this YouTube video titled *[How It's Memed: First Order Motion Model Deepfake](https://www.youtube.com/watch?v=zZr3EHLBm4g&feature=youtu.be)*.

Google Colab demo, from which I adapted and modified from, can be found in their GitHub repo [here](https://github.com/AliaksandrSiarohin/first-order-model/blob/master/demo.ipynb). The pre-trained checkpoint (which is required but since it's too big thus I excluded it in this repo) can be obtained from this shared Drive [here](https://drive.google.com/drive/folders/1kZ1gCnpfU0BnpdU47pLM_TQ6RypDDqgw?usp=sharing) or, you can look at the repo's [README.md to](https://github.com/AliaksandrSiarohin/first-order-model#pre-trained-checkpoint) find it. Place the `.tar` file in the `first-order-motion-model` directory.

Note that the model checkpoint is trained on 256\*256 pixel images. From my understanding, at time of this writing there's no other pre-trained sizes available unfortunately.

# Output Gif

![Alt Text](https://github.com/ktingyew/DeepFakeMe/blob/master/output.gif)
