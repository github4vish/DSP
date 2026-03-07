# R23 Data Science Using Python Lab

Welcome to the **Data Science Using Python Lab** repository! This is a comprehensive collection of hands-on Jupyter Notebook experiments designed to teach data science fundamentals using Python.

## 📚 Table of Contents

- [About the Lab](#about-the-lab)
- [Experiments & Topics](#experiments--topics)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [How to Use](#how-to-use)
- [Learning Path](#learning-path)
- [Resources & References](#resources--references)
- [Contributing](#contributing)

---

## About the Lab

This repository contains a curated set of **Data Science experiments** aligned with the R23 curriculum. Each experiment is a self-contained Jupyter Notebook that combines theoretical concepts with practical implementation using Python's most popular data science libraries.

**Ideal for:**
- Students learning data science fundamentals
- Practitioners brushing up on Python data science skills
- Anyone interested in hands-on data science projects

---

## Experiments & Topics

### Core Experiments:

| # | Notebook | Topic | Focus Area |
|---|----------|-------|-----------|
| 1 | `NumPy.ipynb` | NumPy Fundamentals | Arrays, mathematical operations, linear algebra |
| 2 | `pandas.ipynb` | Data Manipulation | DataFrames, data cleaning, transformation |
| 3 | `dv.ipynb` | Data Visualization | Plots, charts, exploratory data analysis |
| 4 | `nlp.ipynb` | Natural Language Processing | Text processing, tokenization, analysis |
| 5 | `web.ipynb` | Web Data Collection | Web scraping, data acquisition |

### Supporting Resources:

- **Sample Datasets**: `reviews.csv` - Pre-loaded for quick start
- **Visualization Tools**: `crosssfilter/`, `dc/` - Interactive visualization frameworks
- **Use Cases**: `usecases/` - Real-world application scenarios

---

## Repository Structure

```
DSP/
├── NumPy.ipynb              # NumPy operations and concepts
├── pandas.ipynb             # Data manipulation with Pandas
├── dv.ipynb                 # Data visualization techniques
├── nlp.ipynb                # NLP fundamentals
├── web.ipynb                # Web scraping & data collection
├── reviews.csv              # Sample dataset
├── crosssfilter/            # Crossfilter visualization resources
├── dc/                      # DC.js visualization resources
├── usecases/                # Real-world use cases
└── README.md                # This file
```

---

## Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/github4vish/DSP.git
cd DSP
```

### Step 2: Set Up Your Python Environment

We recommend using **Anaconda** or **conda** for environment management:

```bash
# Create a new environment (optional but recommended)
conda create -n dsp-lab python=3.9
conda activate dsp-lab
```

### Step 3: Install Required Libraries

```bash
pip install -r requirements.txt
```

Or manually install the essentials:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter nltk beautifulsoup4 requests
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Navigate to the notebook of your choice and start learning!

---

## Prerequisites

- **Python**: 3.8 or higher (3.9+ recommended)
- **Jupyter Notebook** or **Jupyter Lab**
- **Core Libraries**:
  - NumPy - Numerical computing
  - Pandas - Data manipulation
  - Matplotlib & Seaborn - Visualization
  - scikit-learn - Machine learning
  - NLTK - Natural language processing
  - BeautifulSoup4 - Web scraping

---

## How to Use

### For Beginners:
1. Start with `NumPy.ipynb` to understand arrays and operations
2. Move to `pandas.ipynb` for data manipulation
3. Explore `dv.ipynb` for visualization techniques
4. Progress to `nlp.ipynb` and `web.ipynb` as you gain confidence

### For Experienced Learners:
- Jump directly to experiments matching your interest
- Use this lab to refresh specific topics
- Experiment with modifying code and exploring variations

### Tips:
- Read all markdown cells and comments carefully
- Run cells sequentially for best results
- Experiment by modifying code and observing outputs
- Use the sample dataset `reviews.csv` to practice

---

## Learning Path

```
Start
  ↓
NumPy Basics (arrays, operations)
  ↓
Pandas (data loading, cleaning, transformation)
  ↓
Data Visualization (understanding data visually)
  ↓
Web Data Collection (getting real-world data)
  ↓
NLP Applications (text analysis)
  ↓
Use Cases & Projects (apply knowledge to real problems)
```

---

## Resources & References

### Official Documentation:
- [Python Docs](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)
- [NLTK Book](https://www.nltk.org/book/)
- [Jupyter Documentation](https://jupyter.org/documentation)

### Recommended Learning Resources:
- [Data Science with Python - DataCamp](https://www.datacamp.com/)
- [Real Python](https://realpython.com/)
- [Kaggle Learn](https://www.kaggle.com/learn)

---

## Contributing

We welcome contributions! If you'd like to:
- Fix bugs or improve existing notebooks
- Add new experiments
- Enhance documentation
- Suggest improvements

Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## Questions & Support

If you have questions or encounter issues:
- 📧 Reach out through GitHub Issues
- 💬 Check existing discussions for similar problems
- 📖 Review notebook comments and markdown explanations

---

**Happy Learning! 🚀 Data Science is a journey—enjoy the process!**

Last Updated: 2026-03-07
