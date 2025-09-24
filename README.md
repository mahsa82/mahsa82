## Hi there 👋

```python
class Developer:
    def __init__(self):
        self.name = "Mahsa Alizade"
        self.university = "Azad University, Qom"
        self.role = "Backend Developer (Python, Django, DRF)"
        self.skills = [
            "HTML", "CSS", "JavaScript",
            "Python", "Django", "DRF", "Git"
        ]
        self.interests = [
            "Learning new skills",
            "Facing different challenges"
        ]

    def introduce(self):
        print(f"Hi, I'm {self.name} ")
        print(f"🎓 {self.university}")
        print(f"💻 Role: {self.role}")
        print("\n🚀 Skills:")
        for skill in self.skills:
            print(f" - {skill}")
        print("\n💡 Interests:")
        for interest in self.interests:
            print(f" - {interest}")


if __name__ == "__main__":
    me = Developer()
    me.introduce()
```
