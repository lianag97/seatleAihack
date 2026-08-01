# seatleAihack
Seattle AI hackathon
Goal: help users organize task lists into actions to approve/reject/edit
Setup & Installation: Use Gemini to prompt engineer a working web app with approve/reject/edit controls that takes in an input of a task list and returns actions based on that task list. human must approve/reject/edit before finalization. actions are recorded for each item.
Execution: take sample task list and feed it into gemini and web app
Demo instructions: feed task list into web app and receive action items to approve/reject/edit
Architecture & Workflow: gemini creates code to create web app --> create task list --> feed task list into web app --> approve/reject/edit action items --> web app logs actions
Trust/safety feature: approve/reject/edit buttons for each item, human control
