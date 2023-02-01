# Get the GCC preinstalled image from Docker Hub
FROM gcc:4.9

# Copy the current folder which contains C++ source code to the Docker image under /usr/src
COPY . /usr/src/cppConsoleInDocker

# Specify the working directory
WORKDIR /usr/src/cppConsoleInDocker

# Use GCC to compile the Test.cpp source file
RUN g++ -o CppConsoleInDocker CppConsoleInDocker.cpp

# Run the output program from the previous step
CMD ["./CppConsoleInDocker"]