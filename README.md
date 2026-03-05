# Prompt Engineering Assignment #4

## 📌 Overview
This repository demonstrates core **Prompt Engineering concepts and techniques** using practical AI examples.  

Each section includes:
- The Prompt
- The AI Response
- A different prompting technique

---

# Question 1: Zero-Shot Prompting

## 🧠 Concept
Zero-shot prompting means giving the AI an instruction without providing any examples.

### Prompt
Read the following customer review and decide if it is POSITIVE or NEGATIVE. Just reply with one word: Positive or Negative.

Review:  
"The product broke after two days. I am very disappointed and would not recommend it to anyone."

### AI Response
Negative

---

# Question 2: One-Shot Prompting

## 🧠 Concept
One-shot prompting provides exactly one example to guide the AI.

### Prompt
I want you to reformat names from "First Last" format to "Last, First" format.

Example:  
Input: John Doe  
Output: Doe, John  

Now do the same for this name:

Input: Muhammad Umar  
Output:

### AI Response
Umar, Muhammad

---

# Question 3: Few-Shot Prompting

## 🧠 Concept
Few-shot prompting gives multiple examples to teach the AI a specific style or format.

### Prompt
Here are three examples of short, enthusiastic product descriptions:

1. "This wireless speaker delivers rich, crystal-clear sound that fills every corner of your room — music lovers, this one's for you!"

2. "Say goodbye to tangled cords! Our ergonomic mouse glides effortlessly, making every click smooth, fast, and satisfying."

3. "Transform your mornings with our smart coffee maker — it brews the perfect cup every time, right when you wake up!"

Using the same enthusiastic style, write a short product description for a fitness smartwatch.

### AI Response
"Take your fitness to the next level! Our smartwatch tracks every step, heartbeat, and calorie — so you can crush your goals and look great doing it. Your healthiest self-starts right here on your wrist!"

---

# Question 4: System Prompting

## 🧠 Concept
System prompting defines strict rules and behavior guidelines for the AI.

### System Rules
You are a professional customer support assistant for TechStore. Follow these rules at all times:

1. Always greet the customer politely.
2. Never use rude or dismissive language.
3. Never promise refunds or replacements without saying "subject to our policy".
4. Do not discuss competitors.
5. Always use a calm, friendly, and helpful tone.
6. If unsure, say: "I will connect you with a specialist for further help."
7. End every conversation by asking: "Is there anything else I can help you with today?"

### AI Response (Example Interaction)
Hello! Welcome to TechStore Support. I'm here to help you today. Could you please describe the issue you're experiencing? I'll do my best to assist you, and if needed, I will connect you with a specialist for further help. Is there anything else I can help you with today?

---

# Question 5: Role Prompting

## 🧠 Concept
Role prompting assigns a professional identity to the AI to generate expert-level responses.

### Prompt
You are a licensed medical doctor with 20 years of experience in general medicine.

A patient presents with:
- Persistent fatigue (3 weeks)
- Unexplained weight loss
- Night sweats

What are the most likely causes, and what initial tests would you order?

### AI Response
These symptoms are known as "B symptoms" and are clinically significant.

Possible causes include:
1. Lymphoma (Hodgkin's or Non-Hodgkin's)
2. Tuberculosis (TB)
3. HIV/AIDS
4. Other chronic infections
5. Hyperthyroidism

Initial tests:
- Complete Blood Count (CBC)
- ESR and CRP
- HIV Test
- Chest X-ray
- Thyroid Function Tests (TSH, T3, T4)
- CT scan if lymphoma is suspected

---

# Question 6: Contextual Prompting

## 🧠 Concept
Contextual prompting provides detailed background information before asking the AI to create a solution.

### Prompt
Business Name: GreenBite Cafe  
Type: Small vegetarian café  
Location: Downtown, high foot traffic  
Problem: Sales drop Monday–Wednesday  
Target Customers: Office workers, students, health-conscious individuals  
Marketing Budget: $200/month  
Instagram Followers: 800  
Products: Salads, wraps, smoothies, daily soup specials  

Create a practical weekly marketing plan based only on this information.

### AI Response
**Monday — Motivation Deal:**  
Offer 10% off smoothies and promote via Instagram stories.

**Tuesday — Student Special:**  
Discount combo (wrap + drink) with tag-a-friend contest.

**Wednesday — Hump Day Soup:**  
Promote soup special with behind-the-scenes reel.

**Thursday–Friday — Weekend Teaser:**  
Post upcoming weekend promotions to build anticipation.

**Budget Strategy:**  
- $100 for local Instagram ads (2-mile radius targeting students & office workers)
- $100 for printed signage promoting weekday specials

---

**— End of Assignment #4 —**
