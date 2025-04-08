Authors
Malcolm Wengel

Problem Statement
Job seekers often struggle with efficiently tailoring their resumes and preparing for interviews when applying for jobs on LinkedIn. The process typically involves manually copying job descriptions, reviewing them against their resume, identifying required qualifications, and then editing the resume to better align with the role. This workflow is time-consuming, repetitive, and prone to human error, especially when applying to multiple positions.


Target Audience
The primary target audience is university students, recent graduates, and early-career professionals actively applying for internships or full-time positions. These users are likely to be browsing LinkedIn regularly and are seeking ways to make their applications stand out in competitive job markets. Secondary audiences include anyone engaged in frequent job searching who wants to streamline their application workflow and better prepare for interviews.

Description
JobTailor is a Chrome extension that helps job seekers optimize their application process on LinkedIn. When a user visits a job posting, the extension automatically extracts the job details and, when paired with the user's uploaded resume, provides AI-powered suggestions for resume improvements, identifies skill gaps, and generates relevant interview preparation questions. This extension makes job applications faster, more accurate, and less stressful.



Selling Points
Automates the extraction of LinkedIn job descriptions, reducing manual effort.

Provides AI-generated, tailored resume suggestions to improve alignment with job requirements.

Identifies missing skills and qualifications to help users address potential gaps.

Generates likely interview questions based on the specific job description.

Offers an intuitive, user-friendly interface with copy/download functionality for seamless application preparation.
User Stories
As a job seeker, I want to automatically extract job details from LinkedIn so that I do not have to manually copy and paste descriptions.

As a job seeker, I want to upload or paste my resume into the extension so that it can be used for comparison against job postings.

As a job seeker, I want to receive AI-generated suggestions for improving my resume so that my application better matches job requirements.

As a job seeker, I want to see a list of skills missing from my resume compared to the job description so that I can address gaps in my qualifications.

As a job seeker, I want to generate a set of likely interview questions based on the job description so that I can better prepare for interviews.

Notes
The extension will use content scripts to scrape job information directly from LinkedIn job pages.

OpenAI's API will be used to generate the resume suggestions, skills gap analysis, and interview questions.

Resume input will be kept simple as pasted text or optional upload, avoiding complex file parsing.

A clean and simple user interface is a priority to ensure ease of use for job seekers.

We will initially scope the extension to work specifically with LinkedIn, with potential to expand to other platforms (e.g., Indeed) in future versions.

We may explore adding features such as saving favorite jobs and exporting tailored resumes or application notes as stretch goals.

Care will be taken to ensure compliance with LinkedIn's terms of service, and all processing will happen client-side for job description extraction.



References & Inspiration
LinkedIn Job Search

OpenAI API Documentation: https://platform.openai.com/docs

Example Resume Tailoring Prompt: "Given this resume and this job description, suggest resume edits to better match the job."

Example Extensions: Grammarly for Chrome (for UI/UX inspiration), similar job helper extensions