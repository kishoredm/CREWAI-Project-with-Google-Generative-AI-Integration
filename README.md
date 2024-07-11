# CREWAI-Project-with-Google-Generative-AI-Integration
This project demonstrates the integration of the CREWAI framework with Google's Generative AI to automate customer service responses. The system consists of multiple agents, each responsible for handling specific tasks and inquiries. The agents work together to receive user input, process it, and provide accurate and relevant responses.

# Agents:

Router Agent
Role: Direct user requests to the appropriate department agent.
Goal: Correctly delegate the request based on its nature.

Marketing Department
Role: Handle marketing-related inquiries.
Goal: Provide marketing strategies, market analysis, and promotional activities.

Development Department
Role: Handle development-related inquiries.
Goal: Provide technical solutions and advice.

Testing Department
Role: Handle testing-related inquiries.
Goal: Provide quality assurance strategies and practices.

Sales Department
Role: Handle sales-related inquiries.
Goal: Provide sales strategies and client management advice.

HR Department
Role: Handle human resources-related inquiries.
Goal: Provide HR policies and management advice.

Grader Agent
Role: Evaluate the responses from department agents.
Goal: Ensure responses are accurate and free from hallucinations.

Answering Agent
Role: Deliver the final response to the user.
Goal: Provide a validated response to the user.

Feedback Agent
Role: Collect user feedback.
Goal: Process user feedback for system improvement.

# Tasks
Router Task: The router agent receives user input and delegates it to the appropriate department agent.

Marketing Task: The marketing agent handles marketing-related inquiries and provides relevant information.

Grader Task: The grader agent evaluates responses to ensure accuracy and sends the final answer to the answering agent.

Answering Task: The answering agent delivers the final response to the user.

Feedback Task: The feedback agent collects and processes user feedback.

#Feedback Collection
User feedback is collected after each interaction and saved in the feedback.txt file for further analysis and improvement.
