# IT3213P_HCI_Day02
summary of Basic_Calculator - Day 02 progress:

Basic Interface & Number Pad Interactions
Interface Design
- Created a basic layout with:
  - A calculator screen
  - Number pad (buttons 0–9)
  - (Operation buttons will be added later)

Variable Setup
- Flag= Replace(determines input behavior)
- Saved Number = ""(holds current input)

Number Button Interactions
-For Numbers 1–9:
  - If Flag = "Replace":
    - Replace screen text with clicked number (`This.text`)
    - Set Flag to "Join"
  - If Flag = "Join":
    - Append clicked number to screen text (`Target.text + This.text`)

-For Number 0:
  - Same logic as above, but initializes screen to `"0"` when replacing.


This wraps up the basic number input and UI interaction for your calculator. 