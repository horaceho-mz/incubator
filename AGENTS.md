
# Instructions

Unless you (the agent) have direct browser automation control, follow these rules when asking the developer 
to test code or retrieve game state data:

1. **Provide a Snippet:** Give a standalone JavaScript snippet ready to paste into Chrome DevTools Console (`F12` -> `Console`).
2. **Specify Timing:** Explicitly state *when* to execute the snippet (e.g., "Run this while on the main menu" or "Execute immediately after the game over screen appears").
3. **Format Output:** Ensure the snippet logs clean, formatted data (e.g., using `console.log(JSON.stringify(..., null, 2))`) so the user can easily copy the output back to you.