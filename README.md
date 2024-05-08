<h2> Hi, I'm Sourabh Shrishrimal! </h2>
<p><em>Machine Learning Engineer<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Linkedin: sourabhshrishrimal](https://img.shields.io/badge/-sourabhshrishrimal-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/sourabhshrishrimal/)](https://www.linkedin.com/in/sourabhshrishrimal/)
[![GitHub crazycloud](https://img.shields.io/github/followers/crazycloud?label=follow&style=social)](https://github.com/crazycloud/)


#### Warning: somewhat-intelligent being ahead!

```python
completion = await client.chat.completions.create(
  model="Sourabh-v2",
  messages=[
    {"role": "system", "content": """I want you to act as Sourabh Shrishrimal, an ML Engineer with 14+ years of experience,
                                    which is just a nice way of saying you've been messing around with code for a really long time."""},
    {"role": "user", "content": "What makes you think you're a game-changer in ML engineering?"},
    {"role": "assistant", "content": """I'm not bragging or anything, but I've got a solid track record of not completely breaking AI projects.
                                        Currently, I'm tinkering with generative AI and LLM agents, because why not?"""}
  ],
  tools=[
    {
      "type": "function",
      "function": {
        "name": "develop_ml_models",
        "description": """Develop and deploy machine learning models at scale, because who doesn't love a good challenge?
            Utilizing expertise in:
          - Python (my go-to, Java's not my jam)
          - PyTorch 
          - Generative AI (hype or not, I'm all in)
""",
        "parameters": {
          "type": "object",
          "properties": {
            "project_requirements": {
              "type": "string",
              "description": "Project requirements"
            },
            "resources": {
              "type": "string",
              "description": "Resources available"
            },
            "constraints": {
              "type": "string",
              "description": "Constraints (e.g. timeline, budget, or 'make it happen ASAP')"
            }
          },
          "required": ["project_requirements", "resources", "constraints"],
        },
      },
    },
    {
      "type": "function",
      "function": {
        "name": "lead_ml_teams",
        "description": """Lead teams from a technical perspective, because someone has to keep the AI enthusiasts in line.
            Leveraging skills in:
          - Technical Leadership (because someone has to make the tough decisions)
          - Python Wizardry (because who doesn't love a good spell?)
          - PyTorch Mastery (because it's like having a superpower)""",
        "parameters": {
          "type": "object",
          "properties": {
            "team_members": {
              "type": "array",
              "items": {
                "type": "string"
              },
              "description": "List of team members ('the usual suspects')"
            }
          },
          "required": ["team_members"],
        },
      },
    },
  ]
)
```

<em>So, that's me in a nutshell (or in python). If you're looking for someone to geek out with over AI, or just want to say hi, I'm all ears (or in this case, all text). And if you've got an amazing opportunity or want to collaborate on a project, don't be shy - hit me up! I'm always down to chat about the next big thing in AI or just share some laughs.</b> :)</em>

---
