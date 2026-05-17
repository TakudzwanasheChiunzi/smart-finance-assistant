# 📓 Developer's Diary – AI Collaboration Guide

This file shows sample entries for your **Developer's Diary**. You must document your AI collaboration throughout the project development. Each entry should have:
- **Artifact**: a screenshot, GIF, or snippet of your AI interaction
- **Context**: one-sentence description of your goal
- **Reflection**: analysis of what happened, what you learned, and how you improved the solution

**Key Principle**: You're directing AI like a junior developer - always review, critique, and improve their suggestions.

---

## ☀️TAKU'S DEVELOPER DIARY ENTRIES☀️

### Entry 1 – ASSIGNMENT BREAKDOWN AND PERSONAL CHOICES FOR THE ASSIGNMENT
- The goal of this assignment is to create a finance assistant, a finance app that can help people with their personal finance goals. I chose my app to focus on tracking expenses (budgeting) and to act as a savings planner/helper.
- I started by breaking down the assignment and identifying what the assignment was requiring of me. I then used AI to better understand the assignment's goal and specifications.

**Artifact:** 
<img width="1337" height="651" alt="Screenshot 2026-05-17 204900" src="https://github.com/user-attachments/assets/d3c813ea-5558-4b64-a71b-80f85a73357c" />
<img width="1362" height="645" alt="Screenshot 2026-05-17 204926" src="https://github.com/user-attachments/assets/127721fd-8b8c-4a1a-9bd1-cf91e27e22a3" />
<img width="1335" height="658" alt="Screenshot 2026-05-17 204938" src="https://github.com/user-attachments/assets/181b418c-ba52-44c4-bff4-20a9c34065b2" />
<img width="1349" height="661" alt="Screenshot 2026-05-17 204950" src="https://github.com/user-attachments/assets/d6ea5a45-1d91-4f1b-a0f2-ab3e51ab4737" />
<img width="1352" height="648" alt="Screenshot 2026-05-17 205003" src="https://github.com/user-attachments/assets/c60f3eab-a925-45a1-b2d9-9d75e87dd6c6" />
<img width="1391" height="649" alt="Screenshot 2026-05-17 205014" src="https://github.com/user-attachments/assets/a5a17ef7-9eed-40a3-90b3-60d1e2cf6e07" />
<img width="1373" height="658" alt="Screenshot 2026-05-17 205032" src="https://github.com/user-attachments/assets/defb148e-7e8b-4995-b859-7b5de54ad27f" />
<img width="1393" height="654" alt="Screenshot 2026-05-17 205045" src="https://github.com/user-attachments/assets/68ba48fe-8b2d-4207-aabd-3d7fbc5f8589" />
<img width="1408" height="661" alt="Screenshot 2026-05-17 205058" src="https://github.com/user-attachments/assets/85f64344-023a-4f4c-9eee-38f75ffaad61" />
<img width="1436" height="665" alt="Screenshot 2026-05-17 205113" src="https://github.com/user-attachments/assets/7032cbd3-3c9c-4d75-bd9c-053894ed74f1" />
<img width="1413" height="655" alt="Screenshot 2026-05-17 205128" src="https://github.com/user-attachments/assets/5006a7e8-873b-4566-8913-69d300765cc2" />
<img width="1441" height="660" alt="Screenshot 2026-05-17 205142" src="https://github.com/user-attachments/assets/6c82f64c-1086-4174-b710-7e6ed94a68bb" />
<img width="1432" height="661" alt="Screenshot 2026-05-17 205157" src="https://github.com/user-attachments/assets/99c1469c-242e-4372-ba67-c88ad78004bb" />
<img width="1431" height="654" alt="Screenshot 2026-05-17 205211" src="https://github.com/user-attachments/assets/2e2fb983-a2ab-4b44-ab77-dcfd91bf9f49" />
<img width="1392" height="638" alt="Screenshot 2026-05-17 205226" src="https://github.com/user-attachments/assets/d3ba231c-3c1d-4d34-a621-af79647dd123" />


**My Initial Prompt:** "Hello Gemini. I'm a BCOM business information systems undergraduate student, in my first year, second semester. I'm doing my Introduction to Business Programming assignment, and I would like your help breaking down what the assignment requires in a way a complete novice would understand (since I am new to Python)."

**My Improved Prompt:** N/A

**Context:** Here, I asked Gemini to break down the assignment in a simple way so I could compare my understanding with its understanding.

**Reflection:** The response provided validation that I understood the gist of the assignment and provided the base understanding for me to begin work on it.

GOALS:
- My financial assistant will be taking on the Budget Buddy theme.
- My app will make use of colourful texts, themes and a menu page for maximum user interaction (all customisable, to an extent, by the user)
- My app will be able to take in CSV files of expenses, calculate savings based on goals and provide advice based on what the results of their inpus are

---

### Entry 2 – RESEARCHING ON APP BUILDING (LEARNING HOW TO MAKE THINGS PERSONALISED)
**Artifact:** Before/after screenshots of AI-generated spending analysis code.

**Context:** AI gave me complex code that was hard to understand for my transaction analysis.

**AI's First Response:**
```python
df.groupby('Category')['Amount'].agg({'sum','mean','count'}).round(2)
```

**My Critique:** "This code is unclear and doesn't handle dollar signs. Can you make it more readable with business-friendly variable names and add data cleaning?"

