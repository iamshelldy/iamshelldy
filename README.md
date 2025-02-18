# Hi there 👋

```python
#!/usr/bin/python3
# -*- coding: utf-8 -*-

from .workers.it import SoftwareEngineer
from .greetings import greetings_map


class Me(SoftwareEngineer):
    def __init__(self) -> None:
        super().__init__(
            name="Denis Raetskii",
            languages_spoken=["ru", "uk", "en"],
            stack=["Python", "FastAPI", "Flask", "Django", "SQLAlchemy"],
            hobbies=[
                "learning new technologies", "building applications",
                "solving problems", "pastel painting", "hiking",
            ],
        )

    def greet(self, language_code: str = "en") -> None:
        print(greetings_map.get(language_code, greetings_map["en"]))


me = Me()
me.greet()
```

## About Me
* 👨‍💻 Software Engineer with a passion for building efficient and scalable applications.
* 🌐 Languages: Russian (native), Ukrainian (native), English (Elementary), Swedish (Beginner).
* 💻 Tech Stack:
  * Back-end: Python, FastAPI, Flask, Django, SQLAlchemy.
  * Front-end: Basics of HTML, CSS, and JavaScript.
  * Other Tools: Redis, Pandas, NumPy, Jinja2, SQLite, PostgreSQL, MongoDB.
* 🎯 Focus Areas: API design, data processing, software architecture, and web development.

## How to Reach Me
* ➤ Telegram: https://t.me/iamshelldy
* 📫 Email: iamshelldy@gmail.com
* 🔗 LinkedIn: https://linkedin.com/in/denis-raetskii-30564a2b3

