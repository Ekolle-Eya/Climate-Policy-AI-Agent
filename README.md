# 🌍 AI Climate Policy Agent for Kitui County, Kenya

### **Empowering Communities to Adapt and Thrive in Changing Climate**
This project presents a cutting-edge application of Artificial Intelligence (AI) to address the critical challenge of climate change adaptation in vulnerable regions.Using real-world data from Kitui County, Kenya, The AI Agent have be trained to act as a **Climate Policy Expert**, learning to strategically invest limited resources in different policies to reduce poverty and build resilience against climate shocks like drought.

## ✨ The Challenge

Regions like Kitui County in Kenya are on the front lines of climate change. Increasingly unpredictable rainfall patterns and recurring droughts threaten livelihoods, exacerbate poverty, and strain limited resources. Decision-makers face complex choices: should they invest in immediate relief, or focus on long-term solutions? How can they maximize positive impact with a limited budget?

This is where **AI** can help. By simulating the complex interactions between climate, economy, and society, an **AI Agent** can learn to make informed decisions that lead to better outcomes for the community.

## 🤖 My AI Solution

I've developed a **Reinforcement Learning (RL)** model that learns through trial and error within a simulated environment representing Kitui County. Think of it like training a skilled policy advisor:

*   **The Environment:** A realistic simulation of Kitui County over 25 years, incorporating real historical data on **rainfall, vegetation health, and population**. It also models key factors like **poverty rate, available budget, and the impact of different investments**.
*   **The AI Agent:** A Deep Q-Network (DQN) model, a type of AI particularly good at making sequential decisions to maximize a long-term reward.
*   **The Actions:** The AI can choose from 9 distinct policy actions each year, ranging from short-term support to long-term infrastructure projects:
    1.  Do Nothing
    2.  Build Irrigation Systems
    3.  Subsidize Drought-Resistant Crops
    4.  Develop Early Warning Systems
    5.  Fund Microfinance Loans
    6.  Invest in Community Health Programs
    7.  Invest in Education
    8.  Agroforestry / Mangrove Restoration
    9.  Build a Water Reservoir (Dam)
*   **The Goal:** The AI's objective is to learn a policy that maximizes a "reward" over time. This reward is designed to incentivize **reducing poverty, maintaining a healthy budget, and building long-term resilience** in the community.

By training the AI in this simulation, it learns which policies are most effective under different conditions and how to balance immediate needs with long-term sustainable development.

## 📊 Results & Visualizations

After training, I run a simulation of the AI's learned policy for 25 years to see how it performs. The visualizations below provide a clear picture of the AI's impact:

<img width="1589" height="1181" alt="AI policy 3" src="https://github.com/user-attachments/assets/264cc951-63ec-4db0-aeb0-7eb42f69a6e9" />
