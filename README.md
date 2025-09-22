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

**Key Plot Descriptions:**

*   **Key Outcomes: Poverty vs. Budget:** This plot uses two y-axes to show how the poverty rate (in red) and the available budget (in blue) change year by year under the AI's policy. It helps assess the AI's success in its primary goals.
*   **AI Policy Preferences:** A bar chart showing the total count of times the AI chose each of the 9 available policy actions throughout the 25-year simulation. This gives insight into the AI's learned strategy and which policies it prioritized.
*   **Long-Term Resilience Investments:** This plot tracks the levels of key long-term indicators: Health Infrastructure, Education Level, and Agroforestry. An increase in these lines suggests the AI invested in building the region's long-term capacity to handle future challenges.
*   **Climate Context & AI Decisions:** This plot shows the annual rainfall anomaly (bars, red for drought, blue for good rain) overlaid with markers indicating which specific policy action the AI took in each given year. This helps analyze how the AI's decisions are influenced by the climate conditions.

**Analysis of a Sample Simulation Run:**

Based on the recent simulation run using the trained AI model, the results show:

*   **Significant Poverty Reduction:** The simulation demonstrated a **30.2% reduction in the poverty rate**, dropping from an initial 50% to a final rate of **18.8%**. This indicates the AI's policies were effective in improving the economic well-being of the population within the simulated environment.
*   **Effective Budget Management:** The AI successfully managed the region's finances, with the budget generally increasing over the simulation and averaging **$120M** annually. The AI avoided critical budget shortages.
*   **Learned Policy Strategy:** The most frequently chosen policy action by the AI was **Agroforestry**, which was selected **72%** of the time. This highlights the AI's reliance on this particular strategy to achieve its objectives.
*   **Limited Action Diversity:** While the AI primarily favored **Agroforestry**, the simulation plots also show that the AI did utilize other actions like **Irrigation** and **Early Warning** at times, demonstrating some level of policy diversification beyond the most frequent choice. However, the dominance of one action suggests room for further exploration or reward tuning.
*   **Focus on Specific Resilience:** The AI showed a strong preference for building **Agroforestry**, reaching the maximum level. However, investment in **Health Infrastructure** and **Education** remained static at their initial levels, and the AI **did not invest in the Dam project**. This indicates the AI's learned strategy prioritized certain types of resilience building over others in this simulation run.
*   **Drought Response:** The AI Idenfired 10 years of experiencing significant feature drought and took actions to invest in Irrifation, Early Warning and Agroforestry, suggesting a learned response to adverse climate conditions using its available policies.

While the AI achieved notable success in poverty reduction and budget management in this simulation, further experimentation with reward function design and different reinforcement learning algorithms (like PPO or A2C, which are included in this project for comparison) could potentially lead to an even more balanced and effective policy portfolio that leverages the full range of available actions.
