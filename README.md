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

1.  Select the topic **“The Basics of Blockchain Technology.”**
2.  Prepare five different prompts: Basic, Role, Context, Constraint and Output Format.
3.  Enter the prompts into different AI platforms such as ChatGPT, Claude, Google Gemini and Microsoft Copilot.
4.  Collect the generated text summaries from each AI platform.
5.  Evaluate the outputs based on Accuracy, Coherence, Simplicity, Speed and User Experience.
6.  Compare the results using a comparison table and graph.
7.  Identify the most effective prompting technique based on the evaluation.

## ChatGPT – The Technical Analyst

ChatGPT presents Blockchain Technology as a decentralized digital system that allows information and transactions to be stored securely without depending on a single central authority. It explains that blockchain consists of a series of blocks, where each block contains transaction details and a unique cryptographic hash. These blocks are connected together to form a continuous chain. ChatGPT highlights the importance of cryptographic hashing, distributed networks and consensus mechanisms in maintaining data security and transparency. It also explains that once information is recorded on the blockchain, changing it becomes extremely difficult. For example, blockchain can be used in academic certificate verification, where universities can securely store student certificates and allow employers to verify their authenticity. This helps reduce fake certificates and improves trust. Its explanation focuses on technical accuracy, structured information and practical applications, making it useful for computer science students.


<img width="257" height="252" alt="image" src="https://github.com/user-attachments/assets/fe63f297-4f2c-43bb-8d7d-f243c364c536" />

ChatGPT
Zero-Shot Output:
Blockchain is a decentralized digital ledger that securely records transactions across multiple computers. It uses cryptographic hashing and consensus mechanisms to maintain data security, transparency, and reliability.

Few-Shot Output:
Blockchain stores information in connected blocks, where each block contains transaction data and a unique hash. It provides transparency, security, and immutability. Applications include cryptocurrency, banking, healthcare, and supply chain management.

## Chain-of-Thought Output:

Step 1: Blockchain is a decentralized digital ledger.
Step 2: Transactions are stored in blocks.
Step 3: Cryptographic hashing connects the blocks securely.
Step 4: Consensus mechanisms validate transactions.

Role-Based Output:
From an academic perspective, blockchain is a distributed ledger technology that securely records transactions using cryptography and consensus mechanisms. It supports cryptocurrencies, smart contracts, and secure digital transactions.


## Claude – The Conceptual Storyteller

Claude explains Blockchain Technology using simple language and real-world comparisons. It describes blockchain as a digital record book that is shared among multiple computers in a network. Instead of storing information in one central location, copies of the records are maintained by different participants. Whenever a new transaction takes place, the network checks and verifies the transaction before adding it to the blockchain. Claude explains that each block is connected to the previous block, which helps maintain the order and reliability of information. It uses the example of supply chain management, where customers can track a product from its manufacturing stage to its final delivery. This makes it easier to understand where a product comes from and how it reaches the customer. Claude's explanation uses simple analogies and clear examples, making complex technical concepts easier for beginners to understand.


<img width="287" height="155" alt="image" src="https://github.com/user-attachments/assets/8a429f81-a345-4d7a-be3e-cfb9290cd03a" />

claude
Zero-Shot Output:
Blockchain is a decentralized technology that records transactions in a secure and transparent digital ledger. It uses cryptography to protect information and maintain data integrity.

Few-Shot Output:
Blockchain stores transaction details in connected blocks secured by cryptographic hashes. Its decentralized structure improves security and transparency. Common applications include cryptocurrencies, digital identity, and smart contracts.

Chain-of-Thought Output:

Step 1: Define blockchain as a distributed ledger.
Step 2: Explain how transaction data is stored in blocks.
Step 3: Describe the role of cryptographic hashing.
Step 4: Explain consensus mechanisms and applications.

Role-Based Output:
In an academic context, blockchain is a decentralized ledger technology that maintains secure and transparent records through cryptographic techniques and distributed consensus.

## Google Gemini – The Real-World Explorer

Google Gemini explains Blockchain Technology by focusing on its practical uses in modern industries. It describes blockchain as a decentralized digital ledger that records transactions across multiple computers in a secure and transparent manner. It explains important concepts such as blocks, digital signatures, cryptographic hashing and distributed networks. Gemini also highlights how blockchain technology can reduce the need for intermediaries and improve trust between users. It provides real-world examples such as food supply chain management, banking, healthcare and digital identity verification. For instance, in the food industry, blockchain can record information about where food products are grown, processed, transported and delivered. Customers and businesses can use these records to trace the product's journey. This approach helps readers understand how blockchain is used beyond cryptocurrencies. Its practical and application-oriented explanation makes it useful for students who want to connect theoretical knowledge with real-world situations.

