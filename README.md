### Getting started

- Set up Docker Desktop and WSL 2 on Windows: https://www.youtube.com/watch?v=2ezNqqaSjq8
- Set up JupyterLab and minIO using Docker
    - Prepare docker-compose.yml
    - Run docker-compose up -d in root directory
    - Access minIO web portal using http://localhost:9001
    - Create bucket using web portal: mybucket
    - Access JupyterLab using URL in logs (can find in Docker Desktop)

### Scripts

- Notebook: `big_data_file_formats.ipynb`