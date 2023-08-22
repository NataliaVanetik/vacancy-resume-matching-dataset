# vacancy-resume-matching-dataset
Vacancy-resume matching dataset, with human ground truth rankings
File list:

5_vacancies.csv  List of 5 selected vacancies from data.world on which human evaluation was conducted

CV/ Directory containing 65 resumes in .docx format, anonymized

annotations-for-the-first-30-cvs.txt human rankings of 5 resumes for CV files 1-30 produced by two human annotators

annotation_instructions.docs  Instructions received from a senior HR specialist 


If you use any part of this data, please cite the following paper:

@Article{info14080468,
AUTHOR = {Vanetik, Natalia and Kogan, Genady},
TITLE = {Job Vacancy Ranking with Sentence Embeddings, Keywords, and Named Entities},
JOURNAL = {Information},
VOLUME = {14},
YEAR = {2023},
NUMBER = {8},
ARTICLE-NUMBER = {468},
URL = {https://www.mdpi.com/2078-2489/14/8/468},
ISSN = {2078-2489},
ABSTRACT = {Resume matching is the process of comparing a candidate&rsquo;s curriculum vitae (CV) or resume with a job description or a set of employment requirements. The objective of this procedure is to assess the degree to which a candidate&rsquo;s skills, qualifications, experience, and other relevant attributes align with the demands of the position. Some employment courses guide applicants in identifying the key requirements within a job description and tailoring their experience to highlight these aspects. Conversely, human resources (HR) specialists are trained to extract critical information from numerous submitted resumes to identify the most suitable candidate for their organization. An automated system is typically employed to compare the text of resumes with job vacancies, providing a score or ranking to indicate the level of similarity between the two. However, this process can become time-consuming when dealing with a large number of applicants and lengthy vacancy descriptions. In this paper, we present a dataset consisting of resumes of software developers extracted from a public Telegram channel dedicated to Israeli hi-tech job applications. Additionally, we propose a natural language processing (NLP)-based approach that leverages neural sentence representations, keywords, and named entities to achieve state-of-the-art performance in resume matching. We evaluate our approach using both human and automatic annotations and demonstrate its superiority over the leading resume&ndash;vacancy matching algorithm.},
DOI = {10.3390/info14080468}
}
