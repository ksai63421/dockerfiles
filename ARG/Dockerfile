ARG version 
FROM almalinux:${version:-8}
# variable before FROM will not work after FROM
RUN echo "version passed by user is: ${version}"
ARG COURSE 
ARG TRAINER
ENV COURSE=#{COURSE}
ENV TRAINER=${TARINER}
RUN echo "course: ${course}, trainer is: ${TRAINER}"
