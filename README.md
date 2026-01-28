# Automated-CSR-Summary-Report-Generator

A course level project, powered by Agentic AI, which generates CSR Summaries.
This particular project contains the JSON code for the AI Workflow which is implemented in n8n through Docker.
The file can be imported into the n8n and user can get the workflow directly on their screens.
The user has to create their credentials to be able to operate the workflow and get their summaries.
The input folder has to be created and the path has to be set up in n8n, where you have to create a folder of input and output.
The final node's path has to be mapped to the output folder in the device memory.
Add some CSR Reports in the input folder and then run the workflow.
You will receive your desired output in the form of a CSV file in the output folder.
