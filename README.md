# PromptWriter 🚀  
**A Modern CLI Tool for Crafting AI Prompts**

```
   P R O M P T W R I T E R
   ------------------------
   > Crafting AI Prompts <
   ------------------------
   [===>    ] Loading...
   [======> ] Refining...
   [========] Done!
```

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)]()
[![Build Status](https://img.shields.io/github/actions/workflow/status/username/promptwriter/ci.yml?branch=main)](https://github.com/username/promptwriter/actions)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## Overview 🌟

PromptWriter is a streamlined command-line interface (CLI) tool designed to simplify the art of prompt engineering. Whether you're a developer, writer, or AI enthusiast, PromptWriter helps you craft high-quality, optimized prompts for AI models with ease. By automating the refinement and generation process, it transforms raw ideas into polished, AI-ready prompts—saving time and ensuring consistency. Say goodbye to tedious manual editing and hello to efficient, effective AI interactions!

---

## Features

- 🔌 **Two-Step Smart Processing**:  
  - Refines your input for grammar, clarity, and intent.  
  - Generates structured, best-practice prompts for AI systems.  
- 🛠️ **User-Friendly CLI**: Simple commands with optional verbose mode for transparency.  
- 📊 **Real-Time Progress Tracking**: Animated spinners and updates during processing.  
- ⚡ **AI-Powered Backend**: Leverages advanced models like Mistral 24B and Qwen-QwQ-32B via the Groq API.

---

## Installation 🛠️

Follow these steps to get PromptWriter up and running on your system.

### Prerequisites
- **OS**: Windows, macOS, or Linux  
- **Python**: Version 3.8 or higher  
- **Pip**: Python package manager  
- **Groq API Key**: Sign up at [Groq](https://groq.com) to obtain your API key.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/promptwriter.git
   cd promptwriter
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your Groq API key:
   ```bash
   export GROQ_API_KEY="your-api-key-here"
   ```
4. Verify installation:
   ```bash
   promptwriter --version
   ```

**Edge Case**: Ensure your internet connection is active, as PromptWriter relies on the Groq API for processing.

---

## Usage 📖

PromptWriter is designed to be intuitive. Here’s how to start crafting prompts:

### Basic Command
```bash
promptwriter craft --idea "Write a poem about summer"
```

### Verbose Mode (Optional)
See the step-by-step process:
```bash
promptwriter craft --idea "Write a poem about summer" --verbose
```
Output example:
```
Original: "Write a poem about summer"  
Refined: "Compose a poem describing the essence of summer."  
Final Prompt: "Generate a well-structured poem capturing the warmth, vibrancy, and spirit of summer, with clear imagery and a consistent tone."
```

For more details, check the [documentation](docs/README.md).

---

## Examples 🌟

### Use Case 1: Creative Writing
**Input**:  
```bash
promptwriter craft --idea "Tell a story about a lost astronaut"
```
**Output**:  
"Create a narrative about an astronaut stranded in space, exploring themes of isolation and resilience, with vivid descriptions and a compelling conclusion."

### Use Case 2: Data Analysis
**Input**:  
```bash
promptwriter craft --idea "Analyze sales data"
```
**Output**:  
"Perform a detailed analysis of sales data, identifying trends, key insights, and actionable recommendations, presented in a clear and concise format."

---

## Contributing 🤝

We welcome contributions from the community! To get involved:

1. **Fork the Repository**: Click "Fork" on GitHub.  
2. **Create a Branch**: `git checkout -b feature/your-feature-name`  
3. **Submit a Pull Request**: Follow our [PR template](CONTRIBUTING.md#pull-requests).  
4. **Report Issues**: Use the [Issues tab](https://github.com/username/promptwriter/issues).

Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

---

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

---

## Contact ✉️

Have questions or feedback? Reach out to us:  
- **Email**: promptwriter-support@example.com  
- **Twitter**: [@PromptWriterHQ](https://twitter.com/PromptWriterHQ)  
- **GitHub Issues**: [Report a bug](https://github.com/username/promptwriter/issues)

---

## Acknowledgments 🙌

- **Groq API**: For powering our AI backend.  
- **Mistral 24B & Qwen-QwQ-32B**: State-of-the-art models for refinement and generation.  
- **Open-Source Community**: For inspiration and support.

---
