# 🤖 AI Orchestration Pro

From Idea to Production App in 30mins – $0.15 per Project

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Build Status](https://img.shields.io/github/actions/workflow/status/damaso1/AI-orchestration-pro/ci.yml?branch=main)](.github/workflows/ci.yml)

## 🌟 What This Does

This project automates your entire development process using **multiple, specialized AI models** orchestrated via a single **`workflow.json`** configuration. It takes a high-level concept and autonomously generates all the necessary foundational assets, dramatically cutting down project kick-off time.

The workflow delegates tasks to different agents:
1.  **Gemini** - Business analysis & ideation.
2.  **LLM Agent 2 (e.g., GPT-4)** - Technical documentation and structure.
3.  **LLM Agent 3 (e.g., Claude)** - Marketing and public relations copy.

---

## 🚀 Getting Started

Follow these steps to get a copy of the project up and running on your local machine.

### Prerequisites

* **Python 3.10+**
* **Git**
* **API Keys** for the required Large Language Models (LLMs).

### Installation

1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/damaso1/AI-orchestration-pro.git](https://github.com/damaso1/AI-orchestration-pro.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd AI-orchestration-pro
    ```
3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Configuration

1.  Create a file named **`.env`** in the root directory.
2.  Add your API keys to the file. This is crucial for the agents to function.
    ```env
    # Example .env file content
    GEMINI_API_KEY="YOUR_GEMINI_KEY_HERE"
    OPENAI_API_KEY="YOUR_OPENAI_KEY_HERE"
    ```

---

## 🛠️ Usage

To run the full AI orchestration workflow, execute the main script and provide a prompt.

1.  **Execute the Orchestrator:**
    ```bash
    python run.py 
    ```
    *(Note: Replace `run.py` with the actual launch script if it's named differently, e.g., `main.py`)*

2.  **Input your Idea:** The system will prompt you for the initial idea or project concept (e.g., "Build a subscription-based AI fitness coach that uses computer vision.").

### Output Files

After execution, the following structured files will be generated and saved to the `/output` directory:
* `Business.htm`
* `Filename_Documentation.htm`
* `Filename_Marketing.htm`
* ...and a new `workflow.json` reflecting the executed state.

---

## 🗺️ Roadmap

* [ ] Integration with local code generation models (e.g., self-hosted Llama).
* [ ] Add a Quality Control (QC) Agent to review all generated assets.
* [ ] Support for deployment and CI/CD pipeline configuration.

## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## ⚖️ License

Distributed under the **MIT License**. See `LICENSE` for more information.

## 🧑‍💻 Contact

Damaso - **[Your Contact Email Here]**

Project Link: [https://github.com/damaso1/AI-orchestration-pro](https://github.com/damaso1/AI-orchestration-pro)
Im going to use this
