
# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different prompting patterns respond to various prompts, such as broad or unstructured prompts versus clear and refined prompts, across multiple test scenarios, and to analyze the generated responses based on quality, accuracy, and depth.

### AI Tools Required: 
ChatGPT

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.
# 1.INTRODUCTION

Prompt engineering is the process of designing effective instructions for an Artificial Intelligence model to obtain accurate, relevant, and useful responses.
A simple or broad prompt may produce a general answer, whereas a clear and structured prompt can guide the AI to generate a more specific and organized response.
<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/0c1691f5-fa34-4a45-8918-2c0f26735f0f" />

# 2.TYPES OF PROMPT
## 2.1 Naïve Prompt
A naïve prompt is a simple, broad, or unstructured instruction given to an AI model. It provides minimum information about the expected output.

Example
~~~
Explain Artificial Intelligence.
~~~

The AI has to decide the content, depth, structure, and target audience by itself.
## 2.2 Basic / Refined Prompt
A basic prompt is a clearer and more structured instruction that provides context, task requirements, audience, output format, and constraints.

Example
~~~
Explain Artificial Intelligence to a beginner.
Include its definition, major applications, advantages,
limitations, and two real-world examples.
Use simple language and clear headings.
~~~
This gives the AI better guidance and generally produces a more focused response.
# 3. Comparative Prompting Test Scenarios
The following scenarios are used to compare naïve and basic prompts.
## Scenario 1 – Creative Story Generation
## Naïve Prompt
~~~
Write a story about a robot.
~~~
## Basic Prompt
~~~
Write a 200-word creative story about a friendly robot
that helps students in a school. Include a beginning,
a problem, a solution, and a positive ending. Use simple
and engaging language.
~~~
# Comparison
| Parameter  | Naïve Prompt | Basic Prompt   |
| ---------- | ------------ | -------------- |
| Quality    | Moderate     | High           |
| Accuracy   | Good         | High           |
| Depth      | Limited      | Detailed       |
| Creativity | General      | Focused        |
| Structure  | Basic        | Well organized |
## Observation: 
The basic prompt generates a more structured and meaningful story because it specifies the length, characters, problem, solution, and ending.
## Scenario 2 – Factual Question
## Naïve Prompt
~~~
What is cloud computing?
~~~
## Basic Prompt
~~~
Explain cloud computing for a beginner who has no
technical knowledge. Give a simple definition, explain
how it works, provide three examples, and list two
advantages and two limitations.
~~~
# Comparison
| Parameter    | Naïve Prompt | Basic Prompt |
| ------------ | ------------ | ------------ |
| Quality      | Good         | Very High    |
| Accuracy     | Good         | High         |
| Depth        | Basic        | Detailed     |
| Clarity      | Moderate     | Excellent    |
| Organization | Simple       | Structured   |
## Observation: 
Both prompts can produce a correct answer, but the basic prompt provides a more complete and beginner-friendly explanation.
## Scenario 3 – Summarization
## Naïve Prompt
~~~
Summarize Artificial Intelligence.
~~~
## Basic Prompt
~~~
Summarize Artificial Intelligence in approximately
100 words. Include its definition, applications,
benefits, and one limitation. Use simple language and
include only the most important points.
~~~
# Comparison
| Parameter   | Naïve Prompt | Basic Prompt |
| ----------- | ------------ | ------------ |
| Quality     | Moderate     | High         |
| Accuracy    | Good         | High         |
| Depth       | Variable     | Appropriate  |
| Relevance   | Moderate     | High         |
| Conciseness | Moderate     | Excellent    |
## Observation:
The refined prompt produces a focused summary because the required points and approximate length are clearly specified.
## Scenario 4 – Advice and Recommendation
## Naïve Prompt
~~~
How can I learn Java?
~~~
## Basic Prompt
~~~
Create a 30-day Java learning plan for a college student
with basic programming knowledge. Divide the plan into
weekly stages covering Java syntax, OOP, arrays, collections,
exception handling, and problem-solving. Include daily
practice activities and a small final project.
~~~
# Comparison
| Parameter    | Naïve Prompt | Basic Prompt |
| ------------ | ------------ | ------------ |
| Quality      | Moderate     | High         |
| Practicality | General      | Very High    |
| Depth        | Limited      | Detailed     |
| Organization | Low          | Excellent    |
| Usefulness   | Moderate     | High         |
## Observation:
The basic prompt provides an actionable learning plan instead of only giving general suggestions.
## Scenario 5 – Technical Explanation
## Naïve Prompt
~~~
Explain Internet of Things.
~~~
## Basic Prompt
~~~
Explain the Internet of Things (IoT) to an ECE student.
Start with a simple definition. Explain sensors,
connectivity, processing, and actuators. Describe the
working process step by step and provide two real-world
examples. Use simple technical language.
~~~
# Comparison
| Parameter           | Naïve Prompt | Basic Prompt |
| ------------------- | ------------ | ------------ |
| Quality             | Good         | Very High    |
| Accuracy            | Good         | High         |
| Depth               | Moderate     | Detailed     |
| Technical Relevance | General      | High         |
| Organization        | Moderate     | Excellent    |
## Observation: 
The basic prompt produces an answer that is more appropriate for the specified audience and technical context.
# 4. Prompt Templating Techniques
A prompt template is a predefined structure containing fixed instructions and dynamic information. It allows the same prompt structure to be reused for different inputs.
<img width="1400" height="764" alt="image" src="https://github.com/user-attachments/assets/238a97ef-49c9-48c4-86f2-0452a0bde1be" />
## 4.1 Static Templates
A static template contains fixed instructions with little or no customization.
Example
~~~
Generate a maintenance report.
~~~
## 4.2 Parameterized Templates
Parameterized templates contain placeholders that can be replaced with dynamic information.
Example
~~~
Equipment: {equipment_name}
Equipment ID: {equipment_id}
Fault: {fault_description}
Date: {detection_date}
~~~
## 4.3 Conditional Templates
Conditional templates change their instructions based on a particular condition.
Example
~~~
If severity is High:
Generate a detailed report with safety warnings.

