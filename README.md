```python
# Experiment: Personal Portfolio using Python
# Name: Khushboo Rai
# Course: MCA

def display_portfolio():
    print("=" * 50)
    print("           MY PERSONAL PORTFOLIO")
    print("=" * 50)

    print("\nPERSONAL INFORMATION")
    print("-" * 50)
    print("Name       : Khushboo Rai")
    print("Course     : MCA")
    print("Profession : Student")
    print("Location   : Bihar")

    print("\nABOUT ME")
    print("-" * 50)
    print("I am an MCA student interested in Python")
    print("programming, software development, and data analysis.")

    print("\nTECHNICAL SKILLS")
    print("-" * 50)
    skills = ["Python", "HTML", "CSS", "JavaScript"]

    for skill in skills:
        print("- " + skill)

    print("\nMY PROJECTS")
    print("-" * 50)
    projects = [
        "Personal Portfolio",
        "Campus Connect Placement Management Portal"
    ]

    for project in projects:
        print("- " + project)

    print("\nHOBBIES")
    print("-" * 50)
    print("- Playing Badminton")
    print("- Reading Books")

    print("\nCAREER GOAL")
    print("-" * 50)
    print("To improve my programming skills and become")
    print("a successful software professional.")

    print("\n" + "=" * 50)
    print("       THANK YOU FOR VISITING!")
    print("=" * 50)


if __name__ == "__main__":
    display_portfolio()
```
