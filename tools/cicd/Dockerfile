# This Docker image is a modified version of the python image including
# a few necessary packages for building and publishing this library.
ARG PYTHON_VERSION

FROM python:${PYTHON_VERSION}

RUN python -m pip install --upgrade pip

RUN python -m pip install build==1.3.0 twine==6.2.0

ENTRYPOINT ["python3"]