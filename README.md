# Prompt-which-takes-your-Resume-as-input-and-parse-the-content-in-JSON-format


###
I will provide you with a resume, and you need to parse its content into JSON format. The JSON should include the following fields: Name, Contact Information, Education, Experience, Skills, and Certifications. Here is the format:


```json
{
  "Name": "Full Name",
  "Contact Information": {
    "Email": "email@example.com",
    "Phone": "123-456-7890",
    "LinkedIn": "linkedin.com/in/username"
  },
  "Education": [
    {
      "Degree": "Degree",
      "Institution": "Institution Name",
      "Year": "Year of Graduation"
    }
  ],
  "Experience": [
    {
      "Job Title": "Job Title",
      "Company": "Company Name",
      "Duration": "Start Date - End Date",
      "Responsibilities": "List of responsibilities"
    }
  ],
  "Skills": ["Skill1", "Skill2", "Skill3"],
  "Certifications": ["Certification1", "Certification2"]
}
```

Here is the resume:

Please parse the resume into the specified JSON format.

### demo resume
![image](https://github.com/user-attachments/assets/d4024236-cfc3-4fab-a437-91c5bebfa500)



## output:

```json
{
  "Name": "Alice",
  "Contact Information": {
    "Email": "alice@wonderland.com",
    "Phone": "+39 0325659874",
    "LinkedIn": "http://en.wikipedia.org/alice"
  },
  "Education": [
    {
      "Degree": "Ph.D. candidate in Computer Science",
      "Institution": "Wonderland",
      "Year": "since 1865"
    },
    {
      "Degree": "M.Sc. magna cum laude, Majoring in Computer Science",
      "Institution": "Wonderland",
      "Year": "1863-1865"
    },
    {
      "Degree": "B.Sc. magna cum laude, Majoring in Computer Science",
      "Institution": "Wonderland",
      "Year": "1861-1863"
    },
    {
      "Degree": "High school, Specializing in mathematics and physics",
      "Institution": "Wonderland",
      "Year": "1856-1861"
    }
  ],
  "Experience": [
    {
      "Job Title": "Alice in Wonderland-The Circra (1900’s) Silent Film",
      "Company": "Film",
      "Duration": "1900",
      "Responsibilities": "The first Alice on film was over a hundred years ago."
    },
    {
      "Job Title": "Alice in Wonderland 1933 version",
      "Company": "Film",
      "Duration": "1933",
      "Responsibilities": "This film stars Ethel enards and Charlotte Henry. It was a box office flop when it was released."
    },
    {
      "Job Title": "Disney Film",
      "Company": "Film",
      "Duration": "1951",
      "Responsibilities": "Walt Disney brings Lewis Carroll’s fantasy story to life in this well done animated classic. Even though many elements from the book were dropped, such as the duchess with the baby pig and mock turtle, this version is without a doubt the most famous Alice adaption made."
    }
  ],
  "Skills": ["Java", "polite", "outgoing", "good manners", "pursuer of rabbits"],
  "Certifications": []
}

```
