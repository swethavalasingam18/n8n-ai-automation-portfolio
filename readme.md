# 🚀 AI Content Studio v2.0

## 📌 Project Overview

AI Content Studio v2.0 is an AI-powered content generation workflow built using **n8n**, **Google Gemini AI**, and **Google Sheets**.

The workflow automatically reads content ideas from Google Sheets, sends them to Google Gemini AI for content generation, processes the AI response using JavaScript, and updates the generated content back into Google Sheets.

This automation eliminates manual content writing and enables fast AI-powered content generation for blogs, social media posts, product descriptions, captions, and marketing content.

---

# 🎯 Features

✅ Read content ideas from Google Sheets

✅ Generate AI content using Google Gemini

✅ Process AI response using JavaScript

✅ Automatically update Google Sheets

✅ Fully automated workflow

---

# 🛠 Technologies Used

- n8n
- Google Gemini AI
- Google Sheets
- JavaScript
- JSON

---

# 📊 Workflow Architecture

Manual Trigger

↓

Read Data from Google Sheets

↓

Google Gemini AI Agent

↓

JavaScript Processing

↓

Update Google Sheets

---

# 📥 Input

Google Sheet contains:

| Topic | Keywords | Tone | Target Audience |
|-------|----------|------|-----------------|
| AI Tools | Productivity | Professional | Business Owners |

---

# 🤖 AI Processing

The AI Agent receives:

- Topic
- Keywords
- Writing Style
- Audience

Gemini generates:

- SEO Title
- Content
- Summary
- Social Caption (Optional)

---

# 📤 Output

Google Sheet automatically updates with:

- AI Generated Content
- SEO Title
- Summary
- Status

---

# 🧠 Workflow Nodes

## 1️⃣ Manual Trigger

Starts the workflow manually.

---

## 2️⃣ Google Sheets (Read)

Reads pending content requests from Google Sheets.

---

## 3️⃣ Google Gemini AI Agent

Generates high-quality AI content based on the provided prompt.

---

## 4️⃣ JavaScript Code Node

Processes AI output.

Example tasks:

- Clean AI response
- Remove unnecessary formatting
- Format JSON
- Prepare output for Google Sheets

---

## 5️⃣ Google Sheets (Update Row)

Updates the generated AI content back into the corresponding Google Sheet row.

---

# 📂 Project Structure

AI Content Studio v2.0/

├── README.md

├── workflow.json

├── project-notes.md

├── prompts/

│ └── ai_prompt.txt

├── code/

│ └── code_node.js

└── assets/

├── workflow.png

├── execution.png

├── google-sheet.png

└── output.png

---

# 💡 AI Prompt

Stored inside:

prompts/ai_prompt.txt

Example:

Generate high-quality content using the provided topic.

Requirements:

- SEO Optimized
- Professional Tone
- Engaging
- Easy to Read

Return clean text only.

---

# 💻 JavaScript

Stored inside:

code/code_node.js

Purpose:

- Parse AI output
- Remove unnecessary formatting
- Prepare final response
- Send data to Google Sheets

---

# 📸 Assets

workflow.png

Complete workflow

execution.png

Successful execution

google-sheet.png

Google Sheet before & after update

output.png

Generated AI content

---

# 🚀 Future Improvements

- Multiple AI Models

- OpenAI Support

- Claude Support

- Blog Generation

- LinkedIn Post Generator

- Instagram Caption Generator

- Facebook Post Generator

- Email Generator

- Content Scheduling

- WordPress Publishing

---

# 📚 Skills Demonstrated

✔ AI Automation

✔ Prompt Engineering

✔ Google Gemini Integration

✔ Google Sheets Automation

✔ JavaScript

✔ JSON Processing

✔ n8n Workflow Design

✔ AI Content Generation

---

# 🎯 Real-world Use Cases

- Marketing Agencies

- Content Writers

- SEO Teams

- Bloggers

- Freelancers

- Digital Marketing

- Social Media Management

---

# 📈 Workflow Summary

Google Sheet

↓

Read Pending Topic

↓

Google Gemini AI

↓

Generate Content

↓

JavaScript Processing

↓

Update Google Sheet

---

# 👨‍💻 Author

Developed by Swetha
