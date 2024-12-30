ARG version
FROM almalinux:${version:-9}
ARG job="DevOps" \
    location="Singapore"
ENV location=$location
RUN echo "Job: $job, location: $location, version: $version"
CMD ["sleep","100"]
