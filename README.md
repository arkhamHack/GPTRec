# GPT4Rec (backend repository for MovieBox)

Using LLMs to enhance Recommendation Systems. An application to get the movies of your desire.

## How to set up the server

You can manually build the dependencies on the server, or just use docker to build the environment using this command:

```bash
# Go to server/ folder 
cd server

# Build the image
docker build -t gpt4rec-server:v1 -f Dockerfile.local .
```

This should build the image, and now run the server using this command:

```bash
docker run --gpus all -d -p 8000:8000 gpt4rec-server:v1
```

## Some screenshots of the website:
![image](https://github.com/arkhamHack/GPTRec/assets/72064090/18cc4189-ba5a-4aec-9423-616fbb81309e)

![image](https://github.com/arkhamHack/GPTRec/assets/72064090/02c3f1b5-47de-4592-b415-7ac0b6cded2a)

![image](https://github.com/arkhamHack/GPTRec/assets/72064090/eb3dfd81-744d-4ed5-976d-e5fe7e458918)

