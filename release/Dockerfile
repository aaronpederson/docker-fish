FROM aaronpederson/ubuntu

RUN ansible-galaxy install telusdigital.fish
COPY playbook.yml /etc/
RUN ansible-playbook /etc/playbook.yml
