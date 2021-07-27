#Running locally

python3 -m venv ./env
source ./env/bin/activate
python3 -m pip install --upgrade pip
pip3 install -r src/requirements.txt
cd src && python3 -m flask run

#Running via docker
docker build --tag publicbullet src/.
docker run --publish 5000:5000 python-docker
