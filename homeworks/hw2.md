### Genome Bioinformatics: Homework 2

**Course Code:** [Insert Course Code]

**Instructor:** [Aleksey Komissarov]

**Submission Date:** [Insert Due Date]

#### Objective:
The objective of this assignment is to automate the tasks from Genome Bioinformatics Homework 1 using different programming and scripting languages. You will learn to encapsulate repetitive bioinformatics tasks into scripts and pipelines, making your research more reproducible and efficient. By the end of this homework, you should be able to run the entire analysis with just a single parameter: the taxon name or taxon ID.

#### Instructions:
Complete the tasks outlined below, creating scripts and documentation for each step. You should ensure that each script is well-commented and includes instructions on how to run it. Submit your scripts, any supporting files, and a detailed report explaining your process and any challenges you encountered.

---

### Task 1: Automation with Python
**Objective:** Write a Python script to automate the downloading and basic analysis of genome data based on a taxon name or taxon ID.

#### Instructions:

1. **Script Creation:**
   - Create a Python script that takes a taxon name or taxon ID as input.
   - Use libraries like `requests` to download genome data from a specified database (e.g., NCBI, Ensembl).

2. **Data Processing:**
   - Process the downloaded data to perform a simplified version of the quality assessment and repeat masking tasks from Homework 1.

3. **Output:**
   - Ensure your script outputs a summary of the findings and saves any relevant data to files.

#### Deliverables:
- Your Python script, along with a README file explaining how to install any dependencies and run the script.

---

### Task 2: Automation with Bash
**Objective:** Create a Bash script to manage the workflow of downloading, assessing, and processing genomic data.

#### Instructions:

1. **Script Creation:**
   - Write a Bash script that accepts a taxon name or taxon ID as input.
   - Include commands to download genomic data from a public database.

2. **Pipeline Integration:**
   - Integrate tools like QUAST and RepeatMasker directly into your script, automating the analysis process.

3. **Efficiency and Logging:**
   - Ensure your script is efficient and logs its progress and any errors that occur.

#### Deliverables:
- The Bash script and a README file detailing its functionality and usage.

---

### Task 3: Workflow Management with Snakemake
**Objective:** Use Snakemake to create a reproducible workflow for the tasks in Homework 1.

#### Instructions:

1. **Snakemake Setup:**
   - Write a Snakemake file that defines rules for each step of the homework tasks, from downloading data to running analyses.

2. **Parameterization:**
   - Ensure that your Snakemake workflow can be started with just a taxon name or taxon ID as the input parameter.

3. **Documentation:**
   - Provide clear documentation on how to run your Snakemake workflow, including any necessary software or environment setup.

#### Deliverables:
- Your Snakemake file and any additional scripts it uses, along with a comprehensive README.

---

### Task 4*: Containerization with Docker (optional)
**Objective:** Package your analysis environment using Docker to ensure consistency and reproducibility.

#### Instructions:

1. **Dockerfile Creation:**
   - Create a Dockerfile that sets up an environment with all the necessary tools and libraries installed (Python, Bash, Snakemake, QUAST, RepeatMasker, etc.).

2. **Integration:**
   - Ensure that your Docker container can accept a taxon name or taxon ID as input and run the entire workflow from Homework 1.

3. **Documentation:**
   - Write detailed instructions on how to build and run your Docker container.

#### Deliverables:
- A Python script for Quast / BUSCO / RepeatModeler / RepeatMasker
- A Bash script for Quast / BUSCO / RepeatModeler / RepeatMasker
- A Snakemake program for Quast / BUSCO / RepeatModeler / RepeatMasker
- A Docker file for Quast / BUSCO / RepeatModeler / RepeatMasker

- Try to add downloading from DB too.

#### Pitfalls to Avoid:

- ?

---

### Submission Guidelines:
- Compile your scripts, Dockerfile, Snakemake file, and any additional notes or supporting files into a single, organized submission.
- Label each section clearly and provide thorough documentation and instructions.
- Check for clarity and accuracy before submitting. Your code should be well-commented and easy to understand.

**Good luck, and enjoy automating your journey through the world of genome bioinformatics!**
