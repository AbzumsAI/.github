# Missing Materials To Collect

I use this list to keep the public repos honest about what is present and what still needs an original source file.

## Current State

All 9 AbzumsAI repositories are cloned locally and synced with `origin/main`.

Recovered and pushed:

- 59 slide and workshop files with labels and PDF previews.
- Editable Numpy and Pandas assignment folders with solutions, checks, and notebooks.
- Assignment 14 and Assignment 15 solution folders with checks and notebooks.
- Final machine learning homework handout, dataset, data dictionary, editable problem text, and starter analysis.
- Notebook solutions for assignments 1 to 7.
- Cleaned session, project, NumPy, and Pandas notebooks from the chat export.
- Cleaned clinic and openFDA code examples from the chat export.
- Public site cards and counts for the current repos and materials.

## Still Needed

Please provide these if you have them:

- The two article PDFs mentioned by `Assignments/MachineLearningHomework/Homework.pdf`.
- Official grading rubrics for Assignment 14, Assignment 15, and the machine learning homework, if they exist.
- Official rubrics or expected outputs for notebook assignments 1 to 7, if they exist.
- Editable slide sources, such as `.pptx`, `.key`, `.tex`, or `.md`, if the PDFs are not enough.
- Source logo file, such as `.svg` or `.ai`, if the site and template should use a vector logo.
- Final public homepage text in Persian and English, if it should replace the current site copy.
- Production deployment values for QA-Bot, only through private environment settings.

## Kept Out Of Git

These were found but not pushed:

- Raw chat export HTML, CSS, JavaScript, photos, screenshots, and thumbnails.
- Full textbook PDFs.
- `casteller_check_bot.py`, because it contains a Telegram token and an AvalAI key.
- `Numpy_Masterclass.html`, because the cleaned notebook copy is already in the Notebooks repo.
- The Persian summit planning PDF, because it is not course assignment or slide material.
- Duplicate assignment PDFs already present in the Assignments repo.

## Security Rule

Never put live tokens, API keys, bot tokens, private emails, phone numbers, or production paths in git. Use environment variables and private deployment settings instead.
