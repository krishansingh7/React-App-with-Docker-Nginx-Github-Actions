# My React App

Built with React + Vite. Containerised with Docker. Auto-deployed via GitHub Actions.

## Local development

npm install
npm run dev        # http://localhost:5173

## Run with Docker locally

docker build -t react-app .
docker run -d --name react-docker-cicd -p 3000:80 react-app
# open http://localhost:3000

## GitHub Secrets required

| Secret             | Where to get it          |
|--------------------|--------------------------|
| DOCKER_USERNAME    | your Docker Hub username |
| DOCKER_PASSWORD    | your Docker Hub password |
