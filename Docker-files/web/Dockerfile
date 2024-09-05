FROM nginx
LABEL "Project"="boma-docker"
LABEL "Author"="Bomasi"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf