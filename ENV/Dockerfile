FROM almalinux:8
RUN yum install nginx -y
ENV TRAINING="DEVOPS" \
    TRAINER="MANI" \
    DURATION="120HRS"
CMD ["nginx","-g","daemon off;"]