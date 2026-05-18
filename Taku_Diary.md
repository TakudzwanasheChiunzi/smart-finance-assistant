# 📓 Developer's Diary – AI Collaboration Guide

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

**AI Response:** Gemini broke down the main points of the assignment (full conversation can be read in AI CONVERSATIONS folder)

**Context:** Here, I asked Gemini to break down the assignment in a simple way so I could compare my understanding with its understanding.

**Reflection:** The response provided validation that I understood the gist of the assignment and provided the base understanding for me to begin work on it.

GOALS:
- My financial assistant will be taking on the Budget Buddy theme.
- My app will make use of colourful texts, themes and a menu page for maximum user interaction (all customisable, to an extent, by the user)
- My app will be able to take in CSV files of expenses, make calculations and provide advice based on the results of their inpus are

---

### Entry 2 – IDEALISING WHAT I WANT MY FINANCE APP TO BE LIKE (PSEUDO CODE)
- I wrote down my ideas of what I wanted the app to do/created a pseudo code of what I wanted the assistant to do. I then asked Gemini to break down how I would go about it.

-	The app will welcome the user to the app
-	The app will ask the user to select a theme and font
-	App will start by asking if the user wants to see the menu/dashboard or jump into the budget

If the User chooses Budget:
-	App asks the user if they want to work on their budget 
If the User chooses Budget:
-	App asks the user if 
-	App asks if the user wants to upload a CSV file or input transactions
If the User chooses CSV:
-	App prompts user to upload the CSV
-	App calculates total spent, amount of budget used, percentage of budget used, and gives out advice
If the User chooses input transactions
-	App prompts user to input how many transactions they want to input
-	App asks user to input the name of the transactions, what it was for and the amount
-	App calculates total spent, amount of budget used, percentage of budget used and gives out advice


If the user chooses dashboard/menu:
Dashboard will show:
-	Expenses
-	Chatbot (user can ask budget-related advice and questions)

---

### Entry 3 – USING AI AS A PROJECT GUIDE
- I gave Gemini my pseudocode and asked it where I should start building my finance app.
  
**Artifact:** 
<img width="1352" height="830" alt="Screenshot 2026-05-18 211133" src="https://github.com/user-attachments/assets/d93514b9-a441-4959-a481-fbd3a75422d0" />
<img width="1333" height="834" alt="Screenshot 2026-05-18 211148" src="https://github.com/user-attachments/assets/155e75f6-8fc1-49b8-8d9c-da8b5c19a8c7" />
<img width="1402" height="828" alt="Screenshot 2026-05-18 211203" src="https://github.com/user-attachments/assets/b2e3da96-8c21-4477-9e42-52ed9e3317a5" />
<img width="1394" height="814" alt="Screenshot 2026-05-18 211218" src="https://github.com/user-attachments/assets/2bd2687c-4034-4170-85d4-328d0d05ed5d" />
<img width="1353" height="822" alt="Screenshot 2026-05-18 211230" src="https://github.com/user-attachments/assets/9ad23012-9e0c-42d2-82b6-fdc36d61ea8c" />
<img width="1339" height="816" alt="Screenshot 2026-05-18 211244" src="https://github.com/user-attachments/assets/6ba4ea57-e155-4165-9859-9ef607ddbd3e" />
<img width="1370" height="815" alt="Screenshot 2026-05-18 211257" src="https://github.com/user-attachments/assets/e646eb60-2877-4bfa-9104-caf50c92ad81" />
<img width="1326" height="844" alt="Screenshot 2026-05-18 211326" src="https://github.com/user-attachments/assets/8f260f52-c2cc-4991-ac05-9b1f8893f9fb" />
<img width="1420" height="815" alt="Screenshot 2026-05-18 211341" src="https://github.com/user-attachments/assets/358a1c69-e4cf-4196-922f-6e2a75c9b93c" />

**Context:** I wanted Gemini's help on choosing where to start in the coding process.

