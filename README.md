# Why?
If your copilot studio use case would benefit from better leverage/control of Chat History, this will likely be of interest to you.
# Pre-reqs
- A sandbox to try the solution out in
- Dataverse / Premium License
- AI Builder Credits
- An environment that has AI Builder GPT Text feature
  - GCC ✅
- An environment that has Copilot Studio Generative Answers
  - GCC ⛔
  - This is order to showcase GPT fallback with generative answers. You technically can leverage this pattern without generative answers, it just breaks the demo. Reach out for more details.

# Deployment Steps
- Download the latest release from the releases area which consists of:
  - the solution zip file
  - an employee data import csv
- Import the solution in your target environment
- Go to the Employee Data Table in said environment
- Click "Import from Excel" and browse to the downloaded import csv
- Go to the Bot called ChatGPTish in the solution and test it out

# The Script
There's a lot of ways you can demo this thing, but here's a good baseline of 5 questions to ask with tracing turned on:
1. Provide me a list of annual employee salaries 
2. what is the sum of annual salaries?
3. what is the average?
4. what is the name of the popular electric type pokemon?
5. summarize the conversation