**AI's Improved Response:**
```python
# Clean amount data by removing dollar signs
df['Amount_Clean'] = pd.to_numeric(df['Amount'].str.replace('$', ''), errors='coerce')

# Calculate spending metrics by category
spending_summary = df.groupby('Category')['Amount_Clean'].agg({
    'Total_Spent': 'sum',
    'Average_Amount': 'mean', 
    'Transaction_Count': 'count'
}).round(2)
```

**Reflection:** I learned that AI's first response isn't always the best. By asking for clearer variable names and business context, I got much better code. This taught me to always review AI code and ask for improvements rather than accepting the first solution.

---

### Entry 3 – Business Context in AI Interactions
**Artifact:** Screenshot of Gemini generating financial insights from data.

**Context:** I wanted AI to help generate business recommendations from spending analysis.

**My Prompt:** "Based on this spending analysis showing Groceries: $450, Dining: $380, Coffee: $120, Transport: $95, create business insights and savings recommendations that sound professional for a personal finance app."

**AI Response:** Generated specific recommendations like "Consider meal planning to reduce dining expenses" and "Coffee purchases represent 8% of total spending - consider brewing at home."

**Reflection:** When I include business context and specify the audience (personal finance app users), AI generates much more relevant and professional output. I learned that framing requests in business terms gets business-quality responses. Now I always think about who will read the output and what decisions they need to make.

---

### Entry 4 – Data Quality and Edge Cases
**Artifact:** Screenshot of debugging session with Claude about handling messy CSV data.

**Context:** My CSV had negative amounts (refunds) and missing values that broke my calculations.

**My Problem:** "My spending analysis is giving wrong totals because some amounts are negative (refunds) and some cells are empty."

**AI Solution:** Helped me add data validation:
```python
# Handle refunds and missing data appropriately
df_clean = df.dropna(subset=['Amount_Clean'])
positive_spending = df_clean[df_clean['Amount_Clean'] > 0]
refunds = df_clean[df_clean['Amount_Clean'] < 0]
```

**Reflection:** AI helped me think about real-world data issues I hadn't considered. I learned that business data is always messy and I need to ask AI specifically about edge cases like refunds, missing values, and invalid entries. This makes my finance assistant more robust for actual use.

---

## Advanced Integration Examples

### Entry 5 – Combining Multiple AI Tools
**Artifact:** Screenshot showing integration of hands-on-ai chat with pandas analysis.

**Context:** I wanted to create a chatbot that could answer questions about spending data.

**My Approach:** Used AI to help me combine CSV analysis with hands-on-ai chat functionality.

**Key Learning:** AI helped me structure the integration, but I had to understand the business logic to make it useful. The chatbot needed to understand financial concepts, not just execute code.

**Reflection:** Integrating multiple technologies requires understanding how each piece serves the business purpose. AI can generate technical integration code, but I need to guide it toward business value.

---

### Entry 6 – Professional Error Handling
**Artifact:** Code snippet showing error handling for file uploads.

**Context:** I needed my Gradio interface to handle bad CSV files gracefully.

**AI Suggestion:** Generated try/catch blocks with business-appropriate error messages:
```python
try:
    df = pd.read_csv(file.name)
    # Analysis code...
except FileNotFoundError:
    return "Please upload a valid CSV file."
except pd.errors.EmptyDataError:
    return "The uploaded file appears to be empty. Please check your data."
```

**Reflection:** AI helped me think about user experience, not just technical functionality. Good error messages help users understand what went wrong and how to fix it. This is crucial for business applications.

---

## AI Collaboration Best Practices I've Learned

### 🎯 Effective Prompting Strategies
1. **Always provide business context**: "I'm building a finance assistant for..."
2. **Specify data structure**: "My CSV has columns X, Y, Z with these data types..."  
3. **Request professional formatting**: "Format output for business presentation"
4. **Ask for comments**: "Include clear comments explaining the business logic"

### 🤔 Critique Questions I Always Ask
- "Does this handle edge cases like negative amounts or missing data?"
- "Are the variable names clear for a business context?"
- "How would I explain this code to a non-technical manager?"
- "What assumptions is this code making about my data?"

### 🔄 Iterative Improvement Process
1. **Get basic working code** from AI
2. **Test with real data** and find issues  
3. **Ask AI to fix specific problems** with context
4. **Simplify complex solutions** for maintainability
5. **Add business-appropriate formatting** and error handling

### 📊 Business Value Focus
- Always connect code back to business decisions
- Format outputs for non-technical users
- Include actionable insights, not just data summaries
- Consider the end user's needs and context

---

## 📝 Documentation Template for Your Entries

Use this format for consistent diary entries:

```markdown
### Entry [Number] – [Descriptive Title]
**Artifact:** [Screenshot/code snippet/GIF of AI interaction]

**Context:** [One sentence: what you were trying to achieve]

**My Prompt:** "[Your exact prompt to AI]"

**AI Response Summary:** [Brief description of what AI provided]

**My Critique/Improvement:** [How you modified or improved the AI's suggestion]

**Result:** [What you ended up with and why it's better]

**Reflection:** [What you learned about AI collaboration, business programming, or problem-solving]
```

---

✅ **Remember**: Document your AI collaboration throughout your project development. Each entry should show learning and improvement, not just successful interactions. Show how you direct AI like a junior developer to create business-appropriate solutions.

