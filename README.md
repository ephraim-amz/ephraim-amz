### Hi 👋🏾, Welcome to my GitHub profile

``` python
class AboutMe:
    name: str = 'Ephraïm'
    hobbies: list[str] = ['⚽', '🏀', '🏈', '📖', '👨🏾‍💻', '👨🏾‍🍳', '🏃🏾‍♂️', '🏋🏾‍♂️', '🎞️']
    presentation: str = 'Im a Data Science and AI student who likes to write code on free time'

    def current_project(self) -> str | None:
        return 'https://github.com/ephraim-amz/address-notebook-analysis'

    def current_learning(self) -> str | None:
        return 'Maven'

    def loc(self) -> str:
        return 'France'

    def programming_langages_skills(self) -> dict[str, list[str]]:
        return {
            "Python 🐍": [
                "Pandas", "Seaborn", "Polars", "Numpy", "Pandas", "Scikit-learn", "Tensorflow"],
            "Java ☕": ["Streams", "Multi-Threading", "Reflection", "JDBC", "Java EE"],
            "C#": [".NET Core CLI", "Blazor"],
            "Rust 🦀": ["Serde", "Cargo", "Crates"],
            "CLI": ["Bash", "Powershell", "Command Prompt"]
        }

    def web_programming_skills(self) -> dict[str, list[str]]:
        return {
            "Frontend": ["HTML", "CSS3", "JavaScript"],
            "Backend": ["Flask", "NodeJS"]
        }

    def databases_skills(self) -> dict[str, list[str]]:
        return {
            "SQL Databases": ["My SQL", "PostgreSQL", "Oracle 11g", "Microsoft SQL Server"],
            "NoSQL Databases": ["MongoDB", "Neo4j", "Redis"]
        }

    def devops_skills(self) -> dict[str, list[str]]:
        return {
            "Docker": ["Images", "Containers", "Volumes", "Dockerfile", "Docker CLI"],
            "CI/CD": ["Gitlab CI/CD Pipeline"],
            "Cloud": ["Microsoft Azure", "Digital Ocean"],
            "Deployment": ["Jenkins"]
        }

    def spreadsheet_tools(self) -> dict[str, list[str]]:
        return {
            "Excel": [
                "Dynamic Tables", "Graphs 📈", "VBA Macros",
                "Power Query", "What-If Scenarios", "V,H,X Lookup"
            ],
            "Other_tools": ["Google Sheets", "Numbers"]
        }

    def my_skills(self) -> dict[str, dict[str, list[str]]]:
        return {
            "Languages": self.programming_langages_skills(),
            "Web": self.web_programming_skills(),
            "Databases": self.databases_skills(),
            "DevOps": self.devops_skills(),
            "Spreadsheets": self.spreadsheet_tools(),
        }

    def learn_more_about_docker(self) -> None:
        pass

    def learn_hugging_face(self) -> None:
        pass

    def be_better_at_cooking(self) -> None:
        pass

    def goals(self) -> None:
        self.learn_more_about_docker()
        self.learn_hugging_face()
        self.be_better_at_cooking()

    def __str__(self) -> str:
        return f"I'm {self.name} - {self.presentation} - Localisation : {self.loc()} \nMy Skills: \n{self.my_skills()}"
```

📫 You can reach me via [LinkedIn](https://www.linkedin.com/in/ephraïm-amezian-249bb61a4 "My LinkedIn account")

## GitHub Stats

### Overall stats

![Ephraim's github stats](https://github-readme-stats.vercel.app/api?username=ephraim-amz&show_icons=true&layout=compact)

### Most used langages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ephraim-amz)](https://github.com/ephraim-amz/github-readme-stats)
