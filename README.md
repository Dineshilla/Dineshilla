Hi there 👋 \
🔭 I’m currently working on Something Really Cool \
🌱 I’m currently learning Large Language Models, Prompt Engineering 

``` python
from typing import List

__author__ = "Dinesh Kumar Illa"
__email__ = "idineshkumar12321@gmail.com"
__description__ = (
    " 🤖 Artificial Intelligence Enthusiastic | 🐬 Deep Learning | 🐍 Python "
)
__location__ = "🌎 Anytown, SomeWhere"
__github__ = "https://github.com/Dineshilla"


class Who:
    def __init__(self):
        self.author = __author__
        self.email = __email__
        self.description = __description__
        self.location = __location__
        self.github = __github__
        self.interests = [
            "📈 Data science",
            "🤖 Machine learning",
            "🎨 Creative coding"
        ]
        self.skills = [
            "🐍 Python",
            "☕ Java"
        ]
    def get_interests(self) -> str:
        return " | ".join(self.interests)
    def get_skills(self) -> str:
        return " | ".join(self.skills)
    def __repr__(self):
        return f"<h1>{self.author}</h1><p>{self.description}</p><p>{self.location}</p><p>Interests: {self.get_interests()}</p><p>Skills: {self.get_skills()}</p><a href='{self.github}' target='_blank'>Check out my code on GitHub</a>"

Who()
```

<h1>Dinesh Illa</h1><p>🐍 Python | 🤖 Artificial Intelligence Enthusiastic | 🐬 Deep Learning </p><p>🌎 Anytown, SomeWhere</p><p>Interests: 📈 Data science | 🤖 Machine learning | 🎨 Creative coding </p><p>Skills: 🐍 Python | ☕ Java | 🐘 PostgreSQL | 🍃 MongoDB</p><a href='https://github.com/Dineshilla' target='_blank'>Check out my code on GitHub</a>
