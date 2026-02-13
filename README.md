# Gmail Autosorter - Agentic AI Hackathon Project

> An intelligent email management system built for the Agentic AI App Hackathon

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

## 🎯 Project Overview

Gmail Autosorter is an AI-powered email organization tool that intelligently categorizes, prioritizes, and manages your inbox using agentic AI principles. Built as part of the Agentic AI App Hackathon, this project demonstrates how autonomous agents can streamline email workflow management.

**Note:** The complete implementation is in a private repository for security reasons. This repository serves as the public-facing submission for the hackathon.

## ✨ Key Features

- **Intelligent Email Categorization**: Automatically sorts emails into relevant folders based on content analysis
- **Priority Detection**: Identifies urgent and important emails requiring immediate attention
- **Autonomous Actions**: Performs actions like archiving, labeling, and responding based on learned patterns
- **Contextual Understanding**: Uses natural language processing to understand email intent and context
- **Memory System**: Learns from user preferences and adapts sorting behavior over time

## 🏗️ Architecture

The system follows an agentic AI architecture with the following components:

- **Planning Module**: Analyzes incoming emails and determines appropriate actions
- **Tool Integration**: Connects with Gmail API and other productivity tools
- **Memory Layer**: Maintains context and user preferences across sessions
- **Action Executor**: Performs email management tasks autonomously

For detailed architecture information, see [ARCHITECTURE.md](ARCHITECTURE.md).

## 📦 Installation

### Using Conda

```bash
# Clone the repository
git clone https://github.com/Lakshya751/Google-Hackathon-.git
cd Google-Hackathon-

# Create and activate conda environment
conda env create -f environment.yml
conda activate agentic-hackathon
```

### Using Docker

```bash
# Build the Docker image
docker build -t gmail-autosorter .

# Run the container
docker run --rm -it gmail-autosorter bash
```

## 🚀 Getting Started

1. **Configure Gmail API credentials** (see setup guide in docs)
2. **Run the agent**:
   ```bash
   python src/main.py
   ```
3. **Customize sorting rules** through the configuration file

## 📖 Documentation

- **[ARCHITECTURE.md](ARCHITECTURE.md)** - System design and component diagrams
- **[EXPLANATION.md](EXPLANATION.md)** - Planning strategy, tool usage, and limitations
- **[DEMO.md](DEMO.md)** - Video demonstration with timestamped highlights

## 🎥 Demo

Watch our 3-5 minute demo video showcasing the Gmail Autosorter in action. See [DEMO.md](DEMO.md) for the full video and timestamped highlights of key features.

## 🔧 Technical Stack

- **AI Framework**: LangChain / Custom Agent Framework
- **NLP**: OpenAI GPT / Anthropic Claude
- **Email Integration**: Gmail API
- **Backend**: Python 3.10+
- **Memory**: Vector Database for contextual storage

## 🤝 Hackathon Submission

This project was created for the **Agentic AI App Hackathon**. Our submission includes:

- ✅ Functional code in `src/` directory
- ✅ Detailed architecture documentation
- ✅ Comprehensive explanation of agent design
- ✅ Video demonstration of capabilities

## 👥 Team

Team Name: **[Your Team Name]**

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to the hackathon organizers for this opportunity
- Built using the [agentic-hackathon-template](https://github.com/odsc2015/agentic-hackathon-template)

---

**Note:** The full source code and implementation details are maintained in a private repository for security and privacy reasons (collaborated). This public repository contains the documentation and submission materials for the hackathon.
