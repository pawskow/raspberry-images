FROM pawskow/raspberrypi3:base@sha256:b10dec1fc70d726fa71aa943482b21d3e9b6bbe6ac61f043a9f98c425f2cd6d1

RUN apt-get update
RUN apt-get install -y build-essential tk-dev libncurses5-dev libncursesw5-dev libreadline6-dev libdb5.3-dev libgdbm-dev libsqlite3-dev libssl-dev libbz2-dev libexpat1-dev liblzma-dev zlib1g-dev libffi-dev

RUN apt-get install -y python3.9 python3-pip python3.9-venv

RUN pip install pipenv