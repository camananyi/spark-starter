# spark-starter

# Welcome to SPARK Tech Africa 👋

This is your own coding space for the course. Every assignment you write lives here, and every time you submit, your work is checked automatically and sent to your mentors.

---

## Getting started (do this once)

1. **Open your Codespace.** At the top of this page, click the green **Code** button, choose the **Codespaces** tab, then click **Create codespace on main**.
2. **Wait for it to load.** The first time takes a minute or two. You'll see an editor at the top and a **terminal** (where you type commands) at the bottom.
3. **Next time,** click the same **Code → Codespaces** button and pick the Codespace you already have. Don't create a new one each time.

> Always do your work in Codespaces. It works on any computer with a browser, and everything you need is already installed.

---

## Every assignment: run it, check it, submit it

Each assignment tells you the **week folder** and the **exact file name** to use, for example `week1/week1_aboutme.py`.

### 1. Go to the week's folder

```
cd week1
```

### 2. Create your file and write your code

Use the exact file name from the assignment. `week1_aboutme.py` is not the same as `Week1_AboutMe.py` or `week1 aboutme.py`.

### 3. Run it yourself

```
python3 week1_aboutme.py
```

Answer the questions and make sure it does what you expect.

### 4. Check it

```
check50 --local camananyi/spark-checks/main/week1_aboutme
```

- `:)` means that part passed.
- `:(` means something needs fixing. **Read the line underneath it**: it tells you what's wrong and how to fix it.
- `:|` means that check is waiting until you fix an earlier problem.

Fix, run, and check again as many times as you like. Checking does **not** submit your work.

### 5. Submit it

When everything shows `:)`, submit with these three commands:

```
git add .
git commit -m "week1 about me"
git push origin main
```

Your work is checked again automatically and sent to your mentors. You can push again later if you improve it; your latest push is the one that counts.

---

## Each week, only the name changes

| Week | Folder | Check command ends with |
| --- | --- | --- |
| 1 | `week1` | `week1_aboutme` |
| 2 | `week2` | *(given in the assignment)* |

The check command always follows this pattern:

```
check50 --local camananyi/spark-checks/main/<assignment name>
```

---

## Something not working?

| What you see | What to do |
| --- | --- |
| `check50: command not found` | Run `pip install check50`, then try again |
| `Could not find checks for ...` | Check that you typed the command exactly, with the right assignment name |
| `:( week1_aboutme.py exists` | Your file name doesn't match, or you're in the wrong folder. Use `cd week1` and check the spelling |
| `your program crashed before it finished` | Run `python3 week1_aboutme.py` yourself and read the last line of the red error message |
| A `:(` you can't fix | Submit the **help request form** and paste the check50 message into it. A mentor will help you |

---

## Good habits

- **Close your Codespace tab when you're done.** You get about 60 free hours a month, and a closed Codespace doesn't use them.
- **Write comments** that explain what your code does, like `# this asks the user for their name`.
- **Check before you submit.** It's the fastest way to learn what to fix.

Happy coding! 🚀
