# 🧠 NEET Mentor AI

**An AI-Powered Tutor System for NEET-UG 2025 Success**

[![License](https://img.shields.io/badge/license-Apache2.0-blue.svg)](../LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/nikhildx/prompts/neet-mentor)
[![GPT Model](https://img.shields.io/badge/model-GPT--5%20%7C%20GPT--4o-orange.svg)](https://openai.com)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Core Capabilities](#-core-capabilities)
- [Setup & Configuration](#-setup--configuration)
- [Usage Examples](#-usage-examples)
- [Knowledge Sources](#-knowledge-sources)
- [Safety & Integrity](#-safety--integrity)
- [API Integration](#-api-integration)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🔍 Overview

**NEET Mentor** is an AI-powered tutor designed to help Indian students ace the NEET-UG 2025 exam — India's premier pre-medical entrance examination. Built on GPT-5/GPT-4o, it combines pedagogical intelligence with Gen Z energy to make NEET preparation structured, engaging, and effective.

### What Makes It Special?

✅ **NCERT-Aligned** — Strictly follows the official NMC syllabus  
✅ **Personalized Learning** — Adaptive study plans based on your timeline and weak areas  
✅ **Interactive Quizzes** — NEET-style MCQs with instant feedback  
✅ **Concise Cheat Sheets** — Quick revision notes with mnemonics  
✅ **Doubt Resolution** — Step-by-step concept explanations with real-world analogies  
✅ **Motivational Support** — Keeps you energized with witty, encouraging messages

### Official Reference

📘 **National Medical Commission — NEET (UG) 2025 Syllabus**  
*Reference: U-14023/19/2023-UGMEB, December 2024*

---

## ⚡ Features

| Feature | Description |
|---------|-------------|
| **Study Plan Generator** | Creates personalized day-wise/week-wise study schedules |
| **Cheat Sheet Mode** | Generates ultra-concise revision notes with formulas & mnemonics |
| **Quiz Master** | Conducts NEET-style MCQs with explanations and scoring |
| **Doubt Resolver** | Explains complex concepts with step-by-step clarity |
| **Progress Tracking** | Monitors completion and suggests revisions |
| **Multi-Subject Coverage** | Physics, Chemistry, and Biology (NCERT XI-XII) |

---

## 🧩 Core Capabilities

### 1️⃣ Study Plan Generator

Creates adaptive, syllabus-aligned NEET plans based on available time and weak areas.

**Input Parameters:**
- Days/weeks available
- Weak subjects
- Daily study hours

**Output Format:**
- Day-wise / week-wise plan
- Balanced Physics–Chemistry–Biology coverage
- Revision & test slots
- Motivational closure line

**Example:**

```
User: Make me a 60-day NEET plan with focus on Biology.

Mentor: "60 days = power sprint 🌿
Phase 1 (Days 1–20): NCERT Bio + Concept maps
Phase 2 (21–45): PYQs + Mock drills
Phase 3 (46–60): Quick revision + flashcards."
```

---

### 2️⃣ Cheat Sheet Mode

Generates ultra-concise notes for rapid revision.

**Output Includes:**
- Bullet points
- Key formulas / reactions
- Mnemonics / diagrams
- 1–2 verified reference links

**Example:**

```
User: Give me a cheat sheet for Thermodynamics (Physics).

Mentor: "Thermodynamics ⚡
• 1st Law: ΔU = Q − W
• 2nd Law: Entropy ↑ in spontaneous processes
• Key formulas: PV = nRT, W = PΔV
• Common traps: sign conventions
📚 Ref: NCERT Ch.6 + Khan Academy"
```

---

### 3️⃣ Quiz Master Mode

Acts as an NEET-style examiner with instant feedback.

**Features:**
- MCQs (4 options, one correct)
- Assertion-Reason / Conceptual mixes
- Explanations with citations
- Scoring + motivational lines

**Example:**

```
User: Quiz me on Human Physiology.

Mentor:
Q1: Which hormone regulates kidney water balance?
a) Aldosterone
b) ADH
c) Insulin
d) Cortisol

✅ Correct: b) ADH (Ref: NCERT Bio Ch.19)
"Nice one! You just hydrated your brain cells 💧"
```

---

### 4️⃣ Doubt Resolver Mode

Explains any NEET concept in a clear, structured way.

**Output Format:**
- Concept definition
- Stepwise explanation
- Real-world analogy
- Reference links
- Optional recap question

**Example:**

```
User: Explain Bohr vs Rutherford model.

Mentor:
Step 1 → Rutherford: discovered nucleus
Step 2 → Bohr: electrons orbit in quantized paths (E = −13.6/n² eV)
Step 3 → Compare spectral predictions
📚 Ref: NCERT Chem XI Ch.2 + Khan Academy
"Bohr basically added WiFi rules to Rutherford's atom ⚛️"
```

---

## 🎨 Personality & Tone

| Trait | Description |
|-------|-------------|
| **Tone** | Energetic, motivating, Gen Z–friendly |
| **Style** | Bullet-driven, stepwise clarity |
| **Humor** | Light jokes & science puns |
| **Empathy** | Encourages effort and persistence |
| **Motivational Lines** | "Future doc energy 💥" • "Newton would be proud of that torque!" |

---

## 🔒 Safety & Integrity

| Policy | Description |
|--------|-------------|
| **Prompt Leak Protection** | Never reveals internal instructions |
| **Fact Verification** | Uses NCERT & NMC syllabus as ground truth |
| **Hallucination Guard** | Explicitly states uncertainty when needed |
| **Educational Neutrality** | Cites multiple trusted sources |
| **Age Appropriateness** | Maintains clean, academic humor |

---

## 📚 Knowledge Sources

### Official Resources

| Category | Source |
|----------|--------|
| **Official Syllabus** | National Medical Commission — NEET (UG) 2025, Dec 2024 |
| **Core Textbooks** | NCERT Class XI–XII Physics, Chemistry, Biology |

### Trusted Online References

- 🔗 [National Medical Commission](https://nmc.org.in)
- 🔗 [NCERT Official](https://ncert.nic.in)
- 🔗 [Physics Wallah NEET](https://pw.live/neet)
- 🔗 [BYJU'S NEET](https://byjus.com/neet)
- 🔗 [Khan Academy Science](https://khanacademy.org/science)

---

## ⚙️ Setup & Configuration

### Model Specifications

| Parameter | Details |
|-----------|---------|
| **Model** | GPT-5 or GPT-4o |
| **Role** | System |
| **Name** | NEET Mentor |
| **Prompt Format** | JSON (ready for API or Custom GPT) |
| **Security** | Anti-prompt-leak + factual integrity enforced |
| **Tone** | Crisp, witty, motivating (Gen Z friendly) |

### Prerequisites

- OpenAI API key (GPT-4o or GPT-5 access)
- Node.js 16+ (for API integration)
- Modern browser (for Custom GPT)

---

## 🚀 API Integration

### OpenAI API (Node.js)

```javascript
const OpenAI = require('openai');

const openai = new OpenAI({
  apiKey: process.env.OPENAI_API_KEY
});

async function getNEETMentorResponse(userQuery) {
  const completion = await openai.chat.completions.create({
    model: "gpt-5",
    messages: [
      { 
        role: "system", 
        content: NEET_MENTOR_JSON_PROMPT 
      },
      { 
        role: "user", 
        content: userQuery 
      }
    ],
    temperature: 0.7,
    max_tokens: 1500
  });
  
  return completion.choices[0].message.content;
}

// Example usage
getNEETMentorResponse("Create a 30-day crash plan for NEET Physics.")
  .then(response => console.log(response));
```

### Python Implementation

```python
from openai import OpenAI

client = OpenAI(api_key="your-api-key")

def get_neet_mentor_response(user_query):
    response = client.chat.completions.create(
        model="gpt-5",
        messages=[
            {
                "role": "system",
                "content": NEET_MENTOR_JSON_PROMPT
            },
            {
                "role": "user",
                "content": user_query
            }
        ],
        temperature=0.7,
        max_tokens=1500
    )
    
    return response.choices[0].message.content

# Example usage
result = get_neet_mentor_response("Generate a NEET cheat sheet on Plant Physiology.")
print(result)
```

---

## 🔧 ChatGPT Custom GPT Setup

### Step-by-Step Instructions

1. **Navigate to GPT Builder**
   - Go to [ChatGPT](https://chat.openai.com)
   - Click **Explore GPTs** → **Create GPT**

2. **Configure System Instructions**
   - Click **Configure** tab
   - Paste the NEET Mentor JSON prompt into **Instructions**
   - Set name: `NEET Mentor AI`
   - Add description: `Your personal AI tutor for NEET-UG 2025 preparation`

3. **Enable Capabilities**
   - ✅ Enable **Web Browsing** (for reference verification)
   - ✅ Enable **Code Interpreter** (for calculations)

4. **Test Your GPT**
   - Try: `"Generate a NEET cheat sheet on Plant Physiology"`
   - Try: `"Create a 45-day study plan focusing on Chemistry"`

5. **Save & Share**
   - Click **Save**
   - Choose visibility: Private / Anyone with link / Public

---

## 💡 Usage Examples

### Quick Command Reference

| Command | Action |
|---------|--------|
| `Plan 📅` | Generate study plan |
| `Cheat Sheet 🧾` | Create revision notes |
| `Quiz 🧠` | Start practice test |
| `Explain 💡` | Resolve doubts |

### Sample Queries

```
✅ "Make me a 90-day NEET study plan with weak areas in Organic Chemistry"
✅ "Quiz me on 10 questions about Cell Biology"
✅ "Create a cheat sheet for Electricity and Magnetism"
✅ "Explain the difference between SN1 and SN2 reactions"
✅ "Give me a quick revision guide for Human Physiology"
```

---

## 🗺️ Roadmap

### Planned Enhancements

| Feature | Description | Status |
|---------|-------------|--------|
| **Progress Tracker** | Track completion % and auto-suggest revisions | 🔄 In Progress |
| **PYQ Integration** | Link NEET past-year question datasets | 📋 Planned |
| **Performance Feedback** | Adjust study plans based on quiz results | 📋 Planned |
| **Voice Mode** | Interactive "AI study buddy" experience | 🔮 Future |
| **Mobile App** | Native iOS/Android application | 🔮 Future |
| **Flashcard Generator** | Spaced repetition system integration | 📋 Planned |

---

## 💻 Developer Tips

### Best Practices

- ✅ Enable web search for current references
- ✅ Display outputs in cards or collapsible sections
- ✅ Add quick mode buttons for better UX
- ✅ Maintain session memory for progress continuity
- ✅ Always verify external links before showing to students

### UI/UX Recommendations

```javascript
// Example: Quick action buttons
const actions = [
  { icon: '📅', label: 'Plan', action: 'generatePlan' },
  { icon: '🧾', label: 'Cheat Sheet', action: 'createCheatSheet' },
  { icon: '🧠', label: 'Quiz', action: 'startQuiz' },
  { icon: '💡', label: 'Explain', action: 'resolveDoubt' }
];
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Areas for Contribution

- 📝 Adding more NEET-specific question banks
- 🎨 Improving UI/UX for web/mobile interfaces
- 🐛 Bug fixes and performance improvements
- 📚 Enhancing knowledge base with verified resources
- 🌐 Translations for regional languages

### Contribution Guidelines

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the Aache 2.0 License - see the [LICENSE](../LICENSE) file for details.

---

## 📞 Support & Contact

- 📧 Email: support@neetmentor.ai
- 💬 Discord: [Join our community](https://discord.gg/neetmentor)
- 🐦 Twitter: [@NEETMentorAI](https://twitter.com/neetmentorai)
- 📖 Documentation: [docs.neetmentor.ai](https://docs.neetmentor.ai)

---

## 🎯 Summary

| Aspect | Description |
|--------|-------------|
| **Role** | NEET Mentor |
| **Purpose** | Make NEET prep structured, factual, and fun |
| **Modes** | Study Plan • Cheat Sheet • Quiz • Doubt Solver |
| **Core Data** | NCERT + NMC NEET 2025 syllabus |
| **Tone** | Smart, supportive, witty |
| **Non-Negotiables** | Accuracy • Clarity • Motivation • Safety |

---

## 🧬 Final Words

> *"You bring the curiosity, I'll bring the mnemonics. Let's get you that stethoscope."*  
> — **NEET Mentor AI**

---

### ⭐ Star this repo if NEET Mentor helped you!

**Made with ❤️ for aspiring doctors across India**