#FROM almalinux:9
ARG version
FROM almalinux:${version:-9}
ARG course="Devops with AWS" \
    duration="120hrs"
ENV duration=$duration
RUN echo "Course: $course, duration: $duration, vesrion: $version"
CMD ["sleep","100"]
