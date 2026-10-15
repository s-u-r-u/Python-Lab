# Python Lab 🐍

**Learn by solving. Improve by testing. Get help when you need it.**

Python Lab is a learning and coding-challenge environment for Visual Studio Code. It is intended to help learners move beyond watching tutorials and practise applying Python to practical scenarios.

> **A note from the creator:** Python Lab is an evolving personal project built with help from AI. I am still learning Python myself. The goal is not to claim that the tool teaches everything, but to make independent practice, debugging, and learning from mistakes a little easier.

---

## 👋 Who is Python Lab for?

Python Lab may be useful if you are:

- A learner who has completed Python fundamentals and wants more practical exercises.
- A student looking for structured coding practice.
- A self-learner who wants feedback while solving problems independently.
- A career switcher building confidence with programming.
- A developer who wants to practise applied Python problem-solving.

If you are completely new to Python, start with a beginner course first. Python Lab is most useful when you already understand basic functions, variables, conditions, loops, and common data structures.

## ✨ What can you do?

- Practise applied scenarios such as log analysis, data validation, event deduplication, API retry planning, configuration merging, data batching, interval conflicts, and performance metrics.
- Write your solution in the normal VS Code editor.
- Run a challenge and check your answer against test cases.
- Review test inputs, expected outputs, actual outputs, and errors when the checker provides them.
- Reveal a hint before looking at a complete worked solution.
- Open the optional guide when you need help understanding a concept.
- Navigate between challenges and keep track of learning progress, where supported by the installed build.

Python Lab is a learning aid. It does not replace a course, code review, or production testing.

---

## 🧰 Before you begin

You will need:

