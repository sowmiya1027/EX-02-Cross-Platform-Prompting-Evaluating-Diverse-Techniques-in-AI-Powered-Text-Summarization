# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
# Name: Sowmiya R
# Reg No: 212225040420

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy
2.Coherence
3.Simplicity
4.Speed
5.User experience

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
## Result


