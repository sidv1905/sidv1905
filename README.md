### Hi there 👋
```python
class Developer:

  def __init__(self):
    self.skills = []
    self.languages = []
    
  def getSkills(self):
    
    print("My Tech skills:")  
    print(*self.skills,sep=" | ")
    print("\n")
    
  def getLanguages(self):
    
    print("Programming Languages I am good at:")
    print(*self.languages,sep=" | ")
    
  def addSkills(self,Skills_Acquired):
      
      self.skills.extend(Skills_Acquired)
      
  def addLanguages(self,Programming_Languages):
      
      self.languages.extend(Programming_Languages)

Siddharth_Varangaonkar = Developer()

Siddharth_Varangaonkar.addSkills(["Web Development","Reactjs","Flask","Express","Machine Learning","REST Api","SQL","MongoDB"])

Siddharth_Varangaonkar.addLanguages(["Python","Javascript","C"])


Siddharth_Varangaonkar.getSkills()

Siddharth_Varangaonkar.getLanguages()
```
<!--
**sidv1905/sidv1905** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
