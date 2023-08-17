# base image with Python
FROM python:3.11.4
 
# working directory for the app
WORKDIR app/

# copy the code from system
COPY . app.py

# install required library
RUN pip install Flask

# run the app
CMD ["python","app.py"]