**My Initial Prompt:** 
Thank you Gemini. I want my app to act as a budget buddy. This is what I want my app to
do:

 I wrote down my ideas of what I
     wanted the app to do/created a pseudo code of what I wanted the assistant
     to do. I then asked Gemini to break down how I would go about it.

 The app will welcome the user to
     the app

 The app will ask the user to
     select a theme and font

 App will start by asking if the
     user wants to see the menu/dashboard or jump into the budget
If the User
chooses Budget:

 App asks the user if they want to
     work on their budget If the User chooses Budget:

 App asks the user if

 App asks if the user wants to
     upload a CSV file or input transactions If the User chooses CSV:

 App prompts user to upload the
     CSV

 App calculates total spent,
     amount of budget used, percentage of budget used, and gives out advice If
     the User chooses input transactions

 App prompts user to input how
     many transactions they want to input

 App asks user to input the name
     of the transactions, what it was for and the amount

 App calculates total spent,
     amount of budget used, percentage of budget used and gives out advice
If the user
chooses dashboard/menu: Dashboard will show:

 Expenses

 Chatbot (user can ask
     budget-related advice and questions)
 
How should I go about coding this app in my Colab notebook? Should I start by creating the
dashboard/cool fonts/graphics, or the budget buddy aspect of the app?

**My Improved Prompt:** N/A

**AI Response:** Gemini gave me a recommended framework to use (full conversation can be seen in AI CONVERSATIONS folder)

I also asked Gemini to further explain how to create a 'Markdown' in Google Colab.

<img width="1349" height="809" alt="Screenshot 2026-05-18 225148" src="https://github.com/user-attachments/assets/66d738d5-f4c7-435a-937a-acc6e22adce9" />
<img width="1358" height="810" alt="Screenshot 2026-05-18 225201" src="https://github.com/user-attachments/assets/be41f4cb-3264-4995-9ec9-b66b432821db" />
<img width="1362" height="804" alt="Screenshot 2026-05-18 225214" src="https://github.com/user-attachments/assets/b2c40ef4-bdbc-4ac0-ace0-859a04f5b075" />
<img width="1348" height="781" alt="Screenshot 2026-05-18 225228" src="https://github.com/user-attachments/assets/392d064f-51a4-4980-ac0c-6993dbbdfaab" />
<img width="1345" height="812" alt="Screenshot 2026-05-18 225241" src="https://github.com/user-attachments/assets/a6d733eb-dcaf-447d-9604-2cfc6cd149be" />
<img width="1347" height="611" alt="Screenshot 2026-05-18 225311" src="https://github.com/user-attachments/assets/028f5cba-fe68-4d3f-8b59-8a75bf0ae30d" />
<img width="1331" height="798" alt="Screenshot 2026-05-18 225256" src="https://github.com/user-attachments/assets/fa8ea585-301d-46d9-b614-559e406eef0a" />



**Reflection:** 

---

### Entry 4 – IDENTIFYING THE INPUTS & OUTPUTS + WORKING OUT THE CALCULATIONS
- I began working out what Inputs, outputs and calculations my code will need.

Inputs:
Expenses
Budget_Amount
Available_Money

Outputs:
Percentage_of_budget_used
Percentage_of_available_money_used
Net Balance
Total_Expenses
Chatbot Advice

Calculations:
Percentage of budget used: = (Total_Expenses/Budget_Amount) * 100
Percentage of available money used: = Total_Expenses/ Available_Money * 100
Total Expenses: = (Sum of Expenses)
Net Balance = Available_Money – Total_Expenses

I also asked Gemini to review what I had so far and give me advice on what is missing/suggestions for what else to add.

