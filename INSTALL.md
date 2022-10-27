1. In build: ```docker build -t project-dev -f Dockerfile .```
2. In project directory: ```docker run --gpus all -v $(pwd):/app/project/ --network=host -ti project-dev bash```
3. In container: ```curl https://sdk.cloud.google.com | bash``` & ```gcloud auth login```
4. Download data: ```python3 download_process.py --data_dir ./data```
