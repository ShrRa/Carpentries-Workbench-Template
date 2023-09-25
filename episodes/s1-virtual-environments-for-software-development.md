---
title: "Virtual Environments for Software Development"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- What are virtual environments in software development and why you should use them?
- How can we manage Python virtual environments and external (third-party) libraries?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Set up a Python virtual environment for our software project using `venv` and `pip`.
- Run our software from the command line.
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints

- Virtual environments keep Python versions and dependencies required by different projects separate.
- A virtual environment is itself a directory structure.
- Use `venv` to create and manage Python virtual environments.
- Use `pip` to install and manage Python external (third-party) libraries.
- `pip` allows you to declare all dependencies for a project in a separate file (by convention called `requirements.txt`) which can be shared with - collaborators/users and used to replicate a virtual environment.
- Use `pip3 freeze > requirements.txt` to take snapshot of your project’s dependencies.
- Use `pip3 install -r requirements.txt` to replicate someone else’s virtual environment on your machine from the `requirements.txt` file.
::::::::::::::::::::::::::::::::::::::::::::::::
