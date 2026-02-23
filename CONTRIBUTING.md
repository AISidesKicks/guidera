# 🤝 Contributing to GUIDERA

> **Welcome, fellow developer!** 🎉
>
> You're here to learn, help, and build cool stuff. That's awesome!

---

## 🎮 Ways You Can Help

| Type | What It Means | Good For Beginners? |
|------|---------------|---------------------|
| 💡 **Game Ideas** | Suggest new games or features | ✅ Yes! |
| 🐛 **Bug Reports** | Found something broken? Tell us! | ✅ Yes! |
| 📝 **Documentation** | Fix typos, improve explanations | ✅ Yes! |
| 💻 **Code** | Fix bugs, add features | 🟡 Some experience helpful |
| ✅ **Tests** | Write tests for game features | 🟡 Some experience helpful |

---

## 🚀 Before You Start

### Be Kind & Respectful 💜

We're all here to learn! Remember:
- Be patient with others (everyone was a beginner once)
- Use friendly language
- Help others when you can
- Accept feedback gracefully
- No question is too "dumb" to ask

### Issues & Discussions 💬

**Use [Issues](https://github.com/AISidesKicks/guidera/issues) for:**
- 🐛 Bug reports
- 🎮 Feature requests
- 📝 Documentation problems

**Use [Discussions](https://github.com/AISidesKicks/guidera/discussion) for:**
- ❓ Questions about how things work
- 💡 Ideas and brainstorming
- 🗣️ General chat about the project

### Setup Your Environment

```bash
conda create -n guidera python=3.12
conda activate guidera
pip install -r requirements.txt
```

---

## 📋 Making Changes

### Step 1: Create a Branch

```bash
# Create a new branch with a clear name
git checkout -b fix-typo-in-readme
# or
git checkout -b add-new-monster-type
```

**Branch naming tips:**
- `fix-` for bug fixes
- `add-` for new features
- `update-` for improvements
- `docs-` for documentation changes

### Step 2: Make Your Changes

- Write clean code
- Follow the existing style
- Test your changes!

### Step 3: Test Your Code

```bash
# Run tests (when available)
pytest tests/

# Or test manually by running the game
python main.py
```

### Step 4: Commit Your Changes

```bash
# Add your files
git add .

# Commit with a clear message
git commit -m "Fix: Corrected typo in dungeon description"
```

**Good commit messages:**
- ✅ `Fix: Player can't pick up items twice`
- ✅ `Add: New monster type - Cave Spider`
- ✅ `Docs: Updated installation instructions`
- ❌ `fixed stuff`
- ❌ `updates`

---

## 📤 Sending Your Changes

### Step 1: Push to Your Fork

```bash
git push origin your-branch-name
```

### Step 2: Open a Pull Request (PR)

1. Go to your fork on GitHub
2. Click **"Compare & pull request"**
3. Write a clear title and description
4. Click **"Create pull request"**

### Step 3: Wait for Review

Someone will review your changes. They might:
- ✅ Approve and merge it
- 💬 Ask questions or suggest changes
- ❌ Explain why it can't be merged (don't worry, we'll help!)

---

## 💡 Tips for Beginners

### Start Small 🌱

Your first contribution doesn't have to be huge:
- Fix a typo
- Improve a comment
- Add a docstring
- Report a bug

### Ask Questions ❓

Stuck? That's normal! 
- Open an issue and ask
- Comment on an existing issue
- We're here to help you learn!

### Read the Code 📖

Understanding how things work is the best way to learn:
- Start with `main.py`
- Look at the game logic files
- Check out the tests

### Follow the Style 🎨

- Use clear variable names (`player_health` not `ph`)
- Write functions that do one thing well
- Add comments for tricky parts

---

## 🐛 Reporting Bugs

Found a bug? Help us fix it!

**Include in your report:**
1. What you were doing
2. What you expected to happen
3. What actually happened
4. How to reproduce it (step by step)
5. Your Python version (`python --version`)

**Example:**
> **Bug:** Game crashes when entering the dark room
> 
> **Steps to reproduce:**
> 1. Start a new game
> 2. Go north twice
> 3. Enter the dark room
> 
> **Expected:** Game describes the dark room
> **Actual:** Game crashes with "KeyError: 'dark_room'"
> **Python version:** 3.12.0

---

## 💡 Suggesting Features

Have a cool idea? We want to hear it!

**Include in your suggestion:**
1. What the feature does
2. Why it would be useful/fun
3. How it might work (if you have ideas)

---

## ✅ Code Style Guide

Keep it simple and readable:

```python
# Good ✅
def calculate_damage(attacker_strength, defender_armor):
    """Calculate damage after armor reduction."""
    base_damage = attacker_strength * 2
    actual_damage = max(1, base_damage - defender_armor)
    return actual_damage

# Bad ❌
def cd(a,d):
    return max(1,a*2-d)
```

**Key rules:**
- Use meaningful names
- Keep functions small (10-20 lines)
- Add docstrings to functions
- Follow PEP 8 style (use `ruff` or `black` to format)

---

## ❓ Need Help?

- **Questions?** [Open a discussion](https://github.com/AISidesKicks/guidera/discussion)
- **Found a bug?** [Open an issue](https://github.com/AISidesKicks/guidera/issues)
- **Want to chat?** Check out our community links in README.md

---

## 🙏 Thank You!

Every contribution matters, no matter how small. You're helping make GUIDERA better for everyone learning Python!

**Happy coding!** 🚀