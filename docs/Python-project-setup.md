# Python Porject setup

As you start working on your python project, you’ll likely need to set it up in a consistent and collaboration-friendly way. In this article, I’ll describe a setup that works great for our projects at Turo, and also my personal ones. It includes many industry best practices (semantic versioning, pre-commit, linting, or how to release code to mention but a few).

In short, we’ll cover how to properly install python, structure your code, run automated checks both on local with pre-commit and the server side with GitHub Actions (aka GHA).

This article covers quite a few topics. To ease the reading, each section will usually be split in two parts:

📚 for the theory part
🛠️ for the practical part (i.e. the commands you need to run to reproduce).
Sometimes a 💡 section will also indicate a coding tip or trick.

# Table of Contents

- Install a Python version manage (pyenv)
- Choose an environment manager (poetry)
- Otherwise, use Docker to isolate dependencies
- Add Some Code
- Write Some Tests
- Linting our code
- Automate checks on local with pre-commit
- Automate checks on remote with GitHub Actions
- Automate our release with GitHub Actions
- Enjoy the benefits of your new code practices

# How to properly setup your Python project

[How to properly setup your Python project](https://dev.to/armandsauzay/how-to-properly-setup-your-python-project-3fng)
[](https://github.com/pyenv/pyenv)
