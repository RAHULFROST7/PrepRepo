## **Week 1 Python Refresher Guide**

### **Day 1: Advanced Python Core ✅**

**Topics:**

* OOP Refresher (Inheritance, `super()`, MRO, mixins, `__slots__`)
* Decorators (function, class decorators, `functools.wraps`)
* Context Managers (`with`, `__enter__`, `__exit__`, `contextlib`)
* Typing & Annotations (`typing`, `mypy`, `TypedDict`, `Protocol`)

**Practice ✅:**

* Build a `ResourceHandler` class using a context manager for file/database mocks.
* Implement a decorator for execution timing.
* Write a small project using `Protocol` for structural typing.

---

### **Day 2: Functional Python & Code Compactness**

**Topics:**

* Comprehensions (nested, dict, set, generator) ✅
* `lambda`, `map`, `filter`, `reduce` ✅
* `itertools` & `functools` (e.g., `partial`, `lru_cache`)

**Practice:**

* Write one-liner data transformations with `map/filter`.
* Use `itertools.groupby` for grouped summarization.
* Profile & compare loop vs comprehension performance using `timeit`.

---

### **Day 3: Robustness & File Operations**

**Topics:**

* Exception handling best practices (`try/except/else/finally`, custom exceptions)
* Logging (`logging.config`, rotating logs, log levels)
* File I/O (`with`, `os`, `pathlib`)
* Config management (`json`, `yaml`, `dotenv`)

**Practice:**

* Build a logging wrapper with custom formats.
* Simulate error handling in a data pipeline.
* Parse a config YAML & write to JSON.

---

### **Day 4: Data Handling (Pandas & NumPy Intensive)**

**Topics:**

* NumPy: `ndarray`, broadcasting, vectorized ops, `np.where`, `np.select`
* Pandas: `merge`, `groupby`, `pivot`, `apply`
* I/O: CSV, Parquet, Excel
* Handling missing data, datetimes, categoricals

**Practice:**

* Create a synthetic dataset (`np.random`).
* Run typical `ETL` steps: Clean → Transform → Aggregate.
* Write a small script converting CSV to Parquet.

---

### **Day 5: Visualization**

**Topics:**

* `matplotlib` basics (figure, axes, labels, grids)
* `seaborn` for statistical plots (boxplot, heatmap, KDE, pairplot)
* Styling plots (themes, palettes)
* Save/export charts

**Practice:**

* Visualize the dataset you created on Day 4.
* Write a function that saves 3 charts with consistent styling.

---

### **Day 6: Packaging & Environment Setup**

**Topics:**

* `virtualenv`, `pip`, `pip freeze`
* `requirements.txt` vs `Pipfile` vs `pyproject.toml`
* Building simple Python packages (`setup.py`, `__init__.py`)
* Using `argparse` or `click` for CLI scripts

**Practice:**

* Package a utility function (e.g., logger or data loader) into a local pip-installable package.
* Create a CLI tool to run your data pipeline.

---

### **Day 7: Capstone Mini-Project**

**Build a mini end-to-end script:**

**Problem Statement Example:**

> "Read messy CSV → Clean & transform (handle nulls, parse dates) → Save as Parquet → Visualize summary → Log each step."

**Deliverable:**

* Use OOP or functional design as you prefer.
* Log process, handle exceptions gracefully.
* Save both plots and data.
* Package the tool as a CLI command.

---

## **Bonus (Optional)**

If you finish early:

* Review `asyncio` basics for I/O-bound tasks.
* Explore `pydantic` for data validation (aligns well with LLM/NLP pipeline work).

---

### **Output by End of Week:**

* Solid grip over Python advanced features
* 1–2 reusable utilities or packages
* 1 mini end-to-end script (data + viz + logs + CLI)