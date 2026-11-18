
# StudentHub - Student Information System

StudentHub is a cloud-native Student Information System developed using Python Flask, SQLite, HTML, and CSS.

The application allows users to manage student records through a simple web dashboard.

## Features

- Add new student records.
- View all registered students.
- Delete student records.
- Dashboard displaying the total number of registered students.
- Responsive web interface.

## Technologies Used

- Python 3.11
- Flask
- SQLite
- HTML5
- CSS3
- Docker
- Amazon ECR
- Amazon EKS
- GitHub Actions
- Argo CD

## Project Structure

```text
studenthub-app/
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── app.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
└── .gitignore
```

## Run Locally

1. Clone the repository:

```bash
git clone https://github.com/thatgoddessofgold-sketch/studenthub-app.git
cd studenthub-app
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the application:

```bash
python app.py
```

4. Open your browser:

```text
http://localhost:5000
```

## Run Using Docker

Build the Docker image:

```bash
docker build -t studenthub:v2 .
```

Run the container:

```bash
docker run -d --name studenthub-test -p 5000:5000 studenthub:v2
```

Open:

```text
http://localhost:5000
```

## Cloud Deployment

The project is being prepared for an end-to-end cloud-native deployment using:

- Amazon EC2
- Amazon Elastic Container Registry (ECR)
- Amazon Elastic Kubernetes Service (EKS)
- GitHub Actions for CI/CD
- Argo CD for GitOps-based deployment

## Author

Student Project - Cloud-Native Application Deployment

