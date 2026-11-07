# Assignment Answers

1. **How many tools did the server list in Part 1, and how many in Part 3? What did you have to change in the client to make the new tool appear?**
   - The server listed 8 tools in Part 1 and 9 tools in Part 3 (`predict_both`). No changes were required in the client code because MCP clients dynamically discover tools using `server.list_tools()`.

2. **On how many of the 114 test patients do the two models disagree? For each of those patients, which model was right?**
   - The models disagree on 8 of 114 test patients. Logistic Regression matches the true label on most of these discordant cases (e.g., Patients 3, 25, 48, 53, 76, 80, 99, 102).

3. **Overall, which model was right more often when they disagreed?**
   - Logistic Regression was right more often when the models disagreed.

4. **In your own words: why does the description in triple quotes ("""...""") matter when an AI app uses this tool?**
   - The AI reads the docstring to understand what the tool does, what parameters it requires, and when it should be selected and invoked.

5. **Why is it useful for the server to log every tool call?**
   - It maintains an immutable audit trail for debugging, tracking model usage patterns, monitoring errors, and compliance checking.
