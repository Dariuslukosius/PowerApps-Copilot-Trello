
- `images/flow.png` – screenshot of the Power Automate flow.
- `images/trello.png` – screenshot of the created Trello card.

---

## **How it works**

1. **User input**  
   - The user fills a form in Power Apps:
     - **Issue Name** (e.g., "PC Overheating")
     - **Issue Description** (e.g., "My computer gets hot and shuts down unexpectedly")
     - **App Type** (e.g., "IT App")

2. **Copilot Agent (APP Helper)**  
   - Collects the input from the user.
   - Calls the Power Automate flow.

3. **Power Automate Flow**  
   - Triggered by the Copilot agent.
   - Steps:
     1. Compose / transform user input (Issue Name, Description, App Type)
     2. Create Trello card in the selected Board and List
     3. Respond back to Copilot agent with status and card link

4. **Response to User**  
   - Copilot agent displays confirmation and optionally the Trello card URL.

---

## **Flow Sample**


