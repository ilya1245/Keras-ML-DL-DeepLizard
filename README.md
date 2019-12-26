# Machine Learning / Deep Learning / Keras - Jupyter Notebooks
This repository contains the Jupyter notebooks and other resources used in the following deeplizard YouTube playlists:

- [Keras Machine Learning / Deep Learning Tutorial](https://www.youtube.com/playlist?list=PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL)
- [Machine Learning & Deep Learning Fundamentals](https://www.youtube.com/playlist?list=PLZbbT5o_s2xq7LwI2y8_QtvuXZedL6tQU)

In order to use it:
1. Build docker image imiflig/flask from my docker repo
2. Copy static flask_apps folder content to /home/ilya/docker_share/flask/app
3. docker run -v /home/ilya/docker_share/flask/app:/app/app -d --name=my_flask -p 5000:5000 -e PORT="5000" -e MODULE_NAME="app.hello_app" imiflig/flask
4. open http://134.249.124.221:5000/static/hello.html