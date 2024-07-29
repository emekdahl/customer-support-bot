# customer-service-bot

# How to Develop

Copy `.example_env` to a file named `.env` and populate the environmental variables. 

Right now the customer support bot is running with OpenAI. You can select either OpenAI or Claude and make updates as appropriate to the env vars.

Go to the Jupyter Notebook, make sure you have the correct ipykernel selected: `customer-support-bot`. If it doesn't exist, you may need to create the virtual environment and ipykernel either in the notebook or with the terminal.

Run all cells.

There's a known bug where one of the tool calls doesn't work as expected; however, you can see most of the conversation.
