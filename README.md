<h1>Hi there, I'm KJR020 👋</h1>

<!-- <p align="center">
  <a href="https://github.com/KJR020">
    <img src="https://github-readme-stats.vercel.app/api?username=KJR020&show_icons=true&theme=onedark" alt="KJR020's GitHub Stats">
  </a>
</p> -->

<p align="left">
  <a href="https://github.com/KJR020">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KJR020&theme=onedark" alt="Top Langs">
  </a>
</p>

## About Me
```
#!/usr/bin/python
# -*- coding: utf-8 -*-

class DeveloperProfile:
    def __init__(self, name: str, contact: str, pronouns: list):
        self.name = name
        self.contact = contact
        self.pronouns = " / ".join(pronouns)  
        self.details = {}

    def add_detail(self, key: str, value):
        if isinstance(value, list):
            value = ", ".join(value)
        self.details[key] = value

    def introduce(self):
        intro = f"Hello, I'm {self.name} ({self.pronouns}).\nYou can reach me at: {self.contact}.\n\nAbout Me:\n"
        details = "\n".join([f"{key}: {value}" for key, value in self.details.items()])
        return intro + details

my_profile = DeveloperProfile(
    name="KJR020",
    contact="johnjiro1114@gmail.com",
    pronouns=["He", "Him"]
)

my_profile.add_detail("Working On", "Developing IT-based production technologies, focusing on IoT and machine learning in manufacturing.")
my_profile.add_detail("Learning", "Advanced software development, machine learning, data engineering, GitHub for team development, and Test-Driven Development (TDD).")
my_profile.add_detail("Collaboration Interests", "Interested in software development and web service projects. Keen on contributing to projects that embrace modern development practices.")
my_profile.add_detail("Seeking Help With", "Learning from experienced IT engineers and software engineers about best practices in software engineering, including team collaboration using GitHub and TDD.")
my_profile.add_detail("Expertise", "Python, machine learning, IIoT system development, smart manufacturing processes.")
my_profile.add_detail("Fun Fact", "Exploring the intersection of technology and engineering, from Raspberry Pi experiments to developing manufacturing dashboards.")

print(my_profile.introduce())

```


## Connect with Me

<p align="left">
  <a href="https://qiita.com/Jirox">
    <img alt="Qiita" src="https://img.shields.io/badge/-Qiita-55C500?style=flat-square&logo=qiita&logoColor=white" />
  </a>
  <a href="https://note.com/jirox">
    <img alt="note" src="https://img.shields.io/badge/-note-41C9B4?style=flat-square&logo=note&logoColor=white" />
  </a>
</p>


## Technologies & Tools
1. **Programming Languages and Frameworks**
   - **Python**: Utilized for a broad range of applications including data analysis (with pandas), machine learning (using scikit-learn, tslearn, PyTorch), API development (with FastAPI), web application development (using Streamlit), and graphical user interface creation (with PyQt).
   - **JavaScript/Node.js**: Applied in web development and IoT projects, specifically using Node-RED for IoT integration, Vue.js for front-end development, and Plotly.js for interactive data visualizations.
   - **C#**: Used within the .NET ecosystem (particularly .NET 6) for developing desktop applications, services, and interfacing with IoT devices.

2. **Networking and Analysis Tools**
   - **Wireshark**: A network protocol analyzer used for troubleshooting, analysis, and education in networking.

3. **Industrial Automation**
   - **CODESYS**: A development environment for programming controller applications according to the international industrial standard IEC 61131-3, used in automation and control system projects.

4. **Data Visualization and Business Intelligence**
   - **Power BI**: A Microsoft product used for business analytics, enabling data modeling, analysis, and report generation.

5. **Database**
   - **SQL**: Employed for querying and managing databases, used extensively for data extraction, manipulation, and reporting tasks.



<!-- ## Recent Blog Posts -->


