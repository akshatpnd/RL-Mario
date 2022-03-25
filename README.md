# RL-Mario

## Introduction
As I further my journey into the realm of Reinforcement Learning, I cam across [OpenAI Gym](https://gym.openai.com/) and was fascinated by the possibilities it provided for testing out RL algorithms. Additionally, I found that there existed a SuperMario environment. Hence, I decided what better way to practice than try and teach a model how to play Mario.

## Background
Most of the setup for this project comes from the documentation for [Mario](https://pypi.org/project/gym-super-mario-bros/) and [OpenAI Gym](https://gym.openai.com/docs/#environments). In addition, I utilized the [PPO](https://openai.com/blog/openai-baselines-ppo/) algorithm which in very simple terms aims to conservatively update the policy while working with the KL divergence as a penalty term rather than a constraint. The model is then trained over 1000000 steps.

## Results and Next Steps
One big positive from this was that my laptop didn't die! Otherwise, by the 800000 step mark Mario was able to somewhat reliably complete the first level. I am certain that by better tuning I could make it so that it could go further; however, I do not possess the resources to really allow for much more training without risking the death of my laptop. Furthermore, I aim to better understand the PPO algorithm and implement it myself.
