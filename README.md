# Automated CSR Summary Report Generator

## Project Overview
- The Automated CSR Summary Report Generator is an AI-driven automation project designed to generate concise summaries from Corporate Social Responsibility (CSR) reports.
- The system eliminates the need for manual review of lengthy CSR documents by using an automated workflow built on n8n and executed through Docker.
- Users only need to place CSR documents in a predefined input location and the workflow generates a structured summary in CSV format.

## Features
- Automated summarization of CSR documents
- Fully automated workflow after initial setup
- Workflow orchestration using n8n
- Structured CSV output for reporting
- Scalable and reusable design

## How the System Works
- CSR documents are placed in the input directory
- n8n workflow processes the documents
- AI extracts and summarizes key CSR information
- Consolidated summary is generated in CSV format
- Output is stored in the output directory

## Setup and Installation
### Prerequisites
- Docker installed
- n8n workflow automation tool
- Basic understanding of Docker and file paths

### Installation Steps
- Clone the repository
- Navigate to the project directory
- Start n8n using Docker
- Import the workflow JSON file
- Configure input and output directory paths

## Usage
- Place CSR documents in the input folder
- Run the n8n workflow
- Wait for execution to complete
- Access the summary CSV file in the output folder

## Project Structure
Automated-CSR-Summary-Report-Generator/
- SE_Final.json
- Automated CSR Summarizer using n8n.pdf
- README.md
- input/
- output/

## Configuration
- Configure input directory path in workflow
- Configure output directory path in workflow
- Ensure file permissions are set correctly
- Set API keys if required

## Input and Output
- Input: CSR documents in input directory
- Output: Summary CSV file in output directory

## Technology Stack
- Agentic AI
- n8n
- Docker

## Use Cases
- Corporate CSR analysis
- Academic research
- Compliance documentation
- Automated CSR reporting

## Contribution
- Fork the repository
- Create a feature branch
- Commit changes
- Submit a pull request

## License
- Open source for educational and non-commercial use
