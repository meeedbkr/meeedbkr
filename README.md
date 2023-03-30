<!-- made by mohammed EL-boukri , March 30, 2023 6:00AM -->
<!-- a class contains all my info -->
```python 
class AboutMe:
	# constuctor
    def __init__(self):
    	# my attributes
        self.name = "Mohammed El-boukri"
        #self.current_workplace = {
        #    "company": "Fiverr",
        #    "position": "Freelancer"
        #}
        self.education = {
            "degree": "Master of Science and Technology",
            "field": "Computer Science and Complex Systems Modeling",
            "year": "M1"
        }
        self.skills = {
            "C Language": 4,
            "Java": 4,
            "Python": 5,
            "Html5": 5,
            "Css3": 5,
            "Javascript": 5,
            "Php": 5,
            "Sql": 5,
            "Pl/Sql": 5,
        }
        self.interests = ["Open source", "Data science", "Machine learning", "Web development"]
        self.bio = f" { self.name } is a { self.education.degree }'s student in \
        Computer Science with a focus on modeling complex systems. He has a \
        Bachelor's degree in { self.education.fields } and experience in freelance \
        drawing NFT characters and fixing PHP website bugs. Mohammed is proficient \
        in { ' ,'.join(skills.keys()) } and has knowledge of machine learning \
        concepts. He is experienced in agile methodologies, Scrum, FDD, Merise,  \
        and UML. "

    # getters methods
    def get_current_workplace(self):
        return self.current_workplace

    def get_skills(self):
        return self.skills

    def get_interests(self):
        return self.interests

    def get_future_goal(self):
        return "To make meaningful contributions to the tech industry and open source community."

    def get_hobbies(self):
        return ["Coding", "Hiking", "Photography", "Traveling"]

    def get_favorite_python_libraries(self):
        return ["NumPy", "Pandas", "Matplotlib", "Scikit-learn", "Tkinter"]
```

## Contact Me
<!-- links so you can contact me -->
You can reach me at:

- [Email](mailto:mohammedelboukri00@gmail.com)
- [Linkedin](https://www.linkedin.com/in/mohammed.elboukri)
- [Kaggle](https://www.kaggle.com/mohammedelboukri)
- [hackerrank](https://www.hackerrank.com/mohammedelboukr1)