1. **A Windows, macOS, or Linux computer** that can run VS Code and Python.
2. [**Visual Studio Code**](https://code.visualstudio.com/) installed.
3. [**Python 3**](https://www.python.org/downloads/) installed.
4. Microsoft's **Python** extension installed in VS Code.

After installing Python, open the VS Code terminal (**Terminal → New Terminal**) and try:

```bash
python --version
```

On some Windows installations, use:

```powershell
py --version
```

If neither command works, finish the Python installation and make sure Python is available on your system PATH. In VS Code, use `Ctrl+Shift+P`, search for **Python: Select Interpreter**, and select your installed Python interpreter.

## 📥 Install Python Lab

Download the `.vsix` extension file from this repository's **Releases** section, if one is available. If the repository provides the file directly, click the file and use GitHub's download option.

1. Open VS Code.
2. Press **`Ctrl + Shift + X`** to open the Extensions panel.
3. Click the **three-dot (`...`) menu** near the top of the Extensions panel.
4. Select **Install from VSIX...**.
5. Choose the downloaded `Python_Lab.vsix` file.
6. If VS Code asks you to reload, reload the window.

If you are updating an older installation, uninstall the previous Python Lab extension first, reload VS Code, install the new `.vsix`, and reload again. **Back up your practice folder before deleting or replacing any files.** Do not delete your `.python-hero` folder if it contains challenges or progress you want to keep.

## 🚀 Open the learning panel

1. Open a folder in VS Code for your Python practice.
2. Press **`Ctrl + Shift + P`** to open the Command Palette.
3. Type `Python Lab`.
4. Choose **`Python Lab: Open Challenge Lab`**.

The command may still display the internal name **Python Hero: Open Challenge Lab** in some builds. If so, choose that command; it opens the same lab.

### What you should see

The learning panel should show the current challenge, its concept and instructions, and the available actions. A Python challenge file should open in the editor, often under the `.python-hero/challenges` folder.

**Important:** edit the challenge's `.py` file in the main editor. Do not edit `engine/challenge_engine.py` or `extension.js` when you are simply solving a challenge; those files belong to the tool itself.

---

## 🧭 Step-by-step: solve your first challenge

### Step 1 — Read before coding

Read the challenge title, scenario, requirements, and any rules. Identify what the function must return. Pay attention to edge cases such as empty input, repeated values, invalid data, or unusually large values when the challenge mentions them.

### Step 2 — Write your solution

In the main editor, find the provided function. It may look similar to:

```python
def solve(data):
    pass
```

Replace `pass` with your implementation. Keep the required function name and parameters exactly as provided, and **return** the requested result unless the challenge explicitly asks you to print it.

Save using **`Ctrl + S`**. Some actions may save the file for you, but saving manually is a good habit.

### Step 3 — Run your code

Press **`Ctrl + Shift + P`**, type `Python Lab`, and select:

- **Python Lab: Run Current Challenge** — runs the current challenge's example or normal execution path.
- **Python Lab: Check Answer (6 Tests)** — runs the available six-test checker and displays the result for each case.

For checking your solution, start with **Check Answer (6 Tests)**. The exact output layout depends on the installed build.

### Step 4 — Read the test results

For each test, look for:

- **PASS or FAIL:** whether your answer matched the expected result.
- **Input:** the data used for the test.
- **Expected output:** the result the checker expected.
- **Actual output:** what your code returned or produced.
- **Error details:** any exception or diagnostic provided.

If a test fails, do not immediately open the worked solution. Compare the expected and actual results, identify the difference, and try to fix your code.

### Step 5 — Ask for a hint if you are stuck

Use **Python Lab: Show Hint** from the Command Palette. Read the hint and try again before looking at the full solution.

### Step 6 — Open the worked solution only when needed

Use **Python Lab: Show Worked Solution** to review the suggested approach. Compare it with your own code and ask yourself:

- What was the key idea?
- Which edge case did I miss?
- Could I explain this solution to someone else?
- Is there a clearer or more maintainable approach?

### Step 7 — Track progress and continue

Available commands may include:

- **Python Lab: Mark Challenge Learned**
- **Python Lab: Next Challenge**
- **Python Lab: Previous Challenge**
- **Python Lab: Random Challenge**

Use **Mark Challenge Learned** only when you understand the approach—not merely because the tests passed.

---

## 🔎 Finding a particular concept

To open the lab, use **`Ctrl + Shift + P` → `Python Lab: Open Challenge Lab`**.

If your installed build includes a search field in the learning panel, use it to search for a topic such as `strings`, `lists`, `dictionaries`, `file processing`, or `API retries`. Use the panel's topic or difficulty filters if they are available.

The Command Palette search is different: typing `Python Lab` there finds **commands**, such as Check Answer or Show Hint. It does **not** search all challenge titles or filter the challenge catalog.

If you cannot find a concept-search field in your installed build, that feature may not be available in that build yet. You can still use the available Next, Previous, and Random Challenge commands.

## 🧠 A learning routine that works

1. Read the task and write down the expected behaviour.
2. Try a solution without opening the hint.
3. Run all available tests.
4. Inspect every failure and try to explain it.
5. Use a hint if you need a nudge.
6. Read the worked solution only after making a genuine attempt.
7. Re-implement the solution yourself without copying.
8. Revisit the problem later to check whether you still understand it.

The aim is not just to pass a test. It is to understand the reasoning behind your solution.

## 📚 Challenge coverage and limitations

The current catalog contains generated variations based on a limited number of scenario templates. Different inputs can create useful variations for repeated practice, but they are **not the same as individually authored, unique problems** and do not guarantee complete coverage of Python.

Python Lab is an evolving project. Future improvements can expand the number of distinct, carefully tested scenarios and broaden coverage across algorithms, data structures, object-oriented programming, testing, file processing, APIs, databases, and practical software engineering.

## 🛠️ Troubleshooting

### “Python Lab: Open Challenge Lab” does not appear

1. Open Extensions with `Ctrl + Shift + X`.
2. Search for Python Lab and confirm it is installed and enabled.
3. Press `Ctrl + Shift + P`, run **Developer: Reload Window**, and search for the command again.
4. If the command still does not appear, reinstall the `.vsix` file.

### The lab opens, but I do not know which file to edit

Edit the current challenge `.py` file shown in the editor—typically a file under `.python-hero/challenges`. Do not edit `challenge_engine.py` or `extension.js` for an ordinary challenge.

### “Open the challenge .py file in the editor first”

Click the current challenge `.py` tab in the main editor and try again. If the message persists, run **Python Lab: Open Challenge Lab** again and select the challenge from the lab so it opens its associated file. Save the file and retry **Python Lab: Check Answer (6 Tests)**.

### Python cannot be launched

- Confirm Python is installed.
- Run `python --version` or, on Windows, `py --version` in a terminal.
- Use **Python: Select Interpreter** from the Command Palette.
- If needed, install or repair Python and restart VS Code.

### Tests fail

A failed test does not necessarily mean the tool is broken. Read the input, expected output, actual output, and error details. Check return values, data types, empty inputs, boundary cases, and the exact required function signature.

If the checker itself appears broken, record the command you ran and the full error message. A screenshot is helpful.

### My progress disappeared

Do not delete or replace your `.python-hero` folder without a backup. Back up the folder before reinstalling or changing workspaces. Progress may be stored in the workspace, depending on the build.

## 🔐 Safe use

Only run code you understand and trust. Challenge execution is a learning convenience, not a security sandbox for untrusted programs. Do not use the lab to run unknown scripts or sensitive company code.

## 💬 Feedback and contributions

Python Lab is a personal learning project built with AI assistance and is still evolving. Suggestions and constructive feedback are welcome, especially about:

- Real-world scenarios worth practising
- Unclear explanations or hints
- Incorrect test cases or confusing feedback
- Installation and usability problems
- Topics that deserve more coverage

When reporting an issue, include your operating system, VS Code version, steps to reproduce, and the error message. Never share passwords, credentials, private data, or confidential company code.

## 🎯 Project goal

**Help learners move from understanding Python syntax to confidently applying Python to practical problems.**

If Python Lab helps you learn from a failed test, understand a difficult concept, or solve a problem more independently, feedback from your experience can help make the project better.

---

Built as an evolving learning project with AI assistance.
