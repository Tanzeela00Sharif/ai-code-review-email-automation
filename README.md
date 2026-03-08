# ai-code-review-email-automation
# AI Code Review Email Automation

This project automates code review using AI.

## Workflow

1. User sends code via Gmail
2. Gmail trigger activates workflow
3. Google Gemini analyzes the code
4. AI generates:
   - Code summary
   - Code comments
5. Results are merged
6. Final formatted response email is sent to the user

## Tools Used

- Gmail API
- Google Gemini
- Workflow Automation
- Prompt Engineering

## Input

Email containing code snippet.

Example:

Subject: Review My Python Code

def add(a,b):
return a+b


## Output

Automated reply email:

Code Summary:
This function adds two numbers.

Code Comments:
Line 1: Function definition
Line 2: Returns sum of numbers
