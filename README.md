# Introduction to deployment with GCP
## Dependencies

- Python 3.7+
- Pip
- Other listed in requirements.txt

## Running

- Clone the repo using

```bash
git clone https://github.com/mdhishaamakhtar/fastapi-sqlalchemy-postgres-template
```

- Create a Virtual Environment using

```bash
sudo pip install virtualenv
virtualenv env
```

- Activate the virtualenv

```bash
env\Scripts\activate # for windows
source env/bin/activate # for linux and mac
```

- Install dependencies

```bash
pip install -r requirements.txt
```

- Setting up environment variables

| Key     | Value |
| ----------- | ----------- |
| DATABASE_URL   | postgresql://user:password@host:port/db|

- To run the project

```bash
uvicorn main:app
```

### Running tests

- command to run pytest 
```
python3 -m pytest
```

#### Resources:

- Github Actions triggers: https://docs.github.com/en/actions/learn-github-actions/events-that-trigger-workflows
- Github App Engine Action: https://github.com/google-github-actions/deploy-appengine
- Github Workflow syntax: https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions
- Github action marketplace: https://github.com/marketplace?type=actions