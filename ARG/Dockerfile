ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG COURSE=Docker
ARG TRAINER=Neelareddy
ARG DURATION=150HRS
ENV Duration=${DURATION}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${DURATION}"
CMD ["sleep","120"]