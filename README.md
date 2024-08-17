# Investment Evaluation by Funds Using LLM
This project, developed using Google Colab, aims to create a Large Language Model (LLM) to evaluate wheter an investment fund can invest in a specific type of asset according to current regulations.

## Project Description
The goal of the project is to create a system that uses LLM to answer questions related to investment regulations. The system will be able to determine if a fund can invest in a specific asset, taking into account Brazilian laws and regulations.

## Project Structure

1. Database Construction
  - Question and Answer Database: Create a  database that coains both easy and difficult questions, along with the answers and the process of understand each answer.

2. Prompt Writing
  -  Define and write the prompt for the model.

3. Law Importation
  - Import the brazilian regulation for funds (CVM 175) and fund prospectus
    
4. Model Testing
  Models to Test:
    - Native GPT: Comparison between different models.
    - Native GPT + prompt training with the modeling database.
    - Agents.
    - RAG (Query).
    - Agents + Memory (chat) + prompt training.
      

5. Code
   
  The code developed in Google Colab is divided into the following sections:

a. Law and Regulation Importation
  - Code to import and process the necessary laws and regulations.

b. Native GPT
  -Refinement of the prompt for the native GPT model.

c. Agents
  - Agent implementation

d. Tool for Importing Fund Regulations
  - Create a tool for importing fund regulations.

e. Prompt Refinement
  - Adjustments and improvements to the prompt for different test scenarios.

f. Test Importation
  - Importing test data to a .xlsx file.


6. Test Database
   
A test table will be used with the following columns:
- Fund Name
- Asset Name
- Allowed (whether the fund can invest or not)
- Difficulty (1 to 5)


7. Requirements
   
Google Colab: To run the code and perform the tests.
GPT Model: Access to the GPT model to run the tests.
.xlsx File: File containing the test database.


License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For more information or questions, contact via gigi.bduarte@gmail.com
