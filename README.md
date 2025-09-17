# Cloud Deployment - GCP

In this project the SpringBoot application , course-service is connected to MySQL database which is host 
in Google Cloud Platform

Here is the demo video of the project.
[Click here to watch video](https://drive.google.com/file/d/1hPSzMYLHk108c7n45agLWmKI8v0qYd9g/view?usp=sharing)

## Structure of this project

1.Frontend-app ( React + TypeScript)
2.Course_service (SpringBoot + MySQL)
3.Student_service (SpringBoot + MongoDB)
4.Media_service (Spring Boot + Local file storage, can be extended to S3/MinIO)


## Build

- Backend: run `mvn -q -e -DskipTests package` at repo root to build services.
- Frontend: run `npm install` then `npm run dev` inside `frontend-app`.

## LICENSE

This project is licensed under the [MIT License](LICENSE)