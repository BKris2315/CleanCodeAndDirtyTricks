# 🧼 Clean Code & Dirty Tricks  
**Seminar Series @ BME, Spring 2025**  
_Organized by Kristóf Benedek_

---

Welcome to the GitHub repository for the seminar series **Clean Code & Dirty Tricks**, held at BME (Budapest University of Technology and Economics) during the Spring 2025 semester.

This interactive series explores how to write maintainable, efficient, and elegant code, while also diving into the occasional clever "dirty trick" that saves the day. Topics span clean coding practices, Python performance optimization, modern AI-enhanced workflows, and practical GitHub-based project management.

---

## 🗂️ Seminar Topics

1. **🧼 Clean Code Fundamentals**  
   - Function and class design  
   - Naming, comments, structure  
   - Documentation, typing

2. **⚙️ Python Optimization**  
   - Vectorization, parallelization  
   - Multiprocessing, JIT, GPU acceleration  
   - Structuring code for performance

3. **🤖 AI in Development**  
   - ChatGPT, Copilot, and prompting  
   - AI hallucinations and confidentiality concerns  
   - Automating code reviews and docs

4. **🌐 GitHub & Project Workflow**  
   - Project layout, branching, pull requests  
   - Collaborative task tracking  
   - Appealing READMEs and deployment basics

5. **(Optional) 🧠 AI + Symbolic Tools**  
   - SymPy, Transformers, Object Detection  
   - Contrastive learning, Distillation techniques

---

## 🧰 Project Structure

All material — including slides, code snippets, and links — is hosted in this repo. Notebooks and markdown presentations are located in `/presentations`.

---

Run the `notebooks` as a slide show with:

```bash
jupyter nbconvert <notebook.ipynb> --to slides --post serve --no-input --no-prompt
```

**Note:** You might want to `cd` into the directory where the notebook is.

It needs:
- jupyter
- nbconvert 

```bash
pip install jupyter notebook
```

---
## 📚 Reference Materials

### 🧼 Clean Code

- [Clean Code Notes Series – Akiner Alkan (Medium)](https://medium.com/@akineralkan/list/clean-code-notes-bb47e308d51e)
- [Spanish-language Clean Code Repo (ICMC-USP)](https://github.com/ropalma/ICMC-USP)
- [Python Virtual Environments – Real Python](https://realpython.com/python-virtual-environments-a-primer/#why-do-you-need-virtual-environments)
- [Clean Code in Python](https://ep2016.europython.eu/media/conference/slides/clean-code-in-python.pdf) by Mariano Anaya from EuroPython

---

### ⚙️ Python Performance & Optimization

- [Why Python is slower than C](https://medium.com/thedeephub/but-why-python-is-so-slow-da1a4fb9be92)
- [Numba from Scratch](https://pythonspeed.com/articles/numba-faster-python/)
- [PyPy 101 – Real Python](https://realpython.com/pypy-faster-python/)
- [JIT Compilation (Numba Tutorial)](https://medium.com/data-science/make-python-run-as-fast-as-c-9fdccdb501d4)
- [Speed Up with Numba – Kaggle](https://www.kaggle.com/code/rudrasing/speed-up-python-code-up-to-100x-using-numba)
- [Make python fast with numba](https://thedatafrog.com/en/articles/make-python-fast-numba/)
- [PyPy Documentation](https://doc.pypy.org/en/latest/)
- [JAX vs NumPy](https://medium.com/@harshavardhangv/jax-vs-numpy-key-differences-and-benefits-72e442bbf67f)
- [Introduction to Jax](https://www.kaggle.com/code/goktugguvercin/introduction-to-jax)

---

### 🧵 Multiprocessing & Parallelism

- [Intro to Multiprocessing – Analytics Vidhya](https://www.analyticsvidhya.com/blog/2021/04/a-beginners-guide-to-multi-processing-in-python/)
- [Optimal Multiprocessing – Medium](https://medium.com/@sampsa.riikonen/doing-python-multiprocessing-the-right-way-a54c1880e300)
- [Threads vs Processes – DataCamp](https://www.datacamp.com/tutorial/python-multiprocessing-tutorial)
- [Threads vs Processes – Contentsquare](https://engineering.contentsquare.com/2018/multithreading-vs-multiprocessing-in-python/)
- [ProcessPoolExecutor Guide – Medium](https://medium.com/@superfastpython/python-processpoolexecutor-7-day-crash-course-71cf062409d2)
- [SuperfastPython – ProcessPoolExecutor](https://superfastpython.com/processpoolexecutor-in-python/)
- [RealPython on the GIL](https://realpython.com/python-gil/)
- [High-Speed Execution Tips – Analytics Vidhya](https://www.analyticsvidhya.com/blog/2024/01/optimize-python-code-for-high-speed-execution/)
- [PyTorch mastery course](https://github.com/mrdbourke/pytorch-deep-learning?tab=readme-ov-file)

---

### 🤖 AI & Coding Assistants

- (To be expanded during sessions)

---

### 🌐 Git & GitHub

- [Git Basics – Webtuu](https://webtuu.com/blog/04/git-basics-branching-merging-push-to-githubhttps://realpython.com/python-git-github-intro/)
- [GitHub Project Management – Frankfurt Seminar](https://itp.uni-frankfurt.de/~hees/transport-meeting/ss19/talk-Staudenmeier.pdf)

---

## 🧑‍🏫 Instructor

**Kristóf Benedek**  
_Physicist, coder, complexity tamer._

🔗 [Personal Site](https://bkris2315.github.io/)  
🐙 [GitHub](https://github.com/bkris2315)  
📬 kristof.benedek@ek.hun-ren.hu  

---

> _“Write code that doesn’t just work — but works clearly, fast, and beautifully.”_
