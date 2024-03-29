# Movie recommendation System [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/MarcSkovMadsen/awesome-streamlit)

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

This is a movie recommendation System using Porter Stemmer , TF-IDF Vectorizer, and text processing.

<a name="feat1"/>

## Features

- Movie Recommendation system based on Popularity rating, Director similarity
- Movie Plot Description/Overview based Recommendation.

<a name="examples1"/>

## Examples

|                                        Examples                                        |                                        Examples                                        |
| :------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |
| ![](https://github.com/Sghosh1999/Movie-Recommendation-System/blob/main/demo/img1.JPG) | ![](https://github.com/Sghosh1999/Movie-Recommendation-System/blob/main/demo/img2.JPG) |

---

<a name="demo1"/>

### Application Demo

<p align="center">
  <img src="https://github.com/Sghosh1999/Movie-Recommendation-System/blob/main/demo/recommendation.gif" alt="animated" />
</p>

# Steps :heart_eyes:

- Step 1: Generating a Bag Of Words of teh Search results
- Step 2: Calculating Word frequency ofeach words (TF-IDF) in the Bag Of Words.
- Step 3: Calculating Weighted Movie Score.
- Step 4: Finalizing the results.

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
