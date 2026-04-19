# Prathamesh-resume-
def generate_resume():
    name = "Prathamesh Vivekanand Kamble"
    phone = "+91-8459367274"
    email = "pvkamble99@gmail.com"
   

    summary = "Motivated individual with strong problem-solving skills and interest in technology."

    skills = ["Python", "HTML", "CSS", "JavaScript", "Problem Solving"]

    education = [
        {"deploma": "Computer Science & Engineering", "college": "BSIET KOLHAPUR", "year": "2021", "Percntage": "67.83%"}
    ]

    experience = [
        {
            "role": "Intern",
            "company": "Fox&clude tecnology kolhapur Company",
            "duration": "Jan 2021 - Jun 2025",
            "details": "Worked on web development and automation scripts."
        }
    ]

    projects = [
        "Portfolio Website using HTML/CSS",
        "Python Automation Script",
        "Simple Chat Application"
    ]

    print("="*40)
    print(name.upper())
    print("="*40)
    print(f"Phone: {phone}")
    print(f"Email: {email}")
    
    
    print("\nSUMMARY")
    print(summary)
    
    print("\nSKILLS")
    for skill in skills:
        print(f"- {skill}")
    
    print("\nEDUCATION")
    for edu in education:
        print(f"{edu['deploma']} - {edu['college']} ({edu['year']})")
    
    print("\nEXPERIENCE")
    for exp in experience:
        print(f"{exp['role']} at {exp['company']} ({exp['duration']})")
        print(f"  - {exp['details']}")
    
    print("\nPROJECTS")
    for project in projects:
        print(f"- {project}")

    print("\n" + "="*40)


# Run the function
generate_resume()
