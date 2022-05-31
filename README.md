# Fuzzy String Search [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/MarcSkovMadsen/awesome-streamlit)

[<img src="https://static.vecteezy.com/system/resources/thumbnails/000/623/500/small/5-29.jpg" align="right" height="75" width="100">](https://streamlit.io)

> An advanced Movie Recommendation System.!

## Live Demo :

### Table of Contents

- [Description](#description)
- [Features](#feat1)
- [Examples](#examples1)
- [Application Demo](#demo1)
- [Prerequisites](#preq)
- [Installation Guide](#guide1)

---

<a name="description"/>

## Description

This is a movie recommendation System .

<a name="feat1"/>

## Features

- Automatic Search Phrase Matcher.
- Can Handle wrong Spellings.

<a name="examples1"/>

## Examples

- The search results are fetching from **Google Search API ( rapid API)** . So **search resposnses may differ** in each API call.
- **Refresh the App to get your desired results**, if first time you didn't get the accurate results.

|                                                   Examples                                                   |                                                   Examples                                                   |
| :----------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: |
| ![](https://github.com/Sghosh1999/fuzzy_search/blob/1aa1e4c0bfc233828c1f69b69366713d542f1ea4/images/ex1.jpg) | ![](https://github.com/Sghosh1999/fuzzy_search/blob/1aa1e4c0bfc233828c1f69b69366713d542f1ea4/images/ex2.jpg) |

---

<a name="demo1"/>

### Application Demo

<p align="center">
  <img src="https://github.com/Sghosh1999/fuzzy_search/blob/499749530b2f3c0d13e37c0c8587011ebe0a67db/images/fuzzy_demo.gif" alt="animated" />
</p>

# Steps :heart_eyes:

- Step 1: Generating a Bag Of Words of teh Search results
- Step 2: Calculating Word frequency ofeach words in the Bag Of Words.
- Step 3: Calculating the Stop Index.
- Step 4: Finalizing the results.

<a name="form1"/>

<p align="center">
  <img src="https://github.com/Sghosh1999/fuzzy_search/blob/7ab472ecfd877f8a3fb11ebeadd7fa68809bf7e9/images/screen3.PNG" alt="formula" />
</p>

---

## Built With

This section should list any major frameworks that we have used to build the application.

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)

---

<!-- GETTING STARTED -->

## Getting Started :robot:

In this section, A whole installation guide is mentioned. also trouble shooting guide is also given.

<a name="preq"/>

## Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- Python ( Version 3.8.5)
- Git

<a name="guide1"/>

## Installation

1. Clone the repo

   ```sh
   git clone https://github.com/Sghosh1999/fuzzy_search.git
   ```

   Open Command prompt and navigate to the folder ( fuzzy_search)

   ```
   cd fuzzy_search
   ```

2. Install & Create a Virtual Python environment
   ```python
   python -m pip install virtualenv
   python -m virtualenv myenv
   ```
3. Activate the Virtual environment
   ```python
   myenv\scripts\activate
   ```
4. Install necessary packages
   ```sh
   python -m pip install -r requirements.txt
   ```
5. Check if these two packages are installed or not: (Optional)
   ```sh
   python -m streamlit --version
   ```
   If streamlit is not recognized, then run the command (Optional if error)

```sh
  python -m pip install streamlit
```

## Running the Application

```python
python -m streamlit run app.py
```

- For the first time it will ask you for the email. Please provide the email and the application will be open in your browser.

### Built with :heart: by Team 8 ( Droid )