If severity is Low:
Generate a brief maintenance summary.
~~~
## 4.4 Chained Templates
Chained templates divide a complex task into multiple smaller tasks.
Example
~~~
Main Report
      ↓
Root Cause Analysis
      ↓
Downtime Estimation
      ↓
Maintenance Recommendation
      ↓
Final Report
~~~
# 5. Command Pattern
The Command Pattern is a software design pattern that converts a request into an object. This allows the sender of a request to be separated from the component that performs the request.
In the proposed AI system:
Client → Configures the report
Invoker → Maintenance management system
Command → Report generation request
Receiver → AI/LLM model
<img width="666" height="564" alt="image" src="https://github.com/user-attachments/assets/a6512587-3c2e-4126-8946-0c81f0353b18" />
# 6. Components of Command Pattern
| Component         | Description                           |
| ----------------- | ------------------------------------- |
| Command Interface | Defines the `execute()` operation     |
| Concrete Command  | Implements report-generation logic    |
| Invoker           | Sends the report-generation request   |
| Receiver          | AI/LLM that generates the response    |
| Client            | Configures templates and machine data |
# 7. Integration of Prompt Templates with Command Pattern
Prompt templates and the Command Pattern can be combined to create a modular AI-based maintenance reporting system.
<img width="1432" height="692" alt="image" src="https://github.com/user-attachments/assets/d422bff1-6f81-4149-9dc5-8c388089afa4" />
# 8. Workflow
The system works according to the following steps:
The maintenance manager requests a report.

The system receives equipment information.

An appropriate prompt template is selected.

Machine data is inserted into the template.

A command object is created.

The command sends the prompt to the AI model.

The AI model analyzes the information.

A structured maintenance report is generated.

The report is stored or displayed on a dashboard.
# 9. Scenario 6: Engineering Problem
## 9.1 Real-World Scenario
A busy 4-way city intersection has many vehicles during peak hours. Traffic levels can change on each road.

When an ambulance arrives, fixed-time traffic signals may cause unnecessary delay.

An ai-based smart traffic management system can use cameras to monitor traffic and automatically control signals.

The system should:

detect vehicles using cameras
calculate traffic density
classify traffic as low, medium, or high
detect emergency vehicles
give emergency vehicles highest priority
change traffic signals automatically
return to normal operation after the ambulance passes

