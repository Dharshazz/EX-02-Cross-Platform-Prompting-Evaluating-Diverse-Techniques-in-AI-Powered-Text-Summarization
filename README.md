# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
# 1. ChatGPT (GPT-4/5) + Structured Output Prompt
```
Prompt:
“Summarize this article on blockchain in under 300 words for undergraduate students. Use three sections: (1) What blockchain is, (2) How it works, (3) Why it matters.”

Output (sample):
1. What blockchain is:
Blockchain is a digital ledger system where information is stored across many computers instead of one central server. It records transactions in blocks that are linked together, making the data permanent and tamper-proof.

2. How it works:
Each block contains a list of transactions and a unique code (hash). Once added, blocks are connected to the chain in chronological order. A consensus system ensures everyone agrees on the data, preventing fraud.

3. Why it matters:
Blockchain provides security, transparency, and trust without needing banks or central authorities. It supports cryptocurrencies like Bitcoin, but also supply chain tracking, voting systems, and digital identity management.

Evaluation:

Accuracy: ⭐⭐⭐⭐⭐

Coherence: ⭐⭐⭐⭐

Simplicity: ⭐⭐⭐⭐

Speed: ⭐⭐⭐⭐

UX: ⭐⭐⭐⭐⭐
```

# 2. Claude + Role-based Prompt
```
Prompt:
“You are a university lecturer. Explain this blockchain article to first-year undergraduates in a friendly and clear way.”

Output (sample):
“Imagine a notebook that everyone in class can see, but no one can erase. That’s blockchain. Instead of one person holding it, copies are everywhere. When a new note is added, the whole class agrees it’s valid before it’s written permanently. This prevents cheating. Blockchain isn’t just about Bitcoin—it’s about trust. It can track food safety, secure elections, and protect medical records. Think of it as the internet’s way of keeping receipts safe forever.”

Evaluation:

Accuracy: ⭐⭐⭐⭐⭐

Coherence: ⭐⭐⭐⭐⭐

Simplicity: ⭐⭐⭐⭐

Speed: ⭐⭐⭐

UX: ⭐⭐⭐⭐
```
# 3. Gemini + Zero-shot Prompt
```
Prompt:
“Summarize this blockchain article in simple words.”

Output (sample):
“Blockchain is a record-keeping system that works without banks. Data is stored in linked ‘blocks.’ Each block is secure and can’t be changed. People use it for cryptocurrencies like Bitcoin and also for things like shipping, voting, and contracts. Its main strength is trust and transparency.”

Evaluation:

Accuracy: ⭐⭐⭐⭐

Coherence: ⭐⭐⭐

Simplicity: ⭐⭐⭐⭐

Speed: ⭐⭐⭐⭐⭐

UX: ⭐⭐⭐
```

# 4. Cohere + Step-by-step Prompt
```
Prompt (2-step):
Step 1: “List the main points of this blockchain article.”
Step 2: “Now explain those points simply, as if to high schoolers.”

Output (sample):
“Blockchain is:

A digital ledger shared by many computers.

Each block stores transactions permanently.

Security is ensured by agreement among users.

It powers Bitcoin and many other uses.

In simple words: Blockchain is like a shared Google Doc where every change is locked forever. It helps people trust information without needing a teacher or bank to watch over it.”

Evaluation:

Accuracy: ⭐⭐⭐

Coherence: ⭐⭐⭐

Simplicity: ⭐⭐⭐⭐⭐

Speed: ⭐⭐⭐

UX: ⭐⭐⭐
```

# 📊 Final Comparison
<img width="1978" height="1963" alt="image" src="https://github.com/user-attachments/assets/26cde231-afb5-4909-90d1-fa50bc2679ba" />

## Result
Thus Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Tex t-Summarization is executed successfully

