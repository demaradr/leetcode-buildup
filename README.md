# leetcode-buildup

Skills-first LeetCode practice in Jupyter notebooks — micro-exercises before the full solve.

## Run without installing Jupyter

### Google Colab (fastest)

Open a notebook in your browser — no local install. Sign in with a Google account.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/demaradr/leetcode-buildup/blob/main/problems/strings/14-longest-common-prefix.ipynb)

**From a fork:** replace `demaradr` with your GitHub username in the URL, or in Colab use **File → Open notebook → GitHub** and paste your repo URL.

**From a zip download:** upload the `.ipynb` file in Colab (**File → Upload notebook**).

### Binder (full repo in the browser)

Launches JupyterLab for this repo. First start can take a minute or two.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/demaradr/leetcode-buildup/HEAD?labpath=problems%2Fstrings%2F14-longest-common-prefix.ipynb)

**From a fork:** use `https://mybinder.org/v2/gh/YOUR_USER/leetcode-buildup/HEAD` (add `?labpath=...` to open a specific notebook).

Sessions stop after idle time; your work is not saved unless you download the notebook.

## Run locally (optional)

```bash
git clone https://github.com/demaradr/leetcode-buildup.git
cd leetcode-buildup
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Then open `problems/strings/14-longest-common-prefix.ipynb`.

## Notebooks

| Problem | Notebook |
|---------|----------|
| [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) | [problems/strings/14-longest-common-prefix.ipynb](problems/strings/14-longest-common-prefix.ipynb) |

## How to use

1. Read the LeetCode problem and write your approach in plain English first.
2. Complete the skill exercises in the notebook.
3. Implement the solution yourself — then run the tests in the notebook.

This repo is for learning, not answer keys. Solve it, then re-solve from scratch after a break.
