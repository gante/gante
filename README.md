<!-- Must be saved without formatting, i.e. CMD+K -> S -->
### Hello there 👋

I'm a member of the OS team at Hugging Face 🤗, expanding what's possible with text generation (PT/TF/JAX). I have a PhD in ML applied to 5G signal processing 📡 and I've applied ML to several modalities (text, image, graphs, time-based signals) and industries (telecom, construction, software).

Here are a few interesting open projects and publications I've been part of, by industry:

🤖 Software
1. [Hugging Face](https://huggingface.co/) 🤗  
  1.1. 100x faster TensorFlow text generation with XLA ([blog post](https://huggingface.co/blog/tf-xla-generate), [twitter thread](https://twitter.com/joao_gante/status/1555527603716444160), [TensorFlow blog](https://blog.tensorflow.org/2022/11/how-hugging-face-improved-text-generation-performance-with-xla.html));  
  1.2. PT ➡️ TF safe weight conversion CLI ([twitter thread](https://twitter.com/joao_gante/status/1540350265890684930));  
  1.3. Assisted Generation -- faster text generation with the aid of a smaller model ([blog post](https://huggingface.co/blog/assisted-generation), [twitter thread](https://twitter.com/joao_gante/status/1656697682646429696));  
  1.4. ...and many others. A repo with personal notebooks can be found [here](https://github.com/gante/huggingface-demos).

🏗 Construction
1. [nPlan](https://www.nplan.io/)  
  1.1. Forecasting delays in construction projects' activities. When modeled as a classification problem, learning arbitrary delay distributions for each input becomes possible ([paper](https://link.springer.com/chapter/10.1007/978-3-031-08223-8_9));  
  1.2. Exploring aleatoric vs epistemic uncertainty with [Monte Carlo Dropout](https://arxiv.org/abs/1506.02142v6) and ensembles ([some code](https://github.com/nitbix/toupee)), and estimating their impact on forecasts.

📡 Telecommunications
1. [Square Kilometer Array](https://en.wikipedia.org/wiki/Square_Kilometre_Array)  
  1.1. Accelerating FIR filters using OpenCL, on FPGAs ([paper](https://ieeexplore.ieee.org/abstract/document/7828456/), [code](https://github.com/gante/OpenCL-FPGA-FIR-Filter));
2. Positioning (PhD)  
  2.1. Designing new signals that can be collected from 5G communications, which contain spatial information about the surroundings ([paper](https://ieeexplore.ieee.org/document/8690987));  
  2.2. ML modeling (DNNs, CNNs, LSTMs, and [TCNs](https://arxiv.org/abs/1803.01271)) can then be used to convert that signal in 2.1. into the receiver's position, while being as accurate, but much more energy efficient, than the GPS ([paper](https://ieeexplore.ieee.org/document/9080126), [code](https://github.com/gante/mmWave-localization-learning));  
  2.3 Using [Monte Carlo Dropout](https://arxiv.org/abs/1506.02142v6) to estimate the uncertainty of the position predictions from 2.2. ([paper](https://ieeexplore.ieee.org/abstract/document/9626568), [code](https://github.com/gante/mmWave-localization-learning)).


Feel free to reach out using the contacts on this profile.
