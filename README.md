# Repo-1
# Myma.ai - ChatGPT for Tourism, Hospitality & Experiences Operations

# Project Overview
Myma.ai is an innovative AI chatbot tailored for the tourism and hospitality industry. The project aims to revolutionize customer service and operational efficiency by enhancing chatbot interactions with improved memory, accuracy, and real-time functionalities such as bookings. The project is critical in addressing challenges like chatbot hallucinations and integrating contextual conversations to meet market and customer demands.

# Team Members
Prashant Goswami - Data Analyst & IT Systems Analyst & Developer
Hetvi Shah - IT Project Manager & UI Designer & Developer
Sandnya Patil - Scrum Master & Software Quality Assurance Analyst & Developer
Kangcheng Su - Software Architect & Data Architect & Developer
Sairamnath Krishnan - Business Systems Analyst & User Experience Developer
Rohit Abbireddi - Software Developer & Developer

# Setting Up the System
To begin the setup, follow the steps below:
## A. Creating the Backend Database
The backend database is hosted on Azure Cosmos DB. <br> Follow these steps to set up a NoSQL database:
Refer to the official Azure Cosmos DB documentation (https://learn.microsoft.com/en-us/azure/cosmos-db/nosql/quickstart-portal) for step-by-step guidance. <br>
Configure the database to store hotel data efficiently, ensuring proper indexing for queries related to chatbot operations.<br>
## B. Configuring the Chatbot Application
Access the application at app.bookmebob.com <br>
  - Use the provided username and password to log in.<br>
  - URL for the application: https://app.bookmebob.com<br>
  - A username and password provided by Myma.AI’s Developpment Team.<br>
* Populate the knowledge base with hotel-specific data such as:<br>
  - Room types and availability
  - Restaurant and spa services
  - Policies (e.g., cancellation, check-in/out times)
  - Nearby attractions
</br></br>
* Define the dynamic conversation flow to align with the hotel's use case. This could include FAQs, booking instructions, and service requests.
  - Step 1: Create a new conversation flow and select “dynamic flow” as flow type.
  - Step 2: Select the chatbot model for the chatbot.
  - Step 3: Include training data for the chatbot and attach the documents.
</br></br>
* Create an AI chatbot for Web integration to connect data from the knowledge hub and the dynamic conversation flow.
  - Step 1: Select the AI chatbot for web integration.
  - Step 2: Select the Demo Resort and give a name to the integration.
  - Step 3: Select the Dynamic conversation flow the user created and click on save.
</br></br>
* Create a Web integration to connect the chatbot into the customer's website  / Facebook page / WhatsApp page etc.This widget should be integrated with other hotel systems, such as printers or room service complaint receivers via APIs. The chatbot’s UI can be modified here before deployment.<br>
  - Step 1: Select the Web widget for Property website for connecting the chatbot to a website.
  - Step 2: Select the property and give it an integration name.
  - Step 3: Go to the “appearance" tab to customize the UI of the web widget created and go to the “Chatbot / contact” tab to select the chatbot we created in the previous step.
  - Step 4: Click on save buttons and Preview to test out the newly created chatbot for edge cases.
  - Step 5: Click on the preview button and test out the workflows for the room service and complaints chatbot and the event planning chatbot.

## C. Running the Application
  - After publishing the chatbot, visit the webpage of the hotel to make a complaint or plan an event.
  - The chatbot is integrated with the hotel’s website using the BookMeBob application. After configuring the chatbot’s dynamic flow and publishing it, a unique assistant ID is generated.
  - This assistant ID is used to link the chatbot with the hotel’s website via a web widget or API.


# Project Goals
The primary goal of Myma.ai is to create a more interactive, accurate, and memory-efficient chatbot that meets the demands of customers in the tourism and hospitality industry. The project is focused on delivering:
- Contextual Memory for Chat History: The chatbot will remember previous interactions and provide consistent follow-up responses.
- Accurate Information: Preventing hallucinations through advanced error-checking and validation mechanisms.
- User Experience Enhancement: Improving the interface for more intuitive and seamless user interaction.

# Key Features
Chat History Recall: Chatbot will have the ability to store and reference prior customer interactions to enhance conversation continuity.
Accurate Responses: Reducing response inaccuracies and ensuring the chatbot provides correct information.
Real-Time Booking Integration: A feature allowing customers to make real-time bookings, improving operational efficiency.
Contextual Conversations: The chatbot will adapt its context based on user interactions and event-driven market demands, ensuring relevant information is provided.

# Success Criteria
25% improvement in response time for customer service.
20% increase in customer satisfaction scores.
95% accuracy rate in chatbot responses, significantly reducing hallucinations.
30% increase in chatbot usage for hotel inquiries and bookings.

# Technologies Used
Backend: Chatbot development with a focus on advanced AI algorithms for context handling and hallucination prevention.
Frontend: User interface enhancements based on feedback to improve user experience.

# Communication Plan
Internal Communication: Microsoft Teams for daily stand-ups, project updates, and collaboration.
Stakeholders: Bi-weekly meetings with stakeholders, including the project sponsor, Andy Dharmani, and course instructors.

# Risk Management
Integration Challenges with External APIs: Addressed by implementing strict version control and continuous testing.
Chatbot Hallucinations: Mitigated through advanced training of AI models and real-time error-checking.
Data Privacy: Ensuring compliance with data protection regulations through robust security measures.

# Contact Information
Please contact ** Andy Dharmani (andy@myma.com) ** or ** Sandnya Patel (spatil23@umd.edu) ** for any support requests.

# Example:
Event or Promotion Notification Context
Trigger: When there is a new event, promotion, or deal relevant to the customer’s preferences.

Contextual Information:
Notify customers about upcoming events or promotions related to their past bookings.
Provide personalized promotions based on historical preferences or seasonal offers.

Example Dialogue:
Customer: "What events are happening in December?"
Chatbot: "Based on your interest in concerts, there’s a special music event happening on December 15th at the city center. Would you like more details?"
