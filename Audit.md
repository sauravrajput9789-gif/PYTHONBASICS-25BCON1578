# README audit table

This is the core deliverable

| Claim made in README | True? | Evidence or correction made |
| :--- | :--- | :--- |
| Requires pip install -r requirements.txt | No | No requirements.txt exists; standard library only. Delete the line. |
| Repository contains 6 basic Python scripts (`dictionary.py`, `factorial.py.PY`, `fibonacci.py`, `list.py`, `mulitiplication.py`, `pattern.py`) | Yes | Verified directly against repository file list. All 6 files are present in the root directory. |
| Factorial script filename is `factorial.py` | No | File is named `factorial.py.PY` due to double extension. Corrected run command to `python factorial.py.PY`. |
| Multiplication script filename is spelled `multiplication.py` | No | File has a typo in repository: `mulitiplication.py`. Documented exact run command `python mulitiplication.py`. |
| Programs require Python 3.6+ to run | Yes | Scripts use basic Python 3 syntax and built-in functions compatible with Python 3.x. |
| Third-party external packages/dependencies are required | No | All programs rely purely on core Python syntax and standard built-ins; zero pip dependencies needed. |
| Programs can be run independently from CLI via `python <filename>` | Yes | Each file is a standalone script executable directly via `python <script_name>` or `python3 <script_name>`. |
| Repository owner and clone URL point to `sauravrajput9789-gif/PYTHONBASICS-25BCON1578` | Yes | Verified from GitHub repository header and breadcrumb navigation path. |

