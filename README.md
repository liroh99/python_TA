## Summary of class 3

### Lesson 1

* Difference between markdown vs markup
* `README.md` renders automatically in the repository
* GitHub flavored markdown for formatting markdown files in GitHub

---

* **Notes on assignment 2:**
    * **Parmita**
        * Include links for the background of the biology
    * **Arad**
        * How to include tests to verify the validity of your code
        * Note - use approximation since computers don’t know how to represent floating point numbers
    * **David**
        * REPL - read evaluate print loop
        * `uv run python` to enter interpreter
        * `exit()` to exit

---

* **Python includes:**
    * The language itself
    * Python libraries which are needed to be imported
    * Third party libraries which need to be installed

---

* **How to define dependencies needed to run in your code:**
    * `requirements.txt`: To install dependencies listed in a standard `requirements.txt` file, use the command `uv pip install -r requirements.txt`.
    * `environment.yml`: To install dependencies listed in a Conda-style `environment.yml` file, use the command `uv pip install -c environment.yml`.
    * **Adding Dependencies:**
        * `uv init` create toml file
        * To add a single new dependency (and ensure all existing ones are resolved and installed) use `uv add [name of dependency]` (e.g., `uv add pandas`)
        * `uv lock` states specifically the hierarchy of what is downloaded and what is needed to run the program
        * `uv update` can update the libraries

---

### Lesson 2

* **Example of code- `words.py`**
    * Create a function that receives two words and return a numerical value indicating distance of the two words
* **Goes over:**
    * Functions
    * Methods for strings
    * For loop
    * Range function
    * Lists
    * Dictionaries
* **Another way to add to GitHub:**
    * `git status`
    * `git add .`
    * `git commit -m " "`
    * `git push`

---

### Lesson 3

* Using `pytest` to write tests (example in `words.py`)
* Implementation of a library that can execute the function instead of writing it ourselves
