# SLU Football Tackle Analytics
## Tackle Efficiency Study: A Look at Level 2 vs Level 3 Tackle Efficiency

This repository contains the working materials for my tackle efficiency study built around St. Lawrence University football.

I am approaching this like a coach who also speaks statistics. The goal is not to recreate any public grading product. It is to build a clear, repeatable way to evaluate tackling on film, connect those observations to outcomes, and turn it into something that can actually support coaching decisions.

## What this project is doing

Tackling is one of those areas where the “result” (made the tackle or did not) hides a lot of what mattered on the rep.

This project focuses on:
- Defining film based tackle process indicators (what happened before contact, at contact, and through the finish)
- Studying how those indicators relate to outcomes and efficiency
- Building a framework that can be used consistently across games and players

The deliverables live in two places:
- Jupyter notebooks for cleaning, analysis, and visuals
- A written report in the `reports/` folder that summarizes the study and findings

## Repository structure

- `notebooks/`
  - Data prep, feature creation, analysis, and visualization
  - Any modeling or statistical testing used in the study
- `reports/`
  - The written report for the project (PDF)
- `README.md`
  - Project overview and instructions

## How to run the notebooks

1. Clone the repo
   ```bash
   git clone https://github.com/jlars88/SLU-Football-Analytics.git
   cd SLU-Football-Analytics
