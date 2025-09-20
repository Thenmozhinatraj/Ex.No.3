# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques

### DATE: 19/08/2025                                                                            
### REGISTER NUMBER : 212223060291
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting  

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type

# Procedure:
1.	Define the Scenario and Use Case:
Manufacturing companies aim to reduce manual monitoring and improve efficiency using IoT automation.
Goal: Streamline production, minimize downtime, and save energy.
Target Audience: Automotive, electronics, and food-processing industries.

# Objectives:

Increase production efficiency by 30 %.
Minimize downtime with predictive maintenance.
Provide real-time monitoring and remote control.
Reduce energy consumption through smart scheduling.

# Procedure:
```
1. Identify the Scenario
Select a real-world use case.
For this experiment, choose an IoT-enabled manufacturing plant that requires an AI-powered chatbot for production monitoring and customer support.

2. Set the Objective
Decide what the chatbot must accomplish (e.g., predictive-maintenance guidance, order tracking, energy-efficiency tips).
Note key goals: improve efficiency, reduce downtime, provide real-time insights.

3. Choose Prompting Techniques
Straightforward Prompting
Tabular-Format Prompting
Preceding-Question (follow-up) Prompting

4. Design Test Prompts
Prepare 2–3 example prompts for each technique.
Ensure that each prompt relates to the manufacturing chatbot scenario (e.g., “List IoT features…”, “Create a table of hardware modules…”).

5. Interact with the AI Model
Enter each prompt in the ChatGPT interface.
Observe and record the AI’s responses (outputs).

6. Analyze Responses
Check whether answers meet the intended goal:
Are Straightforward prompts concise and direct?
Are Tabular prompts producing clear, structured tables?
Do Preceding questions show logical, progressive depth?

7. Document Results
For each prompt type, note:
The exact prompt text.
The generated output.
Any key observations (accuracy, completeness, formatting).

8. Compare Techniques
Evaluate which prompting method best supports:
Quick idea generation.
Organized data presentation.
In-depth technical exploration.

9. Draw Conclusions
Summarize how each prompting technique contributes to building a well-specified AI chatbot for industrial IoT automation.
``` 
# Identify Prompt Patterns for Each Design Aspect:
Idea Generation Prompts:

•	Prompt: “What features can be incorporated into the automation system to optimize production and reduce downtime?” Generated Ideas:
•	Sensors for real-time monitoring of equipment performance.
•	Predictive maintenance alerts to anticipate equipment failures.
•	Energy usage optimization by automating the switching of machines on/off based on demand.
•	Cloud-based dashboards for remote monitoring and control of machinery.

Persona and Context Prompts:

•	Prompt: “What should the user interface and control system convey to the operators and managers?” Generated Context:
•	The user interface should be intuitive and provide real-time data on machine performance, energy usage, and alerts.
•	The system should convey reliability and ease of use, with minimal training required for operators.

# Straightforward Prompting

Purpose: Quick idea generation or fact gathering without special formatting.

Example 1

Prompt:

“List five essential IoT features for improving production efficiency in a medium-scale manufacturing plant.”

Output:
1. Vibration, temperature, and current sensors on each machine.
2. Edge controllers (STM32/ESP32) for local decision making.
3. Predictive-maintenance alerts using historical data.
4. Cloud dashboards for live monitoring and remote start/stop.
5. Secure data transfer via MQTT or LoRaWAN.

Example 2

Prompt:
“Identify major risks if predictive maintenance is not implemented in a smart factory.”
Output:
1. Unexpected machinery breakdowns causing long downtime.
2. Higher repair costs due to catastrophic failures.
3. Reduced production output and missed delivery deadlines.
4. Increased energy waste from malfunctioning equipment.

Example 3

Prompt:
“Suggest three customer-support features the chatbot should include for factory managers.”
Output:
1. Real-time machine-status query (“Check Machine 7 temperature”).
2. Automated maintenance scheduling with reminders.
3. Order/parts tracking for replacement components.

