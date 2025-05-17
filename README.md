# SEcon-Last-Class-Quater-3
Python Practice OOPs
# Class 8 – Object‑Oriented Programming (OOP) in Python

Welcome to **Class 8**! 👋  This README summarises the key OOP concepts we covered and includes a sample Python class you can copy–paste into your own projects.

---

## 📚 Key Concepts

| # | Term              | Description                                                                         |
| - | ----------------- | ----------------------------------------------------------------------------------- |
| 1 | **Class**         | Blueprint for creating objects.                                                     |
| 2 | **Object**        | Instance of a class with its own data (**attributes**) and behaviour (**methods**). |
| 3 | **Inheritance**   | A class can reuse and extend code from a *parent* class.                            |
| 4 | **Polymorphism**  | Same method name can behave differently depending on the object that calls it.      |
| 5 | **Encapsulation** | Hide internal details & expose only what is necessary (public interface).           |

### Common OOP Terms

* **Attributes** – data members stored on each object
* **Methods** – functions defined inside a class
* **Constructor** – `__init__`, automatically runs to initialise an object

---

## 🍛 Example: `Biryani` Class

```python
class Biryani:
    """Simple OOP example showing constructor, attributes & a method."""

    def __init__(self, rice_type: str, spice_level: str):
        # instance attributes
        self.rice_type = rice_type
        self.spice_level = spice_level

    def serve_biryani(self) -> None:
        """Simulate serving biryani."""
        print("Serving hot and delicious biryani! 🌶️🍚")


# usage
my_biryani = Biryani("Basmati", "Medium")
my_biryani.serve_biryani()
# → Serving hot and delicious biryani! 🌶️🍚
```

---

## 📝 How to Use This Repo

1. **Clone** the repository.
2. Add your own classes or extend the `Biryani` class to practise inheritance and polymorphism.
3. Commit your changes with clear messages.
4. Push to GitHub and share the link with your instructor.

Happy coding! 🚀

