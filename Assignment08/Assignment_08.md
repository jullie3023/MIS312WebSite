# MIS312 Assignment 8 — Debugging and Better Understanding Your Code

**Book Alignment:** Chapter 8  
**Primary Goal:** Build a repeatable debugging process  
**Environment:** JupyterLab + VS Code (`.ipynb`)  
**Submission:** OneNote Artifact (PDF)

---

## Learning Objectives
- Identify common error types
- Fix code methodically
- Explain the cause and fix

---

## Student Tasks
For each bug: run → screenshot error → fix → screenshot success.

### Bug A
```python
total = 10
totl = total + 5
print(totl2)
```

### Bug B
```python
age = input("Enter your age: ")
print(age + 1)
```

### Bug C
```python
def is_discount_big(discount_percent):
    return discount_percent > 100
print(is_discount_big(20))
```

### AI explanation (required)
Pick one bug and ask AI to explain the error and suggest a fix.

---

## VS Code Exercise — Debugging a `.py` Script with the VS Code Debugger

### Task 5 — Put Bug B into a script file
1. Create folder: `C:\Users\<StarID>\MIS312\assignment08\`
2. Create file: `bug_b.py`
3. Paste Bug B into the file:
```python
age = input("Enter your age: ")
print(age + 1)
```

### Task 6 — Run and capture the error
Run in VS Code terminal:
```powershell
python bug_b.py
```
Take a screenshot of the error.

### Task 7 — Fix it (required)
Fix the script so it works correctly (hint: convert input to an integer).
Re-run. Screenshot the successful output.

### Task 8 — Debugger (required)
Use the VS Code debugger at least once:
- Set a breakpoint on the line that prints the result
- Start debugging (Run → Start Debugging)
- In the Variables panel, confirm the type of `age` before and after your fix

### Add to OneNote Artifact
- Error screenshot + fix screenshot
- Screenshot of breakpoint/debugger view (Variables panel visible)
- Short reflection: what the debugger showed you


## OneNote Artifact Requirements
- Before/after screenshots
- Fix snippets
- AI prompt + summary
- Reflection: Your debugging checklist (3 bullets)
