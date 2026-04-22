# Media Catalogue (OOP in Python)

This project is a structured Object-Oriented Programming (OOP) implementation of a media catalogue system in Python. It demonstrates core OOP concepts such as inheritance, encapsulation, polymorphism, and custom exception handling through a practical and realistic use case.

## 🚀 Features

- Add and manage different types of media (Movies and TV Series)
- Inheritance-based design (TVSeries extends Movie)
- Input validation with meaningful error messages
- Custom exception handling using `MediaError`
- Dynamic categorization of media into Movies and TV Series
- Clean string representation using `__str__` methods
- Enumeration-based listing of media items

## 🧠 Concepts Covered

- Classes and Objects
- Inheritance (`super()` usage)
- Method overriding (`__str__`)
- Exception handling (`try-except`)
- Custom exceptions
- List comprehensions
- Type checking with `isinstance()`

## 🏗️ Project Structure

- `Movie` → Base class for all media items
- `TVSeries` → Child class extending Movie
- `MediaCatalogue` → Handles storage and organization
- `MediaError` → Custom exception for invalid media additions

## ⚙️ Example Usage

```python
catalogue = MediaCatalogue()

movie = Movie('Inception', 2010, 'Christopher Nolan', 148)
series = TVSeries('Breaking Bad', 2008, 'Vince Gilligan', 47, 5, 62)

catalogue.add(movie)
catalogue.add(series)

print(catalogue)
