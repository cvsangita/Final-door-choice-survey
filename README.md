# Predicting Passenger’s Vehicle Door Choice in Subway Transportation

This project investigates the factors influencing subway passengers’ choice of vehicle doors during boarding, with the aim of reducing station dwell times and improving passenger distribution. By combining Discrete Choice Experiments (DCEs), dynamic image generation, and a Streamlit-based survey application, the study provides a robust framework for analyzing boarding behavior in urban rail systems.

📌 Project Overview

Uneven passenger distribution across train doors contributes to congestion and increased dwell times in metro systems. This project uses a stated preference survey with dynamically generated visual scenarios to model passenger choices at the door level.

Key research objectives:

Design a realistic Discrete Choice Experiment (DCE) incorporating spatial, crowding, and contextual factors.

Generate dynamic, visually realistic platform images programmatically.

Deploy an interactive Streamlit survey application with Google Sheets integration.

Estimate a Multinomial Logit (MNL) model to analyze passenger preferences.

Provide insights for operational interventions such as signage, real-time crowding information, and incentive schemes.

🛠️ Tech Stack

Python – data processing, modeling, image generation

Pillow (PIL fork) – programmatic image creation and compositing

Streamlit – interactive web-based survey interface

Google Sheets API – real-time data storage

Jupyter Notebooks – prototyping and development

Choicedesign / Biogene – choice modeling and estimation
