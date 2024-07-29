# customer-service-bot

## How to Develop

Copy `.example_env` to a file named `.env` and populate the environmental variables. 

Right now the customer support bot is running with OpenAI. You can select either OpenAI or Claude and make updates as appropriate to the env vars.

Go to the Jupyter Notebook, make sure you have the correct ipykernel selected: `customer-support-bot`. If it doesn't exist, you may need to create the virtual environment and ipykernel either in the notebook or with the terminal.

Run all cells.

There's a known bug where one of the tool calls doesn't work as expected; however, you can see most of the conversation.


## Resources

[Original Video Tutorial](https://www.youtube.com/watch?v=b3XsvoFWp4c)

Additional Resources:
- [Tutorial Code](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbV9ueUotdFRUXzVfUWpkMmtaLVBoOTJWMkhmQXxBQ3Jtc0tsYXdma2tNQmNjb294S0N6VDJuQ0tJOVB6UTZBM0pkdHByMlJTMjg0azEzQ1o2Nm9xa01qQ0V6MUxMaVJBNE5qekp0OTQ4ajhoUmlwTUZNZ2RUejQ5Qm5SNWwwcndYaFVEZkFHekprZ2dFLUxoVXQ4dw&q=https%3A%2F%2Flangchain-ai.github.io%2Flanggraph%2Ftutorials%2Fcustomer-support%2Fcustomer-support%2F&v=b3XsvoFWp4c)
- [LangGraph Documentation](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjU4QUZ4Szc1Zm5pT2EySTVvUUZqSFhOWVpNUXxBQ3Jtc0trd3A1cnRRSGpFM0t0OVNmNjZDSWZ6NVZPSVJxelgySno5U2dpRVZDd0tOejNORDlaWHhTdVhKV0oyNWVpU3AzeGgySHY4ZWp4OHphQjVjcmRZVXNGajFSdDhDQUc4emZYY3F2dUo0RFdiN2hRRVJOQQ&q=https%3A%2F%2Flangchain-ai.github.io%2Flanggraph%2F&v=b3XsvoFWp4c)