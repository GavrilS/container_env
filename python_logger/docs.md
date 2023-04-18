# This is a test for running python in a container environment

# Commands for building and running the container:

1. docker build --tag python_logger_docker .
2. docker run --volume="C:\Users\Gari\Desktop\Projects\container_env_test\python_logger\logs\:/src/logger/" python_logger_docker
