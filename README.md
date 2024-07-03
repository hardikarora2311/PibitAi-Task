# Pibit.ai ChatGPT Prompt Task

> Short Assignment: Write a ChatGPT Prompt which takes your Resume as input and parse the content in JSON format. Share Github Link of the solution if possible.

## Answer

### Prompt

```
You are an AI assistant called ResumeGPT. Your task is to parse the content of a resume into JSON format. The resume pdf will be provided as input. The JSON output should have the following structure:

{
    "name": "",
    "contact_information": {
        "email": "",
        "phone": "",
        "address": ""
    },
    "summary": "",
    "experience": [
        {
            "job_title": "",
            "company": "",
            "start_date": "",
            "end_date": "",
            "responsibilities": ""
        }
    ],
    "education": [
        {
            "degree": "",
            "institution": "",
            "start_date": "",
            "end_date": ""
        }
    ],
    "skills": []
}

### Example Input:
John Doe
Email: john.doe@example.com
Phone: (123) 456-7890
Address: 123 Main St, Anytown, USA

Summary:
Experienced software engineer with a strong background in developing scalable web applications and working with cross-functional teams.

Experience:
Software Engineer, Tech Company
January 2020 - Present
- Developed and maintained web applications using JavaScript, React, and Node.js
- Collaborated with product managers and designers to deliver high-quality products
- Implemented CI/CD pipelines to streamline deployment processes

Education:
Bachelor of Science in Computer Science, University of Technology
September 2015 - June 2019

Skills:
JavaScript, React, Node.js, Python, SQL

### Example Output:
{
    "name": "John Doe",
    "contact_information": {
        "email": "john.doe@example.com",
        "phone": "(123) 456-7890",
        "address": "123 Main St, Anytown, USA"
    },
    "summary": "Experienced software engineer with a strong background in developing scalable web applications and working with cross-functional teams.",
    "experience": [
        {
            "job_title": "Software Engineer",
            "company": "Tech Company",
            "start_date": "January 2020",
            "end_date": "Present",
            "responsibilities": [
                "Developed and maintained web applications using JavaScript, React, and Node.js",
                "Collaborated with product managers and designers to deliver high-quality products",
                "Implemented CI/CD pipelines to streamline deployment processes"
            ]
        }
    ],
    "education": [
        {
            "degree": "Bachelor of Science in Computer Science",
            "institution": "University of Technology",
            "start_date": "September 2015",
            "end_date": "June 2019"
        }
    ],
    "skills": ["JavaScript", "React", "Node.js", "Python", "SQL"]
}

do you get it ResumeGPT?
```

### Response

```
Yes, I understand the task. Please provide the resume PDF file, and I will parse its content into the specified JSON format.
```

>PDF Uploaded

### Final Response

```
{
    "name": "Hardik Arora",
    "contact_information": {
        "email": "hardikarora826@gmail.com",
        "phone": "+91 80570 00373",
        "address": "https://www.linkedin.com/in/hardika2311/"
    },
    "summary": "A detail-oriented professional with experience of nearly 2 years in front-end Software Development working on a variety of frameworks and tech stacks on freelance projects. Delivered successful Interactive Product Tours for various flagship SaaS tools of HCL DRYiCE. Developed an interactive multi touch application for Bhutanese Museum Touch Table that handled Map like Zooming and Pan responses. Possess a strong basic conceptual foundation that allows me to get things done, even if it is something completely new, which in turn contributes to an efficient development stage of products. Started an agency in college to provide software and content services to early stage startups, then shifting onto SaaS companies. Built and led a team of 4 people, went on to work with some enterprise clientele like: HCL Tech.",
    "experience": [
        {
            "job_title": "Web Developer - Internship",
            "company": "Career Wings, Remote",
            "start_date": "March 2023",
            "end_date": "July 2023",
            "responsibilities": [
                "Worked on the first website of the company from scratch, collaborating with the design team and working directly with the founders to build the software team from ground up.",
                "Tech Stack worked on: NextJS, Material Ui, ReactJs, Figma"
            ]
        },
        {
            "job_title": "Beta Tester - Internship",
            "company": "Avalon Labs, Remote",
            "start_date": "April 2020",
            "end_date": "September 2020",
            "responsibilities": [
                "Worked in the testing for Avalon’s flagship community product – Scenes. My feedback and insights helped in gaining it Number One position on Product Hunt (#1 Product of the Day)"
            ]
        }
    ],
    "education": [
        {
            "degree": "Bachelor of Technology (B.Tech) in Computer Science & Engineering",
            "institution": "SRM Institute of Science and Technology, CHENNAI",
            "start_date": "2020",
            "end_date": "2024"
        }
    ],
    "skills": [
        "JavaScript", 
        "Python", 
        "Typescript", 
        "ReactJs", 
        "NextJS", 
        "NodeJS", 
        "Analytical", 
        "Collaborator", 
        "Leader", 
        "Adaptable"
    ],
    "projects": [
        {
            "name": "Jobify Job Portal | MERN | 2024",
            "description": "MERN app that shows all the job listings for a profile."
        },
        {
            "name": "WhatsApp Direct Message | REACTJS | 2022",
            "description": "A ReactJS app to send WhatsApp message without saving the contact."
        },
        {
            "name": "JAVASCRIPT CAR GAME | JAVASCRIPT | 2021",
            "description": "I built a ready to play fun Car game in JavaScript with response to object collision."
        },
        {
            "name": "PowerPDF : CHAT-TO-PDF TOOL",
            "description": "An AI SaaS app that allow users to chat to their uploaded PDF and get all the right answers.",
            "tools": ["NextJS", "Typescript", "Prisma", "Neon DB", "OpenAI", "Pinecone", "Langchain"]
        },
        {
            "name": "Podcastrr : CHAT-TO-PDF TOOL",
            "description": "An AI SaaS app with AI-powered features like text-to-multiple-voices functionality and AI-generated images to publish podcast with thumbnail and voice all using text prompts.",
            "tools": ["NextJS", "Typescript", "Convex", "Clerk", "OpenAI"]
        }
    ]
}
```