# Tabular-Format Prompting

Purpose: Organise detailed comparisons or specifications into clear tables.

Example 1

Prompt
“Create a table of IoT hardware modules with their function and expected benefit.”
<img width="887" height="266" alt="image" src="https://github.com/user-attachments/assets/a1c67c14-6632-4ab1-b1d8-623ccc1739a4" />

Example 2:
<img width="867" height="352" alt="image" src="https://github.com/user-attachments/assets/c8baac3c-e69e-4172-9012-6ce8372e6b01" />

# Preceding-Question (Follow-Up) Prompting

Purpose: Explore a topic deeply by asking linked questions where each depends on the previous answer.

Example 1

Prompt 1

“Which lightweight machine-learning algorithms can run on low-power microcontrollers for vibration analysis?”
Output 1
Random Forest, Decision Tree, 1-D CNN, SVM (linear kernel).

Prompt 2

“Which of these gives the best balance of accuracy and power use for STM32?”
Output 2
Random Forest and 1-D CNN provide the best trade-off.

Prompt 3

“Give approximate RAM and inference time for those models using TensorFlow Lite Micro.”
Output 3
Random Forest ~60 KB, 20 ms; 1-D CNN ~80 KB, 25 ms.

Example 2

Prompt 1
“Identify the main energy-consuming machines in a food-processing plant.”
Output 1
Industrial ovens, refrigeration units, high-speed mixers.

Prompt 2 
“What sensor types are best to monitor energy usage of these machines?”
Output 2
Smart power meters, current transformers, temperature probes.

<img width="474" height="355" alt="image" src="https://github.com/user-attachments/assets/872a5a58-3d5d-4a01-b94f-deec80a9938e" />

# Best practices for prompting
The qualities that turn you into an excellent communicator — clarity, precision, context, and structure — are very similar to those you need to write great prompts. Follow the following proven practices to consistently elevate the’ quality and strategic value of your AI interactions.

Know your model: In a conversation, you are better off if you know your counterpart. AI is no different. Understand what your model knows and what it doesn’t. Check its cutoff date (until when the training data was collected), reasoning strengths, and common blind spots. Experiment with different models for different tasks. To facilitate your prompting journey, download our overview of the top-10 popular LLMs for frontend prompting here.
Be clear and specific: Imagine you’re giving instructions to a personal assistant on their very first day. They’re smart, but they don’t yet know your preferences, so spell things out.
Ground the model in your enterprise context: Your model likely doesn’t know too much about your company. Attach files and documents that contain information that is relevant for the request.
💡Governance tip: Before including any sensitive or confidential information in a prompt, review your language model provider’s data retention and usage policies. Understand where your data goes, how it’s stored, and whether it might be used for future model training.

4. Specify the output format: By default, models return unstructured text. If you want a certain structure, say so. For example: “List 5 space tourism companies in JSON. Include: name, founded year, HQ, and unique selling point.”

5. Iterate and test: Prompting is experimental. Try variations, compare, and refine. Small tweaks = big gains.

Example: Start with: “Summarize the meeting.” Then test: “Summarize for the CTO — focus on unresolved decisions and next steps.”
6. Embrace your editing function: With AI, you are in the role of a curator and editor. Achieving a high quality by just copy-pasting an AI output is a rare thing. Likely, you need to do editing work of some kind, like fact-checking, humanizing the tone, adapting it to your context, etc.

💡Pro tip: You might have heard the saying: “Your job will not be replaced by AI, but by someone who can use AI.” Becoming a pro at editing AI outputs is your first step towards the AI-upgraded role.

7. Systematize prompting: As your prompting matures, create a repeatable process:

Use templates for recurring tasks
Save and version proven prompts
Document what works — and why
### Conclusion
Result: The various types of Prompts are executed successfully with generated the report.

