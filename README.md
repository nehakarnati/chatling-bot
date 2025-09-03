# Namaste Navigator Chatbot – Build Process

This README documents the step-by-step process of building **Namaste Navigator**—an AI-powered travel assistant for exploring India—using the **Chatling** platform.  

---

## 🌐 Overview
**Namaste Navigator** helps users discover India’s diverse regions, themes, and destinations. It combines structured conversation flows with a knowledge base of curated documents, and even allows meeting bookings with travel guides.

---

## 🛠️ Prerequisites
- A registered account on [Chatling AI](https://chatling.ai)  
- Prepared travel content (PDFs with region/theme details)  
- (Optional) Cal.com account for booking integration  
- Basic familiarity with chatbot flow builders(**must refer documentation for this**)

---

## 📂 1. Prepare Knowledge Base
Organize documents for training:  

- **State-wise guides** (e.g., `states.pdf`)  
- **Themes**: Spiritual Journeys, Beaches, Hill Stations, Wildlife, Culture, Heritage  
- **Regional breakdowns**: North, South, East, West India  
- Use **clear file names** for quick reference. ✅
  
- <img width="257" height="411" alt="Screenshot 2025-09-03 234120" src="https://github.com/user-attachments/assets/f4c7ec77-02bb-4287-a4c0-9c3a0b7b7e34" />
 

---

## 🤖 2. Create the Chatbot
1. Log in to Chatling dashboard.  
2. Click **Create New Bot**.  
3. Name it **Namaste Navigator**.  
4. Add a travel-friendly welcome message.

<img width="1314" height="835" alt="Screenshot 2025-09-03 234322" src="https://github.com/user-attachments/assets/a4b0dd76-bdd0-4eb4-933e-50a19290feac" />


---

## 🗺️ 3. Design Conversation Flow
Use Chatling’s visual builder:  

- **Start Node** → Friendly intro  
- **Main Menu**:  
  - Book a Meeting with Guide  
  - Explore Places  
  - Learn About Each Place  
  - Submit Details  

### Example Branches:
- **Explore Places** → By Region (North, South, East, West) or By Theme (Beaches, Hills, Wildlife, Culture, Spiritual) or Top Picks(TajMahal. Golden Temple, Red Fort, Gateway of India, Hawa Mahal 
- **Booking Flow** → Calendar form + Cal.com integration  

<img width="1721" height="497" alt="Screenshot 2025-09-03 234604" src="https://github.com/user-attachments/assets/6547147e-7e7d-4cff-a9f6-338d3fadeb7a" />

---

## 🏞️ 4. Add Regional & Thematic Blocks
- Each block greets the user and asks for specific needs.  
- Example:  
  > “Welcome to North India! What would you like to explore—Himalayas, culture, or spiritual journeys?”  



## 📚 5. Connect Knowledge Base
- Configure AI blocks to **search uploaded documents**.  
- Add fallback responses like:  
  > “I don’t have that info right now, but I can guide you to related options.”  

<img width="1855" height="476" alt="Screenshot 2025-09-03 234757" src="https://github.com/user-attachments/assets/aad24ca0-29ab-46d9-89c4-c3f43423b826" />

Test queries such as:  
- *“Best beaches in Goa”*  
- *“Wildlife sanctuaries in South India”*  

---

## 📅 6. Add Booking Integration
- Insert a **Calendar Form**: Name, Email, Phone, Nationality  
- Connect with **Cal.com** for real-time booking  
- Provide clear success/failure messages  

---

## 🙏 7. Conversation Endings
- Add **thank you messages** + travel inspiration  
- Example:  
  > “✨ Thanks for exploring with Namaste Navigator! Ready for your next journey? 🇮🇳”  

---

## 🔍 8. Test & Iterate
- Use Chatling Preview to simulate flows  
- Ensure no dead-ends  
- Fine-tune prompts and docs for clarity  

---

## 🚀 9. Publish & Deploy
- Click **Publish** in Chatling  
- Share the link or **embed chatbot in your website** (via `<iframe>`)  

---
## 📖 10. Documentation Help

For more detailed guidance on building and deploying chatbots with Chatling, check out the official documentation:

👉 [Chatling Documentation – Getting Started](https://docs.chatling.ai/getting-started)

This resource includes:
- Step-by-step tutorials
- Platform features overview
- Best practices for chatbot design
- Integration instructions (embedding, APIs, etc.)

 

---

### 🔗 Live Chatbot Link
👉 [Namaste Navigator on Chatling](https://share.chatling.ai/s/Wa8P7uGKVRCE51m)  

---

