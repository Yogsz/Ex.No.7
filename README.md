# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 9/10/2025
# Register no: 212223060312
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
Build a full-stack web application called Project Task Breakdown. The app should help users convert high-level project ideas into detailed, structured task breakdowns with subtasks, dependencies, and effort estimates.

Core Features:

User authentication (login/signup with JWT).
Create, view, update, and delete projects.
For each project, allow creation of tasks and subtasks (hierarchical structure).
Support task details: title, description, status (To-Do, In-Progress, Done), assignee, priority, estimated time, and due date.
Allow dependencies between tasks and prevent circular dependencies.
AI-powered task suggestion: given a high-level task description, automatically suggest subtasks with descriptions and estimated effort.
Display tasks in multiple views: Task Tree (hierarchical), Kanban board, and simple Gantt timeline.
Export project plan to CSV or PDF format.
Real-time sync for team collaboration using WebSockets.

Technical Requirements:

Frontend: React + Tailwind CSS.
Backend: Node.js + Express (or Python FastAPI).
Database: PostgreSQL (with parent_id for subtasks).
AI integration: Use an API call (like OpenAI or local LLM) to generate subtasks.
Deployment: Dockerized app with a simple README for setup.
Bonus Features (if time permits):
Role-based access (Owner, Editor, Viewer).
Comments and file attachments per task.
Progress tracking dashboard (% completed).
Project templates for common workflows.

Goal:

Create a visually clean and easy-to-use web app where a user can:
Create a project
Add high-level tasks
Auto-generate subtasks using AI
Reorganize tasks visually
Export or share the breakdown

# Output: <img width="1310" height="783" alt="image" src="https://github.com/user-attachments/assets/ef545350-ddc6-4b75-9bfb-0c1023d07128" />


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
