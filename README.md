# CyberSecurityBot
Year 2 POE Programming
# 🛡️ Cybersecurity Chatbot - POE Part 1 and 2 - PROG6221

Welcome to the Cybersecurity Chatbot — a C# console-based chatbot that teaches users about online safety and cybersecurity principles.

> 🔧 Created by **Prean Govender**  
> 📚 Module: PROG6221 - Programming 2A  
> 🧑‍🎓 Student Number: ST10447995  
> 📅 Year: 2025  
> 🎯 Assignment: POE Part 1

---

## 🧠 Features

This chatbot demonstrates several intelligent response techniques based on user input:

### ✅ 1. Predefined Responses
Basic greetings and fixed questions like "Hello", "How are you", "What is your purpose".

### ✅ 2. Keyword Recognition
Identifies and responds to key cybersecurity terms such as:
- **phishing**
- **password**
- **privacy**
- **safe browsing**
- **scam**

### ✅ 3. Random Tips
Gives **random cybersecurity tips** for phishing, password safety, and safe browsing.

### ✅ 4. Conversation Memory
- Remembers the **last topic** and provides **follow-up answers** when the user asks "Tell me more".
- Remembers user's **favorite topic** and responds accordingly.

### ✅ 5. Sentiment Detection
Detects user emotions such as:
- "worried"
- "frustrated"
- "curious"

... and replies with **empathetic encouragement**.

---

## ▶️ How to Run

1. **Open the solution in Visual Studio (`POE_PART1_CHATBOT.sln`)**
2. **Build the solution** to make sure there are no syntax errors
3. **Run the application** (it’s a console app)
4. Type your messages to the chatbot and explore its responses.

---

## 🔄 GitHub Actions - Continuous Integration

This project uses **GitHub Actions** to automatically check:
- ✅ Syntax errors (via `dotnet build`)
- ✅ Code formatting (via `dotnet format`)
- ✅ Build success on each push

You can view the status under the **Actions** tab in the GitHub repo. ✅ = passed build.

---

## 🔊 WAV File

The project includes a WAV file named `greeting.wav`.

You can test playing the audio file using a WAV player like:
- Windows Media Player
- Or use `System.Media.SoundPlayer` in C# for playback in code

```csharp
System.Media.SoundPlayer player = new System.Media.SoundPlayer("greeting.wav");
player.Play();

