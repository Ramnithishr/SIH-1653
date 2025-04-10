# Smart India Hackathon Workshop
# Date: 10/04/2025
## Register Number: 212224230219
## Name: R.Ramnithish
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Real-life Interview Simulation:

Ice-breaking questions: The simulation should start with general questions to help break the ice between the candidate and the interviewers. Techno-managerial questions: For more experienced candidates, the questions should delve into both technical knowledge and managerial skills, based on the level of the candidate. Question Relevancy:

Relevancy to the applicant's expertise: The tool should be able to evaluate the relevance of the questions to the candidate’s area of expertise. This means categorizing questions based on the field of the candidate’s expertise and ensuring they match the role or position they have applied for. Candidate Response Evaluation:

The tool should evaluate responses for relevancy and depth, ensuring that the candidate's answers are directly related to the questions posed. Score for relevancy: Both the question's relevancy to the role and the candidate's response relevancy should be quantified. Quantifiable Scoring System:

Overall subject knowledge score: Based on the relevancy and quality of the responses, the tool should calculate an overall score that reflects the candidate's suitability for the advertised post. Evaluation of experts: It should also evaluate the interviewer's performance in asking relevant questions based on the candidate’s area of expertise. Feedback Mechanism:

The tool should allow both the experts and candidates to receive feedback on the interview. This feedback would help assess the candidate's strengths and areas for improvement. Interactive Platform:

Web-based: The solution should be accessible on a web platform, enabling users to access it from anywhere, without the need for specialized software. User-friendly interface: The interface should allow both the candidate and the interviewer (expert) to interact seamlessly during the simulation. Customizable Question Bank:

The tool should allow experts to define and customize a question bank based on different roles or technical expertise areas. This would help in generating specific interview questions for various positions within the DRDO.


## Proposed Solution / Architecture Diagram
![422836576-1fed549d-0a9f-40d3-a28f-32cc9b58cfb0](https://github.com/user-attachments/assets/a96bca41-14e2-4d6b-b07d-991bd8d7cbea)



## Use Cases
![422837498-9d2fb37b-57c0-495b-97b2-ba2adb6ae1f8](https://github.com/user-attachments/assets/2961f828-87c5-4ff0-bfa3-0c83d623f0ad)


## Technology Stack
Frontend:

ReactJS for building an interactive, responsive user interface. Bootstrap or Material UI for UI components. Backend:

Node.js with Express for handling requests and serving the application. Python/Django could be an alternative if more advanced AI-based scoring and analysis is required. Database:

MySQL or MongoDB to store user profiles, question banks, candidate responses, and scores. AI/ML Algorithms (for Question/Answer Evaluation):

Natural Language Processing (NLP) algorithms to evaluate response quality, including accuracy, context relevance, and depth. Machine learning algorithms to analyze patterns in responses and assess both the candidate's and expert's performance. Video Integration:

WebRTC or other video APIs for live interviews. Cloud/Hosting:

AWS or Google Cloud for hosting the platform, ensuring scalability and security.

## Dependencies
Frontend:

Use ReactJS for building the user interface. Use React Router for navigation between pages. Use Axios for making API requests. Integrate Material-UI (or Bootstrap) for UI components. Use WebRTC for video functionality (if required). Backend:

Set up a Node.js server with Express. Implement JWT for authentication. Use Bcrypt for password hashing. Store data in MongoDB (or MySQL) with Mongoose (or Sequelize). Use dotenv for managing environment variables and Cors for cross-origin resource sharing.

