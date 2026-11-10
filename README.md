# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
# Name: Sowmiya R
# Reg No: 212225040420

## AIM
To evaluate and compare the effectiveness of prompting techniques across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- Accuracy
- Coherence
- Simplicity
- Speed
- User experience

## AI Tools Used:
- ChatGPT
- Google Gemini
- Claude
- Microsoft Copilot

## Algorithm

### Step 1: 
Select a technical article on "The Basics of Blockchain Technology".

### Step 2:
Prepare four prompting techniques: Zero-Shot, Few-Shot, Chain-of-Thought and Role-Based Prompting.

### Step 3:
Open the AI platforms such as ChatGPT, Gemini, Claude and Microsoft Copilot.

### Step 4:
Enter the same article and apply each prompting technique.

### Step 5:
Generate summaries using all four AI platforms.

### Step 6:
Collect and save the generated outputs.

### Step 7:
Evaluate the summaries based on accuracy, coherence, simplicity, speed and user experience.

### Step 8:
Compare the results obtained from different AI platforms and prompting techniques.

### Step 9:
Identify the best-performing AI platform and prompting technique based on the evaluation.


## PROMPT ENGINEERING TECHNIQUES:

## 1. Basic Prompting:
### Prompt:
Provide a short summary on the article 'The Basics of Blockchain Technology' in simple English.

### Output:
Summary: The Basics of Blockchain Technology

Blockchain is a digital technology used to store information securely. It records data in blocks that are connected together in a chain. Each block contains information about transactions. The data is shared across many computers, making it difficult to change or hack. Blockchain provides transparency, security, and trust without the need for a central authority. It is mainly used in cryptocurrencies, banking, healthcare, and supply chain management.

## 2. Role based Prompting:
### Prompt:
Act as a technical content writer and summarize the article titled "The Basics of Blockchain Technology" for undergraduate students. Explain the technical concepts in simple language.

### Output:
## Blockchain Basics: A Summary for Undergraduates

**The big idea.** Blockchain can be defined as an immutable, decentralized digital ledger that is duplicated and distributed across an entire network. Think of a shared notebook that thousands of people hold identical copies of. Nobody owns it, and everyone can check it.

**The problem it solves.** Blockchain started as a technology to solve one problem: establishing trust in a trustless environment. Normally a bank or government vouches that a transaction is real. A blockchain lets strangers agree on what happened without a middleman.

### Key concepts in plain language

- **Block:** A page in the notebook. It holds a batch of records (such as "Asha paid Ravi 5 coins") plus a timestamp.
- **Chain:** Each block stores a fingerprint (a *hash*) of the block before it, so the pages are linked in order. Changing an old page changes its fingerprint, which breaks every link after it. This is why the record is called *immutable* (practically impossible to alter quietly).
- **Hash:** A function that turns any data into a short, fixed-length code. A tiny change in the input produces a completely different code, so tampering is easy to spot.
- **Decentralization:** There is no central governing body, and a group of nodes maintains the network. A *node* is just a computer that holds a copy of the ledger and checks new entries.
- **Consensus mechanism:** The rule nodes follow to agree on which new block gets added. The two major groups are Proof of Work and Proof of Stake. In Proof of Work, computers compete to solve a hard puzzle (this is "mining"). In Proof of Stake, participants lock up their own coins as a deposit and lose them if they cheat.
- **Smart contracts:** Programs that can also be stored on the blockchain. They run automatically when conditions are met, like a vending machine for agreements.

### How a transaction works, step by step

1. Someone requests a transaction.
2. The request is broadcast to the network's nodes.
3. Nodes verify it, using the consensus rule.
4. The transaction is bundled into a new block.
5. The block is linked to the chain, and every node updates its copy.

### Benefits and drawbacks

| Benefits | Drawbacks |
|---|---|
| Transparent: all participants can view the ledger | Complex for non-technical users to understand and implement |
| Tamper-resistant records | Still a target for hacks and attacks, like any connected technology |
| No middleman needed | Open in theory, but much of the technology is in the hands of a few. |

## 3. Context Based Prompting
### Prompt:
You are working for an educational platform that provides short summaries of technical research articles to undergraduate students.Most students have basic computer knowledge but may not have prior knowledge of blockchain technology.The purpose of this summary is to help students quickly understand the article without reading the entire 500-word text.Summarize the following article, "The Basics of Blockchain Technology". Explain the fundamental concepts and real-world applications using simple english.

### Output:
### Summary: The Basics of Blockchain Technology

Blockchain is a digital technology used to store and share information securely. It works like a digital record book where information is stored in blocks connected in a chain. Each block contains transaction details, a timestamp, and a unique code called a hash.

Blockchain uses a network of computers to verify transactions instead of depending on a single central authority. Once information is added and verified, it is very difficult to change or delete. This makes blockchain secure and reliable.

### Fundamental Concepts:

1. Blocks: Store transaction information.
2. Chain: Connects all blocks in a sequence.
3. Hash: A unique digital code used to identify and protect each block.
4. Decentralization: Data is shared across many computers instead of being controlled by one organization.
5. Consensus: A process through which computers agree that transactions are valid.

### Real-World Applications:

- Cryptocurrency: Used for digital currencies like Bitcoin.
- Banking: Helps make digital transactions secure.
- Healthcare: Stores and manages medical records.
- Supply Chain: Tracks products from manufacturers to customers.
- Digital Identity: Helps verify user identities securely.

### Conclusion:

