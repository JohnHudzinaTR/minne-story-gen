# MinneAnalytics Story Generation Repo


## Suspenseful Stories

[A notebook with prompts](https://github.com/JohnHudzinaTR/minne-story-gen/blob/main/examples/goal_oriented_gen.ipynb) to generate a supenseful store based on a goal, actions, reasons why the act fails. 

Background Setup Prompts:

- The protagonist name & occupation 
- The goal they want to achieve
- The consequence of not achieving the goal

Introduction Prompt:

- Based on the background, generate an introduction

Action - Suspense Prompts:

- Step 1: Action to achieve the goal
- Step 2: Reason they fail
- Repeat action prompts with past actions as inputs

For an example story, [look here](https://github.com/JohnHudzinaTR/minne-story-gen/blob/80af4a811ef2f97be490b6bb684b7a1362bda591/examples/story.md). 


Example prompts based on: 

[Xie, K., & Riedl, M. (2024). Creating Suspenseful Stories: Iterative Planning with Large Language Models](https://doi.org/10.48550/arXiv.2402.17119)


## Installation

```
poetry install
```