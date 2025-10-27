

# Use a lightweight base image
FROM alpine

# Install a simple package (optional)
RUN apk add --no-cache curl

# Create a directory that will be used as a volume
RUN mkdir -p /mydata

# Declare a volume
VOLUME /mydata

# Set working directory
WORKDIR /mydata

# Default command
CMD ["sh"]

