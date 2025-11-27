# Python JSON Handling – Tutorial & Examples

This project demonstrates how to work with **JSON (JavaScript Object Notation)** in Python.  
The notebook covers essential JSON operations including reading, writing, parsing, and converting JSON to Python objects and vice-versa.

---

## 📌 Features
- What is JSON and how it works  
- Converting Python dictionaries to JSON  
- Parsing JSON strings into Python objects  
- Reading JSON files  
- Writing JSON files  
- Formatting JSON using `indent`, `sort_keys`  
- Handling nested JSON structures  
- Error handling using `try/except` (if included)

---

## 📁 Project Structure
```
project/
│── 15_json.ipynb
│── data/
│    ├── example.json
│
│── README.md
```

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  
- Built-in `json` module (no external packages required)

---

## 📚 Topics Covered

### ✔ Importing JSON Module
```python
import json
```

### ✔ Converting Python → JSON
```python
data_json = json.dumps(python_dict)
```

### ✔ Pretty Printing JSON
```python
json.dumps(python_dict, indent=4)
```

### ✔ JSON → Python Dictionary
```python
parsed = json.loads(json_string)
```

### ✔ Reading JSON File
```python
with open("data.json", "r") as f:
    data = json.load(f)
```

### ✔ Writing JSON File
```python
with open("output.json", "w") as f:
    json.dump(python_dict, f, indent=4)
```

### ✔ Working With Nested JSON
- Access nested keys  
- Convert nested structures  
- Modify JSON fields  

---

## ▶️ How to Run
Run the notebook:

```
jupyter notebook 15_json.ipynb
```

Make sure any JSON files are placed in the correct folder (`data/`).

---

## 📊 Output
- JSON files created  
- Pretty printed JSON  
- Parsed Python dictionaries  
- Clean JSON formatting  

---

## 📜 Documentation
All explanations and examples are included inside the notebook.

---

## 🤝 Contributing
Pull requests are welcome.  
For major changes, open an issue first.

---

## 📝 License
This project is licensed under the MIT License.

---

## 👨‍💻 Author
Satyam Gajjar
