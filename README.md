# [Kaggle Code link](https://www.kaggle.com/arghyadeeppaul07/report-generator-multiple-files)

# Design Decisions

Using the advent in LLMs & the likes of **GPT-4** & **CodeLlama-2** to make learning a better experience for all

**Sample Usage** (Submitted Code does not include a hosted app) :

![Alt text](https://github.com/arghyadeeppaul/Updates/blob/main/image.png?raw=true "Sample Usage")


•Using LLM **(CodeLlama-7b-Instruct-hf)** for finding errors with code, giving completion score & find thought process of students

**Reasons to use CodeLlama-7b-Instruct-hf:**

•out of 7b,13b,34b, and 70b models ideally, the most accurate results would be given by 70b parameters model & 34b model gives the best mix of speed and accuracy

•we use 7b model due to **computational resources limits** (20 gb GPU VRAM limit)


**OTHER DESIGN DECISIONS:**  
• Enabled History to implement a chain-of-thought processing system  
• Did not use LangChain to implement chain-of-thought to allow easier readability and lesser coding complexity  
• All other Designing Decisions are well Documented in the codes themselves  

## Other than the final code, 2 other folders, 'Proof of Concept' & 'ONE-FILE-EXAMPLE', are provided for proof of concept testing and sample inference & report generation using one code file


# Instructions to Run your Program:
• USE THIS GIVEN LINK TO FIND PROGRAM: **[Kaggle CODE LINK](https://www.kaggle.com/arghyadeeppaul07/report-generator-multiple-files)**  
• ADD THE WHOLE REPOSITORY AS A ZIP FILE AS THE DATA INPUT & RUN  
• MAKE SURE TO SELECT THE ACCELERATOR **AS GPU T4 x2**  
• TO DOWNLOAD ZIP FILE CAN USE THIS LINK : **[.zip FILE LINK](https://github.com/arghyadeeppaul/Updates/blob/575c9f91c1292137ee03351e979e7361e4c102ad/psychic-invention-main.zip)**  

# Other Notes:  
I was facing issues in committing changes to the given repo, so I have done so in my own repo named **[Updates](https://github.com/arghyadeeppaul/Updates).**  
Please check for version histories and regular snapshots  in it if needed.  
•Model performs better with Python codes than Java unless models with more parameters are used with more GPU Resources : 13b, 34b, 70b  

## Make Sure to check the final reports and code in **[FINAL CODE (REPORT GENERATOR) + SAMPLE REPORTS](https://github.com/2Sigma-Careers/psychic-invention/tree/05f3b74c101a239d761d32aed8594fad4fbbfaf5/FINAL%20CODE%20(REPORT%20GENERATOR)%20%2B%20SAMPLE%20REPORTS)**

# References Used

• [HUGGINGFACE](https://huggingface.co/codellama/CodeLlama-7b-Instruct-hf)  
• [REPLICATE AI](https://replicate.com/meta/codellama-7b-instruct)  
• [KAGGLE](https://www.kaggle.com/)  
• [CHATGPT](https://chat.openai.com/share/ba1b401e-0bd5-42c8-a0b0-095686d3d15b)  

**We can also use fine-tuning with teachers feedbacks available and make the outputs better**
