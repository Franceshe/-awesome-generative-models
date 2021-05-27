# awesome-generative-models
A curated list of awesome generative model frameworks, libraries, software and resources for media production

inspired by [awesome-python](https://github.com/vinta/awesome-python)
<div align="center">
	<img width="500" height="350" src="media/somercloud_1_logo.PNG" alt="Awesome">
	<br>
	<br>
	<hr>
	<p>
		<p>
			<sup>
				<a href="https://github.com/SomerCloud-Studio">My open source work is supported by the community</a>
			</sup>
</div>

- [Awesome Generative Mdels](#awesome-generative-models)
	- [Code generation: ML algorithm + Static Analysis](#CodeGeration)
    - [Code to GUI: algorithm to user interface](#CodeToGUI)
	- [Image Synthesis](#imageSynthesis)
		- [Image Style Transfer](#ImageStyleTransfer)
    - [Text Generation/NLP](#NLP)
		- [Audio and music generation/processing](#AudioAndMusicGenerationProcessing)
		- [Music-Video Synthesis](#MusicVideoSynthesis)
    - [Video-Synth](#videoSynth)
	- [Procedural Generation for gaming](#ProceduralGenerationForGaming)
	- [Image-Generation](#imageGeneration)
    - [Forum](#forum)

## Code to GUI: algorithm to user interface:
* [Screenshoot to Code](https://github.com/emilwallner/Screenshot-to-code)
* [pix2code: Generating Code from a Graphical User Interface Screenshot](https://github.com/tonybeltramelli/pix2code)
* [Bred Victor: Machine learning in Engineering inference from enviroment](http://worrydream.com/#!/MagicInk)

## Code generation: ML algorithm + Static Analysis
* [Tabnine: Autocompletion with deep learning](https://www.tabnine.com/blog/deep/)
* [Kite: Algorithm assisted coder completion ](https://kite.com/)
* Insignt:
  Standard code completion tools often still use alphabetical sorting, while Kite uses ML algorithms to infer what a developer is likely trying to do
## Image Synthesis
* [SPADE by NVlabs: Synthesizing photorealistic images given an input semantic layout](https://nvlabs.github.io/SPADE/).
  [code](https://github.com/nvlabs/spade/)

## Image Style Transfer
* [Artbreeder based on BigGAN models](https://artbreeder.com/)
   [opensource version](https://github.com/joel-simon/ganbreeder)
   [BigGAN models](https://tfhub.dev/deepmind/biggan-512/2)
   [About](https://artbreeder.com/about)
* A cool artistic project: 
... DGSpitzer(Eddie Hu) a indie game maker Use [Artbreeder based on BigGAN models](https://artbreeder.com/), StyleGAN-Artm Realistic-Neural_Talking_Head_Modelsm First-Order_Modelsm DAIN
and Topaz Lab for some great work on digital video repair, which colorize black and while video.

* A cool project: [Visual Novel using ML Style transfer](https://medium.com/@pbriod/how-i-used-artificial-intelligence-to-make-my-first-graphic-novel-about-my-trip-to-india-although-ff4af46fd6a3)
## NLP: Text-Sentiment-Analysis:
* [DeepMoji:a sentiment analysis model](https://arxiv.org/pdf/1708.00524.pdf) **This model also used in [15.ai](https://15.ai/about), a text-to-speech tool for generating voices of various characters.**

## Text-to-Image:
* dataset: [Google’s “Quick Draw” open source dataset](https://opensource.google/projects/quickdrawdataset)
  [github](https://github.com/googlecreativelab/quickdraw-dataset)

## Text-to-Video:
* AllenNLP: [Imagine This! Scripts to Compositions to Videos](https://prior.allenai.org/projects/craft)

## Image Captioning
* [Tensorflow core: Image captioning with visual attention](https://www.tensorflow.org/tutorials/text/image_captioning)

## Text-to-Animation
* [Generating Animations from Screenplays](https://arxiv.org/pdf/1904.05440.pdf)

## Text Generation/NLP
### Question Generation:
* [Question Generation: generate multiple choice answers from text](https://github.com/KristiyanVachev/Question-Generation)
### Other
* [OpenAI 1.5 billion params GPT-2 release](https://openai.com/blog/gpt-2-1-5b-release/)
* [AIDungeon](https://github.com/AIDungeon/AIDungeon)
* [ctrl-gce: CTRL text-generating model on Google Compute Engine with just a few console commands.](https://github.com/minimaxir/ctrl-gce), why google compute engine: The CTRL model is so large (12 GB on disk, 15.5 GB GPU VRAM when loaded, even more system RAM during runtime) that it will currently not fit into a free Colaboratory or Kaggle Notebook. 
* [Writing with the machine](https://www.robinsloan.com/notes/writing-with-the-machine/)
  [scifi corpus txt dataset](https://www.kaggle.com/jannesklaas/scifi-stories-text-corpus)
  Could be useful for gpt2 model fine tune
* [GPT2-Chinese-wuxiao-novel](https://leemeng.tw/gpt2-language-model-generate-chinese-jing-yong-novels.html)
* [GPT-2 Chinese](https://github.com/Morizeyao/GPT2-Chinese)
* [Hugging face Transformer]-Pytorch hub 

### Text Corpus/dataset
* [Sci-fi-Script](http://www.scifiscripts.com/)
* [Detroit-Becoming-Human](https://github.com/detroitbecometext/detroitbecometext.github.io)
   Could be source to analyze dialogue tree and decision tree structure.
   
## Audio and music generation/processing
### Project:
* [Talking like your favorite character: Text-To-Speech audio generation ](https://fifteen.ai/app)
related research:
* [Tacotron2](https://github.com/NVIDIA/tacotron2)
* [ForwardTacotron: Tacotron2 without attention](https://github.com/as-ideas/ForwardTacotron)
* Voice clone: [Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)
* [Spleeter: sound track seperation](https://github.com/deezer/spleeter)
  sound seperation is under domain of music information retrival.
* [Ambient Generative Music by Alex Bainter](https://generative.fm/)
  Although this project is not generated by algorithm, gives much inspiration in the field of music generation.
  [Medium](https://medium.com/@metalex9)
  [code](https://github.com/generative-music/pieces-alex-bainter/blob/master/packages/piece-trees/src/piece.js)
*[NeuralFunk: Sound design with ML](https://towardsdatascience.com/neuralfunk-combining-deep-learning-with-sound-design-91935759d628)

### Music-Video Synthesis
* [Deep Music Visualizer using BigGan](https://towardsdatascience.com/the-deep-music-visualizer-using-sound-to-explore-the-latent-space-of-biggan-198cd37dac9a)
  [code](https://github.com/msieg/deep-music-visualizer)

## Video Synthesis and Generation:
* [pix2pix-tensorflow: poweed interative rendereed Virtual world](https://www.youtube.com/watch?v=ayPqjPekn7g)
  [code](https://github.com/affinelayer/pix2pix-tensorflow)
   update: pretrained model added
   [more about](https://affinelayer.com/pix2pix/)
   [colab](https://www.tensorflow.org/tutorials/generative/pix2pix)
   * Using this technique we can colorize black and white photos, convert google maps to google earth, etc.

* [CRAFT, which generates cartoons based on text descritpionsa](https://arxiv.org/abs/1804.03608)
  A very creative work involved text to video generation from allen nlp
  by [researcher](http://tanmaygupta.info/publications/)
  [Project page](https://prior.allenai.org/projects/craft)
  [Video](https://www.youtube.com/watch?v=688Vv86n0z8&feature=youtu.be)

## Audio Systhesis
* [nvidia's taco2 pytorch implementation](https://github.com/NVIDIA/tacotron2)
* [real-time-voice-clone](https://github.com/CorentinJ/Real-Time-Voice-Cloning)

## ProceduralGenerationForGaming
### Map generation
* [AI-Powered Procedural Fantasy Map Generator](https://80.lv/articles/ai-powered-procedural-fantasy-map-generator/), reference: [@linonetwo's blog](https://onetwo.ren/wiki/#:%E5%9C%B0%E5%9B%BE%E7%94%9F%E6%88%90%E7%9A%84%E4%BE%8B%E5%AD%90)

## Animation
* [deep learning for character animation and control](https://github.com/sebastianstarke/AI4Animation)
* [DeepMimic: Motion imitation with deep reinforcement learning](https://github.com/xbpeng/DeepMimic)

# Distributed Training:
* [MPI Reduce and Allreduce](https://mpitutorial.com/tutorials/mpi-reduce-and-allreduce/)
   Very useful tutorial to illustrate the concept of MPT.
   CHECK [CODE](https://github.com/wesleykendall/mpitutorial/tree/gh-pages)
* Also check on [Tensorflow-core](https://www.tensorflow.org/tutorials/distribute/keras)
* [Distributed Traning strategy](https://www.tensorflow.org/guide/distributed_training)

## Computer Vision application in gaming
* [E-Sports Talent Scouting Based on Multimodal Twitch Stream Data](https://arxiv.org/pdf/1907.01615.pdf)
  [data acquisition and modeling code](https://github.com/mug31416/E-sports-on-Twitch/tree/master/data)
  [Chat Log](https://github.com/bernardopires/twitch-chat-logger)
  [Twich Stream](https://www.godo.dev/tutorials/python-record-twitch/)

## Paper with code
* [Paper with code](https://paperswithcode.com/)

## Resources on related course:
* [UIUC CS598RK: HCI for ML](https://courses.grainger.illinois.edu/cs598rk/fa2019/)
* [coursera: Sequence Models](https://www.coursera.org/learn/nlp-sequence-models/)
* [Full Stack Deep Learning](https://fullstackdeeplearning.com/)
* fast.ai
* [UIUC: ECE420 Video processing lab](https://courses.grainger.illinois.edu/ece420/fa2019/lab7/lab/)
* GPU free resource:[Setting Up a Google Cloud Instance GPU for fast.ai for Free](https://medium.com/@jamsawamsa/running-a-google-cloud-gpu-for-fast-ai-for-free-5f89c707bae6)

## Cloud computing set up
* [AWS](https://sebastianraschka.com/pdf/books/dlb/appendix_cloud-computing.pdf)
* [Google colab](https://medium.com/@mslavescu/try-live-ssd-object-detection-mask-r-cnn-object-detection-and-instance-segmentation-sfmlearner-df62bdc97d52)

## Full Stack Deep Learning tools in data processing pipeline:
* [cortex: Deploy machine learning models in production possibly without docker and kubernetes](https://github.com/cortexlabs/cortex)
   [medium](https://towardsdatascience.com/@calebkaiser)

## Resources for dev tool:
* Lumen: Video syth software
* [Dialogue tree based node editor for unity](https://github.com/Seneral/Node_Editor_Framework)
  and [example](https://github.com/Seneral/Node_Editor_Framework/tree/Examples/Dialogue-System)
  [demo](https://nodeeditor.seneral.dev/Examples.html)


## More resources on pretrained model:
 * [Pytorch hub]https://pytorch.org/hub/research-models
 * Tensorflow hub

## MEET mind-linked people in forum:
* [reddit-MediaSynthesis](https://www.reddit.com/r/MediaSynthesis/)

## Application:
### Generating voices of various characters: Ideally podcast and gaming etc:
* [15.ai](https://15.ai/about)

### FILM MAKING:
* Black Mirror: Bandersnatch
  [Show case: dialogue tree](https://www.reddit.com/r/blackmirror/comments/aajk5r/full_bandersnatch_flowchart_all_branches_story/)
* [LATE-SHIFT](https://lateshift-movie.com/)

## Design
* [Algorithm Driven Design](https://algorithms.design/)
* [Algorithm generated Logo](https://app.brandmark.io/)

## Reference:
* For details about how to represent animation architecture from software perspective
and in math. Check Chapter11-Animation System of Game Engine Architecture,2nd edition
by Jason Gregory
* [Kite's new AI model](https://techcrunch.com/2019/01/28/kite-raises-17m-for-its-ai-driven-code-completion-tool/)
