The dataset is divided into training, testing, and development (dev) sets to facilitate systematic model evaluation and fine-tuning. Each data entry is represented as a row in JSONL format, containing the following key-value pairs:

- **Job-Description**: the generated textual description outlining the responsibilities, qualifications, and requirements of the job.
- **Resume-matched**: The generated resume, which is a strong match for the given job description because both were created based on the same context of skills and experiences.
- **Resume-unmatched**: The resume that is created by selectively filtering information from the Resume-matched, resulting in it no longer meeting the criteria for the job description or becoming a weaker match.
- **Skills**: The list of specific skills sampled from a skill-occupation graph, used as the foundation for generating the resume and job description.
- **Experiences**: The list of experiences sampled from a skill-occupation graph, serving as the basis for generating the resume and job description.
- **Experience-years**: The duration of activity for each experience.
- **Filtered-information**: The list of filtered information from the Resume-matched, used to create the Resume-unmatched.
