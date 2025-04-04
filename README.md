# 🕵️‍♀️ AI Agent Squad on Bedrock

Welcome to **AI Agent Squad on Bedrock** — an intelligent, serverless chatbot system powered by **Amazon Bedrock**, **Lambda**, and **S3**, designed to help users find **hotels** and **restaurants** with the help of 3 specialized AI agents working together!

This isn't just a chatbot — it's a full-on **AI mission squad** 🎯

---

## 🧠 What Is It?

Imagine asking a single chatbot:  
_"Find me a nice hotel in Houston."_  
And instead of one generic answer, **multiple AI agents** team up behind the scenes to get you the right info.

You get a quick, smart, and helpful answer — no coding required.

---

## 👥 Meet the Agents

We built 3 cool AI agents that each have a unique role:

| Agent Name              | Mission                                               |
|------------------------|--------------------------------------------------------|
| 🏨 Accommodation Agent | Finds hotels or Airbnbs (with options like pool, sauna) |
| 🍽️ Restaurant Agent    | Suggests restaurants in your city (fine dining or casual)|
| 🧠 Orchestrator Agent   | Acts like a manager — decides which agent should help you|

They all work together using **Amazon Bedrock’s serverless agent framework**!

---

## 🧰 Tech Stack

- **Amazon Bedrock** – To power our generative AI agents
- **Lambda Functions** – Each agent uses Lambda for business logic
- **Amazon S3** – Stores conversation logs, configs, and mock data
- **Postman** – For testing and chatting with the agents
- **Serverless Architecture** – Zero infrastructure management

---

## 🎯 Why It’s Cool (Even If You're Non-Technical)

- 🧾 **Natural Chat** – You just type what you want. No commands or apps.
- 🧠 **Smart Behind the Scenes** – The system knows when to call a hotel agent vs. a restaurant agent.
- 🕹️ **No Servers** – Everything runs in the cloud, saving cost and headaches.
- 🚀 **Scalable** – This can grow into a travel planner, concierge bot, or more!

It’s like asking a travel expert, food critic, and concierge all at once… and they never get tired.

---

## 💬 Example Conversation

> **User:** Hey agent, suggest me a hotel in Houston  
> **System:** Here’s a great pick — *The Velvet Rose* 🌹  

> **User:** And a nice fine-dining restaurant?  
> **System:** How about *Le Gourmet* in downtown?

All of this happens by the agents working together like a dream team behind the scenes.

---

## 🛠️ How We Built It

1. **Created 3 Bedrock Agents** – Each with their own tools and instructions.
2. **Connected them via an Orchestrator Agent** – The brains of the operation.
3. **Wrote Lambda functions** – To fetch hotels, restaurants, etc.
4. **Stored our data in S3** – Lightweight and easy.
5. **Tested the whole thing in Postman** – Because why not?

---

## 🧪 Try It Out

You can run this project using:
- **Postman** to simulate chats with the agents
- **AWS Console** to test the agents and Lambda flows

## 👋 Authors

Built with love (and a few rate limit errors 😅) by  
Ruzsan , inspired by the Serverless Agentic Workflows with Amazon Bedrock


Star ⭐ the repo, fork it, or contribute with:
- New agent ideas
- Real hotel/restaurant APIs
- UI interfaces for chatting
