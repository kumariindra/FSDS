# FSDS Project All Commands are as follows:
# 1. For Environment Variable

1. Creating conda environment
```
conda create -p venv python==3.7 -y
```
OR
```
conda activate venv/
```
OR
```
conda activate venv

2. For requirements.txt
``` 
pip install -r requirements.txt
```

# 2. For git all commands are as follows:

1. To Add files to git
```
git add .
```
OR
```
git add <file_name>
```
2. To ignore file and folder from git we can write name of file/folder in 
```
.gitignore file
```
3. To check the git status
```
git status
```
4. To check all version maintained by git
```
git log
```
5. To create version/commit all changes by git
```
git commit -m "message"
```
6. To send version/changes to github
``` 
git push origin main
```
7. To check remote url
```
git remote -v
```
8. To check branch
```
git branch
```


3. To setup CI/CD pipeline in Heroku we need 3 information

1. HEROKU_EMAIL = kumariindra7@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = learning-classification


4. BUILD DOCKER IMAGE

```
docker --version
docker status
docker build -t <image_name>:<indra> .
```
> Note: Image name for docker must be lowercase

1. To list docker image
```
docker image
```

2. Run docker image
```
docker run -p 5000:5000 -e PORT=5000 <imageID>
```
3. To check running container in docker
```
docker ps
```
4. To stop docker container
```
docker stop <container_id>
```

For Configuration :

1. pip install ipykernel
