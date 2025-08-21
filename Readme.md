# Jarvis – Multiagentic Assistant

## Short Intro

Jarvis is a next-generation multi-agent conversational assistant. Unlike most AI assistants that act as a single agent, Jarvis can coordinate multiple specialized agents—such as calendar, summarizer, and memory—through a central reasoning system.

What makes it unique is its **emotional intelligence**: by analyzing the tone of your voice, Jarvis adapts its responses to match your mood, making conversations feel more natural and human.

Thanks to **persistent memory**, Jarvis can recall past interactions and personalize future ones, making it useful for productivity, customer support, and smart device applications.

---

## Full Description

### Problem Solved

Most AI assistants operate as single-agent systems with limited emotional intelligence and poor task coordination. They often fail to manage complex conversations, switch between tasks, or respond appropriately to a user’s emotional tone. This limits their usefulness in dynamic, real-world scenarios that require both functionality and empathy.

---

### Solution & Achievements

Jarvis is a multiagent conversational assistant built on top of Hume AI. It combines emotional intelligence, task-specific agents, and real-time voice interaction to create a more adaptive and human-like assistant.

Jarvis coordinates specialized agents (e.g., calendar, summarizer, memory) through a central reasoning system and adapts its responses based on emotional cues in the user's voice.

**Key Achievements:**

- Built multiagent orchestration using LangChain and Mistral for real-time reasoning and delegation
- Integrated Hume’s Empathic Voice API to adapt behavior and tone based on detected emotions
- Enabled full voice interface with Google STT and TTS for low-latency interaction
- Achieved end-to-end latency < 400ms using WebRTC for audio streaming
- Implemented persistent memory using PostgreSQL for long-term context and personalization

---

### Training & System Highlights

**Multiagent Coordination:**  
Used LangChain to build a routing system that delegates tasks to dedicated agents. Agents communicate through shared context and reasoning layers, allowing Jarvis to manage multiple goals at once.

**Emotion-Aware Interaction:**  
Voice input is processed with Hume’s API to extract emotional signals. These signals influence agent routing, tone of response, and assistant behavior.

**Voice & Memory:**  
Used Google STT and TTS for speech handling, with WebRTC enabling real-time audio. Memory is stored in PostgreSQL using vector-based indexing and recall.

---

### Technologies Used

- Python, LangChain, Mistral
- Hume AI, Google STT/TTS
- WebRTC, PostgreSQL, FastAPI
- Docker, Streamlit (for testing)

---

### End Use Cases

- Emotionally responsive assistant for productivity and daily tasks
- Multi-tasking conversational agent for customer support
- Voice-enabled agent for embedded or smart device platforms

---

### References

1. Wooldridge, M. (2009). *An Introduction to MultiAgent Systems* (2nd ed.). Wiley.
2. Russell, S., & Norvig, P. (2021). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson.
3. Picard, R. W. (1997). *Affective Computing*. MIT Press.
4. Ekman, P. (2003). *Emotions Revealed: Recognizing Faces and Feelings to Improve Communication and Emotional Life*. Times Books.
5. Minsky, M. (1986). *The Society of Mind*. Simon & Schuster.
6. Jurafsky, D., & Martin, J. H. (2023). *Speech and Language Processing* (3rd ed., draft). Prentice Hall.
7. Kepuska, V., & Bohouta, M. (2018). Next-generation of virtual personal assistants (Microsoft Cortana, Apple Siri, Amazon Alexa and Google Home). 2018 IEEE CCWC.
8. Liu, B., et al. (2021). Towards Emotionally Intelligent Dialogue Systems. Proceedings of the 59th Annual Meeting of the ACL.
