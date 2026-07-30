# intelligient-shopping-agent
AI-powered Intelligent Shopping Agent using IBM watsonx Orchestrate, watsonx.ai, Granite Models, and RAG to provide personalized product recommendations, price intelligence, product comparison, and explainable shopping decisions.

# Proposed Solution: AI-Powered Intelligent Shopping Agent
The proposed solution is a multi-agent AI-powered Intelligent Shopping Agent built using IBM watsonx Orchestrate, IBM watsonx.ai, and Granite Models to provide personalized, real-time shopping assistance. The system addresses challenges such as product overload, scattered reviews, price fluctuations, and difficulty in making informed purchase decisions through an intelligent, modular architecture.

At its core, the solution uses a Retrieval-Augmented Generation (RAG) pipeline to fetch accurate and up-to-date product information from trusted e-commerce platforms, manufacturer websites, and review sources. Product specifications, customer reviews, ratings, pricing, and availability are embedded and stored in a vector database, enabling the system to retrieve, compare, and summarize relevant product insights using Granite models.

The system consists of four key agents:
Product Discovery Agent retrieves and summarizes product details, specifications, reviews, and ratings using the RAG pipeline, helping users quickly understand available options.

Personalized Recommendation Agent generates tailored product recommendations based on user preferences, budget, shopping history, brand preferences, and specific requirements.

Price & Deal Intelligence Agent continuously monitors product prices across multiple platforms, identifies discounts, cashback offers, coupons, and price-drop alerts, ensuring users get the best value for money.

Comparison & Purchase Advisor Agent compares shortlisted products based on price, features, quality, customer sentiment, warranty, and value for money, then provides a final buying recommendation with clear reasoning.

The solution includes a user-friendly dashboard (built with React or Streamlit) where users can search products, compare multiple options, track price history, save wishlists, receive personalized deal notifications, and monitor their shopping preferences.


# Project Screenshot 

1. ShopAI Dashboard
   <img width="1918" height="1003" alt="1000127600" src="https://github.com/user-attachments/assets/90145d39-b7f1-440c-a248-85185d00bc22" />

2. ShopAI in Action
   <img width="959" height="495" alt="Screenshot 2026-07-28 224144" src="https://github.com/user-attachments/assets/991ebcb1-7e91-41d0-9906-25e25f4fc529" />

   <img width="959" height="539" alt="Screenshot 2026-07-29 115415" src="https://github.com/user-attachments/assets/0e146ec0-49f4-47a1-9db9-c458eb1e4fde" />