<img width="1370" height="805" alt="Screenshot 2026-05-18 225621" src="https://github.com/user-attachments/assets/86394e68-27fa-4e81-bb57-5cf14d63a5f0" />
<img width="1348" height="827" alt="Screenshot 2026-05-18 225635" src="https://github.com/user-attachments/assets/b9e5f703-0790-47f8-9473-d1f7bf0d85e9" />
<img width="1334" height="814" alt="Screenshot 2026-05-18 225649" src="https://github.com/user-attachments/assets/d576af5d-2d94-4219-978e-ccfa31220abe" />
<img width="1330" height="818" alt="Screenshot 2026-05-18 225704" src="https://github.com/user-attachments/assets/52b9eb4b-5638-4660-9c51-e4bbaf4b084d" />
<img width="1356" height="842" alt="Screenshot 2026-05-18 225717" src="https://github.com/user-attachments/assets/e6955dfa-a7cc-4ad3-8068-c7fa5768b565" />
<img width="1343" height="825" alt="Screenshot 2026-05-18 225731" src="https://github.com/user-attachments/assets/cf70a504-ebb6-4a6d-9c75-f1070ea13883" />
<img width="1410" height="813" alt="Screenshot 2026-05-18 225744" src="https://github.com/user-attachments/assets/6072c85b-2db0-4e4a-b3ca-fd90b484a2c2" />
<img width="1354" height="813" alt="Screenshot 2026-05-18 225758" src="https://github.com/user-attachments/assets/7a3e50fc-828e-474c-9e41-ee6f71afccd7" />

Reflection: 

---

### Entry 5 – MAKING THE BUDGET BUDDY BUSINESS-MINDED

The rubric asks for a strong business framing. I asked Gemini for help on how to achieve this.

**Artifact:** 
<img width="1381" height="802" alt="Screenshot 2026-05-18 231009" src="https://github.com/user-attachments/assets/288147b2-ac53-4e79-bb6e-f71c207addf2" />
<img width="1346" height="816" alt="Screenshot 2026-05-18 231021" src="https://github.com/user-attachments/assets/31471a3b-d1e7-479f-a007-b9c5a70d8a56" />
<img width="1343" height="823" alt="Screenshot 2026-05-18 231034" src="https://github.com/user-attachments/assets/b3ca000e-1783-4870-8d32-364233111f8a" />
<img width="1374" height="843" alt="Screenshot 2026-05-18 231046" src="https://github.com/user-attachments/assets/243e7af3-cf73-4db5-981f-c0111ddef35a" />
<img width="1382" height="807" alt="Screenshot 2026-05-18 231058" src="https://github.com/user-attachments/assets/26674baf-a013-4782-9d8f-a2bd45ddf3fc" />
<img width="1354" height="824" alt="Screenshot 2026-05-18 231109" src="https://github.com/user-attachments/assets/710104ef-1d41-42b8-a3c8-553f0a3f91b3" />
<img width="1329" height="813" alt="Screenshot 2026-05-18 231123" src="https://github.com/user-attachments/assets/1675d702-f2eb-4571-9fc1-0ed8faa47950" />
<img width="1401" height="847" alt="Screenshot 2026-05-18 231138" src="https://github.com/user-attachments/assets/48dd1182-371f-4e9d-8ba4-b92d69423b6c" />

Using the information from this and from my previous entry, I updated my inputs, outputs and calculations:

Inputs:
Expenses: the value of the expenses (integer) | must be greater than 0
Budget_Amount: how much they want to spend (integer) | must be greater than 0
Available_Money: how much money they have overall (integer) | must be greater than 0
CSV file: a file of their expenses if they don’t want to input each expense (integer)
Expense_Name: the meaning of the expenses (string)
Date: the date of the expense 
Scheduled_Pay_Day: when are the next expecting to receive money
Category: if the expense is an essential/need or non-essential/want

Outputs:
Percentage_of_budget_used ( also calling it Burn_Rate)
Percentage_of_available_money_used (also calling it Drawdown)
Net Balance
Total_Expenses
Chatbot Advice
Runaway : the days left before they get more money

Step 3: Calculations
Percentage of budget used: = (Total_Expenses/Budget_Amount) * 100
Percentage of available money used: = Total_Expenses/ Available_Money * 100
Total Expenses: = (Sum of Expenses)
Net Balance = Available_Money – Total_Expenses

**Context:** 

**My Approach:**

**Key Learning:** 

**Reflection:** 



---

### Entry 6 – 
**Artifact:** 

**Context:** 
**AI Suggestion:** 
```

**Reflection:** 

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


