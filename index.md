__Student:__ Dallas Plunkett\
__Email:__ [dmplunkett@ucsd.edu](dmplunkett@ucsd.edu)

__Section:__ B21\
__Mentor:__ Albert Hsiao

__What is the most interesting topic covered in your domain this quarter?__

The use of convolutional neural networks (CNNs) to help radiologists more consistently identify pulmonary edema. I found it surprising how much disagreement exists between radiologists when grading edema severity. This makes it clear why assistive AI tools could be valuable in clinical workflows. Seeing how CNNs trained on radiographic data and serum biomarkers like BNP and BNPP can reach or even exceed radiologist performance makes this a particularly compelling direction for medical AI research.

__Describe a potential investigation you would like to pursue for your Quarter 2 Project.__

I’d like to investigate how different quantization strategies—specifically Post-Training Quantization (PTQ) and Quantization-Aware Training (QAT)—affect model accuracy and interpretability for radiographic CNNs like ours. Since our current setup trains a ResNet-based model on chest X-rays to infer BNP/BNPP, comparing these quantization methods could reveal trade-offs between performance and model efficiency. This could be especially relevant for deploying medical imaging models on limited hardware in clinical environments, where precision and cost both matter.

__What is a potential change you’d make to the approach taken in your current Quarter 1 Project?__

I’d be more deliberate about documenting experiments and their outcomes as I code. It’s easy to iterate quickly on model setups, learning rates, and data transforms, but those small insights—why a configuration worked or didn’t—are easy to lose without structured notes. Having better records of metrics, parameter settings, and qualitative observations would make it much easier to interpret results and write a strong final analysis later.

__What other techniques would you be interested in using in your project?__

Since our project replicates a CNN-based medical imaging study, I’d like to explore more explainability and introspection methods—especially activation visualization techniques such as Grad-CAM, XRAI, and saliency maps that were used in the original paper. These methods help us understand what parts of an X-ray the CNN focuses on and whether that aligns with clinical expectations. Extending this with quantitative attention metrics (like lung area attention or blur sensitivity) would make our model more interpretable and clinically trustworthy.
