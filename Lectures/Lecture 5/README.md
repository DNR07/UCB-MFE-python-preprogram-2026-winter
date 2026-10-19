# Lecture 5: Python, Memory and Systems

Monday, October 19, 2026 · Advanced Python I · 9 a.m.–noon Pacific.

This lesson connects interview foundations—scope, mutation, functions, objects, and iteration—to memory use, CPU/GPU roles, and independently checked agent tools. Deeper GPU execution and KV-cache material is reserved for Thursday.

## Monday teaching package

- [Google Slides](https://docs.google.com/presentation/d/1xA45CDxuf3ebqsKiuQmzFhNWOriNvuJ-VkAtEJLHEzc/edit): native deck with all 46 slides and speaker notes.
- [Instructor guide](monday-2026-10-19/Monday_Instructor_Guide.html): five-minute preparation, pacing, answers, slide-by-slide teaching notes, and a shortened route.
- [Slides with speaker notes](monday-2026-10-19/UCB_MFE_Lesson_5_Python_Systems.pptx): 43 lesson slides plus 3 appendix/reference slides, exported from Google Slides after class.
- [Prepared notebook](monday-2026-10-19/Monday_Prepared_Notebook.ipynb): the 20 numbered examples plus 5 code cells added during class, with saved outputs and instructor answers.
- [Offline notebook reader](monday-2026-10-19/Monday_Notebook_Reader.html): the original 20 prepared examples and saved outputs. The notebook also includes additions made during class.

Keep these four files together so the guide's links work. Download the HTML files to view them in a browser. The notebook needs Python 3.12+ and NumPy; use the course environment. The numbered prepared examples include their own setup and imports. Classroom additions can depend on preceding cells; run the notebook from top to bottom. No API keys, external data, network calls, or GPU are required. All financial inputs are synthetic classroom examples. No homework deadline changes are introduced.

## January cohort source materials

- **Slides**: `UCB_MFE_2026_Lesson_5_Updated.pptx`
- **Interactive Notebook**: `advanced_python_part1_interactive.ipynb`

### Topics in the January materials

1. **Code as a Tool for AI Agents** - Why Python matters in the age of AI, Agent Skills, MCPs, and how Python enables human-AI collaboration
2. **Python Fundamentals** - LEGB scope, memory model, reference counting, modules
3. **Functional Programming** - Pure functions, lambdas, map/filter/reduce, list comprehensions
4. **Decorators** - Building decorators from scratch, practical examples (timer, retry)
5. **Object-Oriented Programming** - Classes, inheritance, composition, special methods
6. **Iterators and Generators** - Memory-efficient iteration, generator expressions

## Additional Resources

- [Equipping Agents for the Real World with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Blog post on agent skills
- [Anthropic Skills Repository](https://github.com/anthropics/skills) - GitHub repository with example skills
