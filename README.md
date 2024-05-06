# Cognitively-Inspired-LLM-using-Curriculum-learning-
Does cognitively inspired learning allow large language models to learn efficiently?

##Abstract
The scale at which the size of LLMs is increasing is huge. Various state-of-the-art models like GPT-4, Bard, Gemini have been trained on terabytes of data. Despite being on such large datasets, these models fail to do simple math, plan approaches to solve problems and still suffer from catastrophic. Their huge size also makes these models a black box which is very different to understand. Training such large language models is infeasible for any university or academic institution. Cognitively inspired learning tries to alleviate some of the concerns addressed. In this project, we use the popular approach of Curriculum learning on three datasets with three different configuration settings. We find that using curriculum learning on small datasets allows models to converge quickly and train faster.

*Keywords: state-of-the-art, curriculum-learning, llms, cognitively-inspired-learning*

##To run
To reproduce the results that we have obtained, add your project ID (that you can use on BigRed200) in nanogpt-gpu-debug.sh and nanogpt-gpu.sh depending on which partition you wish to your code on.

Before running this shell file, install the requirements from training/requirements.txt. Instructions are listed in the training/README.md

chmod +x training/submit_all.sh
./training/submit_all.sh
Acknowledgement

This research was supported in part by Lilly Endowment, Inc., through its support for the Indiana University Pervasive Technology Institute.
