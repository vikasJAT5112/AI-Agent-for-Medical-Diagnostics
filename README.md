# README: Specialized LLM-Based AI Medical Analysis System

## Overview  
This project demonstrates the potential of AI in multidisciplinary medicine by using specialized LLM-based AI agents to analyze complex medical cases. Each agent focuses on a specific medical field, integrates insights, and provides personalized treatment recommendations. The results are combined and summarized for comprehensive health assessments.

---

## Current Version Features  
### AI Agents:  
1. **Cardiologist Agent**  
   - Focus: Detect potential cardiac issues like arrhythmias or structural abnormalities.  
   - Recommendation: Suggest cardiovascular tests, monitoring, and management strategies.

2. **Psychologist Agent**  
   - Focus: Assess psychological conditions like panic disorder and evaluate lifestyle factors.  
   - Recommendation: Provide therapy, stress management, or medication recommendations.

3. **Pulmonologist Agent**  
   - Focus: Investigate respiratory causes for symptoms like shortness of breath.  
   - Recommendation: Suggest lung function tests and respiratory interventions.

### Workflow:  
- Medical reports are simultaneously analyzed by the agents using threading.  
- Results are summarized by a language model to identify three potential health issues.  

---

## Future Enhancements  
- Introduce additional specialized AI agents (e.g., neurology, endocrinology, immunology).  
- Leverage OpenAI’s Assistant API for function calling and code interpreter capabilities.  
- Expand parsing capabilities for handling complex medical data.

---

## Repository Structure  
- **`Medical Reports`**: Contains synthetic medical reports (e.g., Panic Attack Disorder).  
- **`Results`**: Stores analysis outputs from the AI agents.

---

### Get Started  
Clone the repository and explore the provided sample medical reports and results to understand how the system functions.