## 9.2 Problem Statement
Develop an ai-based smart traffic management system for a 4-way intersection.

The system should make signal decisions using real-time traffic conditions and emergency vehicle detection.
~~~
emergency vehicle
        ↓
  highest priority
        ↓
    high traffic
        ↓
   medium traffic
        ↓
     low traffic
~~~
## 9.3 Naïve Prompt
~~~
design an ai-based smart traffic system.
~~~
## 9.4 Expected Output From Naïve Prompt
The ai may give a simple answer:
~~~
ai can use cameras to monitor traffic and control traffic signals based on vehicle density.
~~~
### observation

The answer is general and does not clearly explain the:

requirements
architecture
algorithm
implementation
testing
# 10. Refined Engineering Prompt
~~~
act as an ai and embedded systems engineer.

design an ai-based smart traffic management system for a
4-way urban intersection.

the system should use cameras to detect vehicles,
calculate traffic density, and classify traffic as
low, medium, or high.

the system should detect emergency vehicles and give
them the highest priority.

after the emergency vehicle passes, the system should
return to normal traffic operation.

include:
1. problem definition
2. requirements
3. hardware and software
4. system architecture
5. working principle
6. traffic density algorithm
7. emergency vehicle detection
8. signal decision algorithm
9. flowchart
10. python simulation
11. test cases
12. expected results
13. advantages
14. limitations
15. future enhancements
~~~
# 11. Expected Output From Refined Prompt
The refined prompt produces a complete and organized solution.
~~~
problem
   ↓
requirements
   ↓
architecture
   ↓
algorithm
   ↓
flowchart
   ↓
python code
   ↓
testing
   ↓
documentation
~~~
# 12. System Architecture
~~~
traffic camera
      ↓
vehicle detection
      ↓
vehicle counting
      ↓
traffic density
      ↓
low / medium / high
      ↓
emergency detection
      ↓
ai decision
      ↓
signal controller
      ↓
traffic lights
~~~
# 13. Working Principle
camera captures traffic.

ai detects vehicles.

vehicle count is calculated.

traffic density is classified.

emergency vehicles are detected.

ai selects the priority road.

traffic signal is changed.

normal operation resumes after the emergency vehicle passes.
# 14. Decision Algorithm
~~~
detect traffic
      ↓
check emergency vehicle
      ↓
    yes ─────→ highest priority
      ↓
     no
      ↓
check traffic density
      ↓
high → high priority
medium → medium priority
low → low priority
      ↓
change traffic signal
~~~
# 15. Python Simulation
~~~
def traffic_control(density, emergency):

    if emergency:
        return "emergency priority - green"

    elif density == "high":
        return "high traffic - green"

    elif density == "medium":
        return "medium traffic - green"

    else:
        return "low traffic - green"


print(traffic_control("high", False))
print(traffic_control("medium", False))
print(traffic_control("low", True))
~~~
## Expected Output
~~~
high traffic - green
medium traffic - green
emergency priority - green
~~~

<img width="513" height="311" alt="image" src="https://github.com/user-attachments/assets/e2d587c4-15e5-4e09-bee6-0579de8fae71" />

# 16. Test Cases
| test case | traffic | emergency | expected result    |
| --------- | ------- | --------- | ------------------ |
| tc01      | low     | no        | low priority       |
| tc02      | medium  | no        | medium priority    |
| tc03      | high    | no        | high priority      |
| tc04      | low     | yes       | emergency priority |
| tc05      | medium  | yes       | emergency priority |
| tc06      | high    | yes       | emergency priority |
# 17. Evaluation
| parameter             | naïve prompt | refined prompt |
| --------------------- | ------------ | -------------- |
| problem understanding | basic        | detailed       |
| requirements          | limited      | clear          |
| architecture          | missing      | included       |
| algorithm             | general      | defined        |
| testing               | missing      | included       |
| usefulness            | low          | high           |
# 18. Conclusion
The experiment shows that prompt design improves the quality of ai-generated engineering solutions. The naïve prompt gives a basic idea, while the refined prompt provides a clear and structured solution for ai-based smart traffic management with emergency vehicle priority.
# 19. Result 
**The experiment was successfully completed. The comparison showed that refined prompts provide better-quality and more structured responses than naïve prompts, particularly when solving complex engineering problems.**
