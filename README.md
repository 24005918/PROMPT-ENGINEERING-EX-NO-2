## Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

# 1. Introduction

Text summarization is a process in natural language processing that converts lengthy documents into shorter versions while preserving important information and meaning. AI-powered summarization tools help users quickly understand large volumes of content in areas such as education, healthcare, journalism, and business.

Cross-platform prompting refers to the practice of testing the same prompt across different AI systems to compare their responses and performance. Since each AI platform uses different architectures, training data, and optimization techniques, the generated summaries may vary in quality, structure, and creativity.

The main objective of this experiment is to evaluate how diverse prompting techniques influence summarization results across multiple AI platforms.

# 2. Objectives
To understand the fundamentals of AI-powered text summarization.
To compare summarization outputs from multiple AI platforms.
To evaluate the effectiveness of different prompting techniques.
To analyze summary quality based on coherence, relevance, and readability.
To identify the strengths and limitations of cross-platform prompting.
3. Fundamentals of AI-Powered Text Summarization

AI-powered summarization uses machine learning and deep learning techniques to identify important information within a text and generate a shorter representation of the content.

There are two main types of summarization:

# 3.1 Extractive Summarization

Extractive summarization selects important sentences or phrases directly from the original text without changing the wording. The AI identifies key sentences based on importance scores and combines them into a summary.

Features
Preserves original wording
Easier to implement
Higher factual accuracy
Limited creativity
Applications
News summarization
Legal document summarization
Research paper extraction
# 3.2 Abstractive Summarization

Abstractive summarization generates new sentences that capture the meaning of the original content. It uses advanced language generation models such as transformers and LLMs.

Features
Produces human-like summaries
More flexible and natural
Better readability
Requires advanced AI models
Applications
AI chatbots
Educational content generation
Intelligent assistants
4. Prompt Engineering in Text Summarization

Prompt engineering is the process of designing effective input instructions to guide AI systems toward producing accurate and meaningful outputs.

Different prompt styles can significantly influence summarization quality.

# 4.1 Simple Prompting

A direct instruction asking the AI to summarize the content.

Example

“Summarize the following paragraph in 100 words.”

Advantages
Fast and simple
Suitable for basic tasks
Limitations
Less control over summary quality
May miss important details
# 4.2 Role-Based Prompting

The AI is assigned a specific role before generating the summary.

Example

“Act as a research analyst and summarize the following article.”

Advantages
Improves contextual understanding
Produces domain-specific summaries
# 4.3 Instruction-Based Prompting

Detailed instructions guide the AI regarding style, tone, format, and length.

Example

“Summarize the text in bullet points focusing only on technical details.”

# Advantages
Better customization
More accurate outputs
# 4.4 Chain-of-Thought Prompting

The AI is encouraged to reason step by step before generating the summary.

# Advantages
Improved logical understanding
Better handling of complex documents
Limitations
Increased response time
Longer outputs
## 5. AI Platforms Used for Evaluation
5.1 ChatGPT

ChatGPT is a transformer-based conversational AI model developed by OpenAI. It performs highly effective abstractive summarization with strong contextual understanding and natural language generation.

Strengths
High coherence
Natural language fluency
Good reasoning capability
Limitations
Occasional hallucinations
Context window limitations
# 5.2 Gemini

Google Gemini is a multimodal AI platform capable of processing text, images, and code. It performs well in summarizing technical and factual documents.

Strengths
Strong factual consistency
Multimodal understanding
Efficient response generation
Limitations
Sometimes produces shorter summaries
Less creative abstraction
# 5.3 Claude

Claude, developed by Anthropic, focuses on safe and context-aware responses. It is particularly effective for long document summarization.

Strengths
Strong context retention
Safer outputs
Detailed summaries
Limitations
Conservative response style
Slower for complex prompts
5.4 Copilot

Microsoft Copilot integrates AI assistance into productivity tools and coding environments. It supports summarization tasks within office and development applications.

Strengths
Productivity integration
Technical summarization support
Fast responses
Limitations
Limited creative summarization
Dependency on external applications
## 6. Evaluation Metrics

The generated summaries were evaluated using the following criteria:

# 6.1 Coherence

Measures how logically and smoothly the summary is written.

# 6.2 Relevance

Checks whether important information from the original text is preserved.

# 6.3 Readability

Evaluates how easy the summary is to understand.

# 6.4 Conciseness

Measures how effectively unnecessary details are removed.

# 6.5 Accuracy

Determines whether the generated summary contains factual correctness.

## 7. Experimental Procedure
Step 1: Selection of Source Text

Different types of documents such as news articles, research papers, and technical reports were selected for summarization.

Step 2: Designing Prompts

Multiple prompting strategies including simple, role-based, and instruction-based prompts were created.

Step 3: Cross-Platform Testing

The same prompts were provided to ChatGPT, Gemini, Claude, and Copilot.

Step 4: Output Collection

Summaries generated by each AI platform were collected and documented.

Step 5: Comparative Evaluation

Outputs were compared based on readability, coherence, relevance, and accuracy.

Step 6: Performance Analysis

The strengths and weaknesses of each AI system were analyzed.



## Conclusion

Cross-platform prompting provides valuable insights into how different AI systems perform text summarization tasks. Each platform demonstrates unique strengths depending on the prompting technique and application domain. ChatGPT excels in creative and natural summarization, Gemini performs well in technical accuracy, Claude handles long-context understanding effectively, and Copilot supports productivity-oriented summarization tasks.

The study highlights the importance of prompt engineering in improving summarization quality and demonstrates how AI-powered summarization can enhance productivity, learning, and information management. As AI technologies continue to evolve, cross-platform evaluation will remain essential for identifying the most effective summarization strategies and ensuring responsible AI usage.
