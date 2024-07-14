# Movie Recommender System with Python

## Introduction

This repository contains a project focused on building a Movie Recommender System using collaborative filtering techniques in Python.

## Table of Contents

1. [Introduction](#introduction)
2. [Libraries Used](#libraries-used)
3. [Installation](#installation)
4. [Usage](#usage)
   - 4.1 [Data Preparation](#data-preparation)
   - 4.2 [Building the Recommender System](#building-the-recommender-system)
   - 4.3 [Interactive Interface](#interactive-interface)
5. [Contributing](#contributing)
6. [License](#license)

---

## Introduction

This project implements a Movie Recommender System that suggests movies to users based on their historical ratings and preferences. The system employs collaborative filtering methods to generate personalized recommendations.

---

## Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.metrics.pairwise import cosine_similarity
import matplotlib.pyplot as plt
import seaborn as sns
import streamlit as st

![Capture](https://github.com/user-attachments/assets/cb18643d-531e-4ae9-b7aa-d0ccbb2ef7b9)
