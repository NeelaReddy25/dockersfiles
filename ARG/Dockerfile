ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG COURSE
ARG TRAINER
ARG DURATION
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${DURATION}"
CMD ["sleep","120"]