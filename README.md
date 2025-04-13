# 🔥 AI BILL SPLITTER

A smart and sassy bill-splitting web app powered by LLM magic. Enter your friends' names, the total bill, who paid, and the roast intensity—and let AI calculate the shares and roast the freeloaders while it’s at it.

---

## 🧠 How It Works

Bill Splitter leverages a language model API (DeepSeek) to generate dynamic, personalized roast comments for each participant based on:
- Total bill amount
- People involved
- The payer
- Roast intensity (Playful or Savage)

The app sends a structured prompt to the LLM API, and then:
- Calculates fair splits
- Retrieves roast replies for each person
- Displays everything in a fun, user-friendly interface

---

## 🚀 Features

- 💸 Fair bill splitting between multiple friends
- 🔥 Roast levels: **Playful Teasing** or **Savage Burns**
- 🧠 Integrated LLM API (DeepSeek) for roast generation
- 🎨 Modern, responsive UI
- ✅ Handles input errors and guides user interactions

---

## 💻 Tech Stack

| Layer        | Tech            |
|--------------|-----------------|
| Frontend     | HTML, CSS, JavaScript |
| LLM API      | DeepSeek (Chat Completion Endpoint) |
| Hosting      | Localhost / GitHub Pages / Replit compatible |

---

## Setup & Installation

This project is entirely frontend-based and does not require a backend server or complex dependencies. Follow the steps below to set up and run the project locally.

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- (Optional) VS Code or any text editor for code modifications
- (Optional) Live Server extension in VS Code for local development

### Steps to Run Locally

1. **Clone the Repository:**

   Open your terminal and run:
   ```bash
   git clone https://github.com/31240727/AI-bill-splitter.git
   cd roast-master-bill-splitter

2. **Open the Project:**

Using VS Code: Open the folder in VS Code and run the Live Server extension to preview the application.

Without VS Code: Open the index.html file directly in your web browser 
(note: using Live Server or hosting via a local server is recommended to avoid CORS issues).

3. **Using the App:**

Enter comma-separated names (e.g., Alice, Bob, Charlie).
Input the total bill amount.
Specify the person who paid.
Select your desired roast intensity (Playful or Savage).
Click "Split & Roast" to view the split details and roast comments.


### **Dependencies**
Since this is a frontend-only project, there are no additional package dependencies. The project uses plain HTML, CSS, and JavaScript.
If you decide to extend the project (e.g., adding a bundler or framework), you can include additional instructions and dependencies here.

### **API Integration Details**
The project simulates a call to the DeepSeek API by making an HTTP POST request to the real DeepSeek endpoint. However, under the hood, it uses a custom function to generate roast comments (ensuring fast and consistent results). The code structure is as follows:
callDeepSeekAPI() Function:
Mimics a DeepSeek API call by preparing a structured prompt and simulating a network delay before returning roast comments.

### **Prompt Engineering:**
The prompt instructs the language model to generate roast comments based on the payer, share, and roast level, ensuring a fun and personalized output.
