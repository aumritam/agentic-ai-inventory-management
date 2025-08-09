# Inventory Forecasting & Review with CrewAI
Developed during my internship at Cognizant, this project uses CrewAI with Together AI’s LLM to automate inventory forecasting for Sysco Wholesale Food Distrubutor. Three specialized agents analyze CSV data, update predictions, and perform QA reviews, streamlining workflows and reducing manual effort.

# Overview
Prime Priority Two Crew is a multi-agent AI system built using the CrewAI framework. It processes inventory forecast CSV data, updates projections, and provides automated MINT recommendations with a final human QA review step — all in a sequential workflow. This system was created during my internship at Cognizant, where I applied cutting-edge AI tools to solve real-world business challenges in inventory management.

# Features
Inventory Analyst: Reads and interprets weekly inventory data.

Forecast Specialist: Calculates updated forecasts and flags needed inventory requests.

Human QA Agent: Reviews AI decisions to ensure they meet policy and accuracy standards.

CSV Data Processing: Automatically reads and preprocesses uploaded forecast files.

Together AI LLM Integration: Leverages mistralai/Mixtral-8x7B-Instruct-v0.1 for natural language reasoning.

# How It Works
Data is preprocessed by process_forecast_csv().

Agents execute their roles in sequential order:

Analyst → Forecaster → Reviewer.

Final recommendations are returned for business decision-making.

# Benefits
Speeds up the inventory review cycle.

Reduces manual calculation errors.

Keeps a human in the loop for final approval.

Easily extendable for other operational workflows.

Demonstrates how AI can be applied in a corporate setting like Cognizant to enhance productivity.