Blockchain is a modern technology that provides security, transparency, and trust in digital transactions. It is useful in many industries because it reduces fraud, improves data management, and makes transactions more reliable.


## 4. Constraint Based Prompting
### Prompt:
Summarize the article titled "The Basics of Blockchain Technology" by following these constraints:

- The summary must contain 100–120 words.
- Use simple and clear English.
- Include only the important concepts.
- Avoid unnecessary technical terms.
- Avoid repetition.
- Use grammatically correct sentences.

### Output:
#### Summary: The Basics of Blockchain Technology
Blockchain is a digital technology used to store and share information securely. It works like a digital record book where information is stored in blocks connected in a chain. Each block contains transaction details and a unique code. Information is shared across many computers instead of being controlled by one central authority. This makes blockchain more secure and transparent. Once information is recorded, it is very difficult to change or delete. Blockchain is widely used in cryptocurrency, banking, healthcare, supply chain management, and digital identity verification. It helps reduce fraud, improve data security, and make transactions faster and more reliable.


## 5. Output Format Prompt
### Prompt:
Summarize the article titled "The Basics of Blockchain Technology" using the following structured format:
1. Introduction
2. Key Concepts
3. Working Principle
4. Applications
5. Conclusion

### Output:
## Summary: The Basics of Blockchain Technology

### 1. Introduction

Blockchain is a digital technology used to store and share information securely. It maintains records in a digital format without depending on a central authority.

### 2. Key Concepts

- Blocks: Store transaction information.
- Chain: Connects blocks in a sequence.
- Hash: A unique code that identifies each block.
- Decentralization: Data is shared across multiple computers.
- Consensus: A process used to verify transactions.

### 3. Working Principle

When a transaction takes place, it is shared with a network of computers. The computers verify the transaction through a common agreement. Once approved, the transaction is stored in a new block and connected to the existing chain.

### 4. Applications

- Cryptocurrency (Bitcoin).
- Banking and digital payments.
- Healthcare record management.
- Supply chain tracking.
- Digital identity verification.

### 5. Conclusion

Blockchain is a secure and transparent technology that improves data management, reduces fraud, and builds trust in digital transactions. It has many useful applications in different industries.


# CROSS-PLATFORM OUTPUT COMPARISON

| AI Platform       | Prompting Technique | Output Quality | Main Observation                                                |
| ----------------- | ------------------- | -------------- | --------------------------------------------------------------- |
| ChatGPT           | Basic               | Good           | Generated a simple summary covering the main concepts.          |
| ChatGPT           | Role                | Very Good      | Explained blockchain using student-friendly language.           |
| ChatGPT           | Context             | Very Good      | Focused on concepts relevant to undergraduate students.         |
| ChatGPT           | Constraint          | Very Good      | Followed the word limit and avoided unnecessary details.        |
| ChatGPT           | Output Format       | Excellent      | Presented information under clear headings.                     |
| Gemini            | Basic               | Good           | Provided a brief explanation of blockchain.                     |
| Gemini            | Role                | Very Good      | Included clear explanations and relevant examples.              |
| Gemini            | Context             | Excellent      | Connected blockchain concepts with practical applications.      |
| Gemini            | Constraint          | Very Good      | Produced a concise summary following the instructions.          |
| Gemini            | Output Format       | Excellent      | Organized the summary into structured sections.                 |
| Claude AI         | Basic               | Very Good      | Included important concepts with logical flow.                  |
| Claude AI         | Role                | Very Good      | Generated a detailed student-oriented explanation.              |
| Claude AI         | Context             | Excellent      | Provided relevant explanations with good conceptual coverage.   |
| Claude AI         | Constraint          | Very Good      | Maintained clarity while following the given restrictions.      |
| Claude AI         | Output Format       | Excellent      | Generated a detailed and well-organized summary.                |
| Microsoft Copilot | Basic               | Good           | Generated a short and understandable summary.                   |
| Microsoft Copilot | Role                | Very Good      | Explained the topic in beginner-friendly language.              |
| Microsoft Copilot | Context             | Very Good      | Focused on the educational purpose of the task.                 |
| Microsoft Copilot | Constraint          | Excellent      | Produced a concise response following the specified conditions. |
| Microsoft Copilot | Output Format       | Very Good      | Followed the requested headings and structure.                  |



# OVERALL FINDINGS

| Prompting Technique  | Finding Based on Generated Output                                         |
| -------------------- | ------------------------------------------------------------------------- |
| Basic Prompt         | Generates a general summary                     |
| Role Prompt          | Provides explanations according to the assigned role and audience.        |
| Context Prompt       | Improves relevance by considering the educational background and purpose. |
| Constraint Prompt    | Controls summary length, language, and content.                           |
| Output Format Prompt | Produces structured content with headings and organized information.      |

# CONCLUSION

The experiment shows that prompting techniques have a significant impact on AI-generated text summaries. Basic prompting produces general summaries, while role and context prompting improve audience relevance. Constraint prompting helps maintain the required length and simplicity, whereas output format prompting provides better organization. The four AI platforms demonstrate different strengths in generating summaries. Therefore, the effectiveness of an AI-generated summary depends on both the prompting technique and the AI platform used.

# Result
This experiment helped in understanding the importance of prompt engineering in Generative AI. Different prompting techniques can produce different results even when the same topic is given to an AI system. Selecting an appropriate prompting strategy helps users obtain more accurate, relevant and well-organized responses.
Therefore, effective prompt writing is an important skill for making better use of modern AI tools.
