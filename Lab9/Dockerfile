# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY code2.c .
# Compile the C program
RUN gcc -o code2 code2.c
# Set the command to run when the container starts
CMD ["./code2"]