# Job Portal

The Job Portal is a MERN stack-based web application designed to streamline the job application process by providing a comprehensive platform for both applicants and recruiters. Users can register according to their role, with the platform offering distinct features for each. The application ensures security and ease of use by implementing persistent login sessions and protecting REST APIs with JWT token verification. Recruiters can effortlessly manage job postings, including creating, updating, and deleting listings, as well as handling applications by shortlisting, accepting, or rejecting candidates. On the other hand, applicants benefit from a user-friendly interface that allows them to browse and filter job listings, apply with personalized statements of purpose (SOPs), and manage their profiles, including uploading resumes and profile pictures. This web app serves as an all-in-one solution, catering to the needs of job seekers and recruiters alike, making the entire recruitment process more efficient and organized.


# Directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## Instructions for initializing web app:

- Install Node JS, MongoDB in the machine.
- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.


