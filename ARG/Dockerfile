ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Neelareddy
ENV DURATION=120HRS
#ARG DURATION=150HRS
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${DURATION}"
CMD ["sleep","120"]