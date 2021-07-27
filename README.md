# Running locally

`python3 -m venv ./env` <br>
`source ./env/bin/activate` <br>
`python3 -m pip install --upgrade pip` <br>
`pip3 install -r src/requirements.txt` <br>
`cd src && python3 -m flask run` <br>

# Running via docker
`docker build --tag publicbullet src/.`  <br>
`docker run --publish 5000:5000 python-docker`  <br>
