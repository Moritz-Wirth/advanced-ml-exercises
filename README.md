# Advanced Methods to Machine Learning: Exercises

Exercise notebooks for the lecture **Advanced Methods to Machine Learning** (Universität Kassel / Fraunhofer IEE,
winter term 2026/27).

Each lecture block comes with one notebook. We work through it together in the exercise sessions (Thursdays, 10–12,
room 0303c); a notebook can span more than one session. The exercises are not graded, but the oral examination
assumes you have done them.

## Exercises

| # | Topic | Session | Notebook | Solution |
|---|---|---|---|---|
| 02 | Transformers from scratch, part 1 (sections 1–3) | Thu 29.10.2026 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Moritz-Wirth/advanced-ml-exercises/blob/main/exercises/02_transformer/transformer_exercise.ipynb) | [sections 1–3](https://colab.research.google.com/github/Moritz-Wirth/advanced-ml-exercises/blob/main/exercises/02_transformer/transformer_solution_partial.ipynb) |
| 03 | Transformers from scratch, part 2 (sections 4–7) | Thu 05.11.2026 | same notebook as 02 | after the session |

Solutions are added here after each session. Exercises 02 and 03 share one notebook: the solution for sections 1–3
is available now, the full solution follows after 05.11.

**Already started exercise 02 in Colab?** Keep working in your saved copy. The gaps did not change; the update only
removed the "ahead of the lecture" notes, since the lecture has now covered sections 4–6.

## Getting started

### Option A: Google Colab (recommended)

1. Click the **Open in Colab** badge above.
2. **First, use *File → Save a copy in Drive*.** Otherwise your changes are lost when you close the tab.
3. Run the setup cell at the top, then work through the notebook from top to bottom.

You do not need a GPU or any installs. Everything runs on Colab's free CPU runtime.

### Option B: Locally

You need Python 3.10 or newer.

```bash
git clone https://github.com/Moritz-Wirth/advanced-ml-exercises.git
cd advanced-ml-exercises
python -m venv .venv
```

Activate the environment:

- Windows: `.venv\Scripts\activate`
- macOS / Linux: `source .venv/bin/activate`

Then install the requirements and start Jupyter:

```bash
pip install -r requirements.txt
jupyter notebook
```

`transformers` is only needed for one optional stretch task. If the install causes trouble, skip it.

## How the notebooks work

- `raise NotImplementedError  # TODO` marks your code: replace that line with your implementation.
- After each gap, a **check cell** tells you whether your code is correct (✅). If it isn't (❌), it says what is wrong and which slide to revisit.
- 🧠 **Predict first**: write down your guess before you run the cell.
- ✍️ **Questions**: answer in a few sentences. They are good preparation for the oral exam.
- ⭐ **Stretch tasks** at the end are optional, for home.
- Slide numbers refer to the lecture slides in Moodle.

## Questions and problems

Ask in the exercise session or in the Moodle forum. If you think you found a bug in a notebook, please post it in
the forum or open an issue in this repository.

**Tutor:** Moritz Wirth · **Lecturer:** Dr. Christoph Scholz
