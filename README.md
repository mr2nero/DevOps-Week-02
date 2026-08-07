# DevOps-Week-02

Week 2 project for the Davine Technologies DevOps internship, covering Git,
GitHub and collaborative version control workflows.

## Project Structure## Prerequisites

    .
    ├── docs/
    │   └── deployment.md      # Deployment notes and setup instructions
    ├── src/
    │   ├── app.py             # Application entry point
    │   ├── config.env         # Environment configuration
    │   └── deploy.sh          # Deployment script
    ├── requirements.txt       # Python dependencies
    └── README.md

## Configuration

Settings live in `src/config.env`:

| Variable | Description |
|---|---|
| `APP_NAME` | Application identifier |
| `APP_PORT` | Port the service listens on |
| `HEALTH_CHECK` | Enables the health check endpoint |
| `RETRIES` | Retry attempts on failure |
| `API_VERSION` | API version served |

## Running

```bash
pip install -r requirements.txt
python src/app.py
```

## Branching Strategy

`main` is the stable branch and always deployable. Work happens on feature
branches merged back via pull request.

| Branch | Purpose |
|---|---|
| `feature/deployment-script` | Health check configuration |
| `feature/documentation` | Deployment setup notes |
| `feature/api-endpoint` | API port and versioning (merged via PR #1) |

## Author

Tunde Ayangbenro — DevOps Internship, Davine Technologies# DevOps-Week-02
Week 2 DevOps internship project — Git and GitHub collaboration workflow
git add README.md



