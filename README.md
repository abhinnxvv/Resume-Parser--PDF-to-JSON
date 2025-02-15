# Resume Parser (PDF to JSON)

This repository contains a Python script (`main.py`) to parse resume content into JSON format, based on a provided resume file (`CV_AbhinavRajaRaizada.pdf` in this case).

## Files Included:

- **main.py**: Python script to parse resume content into JSON format.
- **resume.json**: JSON file containing parsed resume information.
- **CV_AbhinavRajaRaizada.pdf**: Actual resume file used for parsing.

## Usage

1. **Clone the Repository**:
   ```
   git clone <repository-url>
   cd <repository-name>
   ```

2. **Install Dependencies** (if any):
   ```
   pip install -r requirements.txt
   ```

3. **Run the Script**:
   ```
   python main.py
   ```

   This will parse the resume (`CV_AbhinavRajaRaizada.pdf`) and generate `resume.json` with the parsed information.

## Example Output (resume.json):

```json
{
  "name": "Abhinav Raja Raizada", 
  "education": [
    {
      "degree": "B.TECH in Computer Science and Engineering",
      "university": "SRM Institute of Science and Technology",
      "location": "Kattankulathur Chennai, Tamil Nadu",
      "dates": "2021 – 2025",
      "details": "CGPA: 9.24"
    },
    {
      "degree": "ISC",
      "university": "SKD Academy",
      "location": "Lucknow, Uttar Pradesh",
      "dates": "2019 – 2021",
      "details": "87%"
    },
    {
      "degree": "ICSE",
      "university": "La Martiniere College",
      "location": "Lucknow, Uttar Pradesh",
      "dates": "2007 – 2019"
    }
  ],
  "skills": {
    "languages": ["Python", "C/C++", "SQL"],
    "libraries_and_tools": ["NumPy", "Pandas", "Scikit-learn", "OpenCV", "NLTK", "TensorFlow", "PyTorch", "Keras", "PowerBI", "Tableau", "Excel", "Git", "Docker", "AWS", "Microsoft Azure", "Terraform", "Ansible", "Kubernetes"],
    "analytics": ["Supply Chain Operations", "BI product development", "Customer interaction", "Feature mapping", "Ad-hoc analysis"]
  },
  "experience": [
    {
      "title": "Research Intern",
      "company": "Samsung R&D Institute",
      "location": "Bangalore, India",
      "dates": "Sep, 2023 – Apr, 2024",
      "description": "Led successful implementation of Automatic Read Speech to Conversational Speech Recognition Project with Samsung Mentorship Team. Achieved 100% completion mark from mentors. Collaborated with a cross-functional team to integrate NLP models into existing frameworks."
    },
    {
      "title": "Summer Intern",
      "company": "Uttar Pradesh Metro Railway Corporation",
      "location": "Lucknow, Uttar Pradesh",
      "dates": "Jun, 2023 – Jul, 2023",
      "description": "Gained hands-on experience in IT department of UPMRC during Summer Internship, enhanced skills in PowerBI & SQL through a Data Science Project directing employee complaints. Developed and maintained business reports to support Supply Chain operations. Provided analytical support."
    },
    {
      "title": "Artificial Intelligence Researcher",
      "company": "Zetpeak",
      "location": "Chennai, India",
      "dates": "Jul, 2023 – Oct, 2023",
      "description": "Engaged in an immersive paid online internship, earning Rs. 5000 per month, and collaborating closely with experienced professionals. Focused on gaining practical skills and knowledge to upscale academic and professional growth in the AI/ML field. Conducted ad-hoc analysis to investigate system decisions and metrics impact."
    }
  ],
  "projects": [
    {
      "name": "Instance Segmentation",
      "description": "Developed an instance segmentation model trained on Sentinel-2 imagery. Accurately delineates agricultural field boundaries but struggles with crop type prediction.",
      "link": "[Link]"
    },
    {
      "name": "Disease Detective",
      "description": "Developed Disease Detective, a robust medical diagnosis chatbot using KNN and Decision Trees on 1100 data points, providing personalized disease identification, severity assessment, & precautionary advice.",
      "link": "[Try It!]"
    },
    {
      "name": "Automated Deploying AWS using Gitlab and Terraform",
      "description": "Automated EC2 instance creation in user-defined VPC & subnet using AWS, GitLab, Terraform. Included init, plan, user approval, apply, destroy stages with dynamic security group config, auto-scaling via CloudWatch.",
      "link": "[Try It!]"
    }
  ],
  "achievements": [
    "Corporate Domain Lead: Led the Corporate Domain, formerly Apple Developers Group (ADG), overseeing club operations and event management. Coordinated with multiple business teams for BI product development and maintenance.",
    "Finalists in Smart India Hackathon (Internal Round) and Philips Ideathon."
  ],
  "publications": [
    {
      "title": "Analyzing the Efficacy: A Critical Assessment of a Symptom Analysis and Initial Diagnosis Chatbot for Disease Detection",
      "conference": "Technological Innovation towards Digital Transformation Arena (ICSCSP2024 · VOLUME-I)",
      "publisher": "Lecture Notes in Networks and Systems (LNNS), Springer",
      "date": "June 2024",
      "link": "[Link]"
    }
  ]
}
