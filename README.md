class Dharanisri:
    def __init__(self):
        self.name        = "Dharanisri D"
        self.location    = "Tamil Nadu, India"
        self.email       = "dharu9599@gmail.com"
        self.degree      = "MTech Computer Science And Engineering"
        self.college     = "Sri Ramakrishna Engineering College"
        self.gpa         = 8.75
        self.stack       = [
            "HTML", "CSS", "JavaScript", "Python", "C"
        ]
        self.currently_learning = [
            "React & Next.js",
            "AI & Machine Learning",
            "Cloud Technologies"
        ]
        self.languages   = {
            "Tamil": "Native",
            "English": "B2 - Upper Intermediate",
            "German": "A1 - Beginner"
        }
        self.fun_fact    = "I participated in Smart India Hackathon & YMI!"

    def motto(self):
        return "Passionate about building practical web applications, exploring AI technologies, and continuously improving through real-world projects."

me = Dharanisri()
print(me.motto())
