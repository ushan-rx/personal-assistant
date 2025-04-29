# personal-assistant

# How to run?

### STEPS:

Clone the repository

### Create a conda environment after opening the repository

```bash
conda create -n myagentapp python=3.12 -y
```

```bash
conda activate myagentapp
```

### install the requirements

```bash
pip install -r requirements.txt
```

Now,

```bash
# Start the Flask Server
python app.py
```

# AWS-CICD-Deployment-with-Github-Actions

 1. Login to AWS console.

 2. Create IAM user for deployment

 3. Create ECR repo to store/save docker image

 4. Create EC2 machine (Ubuntu)

 5. Open EC2 and Install docker in EC2 Machine:

 6. Configure EC2 as self-hosted runner:

 7. Setup github secrets:

-   AWS_ACCESS_KEY_ID
-   AWS_SECRET_ACCESS_KEY
-   AWS_DEFAULT_REGION
-   ECR_REPO
-   PINECONE_API_KEY
-   OPENAI_API_KEY
