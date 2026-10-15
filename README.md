# Python Lab

A practical Python learning and coding-challenge environment designed to help learners move beyond syntax exercises and practise applying Python to realistic problems inside Visual Studio Code.

Python Lab brings coding challenges, test feedback, optional hints, worked solutions, and a learning guide into one workflow.

## Who is Python Lab for?

- **Learners who have completed Python fundamentals** and want to practise applying them.
- **College students** looking for structured, hands-on coding practice.
- **Self-learners** who want feedback while solving problems independently.
- **Career switchers** building confidence with practical programming tasks.
- **Developers** who want to strengthen their Python problem-solving habits.

Python Lab is a learning aid. It does not replace a structured course, code review, or production testing.

## What can you do with it?

- Practise applied scenarios such as log analysis, data validation, event deduplication, API retry planning, configuration merging, data batching, interval conflicts, and performance metrics.
- Write solutions in the normal VS Code editor and use VS Code's available Python editing features.
- Run challenges against test cases and inspect inputs, expected outputs, actual outputs, and errors.
- Reveal hints or worked solutions when you need help.
- Consult the optional Python guide instead of viewing it by default.
- Search and filter the available challenge catalog by topic and difficulty, where supported by the installed build.

## Download

Download the project package and extension from this repository's **Releases** section, if a release is available.

- **VS Code extension:** `Python_Lab.vsix`
- **Complete package:** `Python_Lab_Complete_Package.zip`

If these files are uploaded to the repository root instead of a Release, select the file and use GitHub's download option. Always download from this repository's official files rather than from an unknown mirror.

## Installation on Windows

### Prerequisites

1. Install [Visual Studio Code](https://code.visualstudio.com/).
2. Install Python from [python.org](https://www.python.org/downloads/) if it is not already installed.
3. In VS Code, install Microsoft's **Python** extension.

### Install the VS Code extension

1. Download `Python_Lab.vsix` from the repository or its Releases page.
2. Open VS Code.
3. Open **Extensions** with `Ctrl + Shift + X`.
4. Open the Extensions panel's `...` menu.
5. Select **Install from VSIX...**.
6. Choose the downloaded `.vsix` file.
7. Reload VS Code if prompted.

### Open Python Lab

1. Open a folder in VS Code for your practice work.
2. Press `Ctrl + Shift + P` to open the Command Palette.
3. Search for `Python Hero: Open Challenge Lab`.
4. Select the command to open the challenge interface.

> **Note:** The extension command may still use the earlier internal name `Python Hero: Open Challenge Lab`, even though the project is branded as Python Lab.

## How to use Python Lab

1. Search for a topic or filter the available challenges.
2. Select a challenge and read the scenario and requirements carefully.
3. Write your solution in the Python editor.
4. Run the example or use the all-tests action, depending on the controls available in your installed build.
5. Review each test result. Compare the input, expected output, actual output, and any error.
6. Fix your solution and run the tests again.
7. If you get stuck, reveal a hint first. Use the worked solution or learning guide only when needed.
8. Continue to another challenge and revisit difficult topics.

**Suggested learning approach:** attempt the challenge independently, test edge cases, read the failure feedback, and explain to yourself why your final solution works.

## Challenge bank and coverage

The challenge catalog has been generated from a limited set of scenario templates, with different inputs producing variations. Generated variations are useful for repeated practice, but they are **not the same as individually authored, unique problems**.

Python Lab is an evolving project. Its long-term direction is to expand the number of distinct, carefully tested scenarios and improve coverage across Python, algorithms, data structures, testing, file processing, APIs, databases, and practical software engineering.

Do not interpret a generated challenge count as a guarantee of complete Python coverage or as a count of independently authored questions.

## Troubleshooting

- **The command does not appear:** confirm that the extension is installed and enabled, then run `Developer: Reload Window` from the Command Palette.
- **The challenge panel does not open:** open a workspace folder and try `Python Hero: Open Challenge Lab` again.
- **Python cannot be launched:** install Python and ensure it is available to VS Code; select the correct interpreter using `Python: Select Interpreter`.
- **Test results do not appear:** confirm that the challenge file is open and saved, then retry. If the issue persists, report the error and the steps that caused it.
- **Updating the extension:** uninstall the old extension, reload VS Code, install the new `.vsix`, and reload again. Back up your `.python-hero` workspace data before deleting or replacing any project folders.

## Safety and code execution

Only run code you understand and trust. Treat challenge execution as a learning convenience, not as a security sandbox for untrusted code. Avoid using the lab to execute unknown programs or sensitive scripts.

## Feedback and contributions

Python Lab is an evolving personal project. Feedback is welcome, especially about:

- Missing real-world scenarios
- Incorrect or unclear test cases
- Explanations and hints that could be improved
- Installation and usability issues
- Topics that deserve more challenge coverage

When reporting an issue, include the operating system, VS Code version, steps to reproduce, and the relevant error message. Do not include credentials, private data, or confidential company code.

## Project goal

**Help learners move from understanding Python syntax to confidently applying Python to practical problems.**

If Python Lab helps you practise, learn from a failed test, or build confidence solving a problem independently, consider sharing feedback so the project can improve.

---

Made as an evolving learning project for the Python community.

