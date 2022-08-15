FROM python:3.10.6
WORKDIR /app
EXPOSE 8080

COPY ../requirements.txt ./

RUN pip install -r requirements.txt

# Uses "robbyrussell" theme (original Oh My Zsh theme), with no plugins
RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.1.2/zsh-in-docker.sh)" -- \
    -t robbyrussell