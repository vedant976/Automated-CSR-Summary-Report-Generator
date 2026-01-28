Automated CSR Summary Report Generator
Project Overview

The Automated CSR Summary Report Generator is an AI-driven automation project designed to generate concise summaries from Corporate Social Responsibility (CSR) reports. The system eliminates the need for manual review of lengthy CSR documents by using an automated workflow built on n8n and executed through Docker.

Users only need to place CSR documents in a predefined input location. The workflow automatically processes these documents and generates a structured summary report in CSV format.

Features

Automated summarization of CSR documents

Fully automated workflow with no manual interaction after setup

Centralized processing using n8n workflow automation

Structured CSV output for reporting and analysis

Scalable and reusable workflow design

How the System Works

CSR documents are placed in the input directory

n8n workflow detects and processes the documents

AI logic extracts and summarizes key CSR information

The summarized content is consolidated into a CSV file

Output is stored in the designated output directory

Setup and Installation
Prerequisites

Docker installed on the system

n8n workflow automation tool

Basic understanding of Docker and file paths

Installation Steps

Clone the repository

git clone https://github.com/vedant976/Automated-CSR-Summary-Report-Generator.git


Navigate to the project directory

cd Automated-CSR-Summary-Report-Generator


Start n8n using Docker

Import the workflow JSON file into the n8n interface

Configure input and output directory paths in the workflow

Usage Instructions

Place CSR documents in the input folder

Run the n8n workflow

Wait for the execution to complete

Access the generated summary CSV file from the output folder

Project Structure
Automated-CSR-Summary-Report-Generator/
|
├── SE_Final.json
├── Automated CSR Summarizer using n8n.pdf
├── README.md
├── input/
└── output/

Configuration Details

Input directory path must be correctly mapped in the workflow

Output directory path must be defined in the final workflow node

Ensure all required permissions are granted for file access

API keys or AI configurations (if used) must be properly set

Input and Output Format

Input

CSR documents placed in the input directory

Output

Summary generated in CSV format

Output stored in the output directory

Technology Stack

Agentic AI for document summarization

n8n for workflow automation

Docker for containerized execution

Use Cases

Corporate CSR analysis

Academic research and reporting

Automated compliance documentation

Large scale CSR data summarization

Contribution Guidelines

Fork the repository

Create a new feature branch

Commit changes with clear messages

Submit a pull request for review

License

This project is open source and intended for educational and non-commercial use. A license file can be added based on distribution requirements.
