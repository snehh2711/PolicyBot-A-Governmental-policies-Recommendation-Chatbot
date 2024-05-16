# PolicyBot-The-Governmental-policies-Recommendation-Chatbot

## Developed by : Sneha S, Vaishnavi M Wadawadagi

**Demo Link :** https://drive.google.com/file/d/1YaQAu3ZzFgCbCKfrBl1eYjYHHQ18nNRF/view?usp=sharing

In the complex tapestry of Indian governance, navigating the intricate web of policies can be a daunting task, especially for those not versed in the jargon-filled language of bureaucracy. From the bustling urban centers to the farthest reaches of rural India, individuals often struggle to access, understand, and leverage governmental policies meant to aid and protect them. This gap in accessibility can lead to missed opportunities and unclaimed benefits, perpetuating cycles of disadvantage and inequity. Enter PolicyBot, a pioneering chatbot designed to democratize access to governmental policy information.

PolicyBot stands as a beacon of innovation in the digital governance landscape, being the first of its kind to specifically address the complexity of governmental policies through advanced artificial intelligence. As the first of its kind, PolicyBot uses advanced AI to translate bureaucratic language into clear, actionable insights, providing personalized guidance tailored to individual needs. Available in multiple formats—text, and voice.PolicyBot ensures comprehensive accessibility, empowering a diverse range of citizens to engage actively with governance and claim their rightful benefits.

# Features

- **Natural Language Understanding:** Uses NLP to understand and process user queries.
- **Personalized Recommendations:** Provides recommendations based on user inputs like location, gender, and more.
- **Accessibility:** Designed to be accessible to a broad audience, ensuring that all users can navigate through complex policy information.
- **Comprehensive Dashboard:** Utilizes Tableau for creating dynamic and interactive dashboards to visualize policy data.

# System Architecture

- **Backend:** Built with Python and Django, utilizing libraries like NLTK for NLP tasks and scikit-learn for machine learning.
- **Data Handling:** Uses Pandas for data manipulation and Beautiful Soup for web scraping governmental data.
- **Frontend:** Streamlined user interface designed with Google Dialogflow and Django, offering a seamless user interaction experience.
- **Database:** MySQL for robust data management and efficient query handling.

# Home Page with Chatbot
![image](https://github.com/snehh2711/PolicyBot-A-Governmental-policies-Recommendation-Chatbot/assets/124482094/9132794c-65a9-4d6c-9b79-f434df62d46e)

# Project flow 

The workflow of the PolicyBot, a governmental policies recommendation chatbot, involves several key steps that ensure it effectively provides personalized recommendations based on user queries. Here's a detailed breakdown of how the chatbot operates:

### 1. **User Query Input**
   - **User Interaction**: The user interacts with the chatbot via a text-based interface, inputting a query related to governmental policies. This could be about specific policy details, eligibility for a government scheme, or general information about policy areas.
   - **Data Capture**: User inputs can include specific requirements or preferences such as location, category of policies, or personal demographic details, which are captured to tailor the recommendations.

### 2. **Query Processing**
   - **Natural Language Understanding (NLU)**: The chatbot processes the user's input using NLU techniques to discern the user's intent and extract relevant entities (such as policy categories, location, etc.). This step is crucial for understanding the context and specifics of the user's request.
   - **Data Retrieval**: Based on the parsed input, the chatbot formulates queries to retrieve relevant data. This might involve accessing a database that contains detailed information about various governmental policies.

### 3. **Recommendation System**
   - **Policy Matching**: Using algorithms like cosine similarity, the system compares the user’s input with available policy data to find matches. This process involves vectorizing the text data of both the user input and the policy descriptions to find the most relevant policies.
   - **Summarization**: For complex policy documents, the chatbot utilizes a summarization model, such as the T5 model, to condense the information into more manageable snippets that highlight the key points of the policies, making them easier for users to understand quickly.

### 4. **Response Generation**
   - **Formatting Responses**: The chatbot formats the identified policies into a user-friendly response. If the query is about a specific policy, it provides a detailed explanation, eligibility criteria, and how to apply. For broader queries, it may offer a list of relevant policies with brief descriptions.
   - **Interactive Elements**: Depending on the interface, the chatbot can also include interactive elements such as links to full policy documents, or tools for further personalization (e.g., sliders to adjust preferences, checkboxes for filter options).

### 5. **User Feedback and Learning**
   - **Feedback Collection**: After presenting the information, the chatbot may ask for user feedback to gauge the accuracy and relevance of the provided recommendations. This feedback can be used to refine future interactions.
   - **Continuous Learning**: The system incorporates user interactions and feedback into its learning model to improve the accuracy of its NLP understanding and recommendation algorithms, ensuring that the chatbot becomes more effective over time.

### 6. **Visualization and Reporting**
   - **Dashboard Integration**: For users who require more detailed analysis or visualization, the chatbot integrates with a Tableau dashboard that displays policy impacts, demographic distributions, or effectiveness of certain policies.
   - **Reporting Tools**: Users can generate reports or export data directly from the chatbot interface, providing them with documentation that can be used for further analysis or decision-making processes.

### 7. **Security and Compliance**
   - **Data Security**: Ensuring user data privacy and security is critical, especially when handling personal information. The chatbot implements robust security measures to protect user data and comply with relevant data protection regulations.

This workflow demonstrates the chatbot's capability to act as an intelligent intermediary between complex governmental data and users, simplifying and personalizing the interaction to enhance understanding and accessibility of policy information.
