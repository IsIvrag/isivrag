```py
class IsIvrag:
    def __init__(self):
        self.pseudo = "IsIvrag"
        self.country = "France"
        self.skills = ["Python", "CSS", "HTML", "Batch"]

    def introduce(self):
        print(f"Salut, je suis {self.pseudo} de {self.country}!")
        print(f"Je maîtrise les langages suivants : {', '.join(self.skills)}")

if __name__ == "__main__":
    me = IsIvrag()
    me.introduce()
```
