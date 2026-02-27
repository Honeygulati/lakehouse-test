FROM alpine:3.22

# Set working directory
WORKDIR /usr/src

# Copy script into container
COPY entrypoint.sh .

# Make script executable
RUN chmod +x entrypoint.sh

# Execute script when container starts
ENTRYPOINT ["/usr/src/entrypoint.sh"]
