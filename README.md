# CICD
CI/CD project deploying a simple HTML page
# DevOps HTML Project 🚀
This project deploys a simple HTML page using:
- GitHub Actions (CI/CD pipeline)
- Docker & Docker Hub
- AWS EC2 (free tier)

## Workflow
1. Push code → GitHub.
2. GitHub Actions builds & pushes Docker image.
3. GitHub Actions SSHs into EC2 → pulls latest image → runs container.
4. Open `http://<ec2-public-ip>` to view page.
