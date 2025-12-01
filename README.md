# flask-blogging-app

## 📝 Project Overview

A blogging web application built with Flask and BulmaCSS. I am following the [Python Flask Tutorial](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH) by [Corey Schafer](https://www.youtube.com/@coreyms).

## ▶️ Usage

To run the application, you can either clone the GitHub repository to your local machine or pull the image from Docker. Thereafter, navigate to `localhost:5000/auth/login`.

### GitHub Repository

1.  Clone the repository from GitHub:

    ```bash
    git clone https://github.com/sal-siddiqui/flask-blog.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd flask-blog
    ```

3.  Create a virtual environment and activate it:

    ```bash
    # Create a virtual environment
    python -m venv .venv

    # Activate the virtual environment
    # For PowerShell (Windows):
    .venv\Scripts\Activate.ps1

    # For Linux or macOS:
    source .venv/bin/activate
    ```

4.  Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

5.  Run the application:

    ```bash
    python run.py
    ```

### Docker

1.  Pull the image to your local machine:

    ```bash
    docker image pull salsiddiqui02/flask-blog
    ```

2.  Run the container:

    ```bash
    docker container run --rm -d -p 5000:5000 --name flask_blog salsiddiqui02/flask-blog
    ```


3.  Stop the container:

    ```bash
    docker container stop flask_blog
    ```

4. Remove the image:

    ```bash
    docker image remove salsiddiqui02/flask-blog
    ```

## 🎥 Project Demo

To see the application in action, please click [here](https://youtu.be/z8yGFXgWYDo).
The video provides a guided tour of the project's features and functionality.
