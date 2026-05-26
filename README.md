# Adaptive Fitness & Nutrition MAS
Developed by Yash Purwar.

## Overview
This is a Multi-Agent System (MAS) that dynamically generates health plans.
It uses **Llama 3 (via Groq)** and **Tavily API** to fetch real-time data from **ExerciseDB** and **USDA FoodData Central**.

## Agent Workflow
1. **Researcher Tool:** Queries ExerciseDB and USDA databases.
2. **Coach Agent:** Designs workout based on research.
3. **Nutritionist Agent:** Designs diet based on USDA profiles.
4. **Medical Auditor:** Dynamically adjusts the plan for safety based on injuries.

## Setup Instructions
1. `pip install -r requirements.txt`
2. Enter your `GROQ_API_KEY` and `TAVILY_API_KEY` in the code.
3. Run `python main.py`.