<img width="502" height="207" alt="image" src="https://github.com/user-attachments/assets/9cc42cf0-41a7-4e6e-8f74-c3a65728df43" />

Google Gemini
Zero-Shot Output:
Blockchain is a distributed digital database that stores information in connected blocks. It provides security, transparency, and decentralization through cryptographic techniques.

Few-Shot Output:
Blockchain consists of interconnected blocks containing transaction records. Each block is linked using cryptographic hashes. This technology ensures data integrity and supports applications such as digital payments, smart contracts, and supply chain tracking.

Chain-of-Thought Output:

Step 1: Blockchain is a decentralized database.
Step 2: Data is stored in individual blocks.
Step 3: Hashing links the blocks together.
Step 4: Consensus mechanisms verify transactions.

Role-Based Output:
From a technical perspective, blockchain is an innovative distributed ledger system that ensures secure data sharing, transparency, and trust without depending on a central authority.


## Microsoft copilot  – The Structured Innovator

Microsoft Copilot explains Blockchain Technology in a systematic and organized manner by focusing on its major technical components. It introduces blocks, cryptographic hashes, distributed networks and consensus mechanisms, explaining how each component contributes to the functioning of blockchain. It describes how transactions are collected into blocks and verified by network participants before being added to the chain. It also explains that the distributed nature of blockchain improves transparency and reduces dependence on a central authority. Copilot highlights several applications, including digital identity management, financial transactions, healthcare records and supply chain management. For example, blockchain can support digital identity verification by maintaining reliable records that authorized users can verify. Its structured presentation helps readers understand the topic step by step. The explanation is suitable for academic notes, technical learning and project development because it presents important concepts in a clear and organized format.

<img width="397" height="395" alt="image" src="https://github.com/user-attachments/assets/3dbb0f55-bf25-41e5-98a7-183e54a504b4" />

Microsoft Copilot
Zero-Shot Output:
Blockchain is a decentralized digital ledger that records transactions securely across multiple computers. It uses cryptography to protect data and prevent unauthorized changes.

Few-Shot Output:
Blockchain organizes transaction data into connected blocks. Each block contains a unique hash that helps maintain data security. It is widely used in cryptocurrency, banking, and supply chain management.

Chain-of-Thought Output:

Step 1: Blockchain is a distributed digital ledger.
Step 2: Transactions are collected into blocks.
Step 3: Cryptographic hashing connects the blocks.
Step 4: Consensus algorithms verify transactions.

Role-Based Output:
From an instructional perspective, blockchain is a secure digital record-keeping system that uses decentralization, cryptography, and consensus mechanisms to provide transparency and reliability.


## Perplexity AI
Zero-Shot Output:
Blockchain is a decentralized ledger technology that records transactions in connected blocks. It uses cryptographic hashing and consensus mechanisms to ensure security, transparency, and data integrity.

Few-Shot Output:
Blockchain consists of linked blocks containing transaction information. Cryptographic hashes protect the records, while consensus mechanisms validate transactions. Its applications include cryptocurrency, healthcare, finance, and digital identity management.

Chain-of-Thought Output:

Step 1: Blockchain is a distributed ledger system.
Step 2: Each block contains transaction information.
Step 3: Cryptographic hashes connect and secure blocks.
Step 4: Consensus mechanisms validate transactions and maintain network reliability.

Role-Based Output:
From a research perspective, blockchain is a decentralized technology that enables secure and transparent digital transactions through cryptographic verification and distributed consensus.

<img width="432" height="387" alt="image" src="https://github.com/user-attachments/assets/38074763-2c2d-4266-832f-bb8b101b78ac" />


## Comparison Table

| AI Platform | Explanation Style | Strength | Weakness | Best Suited For |
|---|---|---|---|---|
| ChatGPT | Academic & Structured | Clear and detailed explanation | Slightly formal | College Students |
| Claude | Conversational | Easy-to-understand examples | Less technical detail | Beginners |
| Gemini | Practical & Creative | Real-world applications | Less theoretical depth | Practical Learners |
| Copilot | Organized & Technical | Clear technical points | Less conversational | Academic Notes |




## Comparison of Al Platforms for Blockchain Text Summarization

<img width="947" height="542" alt="image" src="https://github.com/user-attachments/assets/80a91caf-dfe2-4560-a313-323fdd4ed696" />





## RESULT

Thus, different prompting techniques such as Basic Prompt, Role Prompt, Context Prompt, Constraint Prompt and Output Format Prompt were successfully designed and evaluated using ChatGPT, Claude, Google Gemini and Microsoft Copilot. The generated summaries were compared based on Accuracy, Coherence, Simplicity, Speed and User Experience. The experiment demonstrated that structured and well-defined prompts produce more relevant, clear and effective text summaries.
