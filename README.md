# SDS210-ZWN_emotional_metrics
This project analyzes the emotinal state of Request descriptions from Züri Wie Neu in 2025 through the three emotional metrics "Importance", "Annoyance" and "Frustration". 

## Objective
The goal of this project is to analyse the respons from a single year to see which Kreis of zurich put gighest importance on their Issues, is most annoyedd by them and  ultimately most Frustrated about the current circumstances. 

## Data Sources
• **Request**  informations: Geodataframe provided by the City of Zurich
• **City  and Kreis Boundaries**: Vector Kreis layers provided by the City of Zurich. 


## Reproducing the Environment
This project requires a specific spatial software stack. To recreate the environment:
1. Ensure you have Conda installed.
2. Run: `conda env create -f environment.yml`
3. Activate: `conda activate ZWN-emotions-env`

## Usage
Execute the Jupyter Notebook `SDS_NL_Zueri_wie_Neu_analysis.ipynb` from top to bottom. Visulisations will be exported to `outputs`.
