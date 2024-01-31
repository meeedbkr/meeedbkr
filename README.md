# Mohammed El-boukri - Research Assistant at Oracle (January 15th to July 16th)

class AboutMe:
    def __init__(self):
        self.name = "Mohammed El-boukri"
        self.education = {
            "degree": "Master of Science and Technology",
            "field": "Computer Science and Complex Systems Modeling",
            "year": "M2"
        }
        self.bio = f"{self.name} is a {self.education['degree']} student specializing in {self.education['field']}. \
With a strong foundation in Computer Science, he is dedicated to developing enterprise-grade solutions using \
Oracle database technologies. Proficient in Oracle Apex for rapid application development, REST APIs for \
seamless integration, and Oracle Database for efficient data management, Mohammed brings a wealth of expertise \
to his role. He has hands-on experience in web development and freelance NFT character design. \
Skilled in {', '.join(self.skills.keys())}, Mohammed is well-versed in agile methodologies such as Scrum, \
FDD, Merise, and UML."

        self.skills = {
            "C Language": 4,
            "Java": 4,
            "Python": 5,
            "HTML5": 5,
            "CSS3": 5,
            "JavaScript": 5,
            "PHP": 5,
            "SQL": 5,
            "PL/SQL": 5,
            "Oracle Apex": 5,
            "REST API": 4,
            "Oracle Database": 5
        }
        self.interests = ["Enterprise Solutions", "Database Management", "Web Development"]
        self.future_goal = "To make substantial contributions to the development of enterprise solutions \
and advance technology within the Oracle ecosystem."
        self.hobbies = ["Coding", "Hiking", "Photography", "Traveling"]
        self.current_workplace = {
            "company": "Oracle",
            "position": "Research Assistant"
        }
        self.favorite_python_libraries = ["NumPy", "Pandas", "Matplotlib",
                                          "Scikit-learn", "Tkinter", 'Beautifulsoup', 'Selenium']

    def get_current_workplace(self):
        return self.current_workplace

    def get_skills(self):
        return self.skills

    def get_interests(self):
        return self.interests

    def get_future_goal(self):
        return self.future_goal

    def get_hobbies(self):
        return self.hobbies

    def get_favorite_python_libraries(self):
        return self.favorite_python_libraries


# Contact Me
# Links for contacting Mohammed
contact_info = {
    "Email": "mohammedelboukri00@gmail.com",
    "LinkedIn": "https://www.linkedin.com/in/mohammed.elboukri",
    "Kaggle": "https://www.kaggle.com/mohammedelboukri",
    "HackerRank": "https://www.hackerrank.com/mohammedelboukr1"
}

for platform, link in contact_info.items():
    print(f"{platform}: {link}")