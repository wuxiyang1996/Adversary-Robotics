# On the Safety Concerns of Deploying LLMs/VLMs in Robotics: Highlighting the Risks and Vulnerabilities

This repository is the codebase for our paper.

[**On the Safety Concerns of Deploying LLMs/VLMs in Robotics: Highlighting the Risks and Vulnerabilities**](https://arxiv.org/abs/2402.10340)

Project Website: **https://wuxiyang1996.github.io/adversary-vlm-robotics/**

The codebases we implemented adversary attacks are 
[**KnowNo**](https://github.com/google-research/google-research/tree/master/language_model_uncertainty)
and
[**VIMA**](https://github.com/vimalabs/VIMA).
The GPT model used for prompt attack is ```gpt-3.5-turbo-instruct```.
Necessary changes are made to each codebase.

## The Problem
The use of LLMs/VLMs has revolutionized how we interact with robots, offering unprecedented levels of understanding and 
responsiveness. But at what cost?
<p align="center">
    <img src="images/problem.gif"><br/>
</p>

## The Risk
We uncover how these advancements while being impressive, expose robotic systems to even simple adversarial attacks, 
threatening their reliability and safety.
<p align="center">
    <img src="images/risk.gif"><br/>
</p>

## The Attack
Multi-modal Attacks to LLMs/VLMs in Robotic Applications. The middle pipeline is an abstract robotic system with 
LLMs/VLMs, and multi-modal attacks are applied at visual and text prompts. The left-hand side provides different 
attacks to images, such as reducing image quality, applying transformation, and adding new objects. The right-hand side 
shows different types of attacks in text, including simple rephrasing, stealth rephrasing, extension rephrasing, and 
rephrasing of adjectives and nouns.
<p align="center">
    <img src="images/method.png"><br/>
</p>

## Installation
Coming Soon.

## Citation
```
@article{wu2024safety,
  title={On the Safety Concerns of Deploying LLMs/VLMs in Robotics: Highlighting the Risks and Vulnerabilities},
  author={Wu, Xiyang and Xian, Ruiqi and Guan, Tianrui and Liang, Jing and Chakraborty, Souradip and Liu, Fuxiao and Sadler, Brian and Manocha, Dinesh and Bedi, Amrit Singh},
  journal={arXiv preprint arXiv:2402.10340},
  year={2024}
}
```