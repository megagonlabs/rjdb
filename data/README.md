The dataset is divided into training, testing, and development (dev) sets to facilitate systematic model evaluation and fine-tuning. Each data entry is represented as a row in JSONL format, containing the following key-value pairs:

- **Job-Description**: A detailed textual description outlining the responsibilities, qualifications, and requirements of the job.
- **Resume-matched**: The resume that has been identified as a strong match for the given job description, based on predefined criteria.
- Resume-unmatched: A resume that does not meet the criteria for the job description or is a weaker match.
- Skills: A list of specific skills extracted from the job description and/or resumes, relevant to the role.
- Experiences: A summary or list of prior professional experiences mentioned in the matched or unmatched resumes.
- Experience-years: The cumulative years of experience associated with the listed roles or skills.
- Filtered-information: Preprocessed or condensed information derived from the job description and resumes, emphasizing the most relevant data points for analysis.
